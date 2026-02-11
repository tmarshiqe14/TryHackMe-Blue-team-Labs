# SQL Fundamentals

## 💻 Sample Commands / Snippets
These are **generic, legal SQL commands** to explore database queries and basic data retrieval.  
*(No lab-specific outputs or sensitive data included to maintain TryHackMe learning integrity.)*

```sql
-- Select all columns from a table
SELECT * FROM users;

-- Select specific columns
SELECT id, name, email FROM users;

-- Filtering results
SELECT * FROM users WHERE role = 'admin';

-- Ordering results
SELECT * FROM users ORDER BY created_at DESC;

-- Joining tables
SELECT orders.id, users.name, orders.total
FROM orders
JOIN users ON orders.user_id = users.id;

-- Aggregation example
SELECT COUNT(*) AS total_users FROM users;
```
---

## 📝 Overview
The **SQL Fundamentals** room introduces learners to **relational databases** and **SQL query language**.  
Learners explore **SELECT statements, filtering, ordering, joining tables, and aggregation functions**.  
Understanding SQL is essential for **SOC analysts and blue team professionals** to query logs, investigate incidents, and analyze database-related threats.

---

## 🎯 Learning Objectives
- Understand **relational database concepts** and table structures.  
- Learn **basic SQL queries** including SELECT, WHERE, ORDER BY.  
- Explore **joins** to combine data from multiple tables.  
- Use **aggregation functions** like COUNT, SUM, AVG for analysis.  
- Gain foundational skills for **database monitoring and SOC investigations**.  

---

## 🛠 Tools Used
- MySQL, PostgreSQL, or SQLite databases  
- SQL clients (DBeaver, pgAdmin, MySQL Workbench)  
- Virtual lab database environments  

---

## 🔎 Key Concepts Learned
- **Tables & Columns:** Understanding relational data structures  
- **Filtering & Sorting:** Retrieving relevant information efficiently  
- **Joins:** Combining data from multiple sources  
- **Aggregation:** Summarizing and analyzing data  
- **SOC Relevance:** Querying logs, databases, and monitoring for suspicious activity  

---

## 🧠 Methodology / Approach
1. Practiced **basic SELECT queries** to retrieve data from tables.  
2. Applied **WHERE and ORDER BY clauses** to filter and sort results.  
3. Explored **JOIN operations** to combine information across multiple tables.  
4. Used **aggregation functions** to analyze and summarize data.  
5. Reflected on how SQL skills support **incident investigations and SOC monitoring**.  

---

## ✅ Key Takeaways
- SQL knowledge is critical for querying **databases and logs** in SOC roles.  
- Understanding joins and aggregation helps **analyze complex datasets**.  
- Practical SQL skills aid in **detecting anomalies and suspicious activity**.  
- Foundational database knowledge is essential for **incident response and threat hunting**.  

---

## 💡 Notes
- This room is highly relevant for **SOC analysts, database security engineers, and blue team professionals**.  
- Recommended to combine with **Web Application Basics, Burp Suite, and JavaScript Essentials** for full web security and data monitoring coverage.
