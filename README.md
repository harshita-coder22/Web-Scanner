# 🔐 Web Application Vulnerability Scanner

A Python-based web application security scanner designed to identify common vulnerabilities such as SQL Injection, Cross-Site Scripting (XSS), security misconfigurations, and outdated dependencies.

---

## 🚀 Project Overview

This project focuses on automating the process of detecting vulnerabilities in web applications using multiple open-source security tools.

The scanner analyzes a given target URL and generates a detailed report highlighting potential security risks along with recommendations.

---

## ⚙️ Features

✔ Detects SQL Injection vulnerabilities using SQLMap
✔ Identifies XSS vulnerabilities using XSStrike
✔ Checks security headers using SHCheck
✔ Scans Node.js dependencies using NPM Audit
✔ Detects broken or malicious links
✔ Generates detailed PDF reports

---

## 🛠️ Tech Stack

* Python 3
* Flask
* SQLMap
* XSStrike
* SHCheck
* NPM Audit
* WeasyPrint

---

## 🧠 How It Works

1. User inputs a target URL
2. Scanner triggers multiple tools:

   * SQLMap → SQL Injection detection
   * XSStrike → XSS detection
   * SHCheck → Security headers analysis
   * NPM Audit → Dependency vulnerabilities
   * Link Checker → Broken/malicious links
3. Results are collected and analyzed
4. A detailed PDF report is generated

---

## 📁 Project Structure

```
webscanner/
├── app.py
├── scanner.py
├── requirements.txt
├── templates/
│   ├── index.html
│   ├── results.html
│   └── report.html
└── static/
    ├── style.css
    └── script.js
```

---

## ⚠️ Important Note

This project was developed and tested in a Kali Linux environment using WSL.

Due to dependency limitations (SQLMap, XSStrike, etc.), full deployment is not available online.
Screenshots and documentation are provided to demonstrate functionality.

---

## 📸 Screenshots

![Alt Text](https://github.com/harshita-coder22/Web-Scanner/blob/df0603730f6380da956022e1549ab61b46929b43/Web%20scanner/Screenshot%202026-04-07%20111152.png)
![Alt Text](https://github.com/harshita-coder22/Web-Scanner/blob/df0603730f6380da956022e1549ab61b46929b43/Web%20scanner/Screenshot%202026-04-07%20111207.png)
![Alt Text](https://github.com/harshita-coder22/Web-Scanner/blob/df0603730f6380da956022e1549ab61b46929b43/Web%20scanner/Screenshot%202026-04-07%20111221.png)
![Alt Text](https://github.com/harshita-coder22/Web-Scanner/blob/df0603730f6380da956022e1549ab61b46929b43/Web%20scanner/Screenshot%202026-04-07%20111233.png)
![Alt Text](https://github.com/harshita-coder22/Web-Scanner/blob/df0603730f6380da956022e1549ab61b46929b43/Web%20scanner/Screenshot%202026-04-07%20111244.png)
![Alt Text](https://github.com/harshita-coder22/Web-Scanner/blob/df0603730f6380da956022e1549ab61b46929b43/Web%20scanner/Screenshot%202026-04-07%20111257.png)
![Alt Text](https://github.com/harshita-coder22/Web-Scanner/blob/df0603730f6380da956022e1549ab61b46929b43/Web%20scanner/Screenshot%202026-04-07%20111312.png)
![Alt Text](https://github.com/harshita-coder22/Web-Scanner/blob/df0603730f6380da956022e1549ab61b46929b43/Web%20scanner/Screenshot%202026-04-07%20111343.png)
![Alt Text](https://github.com/harshita-coder22/Web-Scanner/blob/df0603730f6380da956022e1549ab61b46929b43/Web%20scanner/Screenshot%202026-04-07%20111404.png)
![Alt Text](https://github.com/harshita-coder22/Web-Scanner/blob/df0603730f6380da956022e1549ab61b46929b43/Web%20scanner/Screenshot%202026-04-07%20111430.png)
![Alt Text](https://github.com/harshita-coder22/Web-Scanner/blob/df0603730f6380da956022e1549ab61b46929b43/Web%20scanner/Screenshot%202026-04-07%20111444.png)


* Scanner Interface
* Terminal Execution
* Generated Report

---

## 🔍 Key Concepts Covered

* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Security Headers Analysis
* Dependency Vulnerability Scanning
* OWASP Top 10 Concepts

---

## 🎯 Learning Outcome

* Practical understanding of web vulnerabilities
* Integration of multiple security tools
* Building a Flask-based application
* Working with Kali Linux environment

---

## 📌 Future Improvements

* Live deployment support
* Advanced vulnerability detection
* Dashboard for real-time results
* Automated remediation suggestions

---

## 👩‍💻 Author

Harshita
Frontend Developer | Cyber Security Learner

---

⭐ If you like this project, feel free to give it a star!
