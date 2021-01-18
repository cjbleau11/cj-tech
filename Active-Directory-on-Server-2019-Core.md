>:bulb: If you can boil down an article to succinct commands, this is great.  You can also add screenshots where it makes sense.
```powershell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
Rename-Computer dc1
Restart-Computer -Force
Install-ADDSForest -DomainName hermione.local -InstallDNS

```
>:bulb: This image was pasted into an issue an the resultant URI pasted here.  Alternatively you can upload images to the code portion of the repo for reuse and total control.

![image](https://user-images.githubusercontent.com/37155987/104953321-2ecab300-5994-11eb-8092-b5825975f223.png)