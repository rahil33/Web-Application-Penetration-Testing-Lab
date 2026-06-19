# Web Application Testing Methodology


## Overview

This document explains the methodology followed during the web application penetration testing lab.


---

# Phase 1: Reconnaissance


Objective:

Understand the target application exposure before testing.


Actions Performed:

- Identified running services
- Checked exposed ports
- Collected application information


Tool Used:

Nmap


---

# Phase 2: Proxy Configuration


Objective:

Analyze client-server communication.


Actions:

Configured Burp Suite as an interception proxy.


Analyzed:

- Requests
- Responses
- Parameters
- Authentication flow


---

# Phase 3: Vulnerability Testing


Testing followed OWASP Top 10 concepts.


Areas tested:


## Injection Testing

Checked user inputs for improper validation.


## XSS Testing

Analyzed user-controlled input handling.


## Authentication Review

Observed authentication request behavior.


---

# Phase 4: Reporting


All findings were documented with:

- Description
- Impact
- Evidence
- Remediation


Professional reporting improves communication of security risks.
