MBS Library JOI Classmate 10 Laptop Basic Programs setup
==
Basic Setup Programs: 
- Chrome Browser
- Debloater
- Minimal Processes
- ManageEngine Mobile Device Manager (ME MDM)

If needed(KMS Server Activation):
- MS Office 365
- Windows 10

Get Back Microsoft Store After Debloating:
1. Get-AppxPackage | Remove-AppxPackage
2. Get-AppXPackage *WindowsStore* -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}
3. You can now use Microsoft Store to reinstall Calculator and any other apps that were removed.  Make sure to download official Microsoft apps.
4. 
