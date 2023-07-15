**This is a HoneyPot VirtualMachine**
The project is meant to lure attackers to attempt to log into the VM. I disabled firewalls, port blocking, and disabled all Azure security features.

**Live Attack Map**
scroll down to see  the process.
![image](https://github.com/SchmaltzVisuals/AzureSentinelLiveAttackMap/assets/38481385/47ce9eb1-07ad-4832-a935-da82c8541ed7)


**Virtual Machine**
![image](https://github.com/SchmaltzVisuals/AzureSentinelLiveAttackMap/assets/38481385/f72aa734-5d6b-4d96-983e-0b7f0f18951a)

**Allow all inbounds**
![image](https://github.com/SchmaltzVisuals/AzureSentinelLiveAttackMap/assets/38481385/8f3d191d-9ae8-46e0-b923-3c2fbfa09eaa)

**Setup Log Analytics Workspace**
![image](https://github.com/SchmaltzVisuals/AzureSentinelLiveAttackMap/assets/38481385/d95c7aad-07f7-4967-8893-54cfeff57633)

**Grab contents from failed_rdp which is tracked security events with eventID = 4625**
![image](https://github.com/SchmaltzVisuals/AzureSentinelLiveAttackMap/assets/38481385/9379365c-6124-4a16-b0b7-49bd27de9921)

**RDP'd into VM - this is the powershell script and the logs of attempted connections / login attempts**
uses API from IPgeolocation.io, tracks coordinates of where attacks originate from
![image](https://github.com/SchmaltzVisuals/AzureSentinelLiveAttackMap/assets/38481385/29d61bf6-1d45-408b-80ca-5c36781b149b)

**Enable Microsoft Defender**
![image](https://github.com/SchmaltzVisuals/AzureSentinelLiveAttackMap/assets/38481385/035df2da-efc7-4586-b549-fba8256f1c51)

**Query to visualize our raw data from the API + PowerShell script**
![image](https://github.com/SchmaltzVisuals/AzureSentinelLiveAttackMap/assets/38481385/427610da-7afc-4dee-b62e-f43df0f8e02c)
