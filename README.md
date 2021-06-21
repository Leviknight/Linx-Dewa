# RDP Windows 10

> **2CPU & 7GB RAM**
> ## [![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/mrijoo/RDP/blob/main/.github/workflows/main.yml)

> **⚠ WARNING**  
> don't close the starter terminal (Connected to Github)

### How to run the project. 

* Click Fork in the right corner of the screen to save it to your Github.
* Visit https://dashboard.ngrok.com to get **Ngrok Auth Token**
* In Github go to Action> RDP> Run workflow
* In Value: visit https://dashboard.ngrok.com/auth/your-authtoken Copy and Paste Your Authtoken into
* Password minimum 8-10 with numbers and characters leave blank if you want to use automatic password
* Press Run workflow
* Reload the page and press RDP> build
* Press the down arrow on Account for Connect to your RDP to get IP, User, Password.

### Tunnel Servers.

* us - United States (Ohio)
* eu - Europe (Frankfurt)
* ap - Asia/Pacific (Singapore)
* au - Australia (Sydney)
* sa - South America (Sao Paulo)
* jp - Japan (Tokyo)
* in - India (Mumbai)

### Google Remote Desktop. 

* Visit https://remotedesktop.google.com/headless to get **Google Remote Desktop Code**
* Click Start> Next> Allow> Copy Windows (PowerShell)
* In Github go to Action> Google Remote Desktop> Run workflow
* In Value: Paste Code
* Press Run workflow
* Reload the page and press RDP> build
* Wait and visit https://remotedesktop.google.com/access to connect rdp
