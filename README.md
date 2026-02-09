<h1 align="center"> SOC Automation Project </h1> 
<p align="center"><img src="https://github.com/user-attachments/assets/396b99e2-a4df-4dc8-b9f4-d0515ca104bd"></p>
<h2 align="center"> High-Level Workflow Diagram </h2>


### Lab Objectives
In modern enterprise environments, security teams must react quickly to threats while handling large volumes of alerts. Manual investigation and response can cause delays that attackers exploit.

This lab demonstrates a fully automated SOC workflow where endpoint security events from a Windows 10 system are collected by Wazuh, processed by Shuffle SOAR, enriched with OSINT threat intelligence, documented in TheHive, and delivered to a SOC analyst via email for action.

The workflow also supports bi-directional response, allowing analysts to trigger automated actions that are executed back on the affected endpoint through Wazuh.

---

### Technical Prerequisites

| **Name**      | **Links**               |
|---------------|---------------------------|
| Virtual Box | https://www.virtualbox.org/|
| Window 11 | https://www.microsoft.com/en-us/software-download/windows11 |
| Sysmon | https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon |
| Sysmon Config | https://github.com/olafhartong/sysmon-modular |
| Wazuh | [https://duo.com/docs/checksums#duo-windows-logon](https://documentation.wazuh.com/current/quickstart.html) |
| TheHive | https://docs.strangebee.com/thehive/installation/installation-guide-linux-standalone-server/ |
| Shuffle | https://shuffler.io/ |
