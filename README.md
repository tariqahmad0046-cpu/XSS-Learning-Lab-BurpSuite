# 🔥 DVWA XSS Learning Lab

## 📌 Overview
This project demonstrates Cross-Site Scripting (XSS) vulnerabilities using DVWA and Burp Suite.

---

## 🛠 Tools Used
- DVWA
- Burp Suite
- Firefox Browser

---

## 📚 Types of XSS Practiced
- Reflected XSS
- Stored XSS
- Basic DOM XSS

---

## 💉 Payloads Used
- <script>alert(1)</script>
- "><script>alert(1)</script>
- <img src=x onerror=alert(1)>

---

## 🚀 Workflow
1. Open DVWA XSS module
2. Set Security LOW
3. Inject payloads
4. Observe script execution
5. Capture cookies (demo)

---

## ⚠️ Disclaimer
For educational purposes only in local lab environment.
``` id="p7b"

---

# 📸 SCREENSHOT GUIDE

Take screenshots like this:

## 📌 01
DVWA XSS page

## 📌 02
Alert popup (`alert(1)`)

## 📌 03
Burp intercepted request

## 📌 04
Stored XSS result appearing again

---

# 📄 learning-notes.md

```markdown id="p8"
# XSS Learning Notes

## What is XSS?
Cross-Site Scripting allows injection of JavaScript into web pages.

---

## Types Learned
- Reflected XSS
- Stored XSS
- DOM XSS

---

## Impact
- Session hijacking
- Cookie theft
- UI manipulation

---

## Practice
Performed attacks on DVWA XSS module using Burp Suite.
