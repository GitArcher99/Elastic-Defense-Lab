Elastic-Defense-Lab: SOC Analyst Home Lab

Overview
Elastic-Defense-Lab is a cybersecurity home lab that simulates real-world SOC analyst tasks using AWS, Windows, Elastic SIEM, and Elastic Defend. It provides hands-on experience in threat detection, monitoring, and incident response.

Tools & Technologies

AWS EC2 – Windows instance for endpoint monitoring
Elastic SIEM – Cloud-based security analytics
Elastic Defend – Endpoint Detection & Response (EDR)
Windows Event Logs – Log collection for analysis
PowerShell – Agent installation & configuration
Key Features
✔ Deploys a Windows VM in AWS
✔ Installs Elastic Defend for endpoint security
✔ Configures Elastic SIEM for log collection & analysis
✔ Simulates malware detection using the EICAR test file
✔ Enables hands-on SOC workflows like alert triage

Setup Steps

Deploy AWS Windows Instance – Set up an EC2 instance, configure security groups, and connect via RDP.
Set Up Elastic SIEM – Deploy an Elastic Cloud instance, enable security analytics, and configure log ingestion.
Install Elastic Defend – Add and install the Elastic Defend agent on the VM to monitor security events.
Simulate Malware Detection – Run the EICAR test file to trigger an alert and review it in Elastic SIEM.
Learning Outcomes
✅ Understand SIEM architecture & log ingestion
✅ Gain hands-on experience with malware detection & response
✅ Configure endpoint security tools & analyze alerts

Future Enhancements
🔹 Automate deployment with Terraform
🔹 Expand to Linux/macOS monitoring
🔹 Develop custom detection rules & integrate other SIEM tools

Acknowledgments
Inspired by Elastic Security Labs & AWS best practices, this project provides practical cybersecurity experience in threat detection and SOC workflows.
