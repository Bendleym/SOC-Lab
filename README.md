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
![Splunk Enterprise Interface]<img width="1918" height="865" alt="splunk_home" src="https://github.com/user-attachments/assets/47dedc28-aac2-45df-bf93-a2269b00cf95" />


**Listener Verification (TCP 9997)**  
![Listener Verification] <img width="915" height="679" alt="port_9997_listening" src="https://github.com/user-attachments/assets/ca8b0d16-cf85-4562-b057-9d2670bd1dec" />


**SOC Monitoring Dashboard**  
![SOC Monitoring Dashboard]<img width="901" height="577" alt="soc_dashboard" src="https://github.com/user-attachments/assets/c759b9a8-3fbe-4c7a-bc6f-3a14670dfa34" />


**Brute Force Alert**  
![Brute Force Alert]<img width="914" height="377" alt="brute_force_alert" src="https://github.com/user-attachments/assets/dcc33501-1bc2-42d8-8c3c-f02adbdd076d" />


**Windows Forwarder Service**  
![Windows Forwarder Service]<img width="825" height="579" alt="forwarder_service" src="https://github.com/user-attachments/assets/5d4043c2-41b6-4675-9f2c-f10baafcff48" />


### Next Steps
Plan to integrate Suricata or Security Onion for network traffic visibility.
