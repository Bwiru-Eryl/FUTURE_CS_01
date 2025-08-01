# 📄 Web Application Security Testing Report

## ✅ Cyber Security Internship – Task 1

**Author:** Eryl Bwiru
**Track Code:** FUTURE\_CS\_01

This repository provides an in-depth security testing report on a sample web application, using DVWA (Damn Vulnerable Web Application). The goal was to identify and exploit common web application vulnerabilities in a controlled environment, aiming to better understand real-world security threats and their mitigations.

---

## 🔍 Key Findings

* ✅ **SQL Injection (SQLi)** – Successfully extracted user credentials and database schema details.
* ✅ **Cross-Site Scripting (XSS)** – Exploited Reflected, Stored, and DOM-based XSS vulnerabilities.
* ✅ **Brute Force Attack Simulation** – Conducted automated login attacks using Burp Suite.

---

## 🧠 Skills Developed

* Penetration Testing & Ethical Hacking
* Vulnerability Identification (SQLi, XSS, Brute Force)
* Web Application Security Assessment
* HTTP Request/Response Analysis with Burp Suite

---

## 🛠️ Tools & Environment

* **Operating System:** Kali Linux
* **Testing Platform:** DVWA (Damn Vulnerable Web Application)
* **Technologies:** Apache, MySQL, PHP
* **Tools Used:** Burp Suite, Custom Wordlists

---

## 📁 Report Contents

* `TASK-1_WEB_APPLICATION_SECURITY_TESTING.pdf`:
  A detailed report covering:

  * Testing methodologies and procedures
  * Payloads and techniques used
  * Evidence (screenshots)
  * Key findings and insights
  * Final conclusions and recommendations

---

## 🧪 Vulnerabilities Explored

### 1. SQL Injection (SQLi)

* Extracted sensitive user information and schema details.
* Retrieved usernames and hashed passwords using UNION-based SQL payloads.

### 2. Cross-Site Scripting (XSS)

* **Reflected XSS:** Malicious input reflected immediately in the HTTP response.
* **Stored XSS:** Injected malicious scripts stored in the database and executed upon page load.
* **DOM-Based XSS:** JavaScript manipulation through URL parameters.

### 3. Brute Force Attack

* Automated login attempts using **Burp Suite Intruder**.
* Identified weak passwords and the lack of rate-limiting protection on login forms.

---

## 📚 Key Learning Outcomes

* Practical experience in exploiting common web vulnerabilities
* Hands-on training with Burp Suite and related security tools
* Gained deeper insights into input validation, output encoding, and improving authentication security

---

## ⚠️ Disclaimer

> This project was conducted in a **safe, controlled lab environment** with intentionally vulnerable software, designed for **educational purposes only**.
> **Do not** attempt any of these techniques on live or unauthorized systems, as they may be illegal and unethical.


