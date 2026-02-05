# DVWA Pentesting Project  
**Focus:** SQL Injection and Brute Force Attacks  

## Overview
This project documents a controlled penetration testing exercise conducted on the Damn Vulnerable Web Application (DVWA). The objective was to understand how common web application vulnerabilities are exploited in practice and how insecure design and configuration choices lead to real attack paths.

All testing was performed in a local lab environment for educational purposes only.

---

## Lab Environment
- Operating System: Kali Linux  
- Target Application: Damn Vulnerable Web Application (DVWA)  
- Web Server: Apache  
- Database: MySQL  
- Browser: Firefox  
- DVWA Security Level: Low and Medium  

---

## Vulnerabilities Tested

### 1. SQL Injection
Tested input fields vulnerable to unsanitized user input, allowing manipulation of backend SQL queries.

**What was tested:**
- Injection through form inputs
- Authentication bypass using crafted SQL payloads
- Error-based responses revealing database behavior

**Impact:**
- Unauthorized access to application functionality
- Exposure of backend query logic

**CVSS Assessment:** High severity

**Key Learning:**
Improper input validation allows attackers to directly influence database logic, enabling authentication bypass and data exposure.

---

### 2. Brute Force Authentication
Tested weak authentication mechanisms by attempting repeated login attempts against the application.

**What was tested:**
- Absence of account lockout mechanisms
- Lack of rate limiting on login attempts
- Predictable credential handling

**Impact:**
- Successful unauthorized account access through repeated attempts

**CVSS Assessment:** Medium severity

**Key Learning:**
Without basic defensive controls, authentication systems are highly susceptible to brute force attacks.

---

## Evidence
- Recorded walkthrough demonstrating successful SQL and Bruteforce


[https://drive.google.com/drive/folders/18UlF3RefN6yEZk9PPg_tviYuxiuxNKyE?usp=sharing]

