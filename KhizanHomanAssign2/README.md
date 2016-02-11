# CMSI 387 Operating System

Assignment #2
02/11/2016


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

[SSH]: https://github.com/SirSeim/cmsi387/blob/master/KhizanHomanAssign2/IO_Gymnastics_1.png


####2.Run something lengthy (ping, vm_stat/vmstat, loooooong download, finding the quadrillionth prime number…) inside screen; logout of that computer entirely, login again, and reconnect to screen to prove to yourself that the process has continued to run without interruption.

![Screen Ping][https://github.com/SirSeim/cmsi387/blob/master/KhizanHomanAssign2/Screen_ping.png]
![Screen Ping 2][https://github.com/SirSeim/cmsi387/blob/master/KhizanHomanAssign2/Screen_ping_2.png]
![Screen Ping 3][https://github.com/SirSeim/cmsi387/blob/master/KhizanHomanAssign2/Screen_ping_3.png]




