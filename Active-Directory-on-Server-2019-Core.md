```powershell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
Rename-Computer dc1
Restart-Computer -Force
Install-ADDSForest -DomainName hermione.local -InstallDNS

```