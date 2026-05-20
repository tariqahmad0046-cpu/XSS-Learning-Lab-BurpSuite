# XSS Security Report

## Target
DVWA Localhost

## Vulnerability
Cross-Site Scripting (XSS)

## Method
Manual payload injection + Burp Suite interception

## Impact
- JavaScript execution in browser
- Possible session theft

## Fix
- Input validation
- Output encoding
- Content Security Policy (CSP)
