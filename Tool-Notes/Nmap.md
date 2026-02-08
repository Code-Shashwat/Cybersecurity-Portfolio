# Nmap

## What it is 
Nmap is a network scanning tool. 

It can be used to 
- Discover live hosts in a network
- Perform port scanning
- Identify running services on hosts
- Detect service versions and OS details

## Why it matters in Cybersecurity 
- Helps in network reconnaissance and visibility
- Useful for validating exposed services during security assessments and investigations

## What i practiced
- Discovering live hosts in a subnet
- Port scanning to identify open ports and listening services
- Identifying OS, services, and service versions
- Controlling scan speed based on environment

## Quick References
- `nmap -sn 192.168.11.0/24`
- `nmap -sT 192.168.11.1`
- `nmap -O -sV 192.168.11.1`

## Key Takeaways
- Network visibility is critical for identifying exposed services and potential attack surfaces
