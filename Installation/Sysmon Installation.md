<img width="1014" height="720" alt="image" src="https://github.com/user-attachments/assets/de16ba11-4a1b-4a10-b85c-3ceccae39ef7" /># 🛡️ Sysmon Installation Guide (Windows)
📌 What is Sysmon?

> ## Sysmon (System Monitor) is a Windows system service and driver that logs detailed system activity such as:
* Process creation
* Network connections
* File creation
* Registry changes
* Image loading

It is widely used in SOC, DFIR, Threat Hunting, and SIEM environments.

---

# Step 1 – Download Sysmon
<p align="center"><img src="https://github.com/user-attachments/assets/60c5c7c5-7784-47b1-9104-6add2eb3c0f0"></p>

---
# Step 2 – Extract File
<p align="center"><img src="https://github.com/user-attachments/assets/ee0d68b8-7ed9-4296-adda-ed7dfe7b5eb8"></p>

---
# Step 3 – Download Sysmon Config
> ## Go this link https://github.com/olafhartong/sysmon-modular
<p align="center"><img src="https://github.com/user-attachments/assets/e20e52ca-8073-4a7a-98ca-a42dfd3f4361"></p>

> ## Click on that `sysmonconfig.xml`
<p align="center"><img src="https://github.com/user-attachments/assets/2240d439-49ad-4422-bb91-aa20b79c822c"></p>

> ## Click `Raw`
<p align="center"><img src="https://github.com/user-attachments/assets/d9f308ea-25d0-4555-9979-19446bdd8e13"></p>

> ## Right click on white space and `Save as`
<p align="center"><img src="https://github.com/user-attachments/assets/786b4593-8b20-45fe-a6b3-1240c55ba2cd"></p>

> ## Save in sysmon file
<p align="center"><img src="https://github.com/user-attachments/assets/acbab1f1-6157-4029-824b-bee6635f3fd5"></p>

> ## Now, we have sysmon and sysmon config file
<p align="center"><img src="https://github.com/user-attachments/assets/a0c7f757-53e8-4b93-9a7d-67f035d8b900"></p>

---
# Step 4 – Run with Powershell

> ## Click `Run as administrator`
<p align="center"><img src="https://github.com/user-attachments/assets/a07765fd-ca71-4125-bb16-bb9b96fda24e"></p>

> ## Go to sysmon directory
<p align="center"><img src="https://github.com/user-attachments/assets/7d276fde-2556-4d0f-b090-3ef28f291a74"></p>

> ## Install `Sysmon64.exe`
```
.\Sysmon64.exe -i .\sysmoncnofig.xml
```
<p align="center"><img src="https://github.com/user-attachments/assets/72fbee93-4d8a-48ca-967c-92bf198e975c"></p>

> ## Click Agree
<p align="center"><img src="https://github.com/user-attachments/assets/1e94d199-38b0-46ed-8270-e446bbef6756"></p>

> ## Now, Sysmon is started.
<p align="center"><img src="https://github.com/user-attachments/assets/9fa4112d-8d8e-42ac-8d27-aa5351665d1d"></p>

> ## If want to check services is running or not, check these steps
<p align="center"><img src="https://github.com/user-attachments/assets/a8f44188-50fb-412a-85a9-589fd35d56d2"></p>



