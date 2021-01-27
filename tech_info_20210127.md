# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210127 | Google 修复 Golang Windows RCE 漏洞（CVE-2021-3115） | https://www.bleepingcomputer.com/news/security/google-fixes-severe-golang-windows-rce-vulnerability/| 
| 20210127 | Apple 紧急发布 iOS 14.4/iPadOS 14.4，修复 3 个可能已被野外利用的 0Day | https://support.apple.com/en-us/HT212146| 
| 20210127 | sudo 堆溢出漏洞 CVE-2021-3156 分析 | https://blog.qualys.com/vulnerabilities-research/2021/01/26/cve-2021-3156-heap-based-buffer-overflow-in-sudo-baron-samedit| 
| 20210127 | The all-in-one Red Team browser extension for Web Pentesters | https://github.com/LasCC/Hack-Tools| 
| 20210127 | Fill your Boots: Enhanced Embedded BootloaderExploits via Fault Injection and Binary Analysis(Paper) | http://tches.iacr.org/index.php/TCHES/article/view/8727/8327| 
| 20210127 | 动静态分析的方法检测软件供应链中的 0Day 攻击 | https://ajinabraham.com/blog/detecting-zero-days-in-software-supply-chain-with-static-and-dynamic-analysis| 
| 20210127 | ZDI 将于 4 月份在温哥华举办 Pwn2Own 2021，比赛的目标及细则公布了 | https://www.thezdi.com/blog/2021/1/25/announcing-pwn2own-vancouver-2021| 
| 20210127 | Checkpoint 对近期发现的 TikTok 通讯录同步相关的隐私问题的分析 | https://research.checkpoint.com/2021/tiktok-fixes-privacy-issue-discovered-by-check-point-research/| 
| 20210127 | SSRF 漏洞以及在不同语言中的利用 | https://security.tencent.com/index.php/blog/msg/179| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210127 | 从弱口令到拿下站群服务器 | https://www.hetianlab.com/specialized/20210119110943| 
| 20210127 | 浅谈Springboot中的文件上传 | https://www.sec-in.com/article/836| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210127T12:56:38Z | CVE-2020-14756 | WebLogic T3/IIOP RCE ExternalizableHelper.class of coherence.jar | https://github.com/Y4er/CVE-2020-14756 | Vulnerability in the Oracle Coherence product of Oracle Fusion Middleware (component: Core Components). Supported versions that are affected are 3.7.1.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via IIOP, T3 to compromise Oracle Coherence. Successful attacks of this vulnerability can result in takeover of Oracle Coherence. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210127T12:52:15Z | CVE-2021-3156 | Null | https://github.com/mr-r3b00t/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character:| 
| 20210127T10:23:27Z | CVE-2021-3129 | Exploit for CVE-2021-3129 | https://github.com/nth347/CVE-2021-3129-exploit | Ignition before 2.5.2, as used in Laravel and other products, allows unauthenticated remote attackers to execute arbitrary code because of insecure usage of file_get_contents() and file_put_contents(). This is exploitable on sites using debug mode with Laravel before 8.4.2.| 
| 20210127T08:29:37Z | CVE-2021-3129 | Laravel debug rce | https://github.com/SNCKER/CVE-2021-3129 | Ignition before 2.5.2, as used in Laravel and other products, allows unauthenticated remote attackers to execute arbitrary code because of insecure usage of file_get_contents() and file_put_contents(). This is exploitable on sites using debug mode with Laravel before 8.4.2.| 
| 20210127T06:32:10Z | CVE-2020-14882 | CVE-2020-14882部署冰蝎内存马 | https://github.com/ShmilySec/CVE-2020-14882 | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210127T06:26:17Z | CVE-2021-3129 | Null | https://github.com/crisprss/Laravel_CVE-2021-3129_EXP | Ignition before 2.5.2, as used in Laravel and other products, allows unauthenticated remote attackers to execute arbitrary code because of insecure usage of file_get_contents() and file_put_contents(). This is exploitable on sites using debug mode with Laravel before 8.4.2.| 
| 20210127T01:22:30Z | CVE-2020-9484 | Null | https://github.com/AssassinUKG/CVE-2020-9484 | When using Apache Tomcat versions 10.0.0-M1 to 10.0.0-M4, 9.0.0.M1 to 9.0.34, 8.5.0 to 8.5.54 and 7.0.0 to 7.0.103 if a) an attacker is able to control the contents and name of a file on the server; and b) the server is configured to use the PersistenceManager with a FileStore; and c) the PersistenceManager is configured with sessionAttributeValueClassNameFilter=%null% (the default unless a SecurityManager is used) or a sufficiently lax filter to allow the attacker provided object to be deserialized; and d) the attacker knows the relative file path from the storage location used by FileStore to the file the attacker has control over; then, using a specifically crafted request, the attacker will be able to trigger remote code execution via deserialization of the file under their control. Note that all of conditions a) to d) must be true for the attack to succeed.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210127T12:52:11Z | Null | https://github.com/kleelab/kleelab.github.io | 0 | 0| 
| 20210127T10:28:27Z | Null | https://github.com/fontworks-fonts/Klee | 334 | 10| 
| 20210127T10:25:16Z | Null | https://github.com/jiseongg/klee_experiment | 0 | 0| 
| 20210127T10:21:46Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1618 | 478| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210127T13:02:32Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 1 | 3| 
| 20210127T13:02:20Z | A tool to identify and exploit sudo rules% misconfigurations and vulnerabilities within sudo | https://github.com/TH3xACE/SUDO_KILLER | 954 | 131| 
| 20210127T12:49:53Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 7 | 4| 
| 20210127T12:38:21Z | Null | https://github.com/MTK-bypass/exploits_collection | 29 | 14| 
| 20210127T12:14:40Z | Exploitation Framework for Embedded Devices | https://github.com/threat9/routersploit | 8931 | 1970| 
| 20210127T12:11:47Z | Just a temporary website to post my ctf writeups and journey into binary exploitation/malware analysis/exploit development | https://github.com/blackbeard666/blackbeard666.github.io | 0 | 0| 
| 20210127T11:41:49Z | Exploits backed up from http://1337day.com in the 2011 | https://github.com/SourceCodeBackup/exploits-backup | 17 | 8| 
| 20210127T11:35:16Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 8934 | 1433| 
| 20210127T10:56:47Z | PoCs for public CVE%s I have been working on. | https://github.com/lockedbyte/CVE-Exploits | 2 | 0| 
| 20210127T10:52:05Z | Geohazards Thematic Exploitation guide | https://github.com/Terradue/doc-tep-geohazards | 9 | 23| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210127T09:40:57Z | Undetectable & Xor encrypting with custom KEY (FUD Metasploit Rat) bypass Top Antivirus like BitDefender,Malwarebytes,Avast,ESET-NOD32,AVG,... & Automatically Add ICON and MANIFEST to excitable | https://github.com/persianhydra/Xeexe-TopAntivirusEvasion | 271 | 76| 
| 20210127T08:52:23Z | Worlds simplest PHP backdoor | https://github.com/F-Masood/php-backdoors | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210127T13:00:58Z | White-box fuzzer for Java bytecode | https://github.com/vorpal-research/kex | 6 | 5| 
| 20210127T13:00:45Z | Null | https://github.com/ercoppa-bot/fuzzolic-builder-ci | 0 | 0| 
| 20210127T12:31:16Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 234 | 31| 
| 20210127T12:20:27Z | SSL and TLS protocol test suite and fuzzer | https://github.com/tlsfuzzer/tlsfuzzer | 330 | 83| 
| 20210127T11:57:27Z | Null | https://github.com/poli625/Fuzzy_Logic_Heat_Engine | 0 | 0| 
| 20210127T11:50:42Z | FormatFuzzer is a framework for high-efficiency, high-quality generation and parsing of binary inputs. | https://github.com/uds-se/FormatFuzzer | 115 | 12| 
| 20210127T11:42:58Z | 搜索工具类;a searching-utils for what you saved | https://github.com/kc910521/MiniSearch | 4 | 0| 
| 20210127T11:01:54Z | Fuzzer for Pharo | https://github.com/mabdi/phazzer | 0 | 0| 
| 20210127T11:00:12Z | PoCs discovered through fuzzing | https://github.com/LyleMi/Fuzz-PoC | 2 | 0| 
| 20210127T10:43:44Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 4 | 1| 



# 日更新程序
