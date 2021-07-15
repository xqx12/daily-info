# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210714 | BruteShark - 用于分析网络流量的工具，支持从中提取密码、认证 Hash、DNS 记录等信息 | https://github.com/odedshimon/BruteShark| 
| 20210714 | Revil 勒索软件攻击 Kaseya VSA Server RCE 漏洞的细节分析 | https://blog.truesec.com/2021/07/06/kaseya-vsa-zero-day-exploit/| 
| 20210714 | 2194 - Windows: CreateProcessWithLogon Write Restricted Service EoP - project-zero | https://bugs.chromium.org/p/project-zero/issues/detail?id=2194| 
| 20210714 | Part 2: Dive into Zoom Applications | https://rakesh-thodupunoori.medium.com/part-2-dive-into-zoom-applications-1b01091345c1| 
| 20210714 | 研究员 Axel Souchet 开源了一个基于快照的用于 Fuzz Windows 用户态程序和内核的 Fuzzer，支持代码覆盖率收集和分布式部署 | https://github.com/0vercl0k/wtf| 
| 20210714 | 微软今天发布 7 月份漏洞补丁，修复 116 个漏洞，其中 3 个已被野外利用 | https://threatpost.com/microsoft-crushes-116-bugs/167764/| 
| 20210714 | DLL Side-Loading Technique Used in the Recent Kaseya Ransomware Attack | https://www.fortinet.com/blog/threat-research/dll-side-loading-technique-used-in-recent-kaseya-ransomware-attack?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+fortinet%2Fblog%2Fthreat-research+%28Fortinet+Threat+Research+Blog%29| 
| 20210714 | Quarkslab 对 WinDefender Network Inspection 驱动实现机制的研究 | https://blog.quarkslab.com/guided-tour-inside-windefenders-network-inspection-driver.html| 
| 20210714 | Windows Hello Bypass Fools Biometrics Safeguards in PCs | https://threatpost.com/windows-hello-bypass-biometrics-pcs/167771/| 
| 20210714 | 基于软件故障注入对策的替代方法(Part 3/3) | https://research.nccgroup.com/2021/07/09/alternative-approaches-for-fault-injection-countermeasures-part-3-3/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210714T21:51:24Z | CVE-2021-1675 | C# and Impacket implementation of PrintNightmare CVE-2021-1675/CVE-2021-34527 | https://github.com/cube0x0/CVE-2021-1675 | Windows Print Spooler Elevation of Privilege Vulnerability| 
| 20210714T19:20:24Z | CVE-2021-30461 | Null | https://github.com/puckiestyle/CVE-2021-30461 | A remote code execution issue was discovered in the web UI of VoIPmonitor before 24.61. When the recheck option is used, the user-supplied SPOOLDIR value (which might contain PHP code) is injected into config/configuration.php.| 
| 20210714T17:17:39Z | CVE-2021-3560 | Null | https://github.com/secnigma/CVE-2021-3560-Polkit-Privilege-Esclation | 未查询到CVE信息| 
| 20210714T15:08:58Z | cve-2021-34558 | Null | https://github.com/alexzorin/cve-2021-34558 | 未查询到CVE信息| 
| 20210714T12:57:40Z | CVE-2021-50126 | Null | https://github.com/hacker-ali-17/CVE-2021-50126 | 未查询到CVE信息| 
| 20210714T06:42:35Z | CVE-2020-0796 | Null | https://github.com/1stPeak/CVE-2020-0796-Scanner | A remote code execution vulnerability exists in the way that the Microsoft Server Message Block 3.1.1 (SMBv3) protocol handles certain requests, aka %Windows SMBv3 Client/Server Remote Code Execution Vulnerability%.| 
| 20210714T05:29:08Z | CVE-2020-15368 | How to exploit a vulnerable windows driver. Exploit for AsrDrv104.sys | https://github.com/stong/CVE-2020-15368 | AsrDrv103.sys in the ASRock RGB Driver does not properly restrict access from user space, as demonstrated by triggering a triple fault via a request to zero CR3.| 
| 20210714T04:43:00Z | CVE-2021-10086 | Null | https://github.com/Mochican/CVE-2021-10086 | 未查询到CVE信息| 
| 20210714T02:26:53Z | CVE-2020-1938 | Scanner for CVE-2020-1938 | https://github.com/yukiNeko114514/CVE-2020-1938 | When using the Apache JServ Protocol (AJP), care must be taken when trusting incoming connections to Apache Tomcat. Tomcat treats AJP connections as having higher trust than, for example, a similar HTTP connection. If such connections are available to an attacker, they can be exploited in ways that may be surprising. In Apache Tomcat 9.0.0.M1 to 9.0.0.30, 8.5.0 to 8.5.50 and 7.0.0 to 7.0.99, Tomcat shipped with an AJP Connector enabled by default that listened on all configured IP addresses. It was expected (and recommended in the security guide) that this Connector would be disabled if not required. This vulnerability report identified a mechanism that allowed: - returning arbitrary files from anywhere in the web application - processing any file in the web application as a JSP Further, if the web application allowed file upload and stored those files within the web application (or the attacker was able to control the content of the web application by some other means) then this, along with the ability to process a file as a JSP, made remote code execution possible. It is important to note that mitigation is only required if an AJP port is accessible to untrusted users. Users wishing to take a defence-in-depth approach and block the vector that permits returning arbitrary files and execution as JSP may upgrade to Apache Tomcat 9.0.31, 8.5.51 or 7.0.100 or later. A number of changes were made to the default AJP Connector configuration in 9.0.31 to harden the default configuration. It is likely that users upgrading to 9.0.31, 8.5.51 or 7.0.100 or later will need to make small changes to their configurations.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210714T19:21:56Z | Null | https://github.com/JaimePSantos/ResearchKlee | 0 | 0| 
| 20210714T17:06:49Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1729 | 498| 
| 20210714T08:40:08Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 161 | 15| 
| 20210714T06:19:45Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 216 | 35| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210714T02:13:53Z | GUI Configuration tool for WIZnet serial to ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool-GUI | 13 | 8| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210714T23:36:02Z | Choose a recent exploit and setup a VM that is vulnerable to the exploit. Write a tutorial about how to execute the exploit, and/or how to defend against it. | https://github.com/EmmaFeaga/Exploit-Tutorial | 1 | 0| 
| 20210714T23:21:15Z | C2X - C2/Post-Exploitation For Red Teaming and Ethical Hacking | https://github.com/nxenon/c2x | 2 | 1| 
| 20210714T22:57:50Z | Null | https://github.com/jeffkwiat/lacework-exploits | 0 | 0| 
| 20210714T22:55:22Z | Exploit for nostromo <= 1.9.6. This exploit has the functionality of being able to have an interactive shell | https://github.com/c0rnf13ld/nostromo-exploit-integrated-shell | 0 | 0| 
| 20210714T22:32:24Z | Purple Fox Plus Stealer, Purple Fox Plus Stealer, all chromium and gecko based browser and many more features. serverless stealer. | https://github.com/exploitblizzard/PurpleFoxPlus-Stealer | 0 | 0| 
| 20210714T21:56:05Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9711 | 1598| 
| 20210714T21:23:54Z | Une liste d%exploits, simples à utiliser. | https://github.com/billythegoat356/Exploits | 0 | 0| 
| 20210714T21:18:19Z | Various techniques for exploiting Windows | https://github.com/billchaison/Windows-Trix | 6 | 0| 
| 20210714T21:15:06Z | Modular penetration testing platform that enables you to write, test, and execute exploit code. | https://github.com/EntySec/HatSploit | 70 | 27| 
| 20210714T21:00:05Z | Null | https://github.com/yuno-dev/Discord-Voice-Exploit | 1 | 1| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210714T23:13:17Z | Null | https://github.com/Wiilldd/backdoor | 0 | 0| 
| 20210714T21:05:27Z | if check(VALUE_NAME) then attach() return end notify(%Backdoor Made Sucess%) end | https://github.com/LuckyD0e001/Backdoor-Checker-ROBLOX | 0 | 0| 
| 20210714T20:57:11Z | Null | https://github.com/Pramodh-G/MalwareBackdoors | 0 | 0| 
| 20210714T20:27:53Z | ash backdoor for LEGO® MINDSTORMS® EV3 | https://github.com/Ljabert/ev3-backdoor | 0 | 0| 
| 20210714T17:44:09Z | Script written in Python to detect and exploit the ICSA-17-124-01 vulnerability, also known as Hikvision Camera Backdoor.  | https://github.com/fracergu/HIKSCript | 0 | 0| 
| 20210714T17:19:49Z | A sample app to demonstrate how to create Xamarin UITests using the Page Object architecture, Backdoor Methods and App Links (aka Deep Linking) | https://github.com/brminnick/UITestSampleApp | 36 | 27| 
| 20210714T17:16:08Z | A python-based backdoor tool | https://github.com/M15AkaSi21n/SirinCat | 0 | 0| 
| 20210714T16:31:39Z | a Minecraft Client with Built in baritone PVP and more. Similar to Enertia, and Future. Specail Elytra Flight Access, & Backdoor Tools  | https://github.com/DrandevJC/Drandev-Client | 1 | 0| 
| 20210714T16:08:45Z | Installs a persistent backdoor binary on android devices with unlocked bootloader via TWRP that runs as system daemon with root permissions and without SELinux restrictions | https://github.com/LuigiVampa92/unlocked-bootloader-backdoor-demo | 5 | 2| 
| 20210714T14:26:27Z | A collection of python written hacking tools consisting of network scanner, arp spoofer and detector, dns spoofer, code injector, packet sniffer, network jammer, email sender, downloader, wireless password harvester credential harvester, keylogger, download&execute, and reverse_backdoor. | https://github.com/dmdhrumilmistry/pyhtools | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210714T19:43:05Z | A tool for generating nonlinear numerical invariants for C and Java programs.  DIG uses dynamic analysis to infer invariants over program execution traces and applies symbolic execution to inferred invariants. | https://github.com/unsat/dig | 4 | 4| 
| 20210714T18:48:10Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 14 | 3| 
| 20210714T17:40:53Z | A symbolic execution engine which works on a subset of RISC-V (compiled from a subset of C). | https://github.com/aabyaneh/ase_artifact | 0 | 0| 
| 20210714T17:09:19Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2385 | 351| 
| 20210714T17:06:49Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1729 | 498| 
| 20210714T15:49:42Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 147 | 33| 
| 20210714T05:19:16Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 439 | 67| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210714T18:32:46Z | A penetration testing tool for finding file upload bugs (NDSS 2020) | https://github.com/WSP-LAB/FUSE | 158 | 36| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210714T23:48:39Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6482 | 1315| 
| 20210714T23:25:25Z | JQF + Zest: Coverage-guided semantic fuzzing for Java. | https://github.com/rohanpadhye/JQF | 381 | 56| 
| 20210714T23:03:21Z | AOSP Service Fuzzing | https://github.com/rnd4u-org/aospfuz | 0 | 1| 
| 20210714T22:59:37Z | Null | https://github.com/cinzfurz/fuzzenapi | 0 | 0| 
| 20210714T22:52:59Z | Null | https://github.com/shobensack/fuzzy_sweater_main | 0 | 0| 
| 20210714T22:39:01Z | Fuzzy Extractors in Java | https://github.com/ThexXTURBOXx/FuzzyExtractors | 1 | 0| 
| 20210714T22:29:50Z | Null | https://github.com/parsegraph/fuzzyequals | 0 | 0| 
| 20210714T21:26:28Z | Null | https://github.com/jerop/fuzzton | 0 | 0| 
| 20210714T21:14:22Z | A fuzzing management tools collection | https://github.com/MozillaSecurity/FuzzManager | 153 | 48| 
| 20210714T21:04:38Z | Null | https://github.com/amitk0693/Possibilistic-Fuzzy-Neural-Gas | 0 | 0| 



# 日更新程序
