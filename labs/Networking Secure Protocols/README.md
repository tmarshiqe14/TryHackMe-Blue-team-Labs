# Networking Secure Protocols

## 💻 Sample Commands / Snippets
These are **generic, legal commands** for exploring secure network protocols and inspecting encrypted traffic.  
*(No lab-specific outputs or flags included to maintain TryHackMe learning integrity.)*

```bash
# Test TLS/SSL connectivity
openssl s_client -connect example.com:443

# Capture HTTPS packets (Linux)
tcpdump -i eth0 port 443

# Test SSH connectivity
ssh user@192.168.1.10

# Display SSL/TLS certificate information
openssl x509 -in certificate.crt -text -noout

# DNS over TLS query (Linux)
dig @1.1.1.1 example.com +dnssec
```
## 📝 Overview
The **Networking Secure Protocols** room introduces learners to **secure communication protocols**, including **TLS/SSL, SSH, and encrypted DNS**, and explains their role in protecting data over networks.  
This room is essential for **SOC analysts and blue team professionals** to monitor secure traffic, identify misconfigurations, and detect suspicious activity.

---

## 🎯 Learning Objectives
- Understand **secure protocols** and their role in protecting data.  
- Explore **TLS/SSL, SSH, and encrypted DNS communications**.  
- Learn to **monitor and troubleshoot secure traffic**.  
- Understand how **encryption impacts network analysis and SOC monitoring**.  
- Apply secure protocol knowledge to **detect anomalies and misconfigurations**.  

---

## 🛠 Tools Used
- Linux and Windows command-line tools (`openssl`, `ssh`, `dig`)  
- Packet capture tools (Wireshark, tcpdump)  
- Virtual lab network environment  

---

## 🔎 Key Concepts Learned
- **TLS/SSL:** Securing web traffic and encryption fundamentals  
- **SSH:** Secure remote access to systems  
- **Encrypted DNS:** Protecting DNS queries and preventing eavesdropping  
- **Traffic Analysis:** Identifying patterns in encrypted communication  
- **SOC Relevance:** Monitoring secure traffic, detecting anomalies, and ensuring compliance  

---

## 🧠 Methodology / Approach
1. Explored **TLS/SSL and SSH communications** in lab environments.  
2. Captured and analyzed **encrypted packets** using Wireshark/tcpdump.  
3. Tested secure protocol configurations and observed **certificate details and handshakes**.  
4. Investigated **misconfigurations or unusual patterns** in secure traffic.  
5. Reflected on how **secure protocol knowledge** supports SOC monitoring and threat detection.  

---

## ✅ Key Takeaways
- Understanding **secure protocols** is critical for SOC analysts and blue team professionals.  
- Secure traffic monitoring requires knowledge of **TLS/SSL, SSH, and encrypted DNS**.  
- Packet capture and analysis of encrypted traffic help **identify anomalies or potential attacks**.  
- Knowledge of **secure protocol configurations** enhances incident response and compliance monitoring.  

---

## 💡 Notes
- This room is highly relevant for **SOC analysts, network security engineers, and blue team professionals**.  
- Recommended to combine with **Networking Concepts, Networking Essentials, and Networking Core Protocols** for complete network security knowledge.
