# SQL Injection Authentication Bypass


## Vulnerability Type

SQL Injection


## Target

OWASP Juice Shop Login Function


## Tools Used

- Burp Suite
- Kali Linux
- Firefox


## Testing Methodology

Captured the login request using Burp Suite Proxy and analyzed the request parameters.

The email parameter was tested for SQL injection weaknesses by modifying user input and observing server responses.


## Finding

The application accepted manipulated SQL input, resulting in authentication bypass inside the intentionally vulnerable lab environment.


## Impact

A successful SQL injection vulnerability could allow attackers to:

- Bypass authentication
- Access unauthorized accounts
- Extract sensitive database information


## Remediation

- Implement prepared statements
- Use parameterized queries
- Validate user input
- Apply secure authentication controls
