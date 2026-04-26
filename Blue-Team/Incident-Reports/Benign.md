# Incident Report: Benign

Platform: Try Hack me 

## Scenario
One of the client’s IDS indicated a potentially suspicious process execution indicating one of the hosts from the HR department was compromised. 

## Investigation
- Checked Logs using SIEM (Splunk)
- Reviewed process activity using event viewer/sysmon
- Correlated system logs  

## Findings
- Identified imposter account
- Certutil utility was used to download malicious payload
- Communication with C2 Server was established in post exploitation phase

## Indicators Identified
- Spawning suspicious process

## Conclusion
System is compromised

## Recommendation
- Isolate Machine
- Removed suspicious file
- Block domain
