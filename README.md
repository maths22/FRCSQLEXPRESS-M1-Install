# FRCSQLEXPRESS-M1-Install
Install scripts for Microsoft SQL Server Express (for FRC FMS) on Apple M1 in VMs.

## Installation
Copy all scripts from the /src folder into some folder in the Parallels VM. It should be a local folder and you must have full permissions for this folder, so ideally please use some folder in the root of your drive e.g. C:\Temp or C:\SqlInstall. Decide which flavor of the SQL Server you want to install and run the *.bat file. Grant elevated permissions for the PowerShell and wait until the script completes. 

## Editions
- Microsoft SQL 2022 Express

## Requirements
- Apple M1, M2, M3
- Parallels Desktop/UTM (tested on 18.1.1)
- Windows 11 for ARM64 (Windows 10 was not tested)