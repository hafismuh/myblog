---
author: "Hafis Muhammad"
title: "How to Install Windows Server 2025 in VMWare Fusion"
date: "2025-08-22"
description: #
tags: 
- Windows Server
- VMWare Fusion
---

When I tried to use Windows Server 2025 in VMware Fusion on my Mac, I couldn’t find the ISO file on the Microsoft website. The ISO file must be in ARM architecture so that it can be run on VMware Fusion on a Mac. After watching many videos on YouTube, I found this website, https://uupdump.net/, which helped me to get the ISO file.

![Windows Server 2025](win-server-2025.webp)


## Download Windows Server 2025

1. Go to https://uupdump.net/ and type ‘Windows Server Preview’ into the ‘Browse’ field
![uup1](uup1.webp)
2. Select the language you want to use, then Next
![uup2](uup2.webp)
3. Select edition, then Next
![uup3](uup3.webp)
4. Create download package
![uup4](uup4.webp)

Once you have downloaded the package, you will receive a ZIP file, but this is not yet complete. To complete the download, you will need to use Terminal and follow the instructions under the ‘Create download package’ button until you get the ISO file.

![steps](steps.webp)



## Install Windows Server 2025 in VMware Fusion on Mac

Create a New Virtual Machine in VMware Fusion then add the ISO file. Follow these steps for installation:

1. Click add to add new machine
![add1](add1.png)
2. Select the Installation Method. Click Continue or you can drag and drop the ISO file here
![add2](add2.png)
3. Create a New Virtual Machine. Click Continue
![add3](add3.png)
4. Choose Operating System. Select "Windows 11 64-bit ARM" then Continue
![add4](add4.png)
5. Choose Firmware Type. This will be automatically because this 64-bit will ran in UEFI mode. Click Continue
![add5](add5.png)
6. Choose Encryption. Just generate the password only for trial purpose. Click Continue
![add6](add6.png)
7. Finish. Resource you use will appear here. You can change it later in Settings
![add7](add7.png)
8. Save your machine and define the name 
![add8](add8.png)
9. The new machine is ready to start
![add9](add9.png)

After successfully added a Windows Server to VMWare Fusion, you have to check the settings to ensure the resource you use and this machine will running after you start up the machine.

![settings](settings.png)

1. Press any key when this screen appear when you start up the machine
![step1](step1.webp)
2. Select your language
![step2](step2.webp)
3. Select your keyboard
![step3](step3.webp)
4. Choose Install Windows Server
![step4](step4.webp)
5. Select Image: Windows Server 2025 Server Data Center
![step5](step5.webp)
6. Accept the agreement
![step6](step6.webp)
7. Select disk location
![step7](step7.webp)
8. Click Install
![step8](step8.webp)
9. Please wait until the installation is complete
![step9](step9.webp)
10. Define your password
![step10](step10.webp)

## Troubleshoot
![error-boot](error-boot.png)

When your machine didn't start, try to reconnect CD/DVD because the correct boot is CD/DVD and make sure you select the correct ISO file.
![tshoot1](tshoot1.png)
![tshoot2](tshoot2.png)


