# New-Windows-Config
Configure the newly installed windows.
Common issue resolving on Windows/Ubuntu dual system on Surface Book 2.

## System Deployment
OneDrive Files  
Chrome  
Taskbar settings  
[Fontlink Settings](https://shajisoft.com/shajisoft_wp/cn/%E5%AE%8C%E7%BE%8E%E8%A7%A3%E5%86%B3%E4%B8%AD%E6%96%87%E5%9C%A8%E8%8B%B1%E6%96%87windows%E4%B8%8A%E6%98%BE%E7%A4%BA%E9%AB%98%E7%9F%AE%E4%B8%8D%E4%B8%80%E7%9A%84%E9%97%AE%E9%A2%98/)
```
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\FontLink\SystemLink

MSYH.TTC,Microsoft YaHei UI,128,96
MSYH.TTC,Microsoft YaHei UI
```
[Adaptive Contrast Settings](https://www.windowscentral.com/how-disable-adapative-contrast-surface)
```
Computer\HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\Class\{4d36e968-e325-11ce-bfc1-08002be10318}\0001\FeatureTestControl 

9240 -> 9250
```

Bluetooth Pairing for Windows Ubuntu Dual System
[Issue Resolving](https://unix.stackexchange.com/questions/402488/dual-boot-bluetooth-device-pairing)

## Software to Install

### Software Engineering

[Visual Studio / Visual Studio Code](https://visualstudio.microsoft.com/)  
[JetBrains IDE](https://www.jetbrains.com/)  
[Github Desktop](https://desktop.github.com/)  
Python - UWP ([Remove path length limit](https://www.howtogeek.com/266621/how-to-make-windows-10-accept-file-paths-over-260-characters/))

### Productivity
[Office 365](https://www.office.com/)  
[Eudic](https://www.eudic.net)  
[Bandizip](https://en.bandisoft.com/bandizip/)  
[Pomotodo](https://pomotodo.com/app/)  

### Music
Spotify - UWP  
Foobar200 - UWP  
[QQMusic](https://y.qq.com/)
