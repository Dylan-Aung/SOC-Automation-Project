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
| Windows Server | https://www.microsoft.com/en-us/evalcenter/download-windows-server-2022?msockid=32a1545e94ca6f9833da42b695216ec9 |
| Window 11 Pro |  |
| Duo Admin Account | https://duo.com/ |
| Duo Window Logon Installer | https://duo.com/docs/checksums#duo-windows-logon |
| Duo Mobile App | **Can download Ios and Android** |
