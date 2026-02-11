# Linux Shells

## 💻 Sample Commands / Snippets
These are **generic, legal Linux shell commands** for system navigation, file management, and basic security tasks.  
*(No lab-specific outputs or flags included to maintain TryHackMe learning integrity.)*

```bash
# List files and directories
ls -la

# Change directory
cd /home/user

# Print current working directory
pwd

# View file contents
cat filename.txt

# Search for a string in files
grep "search_term" filename.txt

# Copy, move, and remove files
cp source.txt destination.txt
mv oldname.txt newname.txt
rm file.txt

# Check running processes
ps aux

# Display network interfaces and IPs
ifconfig

# Show disk usage
df -h
```
## 📝 Overview
The **Linux Shells** room introduces learners to using **Linux command-line interfaces (shells)**, including **Bash**, for system administration and security tasks.  
Understanding Linux shells is crucial for **SOC analysts and blue team professionals**, especially when monitoring Linux endpoints, analyzing logs, and performing automation or scripting tasks.  
This room provides a foundation for navigating the Linux file system, managing processes, and performing basic security-relevant operations from the command line.

---

## 🎯 Learning Objectives
- Understand the purpose and structure of **Linux shells**.  
- Learn essential **Linux commands** for file management, system inspection, and process monitoring.  
- Explore **Bash scripting basics** for automating tasks.  
- Understand Linux **permissions, ownership, and file system hierarchy**.  
- Gain foundational knowledge for **SOC monitoring and incident response** on Linux endpoints.  
- Compare **Linux shell behavior** to Windows command-line environments for hybrid monitoring scenarios.

---

## 🛠 Tools Used
- Linux virtual machine (Ubuntu, Debian, or similar)  
- Bash shell  
- Terminal utilities (`ls`, `cat`, `grep`, `ps`, `df`, `ifconfig`)  
- Basic shell scripting  

---

## 🔎 Key Concepts Learned
- **Linux Commands:** File navigation, process monitoring, and system inspection  
- **Shell Scripting:** Automating repetitive tasks and gathering system information  
- **File System & Permissions:** Ownership, read/write/execute permissions, and directory hierarchy  
- **Process & Network Monitoring:** Viewing active processes and network interfaces  
- **SOC Relevance:** Monitoring Linux endpoints and identifying anomalies or suspicious activity  

---

## 🧠 Methodology / Approach
1. Practiced **basic Linux commands** for navigating directories, managing files, and inspecting system state.  
2. Explored **process and network monitoring commands** to observe active system activity.  
3. Investigated **permissions and ownership** to understand access control in Linux.  
4. Practiced **Bash scripting basics** to automate common tasks and queries.  
5. Reflected on how Linux shell skills support **SOC monitoring, incident response, and threat detection**.  

---

## ✅ Key Takeaways
- Mastery of **Linux shells and command-line tools** is essential for SOC and blue team roles.  
- Shell commands allow for **rapid system inspection, monitoring, and troubleshooting**.  
- **Bash scripting** enhances automation and efficiency for repetitive security tasks.  
- Understanding Linux **permissions, ownership, and file system structure** is critical for endpoint security analysis.  

---

## 💡 Notes
- This room is highly relevant for **SOC analysts and blue team professionals**.  
- Recommended to combine with **Windows Command Line** and **Windows Fundamentals** rooms for full cross-platform endpoint security knowledge.

# Check permissions
ls -l
```


