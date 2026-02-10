# Hydra

## What it is 
Hydra is an online brute-force password cracking tool used to test login credentials against network services.

## Why it matters in Cybersecurity 
- Commonly used by penetration testers to identify weak credentials
- Helps detect misconfigured services and poor password practices

## What i practiced
- Brute forcing FTP authentication
- BBrute forcing SSH authentication

## Quick References
- `hydra -l user -P passlist.txt ftp://MACHINE_IP`
- `hydra -l root -P passwords.txt MACHINE_IP -t 4 ssh`

## Key Takeaways
- Strong, complex passwords significantly reduce the risk of brute-force attacks
- Enforcing password policies and limiting login attempts are critical security controls
