# Cross Site Scripting (XSS) Testing


## Vulnerability Type

Cross Site Scripting (XSS)


## Target

OWASP Juice Shop Search Functionality


## Tools Used

- Burp Suite
- Firefox Browser
- Kali Linux


## Testing Methodology

The application search functionality was tested by injecting script-based input payloads.

Requests were captured and analyzed using Burp Suite Proxy to inspect how user-controlled input was processed by the application.


## Finding

The application processed unsanitized user input, allowing script execution inside the browser environment.


## Security Impact

A successful XSS vulnerability may allow:

- Execution of unwanted browser scripts
- Session theft attacks
- User redirection
- Client-side manipulation


## Remediation

Recommended fixes:

- Validate user input
- Encode output data
- Implement Content Security Policy (CSP)
- Sanitize user-controlled parameters
