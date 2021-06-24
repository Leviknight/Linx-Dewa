## RDP Windows, Ubuntu & MacOS

[![OS - MAcOS](https://img.shields.io/badge/Windows-blue?logo=Windows&logoColor=white)](https://www.apple.com/macos)
[![OS - Ubuntu](https://img.shields.io/badge/Ubuntu-red?logo=Ubuntu&logoColor=white)](https://ubuntu.com/)
[![OS - MAcOS](https://img.shields.io/badge/MacOS-white?logo=Apple&logoColor=black)](https://www.apple.com/macos)

> **⚠ WARNING**  
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
* Password minimum 8-10 with numbers and characters leave blank if you want to use automatic password.
* Press Run workflow.
* Reload the page and press MacOS (Ngrok VNC Viewer)> build.
* Press the down arrow on IP for Connect to your RDP to get IP.
* Open VNC Viewer put ip in the field "Enter a VNC Server Address or search" and enter too connect.