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
| 20210108 | 对 SolarWinds 事件更深的思考：如何防御供应链攻击 | https://mp.weixin.qq.com/s/GdER32Z7K86boHVc-Kic3g| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210108T23:15:08Z | CVE-2020-29254 | TikiWiki 21.2 allows to edit templates without the use of a CSRF protection.  | https://github.com/S1lkys/CVE-2020-29254 | TikiWiki 21.2 allows templates to be edited without CSRF protection. This could allow an unauthenticated, remote attacker to conduct a cross-site request forgery (CSRF) attack and perform arbitrary actions on an affected system. The vulnerability is due to insufficient CSRF protections for the web-based management interface of the affected system. An attacker could exploit this vulnerability by persuading a user of the interface to follow a maliciously crafted link. A successful exploit could allow the attacker to perform arbitrary actions on an affected system with the privileges of the user. These action include allowing attackers to submit their own code through an authenticated user resulting in local file Inclusion. If an authenticated user who is able to edit TikiWiki templates visits an malicious website, template code can be edited.| 
| 20210108T21:20:59Z | CVE-2020-14179 | CVE-2020-14179 Scanner | https://github.com/c0brabaghdad1/CVE-2020-14179 | Affected versions of Atlassian Jira Server and Data Center allow remote, unauthenticated attackers to view custom field names and custom SLA names via an Information Disclosure vulnerability in the /secure/QueryComponent!Default.jspa endpoint. The affected versions are before version 8.5.8, and from version 8.6.0 before 8.11.1.| 
| 20210108T20:32:49Z | CVE-2020-11851 | Remote Code Execution vulnerability on ArcSight Logger | https://github.com/ch1nghz/CVE-2020-11851 | Arbitrary code execution vulnerability on Micro Focus ArcSight Logger product, affecting all version prior to 7.1.1. The vulnerability could be remotely exploited resulting in the execution of arbitrary code.| 
| 20210108T20:07:37Z | CVE-2020-3452 | CISCO CVE-2020-3452 Scanner & Exploiter | https://github.com/darklotuskdb/CISCO-CVE-2020-3452-Scanner-Exploiter | A vulnerability in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct directory traversal attacks and read sensitive files on a targeted system. The vulnerability is due to a lack of proper input validation of URLs in HTTP requests processed by an affected device. An attacker could exploit this vulnerability by sending a crafted HTTP request containing directory traversal character sequences to an affected device. A successful exploit could allow the attacker to view arbitrary files within the web services file system on the targeted device. The web services file system is enabled when the affected device is configured with either WebVPN or AnyConnect features. This vulnerability cannot be used to obtain access to ASA or FTD system files or underlying operating system (OS) files.| 
| 20210108T13:10:23Z | cve-2020-16040 | Crashing PoC for CVE-2020-16040 | https://github.com/farazsth98/cve-2020-16040-poc | 未查询到CVE信息| 
| 20210108T13:03:47Z | cve-2020-16040 | Crashing PoC for CVE-2020-16040 | https://github.com/farazsth98/cve-2020-16040 | | 
| 20210108T11:45:49Z | CVE-2020-17519 | Apache Flink 目录遍历漏洞批量检测 (CVE-2020-17519) | https://github.com/B1anda0/CVE-2020-17519 | A change introduced in Apache Flink 1.11.0 (and released in 1.11.1 and 1.11.2 as well) allows attackers to read any file on the local filesystem of the JobManager through the REST interface of the JobManager process. Access is restricted to files accessible by the JobManager process. All users should upgrade to Flink 1.11.3 or 1.12.0 if their Flink instance(s) are exposed. The issue was fixed in commit b561010b0ee741543c3953306037f00d7a9f0801 from apache/flink:master.| 
| 20210108T10:26:51Z | CVE-2020-0001 | POC to run system component in an untrusted-app process | https://github.com/Zachinio/CVE-2020-0001 | In getProcessRecordLocked of ActivityManagerService.java isolated apps are not handled correctly. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation. Product: Android Versions: Android-8.0, Android-8.1, Android-9, and Android-10 Android ID: A-140055304| 
| 20210108T10:18:02Z | CVE-2020-25498 | Stored XSS via CSRF in Beetel 777VR1 Router  | https://github.com/the-girl-who-lived/CVE-2020-25498 | Cross Site Scripting (XSS) vulnerability in Beetel router 777VR1 can be exploited via the NTP server name in System Time and %Keyword% in URL Filter.| 
| 20210108T08:49:39Z | 未知编号 | 2020l4web-campaign-DanCvejn created by GitHub Classroom | https://github.com/pslib-cz/2020l4web-campaign-DanCvejn | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210108T21:37:19Z | ⬇️ File Upload/sharing application, used by thousands of webmasters since 2007.  | https://github.com/kleeja-official/kleeja | 108 | 32| 
| 20210108T16:24:18Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1598 | 478| 
| 20210108T09:27:22Z | Null | https://github.com/OleDakotaJoe/peachy-kleen | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210108T20:19:44Z | Robo Hazel is a robot prototype made using Arduino and WIZnet S2E module to advance industry 4.0 and solve the problem of message delivery. | https://github.com/hamzakhalidhk/RoboHazel | 0 | 0| 
| 20210108T15:14:31Z | Convert geojson to s2 region cells in different levels | https://github.com/ponlawat-w/uji_mt-geojson_s2encoding | 0 | 0| 
| 20210108T07:54:56Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 89 | 22| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210108T23:56:02Z | Null | https://github.com/Rilshrink/HopeCommanderExploit | 0 | 0| 
| 20210108T23:40:39Z | Null | https://github.com/1N53C/ExploitDBSearch | 0 | 0| 
| 20210108T23:13:40Z | Thi powershell script has got to run in remote windows host, even for pivoting | https://github.com/FabioDefilippo/winallenum | 0 | 1| 
| 20210108T22:56:58Z | A bash script that will automatically install a list of bug hunting tools that I find interesting for recon, exploitation, etc. (minus burp) For Ubuntu/Debain. Feel free to fork, and add your own tools. | https://github.com/0xApt/awesome-bbht | 123 | 47| 
| 20210108T22:26:45Z | MikrotikSploit is a script that searches for and exploits Mikrotik network vulnerabilities | https://github.com/0x802/MikrotikSploit | 30 | 13| 
| 20210108T22:00:24Z | Compiled binaries from https://github.com/tyranid/ExploitRemotingService | https://github.com/skrmsh/ExploitRemotingService | 0 | 0| 
| 20210108T21:49:21Z | A framework for pentesters that facilitates evil twin attacks as well as exploiting other wifi vulnerabilities | https://github.com/Esser420/EvilTwinFramework | 109 | 36| 
| 20210108T21:37:07Z | This is core for build search bot to search vulnerabilities, use exploits, cms detection, mass exploits etc. | https://github.com/minelifes/search_bot_core | 1 | 0| 
| 20210108T21:32:45Z | GEF - GDB Enhanced Features for exploit devs & reversers | https://github.com/hugsy/gef | 3353 | 481| 
| 20210108T21:19:27Z | Some exercises from my System and Network Hacking course @ University of Pisa | https://github.com/loresuso/BinaryExploitation | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210108T23:28:58Z | Code for the paper Explanation-Guided Backdoor Poisoning Attacks Against Malware Classifiers | https://github.com/ClonedOne/Explanation-Guided_Backdoor_Poisoning | 0 | 0| 
| 20210108T20:45:11Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. Ghost Framework gives you the power and convenience of remote Android device administration. | https://github.com/EntySec/ghost | 903 | 460| 
| 20210108T16:29:57Z | Null | https://github.com/MadsKaiser/backdoor | 0 | 0| 
| 20210108T13:04:52Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 141 | 20| 
| 20210108T11:14:02Z | Null | https://github.com/mpandya18/Image_Permutator_For_Backdoor_Generation | 0 | 0| 
| 20210108T09:30:48Z | Information This tool is for educational purpose only, usage of TheFatRat for attacking targets without prior mutual consent is illegal. Developers assume no liability and are not responsible for any misuse or damage cause by this program.  Features ! Fully Automating MSFvenom & Metasploit. Local or remote listener Generation. Easily Make Backdoor by category Operating System. Generate payloads in Various formats. Bypass anti-virus backdoors. File pumper that you can use for increasing the size of your files. The ability to detect external IP & Interface address . Automatically creates AutoRun files for USB / CDROM exploitation But it%s shit! And your implementation sucks! Yes, you%re probably correct. Feel free to %Not use it% and there is a pull button to %Make it better%. Installation Instructions on how to install TheFatRat  git clone https://github.com/Screetsec/TheFatRat.git cd TheFatRat chmod +x setup.sh && ./setup.sh Update cd TheFatRat ./update && chmod +x setup.sh && ./setup.sh Troubleshoot on TheFatRat chk_tools script to use in case of problems in setup.sh of fatrat this script will check if everything is in the right version to run fatrat and will also provide you a solution for the problem  cd TheFatRat chmod +x chk_tools  ./chk_tools | https://github.com/nyctophile6/TheFatRat | 0 | 0| 
| 20210108T08:45:06Z | Null | https://github.com/rensx5514/BackdoorAttackNN-Pro | 0 | 0| 
| 20210108T02:50:25Z | Null | https://github.com/4k5k-Real/backdoored | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210108T22:50:45Z | Repository for Fuzzy Miner Web application. | https://github.com/fnc11/FuzzyMiner | 5 | 0| 
| 20210108T22:36:08Z | Null | https://github.com/fragment137/fuzzy-enigma | 0 | 0| 
| 20210108T21:44:00Z | 2021 | https://github.com/boquetebob49/fuzzy-bassoon | 0 | 0| 
| 20210108T21:16:45Z | GraphQLmap is a scripting engine to interact with a graphql endpoint for pentesting purposes. | https://github.com/swisskyrepo/GraphQLmap | 380 | 74| 
| 20210108T20:54:11Z | a simplified means to CRUD ephemeral user-scoped EC2 instances | https://github.com/rstudio/fuzzbucket | 1 | 1| 
| 20210108T20:53:06Z | This repository presents a readme for the setup of fuzzers and other related tools | https://github.com/c0d3nh4ck/Setup-of-Fuzzers-and-Tools | 0 | 0| 
| 20210108T20:41:09Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 1237 | 265| 
| 20210108T20:21:00Z | Null | https://github.com/Anonyme1396/fuzzparam | 0 | 0| 
| 20210108T20:18:50Z | Automatic fuzzer/reporter for dnethack | https://github.com/demogorgon22/dnhautofuzz | 0 | 0| 
| 20210108T19:47:08Z | Adds ~ to searches on pathofexile.com/trade to enable fuzzy search. No more exact wording needed. | https://github.com/JonasRock/POETradeFuzzySearch | 2 | 1| 



# 日更新程序
