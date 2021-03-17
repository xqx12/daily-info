# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210317 | Sudo CVE-2021-3156 漏洞在 Linux x64 平台的利用 | https://github.com/worawit/CVE-2021-3156| 
| 20210317 | Spectre 漏洞的跨平台 JS 利用实现 | https://dougallj.wordpress.com/2021/03/16/another-approach-to-portable-javascript-spectre-exploitation/| 
| 20210317 | 从内存特征的角度检测 Cobalt Strike | https://www.elastic.co/blog/detecting-cobalt-strike-with-memory-signatures| 
| 20210317 | Riscure 团队对三星可信执行框架 TEEGRIS 的逆向分析 | https://www.riscure.com/blog/samsung-investigation-part2| 
| 20210317 | Chrome issue 1125614 沙箱逃逸漏洞的利用 | https://securitylab.github.com/research/one_day_short_of_a_fullchain_sbx/| 
| 20210317 | PMFuzz: Test Case Generation for Persistent Memory Programs（Paper） | https://www.cs.virginia.edu/~smk9u/Liu_PMFuzz_ASPLOS21.pdf| 
| 20210317 | 利用 CodeQL 静态代码分析工具挖掘 JavaScriptCore JS 引擎的漏洞 | https://www.cyberark.com/resources/threat-research-blog/the-mysterious-realm-of-javascriptcore| 
| 20210317 | Necro 再次升级，使用 Tor+动态域名 DGA 双杀 Windows&Linux | https://blog.netlab.360.com/necro-shi-yong-tor-dong-tai-yu-ming-dga-shuang-sha-windows-linux/| 
| 20210317 | CVE 2017-0261 的 .EPS 恶意文件分析 | https://paper.seebug.org/1509/| 
| 20210316 | macOS CoreGraphics 图形库整数溢出漏洞（CVE-2021-1776） | https://bugs.chromium.org/p/project-zero/issues/detail?id=2130| 
| 20210316 | 有研究员将 macOS 安装在 Docker 里，实现 Run Mac in a Docker | https://github.com/sickcodes/Docker-OSX| 
| 20210316 | Objective-See 开发的 macOS 平台安全检测工具 KnockKnock 开源了 | https://github.com/objective-see/KnockKnock| 
| 20210316 | Introduction to Control-flow Graph Analysis | https://synthesis.to/2021/03/15/control_flow_analysis.html| 
| 20210316 | 微软推出了一个漏洞利用缓解工具，以应对近期 Exchange 漏洞的攻击 | https://msrc-blog.microsoft.com/2021/03/15/one-click-microsoft-exchange-on-premises-mitigation-tool-march-2021/| 
| 20210316 | macOS Big Sur 新引入的进程管理相关的 runningboardd 介绍 | https://themittenmac.com/hurdling-the-runningboards/?utm_source=rss&utm_medium=rss&utm_campaign=hurdling-the-runningboards| 
| 20210316 | fpicker - 基于 Frida 编写的黑盒 in-Process Fuzzer | https://insinuator.net/2021/03/fpicker-fuzzing-with-frida/| 
| 20210316 | OD调试宏代码中的新线程 | https://paper.seebug.org/1508/| 
| 20210315 | 利用 Differential Fuzzing 的方法挖掘正则表达式的漏洞 | https://defparam.medium.com/finding-issues-in-regular-expression-logic-using-differential-fuzzing-30d78d4cb1d5| 
| 20210315 | Hacking Windows HTTP Server - IIS | https://drive.google.com/file/d/1O0IARjqP4Pwa-ae1nAP8Nr9qb0ai2XPu/view| 
| 20210315 | Java 序列化开源组件 XStream 被发现多个高危漏洞 | http://x-stream.github.io/security.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210315 | 隐蔽信道：隐形网络 | https://www.sec-in.com/article/57| 
| 20210315 | SecWiki周刊（第367期) | https://www.sec-wiki.com/weekly/367| 
| 20210315 | 知识图谱技术如何赋能智能安全运营 | https://mp.weixin.qq.com/s/qOuvPv8cm1S-jA-gqH1hZg| 
| 20210314 | 最后防线：osquery功能与实现 | https://mp.weixin.qq.com/s/PvnLnn1gDcl_X4fyocyPrA| 
| 20210313 | Shiro 反序列化漏洞利用工具编写思路 | https://mp.weixin.qq.com/s/WDmj4-2lB-hlf_Fm_wDiOg| 
| 20210313 | 对蚁剑的相关改造及分析 | https://www.anquanke.com/post/id/233114| 
| 20210313 | 如何攻击深度学习系统——后门攻防 | https://www.anquanke.com/post/id/232414| 
| 20210313 | IoT设备漏洞复现到固件后门植入 | https://www.anquanke.com/post/id/232845| 
| 20210313 | TIG 威胁情报收集 | https://github.com/wgpsec/tig| 
| 20210313 | GoScan: 分布式综合资产管理系统 | https://github.com/CTF-MissFeng/GoScan| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210317T11:43:16Z | CVE-2021-3156 | Sudo Baron Samedit Exploit | https://github.com/worawit/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210317T11:30:01Z | CVE-2020-15778 | Null | https://github.com/cpandya2909/CVE-2020-15778 | scp in OpenSSH through 8.3p1 allows command injection in the scp.c toremote function, as demonstrated by backtick characters in the destination argument. NOTE: the vendor reportedly has stated that they intentionally omit validation of %anomalous argument transfers% because that could %stand a great chance of breaking existing workflows.%| 
| 20210317T11:10:56Z | CVE-2021-22986 | This is a Poc for BIGIP iControl unauth RCE  | https://github.com/dorkerdevil/CVE-2021-22986-Poc | 未查询到CVE信息| 
| 20210317T05:51:32Z | CVE-2021-26855 | CVE-2021-26855 proxyLogon metasploit exploit script | https://github.com/TaroballzChen/ProxyLogon-CVE-2021-26855-metasploit | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210317T03:11:02Z | CVE-2021-26411 | Null | https://github.com/avboy1337/CVE-2021-26411 | Internet Explorer Memory Corruption Vulnerability| 
| 20210316T16:39:44Z | CVE-2021-26855 | Null | https://github.com/alt3kx/CVE-2021-26855_PoC | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210316T16:10:29Z | CVE-2021-26855 | Null | https://github.com/shacojx/Scan-Vuln-CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210316T13:53:40Z | CVE-2020-1034 | PoC demonstrating the use of cve-2020-1034 for privilege escalation | https://github.com/yardenshafir/CVE-2020-1034 | An elevation of privilege vulnerability exists in the way that the Windows Kernel handles objects in memory, aka %Windows Kernel Elevation of Privilege Vulnerability%.| 
| 20210316T12:55:41Z | CVE-2021-26855 | RCE exploit for ProxyLogon vulnerability in Microsoft Exchange | https://github.com/mil1200/ProxyLogon-CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210316T12:54:30Z | CVE-2021-26855 | CVE-2021-26855: PoC (Not a HoneyPoC for once!) | https://github.com/ZephrFish/Exch-CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210317T09:14:26Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 212 | 34| 
| 20210317T08:57:28Z | Kleene algebra, regular expressions | https://github.com/phadej/kleene | 27 | 1| 
| 20210317T08:48:54Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 333 | 7| 
| 20210317T05:34:58Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210317T03:50:51Z | 원신 가챠 시뮬레이터 | https://github.com/LunaNyan/Genshin_Klee_Discord_Bot | 1 | 0| 
| 20210317T00:52:52Z | Null | https://github.com/TheBeehive/kleene | 0 | 0| 
| 20210316T21:21:48Z | Minimal Working Example (MWE) to evaluate flexible protections in KLEE | https://github.com/jvdbroeck/mwe-klee | 0 | 0| 
| 20210316T11:23:26Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 14 | 42| 
| 20210316T10:53:00Z | JavaScript graphics | https://github.com/MolluscHotel/MisterKlee | 0 | 0| 
| 20210316T09:29:20Z | Null | https://github.com/kleefi/kleefi.github.io | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210316T01:31:41Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 101 | 25| 
| 20210313T20:42:17Z | Source of Sonic Eclipse, a romhack of Sonic 2 for Sega Master System circa 2018. http://sonicresearch.org/community/index.php?threads/sonic-eclipse.5524/ | https://github.com/mrcat-pixel/s2eclipse | 3 | 0| 
| 20210306T11:03:45Z | Master Thesis %Decentralised Location-Based Reputation Management System in IoT using Blockchain% - Experiment S2 region covering in Golang | https://github.com/ponlawat-w/uji_mt-s2encoding | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210317T11:54:41Z | PS4 Exploit Host | https://github.com/Night-King-Host/Night-King-Host.github.io | 0 | 0| 
| 20210317T11:51:20Z | Exploit Development - Weaponized Exploit and Proof of Concepts (PoC)  | https://github.com/VoidSec/Exploit-Development | 19 | 7| 
| 20210317T11:44:52Z | this is my own exploit, should be private, uses krnl api | https://github.com/XGodsOfWorldsX/Rainer_X-V1.3 | 0 | 0| 
| 20210317T11:35:13Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9148 | 1474| 
| 20210317T11:31:36Z | PS4 Exploits 1.01-7.55 | https://github.com/Buzbee/Buzbee.github.io | 0 | 1| 
| 20210317T11:26:46Z | Null | https://github.com/M0nsterRED/exploit | 0 | 0| 
| 20210317T11:24:03Z | Null | https://github.com/Whomever0/exploit-scripts | 0 | 0| 
| 20210317T11:22:55Z | The Hybrid Fake Face (HFF) dataset is built by exploiting the PGGAN, StyleGAN, Glow, and StarGAN.  | https://github.com/EricGzq/Hybrid-Fake-Face-Dataset | 7 | 0| 
| 20210317T11:13:40Z | Bu Tool İle Local ağdaki bir exploit%i Dış ağa taşıyabilirsiniz. | https://github.com/adeka299aaa/Adeka-MSF-Tool | 2 | 1| 
| 20210317T11:02:23Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 11 | 6| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210317T01:37:46Z | Code for the paper Explanation-Guided Backdoor Poisoning Attacks Against Malware Classifiers | https://github.com/ClonedOne/MalwareBackdoors | 1 | 0| 
| 20210317T00:33:09Z | IPD-H4K8M05-BS series IP-Camera ( Boavision Branded - Hisee P2P - Hankwebs / Hankvision_- 2016 Backdoor Account) | https://github.com/sperglord8008s/IPD-H4K8M05-BS-Camera-Firmware | 0 | 0| 
| 20210316T21:10:49Z | Null | https://github.com/Delle9999/backdoor | 0 | 0| 
| 20210316T17:59:08Z | without any backdoor 🖤 good night Fourloko! | https://github.com/gladoonxyz/fourlokoQBoTSource | 0 | 0| 
| 20210316T17:45:53Z | Null | https://github.com/rippyCoder/backdoor | 0 | 0| 
| 20210316T16:30:12Z | Python KeyLogger | https://github.com/sak110/backdoor | 0 | 0| 
| 20210316T16:26:24Z | Null | https://github.com/wintertee/wso-backdoor | 0 | 0| 
| 20210316T16:12:10Z | kumpulan shell backdoor | https://github.com/FRMFOX/SH3LL-BKDR | 0 | 0| 
| 20210316T15:55:44Z | I created this script to help make it easier for you to directly attack index.html on the website | https://github.com/penucuriCode/shell-backdoor | 1 | 0| 
| 20210316T15:42:29Z | backdoor para windows com opção de baixar arquivos,shell reversa e outros | https://github.com/The-Dark-Hall/backdoor | 1 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210317T01:34:22Z | Fuzzy matching utilities for GNU Emacs | https://github.com/auto-complete/fuzzy-el | 44 | 11| 
| 20210317T01:24:20Z | Null | https://github.com/fernzhao524/Naive-Bayes-and-Fuzzy | 0 | 0| 
| 20210317T00:58:59Z | SecLists is the security tester%s companion. It%s a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. | https://github.com/danielmiessler/SecLists | 30412 | 15474| 
| 20210317T00:50:55Z | Scalable fuzzing infrastructure. | https://github.com/google/clusterfuzz | 4462 | 425| 
| 20210317T00:48:27Z | A Haskell library for fuzzy text search | https://github.com/runarorama/fuzzyfind | 8 | 0| 
| 20210317T00:40:58Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 0| 
| 20210317T00:32:36Z | Fuzz 403/401ing endpoints for bypasses | https://github.com/intrudir/403fuzzer | 28 | 6| 
| 20210317T00:08:58Z | data analytics from kaggle | https://github.com/CYKDataWorld/fuzzy-carnival | 0 | 0| 
| 20210316T23:39:28Z | REST API Fuzz Testing (RAFT): Source code for self-hosted service developed for Azure, including the API, orchestration engine, and default set of security tools (including MSR%s RESTler), that enables developers to embed security tooling into their CI/CD workflows | https://github.com/microsoft/rest-api-fuzz-testing | 116 | 18| 
| 20210316T23:08:31Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6084 | 1222| 



# 日更新程序
