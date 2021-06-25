## RDP Windows, Ubuntu & MacOS

[![OS - Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/en-us/windows-server)
[![OS - Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![OS - MAcOS](https://img.shields.io/badge/MacOs-000000?style=for-the-badge&logo=Apple&logoColor=)](https://www.apple.com/macos/server/)

[![GitHub followers](https://img.shields.io/github/followers/mrijoo.svg?style=social&label=Follow&maxAge=2592000)](https://github.com/mrijoo)
[![GitHub stars](https://img.shields.io/github/stars/mrijoo/RDP.svg?style=social&label=Star)](https://github.com/mrijoo/RDP)
[![GitHub forks](https://img.shields.io/github/forks/mrijoo/RDP.svg?style=social&label=Fork)](https://github.com/mrijoo/RDP/fork)
[![GitHub watchers](https://img.shields.io/github/watchers/mrijoo/RDP.svg?style=social&label=Watch)](https://github.com/mrijoo/RDP)

[![GitHub issues](https://img.shields.io/github/issues/mrijoo/RDP.svg)](https://github.com/mrijoo/RDP/issues)
[![GitHub issues](https://img.shields.io/github/issues-closed/mrijoo/RDP.svg)](https://github.com/mrijoo/RDP/issues)
[![GitHub issues](https://img.shields.io/github/license/mrijoo/RDP.svg
)](https://github.com/mrijoo/RDP)

> **⚠️ WARNING**  
> don't close the starter terminal (Connected to Github)

### Tunnel Servers.

* us - United States (Ohio)
* eu - Europe (Frankfurt)
* ap - Asia/Pacific (Singapore)
* au - Australia (Sydney)
* sa - South America (Sao Paulo)
* jp - Japan (Tokyo)
* in - India (Mumbai)

### How to run the project. 

* Click Fork in the right corner of the screen to save it to your Github.
* Visit https://dashboard.ngrok.com to get **Ngrok Auth Token**.
* In Github go to Action> Windows (Ngrok RDP)> Run workflow.
* In Value: visit https://dashboard.ngrok.com/auth/your-authtoken Copy and Paste Your Authtoken into.
* Password minimum 8-10 with numbers and characters leave blank if you want to use automatic password.
* Press Run workflow.
* Reload the page and press Windows (Ngrok RDP)> build.
* Press the down arrow on Account for Connect to your RDP to get IP, User, Password.

### Google Remote Desktop. 

* Visit https://remotedesktop.google.com/headless to get **Google Remote Desktop Code**.
* Click Start> Next> Allow> Copy Windows (Windows PowerShell) / Ubuntu (Debian Linux).
* In Github go to Action> Windows/Ubuntu (Google Remote Desktop)> Run workflow.
* In Value: Paste Code.
* Press Run workflow.
* Reload the page and press Windows/Ubuntu (Google Remote Desktop)> build.
* Wait and visit https://remotedesktop.google.com/access to connect rdp.

### NVC Viewer. 

* Visit https://www.realvnc.com/en/connect/download/viewer to download **NVC Viewer**.
* Install Software.
* Visit https://dashboard.ngrok.com to get **Ngrok Auth Token**.
* In Github go to Action> MacOS (Ngrok VNC Viewer)> Run workflow.
* In Value: visit https://dashboard.ngrok.com/auth/your-authtoken Copy and Paste Your Authtoken into.
* Password minimum 8-10 numbers/characters.
* Press Run workflow.
* Reload the page and press MacOS (Ngrok VNC Viewer)> build.
* Press the down arrow on IP for Connect to your RDP to get IP.
* Open VNC Viewer put ip in the field "Enter a VNC Server Address or search" and enter too connect.

> **❕ TIPS**  
> Use the te teamviewer to avoid the lag.