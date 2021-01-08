# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210108 | V8 引擎 CVE-2020-16040 漏洞的分析 | https://faraz.faith/2021-01-07-cve-2020-16040-analysis/| 
| 20210108 | 有研究员公开了一个 Fuzz macOS GPU 相关模块的 Fuzzer | https://github.com/astarasikov/macos-gpu-fuzzing-public| 
| 20210108 | 用侧信道的方式还原 Google Titan Security Key | https://ninjalab.io/wp-content/uploads/2021/01/a_side_journey_to_titan.pdf| 
| 20210108 | ClearSky 安全团队对 Kremlin 攻击行动的分析报告 | https://www.clearskysec.com/operation-kremlin/| 
| 20210108 | Google 开源一个 Binary Ninja 的插件，用于对高通骁龙 CPU 处理器的支持 | https://github.com/google/binja-hexagon| 
| 20210108 | Sandboxing vs. Elevated Browsing (As Administrator) | https://textslashplain.com/2021/01/07/sandboxing-vs-elevated-browsing-as-administrator/| 
| 20210108 | 从 VMware Flings 中提取部分 VMware Workstation/ESXi 的调试符号 | https://www.thezdi.com/blog/2021/1/6/mindshare-analysis-of-vmware-workstation-and-esxi-using-debug-symbols-from-flings| 
| 20210108 | Apple M1 SoC 技术概览 | https://gts3.org/2021/overview-of-apple-m1-soc.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210108 | 浅析开源蜜罐识别与全网测绘 | https://mp.weixin.qq.com/s/hq-z2HBGz3nehnCVg_H-RQ| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210108T11:45:49Z | CVE-2020-17519 | Apache Flink 目录遍历漏洞批量检测 (CVE-2020-17519) | https://github.com/B1anda0/CVE-2020-17519 | A change introduced in Apache Flink 1.11.0 (and released in 1.11.1 and 1.11.2 as well) allows attackers to read any file on the local filesystem of the JobManager through the REST interface of the JobManager process. Access is restricted to files accessible by the JobManager process. All users should upgrade to Flink 1.11.3 or 1.12.0 if their Flink instance(s) are exposed. The issue was fixed in commit b561010b0ee741543c3953306037f00d7a9f0801 from apache/flink:master.| 
| 20210108T10:26:51Z | CVE-2020-0001 | POC to run system component in an untrusted-app process | https://github.com/Zachinio/CVE-2020-0001 | In getProcessRecordLocked of ActivityManagerService.java isolated apps are not handled correctly. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation. Product: Android Versions: Android-8.0, Android-8.1, Android-9, and Android-10 Android ID: A-140055304| 
| 20210108T10:18:02Z | CVE-2020-25498 | Stored XSS via CSRF in Beetel 777VR1 Router  | https://github.com/the-girl-who-lived/CVE-2020-25498 | Cross Site Scripting (XSS) vulnerability in Beetel router 777VR1 can be exploited via the NTP server name in System Time and %Keyword% in URL Filter.| 
| 20210108T08:49:39Z | 未知编号 | 2020l4web-campaign-DanCvejn created by GitHub Classroom | https://github.com/pslib-cz/2020l4web-campaign-DanCvejn | 未查询到CVE信息| 
| 20210108T08:47:41Z | CVE-2020-11851 | Remote Code Execution vulnerability on ArcSight Logger | https://github.com/ch1nghz/CVE-2020-11851 | Arbitrary code execution vulnerability on Micro Focus ArcSight Logger product, affecting all version prior to 7.1.1. The vulnerability could be remotely exploited resulting in the execution of arbitrary code.| 
| 20210108T06:55:55Z | CVE-2020-17519 | CVE-2020-17519 | https://github.com/hoanx4/CVE-2020-17519 | A change introduced in Apache Flink 1.11.0 (and released in 1.11.1 and 1.11.2 as well) allows attackers to read any file on the local filesystem of the JobManager through the REST interface of the JobManager process. Access is restricted to files accessible by the JobManager process. All users should upgrade to Flink 1.11.3 or 1.12.0 if their Flink instance(s) are exposed. The issue was fixed in commit b561010b0ee741543c3953306037f00d7a9f0801 from apache/flink:master.| 
| 20210108T06:49:53Z | 未知编号 | 2020一些漏洞 | https://github.com/r0eXpeR/CVE-2020 | 未查询到CVE信息| 
| 20210108T06:43:14Z | CVE-2020-17530 | Null | https://github.com/uzzzval/CVE-2020-17530 | | 
| 20210108T03:41:15Z | CVE-2020-29583 | Scanner for Zyxel products which are potentially vulnerable due to an undocumented user account (CVE-2020-29583) | https://github.com/2d4d/scan_CVE-2020-29583 | Firmware version 4.60 of Zyxel USG devices contains an undocumented account (zyfwp) with an unchangeable password. The password for this account can be found in cleartext in the firmware. This account can be used by someone to login to the ssh server or web interface with admin privileges.| 
| 20210108T01:40:02Z | CVE-2020-3452 | CISCO CVE-2020-3452 Scanner & Exploiter | https://github.com/darklotuskdb/CISCO-CVE-2020-3452-Scanner-Exploiter | A vulnerability in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct directory traversal attacks and read sensitive files on a targeted system. The vulnerability is due to a lack of proper input validation of URLs in HTTP requests processed by an affected device. An attacker could exploit this vulnerability by sending a crafted HTTP request containing directory traversal character sequences to an affected device. A successful exploit could allow the attacker to view arbitrary files within the web services file system on the targeted device. The web services file system is enabled when the affected device is configured with either WebVPN or AnyConnect features. This vulnerability cannot be used to obtain access to ASA or FTD system files or underlying operating system (OS) files.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210108T09:27:22Z | Null | https://github.com/OleDakotaJoe/peachy-kleen | 0 | 0| 
| 20210108T01:37:22Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1596 | 479| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210108T07:54:56Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 89 | 22| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210108T12:49:39Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 7 | 4| 
| 20210108T12:39:47Z | Exploit hub UI | https://github.com/GameLoaded-Entertainment/UI-Library | 0 | 0| 
| 20210108T12:26:57Z | Very simple script(s) to hasten binary exploit creation | https://github.com/152334H/pwnscripts | 32 | 2| 
| 20210108T12:23:21Z | best exploit ever maked for roblox! | https://github.com/TROJAN-Virus/Vexar-X | 0 | 0| 
| 20210108T12:23:13Z | The best tool for finding one gadget RCE in libc.so.6 | https://github.com/david942j/one_gadget | 1266 | 109| 
| 20210108T12:20:43Z | Null | https://github.com/arda6/ProfExploiter | 0 | 0| 
| 20210108T12:14:35Z | Rex library for various exploitation helpers | https://github.com/rapid7/rex-exploitation | 13 | 29| 
| 20210108T12:14:29Z | Null | https://github.com/YossiSassi/ZeroLogon-Exploitation-Check | 3 | 0| 
| 20210108T11:56:14Z | Documentation of the HTB exploits | https://github.com/nic126/HTBWalktrough | 0 | 0| 
| 20210108T11:35:15Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 8870 | 1406| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210108T11:14:02Z | Null | https://github.com/mpandya18/Image_Permutator_For_Backdoor_Generation | 0 | 0| 
| 20210108T09:30:48Z | Information This tool is for educational purpose only, usage of TheFatRat for attacking targets without prior mutual consent is illegal. Developers assume no liability and are not responsible for any misuse or damage cause by this program.  Features ! Fully Automating MSFvenom & Metasploit. Local or remote listener Generation. Easily Make Backdoor by category Operating System. Generate payloads in Various formats. Bypass anti-virus backdoors. File pumper that you can use for increasing the size of your files. The ability to detect external IP & Interface address . Automatically creates AutoRun files for USB / CDROM exploitation But it%s shit! And your implementation sucks! Yes, you%re probably correct. Feel free to %Not use it% and there is a pull button to %Make it better%. Installation Instructions on how to install TheFatRat  git clone https://github.com/Screetsec/TheFatRat.git cd TheFatRat chmod +x setup.sh && ./setup.sh Update cd TheFatRat ./update && chmod +x setup.sh && ./setup.sh Troubleshoot on TheFatRat chk_tools script to use in case of problems in setup.sh of fatrat this script will check if everything is in the right version to run fatrat and will also provide you a solution for the problem  cd TheFatRat chmod +x chk_tools  ./chk_tools | https://github.com/nyctophile6/TheFatRat | 0 | 0| 
| 20210108T08:45:06Z | Null | https://github.com/rensx5514/BackdoorAttackNN-Pro | 0 | 0| 
| 20210108T08:07:09Z | Null | https://github.com/MadsKaiser/backdoor | 0 | 0| 
| 20210108T06:03:00Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 140 | 20| 
| 20210108T02:50:25Z | Null | https://github.com/4k5k-Real/backdoored | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210108T13:01:43Z | Adds ~ to searches on pathofexile.com/trade to enable fuzzy search. No more exact wording needed. | https://github.com/JonasRock/POETradeFuzzySearch | 2 | 2| 
| 20210108T12:49:04Z | Null | https://github.com/cleiomsqs/fuzzy-octo-carnival | 0 | 0| 
| 20210108T12:23:32Z | Challenging testcases for fuzzers | https://github.com/AFLplusplus/fuzzer-challenges | 7 | 0| 
| 20210108T12:22:36Z | The Official Fuzzy Britches Repository. | https://github.com/ThePapaw/fuzzybritches | 0 | 0| 
| 20210108T12:04:27Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 1236 | 265| 
| 20210108T12:02:52Z | C++ Fuzzy logic with ImGui interface | https://github.com/Renardjojo/FuzzyLogic | 0 | 0| 
| 20210108T11:59:23Z | Null | https://github.com/7evy/Fuzzy_Queries | 0 | 0| 
| 20210108T11:33:13Z | Null | https://github.com/s9varesc/url-fuzzing-docker | 0 | 0| 
| 20210108T11:30:44Z | Fuzzy Sync Presentation 2021 | https://github.com/richiejp/fuzzy-sync-pres-2021 | 0 | 0| 
| 20210108T10:49:48Z | Null | https://github.com/guidovranken/wolf-ssl-ssh-fuzzers | 3 | 1| 



# 日更新程序
