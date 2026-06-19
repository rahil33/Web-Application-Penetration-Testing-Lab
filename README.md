# Web Application Penetration Testing Lab 🛡️


## Project Overview

This project demonstrates a web application penetration testing workflow performed against OWASP Juice Shop in a controlled cybersecurity lab environment.

The assessment focused on identifying common web application vulnerabilities, analyzing HTTP communication, exploiting intentionally vulnerable functionality, and documenting findings with remediation recommendations.

The goal of this project was to understand practical offensive security testing methodologies used during web application assessments.


---

# Why I Built This

After practicing vulnerability assessment and network reconnaissance, I wanted to understand how attackers analyze and test web applications.

Instead of only studying OWASP concepts, I built a hands-on lab where I could manually test vulnerabilities, inspect requests, and create professional security reports.

This project helped me understand:

- Web application attack surfaces
- HTTP request analysis
- Burp Suite workflow
- OWASP Top 10 vulnerabilities
- Security documentation


---

# Lab Environment

## Attacker Machine

Operating System:

- Kali Linux


## Target Application

- OWASP Juice Shop


Testing was performed only inside an authorized local lab environment.


---

# Tools Used

| Tool | Purpose |
|-|-|
| Burp Suite | HTTP interception and request analysis |
| Nmap | Service discovery and reconnaissance |
| Firefox | Browser testing environment |
| Kali Linux | Penetration testing platform |
| OWASP Juice Shop | Vulnerable testing application |


---

# Repository Structure

```
Web-Application-Penetration-Testing-Lab/

├── README.md
│
├── Evidence/
│   └── nmap_scan.txt
│
├── Findings/
│   ├── reconnaissance.md
│   ├── sql_injection.md
│   ├── xss_testing.md
│   └── authentication_testing.md
│
├── Reports/
│   └── web_pentest_report.md
│
├── Documentation/
│   ├── methodology.md
│   ├── tools_used.md
│   └── lessons_learned.md
│
└── Screenshots/
```

---

# Testing Methodology


## 1. Reconnaissance

Performed initial information gathering using Nmap.

Identified:

- Running services
- Open ports
- Application exposure


---

## 2. Traffic Analysis

Configured Burp Suite proxy to inspect communication between the browser and application.

Analyzed:

- HTTP requests
- Parameters
- Responses
- Authentication traffic


---

## 3. Vulnerability Testing

Security testing was performed based on OWASP Top 10 concepts.


Tested vulnerabilities:

- SQL Injection
- Cross Site Scripting (XSS)
- Authentication weaknesses


---

# Findings Summary


| Vulnerability | Risk | Status |
|-|-|-|
| SQL Injection | High | Identified |
| Cross Site Scripting | Medium | Identified |
| Authentication Testing | Reviewed | Completed |


---

# Skills Demonstrated

- Web Application Penetration Testing
- Burp Suite Usage
- HTTP Analysis
- Vulnerability Identification
- Security Reporting
- OWASP Methodology


---

# Future Improvements

Planned upgrades:

- Add OWASP ZAP scanning
- Include more OWASP Top 10 categories
- Add API security testing
- Create automated testing scripts


---

# Disclaimer

This project was performed only in an intentionally vulnerable lab environment.

Testing should only be conducted on systems where explicit authorization is provided.
