# BadUSB
![](https://img.shields.io/badge/BadUSB-fsociety-red)<br>
This project takes advantage of the loophole in USB protocol. By changing the internal firmware of USB, after accessing the USB interface, it simulates the functions of external mouse and keyboard, so as to make the target host execute the well-constructed commands.<br>

![68747470733a2f2f696d616765732e67697465652e636f6d2f75706c6f6164732f696d616765732f323032312f303230322f3231333933325f36653462313436665f323332333636362e6a706567](https://user-images.githubusercontent.com/39434325/112772972-75a8e900-9066-11eb-9948-895916bf18ef.jpg)<br>
#### QQ：775942445<br>
#### WeChat：wwy18795980897<br>

### Introduction<br>
Like most of us, BadUSB was first introduced in Mr. Robot and is one of the FSociety's most popular tools. Whether it's downloading a Trojan to a server to control a victim's host, or Darlene throwing a bunch of USB phishing devices in a parking lot, BadUSB is one of the most important physical weapons.  <br>
![黑客军团](https://upload-images.jianshu.io/upload_images/11477676-71045c807dac0df6.png?imageMogr2/auto-orient/strip|imageView2/2/w/554/format/webp)<br>

### Advantage<br>
Is commonly used in the field of USB attack, many years ago old USB virus (automatic) autorun. Inf, but the file is now will be antivirus software easily detected, and the autorun. J inf, BadUSB is to use a loophole in the USB protocol, by changing the interior of the USB firmware, after normal USB port access, to simulate the external function of the mouse, keyboard, in order to make the target host execution has been carefully constructed good command. In this process will not cause anti-virus software, a trace of suspicion firewall. And because it's at the firmware level, USB flash drive formatting can't prevent the execution of its internal code.  <br>
![Leonardo_Arduino](https://upload-images.jianshu.io/upload_images/11477676-4347a3e41663dde6.jpg?imageMogr2/auto-orient/strip|imageView2/2/w/554/format/webp)<br>

My latest favorite is leonardo_Arduino board, because the same is the use of USB, Windows, Linux, Mac and other operating systems default existence leonardo_Arduino USB interface driver, do not have to network download dedicated driver. In addition, to BADUSB burning procedures are very simple, most of the keyboard, mouse keys for simulation, easy to get started.  <br>
BadUSB is also a good example of social engineering. It plays on people's curiosity. It's estimated that more than 90% of people will want to see what's inside a USB they pick up on the side of the road.  <br><br>
![BadUSB钓鱼](https://upload-images.jianshu.io/upload_images/11477676-3d1f812778254931.png?imageMogr2/auto-orient/strip|imageView2/2/w/554/format/webp)<br>

### Tutorial  <br>
[Video address](https://www.yuque.com/u12074055/cpuceb/qicml3) <br>
Video: Introduction to BsdUSB Compiler<br>
Video: BadUSB driver installation and code writing<br>
Video: BadUSB basic operation<br>
[For detailed steps, please go to the brief book](https://www.jianshu.com/p/2b2b1dab85fe) <br>
![操作步骤](https://upload-images.jianshu.io/upload_images/11477676-390539861bec703c.png?imageMogr2/auto-orient/strip|imageView2/2/w/554/format/webp)<br>

### Directory<br>
    
    BadUSB
     │  LICENSE
     │  README.en.md
     │  README.md
     │  
     ├─AddUser_StartService
     │      AddUser_Enable3389(tools).ino
     │      AddUser_EnableFTP(tools).ino
     │      
     ├─BlueScreen
     │      BlueScreen1(DOS).ino
     │      BlueScreen2(DOS).ino
     │      BlueScreen3(DOS).ino
     │      BlueScreen_xp_win7(DOS).ino
     │      DelayedBlueScreen (DOS).ino
     │      RegistryWriteBlueScreen (DOS).ino
     │      RegistryWriteBlueScreenGeneralUse (DOS).ino
     │      
     ├─CobaltStrike_Trojanlinkage
     │  │  Bitsadmin_TrojanExecution (LinkageWithCS).ino
     │  │  Pl_TrojanExecution (LinkageWithCS).ino
     │  │  PSL_TrojanExecution (LinkageWithCS).ino
     │  │  PY_TrojanExecution (LinkageWithCS).ino
     │  │  Regsvr32_TrojanExecution (LinkageWithCS).ino
     │  │  
     │  ├─CobaltStrike_Payload
     │  │      payload.bin
     │  │      payload.c
     │  │      payload.cs
     │  │      payload.java
     │  │      payload.pl
     │  │      payload.ps1
     │  │      payload.py
     │  │      payload.rb
     │  │      payload.sct
     │  │      payload.txt
     │  │      payload.vba
     │  │      
     │  └─CounterStrikeTrojanTutorial
     │          CounterStrike.jpg
     │          CounterStrikeTutorial.png
     │          
     ├─CodePrincipleInterpretation
     │      ArduinoKeyCodeBase.ino
     │      InstructionsOn_setup_loop_Methods.txt
     │      MSF_TrojanMakingTutorial.txt
     │      
     ├─DNSHijack
     │      DOS_CommandSetMultipleDNS(DNSHijack).ino
     │      PSL_CommandSetMultipleDNS(DNSHijack).ino
     │      
     ├─Linux_Built-inReverseShell
     │      LinuxReverseShell (CodeExecution).ino
     │      LinuxReverseShell(BashShell).ino
     │      LinuxReverseShell(PerlShell).ino
     │      
     ├─MSF_Trojanlinkage
     │      shell.apk
     │      shell.asp
     │      shell.aspx
     │      shell.elf
     │      shell.exe
     │      shell.jar
     │      shell.jsp
     │      shell.macho
     │      shell.php
     │      shell.pl
     │      shell.psl
     │      shell.py
     │      shell.sh
     │      shell.war
     │      Shell_TrojanGenerationConfiguration.txt
     │      
     ├─OSX_Built-inReverseShell
     │      OSX_SystemReverseConnection (dns_shell).ino
     │      OSX_SystemReverseConnection (perl_shell).ino
     │      OSX_SystemReverseConnection (ruby_shell).ino
     │      
     ├─PSL_FullScreen-HACKED
     │  ├─FullScreenHackedv0
     │  │  │  get.ps1
     │  │  │  
     │  │  └─FullScreenHackedv
     │  │          FullScreenHackedv.ino
     │  │          
     │  ├─FullScreenHackedv2
     │  │      FullScreenHackedv2.ino
     │  │      wall.ps1
     │  │      
     │  └─FullScreenHackedv3
     │      │  get.ps1
     │      │  
     │      └─FullScreenHackedv3
     │              FullScreenHackedv3.ino
     │              
     ├─RunProgramOn_UDrive_ExpandScopeOfIntrusion
     │  ├─UdiskRun
     │  │      UdiskRun.ino
     │  │      
     │  ├─UdiskRunv2
     │  │      UdiskRunv2.ino
     │  │      
     │  └─UdiskRunv3
     │          UdiskRunv3.ino
     │          
     ├─Site_AWord_IntrusionCode
     │      AspSentenceTrojanWrite(webServerVersion).ino
     │      AspSentenceTrojanWriting(websiteServerVersion-DynamicDecoding).ino
     │      AspSentenceTrojanWriting(websiteServerVersion-ScriptEncoderEncryption).ino
     │      AspxSentenceTrojanWrite(webServerVersion OverDog_OverDShield).ino
     │      AspxSentenceTrojanWrite(webServerVersion).ino
     │      JspSentenceTrojanWritten (JSP_websiteServerUse).ino
     │      JspTrojanWrite(JSP_websiteServerUsing-non-Sentence).ino
     │      PHP_TrojanWrite(PHP_webServerUse-ClassBypass).ino
     │      PHP_TrojanWrite(PHP_webServerUse-XOR-Bypass).ino
     │      PHP_TrojanWrite(usedByPHP_websiteServer).ino
     │      
     ├─SpecificFunctionCode
     │      AddUserCode(Tools).ino
     │      Alt-f4_Loop.ino
     │      ChangePasswordOfAccountUsed+CloseSystemProcess+BlueScreen(Tool).ino
     │      EnablePSL_RemoteConnection(Tools).ino
     │      ForcedDeletionOf360Processes(Tools).ino
     │      ForceShutDownCommand(Tool).ino
     │      Hide_CMD_Window(Display).ino
     │      MouseKeepsMoving(Tools).ino
     │      OpenPort445.ino
     │      OpenSpecified_webPage.ino
     │      ShiftBackdoor.ino
     │      SimplyChangeAllUsersPasswords(TrickItem).ino
     │      SimplyShutDownMachine(TrickItem).ino
     │      TakeScreenshot_SendSpecifiedFTP_Address(Tool).ino
     │      
     ├─TrojanDownloader
     │  ├─CERTUTIL_DownLoader
     │  │      CERTUTIL_DownLoader_MSF.ino
     │  │      
     │  ├─FTP_DownLoader
     │  │      FTP_DownloadNetcat_ConnectBackToShell(TrojanAttack).ino
     │  │      
     │  ├─JAVA_DownLoader
     │  │      JavaTrojanWrite(TargetEnvironmentRunJava).ino
     │  │      server.java
     │  │      
     │  ├─PSL_DownLoader
     │  │      Downloa_PSL_Trojan-Execute_aSecondTime.ino
     │  │      LinkServer_MSF_PSL_Download.ino
     │  │      LinkServer_PSL_Download.ino
     │  │      PSL_DownLoader0.ino
     │  │      PSL_DownLoader1.ino
     │  │      PSL_DownLoader2.ino
     │  │      PSL_DownLoader3.ino
     │  │      PSL_DownLoader4.ino
     │  │      PSL_Downloader_Win&Linux_General.ino
     │  │      PSL_Writes_Bounces.ino
     │  │      
     │  └─PY_DownLoader
     │          PyShellServer.py
     │          Py_TrojanWrite(TargetEnvironmentRunPython).ino
     │          
     ├─Ubuntu_InformationGathering
     │      BasicTerminalCommandsForUbuntu(Display).ino
     │      UbuntuInformationCollectionTXT_File(Information).ino
     │      
     ├─WiFi_ConnectionTrojan
     │      ForceConnectionToSpecifiedWiFi-DownloadPSL_TrojanRun.ino
     │      
     └─WiFi_PasswordAcquisition
             WiFiPasswordCapture(tool).ino
             WiFiPasswordExport(tool).ino
        
### Demo<br>
[Video address](https://www.yuque.com/u12074055/gzgwfh/dg804t) <br>
Video: [Hardware Hacker] Control the upload through WiFi to execute, run, write HID scripts for BADUSB as well as a small extra 1<br>
Video: [Hardware Hacker] Control the upload via WiFi to execute, run, and write HID scripts for BADUSB as well as a small extra 2<br>
Video: [BADUSB Demo] U Drive Attack: Ignore any kill soft, hack your computer in 3 seconds!<br>
Video: [BADUSB Demo] Invading Square Large Screen, with Tutorial 1<br>
Video: [BADUSB Demo] Invading Square Large Screen, with Tutorial 2<br>
Video: [BADUSB demo] BADUSB implementation record keyboard<br>
Video: [BADUSB demo] Change the password of the account used + close the system process + blue screen test<br>
![演示](https://upload-images.jianshu.io/upload_images/11477676-31390e8446540ca3.jpg?imageMogr2/auto-orient/strip|imageView2/2/w/554/format/webp)<br>

### Advanced<br>
[Video address](https://www.yuque.com/u12074055/cpuceb/dm1veu) <br>
Video: Badusb&MSF linkage<br>
Video: Start BadUSB with Nethunter<br>
![进阶](https://upload-images.jianshu.io/upload_images/11477676-cc6c47da713ac2e2.jpg?imageMogr2/auto-orient/strip|imageView2/2/w/554/format/webp)<br>

### Frequently asked questions and errors<br>
[Video address](https://www.yuque.com/u12074055/cpuceb/uofha2) <br>
Video: BadUSB code writes exception handling<br>
![常见问题和错误](https://upload-images.jianshu.io/upload_images/11477676-0c90a8004d5e5420.jpg?imageMogr2/auto-orient/strip|imageView2/2/w/554/format/webp)<br>

### extension<br>
[Video address](https://www.yuque.com/u12074055/cpuceb/hs3n7p) <br>
Video: [Hardware Hacker] Nine dollars to make a BadUSB<br>
Video: [Hardware Hacker] can directly replace Big Yellow Duck and Wifiducky's new BadUSB<br>
Video: BadUSB Tutorial Digispark + Chinese BadUSB<br>
![扩展](https://upload-images.jianshu.io/upload_images/11477676-bba7de72abd2072d.jpg?imageMogr2/auto-orient/strip|imageView2/2/w/554/format/webp)<br>

### Update<br>
###### 2021.02.06 update code, part of which is the open source code searched from other enthusiasts, part of which is the method flow linked with MSF and the Arduino Leonardo basic key code that I think is better to use<br>
###### 2021.02.14 update code, gain inspiration from other good project, join the trojans, DNS hijacking CobaltStrike linkage code, Linux and osx reverse shell, WIFI connection trojans, built-in WIFI password access, website a word invasion code, PSL full-screen hacked images, running programs in the U dish _ for expanding the scope of the invasion, and realize a lot of practical function code, the valentine day is joyful!<br>
![更新](https://upload-images.jianshu.io/upload_images/11477676-a54932b08d3ef2da.jpg?imageMogr2/auto-orient/strip|imageView2/2/w/554/format/webp)<br>

### Link<br>
The code has been uploaded to GitHub and Gitee, **beg star**, other projects are also very fun, **continue to beg star**.<br>

**GitHub：** https://github.com/wangwei39120157028/BadUSB<br>

**Gitee：**  https://gitee.com/wwy2018/BadUSB<br>
