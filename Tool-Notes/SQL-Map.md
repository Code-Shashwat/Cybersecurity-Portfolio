 # SQL Map

## What it is 
SQLMap is a penetration testing tool used to automate the detection and exploitation of SQL injection (SQLi) vulnerabilities in web applications.

## Why it matters in Cybersecurity 
- Widely used by security professionals to identify SQLi flaws
- Helps demonstrate real-world impact such as database enumeration, data extraction, and authentication bypass (in controlled environments)

## What i practiced
- Using common SQLMap flags and options
- Running guided scans using the wizard mode
- Enumerating database information in lab scenarios

## Quick References
- `hydra -l user -P passlist.txt ftp://MACHINE_IP`
- `sqlmap --wizard`

## Key Takeaways
- SQL injection can lead to serious data exposure if input validation is weak
- Secure coding practices (parameterized queries, validation, least privilege) are critical to protect databases
