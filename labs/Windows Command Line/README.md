# Windows Command Line
## 💻 Sample Commands / Snippets
These are **generic, legal commands** for exploring Windows systems, monitoring endpoints, and practicing SOC tasks.  
*(No lab-specific outputs or flags are included to maintain TryHackMe learning integrity.)*

```powershell
# List all files and directories in the current folder
dir

# Change directory
cd C:\Users\Public

# Display current directory path
pwd

# Check running processes
Get-Process

# Check system information
systeminfo

# List local users
Get-LocalUser

# View group membership
Get-LocalGroupMember -Group "Administrators"

# Network configuration
ipconfig /all

# List environment variables
Get-ChildItem Env:

# Basic Linux shell commands (for hybrid environments)
ls
cd /home
pwd
```

## 📝 Overview
The **Windows Command Line** room introduces learners to using the **Windows Command Prompt** and **PowerShell** for system management and security tasks.  
Understanding these tools is crucial for **SOC analysts and blue team professionals** to monitor endpoints, gather system information, and automate security tasks.  
The room also covers basic **Linux shell commands** for comparison, which is useful when working in hybrid environments.

---

## 🎯 Learning Objectives
- Understand the purpose and structure of the **Windows Command Prompt** and **PowerShell**.  
- Learn essential **Windows commands** for system management and security monitoring.  
- Explore **PowerShell scripting basics** for automating tasks.  
- Understand how **Windows shell commands** differ from Linux shells.  
- Gain foundational knowledge for **SOC operations and endpoint monitoring**.

---

## 🛠 Tools Used
- Windows Command Prompt (cmd.exe)  
- PowerShell  
- Linux shell environment (bash)  
- Task Manager and system utilities

---

## 🔎 Key Concepts Learned
- **Windows Commands:** File management, network queries, and system inspection  
- **PowerShell Basics:** Cmdlets, scripts, and object-oriented output  
- **Linux Shell Comparison:** Understanding differences and similarities with Windows commands  
- **SOC Relevance:** Using command line tools to monitor, troubleshoot, and secure endpoints

---

## 🧠 Methodology / Approach
1. Practiced **basic Windows commands** for file, network, and system management.  
2. Explored **PowerShell cmdlets** for querying system configuration and user activity.  
3. Compared Windows commands with **Linux shell commands** to understand environment differences.  
4. Applied commands to **simulate monitoring and security tasks** as a SOC analyst.  
5. Reflected on how command line skills enhance **endpoint visibility and incident response**.

---

## ✅ Key Takeaways
- Mastery of **Windows command line and PowerShell** is essential for SOC and blue team roles.  
- Command line tools allow for **rapid system inspection, monitoring, and troubleshooting**.  
- PowerShell scripting provides automation capabilities for repetitive security tasks.  
- Understanding both Windows and Linux shells increases versatility in monitoring and defense.

---

## 💡 Notes
- This room is highly relevant for **SOC analysts and blue team professionals**.  
- Recommended to combine with **Windows Fundamentals** and **Active Directory Basics** for full Windows security and monitoring context.
