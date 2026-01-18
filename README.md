# 🛡️ SOC Detection Engineering Lab (Security Onion + PCAP Analysis)

## 🔍 Overview
This lab simulates a detection engineering workflow using Security Onion to analyze PCAP traffic and validate detections for common attacker behaviors such as beaconing, lateral movement, credential misuse, and data exfiltration. The project focuses on building analyst ready visibility, tuning detections, and improving triage through structured indicators and dashboards.

## 🏗️ Lab Goals
- Deploy Security Onion with network sensors for PCAP based visibility
- Analyze traffic patterns with Zeek and Suricata telemetry
- Tune detections and extract indicators for correlation and triage
- Validate detection fidelity using simulated scenarios and rule refinement

## 🧰 Tools Used
Security Onion, Zeek, Suricata, PCAP analysis, Splunk (supplemental SIEM monitoring), Sysmon, PowerShell, VirtualBox, Kali Linux, Windows 10

## ⚙️ Detection Engineering Workflow
- Ingested and analyzed PCAP traffic to identify suspicious behaviors
- Reviewed Zeek logs and Suricata alerts for signal quality and context
- Tuned rules and filters to reduce noise and improve fidelity
- Extracted indicators and patterns into dashboards for correlation
- Simulated scenarios to validate detections and refine logic

## 🎯 Scenarios Validated
- Beaconing style traffic patterns
- Lateral movement indicators and internal pivoting behavior
- Credential misuse and abnormal authentication trends
- Exfiltration like activity patterns and suspicious transfers

## 📌 Key Outcomes
- Demonstrated PCAP based investigation workflow using network telemetry
- Practiced detection tuning and indicator extraction for triage support
- Improved confidence in validating detections through simulation and refinement
- Strengthened understanding of how network logs tell an attack story end to end

## 📸 Screenshots

**Splunk Enterprise Interface**  
<img width="1918" height="865" alt="splunk_home" src="https://github.com/user-attachments/assets/47dedc28-aac2-45df-bf93-a2269b00cf95" />

**Listener Verification (TCP 9997)**  
<img width="915" height="679" alt="port_9997_listening" src="https://github.com/user-attachments/assets/ca8b0d16-cf85-4562-b057-9d2670bd1dec" />

**SOC Monitoring Dashboard**  
<img width="901" height="577" alt="soc_dashboard" src="https://github.com/user-attachments/assets/c759b9a8-3fbe-4c7a-bc6f-3a14670dfa34" />

**Brute Force Alert**  
<img width="914" height="377" alt="brute_force_alert" src="https://github.com/user-attachments/assets/dcc33501-1bc2-42d8-8c3c-f02adbdd076d" />

**Windows Forwarder Service**  
<img width="825" height="579" alt="forwarder_service" src="https://github.com/user-attachments/assets/5d4043c2-41b6-4675-9f2c-f10baafcff48" />
