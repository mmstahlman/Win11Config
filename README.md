# Win11Config
Configuration for Windows 11 Endpoints

Usage:
``` PowerShell
$GitScripts = @(
  'https://raw.githubusercontent.com/mmstahlman/Win11Config/refs/heads/main/Test-Script.ps1'
)
ForEach ( $Script in $GitScripts ) { Invoke-Expression ( Invoke-WebRequest $ScriptPath ) }
```
