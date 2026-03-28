# SIEM Installation – Splunk

## 📌 Objective
Deploy a Security Information and Event Management (SIEM) platform to collect and analyze logs.

## SIEM Platform

Splunk Enterprise

##  ⚙️ Installation Steps

1. Download Splunk Enterprise installer
2. Run installer on Windows 10 VM
3. Create admin credentials
4. Launch Splunk Web interface

Access URL:

http://localhost:8000

5. Configure Log Inputs
Enabled:
- Windows Event Logs (Security, Application)
- Sysmon logs
6. Verify Data Ingestion

**Query:**

index=main sourcetype=XmlWinEventLog earliest=-10m

## Result

Splunk SIEM successfully deployed on the Windows system.

## 🧠 Key Learning
- Proper ingestion is critical for detection
- Misconfigured inputs result in missing data
