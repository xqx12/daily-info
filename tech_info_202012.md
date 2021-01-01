# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20201230 | Operation SignSight - 针对越南政府 CA 机构的软件供应链攻击行动 | https://www.welivesecurity.com/2020/12/17/operation-signsight-supply-chain-attack-southeast-asia/| 
| 20201230 | 基于 macOS 最新的 Virtualization.framework 框架创建一个 ARM Linux 虚拟机实例 | https://blog.xpnsec.com/bring-your-own-vm-mac-edition/| 
| 20201230 | Windows 内网、域控安全方向的自动化脚本 | https://github.com/S3cur3Th1sSh1t/WinPwn| 
| 20201230 | Palo Alto 对近些年 DNS 历史漏洞的整理分析 | https://unit42.paloaltonetworks.com/dns-vulnerabilities/| 
| 20201230 | Mobile Physical Memory Security | https://corellium.com/blog/mobile-physical-memory-security| 
| 20201230 | Reverse Engineering For Everyone! | https://github.com/mytechnotalent/Reverse-Engineering-Tutorial| 
| 20201230 | A Visual Studio Code Extension agent for Mythic C2 | https://github.com/MythicAgents/venus| 
| 20201230 | Harvis - 渗透测试时自动化构建 C&C 基础设施的工具 | https://github.com/thiagomayllart/Harvis| 
| 20201230 | 这两天远程线上举办的 CCC 安全会议的部分视频已经公开了 | https://media.ccc.de/c/rc3| 
| 20201230 | Apple 对 iOS 模拟器公司 Corellium 的诉讼败诉了 | https://sec.today/pulses/1a8ef835-2e98-4a2e-b17d-5962767d02df/| 
| 20201230 | Apple 对 iOS 模拟器公司 Corellium 的诉讼败诉了 | https://www.washingtonpost.com/technology/2020/12/29/apple-corellium-lawsuit/| 
| 20201230 | 针对新型 Golang 编写蠕虫在服务器上投放 XMRig Miner 病毒分析。 | https://paper.seebug.org/1440/| 
| 20201230 | 日本航空航天公司川崎官方警告客户数据泄露。 | https://threatpost.com/japanese-aerospace-firm-kawasaki-warns-of-data-breach/162642/| 
| 20201230 | Vimb- 一款Vim的web浏览器项目 | https://github.com/fanglingsu/vimb| 
| 20201229 | GPS circle spoofing discovered in Iran | https://www.gpsworld.com/gps-circle-spoofing-discovered-in-iran/| 
| 20201229 | PcapMonkey - 用于分析 pcap 网络数据包并从中检测威胁的工具 | https://github.com/certego/PcapMonkey| 
| 20201229 | KeyDecoder - 有安全研究员开发了一款基于图片分析钥匙凹槽参数的 App | https://github.com/MaximeBeasse/KeyDecoder| 
| 20201229 | 勒索软件相关的报告收集 | https://github.com/d4rk-d4nph3/Ransomware-Reports| 
| 20201229 | 新网络边缘的智能DNS：DNS加密的新兴要求部署。 | https://blogs.akamai.com/2020/12/smart-dns-for-the-new-network-edge-emerging-requirements-for-dns-encryption.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+TheAkamaiBlog+%28The+Akamai+Blog%29| 
| 20201228 | 针对 SMTP 协议的渗透测试 | https://luemmelsec.github.io/Pentest-Everything-SMTP/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20201231 | MDAT - 综合数据库攻击利用工具 | https://github.com/SafeGroceryStore/MDAT| 
| 20201231 | 2020 南京大学 “操作系统：设计与实现” | https://www.bilibili.com/video/BV1N741177F5| 
| 20201231 | opencve: CVE Alerting Platform | https://github.com/opencve/opencve| 
| 20201230 | 基于机器学习的漏洞检测高影响因素实证研究 | https://www.anquanke.com/post/id/220795| 
| 20201230 | 关于Python病毒样本的分析方法 | https://www.anquanke.com/post/id/226721| 
| 20201230 | apkleaks: Scanning APK file for URIs, endpoints & secrets | https://github.com/dwisiswant0/apkleaks| 
| 20201230 | reverse engineering course covering x86, x64, ARM | https://github.com/mytechnotalent/Reverse-Engineering-Tutorial| 
| 20201230 | AD-Pentest-Notes: 用于记录内网渗透(域渗透)学习 | https://github.com/chriskaliX/AD-Pentest-Notes| 
| 20201230 | FreeRTOS Reverse Engineering | https://mp.weixin.qq.com/s/mnus1BN1CLX4rhrZ1ubnKQ| 
| 20201229 | 静态程序分析入门教程 | https://github.com/RangerNJU/Static-Program-Analysis-Book| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20201231T23:45:40Z | CVE-2020-9484 | Null | https://github.com/PenTestical/CVE-2020-9484 | When using Apache Tomcat versions 10.0.0-M1 to 10.0.0-M4, 9.0.0.M1 to 9.0.34, 8.5.0 to 8.5.54 and 7.0.0 to 7.0.103 if a) an attacker is able to control the contents and name of a file on the server; and b) the server is configured to use the PersistenceManager with a FileStore; and c) the PersistenceManager is configured with sessionAttributeValueClassNameFilter=%null% (the default unless a SecurityManager is used) or a sufficiently lax filter to allow the attacker provided object to be deserialized; and d) the attacker knows the relative file path from the storage location used by FileStore to the file the attacker has control over; then, using a specifically crafted request, the attacker will be able to trigger remote code execution via deserialization of the file under their control. Note that all of conditions a) to d) must be true for the attack to succeed.| 
| 20201231T20:04:01Z | CVE-2020-8417 | Null | https://github.com/Rapidsafeguard/codesnippets_CVE-2020-8417 | The Code Snippets plugin before 2.14.0 for WordPress allows CSRF because of the lack of a Referer check on the import menu.| 
| 20201231T19:25:16Z | CVE-2020-24033 | Null | https://github.com/M0NsTeRRR/CVE-2020-24033 | An issue was discovered in fs.com S3900 24T4S 1.7.0 and earlier. The form does not have an authentication or token authentication mechanism that allows remote attackers to forge requests on behalf of a site administrator to change all settings including deleting users, creating new users with escalated privileges.| 
| 20201231T19:24:52Z | CVE-2020-17530 | Null | https://github.com/CyborgSecurity/CVE-2020-17530 | Forced OGNL evaluation, when evaluated on raw user input in tag attributes, may lead to remote code execution. Affected software : Apache Struts 2.0.0 - Struts 2.5.25.| 
| 20201231T17:03:34Z | CVE-2020-35728 |  CVE-2020-35728 & Jackson-databind RCE | https://github.com/Al1ex/CVE-2020-35728 | | 
| 20201231T10:52:24Z | CVE-2020-14882 | CodeTest信息收集和漏洞利用工具，可在进行渗透测试之时方便利用相关信息收集脚本进行信息的获取和验证工作，漏洞利用模块可选择需要测试的漏洞模块，或者选择所有模块测试，包含CVE-2020-14882, CVE-2020-2555等，可自己收集脚本后按照模板进行修改。 | https://github.com/xkx518/CodeTest | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20201231T08:42:07Z | CVE-2020-6308 | PoC CVE-2020-6308 | https://github.com/InitRoot/CVE-2020-6308-PoC | SAP BusinessObjects Business Intelligence Platform (Web Services) versions - 410, 420, 430, allows an unauthenticated attacker to inject arbitrary values as CMS parameters to perform lookups on the internal network which is otherwise not accessible externally. On successful exploitation, attacker can scan internal network to determine internal infrastructure and gather information for further attacks like remote file inclusion, retrieve server files, bypass firewall and force the vulnerable server to perform malicious requests, resulting in a Server-Side Request Forgery vulnerability.| 
| 20201231T00:34:51Z | CVE-2020-15999 | Todos los materiales necesarios para la PoC en Chrome y ftview | https://github.com/Marmeus/CVE-2020-15999 | Heap buffer overflow in Freetype in Google Chrome prior to 86.0.4240.111 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page.| 
| 20201230T23:32:45Z | CVE-2020-3161 | Cisco IP Phone 11.7 - Denial of Service (PoC) | https://github.com/uromulou/CVE-2020-3161 | A vulnerability in the web server for Cisco IP Phones could allow an unauthenticated, remote attacker to execute code with root privileges or cause a reload of an affected IP phone, resulting in a denial of service (DoS) condition. The vulnerability is due to a lack of proper input validation of HTTP requests. An attacker could exploit this vulnerability by sending a crafted HTTP request to the web server of a targeted device. A successful exploit could allow the attacker to remotely execute code with root privileges or cause a reload of an affected IP phone, resulting in a DoS condition.| 
| 20201230T21:46:27Z | CVE-2020-6308 | CVE-2020-6308 mass exploiter/fuzzer. | https://github.com/Mulvun/CVE-2020-6308-mass-exploiter | SAP BusinessObjects Business Intelligence Platform (Web Services) versions - 410, 420, 430, allows an unauthenticated attacker to inject arbitrary values as CMS parameters to perform lookups on the internal network which is otherwise not accessible externally. On successful exploitation, attacker can scan internal network to determine internal infrastructure and gather information for further attacks like remote file inclusion, retrieve server files, bypass firewall and force the vulnerable server to perform malicious requests, resulting in a Server-Side Request Forgery vulnerability.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20201231T09:00:51Z | Null | https://github.com/viktorfrom/klee_tutorial | 0 | 0| 
| 20201231T05:36:38Z | Data-driven symbolic execution engine, implemented on top of KLEE | https://github.com/kupl/dd-klee | 0 | 1| 
| 20201231T02:36:22Z | Null | https://github.com/fontworks-fonts/Klee | 2 | 0| 
| 20201230T22:52:12Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1590 | 476| 
| 20201230T10:33:02Z | Null | https://github.com/markhakansson/klee-tutorial | 0 | 0| 
| 20201230T09:32:14Z | Null | https://github.com/DonaldKLee/DonaldKLee | 0 | 0| 
| 20201229T22:09:49Z | Urban Evidence Based Policy | https://github.com/KLeeDE/PUS2020_KLee | 0 | 1| 
| 20201229T13:08:17Z | ⬇️ File Upload/sharing application, used by thousands of webmasters since 2007.  | https://github.com/kleeja-official/kleeja | 107 | 32| 
| 20201228T20:46:28Z | Null | https://github.com/thierry-tct/KLEE-SEMu | 2 | 0| 
| 20201228T17:55:53Z | Null | https://github.com/kleenxcoder/kleenxcoder.github.io | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20201229T10:04:52Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 83 | 22| 
| 20201213T21:27:17Z | Null | https://github.com/sameersaadi/s2e.dev | 0 | 0| 
| 20201211T15:27:29Z | S2 EXAM | https://github.com/hussnain126/S2exam-sp18-bse-126 | 0 | 0| 
| 20201211T15:24:26Z | Null | https://github.com/nooraftabcheema/S2exam | 0 | 0| 
| 20201211T15:02:25Z | S2 EXAM | https://github.com/Ahsanch01/SP18-BSE-180-A-S2EXAM | 0 | 0| 
| 20201211T14:22:56Z | Null | https://github.com/iamaliakram/S2EXAM | 0 | 0| 
| 20201204T19:44:50Z | Your S2E project management tools. Visit https://s2e.systems/docs to get started. | https://github.com/S2E/s2e-env | 71 | 30| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20201231T22:31:02Z | Roblox Exploit, Almost full lua executor, unlimited. | https://github.com/xrva/ExTRar | 0 | 0| 
| 20201231T21:26:22Z | A general purpose memory allocator that implements an isolation security strategy to mitigate memory safety issues while maintaining good performance | https://github.com/struct/isoalloc | 126 | 9| 
| 20201231T21:22:38Z | ZetaSploit Framework is a powerful exploitation framework that contains a lot of modules for attacking targets, interacting with targets, exploiting common vulnerabilities and etc. | https://github.com/EntySec/ZetaSploit | 7 | 3| 
| 20201231T21:20:03Z | Utilizar macros e VBA do Office para executar programas maliciosos. | https://github.com/joaopedrordepaiva/MacroExploit | 0 | 0| 
| 20201231T21:09:03Z | Goploit is a tool focused on WebHacking, which is still in development! in your initial project phase. Counting from the start with just 5 commands. You can use the -h parameter to see the Goploit help! | https://github.com/blackcrw/Goploit | 9 | 2| 
| 20201231T20:55:01Z | A tool to scan PHP files and analyze your project to find any malicious code inside it. It provides a text terminal console interface to scan files in a given directory and find PHP code files the seem to contain malicious code. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 160 | 29| 
| 20201231T20:53:08Z | Protekt Protocol puts crypto to work insuring users against hacks, bugs, and exploits of any DeFi protocol or smart contract. The goal is to support and catalyze the growth of the DeFi ecosystem by protecting users from getting rekt. | https://github.com/ProtektProtocol/protekt-protocol-contracts | 4 | 1| 
| 20201231T20:49:56Z | Exploiy | https://github.com/ANRPlays/Exploit | 0 | 0| 
| 20201231T20:45:24Z | a buffer overflow exploit in go for 2016%s Mirai botnet | https://github.com/TotallyNotMalicious/mirai-overflow | 0 | 0| 
| 20201231T20:34:33Z | Exploit for Laravel Remote Code Execution with API_KEY (CVE-2018-15133) | https://github.com/aljavier/exploit_laravel_cve-2018-15133 | 2 | 4| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20201231T20:55:01Z | A tool to scan PHP files and analyze your project to find any malicious code inside it. It provides a text terminal console interface to scan files in a given directory and find PHP code files the seem to contain malicious code. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 160 | 29| 
| 20201231T16:30:14Z | Detect ip address in apk file to find backdoor app%s owner | https://github.com/JuyunLee/apk_ip_hunter | 0 | 0| 
| 20201231T12:53:06Z | Null | https://github.com/cv1002/SoftwareProjectManagerBackdoor | 1 | 5| 
| 20201231T10:47:17Z | Open-Source Remote Administration Tool For Windows C# (Be Based On AsyncRAT) | https://github.com/zhaoweiho/ElegyRAT-C-Sharp | 6 | 1| 
| 20201231T09:34:33Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 19 | 3| 
| 20201231T09:26:30Z | Null | https://github.com/rabbitx1337/backdoor | 0 | 0| 
| 20201231T03:28:05Z | A plugin gives you access to any locked windows pc by calling it with its parameters. It must be run in a cmd enviroment with administrator privilages. | https://github.com/KabueMurage/Windows-Backdoor | 9 | 2| 
| 20201230T22:22:55Z | Null | https://github.com/wcenatus/node-backdoor | 0 | 0| 
| 20201230T18:21:24Z | Null | https://github.com/Veallym0n/resty-socks5-backdoor | 0 | 0| 
| 20201230T17:54:44Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. Ghost Framework gives you the power and convenience of remote Android device administration. | https://github.com/EntySec/ghost | 897 | 452| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20201231T23:15:26Z | Null | https://github.com/lemonstolemonade/fuzzy-adventure | 0 | 0| 
| 20201231T23:10:32Z | Null | https://github.com/hellokatechan/fuzzywuzzy_part1 | 0 | 0| 
| 20201231T22:26:00Z | Null | https://github.com/terminal-labs/fuzzball | 0 | 0| 
| 20201231T21:48:46Z | FuzzBALL: Vine-based Binary Symbolic Execution | https://github.com/bitblaze-fuzzball/fuzzball | 202 | 52| 
| 20201231T20:16:32Z | This is an updated Instagram clone. | https://github.com/virginiah894/Fuzzy_couscious | 0 | 0| 
| 20201231T19:23:34Z | OSS-Fuzz - continuous fuzzing of open source software. | https://github.com/google/oss-fuzz | 5767 | 1145| 
| 20201231T19:23:01Z | Null | https://github.com/Anonster/fuzz | 0 | 0| 
| 20201231T18:50:42Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 229 | 31| 
| 20201231T18:30:50Z | A unit test-like interface for fuzzing and symbolic execution | https://github.com/trailofbits/deepstate | 583 | 61| 
| 20201231T15:44:52Z | Easy to use and powerful fuzzy string matching, port of fuzzywuzzy. | https://github.com/nol13/fuzzball.js | 212 | 23| 



# 日更新程序
