# Networking Essentials

## 💻 Sample Commands / Snippets
These are **generic, legal networking commands** for Windows and Linux to explore connectivity, protocol behavior, and basic network troubleshooting.  
*(No lab-specific outputs or flags included to maintain TryHackMe learning integrity.)*

```bash
# Display IP configuration
ip addr show       # Linux
ifconfig           # Linux
ipconfig /all      # Windows

# Test connectivity to a host
ping 8.8.8.8

# Test open ports on a host
nc -zv 192.168.1.1 80   # Linux
telnet 192.168.1.1 80   # Windows

# Trace route packets to a host
traceroute 8.8.8.8      # Linux
tracert 8.8.8.8         # Windows

# Capture network packets (Linux)
tcpdump -i eth0
```

## 📝 Overview
The **Networking Essentials** room builds on foundational networking concepts by exploring **common protocols, addressing, and network troubleshooting techniques**.  
This room is essential for **SOC analysts and blue team professionals** to understand how devices communicate, how to monitor traffic, and how to diagnose network issues.

---

## 🎯 Learning Objectives
- Understand **IP addressing** and **subnetting concepts**.  
- Learn about **common networking protocols** (TCP, UDP, ICMP, HTTP, DNS).  
- Explore **basic network troubleshooting tools and techniques**.  
- Gain knowledge of **packet flow and device communication**.  
- Apply networking fundamentals to **SOC monitoring and incident response**.  

---

## 🛠 Tools Used
- Linux and Windows command-line tools (`ping`, `traceroute`, `netstat`, `nc`, `ipconfig`/`ifconfig`)  
- Packet capture tools (Wireshark, tcpdump)  
- Virtual lab network environment  

---

## 🔎 Key Concepts Learned
- **IP Addressing & Subnets:** Identifying network and host addresses  
- **Protocols:** Role of TCP, UDP, ICMP, HTTP, and DNS  
- **Troubleshooting:** Using command-line tools to diagnose connectivity issues  
- **Packet Flow:** Understanding how packets traverse a network  
- **SOC Relevance:** Detecting anomalies, monitoring traffic, and identifying potential attacks  

---

## 🧠 Methodology / Approach
1. Practiced **IP addressing and subnetting exercises**.  
2. Explored **network commands** for connectivity checks and troubleshooting.  
3. Captured and analyzed packets to **observe protocol behavior**.  
4. Investigated common **network issues and solutions**.  
5. Reflected on how networking knowledge supports **SOC monitoring and incident response**.  

---

## ✅ Key Takeaways
- Understanding **IP addressing, subnets, and protocols** is critical for SOC analysts.  
- **Command-line networking tools** allow for rapid diagnosis of network issues.  
- **Packet analysis** helps identify abnormal traffic or suspicious behavior.  
- Networking fundamentals are foundational for **incident response and threat detection**.  

---

## 💡 Notes
- This room is highly relevant for **SOC analysts, network security engineers, and blue team professionals**.  
- Recommended to combine with **Networking Concepts** and **Networking Core & Secure Protocols** for complete network security knowledge.
