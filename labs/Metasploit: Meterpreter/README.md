# Metasploit: Meterpreter

---

## 💻 Sample Commands / Snippets
These are **generic, legal Meterpreter commands** for use in controlled lab environments only.  
*(No real-world targets, credentials, or sensitive data included.)*

```bash
# List active sessions
sessions -l

# Interact with a Meterpreter session
sessions -i 1

# Display system information
sysinfo

# Get current user
getuid

# Show network configuration
ipconfig

# List running processes
ps

# Migrate to another process (lab only)
migrate <process_id>

# Capture a screenshot (lab only)
screenshot

# Background the session
background

# Exit Meterpreter
exit
```
---

## 📝 Overview
The **Metasploit: Meterpreter** room introduces learners to **Meterpreter**, an advanced post-exploitation payload within the Metasploit Framework.  
Learners explore how attackers interact with compromised systems after exploitation in a safe lab environment.  
Understanding post-exploitation techniques is critical for **SOC analysts and blue team professionals** to detect lateral movement, privilege escalation, and persistence mechanisms.

---

## 🎯 Learning Objectives
- Understand what **Meterpreter** is and how it functions.  
- Learn common post-exploitation commands and capabilities.  
- Explore system enumeration techniques in a lab setting.  
- Understand how post-exploitation activity appears in logs.  
- Gain foundational knowledge for detecting advanced attacker behavior.

---

## 🛠 Tools Used
- Metasploit Framework (`msfconsole`)  
- Meterpreter payload  
- Virtual lab machines (Windows/Linux)  
- System and network monitoring tools  

---

## 🔎 Key Concepts Learned
- **Post-Exploitation:** Actions performed after gaining system access.  
- **Privilege Escalation Awareness:** Understanding attacker attempts to gain higher permissions.  
- **Persistence Techniques (Conceptual):** Maintaining access to compromised systems.  
- **Process Interaction:** Viewing and migrating between processes.  
- **SOC Relevance:** Detecting abnormal system behavior and unauthorized access.

---

## 🧠 Methodology / Approach
1. Established a Meterpreter session in a controlled lab.  
2. Practiced basic system enumeration commands.  
3. Observed process and network information from the compromised host.  
4. Reflected on how these activities would trigger alerts in a monitored environment.  
5. Connected post-exploitation techniques to SOC detection strategies.

---

## ✅ Key Takeaways
- **Meterpreter** demonstrates how attackers operate after initial compromise.  
- Post-exploitation behavior often generates detectable indicators.  
- Understanding attacker workflows improves **SOC threat detection**.  
- Monitoring processes, privilege changes, and network activity is critical for defense.

---

## 💡 Notes
- This room is highly relevant for **SOC analysts, blue team professionals, and security engineers**.  
- Recommended to complete alongside **Metasploit: Introduction and Exploitation** for full attack lifecycle understanding.  
- Focus should always remain on defensive learning and detection capabilities.


