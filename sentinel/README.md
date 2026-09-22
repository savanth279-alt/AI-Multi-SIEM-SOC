# Microsoft Sentinel

Microsoft Sentinel is used as the primary SIEM platform in this project to collect, monitor, detect, and investigate security activity from our lab environment.

### What We Are Doing

- Ingesting Windows Security, Sysmon, and Microsoft Entra ID logs into Sentinel.
- Using KQL to analyze security events and build detections.
- Creating Analytics Rules to identify suspicious activity and generate incidents.
- Investigating alerts and correlating related events to understand attacker behavior.
- Mapping detected activity to the MITRE ATT&CK framework.
- Using Sentinel automation and playbooks for controlled incident response.
- Integrating Sentinel alerts with our Python/AI investigation layer for enrichment and analyst assistance.

### Detection Scenarios

The project will demonstrate detections for:

- Password Spraying / Brute Force
- Suspicious PowerShell Activity
- Privilege Escalation
- Lateral Movement
- Account Compromise

### Objective

The goal is to demonstrate an end-to-end SOC workflow using Microsoft Sentinel:

**Log Collection → Detection → Alert → Investigation → MITRE Mapping → Response**
