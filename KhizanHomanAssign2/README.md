# CMSI 387 Operating System

Assignment #2
02/11/2016


###Process Survey

1. What root-owned process are running?

- To list all the _root-owned_ process within Terminal. You would need to type in the following command: **pgrep -u root -l**.

####Output

``
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
``