# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210608 | 高通 TEE 可信执行环境（QSEE）漏洞的利用分析 | https://raelize.com/blog/qualcomm-ipq40xx-breaking-into-qsee-using-fault-injection/| 
| 20210608 | YouTube 上有人分享如何为 SerenityOS 打造一款 JS 字节码虚拟机的教程 | https://www.youtube.com/playlist?list=PLMOpZvQB55beChggmvk-sUm8X_vSezpqL| 
| 20210608 | AppLocker-Bypass: Bypassing AppLocker (executing Powershell scripts/commands) with C# | https://github.com/o1mate/AppLocker-Bypass| 
| 20210608 | Project Zero 开源的 Jackalope Fuzzer 支持在 Linux 开启 Sanitizer Coverage 了 | https://github.com/googleprojectzero/Jackalope/blob/main/README_sancov.md| 
| 20210608 | Siloscape - Palo Alto 发现了第一个通过 Windows 容器环境攻击 Kubernetes clusters 的恶意软件 | https://unit42.paloaltonetworks.com/siloscape/| 
| 20210608 | NetGear Nighthawk WiFi 路由器使用的第三方网络套件 QUAGGA 的漏洞分析 | https://versprite.com/blog/security-research/netgear-nighthawk-router-security-bug/?utm_content=169073507&utm_medium=social&utm_source=twitter&hss_channel=tw-146588685| 
| 20210608 | KRF - Kernelspace Randomized Faulter，基于 Fault injection 技术实现的针对 Linux/FreeBSD 平台的 Fuzzer | https://github.com/trailofbits/krf| 
| 20210608 | 研究员 riusksk 对 HITB AMS 2021 会议部分议题的分析 | https://mp.weixin.qq.com/s/5eC3oKLYthmVwzV3gR9ryQ| 
| 20210608 | VCSA 6.5-7.0 远程代码执行 CVE-2021-21985 漏洞分析 | http://noahblog.360.cn/vcenter-cve-2021-2021-21985/| 
| 20210608 | 分析System32系统文件应对DLL搜索顺序劫持行为。 | https://redcanary.com/blog/system32-binaries/| 
| 20210608 | 你的扫描器可以绕过防火墙么？（一） | https://paper.seebug.org/1600/| 
| 20210608 | 白泽带你读论文 ,Favocado: Fuzzing the Binding Code of JavaScript Engines Using Semantically Correct Test Cases--该论文选取自NDSS 2021会议的研究对JS引擎进行模糊测试的文章。 | https://zhuanlan.zhihu.com/p/378952042| 
| 20210608 | 使用 Snyk对PHP Composer 工具安全漏洞检测。 | https://snyk.io/blog/testing-php-composer-security-vulnerabilities-snyk/| 
| 20210608 | Wireshark入门教程视频2021年合集。 | https://www.youtube.com/playlist?list=PLR0bgGon_WTK9PHDzrlje4bqEh3p0NxxX| 
| 20210608 | Windows 内核漏洞利用教程第2部分:堆栈溢出 | https://hacklido.com/blog/147| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210608 | InForSec学术交流会 参会小计DAY2 | https://mp.weixin.qq.com/s/LPRoggcsRIl1xT0xMXpLeQ| 
| 20210608 | InForSec学术交流会 参会小计DAY2 | /news/29266| 
| 20210608 | Snort在工控系统入侵检测的应用 | http://blog.nsfocus.net/snort%e5%9c%a8%e5%b7%a5%e6%8e%a7%e7%b3%bb%e7%bb%9f%e5%85%a5%e4%be%b5%e6%a3%80%e6%b5%8b%e7%9a%84%e5%ba%94%e7%94%a8/| 
| 20210608 | Malicious Lateral Movement Detection 横向移动检测 | http://www.covert.io/four-short-links-on-malicious-lateral-movement-detection/| 
| 20210608 | SecWiki周刊（第379期) | https://www.sec-wiki.com/weekly/379| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210608T21:45:07Z | CVE-2020-8835 | Formal verification example for CVE-2020-8835 | https://github.com/digamma-ai/CVE-2020-8835-verification | In the Linux kernel 5.5.0 and newer, the bpf verifier (kernel/bpf/verifier.c) did not properly restrict the register bounds for 32-bit operations, leading to out-of-bounds reads and writes in kernel memory. The vulnerability also affects the Linux 5.4 stable series, starting with v5.4.7, as the introducing commit was backported to that branch. This vulnerability was fixed in 5.6.1, 5.5.14, and 5.4.29. (issue is aka ZDI-CAN-10780)| 
| 20210608T19:31:54Z | CVE-2021-22911 | Pre-Auth Blind NoSQL Injection leading to Remote Code Execution in Rocket Chat 3.12.1 | https://github.com/CsEnox/CVE-2021-22911 | A improper input sanitization vulnerability exists in Rocket.Chat server 3.11, 3.12 & 3.13 that could lead to unauthenticated NoSQL injection, resulting potentially in RCE.| 
| 20210608T16:08:10Z | CVE-2020-0041 | My implementation for an exploit of the CVE-2020-0041 bug | https://github.com/Byte-Master-101/CVE_2020_0041 | In binder_transaction of binder.c, there is a possible out of bounds write due to an incorrect bounds check. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android kernelAndroid ID: A-145988638References: Upstream kernel| 
| 20210608T15:34:26Z | CVE-2021-26714 | Directory Traversal vulnerability in Enterprise License Manager portal in Mitel MiContact Center Enterprise before 9.4 | https://github.com/PwCNO-CTO/CVE-2021-26714 | | 
| 20210608T15:32:10Z | CVE-2021-21234 | Directory traversal vulnerability in the spring-boot-actuator-logview library | https://github.com/PwCNO-CTO/CVE-2021-21234 | spring-boot-actuator-logview in a library that adds a simple logfile viewer as spring boot actuator endpoint. It is maven package %eu.hinsch:spring-boot-actuator-logview%. In spring-boot-actuator-logview before version 0.2.13 there is a directory traversal vulnerability. The nature of this library is to expose a log file directory via admin (spring boot actuator) HTTP endpoints. Both the filename to view and a base folder (relative to the logging folder root) can be specified via request parameters. While the filename parameter was checked to prevent directory traversal exploits (so that `filename=../somefile` would not work), the base folder parameter was not sufficiently checked, so that `filename=somefile&base=../` could access a file outside the logging base directory). The vulnerability has been patched in release 0.2.13. Any users of 0.2.12 should be able to update without any issues as there are no other changes in that release. There is no workaround to fix the vulnerability other than updating or removing the dependency. However, removing read access of the user the application is run with to any directory not required for running the application can limit the impact. Additionally, access to the logview endpoint can be limited by deploying the application behind a reverse proxy.| 
| 20210608T14:13:49Z | cve-2021-21985 | cve-2021-21985 exploit | https://github.com/xnianq/cve-2021-21985_exp | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210608T05:57:32Z | CVE-2021-29505 | 对CVE-2021-29505进行复现，并分析学了下Xstream反序列化过程 | https://github.com/MyBlackManba/CVE-2021-29505 | XStream is software for serializing Java objects to XML and back again. A vulnerability in XStream versions prior to 1.4.17 may allow a remote attacker has sufficient rights to execute commands of the host only by manipulating the processed input stream. No user who followed the recommendation to setup XStream%s security framework with a whitelist limited to the minimal required types is affected. The vulnerability is patched in version 1.4.17.| 
| 20210608T02:35:21Z | CVE-2021-21985 | Null | https://github.com/testanull/Project_CVE-2021-21985_PoC | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210608T01:26:15Z | CVE-2020-17514 | PoC for exploiting CVE-2020-17514 | https://github.com/JamesGeeee/CVE-2020-17514 | Apache Fineract prior to 1.5.0 disables HTTPS hostname verification in ProcessorHelper in the configureClient method. Under typical deployments, a man in the middle attack could be successful.| 
| 20210608T01:26:05Z | CVE-2021-33839 | PoC for exploiting CVE-2021-33839 | https://github.com/JamesGeeee/CVE-2021-33839 | Luca through 1.7.4 on Android allows remote attackers to obtain sensitive information about COVID-19 tracking because the QR code of a Public Location can be intentionally confused with the QR code of a Private Meeting.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210608T23:50:42Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 656 | 15| 
| 20210608T21:29:16Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 14 | 45| 
| 20210608T18:35:48Z | Null | https://github.com/KLEEEN-SOFTWARE/Kleeen-svgs | 0 | 0| 
| 20210608T16:38:58Z | Null | https://github.com/fontworks-fonts/Klee | 459 | 13| 
| 20210608T13:49:43Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 145 | 14| 
| 20210608T11:39:23Z | Null | https://github.com/JaimePSantos/ResearchKlee | 0 | 0| 
| 20210608T10:40:58Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 18 | 0| 
| 20210608T06:41:04Z | Dodoco doko? | https://github.com/RiceFT/klee | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210608T08:53:41Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 130 | 31| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210608T23:47:13Z | Null | https://github.com/bcattaneo/exur-exploit | 2 | 0| 
| 20210608T22:51:40Z | Null | https://github.com/GreenToxicAura/exploits | 0 | 0| 
| 20210608T22:49:44Z | Various techniques for exploiting Windows | https://github.com/billchaison/Windows-Trix | 5 | 0| 
| 20210608T22:37:15Z | Blog consacré au Raspberry Pi. Au programme : des actualités, des tutoriels en français, des conseils, des projets, et bien plus pour exploiter le maximum de votre framboise ! | https://github.com/Skyost/FramboisePi | 0 | 0| 
| 20210608T21:35:13Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9543 | 1550| 
| 20210608T21:30:39Z | Ryan Johnson and His Exploits | https://github.com/ryancj14/LinkToTheNow | 0 | 0| 
| 20210608T21:24:30Z | A repository for learning  Stack exploitation techniques | https://github.com/xr0o0tx-511/How2Stack | 0 | 0| 
| 20210608T21:07:17Z | Pulsar-Project  Automate Exploitation Radio Frequency | https://github.com/F0rbidden-Equation/Pulsar | 0 | 0| 
| 20210608T20:51:12Z | Null | https://github.com/DiamondHands-Exploit/BedWarsExploit | 0 | 1| 
| 20210608T20:45:34Z | OWASP Benchmark is a test suite designed to verify the speed and accuracy of software vulnerability detection tools. A fully runnable web app written in Java, it supports analysis by Static (SAST), Dynamic (DAST), and Runtime (IAST) tools that support Java. The idea is that since it is fully runnable and all the vulnerabilities are actually exploitable, it’s a fair test for any kind of vulnerability detection tool.  For more details on this project, please see the OWASP Benchmark Project home page. | https://github.com/OWASP/Benchmark | 374 | 343| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210608T21:29:38Z | Undetectable & Xor encrypting with custom KEY (FUD Metasploit Rat) bypass Top Antivirus like BitDefender,Malwarebytes,Avast,ESET-NOD32,AVG,... & Automatically Add ICON and MANIFEST to excitable | https://github.com/persianhydra/Xeexe-TopAntivirusEvasion | 466 | 107| 
| 20210608T21:00:15Z | PHP 8.1.0-dev Backdoor System Shell Script | https://github.com/flast101/php-8.1.0-dev-backdoor-rce | 9 | 3| 
| 20210608T20:46:20Z | Very Easy Relative Backdoor Application | https://github.com/Not-C-Developer/VERBA | 1 | 0| 
| 20210608T19:54:47Z | Creating a Backdoor and attaching Keylogger to the Backdoor | https://github.com/indradhar/Backdoor_With_Keylogger | 0 | 0| 
| 20210608T18:59:28Z | Python 3 IRC Bot / Botnet | https://github.com/trackmastersteve/HackServ | 21 | 17| 
| 20210608T17:51:30Z | Null | https://github.com/EjHvorSerDuVildUdJim/backdoor | 0 | 0| 
| 20210608T16:36:13Z | install meterpreter reverse_tcp  backdoor | https://github.com/Nek0y4nSu/reverse_tcp_meterpreter_installer | 0 | 0| 
| 20210608T15:52:04Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 249 | 43| 
| 20210608T14:04:24Z | Null | https://github.com/KelelawarCyberTeam/Shell-Backdoor | 0 | 0| 
| 20210608T03:36:36Z | php script to gain access to a site once injected | https://github.com/Sliden101/backdoor | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210608T23:19:26Z | Implementation of %Dostrajanie klasyfikatora FUZZY LOGIC z użyciem procedury PSO.%  in python | https://github.com/wujekstaszek/MIO_2021_PSO_FUZZY_LOGIC | 0 | 0| 
| 20210608T22:31:18Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 77 | 21| 
| 20210608T22:23:19Z | fuzzer for the x86 architecture | https://github.com/tomergoodo/x86fuzzer | 0 | 0| 
| 20210608T22:13:33Z | A SpringBoot Application that is vulnerable to value fuzzing | https://github.com/FrancescoDiSalesGithub/DamnVulnerableWebServer | 0 | 0| 
| 20210608T21:47:20Z | Null | https://github.com/marcielfelipe/fuzzy | 0 | 0| 
| 20210608T21:40:53Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210608T20:21:24Z | Null | https://github.com/PoppinOff2/fuzzy-succotash | 0 | 0| 
| 20210608T20:01:58Z | fuzzy_waddle implementation for POE | https://github.com/NathanLangley/fuzzy_waddle_POE | 0 | 0| 
| 20210608T19:56:36Z | Generates Elm types, JSON decoders, JSON encoders and fuzz tests from JSON schema specifications | https://github.com/dragonwasrobot/json-schema-to-elm | 64 | 7| 
| 20210608T19:32:22Z | fuzzy C-Means clustering project, AmirKabir AI course spring 2021 | https://github.com/hamidrezaHemati/fuzzy-C-Means-Clustering | 0 | 0| 



# 日更新程序
