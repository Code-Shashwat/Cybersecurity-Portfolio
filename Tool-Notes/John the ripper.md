# John the ripper

## What it is 
John the Ripper is a powerful password and hash cracking tool. It supports a wide range of hash types and provides multiple cracking modes such as wordlist, single, and rule-based attacks.

## Why it matters in Cybersecurity 
- Helps assess password strength by identifying weak or easily crackable hashes
- Useful for password auditing, incident response, and penetration testing

## What i practiced
- Cracking basic hashes using wordlists
- Cracking windows authentication hashes
- Cracking Linux password hashes from /etc/shadow (using unshadow)
- Creating and applying custom cracking rules
- Cracking password-protected ZIP files (using zip2john)
- Cracking SSH private key passphrases (using ssh2john)

## Quick References
- `john --wordlist=/usr/share/wordlists/rockyou.txt hash_to_crack.txt`
- `john --wordlist=/usr/share/wordlists/rockyou.txt --format=sha512crypt unshadowed.txt`
- `john --single --format=raw-sha256 hashes.txt`
- `john --wordlist=/usr/share/wordlists/rockyou.txt --rule=PoloPassword hash_to_crack.txt`
- `john --wordlist=/usr/share/wordlists/rockyou.txt zip_hash.txt`
- `john --wordlist=/usr/share/wordlists/rockyou.txt id_rsa_hash.txt`

## Key Takeaways
- Strong password policies and secure hashing are critical to protect systems from credential attacks
- Weak passwords can often be cracked quickly, even when hashes are stored securely
