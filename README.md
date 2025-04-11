🛡️ Personal SOC Lab – Pruthviraj Chavan
Welcome to my personal SOC (Security Operations Center) lab portfolio, where I demonstrate my hands-on skills in cybersecurity, threat detection, and incident response using real-world tools and techniques.

This project reflects my dedication to building a strong foundation in blue team operations, leveraging open-source technologies like Wazuh, Sysmon, and Hydra.

🧰 Technologies Used
Tool	Purpose
Wazuh	SIEM platform for monitoring and alerting
Sysmon	Windows endpoint telemetry (Event IDs)
VirtualBox	Virtual lab environment
Kali Linux	Attack simulation (Hydra, Nmap)
Windows 11	Victim endpoint for log collection
🧪 Lab Overview
Network: Static IP range 192.168.5.1/24

Topology: Ubuntu Wazuh server, Windows 11 client, Kali Linux attacker

Agent Setup: Windows agent with Sysmon, monitored by Wazuh dashboard

Brute-force simulation: Using Hydra targeting SMB → detected by Wazuh

Sysmon Event IDs Tracked: 1, 3, 10, 4625

📌 View the full lab layout in portfolio.docx and diagram.png.

🔍 Key Detections & Events
PowerShell encoded command execution

SMB brute-force (Event ID 4625)

Sysmon-based process creation and network activity

Alert rules triggered in Wazuh

📈 Screenshots
All major steps, from agent installation to alert detection, are included in the screenshots/ folder.

🚀 Roadmap
✅ Completed: Brute-force detection, Sysmon + Wazuh agent setup

🛠️ Next:

MITRE ATT&CK mapping

Custom Wazuh rules from Sigma

Threat intel enrichment (VirusTotal, AbuseIPDB)

Portfolio website version (coming soon)

👤 About Me
I'm Pruthviraj Chavan, a cybersecurity learner passionate about blue team ops.
Certified in STAR Cybersecurity, Network+, Red Hat, and CompTIA A+.

My goal is to become a skilled SOC Analyst and help organizations build resilient detection and response capabilities.
