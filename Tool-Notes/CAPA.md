# CAPA

## What it is 
- CAPA is a malware analysis tool used to identify capabilities in executable files (PE, ELF, .NET, shellcode) without executing them.

## Why it matters in Cybersecurity 
- Helps detect malicious capabilities such as persistence, network communication, privilege escalation, and code injection
- Maps identified behaviors to MITRE ATT&CK techniques, supporting faster triage and analysis

## What i practiced
- Understanding how CAPA identifies capabilities using rules
- Running basic scans on sample binaries and interpreting the output


## Quick References
- `capa sample.exe`
- `capa -r rules/ sample.exe`

## Key Takeaways
- Useful for quickly understanding what a suspicious file is capable of, without running it
