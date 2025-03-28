# SQL Injection Vulnerabilities 🚨  

## Overview  
This project explores **SQL injection vulnerabilities**, demonstrating how attackers can manipulate SQL queries to extract, modify, or delete data from databases. It includes a **hands-on lab setup** using **Windows Server, MariaDB, and ASPX files** to showcase common attack techniques and best practices for mitigation.  

## 📌 Topics Covered  
✔️ **What is SQL Injection?**  
✔️ **Why SQL Injection is Dangerous**  
✔️ **Lab Setup & Initial Vulnerability Testing**  
✔️ **Identifying Hidden Data using UNION-Based Injection**  
✔️ **Extracting Sensitive Information**  
✔️ **Lateral Movement via Stolen Credentials**  
✔️ **How to Fix SQL Injection Vulnerabilities**  

## 🏗️ Lab Setup  
The project was tested in a **Windows Server environment** with **MariaDB 10.11** and **ASPX-based web applications**:  
- `dbsetup.aspx` (Database setup)  
- `listalbums.aspx` (SQL query target)  
- ODBC Data Source configuration  

## 💀 Attack Demonstration  
The project covers multiple **SQL injection techniques**:  
- **Basic Injection**: `' OR '1'='1` – Bypasses authentication  
- **Error-Based Injection**: Finding vulnerabilities via SQL errors  
- **UNION-Based Injection**: Extracting hidden database tables  
- **Dumping Sensitive Data**: Retrieving emails & password hashes  
- **Lateral Movement**: Credential reuse & privilege escalation  

## 🔐 Mitigation Strategies  
To secure web applications, the following countermeasures were implemented:  
✅ **Parameterized Queries** – Prevents direct SQL execution  
✅ **Input Validation** – Blocks unexpected input (e.g., `' OR '1'='1`)  
✅ **Least Privilege** – Restricts database permissions  
✅ **Web Application Firewalls (WAFs)** – Detects & blocks SQLi attempts  
✅ **Regular Security Testing** – Ensures ongoing protection  

## 📄 Full Report  
Check out the full report **[here]([SQL_Injection_Vulnerabilities.pdf](https://github.com/smitthbrian/SQL-Injection-Vulnerabilities/blob/main/SQL%20Injection%20Vulnerabilities.pdf))** for step-by-step details.  

## 🔗 Additional Resources  
For more information on SQL Injection, visit:  
🔹 [CISA SQL Injection Guide](https://www.cisa.gov/sites/default/files/publications/sql200901.pdf)  

---

### **GitHub Profile Update**  

Send me the link to your profile repository so I can **update your portfolio README** with this new project! 🚀
