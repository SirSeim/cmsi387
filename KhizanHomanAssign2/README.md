# CMSI 387 Operating System

## Irakli Khizanishvili & Joel Homan

######Assignment #2

######02/11/2016


###Process Survey

####1. What root-owned process are running?

- To list all the _root-owned_ process within Terminal. You would need to type in the following command: **pgrep -u root -l**.

#####Output

```
49 syslogd
50 UserEventAgent
53 kextd
54 fseventsd
59 configd
60 powerd
61 SGProtocolServi
66 airportd
68 warmd
69 mds
73 TBLoopDrivePara
75 iconservicesage
76 diskarbitration
78 coreduetd
79 wdhelper
81 opendirectoryd
82 wirelessproxd
84 apsd
85 AdobeUpdateDaem
86 launchservicesd
88 securityd
93 blued
94 autofsd
100 revisiond
102 logind
103 KernelEventAgen
106 hidd
107 AirPlayXPCHelpe
108 notifyd
134 aslmanager
135 diagnosticd
137 sandboxd
138 cfprefsd
140 taskgated
141 authd
145 coreservicesd
147 com.apple.ctkpc
150 amfid
157 ctkd
159 secinitd
178 findmydeviced
179 awdd
180 networkd_privil
181 com.apple.CodeS
182 coresymbolicati
184 lsd
186 mds_stores
191 nehelper
192 ntpd
193 corestoraged
195 usbd
196 thermald
197 com.apple.ifdre
198 socketfilterfw
199 diskmanagementd
201 com.apple.Ambie
208 akd
212 CVMServer
228 com.apple.Accou
234 securityd_servi
246 WirelessRadioMa
294 CrashReporterSu
302 sharedfilelistd
305 filecoordinatio
307 systemsoundserv
313 tccd
314 watchdogd
352 deleted
353 TMCacheDelete
354 installd
370 SubmitDiagInfo
386 dbfseventsd
387 dbfseventsd
402 com.apple.Perfo
407 writeconfig
414 suhelperd
456 spindump
520 com.apple.GSSCr
622 systemstatsd
659 syspolicyd
677 sysmond
716 com.apple.audio
755 AppleCameraAssi
1048 com.apple.audio
1141 com.apple.cmio.
1395 VDCAssistant
1399 mdflagwriter
1434 system_installd
1443 periodic-wrappe
1444 periodic-wrappe
5034 nbstated
6312 ocspd
6602 login
```

####2. What processes are runnning on your account?

- To list all the processes running on my account machine, you would need to type in the following command: **pgrep -u EKO -l**. *EKO is the name of my machine. Specifically the User.

#####Output

```
101 loginwindow
235 UserEventAgent
237 distnoted
239 cfprefsd
240 CommCenter
241 lsd
245 fontd
249 identityservice
250 usernoted
251 secd
252 bird
253 swcd
256 CalendarAgent
257 mapspushd
258 SocialPushAgent
259 cloudphotosd
260 gamed
261 accountsd
262 secinitd
263 tccd
266 com.apple.Addre
268 SafariCloudHist
269 fmfd
270 CallHistorySync
273 askpermissiond
274 akd
275 nsurlstoraged
276 cloudd
277 iconservicesage
279 CalNCService
280 nsurlsessiond
281 pboard
282 sharedfilelistd
284 com.apple.Cloud
288 CloudKeychainPr
289 callservicesd
290 storeaccountd
291 imagent
292 IMDPersistenceA
293 com.apple.geod
295 useractivityd
297 EscrowSecurityA
298 photolibraryd
299 sharingd
300 CMFSyncAgent
301 ScopedBookmarkA
306 com.apple.photo
308 AssetCacheLocat
315 com.apple.sbd
316 com.apple.lakit
317 FolderActionsDi
319 spindump_agent
322 Keychain Circle
325 NotificationCen
328 icdd
329 AppleIDAuthAgen
330 ApplicationMana
334 SpotifyWebHelpe
335 AirPlayUIAgent
336 cloudpaird
339 WiFiAgent
340 diagnostics_age
343 soagent
344 Dock
346 SystemUIServer
347 Finder
348 Dropbox
351 pkd
356 Spotlight
358 storeassetd
359 SpotlightNetHel
360 WiFiProxy
361 Battery Monitor
362 com.apple.dock.
364 storeinappd
365 com.apple.notif
367 com.apple.Weath
368 storedownloadd
369 com.apple.Comme
374 CallHistoryPlug
391 dbfseventsd
397 garcon
406 ViewBridgeAuxil
409 printtool
416 storelegacy
417 LaterAgent
443 pbs
444 AppleSpell
446 com.apple.Input
454 mdflagwriter
457 USBAgent
465 PrintUITool
482 com.apple.hiser
519 suggestd
568 DataDetectorsDy
569 com.apple.Chara
573 Google Chrome
575 crashpad_handle
576 Google Chrome H
577 VTDecoderXPCSer
580 Google Chrome H
582 Google Chrome H
583 Google Chrome H
584 com.apple.Color
660 com.apple.BKAge
664 com.apple.Comme
681 cdpd
685 com.apple.Addre
688 followupd
719 DiskUnmountWatc
738 com.apple.spotl
870 Firewall
876 IMRemoteURLConn
877 recentsd
886 BezelUIServer
892 com.apple.speec
895 com.apple.audio
896 com.apple.audio
904 imklaunchagent
919 com.apple.tonel
993 reversetemplate
1349 Messages
1555 com.apple.Comme
1963 com.apple.Safar
2091 TextEdit
2882 DataclassOwners
2994 Sublime Text 2
4937 com.apple.Safar
4940 com.apple.Safar
4942 com.apple.WebKi
4949 storeuid
4951 com.apple.appst
4966 nbagent
5366 com.apple.WebKi
5492 CoreServicesUIA
5497 Preview
5498 com.apple.Previ
5499 Image Capture E
5563 Mail
5586 mdworker
5587 mdworker
5604 mdworker
5605 mdworker
6195 Google Chrome H
6274 Notes
6292 Google Chrome H
6293 Google Chrome H
6580 AirPort Base St
6599 Google Chrome H
6603 zsh
6715 Google Chrome H
6718 Google Chrome H
6824 Google Chrome H
6829 com.apple.iClou
6831 quicklookd

```

####3. Run a typical working set of applications (e.g. web browser, chat program, text editor). Which application is using the most real memory? The most virtual memory?

#####a) Application using the most real memory:

```
kernal_task

```

#####b) Application using the most virtual memory:

```
Ableton Live 9 Suite

```

#####c) Command:

```
htop 
top -o mem

```

####4. Login to http://my.cs.lmu.edu. Who else, other than root and you, has process running at that time?


#####Output

```
daemon
jhoman
ikhizani
message+
Live8
ntop
ntp
postfix
root
sshd
syslog
www-data
```
#####Command

```
ps aux | awk '{ print $1 }' | sed '1 d' | sort | uniq

```

###I/O and File "Gymanstics"

####1. Create an ssh tunnel from this computer to a service that is visible from another ssh-capable computer (but, of course, not necessarily visible from the computer you’re using). Then, access that service from your computer through localhost and the tunneled port number.  Submit a screenshot of your successful connection to the remote service via the tunnel.

![Screen Example](https://raw.githubusercontent.com/SirSeim/cmsi387/master/KhizanHomanAssign2/IO_Gymnastics_1.png)

####2. Run something lengthy (ping, vm_stat/vmstat, loooooong download, finding the quadrillionth prime number…)inside screen; logout of that computer entirely, login again, and reconnect to screen to prove to yourself that the process has continued to run without interruption.

![Screen Ping](https://raw.githubusercontent.com/SirSeim/cmsi387/master/KhizanHomanAssign2/Screen_ping.png)
![Screen Ping 2](https://raw.githubusercontent.com/SirSeim/cmsi387/master/KhizanHomanAssign2/Screen_ping_2.png)
![Screen Ping 3](https://raw.githubusercontent.com/SirSeim/cmsi387/master/KhizanHomanAssign2/Screen_ping_3.png)


####3. Learn how to use du, which tells you how much disk space you’re using in a given directory.
a. Which first-level subdirectory in ~ is taking up the most space? Submit the command that includes this information in as little output as possible.

```
du –sh * | sort –rn | head -1

```
b. Submit a command that displays only the disk usage of directories matching some regular expression. Hint: |.

```
du –h * | grep homework

```

####4. On a Keck lab machine, create a file within ~. Run ls -i to determine that file’s inode number. Move this file to another directory inside ~, then move it to /tmp, then move it back to your home directory. After each move, use ls -i to see its inode number.

a. Submit the output of ls -i both right after you created the file and after each file move.

![LS](https://raw.githubusercontent.com/SirSeim/cmsi387/master/KhizanHomanAssign2/LS.png)

b. Submit the piped commands that you would type in order to filter out all lines of ls -i’s output except for the file that you created.

```
ls –i | grep myFile.txt

```

####5. Pop a few storage devices (CD, DVD, flash drive, network drive, etc.) into your computer. Figure out the mount points for each device.

I plugged in an external hard drive titled NO_NAME (listed on the bottom).  Its mount point is /Volumes/NO_NAME.

![mount](https://raw.githubusercontent.com/SirSeim/cmsi387/master/KhizanHomanAssign2/mount.png)

###CSI: OS

####Pre-OS Software:

![mount](https://raw.githubusercontent.com/SirSeim/cmsi387/master/KhizanHomanAssign2/preos.png)

####Kernel Files:

```
total 0
drwxr-xr-x  286 root  wheel  9724 Feb  9 10:31 .
drwxr-xr-x   79 root  wheel  2686 Feb  9 20:19 ..
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:06 ALF.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMD2400Controller.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMD2600Controller.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMD3800Controller.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMD4600Controller.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMD4800Controller.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMD5000Controller.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMD6000Controller.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMD7000Controller.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMD8000Controller.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMD9000Controller.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMDFramebuffer.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMDMTLBronzeDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMDRadeonVADriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMDRadeonX3000.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMDRadeonX3000GLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMDRadeonX4000.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMDRadeonX4000GLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMDShared.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AMDSupport.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 ATIRadeonX2000.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:39 ATIRadeonX2000GA.plugin
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 ATIRadeonX2000GLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 ATIRadeonX2000VADriver.bundle
drwxr-xr-x    3 root  wheel   102 Jan 12  2014 ATTOiSCSI.kext
drwxr-xr-x    3 root  wheel   102 Oct 16  2013 AVFrameBuffer.kext
drwxr-xr-x    3 root  wheel   102 Oct 16  2013 AVVideoCard.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:25 Apple16X50Serial.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:35 AppleACPIPlatform.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:29 AppleAHCIPort.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 AppleAPIC.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:26 AppleBMC.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:33 AppleBacklight.kext
drwxr-xr-x@   6 root  wheel   204 Feb  3 07:25 AppleBacklightExpert.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:27 AppleBluetoothMultitouch.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:10 AppleBluetoothRemote.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:04 AppleCameraInterface.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 AppleCredentialManager.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:03 AppleEFIRuntime.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 AppleFDEKeyStore.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 AppleFIVRDriver.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:03 AppleFSCompressionTypeDataless.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:03 AppleFSCompressionTypeZlib.kext
drwxr-xr-x@   3 root  wheel   102 Aug 22 16:28 AppleFWAudio.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 AppleFileSystemDriver.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:03 AppleGraphicsControl.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:27 AppleGraphicsPowerManagement.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:11 AppleHDA.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:27 AppleHIDKeyboard.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:27 AppleHIDMouse.kext
drwxr-xr-x@   3 root  wheel   102 Jun 28  2015 AppleHIDTransport.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:07 AppleHPET.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:28 AppleHPM.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:28 AppleHSSPIHIDDriver.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:28 AppleHSSPISupport.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 AppleHV.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:03 AppleHWSensor.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:14 AppleIRController.kext
drwxr-xr-x@   3 root  wheel   102 Jun 28  2015 AppleInputDeviceSupport.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelBDWGraphics.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelBDWGraphicsFramebuffer.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelBDWGraphicsGLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:20 AppleIntelBDWGraphicsMTLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelBDWGraphicsVADriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelBDWGraphicsVAME.bundle
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:03 AppleIntelCPUPowerManagement.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 AppleIntelCPUPowerManagementClient.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelFramebufferAzul.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelFramebufferCapri.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:20 AppleIntelGraphicsShared.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 AppleIntelHD3000Graphics.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:39 AppleIntelHD3000GraphicsGA.plugin
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 AppleIntelHD3000GraphicsGLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 AppleIntelHD3000GraphicsVADriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelHD4000Graphics.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelHD4000GraphicsGLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:20 AppleIntelHD4000GraphicsMTLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelHD4000GraphicsVADriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelHD5000Graphics.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelHD5000GraphicsGLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:20 AppleIntelHD5000GraphicsMTLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelHD5000GraphicsVADriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 AppleIntelHDGraphics.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 AppleIntelHDGraphicsFB.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:39 AppleIntelHDGraphicsGA.plugin
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 AppleIntelHDGraphicsGLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 AppleIntelHDGraphicsVADriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelHSWVA.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:22 AppleIntelIVBVA.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:25 AppleIntelLpssDmac.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:25 AppleIntelLpssGspi.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:25 AppleIntelLpssI2C.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:25 AppleIntelLpssI2CController.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:25 AppleIntelLpssSpiController.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:25 AppleIntelLpssUART.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 AppleIntelMCEReporter.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:26 AppleIntelPCHPMC.kext
drwxr-xr-x@   3 root  wheel   102 Oct 13 18:40 AppleIntelSKLGraphics.kext
drwxr-xr-x@   3 root  wheel   102 Oct 13 18:40 AppleIntelSKLGraphicsFramebuffer.kext
drwxr-xr-x@   3 root  wheel   102 Oct 13 18:40 AppleIntelSKLGraphicsGLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Oct 13 18:38 AppleIntelSKLGraphicsMTLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Oct 13 18:40 AppleIntelSKLGraphicsVADriver.bundle
drwxr-xr-x@   3 root  wheel   102 Oct 13 18:40 AppleIntelSKLGraphicsVAME.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 AppleIntelSNBGraphicsFB.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 AppleIntelSNBVA.bundle
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 AppleIntelSlowAdaptiveClocking.kext
drwxr-xr-x@   3 root  wheel   102 Nov 12 10:45 AppleKextExcludeList.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 AppleKeyStore.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:08 AppleKeyswitch.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:27 AppleLPC.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:29 AppleLSIFusionMPT.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:11 AppleMCCSControl.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:29 AppleMCP89RootPortPM.kext
drwxr-xr-x@   3 root  wheel   102 Aug 22 16:24 AppleMIDIBluetoothDriver.plugin
drwxr-xr-x@   3 root  wheel   102 Aug 22 16:26 AppleMIDIFWDriver.plugin
drwxr-xr-x@   3 root  wheel   102 Aug 22 16:23 AppleMIDIIACDriver.plugin
drwxr-xr-x@   3 root  wheel   102 Aug 22 16:24 AppleMIDIRTPDriver.plugin
drwxr-xr-x@   3 root  wheel   102 Aug 22 16:23 AppleMIDIUSBDriver.plugin
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 AppleMatch.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:06 AppleMikeyHIDDriver.kext
drwxr-xr-x    3 root  wheel   102 Sep 12  2014 AppleMobileDevice.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 AppleMobileFileIntegrity.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:03 AppleMultitouchDriver.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:14 AppleOSXUSBNCM.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:25 AppleOSXWatchdog.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:03 ApplePlatformEnabler.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:07 AppleRAID.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:31 AppleRAIDCard.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:07 AppleRTC.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:26 AppleSDXC.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 19:12 AppleSEP.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:08 AppleSMBIOS.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:26 AppleSMBusController.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:26 AppleSMBusPCI.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:07 AppleSMC.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:34 AppleSMCLMU.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 AppleSRP.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 AppleSmartBatteryManager.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:21 AppleStorageDrivers.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:07 AppleThunderboltDPAdapters.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:08 AppleThunderboltEDMService.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:26 AppleThunderboltIP.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:26 AppleThunderboltNHI.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:25 AppleThunderboltPCIAdapters.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 19:12 AppleThunderboltUTDM.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:31 AppleTopCase.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:26 AppleTyMCEDriver.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:15 AppleUSBACM.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:08 AppleUSBAudio.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:15 AppleUSBCDC.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:15 AppleUSBDMM.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:15 AppleUSBDisplays.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:15 AppleUSBECM.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:15 AppleUSBEEM.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:16 AppleUSBEthernet.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:07 AppleUSBEthernetHost.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:08 AppleUSBFTDI.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:14 AppleUSBMultitouch.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:15 AppleUSBNCM.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:16 AppleUSBNetworking.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:15 AppleUSBTopCase.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:15 AppleUSBWCM.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:29 AppleUpstreamUserClient.kext
drwxr-xr-x@   3 root  wheel   102 Aug 28 19:37 AppleVADriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:16 AppleWWANAutoEject.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:11 AppleXsanScheme.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:29 Apple_iSight.kext
drwxr-xr-x@   6 root  wheel   204 Feb  3 07:25 AudioAUUC.kext
drwxr-xr-x    3 root  wheel   102 May 23  2012 BJUSBLoad.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:03 BootCache.kext
drwxr-xr-x    3 root  wheel   102 Sep  5  2013 CUDA.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:07 CellPhoneHelper.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 CoreCaptureResponder.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 CoreStorage.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 DSACL.ppp
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 DSAuth.ppp
drwxr-xr-x@   3 root  wheel   102 Aug 22 18:48 DVFamily.bundle
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:11 Dont Steal Mac OS X.kext
drwxr-xr-x    3 root  wheel   102 May 10  2013 DroboTBT.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 EAP-KRB.ppp
drwxr-xr-x@   3 root  wheel   102 Aug 22 16:12 EAP-RSA.ppp
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 EAP-TLS.ppp
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:24 GeForce.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:24 GeForceAIRPlugin.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:39 GeForceGA.plugin
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:24 GeForceGLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:24 GeForceMTLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 GeForceTesla.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 GeForceTeslaGLDriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 GeForceTeslaVADriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:24 GeForceVADriver.bundle
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:25 IO80211Family.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 IOACPIFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:11 IOAHCIFamily.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:29 IOATAFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 19:12 IOAVBFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 19:12 IOAccelerator2D.plugin
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:33 IOAcceleratorFamily.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:33 IOAcceleratorFamily2.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:10 IOAudioFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:10 IOBDStorageFamily.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:18 IOBluetoothFamily.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:18 IOBluetoothHIDDriver.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:11 IOCDStorageFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 IODVDStorageFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 22 16:01 IOFireWireAVC.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:25 IOFireWireFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:07 IOFireWireIP.kext
drwxr-xr-x@   3 root  wheel   102 Aug 22 16:03 IOFireWireSBP2.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 19:12 IOFireWireSerialBusProtocolTransport.kext
drwxr-xr-x@   6 root  wheel   204 Feb  3 07:25 IOGraphicsFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 IOHDIXController.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 IOHIDFamily.kext
drwxr-xr-x@   6 root  wheel   204 Feb  3 07:25 IONDRVSupport.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:26 IONVMeFamily.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:25 IONetworkingFamily.kext
drwxr-xr-x@   6 root  wheel   204 Feb  3 07:25 IOPCIFamily.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:20 IOPlatformPluginFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 IOReportFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 19:11 IOSCSIArchitectureModelFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 19:12 IOSCSIParallelFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 IOSMBusFamily.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:14 IOSerialFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:03 IOSlowAdaptiveClockingFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:08 IOStorageFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:03 IOStreamFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 19:10 IOSurface.kext
drwxr-xr-x@   3 root  wheel   102 Aug 22 16:03 IOThunderboltFamily.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 19:12 IOTimeSyncFamily.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:15 IOUSBAttachedSCSI.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:14 IOUSBFamily.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:03 IOUSBHostFamily.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:12 IOUSBMassStorageClass.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:07 IOUSBMassStorageDriver.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:07 IOUserEthernet.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:33 IOVideoFamily.kext
drwxr-xr-x    3 root  wheel   102 May 22  2012 JMicronATA.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 L2TP.ppp
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:08 Libm.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:24 NVDAGF100Hal.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:24 NVDAGK100Hal.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 NVDANV50HalTesla.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:24 NVDAResman.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:40 NVDAResmanTesla.kext
drwxr-xr-x@   3 root  wheel   102 Sep 16 18:24 NVDAStartup.kext
drwxr-xr-x@   3 root  wheel   102 Aug 22 16:01 NVMeSMARTLib.plugin
drwxr-xr-x@   3 root  wheel   102 Sep 16 17:25 NVSMU.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:08 OSvKernDSPLib.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 PPP.kext
drwxr-xr-x@   3 root  wheel   102 Aug 22 16:03 PPPSerial.ppp
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 PPPoE.ppp
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 PPTP.ppp
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:15 Quarantine.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 Radius.ppp
drwxr-xr-x@   3 root  wheel   102 Mar 26  2015 RemoteVirtualInterface.kext
drwxr-xr-x@   3 root  wheel   102 Aug 22 16:11 SMARTLib.plugin
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 SMCMotionSensor.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:10 Sandbox.kext
drwxr-xr-x    3 root  wheel   102 Aug  6  2012 Soundflower.kext
drwxr-xr-x@   6 root  wheel   204 Feb  3 07:25 System.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:03 TMSafetyNet.kext
drwxr-xr-x    3 root  wheel   102 May 10  2013 TrustedDataSCSIDriver.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 19:17 acfs.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 19:17 acfsctl.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 autofs.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 cd9660.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:14 cddafs.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 corecapture.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:04 corecrypto.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:03 exfat.kext
drwxr-xr-x    3 root  wheel   102 Aug 14  2013 hp_Deskjet_io_enabler.kext
drwxr-xr-x    3 root  wheel   102 Aug 14  2013 hp_fax_io.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 19:13 iPodDriver.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 mcxalr.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 msdosfs.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 ntfs.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 pmtelemetry.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 pthread.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:08 smbfs.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 triggers.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:05 udf.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:09 vecLib.kext
drwxr-xr-x@   3 root  wheel   102 Aug 27 18:15 webcontentfilter.kext
drwxr-xr-x@   3 root  wheel   102 Aug 26 17:03 webdav_fs.kext

```

####Startup Items:

```
total 0
drwxr-xr-x   3 root  wheel   102 Oct 12 08:50 .
drwxr-xr-x  79 root  wheel  2686 Feb  9 20:19 ..
drwxr-xr-x   4 root  wheel   136 May 22  2013 CUDA
```


####The "First Process"
![firstprocess](https://raw.githubusercontent.com/SirSeim/cmsi387/master/KhizanHomanAssign2/firstprocess.png)


####Network Settings

![network](https://raw.githubusercontent.com/SirSeim/cmsi387/master/KhizanHomanAssign2/network.png)