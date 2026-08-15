# Wed-application-Security-Basis
Task-1
📁 Suggested repository structure
dvwa-xampp-security-lab/
│
├── README.md
├── screenshots/
│   └── dvwa-home.png
└── notes/
    └── setup-notes.md
README.md

You can copy this directly into your GitHub repository:

# DVWA – XAMPP Security Lab 🔐


## Overview


This repository documents my hands-on setup of **Damn Vulnerable Web Application (DVWA)** in a local **XAMPP** environment.


DVWA is an intentionally vulnerable PHP/MySQL web application designed for learning and practicing web application security in a controlled environment.


## 🛠️ Environment


- Operating System: Windows
- Web Server: Apache
- Database: MySQL
- PHP: 8.2.12
- Local Environment: XAMPP
- Application: DVWA


## ⚙️ Setup Completed


The following tasks were completed:


- Installed and configured XAMPP
- Started Apache and MySQL
- Configured the DVWA application
- Created the `dvwa` MySQL database
- Configured the DVWA database credentials
- Fixed the `config.inc.php` filename configuration issue
- Completed the DVWA database setup
- Successfully launched the DVWA web application locally


## 🔧 Troubleshooting


During setup, DVWA displayed:


> DVWA System error - config file not found.


The issue was caused by the configuration file being incorrectly named:


```text
config.inc.php.php

The file was renamed to the correct filename:

config.inc.php

After correcting the filename, DVWA successfully detected the configuration and the database setup could be completed.

🧪 Security Topics

DVWA provides a controlled environment for studying common web application security concepts, including:

Brute Force
Command Injection
CSRF
File Inclusion
File Upload
SQL Injection
SQL Injection (Blind)
XSS
Weak Session IDs
Authentication and authorization concepts
Cryptography
API security
📸 Result

DVWA was successfully launched on the local machine and the application dashboard was accessible through:

http://localhost/DVWA/
🎯 Learning Goals

The goal of this lab is to develop practical understanding of:

Web application security
PHP and MySQL environments
Vulnerability identification
Security testing methodologies
Troubleshooting web application configurations
Secure coding and vulnerability mitigation
⚠️ Disclaimer

DVWA is intentionally vulnerable software.

This project is for educational purposes and authorized local security testing only. DVWA should not be exposed to the public internet or deployed on production systems.

🚀 Next Steps

I plan to continue exploring the individual DVWA security modules and document my learning, observations, and mitigation techniques.

Learning cybersecurity one practical lab at a time. 🔐🚀



### 📌 GitHub repository description


Use this in the **Description** field:


> Hands-on DVWA setup and web application security lab using XAMPP, PHP, and MySQL. Documenting configuration, troubleshooting, and cybersecurity learning.


### 🏷️ Topics


Add these GitHub topics:


```text
cybersecurity
dvwa
web-security
ethical-hacking
penetration-testing
xampp
php
mysql
web-application-security
security-lab
