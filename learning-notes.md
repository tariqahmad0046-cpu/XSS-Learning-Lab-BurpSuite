# 🧠 XSS Learning Notes (DVWA Practice Lab)

## 📌 What I Learned

In this project, I practiced Cross-Site Scripting (XSS) using DVWA in a controlled lab environment. I understood how user input can be executed as JavaScript in a browser.

---

## 🔥 What is XSS?

XSS (Cross-Site Scripting) is a vulnerability where an attacker injects malicious JavaScript into a web page that is executed by other users.

---

## 🧪 Types of XSS Practiced

### 1️⃣ Reflected XSS
- Input is immediately reflected in the response
- Happens via URL or form input

### 2️⃣ Stored XSS
- Payload is saved in database
- Executes every time page is loaded

### 3️⃣ DOM-Based XSS
- Vulnerability exists in client-side JavaScript
- Browser modifies DOM insecurely

---

## 💉 Payloads Tested

- `<script>alert(1)</script>`
- `"><script>alert(1)</script>`
- `<img src=x onerror=alert(1)>`
- `<svg onload=alert(1)>`

---

## 🛠 Tools Used

- DVWA (Damn Vulnerable Web Application)
- Burp Suite Community Edition
- Firefox Browser
- Kali Linux

---

## 🚀 Key Learning Points

- How user input can be dangerous if not sanitized
- How JavaScript executes in browser context
- Importance of output encoding
- How attackers can manipulate web pages

---

## ⚠️ Impact of XSS

XSS vulnerabilities can lead to:
- Session hijacking
- Cookie theft
- Defacement of website
- Phishing attacks

---

## 🛡️ Prevention Methods

- Input validation
- Output encoding
- Content Security Policy (CSP)
- Using secure frameworks

---

## 📌 Conclusion

This lab helped me understand real-world web application security issues and how attackers exploit XSS vulnerabilities. All testing was performed in a safe local DVWA environment for educational purposes only.
