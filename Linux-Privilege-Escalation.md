# Lab Report: Linux Privilege Escalation

## Summary of the Target
This lab demonstrates **Linux privilege escalation techniques** including sudo, SUID, cron jobs, and capabilities.

## Exploitation Steps
1. **Enumeration** – Gathered system information and misconfigurations.  
2. **Privilege Escalation** – Used kernel exploit, misconfigured cron jobs, and SUID binaries.  
3. **Capstone Challenge** – Combined multiple vectors to achieve root access.  

## Findings with Screenshot
- Found multiple misconfigurations allowing privilege escalation.  
- Successfully gained **root privileges** on the system.  
- Retrieved flags as proof of exploitation.

![Linux Privilege Escalation Screenshot](Linux%20Privilege%20Escalation2.PNG)

## Remediation Advice
- Apply **principle of least privilege**.  
- Keep systems patched and kernel updated.  
- Audit and restrict **SUID binaries** and cron jobs.  
- Implement system monitoring for suspicious privilege escalations.
