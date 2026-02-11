# Networking Core Protocols

## 💻 Sample Commands / Snippets
These are **generic, legal commands** for exploring core networking protocols and inspecting traffic behavior.  
*(No lab-specific outputs or flags included to maintain TryHackMe learning integrity.)*

```bash
# Test connectivity using ICMP
ping 8.8.8.8

# Check open TCP/UDP ports
nc -zv 192.168.1.1 80    # Linux
telnet 192.168.1.1 80    # Windows

# Capture TCP packets (Linux)
tcpdump -i eth0 tcp

# Capture UDP packets (Linux)
tcpdump -i eth0 udp

# Analyze HTTP traffic
curl http://example.com
```

## 📝 Overview
The **Networking Core Protocols** room focuses on **fundamental networking protocols** used in daily communications and enterprise networks, including **TCP, UDP, ICMP, and HTTP**.  
Understanding these protocols is essential for **SOC analysts and blue team professionals** to monitor network activity, detect anomalies, and investigate incidents.

---

## 🎯 Learning Objectives
- Understand **core networking protocols** (TCP, UDP, ICMP, HTTP).  
- Learn how protocols facilitate **communication between devices**.  
- Explore **packet structure and protocol headers**.  
- Apply knowledge to **monitor network traffic and detect anomalies**.  
- Gain foundational skills for **SOC monitoring and incident response**.  

---

## 🛠 Tools Used
- Linux and Windows command-line networking tools (`ping`, `netstat`, `nc`, `curl`)  
- Packet capture tools (Wireshark, tcpdump)  
- Virtual lab network environment  

---

## 🔎 Key Concepts Learned
- **TCP & UDP:** Connection-oriented vs connectionless communication  
- **ICMP:** Network diagnostics and error reporting  
- **HTTP Protocol:** Web communication and request/response behavior  
- **Packet Structure:** Understanding headers, flags, and payloads  
- **SOC Relevance:** Monitoring traffic for abnormal protocol usage or suspicious activity  

---

## 🧠 Methodology / Approach
1. Examined the **function and behavior of core protocols**.  
2. Used **command-line tools** to test protocol communication.  
3. Captured packets with **Wireshark/tcpdump** to analyze protocol details.  
4. Investigated **network anomalies and unusual traffic patterns**.  
5. Reflected on how protocol knowledge assists **SOC monitoring and threat detection**.  

---

## ✅ Key Takeaways
- Knowledge of **core protocols** is critical for SOC analysts and blue team professionals.  
- Practical command-line and packet capture skills enable **effective monitoring and analysis**.  
- Understanding **TCP/UDP behavior, ICMP diagnostics, and HTTP communication** is essential for network security.  
- Monitoring protocol usage helps identify **suspicious activity and potential attacks**.  

---

## 💡 Notes
- This room is highly relevant for **SOC analysts, network engineers, and blue team professionals**.  
- Recommended to combine with **Networking Concepts, Networking Essentials, and Networking Secure Protocols** for complete network security coverage.
