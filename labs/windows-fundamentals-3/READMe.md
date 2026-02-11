# Windows Fundamentals 3

## 💻 Sample Commands / Snippets
These are **generic, legal commands** for exploring Windows security and system monitoring.  
*(No lab-specific outputs or flags included to maintain TryHackMe learning integrity.)*

```powershell
# Check Windows Update status
Get-WindowsUpdateLog

# View BitLocker status
Get-BitLockerVolume

# Check Windows Security settings
Get-MpPreference

# List installed Windows updates
Get-HotFix

# Monitor system performance
Get-Process | Sort-Object CPU -Descending
```

## 📝 Overview
**Windows Fundamentals 3** focuses on **built-in security tools and endpoint protection features** in Windows.  
Learners gain hands-on experience with **Windows Updates, Windows Security, BitLocker**, and other tools that help secure devices against threats.  
This room prepares learners for real-world defensive tasks, a core responsibility for **SOC analysts and blue team professionals**.

---

## 🎯 Learning Objectives
- Understand and configure **Windows Security** features.  
- Explore **BitLocker** for full-disk encryption.  
- Learn about **Windows Updates** and their role in system hardening.  
- Gain insight into **endpoint protection workflows** used in SOC environments.  
- Understand the importance of keeping Windows systems **patched and secured**.

---

## 🛠 Tools Used
- Windows Security (Windows Defender)  
- BitLocker drive encryption  
- Windows Update settings  
- Security & Maintenance dashboard  

---

## 🔎 Key Concepts Learned
- **Windows Defender:** Built-in antivirus and threat protection.  
- **BitLocker:** Full-disk encryption to protect sensitive data.  
- **Update Management:** Keeping systems patched to prevent exploits.  
- **Endpoint Protection Workflow:** How SOC teams use these tools to detect and mitigate threats.  
- **Security Best Practices:** Configuring and monitoring security features effectively.

---

## 🧠 Methodology / Approach
1. Explored Windows Security settings to understand available protection layers.  
2. Practiced enabling and configuring **BitLocker** on test drives.  
3. Reviewed Windows Update options and their impact on security.  
4. Learned how built-in tools integrate into endpoint monitoring and SOC workflows.  
5. Reflected on how these settings and tools strengthen overall Windows security posture.

---

## ✅ Key Takeaways
- Built-in Windows security tools provide a strong foundation for endpoint defense.  
- Regular updates and proper configuration are critical for reducing attack surfaces.  
- Understanding these tools is essential for SOC analysts managing Windows environments.  
- Knowledge from this room directly applies to real-world defensive operations.

---

## 💡 Notes
- This is **Part 3 of the Windows Fundamentals series**, focused on security hardening and endpoint protection.  
- Completing all three Windows Fundamentals rooms provides a complete foundation for **Windows-based SOC analysis**.
