# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210106 | The Mac Malware of 2020 | https://objective-see.com/blog/blog_0x5F.html| 
| 20210106 | CVE-2020–35717 — RCE through XSS in zonote Electron App | https://medium.com/bugbountywriteup/remote-code-execution-through-cross-site-scripting-in-electron-f3b891ad637| 
| 20210106 | PyBeacon - NCCGroup 开源的用于处理 Cobalt Strike beacons 的脚本 | https://github.com/nccgroup/pybeacon| 
| 20210106 | 利用 WebKit 0Day 漏洞攻击 PS4 | https://i.blackhat.com/eu-20/Thursday/eu-20-Meffre-This-Is-For-The-Pwners-Exploiting-A-Webkit-0day-In-Playstation4.pdf| 
| 20210106 | ElectroRAT: Attacker Creates Fake Companies to Drain Crypto Wallets | https://www.intezer.com/blog/research/operation-electrorat-attacker-creates-fake-companies-to-drain-your-crypto-wallets/| 
| 20210106 | Apple 公开 macOS 11.0.1 版本的源码 | https://opensource.apple.com/release/macos-1101.html| 
| 20210106 | 两种 Windows anti-debug 新方法 | https://secret.club/2021/01/04/thread-stuff.html| 
| 20210106 | 一月份补丁中 Android 修复 43 个漏洞 | https://threatpost.com/google-warns-of-critical-android-remote-code-execution-bug/162756/| 
| 20210106 | Windows. NTFS 文件系统上个月修复的 CVE-2020-17096 RCE 漏洞的分析 | https://blog.zecops.com/vulnerabilities/ntfs-remote-code-execution-cve-2020-17096-analysis/| 
| 20210106 | NICER协议深入研究：互联网的域名系统（DNS）服务报告公开。 | https://blog.rapid7.com/2021/01/05/nicer-protocol-deep-dive-internet-exposure-of-dns/| 
| 20210106 | 漏洞焦点：Genivia gSOAP工具插件中包出现多个漏洞问题。 | https://blog.talosintelligence.com/2021/01/vuln-spotlight-genivia-gsoap-.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+feedburner%2FTalos+%28Talos%E2%84%A2+Blog%29| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210106 | 记一次匈牙利服务器提权案例 | https://mp.weixin.qq.com/s/kfC4ajyJqH0GNskqgSsQVw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210106T21:16:52Z | CVE-2020-17519 | Apache Flink 目录遍历漏洞批量检测 (CVE-2020-17519) | https://github.com/B1anda0/CVE-2020-17519 | A change introduced in Apache Flink 1.11.0 (and released in 1.11.1 and 1.11.2 as well) allows attackers to read any file on the local filesystem of the JobManager through the REST interface of the JobManager process. Access is restricted to files accessible by the JobManager process. All users should upgrade to Flink 1.11.3 or 1.12.0 if their Flink instance(s) are exposed. The issue was fixed in commit b561010b0ee741543c3953306037f00d7a9f0801 from apache/flink:master.| 
| 20210106T18:53:25Z | CVE-2020-0001 | POC to run system component in an untrusted-app process | https://github.com/Zachinio/CVE-2020-0001 | In getProcessRecordLocked of ActivityManagerService.java isolated apps are not handled correctly. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation. Product: Android Versions: Android-8.0, Android-8.1, Android-9, and Android-10 Android ID: A-140055304| 
| 20210106T16:58:10Z | 未知编号 | 2020一些漏洞 | https://github.com/r0eXpeR/CVE-2020 | 未查询到CVE信息| 
| 20210106T16:12:43Z | CVE-2020-28052 | Null | https://github.com/kurenaif/CVE-2020-28052_PoC | | 
| 20210106T15:54:02Z | CVE-2020-3452 | CISCO CVE-2020-3452 Scanner & Exploiter | https://github.com/darklotuskdb/CISCO-CVE-2020-3452-Scanner-Exploiter | A vulnerability in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct directory traversal attacks and read sensitive files on a targeted system. The vulnerability is due to a lack of proper input validation of URLs in HTTP requests processed by an affected device. An attacker could exploit this vulnerability by sending a crafted HTTP request containing directory traversal character sequences to an affected device. A successful exploit could allow the attacker to view arbitrary files within the web services file system on the targeted device. The web services file system is enabled when the affected device is configured with either WebVPN or AnyConnect features. This vulnerability cannot be used to obtain access to ASA or FTD system files or underlying operating system (OS) files.| 
| 20210106T14:01:08Z | CVE-2020-17518 | Null | https://github.com/QmF0c3UK/CVE-2020-17518 | Apache Flink 1.5.1 introduced a REST handler that allows you to write an uploaded file to an arbitrary location on the local file system, through a maliciously modified HTTP HEADER. The files can be written to any location accessible by Flink 1.5.1. All users should upgrade to Flink 1.11.3 or 1.12.0 if their Flink instance(s) are exposed. The issue was fixed in commit a5264a6f41524afe8ceadf1d8ddc8c80f323ebc4 from apache/flink:master.| 
| 20210106T13:42:00Z | CVE-2020-17519 | Null | https://github.com/QmF0c3UK/CVE-2020-17519 | A change introduced in Apache Flink 1.11.0 (and released in 1.11.1 and 1.11.2 as well) allows attackers to read any file on the local filesystem of the JobManager through the REST interface of the JobManager process. Access is restricted to files accessible by the JobManager process. All users should upgrade to Flink 1.11.3 or 1.12.0 if their Flink instance(s) are exposed. The issue was fixed in commit b561010b0ee741543c3953306037f00d7a9f0801 from apache/flink:master.| 
| 20210106T06:28:36Z | CVE-2020-10148 | SolarWinds Orion API 远程代码执行漏洞批量检测脚本 | https://github.com/B1anda0/CVE-2020-10148 | The SolarWinds Orion API is vulnerable to an authentication bypass that could allow a remote attacker to execute API commands. This vulnerability could allow a remote attacker to bypass authentication and execute API commands which may result in a compromise of the SolarWinds instance. SolarWinds Orion Platform versions 2019.4 HF 5, 2020.2 with no hotfix installed, and 2020.2 HF 1 are affected.| 
| 20210106T02:53:25Z | cve-2020- | Null | https://github.com/asc0t6e/cve-2020-test | 未查询到CVE信息| 
| 20210106T01:32:23Z | CVE-2020-35728 |  CVE-2020-35728 & Jackson-databind RCE | https://github.com/Al1ex/CVE-2020-35728 | FasterXML jackson-databind 2.x before 2.9.10.8 mishandles the interaction between serialization gadgets and typing, related to com.oracle.wls.shaded.org.apache.xalan.lib.sql.JNDIConnectionPool (aka embedded Xalan in org.glassfish.web/javax.servlet.jsp.jstl).| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210106T15:24:38Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1594 | 478| 
| 20210106T14:53:29Z | Data-driven symbolic execution engine, implemented on top of KLEE | https://github.com/kupl/dd-klee | 0 | 1| 
| 20210106T12:41:52Z | Null | https://github.com/Eclipse2552/KleeFieg | 0 | 0| 
| 20210106T11:17:11Z | Null | https://github.com/foxcore-azizi/kleet4 | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210106T02:55:41Z | GUI Configuration tool for WIZnet serial to ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool-GUI | 11 | 7| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210106T23:59:00Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 161 | 29| 
| 20210106T23:28:43Z | Various ASM, C and C++ tools, shellcodes and exploit experiments. | https://github.com/forrest-orr/ExploitDev | 30 | 2| 
| 20210106T23:08:16Z | Minecraft Plugin to stop cheaty raid farms that exploit infinite bad omen loops | https://github.com/jmanpenilla/AntiRaidFarm | 1 | 0| 
| 20210106T22:46:10Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 8860 | 1400| 
| 20210106T22:26:44Z | Security and Hacking Tools, Exploits, Proof of Concepts, Shellcodes, Scripts. | https://github.com/nullsecuritynet/tools | 1281 | 442| 
| 20210106T21:14:11Z | Albatar is a SQLi exploitation framework in Python | https://github.com/lanjelot/albatar | 105 | 33| 
| 20210106T20:49:52Z | Exploiting CVE-2014-3153, AKA Towelroot. | https://github.com/elongl/CVE-2014-3153 | 0 | 0| 
| 20210106T20:09:36Z | Exploit Discord%s cache system to remote upload payloads on Discord users machines | https://github.com/ecriminal/Discord-Cache-Exploit-PoC | 2 | 0| 
| 20210106T20:06:04Z | An attack/exploit Detector that utilizes Polymorphism and Diversity | https://github.com/polyverse/zerotect | 21 | 1| 
| 20210106T19:58:36Z | Basic security exploits originally designed for participants of the Security Engineering workshop at Hack The North 2020++ | https://github.com/katyapotapov/basic-security-exploits | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210106T23:59:00Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 161 | 29| 
| 20210106T18:19:23Z | Null | https://github.com/MadsKaiser/backdoor | 0 | 0| 
| 20210106T16:50:01Z | Null | https://github.com/mpandya18/Image_Permutator_For_Backdoor_Generation | 0 | 0| 
| 20210106T15:18:32Z | PCI Express DIY hacking toolkit for Xilinx SP605 | https://github.com/Cr4sh/s6_pcie_microblaze | 294 | 77| 
| 20210106T12:55:36Z | Null | https://github.com/D4SuCE/backdoor | 0 | 0| 
| 20210106T12:42:43Z | Null | https://github.com/rabbitx1337/backdoor | 0 | 0| 
| 20210106T10:33:53Z | Null | https://github.com/Yunolay/image-backdoor | 0 | 0| 
| 20210106T08:32:14Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 140 | 20| 
| 20210106T07:53:15Z | Null | https://github.com/hassanalharbi123/backdoor | 0 | 0| 
| 20210106T06:45:02Z | Clean version of Phobos with no backdoor, Hacked Client for minecraft 1.12.2 | https://github.com/EnormousPotato/Clean_Phobos_1.5.4 | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210106T13:49:19Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2241 | 113| 
| 20210106T13:38:01Z | Fuzzy search in Dart | https://github.com/comigor/fuzzy | 21 | 9| 
| 20210106T12:36:31Z | A portal for tech savvy people | https://github.com/nkgawade/FuzzBrain | 0 | 0| 
| 20210106T12:28:24Z | Null | https://github.com/Sentinel-One/efi_fuzz | 60 | 6| 
| 20210106T12:21:43Z | The iron-booted robotic resident of The Tsunami Zone. | https://github.com/parafoxia/FuzzySeven | 0 | 0| 
| 20210106T11:34:25Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 4 | 1| 
| 20210106T11:30:04Z | Using different tools to fuzz audit deamon | https://github.com/punnal/Audit-Fuzzing | 1 | 1| 
| 20210106T11:27:20Z | no fuzz configurator | https://github.com/roxiness/configent | 6 | 0| 
| 20210106T10:59:12Z | this fuzzer detect DOM based XSS in chrome extension  | https://github.com/kurotojp/fuzzer | 0 | 0| 
| 20210106T10:37:55Z | Given program metrics, predict fuzzer performance. | https://github.com/AIK13/Fuzz-Predictions | 0 | 0| 



# 日更新程序
