```powershell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
Rename-Computer dc1
Restart-Computer -Force
Install-ADDSForest -DomainName hermione.local -InstallDNS

```

![image](https://user-images.githubusercontent.com/37155987/104953321-2ecab300-5994-11eb-8092-b5825975f223.png)