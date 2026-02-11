# Moniker Link (CVE-2024-21413)

## 💻 Sample Commands / Snippets
These are **generic, legal commands** for exploring web application vulnerabilities in a lab environment.  
*(No lab-specific payloads, targets, or credentials included to maintain TryHackMe learning integrity.)*

```bash
# Test HTTP connectivity
curl http://example.com

# View HTTP headers
curl -I http://example.com

# Make a GET request
curl -X GET http://example.com/path

# Make a POST request with test parameters
curl -X POST -d "username=test&password=test" http://example.com/path

# Basic URL encoding/decoding (Linux)
python3 -c "import urllib.parse; print(urllib.parse.quote('test value'))"

# Check for open ports (generic)
nmap -p 80,443 example.com
```
---

## 📝 Overview
The **Moniker Link (CVE-2024-21413)** room demonstrates a **real-world vulnerability** in Microsoft Outlook that allows bypassing **Protected View** to leak user credentials.  
Learners explore **exploitation concepts**, test the vulnerability in a safe lab environment, and understand its implications.  
This room is essential for **SOC analysts and blue team professionals** to understand attack vectors, detect exploitation attempts, and monitor for suspicious activity.

---

## 🎯 Learning Objectives
- Understand the CVE-2024-21413 vulnerability and its impact.  
- Learn how **Moniker links** can bypass Protected View in Outlook.  
- Explore safe exploitation techniques in a lab environment.  
- Understand the **SOC relevance** of monitoring such attacks.  
- Gain foundational knowledge for incident response and threat detection.  

---

## 🛠 Tools Used
- Windows lab environment (Outlook client)  
- PowerShell (for testing and analysis)  
- Safe lab-based exploitation scripts  
- Event monitoring tools for SOC detection  

---

## 🔎 Key Concepts Learned
- **Moniker Links:** How Outlook processes certain link types.  
- **Protected View Bypass:** Understanding why this security layer can be bypassed.  
- **Credential Theft:** Mechanisms attackers may use to exfiltrate credentials.
