# 🔐 Web Application Security Testing 

This repository contains the outcome of my internship task under **Future Interns**, where I performed Web Application Security Testing on a real-world vulnerable site, **Altoro Mutual**, using the **UpGuard Online Scanner**.

---

# ✅ Task Overview

As part of my cybersecurity internship with **Future Interns**, I was assigned a real-world simulation task to assess the security of a sample web application. The objective was to identify common vulnerabilities using a safe, intentionally insecure site and a lightweight vulnerability scanner.

This task was designed to help me understand how web applications can be misconfigured, how to recognize risks using automated tools, and how to compile a professional Security Assessment Report with real findings, screenshots, and recommended fixes.

---

# 🛠 Tools & Environment

- 🌐 **Altoro Mutual (https://demo.testfire.net)** – Intentionally vulnerable banking application
- 🧪 **UpGuard Online Scanner** – Free browser-based web vulnerability scanner
- 🖥 **Edge Browser** – For browsing and manual interaction
- 📸 **Snipping Tool** – For capturing screenshots
- 📝 **Microsoft Word** – For documentation and report writing

---

# 🧪 Findings from Vulnerability Scan

- ❌ *Missing Security Headers*
  - Strict-Transport-Security, Content-Security-Policy, Referrer-Policy, and others were not implemented
- ❌ *Information Disclosure*
  - Web server technologies (Apache, Tomcat, JSP) were exposed in HTTP response headers
- ❌ *Insecure Defaults*
  - No security.txt file for vulnerability disclosure handling
- ✅ *No high/critical vulnerabilities*
  - No SQLi, XSS, or auth bypass issues detected

🟡 *Summary of Risk Levels Identified:*
- 0 Critical
- 0 High
- 0 Medium
- 5 Low
- 35 Informational

---

# 📁 Repository Contents

- reports/ – Contains:
  - Final_Security_Report.pdf
  - PentestTools-WebsiteScanner-report.pdf: Original scan result
- screenshots/ – Images showing login, tool usage, and scanner results
- README.md – This summary file

---

# 📌 What I Learned

- How to conduct vulnerability scans using web-based tools
- Interpreting scanner outputs and mapping to OWASP Top 10
- Understanding HTTP headers and their security impact
- Writing a structured technical report with screenshots and mitigation steps

---

# 📎 Tags  
#CyberSecurity #AltoroMutual #UpGuard #OWASP #SecurityAssessment #InternshipProject #WebTesting #FutureInterns 

---
