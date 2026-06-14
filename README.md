# 🔎 SIEM Detection Rules

Detection rules are the core of any SOC's ability to identify threats in real time.
They define the logic that turns raw log data into actionable alerts — separating 
meaningful signals from noise across thousands of events per second.

This repository contains detection rules built and tested in a real SOC environment,
organized by platform and log source.

---


### Microsoft Sentinel — Analytics Rules

Analytics rules in Microsoft Sentinel are KQL-based scheduled queries that run against 
ingested log data to detect suspicious behavior, policy violations, and potential threats.
Each rule defines the query logic, trigger conditions, alert severity, and mapped 
MITRE ATT&CK techniques.


| # | Rule Name |
|---|-----------|
| 01 | Distributed Account Takeover Attack |
| 02 | F5 WAF: Password Reset Attempts by Single Source IP |
| 03 | IP tried to reset a user password matches an IOC |
| 04 | Potential DGA Attack Detected |
| 05 | TI Map URL Entity to DeviceProcessEvent |
| 06 | WAF.F5ASM.001: Server Unavailable Error |



## 👤 Author

**Abdalhadi** — SOC Analyst  
[GitHub](https://github.com/abdalhadi12)
