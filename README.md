# ApexPlanet-Task3-Web-Application-Security
Web Application Security Testing using DVWA in Kali Linux
Overview

This project demonstrates common web application vulnerabilities using DVWA (Damn Vulnerable Web Application) in Kali Linux.
The objective is to understand how attackers exploit vulnerabilities and how they can be prevented.

This task is part of the Cybersecurity & Ethical Hacking Internship at ApexPlanet Software Pvt. Ltd.

Environment Setup
Tools Used

Kali Linux

DVWA (Damn Vulnerable Web Application)

Burp Suite

Apache Server

MariaDB Database

Firefox Browser

Vulnerabilities Demonstrated
1. SQL Injection

SQL Injection is a vulnerability that allows attackers to manipulate database queries.

Example payload:

' OR '1'='1

This allows the attacker to bypass authentication and extract database information.

Screenshot

2. Cross Site Scripting (XSS)

XSS allows attackers to inject malicious JavaScript code into a web application.

Example payload:

<script>alert("XSS")</script>

This executes JavaScript inside the victim's browser.

Screenshot

3. File Inclusion

File Inclusion allows attackers to access sensitive files from the server.

Example payload:

../../../../etc/passwd

This exposes system files.

Screenshot

4. Cross Site Request Forgery (CSRF)

CSRF tricks a logged-in user into performing unintended actions.

Example:
Changing a user's password through a malicious request.

Screenshot

5. Burp Suite Interception

Burp Suite is used to intercept and analyze HTTP requests between the browser and the server.

This helps in identifying vulnerabilities in web applications.

Screenshot

DVWA Setup

DVWA was installed in Kali Linux using Apache and MariaDB.
The application was configured and the database was created successfully.

Screenshot

Learning Outcomes

Understanding OWASP Top 10 vulnerabilities

Performing SQL Injection attacks

Testing Cross Site Scripting vulnerabilities

Understanding File Inclusion attacks

Learning CSRF attacks

Using Burp Suite for web security testing

GitHub Repository Structure
ApexPlanet-Task3-Cybersecurity
│
├── README.md
└── screenshots
      ├── dvwa_setup.png
      ├── sql_injection.png
      ├── xss_attack.png
      ├── file_inclusion.png
      ├── csrf_attack.png
      └── burp_suite.png
Internship Information

Domain: Cybersecurity & Ethical Hacking
Company: ApexPlanet Software Pvt Ltd
Task: Task 3 – Web Application Security
