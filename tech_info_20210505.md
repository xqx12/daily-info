# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210505T08:55:20Z | CVE-2021-31856 | Null | https://github.com/ssst0n3/CVE-2021-31856 | A SQL Injection vulnerability in the REST API in Layer5 Meshery 0.5.2 allows an attacker to execute arbitrary SQL commands via the /experimental/patternfiles endpoint (order parameter in GetMesheryPatterns in models/meshery_pattern_persister.go).| 
| 20210505T04:58:52Z | CVE-2021-3156 | Null | https://github.com/ajtech-hue/CVE-2021-3156-Mitigation-ShellScript-Build | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210505T01:02:05Z | CVE-2021-0259 | Null | https://github.com/GoogleProjectZer0/CVE-2021-0259 | | 
| 20210505T01:02:01Z | CVE-2021-0257 | Null | https://github.com/GoogleProjectZer0/CVE-2021-0257 | On Juniper Networks MX Series and EX9200 Series platforms with Trio-based MPCs (Modular Port Concentrators) where Integrated Routing and Bridging (IRB) interfaces are configured and mapped to a VPLS instance or a Bridge-Domain, certain Layer 2 network events at Customer Edge (CE) devices may cause memory leaks in the MPC of Provider Edge (PE) devices which can cause an out of memory condition and MPC restart. When this issue occurs, there will be temporary traffic interruption until the MPC is restored. An administrator can use the following CLI command to monitor the status of memory usage level of the MPC: user@device> show system resource-monitor fpc FPC Resource Usage Summary Free Heap Mem Watermark : 20 % Free NH Mem Watermark : 20 % Free Filter Mem Watermark : 20 % * - Watermark reached Slot # % Heap Free RTT Average RTT 1 87 PFE # % ENCAP mem Free % NH mem Free % FW mem Free 0 NA 88 99 1 NA 89 99 When the issue is occurring, the value of “% NH mem Free” will go down until the MPC restarts. This issue affects MX Series and EX9200 Series with Trio-based PFEs (Packet Forwarding Engines), including MX-MPC1-3D, MX-MPC1E-3D, MX-MPC2-3D, MX-MPC2E-3D, MPC-3D-16XGE, and CHAS-MXxx Series MPCs. No other products or platforms are affected by this issue. This issue affects Juniper Networks Junos OS on MX Series, EX9200 Series: 17.3 versions prior to 17.3R3-S10; 17.4 versions prior to 17.4R3-S3; 18.2 versions prior to 18.2R3-S7; 18.3 versions prior to 18.3R3-S4; 18.4 versions prior to 18.4R3-S6; 19.2 versions prior to 19.2R3-S2; 19.3 versions prior to 19.3R3-S1; 19.4 versions prior to 19.4R2-S2, 19.4R3; 20.2 versions prior to 20.2R1-S3, 20.2R2; 20.3 versions prior to 20.3R1-S1,, 20.3R2. This issue does not affect Juniper Networks Junos OS: 17.3 versions prior to 17.3R3-S8; 17.4 versions prior to 17.4R3-S2; 18.1; 18.2 versions prior to 18.2R3-S4; 18.3 versions prior to 18.3R3-S2; 18.4 versions prior to 18.4R3-S1; 19.1; 19.2 versions prior to 19.2R2; 19.3 versions prior to 19.3R3; 19.4 versions prior to 19.4R2.| 
| 20210505T00:27:59Z | CVE-2021-0261 | Null | https://github.com/GoogleProjectZer0/CVE-2021-0261 | A vulnerability in the HTTP/HTTPS service used by J-Web, Web Authentication, Dynamic-VPN (DVPN), Firewall Authentication Pass-Through with Web-Redirect, and Captive Portal allows an unauthenticated attacker to cause an extended Denial of Service (DoS) for these services by sending a high number of specific requests. This issue affects: Juniper Networks Junos OS 12.3 versions prior to 12.3R12-S17 on EX Series; 12.3X48 versions prior to 12.3X48-D105 on SRX Series; 15.1 versions prior to 15.1R7-S8; 15.1X49 versions prior to 15.1X49-D230 on SRX Series; 16.1 versions prior to 16.1R7-S8; 17.4 versions prior to 17.4R2-S12, 17.4R3-S3; 18.1 versions prior to 18.1R3-S11; 18.2 versions prior to 18.2R3-S6; 18.3 versions prior to 18.3R2-S4, 18.3R3-S3; 18.4 versions prior to 18.4R2-S5, 18.4R3-S4; 19.1 versions prior to 19.1R2-S2, 19.1R3-S2; 19.2 versions prior to 19.2R1-S5, 19.2R3; 19.3 versions prior to 19.3R2-S4, 19.3R3; 19.4 versions prior to 19.4R1-S3, 19.4R2-S2, 19.4R3; 20.1 versions prior to 20.1R1-S3, 20.1R2; 20.2 versions prior to 20.2R1-S1, 20.2R2.| 
| 20210505T00:15:59Z | CVE-2021-25327 | Null | https://github.com/GoogleProjectZer0/CVE-2021-25327 | Skyworth Digital Technology RN510 V.3.1.0.4 contains a cross-site request forgery (CSRF) vulnerability in /cgi-bin/net-routeadd.asp and /cgi-bin/sec-urlfilter.asp. Missing CSRF protection in devices can lead to XSRF, as the above pages are vulnerable to cross-site scripting (XSS).| 
| 20210505T00:15:55Z | CVE-2021-25328 | Null | https://github.com/GoogleProjectZer0/CVE-2021-25328 | Skyworth Digital Technology RN510 V.3.1.0.4 RN510 V.3.1.0.4 contains a buffer overflow vulnerability in /cgi-bin/app-staticIP.asp. An authenticated attacker can send a specially crafted request to endpoint which can lead to a denial of service (DoS) or possible code execution on the device.| 
| 20210505T00:15:51Z | CVE-2021-0262 | Null | https://github.com/GoogleProjectZer0/CVE-2021-0262 | Through routine static code analysis of the Juniper Networks Junos OS software codebase, the Secure Development Life Cycle team identified a Use After Free vulnerability in PFE packet processing on the QFX10002-60C switching platform. Exploitation of this vulnerability may allow a logically adjacent attacker to trigger a Denial of Service (DoS). Continued exploitation of this vulnerability will sustain the Denial of Service (DoS) condition. This issue only affects QFX10002-60C devices. No other product or platform is vulnerable to this issue. This issue affects Juniper Networks Junos OS on QFX10002-60C: 19.1 version 19.1R3-S1 and later versions; 19.1 versions prior to 19.1R3-S3; 19.2 version 19.2R2 and later versions; 19.2 versions prior to 19.2R3-S1; 20.2 versions prior to 20.2R1-S2. This issue does not affect Juniper Networks Junos OS: versions prior to 19.1R3; 19.2 versions prior to 19.2R2; any version of 19.3; version 20.2R2 and later releases.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210505T12:20:54Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 441 | 11| 
| 20210505T01:40:45Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 11 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210505T12:22:37Z | bespoke tooling for offensive security%s Windows Usermode Exploit Dev course (OSED) | https://github.com/epi052/osed-scripts | 26 | 10| 
| 20210505T12:19:57Z | PS4 7.55 EXPLOIT HOST | https://github.com/therayner/projectcali755 | 0 | 0| 
| 20210505T12:18:56Z | A server sided anti exploit capable of handling common exploits smoothly.  | https://github.com/SilentsReplacement/BoboFighter | 5 | 2| 
| 20210505T12:16:56Z | A cheat sheet that contains common enumeration and attack methods for Windows Active Directory. | https://github.com/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet | 1597 | 397| 
| 20210505T12:16:14Z | Thi powershell script has got to run in remote windows host, even for pivoting | https://github.com/FabioDefilippo/winallenum | 2 | 1| 
| 20210505T12:14:07Z | xcube is a Python package for generating and exploiting data cubes powered by xarray, dask, and zarr. | https://github.com/dcs4cop/xcube | 74 | 13| 
| 20210505T12:12:46Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 11 | 3| 
| 20210505T12:02:46Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 22 | 9| 
| 20210505T11:46:02Z | This is an optimized and efficient scene segmentation model which exploits multi-scale feature fusion technique for capturing contextual information from the scene. This model produces less parameters and FLOPS compare to many existing real-time scene segmentation model. | https://github.com/tanmaysingha/FANet | 0 | 1| 
| 20210505T11:32:27Z | My collection of pentesting tools, notes and exploits | https://github.com/gikabyte27/Pentest | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210505T12:32:04Z | the dashboard for managing the backdoor data for the luxr system | https://github.com/EDMONDGIHOZO/luxr_dashboard | 0 | 0| 
| 20210505T12:07:44Z | Backdoor Attack in the Frequency Domain | https://github.com/FTrojanAttack/FTrojan | 0 | 0| 
| 20210505T11:43:08Z | The best backdoor scanner there is. | https://github.com/iK4oS/backdoor.exe | 1 | 1| 
| 20210505T11:12:30Z | Null | https://github.com/Hem1700/backdoor | 0 | 0| 
| 20210505T10:24:32Z | Null | https://github.com/un2verse/Backdoor | 0 | 0| 
| 20210505T09:20:29Z | ParadoxiaRat : Native Windows Remote access Tool. | https://github.com/quantumcored/paradoxiaRAT | 441 | 105| 
| 20210505T08:23:02Z | Small and convenient C2 tool for Windows targets | https://github.com/Cr4sh/MicroBackdoor | 148 | 27| 
| 20210505T04:01:10Z | Full-featured C2 framework which silently persists on webserver with a single-line PHP backdoor | https://github.com/nil0x42/phpsploit | 1261 | 343| 
| 20210505T02:30:00Z | Simple Python Backdoor | https://github.com/zNairy/Sonaris | 6 | 0| 
| 20210505T02:07:58Z | Meterpreter Encrypted Payload by C# | https://github.com/DamonMohammadbagher/NativePayload_Reverse_tcp | 132 | 64| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210505T01:16:59Z | Script to discover and trigger a buffer overflow vulnerability in applications | https://github.com/AvetisP/Fuzzer.py | 0 | 0| 
| 20210505T01:15:27Z | Fuzz testing for go. | https://github.com/google/gofuzz | 1037 | 97| 
| 20210505T00:55:30Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 67 | 15| 
| 20210505T00:53:16Z | CS 4152 Project | https://github.com/nicbarone/Fuzzy-Kiwi | 0 | 0| 
| 20210505T00:51:08Z | Null | https://github.com/paul-gomes/Neuro-Fuzzy-System | 0 | 0| 
| 20210505T00:46:04Z | Cyber ​​Lab - Protection | https://github.com/Nadavkeysar/Fuzzing | 0 | 0| 
| 20210505T00:30:30Z | Coding practice for HTML/CSS/anything else web based | https://github.com/FuzzyPumpkin/FuzzyPumpkin.github.io | 5 | 1| 
| 20210505T00:19:22Z | Null | https://github.com/rittermi/Feeling-Fuzzy | 0 | 0| 
| 20210505T00:03:41Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 278 | 37| 



# 日更新程序
