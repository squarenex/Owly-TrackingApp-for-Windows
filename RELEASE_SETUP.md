# Local build → copy → auto push (no tokens in script)

1. Edit public folder path at top of `scripts\release.ps1`

2. Run:

```powershell
cd D:\office_projects\Squarenex_Staff_Tracking_Desktop
.\scripts\release.ps1
```

Copy only (no build):

```powershell
.\scripts\copy.ps1 -Windows "dist\Staffy-Windows-Setup-….exe" -MacOS "dist\….dmg"
```

Skip push: add `-NoPush`

Stable URLs after push:

```
https://github.com/squarenex/Staffy-Staff-Tracking/raw/main/releases/Staffy-Windows-Setup-latest.exe
https://github.com/squarenex/Staffy-Staff-Tracking/raw/main/releases/Staffy-macOS-latest.dmg
```
