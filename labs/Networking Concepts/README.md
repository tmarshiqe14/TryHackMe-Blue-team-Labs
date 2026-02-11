# Networking Concepts

## 💻 Sample Commands / Snippets
These are **generic, legal networking commands** for Windows and Linux to explore connectivity, routing, and network configuration.  
*(No lab-specific outputs or flags included to maintain TryHackMe learning integrity.)*

```bash
# Display network interfaces (Linux)
ifconfig
ip addr show

# Test network connectivity
ping 8.8.8.8

# Trace network route
traceroute 8.8.8.8   # Linux
tracert 8.8.8.8      # Windows

# Display routing table
netstat -rn           # Linux & Windows
route print           # Windows

# Check active connections
netstat -an

# DNS resolution
nslookup example.com
dig example.com       # Linux
```
## 📝 Overview
The **Networking Concepts** room introduces learners to the **OSI model** and **TCP/IP networking layers**, providing foundational knowledge for understanding how data moves through networks.  
This room is essential for **SOC analysts and blue team professionals** to analyze network traffic, identify anomalies, and monitor for malicious activity.

---

## 🎯 Learning Objectives
- Understand the **OSI model** and **TCP/IP protocol stack**.  
- Learn about **network layers** and how they communicate.  
- Explore common **network protocols** and their purpose.  
- Understand **packet flow and routing concepts**.  
- Gain foundational knowledge for **network monitoring and SOC operations**.

---

## 🛠 Tools Used
- Wireshark for packet capture and analysis  
- Linux and Windows command-line networking tools  
- Network simulation lab environment  

---

## 🔎 Key Concepts Learned
- **OSI & TCP/IP Models:** Layered understanding of networking  
- **Protocols:** ICMP, TCP, UDP, HTTP, DNS, and more  
- **Packet Flow:** How data travels from source to destination  
- **Routing & Switching:** Basic understanding of how packets are directed  
- **SOC Relevance:** Identifying abnormal traffic and monitoring for threats  

---

## 🧠 Methodology / Approach
1. Studied the **OSI model and TCP/IP layers**.  
2. Examined common **protocols** and their role in network communication.  
3. Practiced **network commands** to explore interfaces, routing, and connectivity.  
4. Used **packet capture tools** to observe network traffic patterns.  
5. Reflected on how these concepts support **SOC monitoring and anomaly detection**.  

---

## ✅ Key Takeaways
- Understanding **networking fundamentals** is critical for SOC analysts and blue team roles.  
- Knowledge of **protocols and layers** helps interpret network traffic and detect suspicious activity.  
- Practical command-line skills allow for **rapid network inspection and troubleshooting**.  
- **Packet capture and analysis** are key for incident response and threat hunting.  

---

## 💡 Notes
- This room is highly relevant for **SOC analysts, network security engineers, and blue team professionals**.  
- Recommended to combine with **Networking Essentials** and **Networking Core & Secure Protocols** for full network security knowledge.
