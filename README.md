# proxmox-security-lab

## Overview
Built a virtualized security lab environment to simulate real-world attack scenarios and practice detection, analysis, and remediation using SIEM tools.

## Architecture
[Lab Diagram] (architecture/network-diagram.png)

## Environment
-  Proxmox VE (Dell Optiplex host)
-  Windows VM (monitored endpoint)
-  Kali Linux VM (attack simulation)
-  Ubuntu Server (Wazuh SIEM)
-  Home network (NAT via router)

## Key Capabilities
-  Endpoint monitoring using Wazuh agents
-  Log ingestion and alerting through Wazuh dashboard
-  Attack simulation using Kali Linux
-  Remote management via Proxmox web interface

## Security Use Cases
-  Privilege escalation testing on Windows endpoint
-  Log-based detection of suspicious activity
-  Alert triage and investigation in Wazuh

## Tools Used
- Proxmox
- Wazuh (SIEM)
- Kali Linux
- Windows (PowerShell)
- Linux (Ubuntu Server)

## Next Steps
-  Expand attack simulations (brute force, lateral movement)
-  Implement firewall segmentation (pfSense)
-  Add additional detection rules and alert tuning

