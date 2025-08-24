# Lab Report: Burp Suite – Intruder

## Summary of the Target
This lab focuses on **automating requests with Burp Intruder** to perform attacks such as brute-force and credential stuffing.

## Exploitation Steps
1. **Configured Payloads** – Created a payload list of usernames and passwords.  
2. **Launched Attack** – Used Intruder to send multiple login attempts.  
3. **Analyzed Results** – Checked response lengths to identify valid credentials.  

## Findings with Screenshot
- Burp Intruder can detect valid username/password pairs.
- Example: Successful login attempt with **m.rivera:letmein1**.

![Burp Intruder Screenshot](Burp%20SuiteIntruder.PNG)

## Remediation Advice
- Implement **account lockout mechanisms** after failed login attempts.
- Use **rate limiting and CAPTCHA** to slow down brute-force attacks.
- Enforce **MFA (Multi-Factor Authentication)**.
