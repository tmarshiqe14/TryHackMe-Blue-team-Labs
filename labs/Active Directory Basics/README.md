# 🏢 Active Directory Basics

## 💻 Sample Commands / Snippets
These are **generic, legal PowerShell commands** used to explore Active Directory (AD) objects.  
*(No lab-specific outputs or flags are included to maintain TryHackMe learning integrity.)*

```powershell
# List all users in a domain
Get-ADUser -Filter *

# List all groups in a domain
Get-ADGroup -Filter *

# View members of a specific group
Get-ADGroupMember -Identity "Domain Admins"

# Query organizational units (OUs)
Get-ADOrganizationalUnit -Filter *

# Check detailed properties of a user
Get-ADUser -Identity "username" -Properties *
# Active Directory Basics

```


## 📝 Overview
The **Active Directory (AD) Basics** room introduces the core concepts and functionality of **Microsoft Active Directory**.  
Learners explore **users, groups, organizational units (OUs), domains, and permissions**, gaining foundational knowledge required for **SOC analysts and blue team professionals**.  
Understanding AD is essential for monitoring, incident response, and securing enterprise networks.

---

## 🎯 Learning Objectives
- Understand the purpose and structure of **Active Directory**.  
- Learn about **domains, organizational units (OUs), users, and groups**.  
- Explore **group policies** and their impact on security.  
- Understand how AD integrates with **Windows environments**.  
- Gain foundational knowledge for monitoring **user and group activity** in SOC operations.

---

## 🛠 Tools Used
- Active Directory Users and Computers (ADUC)  
- PowerShell (for querying AD objects)  
- Group Policy Management Console (GPMC)  
- Windows Server environment (lab instance)

---

## 🔎 Key Concepts Learned
- **AD Structure:** Domains, OUs, trees, and forests.  
- **Users & Groups:** How identities are managed and grouped for access control.  
- **Permissions & Access Control:** How security is enforced through AD objects.  
- **Group Policies:** Applying policies to control system behavior and security settings.  
- **Monitoring & SOC Relevance:** Understanding AD events that SOC analysts monitor for anomalies.

---

## 🧠 Methodology / Approach
1. Explored AD hierarchy, including domains and organizational units.  
2. Created and managed **users and groups** to understand permissions.  
3. Investigated **group policies** and their security implications.  
4. Practiced basic PowerShell commands for querying AD objects.  
5. Reflected on how AD monitoring is used in real-world SOC operations to detect suspicious activity.

---

## ✅ Key Takeaways
- Active Directory is central to enterprise security and **user access management**.  
- Understanding AD structure and policies is critical for SOC analysts monitoring user activity.  
- Knowledge of group policies and permissions helps in **incident response and threat detection**.  
- Familiarity with AD tools like PowerShell, ADUC, and GPMC is foundational for blue team work.

---

## 💡 Notes
- This room is highly relevant for **SOC and Blue Team roles**.  
- Recommended to combine with **Windows Fundamentals** rooms for full endpoint and domain security context.
