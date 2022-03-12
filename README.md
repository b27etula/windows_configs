# windows_configs 

config:  
отображать скрытые файлы  
отображать известные расширения файлов  
отключить windows defender  
    "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender"  
    DisableAntiSpyware 1  
    AllowFastServiceStartup 0  
    ServiceKeepAlive 0  
    "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Real-Time Protection"  
    DisableIOAVProtection 1  
    DisableRealtimeMonitoring 1  
    "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Spynet"  
    DisableBlockAtFirstSeen 1  
    LocalSettingOverrideSpynetReporting 0  
    SubmitSamplesConsent 2  
  
Soft:  
browsers:  
firefox  
messengers:  
discord  
telegram  
slack  
  
keepassxc  
  
nordvn  
openvpn  
  
7zip  
winrar  
  
lightshot https://app.prntscr.com/en/index.html  
  
notepad++  
  
python
  
wsl  
wsl --install  
wsl --list --online  
wsl --install -d <DistroName>  
wsl --set-version <distro name> 2
