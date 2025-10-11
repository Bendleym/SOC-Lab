# SOC Splunk Detection Lab

### Overview
Built a home SOC lab using Splunk Enterprise and Windows event forwarding to detect brute-force login attempts and monitor system activity.

### Architecture
- Splunk Enterprise installed on Kali Linux
- Windows 10 Forwarder sending Sysmon, Security, and System logs over TCP 9997
- Host-only VirtualBox network for isolated log traffic

### Tools Used
Splunk, Sysmon, Windows Event Viewer, PowerShell, VirtualBox, Kali Linux

### Key Highlights
- Configured Universal Forwarder and verified event ingestion
- Created a custom dashboard to visualize failed login attempts (Event ID 4625)
- Designed an automated alert for brute-force activity simulation
- Documented full setup and architecture diagrams

### Screenshots
**Splunk Enterprise Interface**  
![Splunk Enterprise Interface](screenshots/splunk_home.png)

**Listener Verification (TCP 9997)**  
![Listener Verification](screenshots/port_9997_listening.png)

**SOC Monitoring Dashboard**  
![SOC Monitoring Dashboard](screenshots/soc_dashboard.png)

**Brute Force Alert**  
![Brute Force Alert](screenshots/brute_force_alert.png)

**Windows Forwarder Service**  
![Windows Forwarder Service](screenshots/forwarder_service.png)

### Next Steps
Plan to integrate Suricata or Security Onion for network traffic visibility.
