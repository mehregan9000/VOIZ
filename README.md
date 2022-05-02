## VOIZ
 Persian Unified Communication 


## Instalation (نصب)
There are two ways to install VOIZ.

### 1. How to Install on Issabel ISO:
-install issabel iso file with Asterisk 16 or 18

-update issabel
```
yum update
```
-Run This command on your Linux CLI:
```
yum install git -y && rm -rf voiz && git clone https://github.com/voipiran/voiz.git && cd voiz && chmod 777 installVoizOnIssabel.sh && ./installVoizOnIssabel.sh
```

### 2. How to  Netinstall (install on centos7 minimal):
-install Centos7 Minimal:
-Run This command on your Linux CLI:
```
curl https://github.com/voipiran/VOIZ/blob/main/voizNetinstall.sh | bash
```


## Documents (مطالب راهنما و آموزش)

https://forum.voipiran.io/t/voiz-documents



## Features (امکانات)



## TODO List (امکانات آینده)
- [ ] Add Documentations Menu
- [ ] Transfer Webmin and Download file to Menus
- [ ] Define Default SIP Trunks
- [ ] add Installation GUI
- [ ] VOIZ Installation script on Centos7 minimal
- [ ] Improve English Theme
- [ ] Configure Linux Firewall and set APIBAN
- [ ] Show Faxes by Groups
- [ ] Add Glances System Monitoring Tools
- [ ] Add Webrtc Webphone
