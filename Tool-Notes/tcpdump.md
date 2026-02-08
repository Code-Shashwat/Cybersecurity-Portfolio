# Tcpdump

## What it is 
Tcpdump is a powerful command-line packet analyzer used to capture and inspect TCP/IP and other network traffic in real time.

## Why it matters in Cybersecurity 
- Helps validate suspicious network activity
- Useful for investigating DNS, HTTP, and TLS traffic

## What i practiced
- Capturing packets on specific interfaces
- Filtering traffic to capture only relevant packets

## Quick References
- `tcpdump -i ens5 -c 5 -n`
- `tcpdump -i wlo1 -w data.pcap`
- `tcpdump host example.com -w http.pcap`

## Key Takeaways
- Capture only the required traffic instead of capturing everything to reduce noise and file size

