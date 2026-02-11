# JavaScript Essentials

## 💻 Sample Commands / Snippets
These are **generic, legal commands** to explore JavaScript behavior in browsers and scripts.  
*(No lab-specific outputs or flags included to maintain TryHackMe learning integrity.)*

```javascript
// Display text in the console
console.log("Hello, world!");

// Variables and basic operations
let username = "user";
let age = 25;
console.log(username, age);

// Functions
function greet(name) {
    return `Hello, ${name}!`;
}
console.log(greet("Alice"));

// DOM manipulation example
document.getElementById("example").innerText = "Updated text";

// Simple event listener
document.querySelector("button").addEventListener("click", () => {
    alert("Button clicked!");
});
```

# JavaScript Essentials

## 📝 Overview
The **JavaScript Essentials** room introduces learners to **JavaScript fundamentals** used in web applications.  
This includes **variables, functions, DOM manipulation, and basic events**.  
Understanding JavaScript is essential for **SOC analysts and blue team professionals** to monitor client-side scripts, detect malicious behavior, and analyze web-based threats.

---

## 🎯 Learning Objectives
- Understand **JavaScript basics**, including variables, operators, and functions.  
- Learn how **JavaScript interacts with the DOM** and web pages.  
- Explore **event handling** and dynamic behavior on websites.  
- Understand common client-side vulnerabilities (e.g., **XSS**).  
- Gain foundational skills for **monitoring web scripts and detecting suspicious activity**.  

---

## 🛠 Tools Used
- Web browsers (Chrome, Firefox) with developer tools  
- Browser console for testing JavaScript  
- Basic scripting editors (VSCode, Sublime, etc.)  
- Virtual lab web applications  

---

## 🔎 Key Concepts Learned
- **Variables & Data Types:** Storing and manipulating information  
- **Functions & Control Flow:** Executing logic and automating tasks  
- **DOM Manipulation:** Accessing and modifying web page elements  
- **Event Handling:** Responding to user interactions  
- **SOC Relevance:** Identifying malicious scripts, client-side attacks, and abnormal behavior  

---

## 🧠 Methodology / Approach
1. Practiced **basic JavaScript syntax**, variables, and functions.  
2. Manipulated **DOM elements** to understand dynamic web page behavior.  
3. Explored **event listeners** to monitor user interactions.  
4. Reflected on how JavaScript can be leveraged for attacks or monitored for anomalies.  
5. Applied concepts to **detect client-side threats** in web environments.  

---

## ✅ Key Takeaways
- Understanding **JavaScript fundamentals** is critical for monitoring web applications.  
- DOM and event knowledge helps SOC analysts detect **abnormal client-side behavior**.  
- Practical use of browser developer tools aids in **script inspection and analysis**.  
- Knowledge of JavaScript is foundational for identifying **web-based attacks like XSS**.  

---

## 💡 Notes
- This room is highly relevant for **SOC analysts, web security engineers, and blue team professionals**.  
- Recommended to combine with **Web Application Basics, SQL Fundamentals, and Burp Suite: The Basics** for full web application security coverage.
