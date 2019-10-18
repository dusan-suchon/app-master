**Azure CLI
[Azure CLI MSI](https://aka.ms/installazurecliwindows)

From Powershell
```
Invoke-WebRequest -Uri https://aka.ms/installazurecliwindows -OutFile .\AzureCLI.msi; Start-Process msiexec.exe -Wait -ArgumentList '/I AzureCLI.msi /quiet'
```
