# wox-settings
Wox settings

# Getting Started
Run the following Powershell:
```ps
Get-Process -Name "wox" -ErrorAction SilentlyContinue | Stop-Process
cd $env:APPDATA
rm -Recurse -Force .\Wox -ErrorAction SilentlyContinue
git clone git@github.com:cmeyertons/wox-settings.git Wox
```
