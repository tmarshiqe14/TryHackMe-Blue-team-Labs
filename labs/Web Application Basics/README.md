# Web Application Basics

## 💻 Sample Commands / Snippets
These are **generic, legal commands** for exploring web applications, HTTP requests, and basic web interactions.  
*(No lab-specific outputs or flags included to maintain TryHackMe learning integrity.)*

```bash
# Test HTTP connectivity
curl http://example.com

# View HTTP headers
curl -I http://example.com

# Make a GET request
curl -X GET http://example.com

# Make a POST request
curl -X POST -d "username=test&password=test" http://example.com

# Basic URL encoding/decoding (Linux)
python3 -c "import urllib.parse; print(urllib.parse.quote('test value'))"
```
# Web Application Basics

## 📝 Overview
The **Web Application Basics** room introduces learners to the fundamentals of **web applications**, including **HTTP requests, URLs, request methods, and response codes**.  
This room is essential for **SOC analysts and blue team professionals** to understand how web applications communicate, identify anomalies, and monitor potential threats.

---

## 🎯 Learning Objectives
- Understand the **structure of web applications** and how clients interact with servers.  
- Learn about **HTTP methods, status codes, and headers**.  
- Explore **URLs, parameters, and query strings**.  
- Understand the basics of **web traffic monitoring**.  
- Gain foundational skills for **SOC monitoring and web security analysis**.  

---

## 🛠 Tools Used
- Web browsers and developer tools  
- Curl for HTTP requests  
- Basic Python or scripting for URL manipulation  
- Virtual lab web applications  

---

## 🔎 Key Concepts Learned
- **HTTP Requests & Responses:** GET, POST, PUT, DELETE, status codes  
- **URLs & Parameters:** Understanding query strings and form data  
- **Request Headers:** How clients provide context to servers  
- **Response Analysis:** Identifying anomalies or errors in web traffic  
- **SOC Relevance:** Monitoring web traffic and detecting unusual behavior  

---

## 🧠 Methodology / Approach
1. Explored **web application structure** and request-response behavior.  
2. Used **curl and browser tools** to test HTTP requests.  
3. Examined **headers, status codes, and parameters** for insights into web app communication.  
4. Practiced analyzing **HTTP responses** to detect unusual activity.  
5. Reflected on how **web traffic knowledge supports SOC monitoring and anomaly detection**.  

---

## ✅ Key Takeaways
- Understanding **HTTP methods, headers, and response codes** is critical for SOC analysts.  
- Knowledge of **URLs and parameters** helps monitor web traffic and detect anomalies.  
- Practical use of tools like **curl and browser developer tools** aids in web security analysis.  
- Foundational web application knowledge is essential for **incident response and threat detection**.  

---

## 💡 Notes
- This room is highly relevant for **SOC analysts, web security engineers, and blue team professionals**.  
- Recommended to combine with **JavaScript Essentials, SQL Fundamentals, and Burp Suite: The Basics** for full web application security coverage.
