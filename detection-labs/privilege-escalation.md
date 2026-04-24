# Privilege Escalation Detection (Windows + Wazuh)

## Objective
Simulate privilege escalation activity on a Windows endpoint and observe detection through Wazuh SIEM.

## Environment
- Windows VM (monitored endpoint with Wazuh agen)
- Ubuntu Server (Wazuh SIEM)
- Kali Linux (attack simulation)
- Proxmox virtualization platform

## Activity Performed
Used PowerShell on the Windows endpoint to modify system-level permissions and simulate privilege escalation behavior.

## Detection
Wazuh SIEM generated alerts indicating suspicious privilege-related activity.

## Analysis
- Alerts observed in Wazuh dashboard
- Logs correlated to endpoint activity and timestamps
- Identified unusual privilege modification behavior

## Response
- Investigated alert details
- Confirmed activity source (PowerShell)
- Documented behavior for detection understanding

## Outcome
Successfully demonstrated detection of privilege escalation-related activity using Wazuh in a controlled lab environment.

## Key Takeaways
- Gained hands-on experience with endpoint monitoring using Wazuh agents
- Improved ability to analyze SIEM alerts and correlate activity
- Better understanding of how privilege-related actions generate detectable events 
