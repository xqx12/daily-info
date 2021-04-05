# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210402 | James Forshaw：关于 Windows Server Containers 的安全研究背景、过程和一些见解。 | https://googleprojectzero.blogspot.com/2021/04/who-contains-containers.html| 
| 20210402 | 通过函数指针回调，很多 Win 32 的 API 可以被用于执行 shellcode。 | https://osandamalith.com/2021/04/01/executing-shellcode-via-callbacks/| 
| 20210402 | CVE-2021-24098 的 POC。关于 Windows 控制台驱动的拒绝服务漏洞。 | https://github.com/waleedassar/CVE-2021-24098| 
| 20210402 | Mikko Kenttälä：macOS Mail 的一个无交互的漏洞。由于符号连接未正确删除，通过自动解压附件，可以实现在 Mail.app 的沙箱环境中添加或修改任意文件。 | https://mikko-kenttala.medium.com/zero-click-vulnerability-in-apples-macos-mail-59e0c14b106c| 
| 20210402 | 当 ajaxpipe 或 quickling 的参数添加到 Fackbook 的任意站点请求时，错误的响应可能会造成 Facebook 的 access_token 被恶意接管。 | https://ysamm.com/?p=654| 
| 20210402 | Facebook 在 OAuth 认证中的 fallback_redirect_uri 路径检查不完整，使得 Facebook 和 Instagram 账户可以被恶意接管。 | https://ysamm.com/?p=646| 
| 20210402 | ProChecker：用于自动化分析 4G LTE 协议的安全性和隐私框架。 | https://syed-rafiul-hussain.github.io/wp-content/uploads/2021/03/ProChecker.pdf| 
| 20210402 | Michael Stepankin：nOtWASP 前十个让人哭笑不得的漏洞。 | https://portswigger.net/research/notwasp-bottom-10-vulnerabilities-that-make-you-cry| 
| 20210401 | iOS 开源工具 objection ios info binary 输出信息的分析 | https://sensepost.com/blog/2021/on-ios-binary-protections/| 
| 20210401 | How To intercept mutually-authenticated TLS communications of a Java thick client | https://offsec.almond.consulting/java-tls-intercept.html| 
| 20210401 | Starkiller：1.7.0 版本发布。基于 Electron 实现的 Powershell Empire 可视化工具。 | https://github.com/BC-SECURITY/Starkiller/releases| 
| 20210401 | SharpProxyLogon：C# 实现的 ProxyLogon RCE，用于 Microsoft Exchange Server 的 CVE-2021-26855 的利用。 | https://github.com/Flangvik/SharpProxyLogon| 
| 20210401 | 在 Cobalt Strike 工具中，使用 GUID 完成对 shellcode 混淆。 | https://www.guidepointsecurity.com/yet-another-cobalt-strike-loader-guid-edition/| 
| 20210401 | ldsview：用于离线检索 LDIF 的工具。 | http://github.com/kgoins/ldsview| 
| 20210401 | FIREEYE 发布一个用于解析 Windows 后台智能传输服务（BITS）的 Python 工具。 | https://github.com/fireeye/BitsParser| 
| 20210401 | 如何搭建一个 Linux 内核调试环境。 | https://pwning.systems/posts/setting-up-a-kernel-debugging-environment/| 
| 20210401 | Google 发表关于针对安全研究人员攻击的最新活动进展。 | https://blog.google/threat-analysis-group/update-campaign-targeting-security-researchers/| 
| 20210401 | MacOS内核安全性探讨。 | https://www.viva64.com/en/b/0818/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210404 | 技术分享 , Git-RCE：CVE-2021-21300 | https://mp.weixin.qq.com/s/VO2dHNVbPcpZQtnBRMNNag| 
| 20210403 | 网络空间资产测绘(CAM)能力指南 | https://mp.weixin.qq.com/s/p3LwmZq7nrGOy5qy7p9SDQ| 
| 20210403 | 安全是一门语言的艺术：威胁调查分析语言概述 | https://mp.weixin.qq.com/s/U8E4JxMDeL5IeVGAh9fuiQ| 
| 20210403 | 对美军新近发展作战理念的梳理与思考 | https://mp.weixin.qq.com/s/D8T6ImssRi8sjDqD4_bGpg| 
| 20210403 | DGA域名检测的工程实践 | https://mp.weixin.qq.com/s/GlWqTWQzBfoXt8J8uJAPRQ| 
| 20210403 | CVE-2016-0165 Win32k漏洞分析笔记 | https://xz.aliyun.com/t/9348| 
| 20210402 | 国内伪基站垃圾短信生态系统研究 | https://mp.weixin.qq.com/s/te4igYM_PHbf2xedXdmQxw| 
| 20210402 | 驱动病毒那些事(三)----APC注入 | https://www.sec-in.com/article/994| 
| 20210401 | 驱动病毒那些事(二)----回调 | https://www.sec-in.com/article/992| 
| 20210401 | 邬晓磊：基于关键词的大型红蓝对抗经验分享 | https://mp.weixin.qq.com/s/8boR_ZucLk5nMJwfi2UdGA| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210404T19:05:37Z | CVE-2021-21975 | Nmap script to check vulnerability CVE-2021-21975 | https://github.com/GuayoyoCyber/CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 
| 20210404T17:29:51Z | CVE-2021-22986 | CVE-2021-22986 & F5 BIG-IP RCE | https://github.com/Al1ex/CVE-2021-22986 | On BIG-IP versions 16.0.x before 16.0.1.1, 15.1.x before 15.1.2.1, 14.1.x before 14.1.4, 13.1.x before 13.1.3.6, and 12.1.x before 12.1.5.3 amd BIG-IQ 7.1.0.x before 7.1.0.3 and 7.0.0.x before 7.0.0.2, the iControl REST interface has an unauthenticated remote command execution vulnerability. Note: Software versions which have reached End of Software Development (EoSD) are not evaluated.| 
| 20210404T15:15:32Z | CVE-2021-3156 | Null | https://github.com/dock0d1/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210404T07:56:06Z | CVE-2020-21224 | 浪潮ClusterEngineV4.0 远程命令执行漏洞扫描脚本。 | https://github.com/MzzdToT/CVE-2020-21224 | A Remote Code Execution vulnerability has been found in Inspur ClusterEngine V4.0. A remote attacker can send a malicious login packet to the control server| 
| 20210404T02:56:12Z | cve-2020-1337 | Null | https://github.com/password520/cve-2020-1337-poc | An elevation of privilege vulnerability exists when the Windows Print Spooler service improperly allows arbitrary writing to the file system, aka %Windows Print Spooler Elevation of Privilege Vulnerability%.| 
| 20210404T01:15:15Z | CVE-2021-3156 | Null | https://github.com/password520/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210403T23:47:22Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210403T21:17:20Z | CVE-2021-24098 | POC for CVE-2021-24098 | https://github.com/waleedassar/CVE-2021-24098 | Windows Console Driver Denial of Service Vulnerability| 
| 20210403T16:23:43Z | 未知编号 | Null | https://github.com/CyberCommands/CVE2021-21975 | 未查询到CVE信息| 
| 20210403T13:53:06Z | CVE-2020-25213 | Null | https://github.com/piruprohacking/CVE-2020-25213 | The File Manager (wp-file-manager) plugin before 6.9 for WordPress allows remote attackers to upload and execute arbitrary PHP code because it renames an unsafe example elFinder connector file to have the .php extension. This, for example, allows attackers to run the elFinder upload (or mkfile and put) command to write PHP code into the wp-content/plugins/wp-file-manager/lib/files/ directory. This was exploited in the wild in August and September 2020.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210404T11:10:53Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210404T04:27:55Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 378 | 9| 
| 20210404T03:49:15Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 7 | 0| 
| 20210403T13:37:18Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 116 | 10| 
| 20210402T23:50:49Z | Null | https://github.com/abbykleespie/LAWk8AbbyKleespie.appstudio | 0 | 0| 
| 20210402T19:52:36Z | Spring 2021 Geography 817 work folder  | https://github.com/klee12/klee12.github.io | 0 | 0| 
| 20210402T17:02:49Z | Personal Blog | https://github.com/klee1611/klee1611.github.io | 0 | 0| 
| 20210402T12:45:42Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 6 | 1| 
| 20210401T14:21:03Z | Readable String Sanitizer | https://github.com/schemenauero/kleen-js | 0 | 0| 
| 20210401T10:43:57Z | KLEE in the browser | https://github.com/klee/klee-web | 45 | 12| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210402T06:55:39Z | Null | https://github.com/yuvalkirstain/s2e-coref | 2 | 2| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210404T23:02:25Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 14 | 7| 
| 20210404T22:16:28Z | GEF - GDB Enhanced Features for exploit devs & reversers | https://github.com/hugsy/gef | 3564 | 499| 
| 20210404T22:15:15Z | Automated exploitation for the most common cves | https://github.com/RENNAARENATA/CVE-ECSPLOITZ | 0 | 0| 
| 20210404T22:01:25Z | -------> RAFEL<------  Android Rat  Written in Java With WebPanel For Controlling Victims | https://github.com/swagkarna/Rafel-Rat | 67 | 35| 
| 20210404T21:59:41Z | AMES is a tool to parse the new Nessus output files and autogenerate an easy to copy and paste command line exploit using Metasploit CLI | https://github.com/CiscoCXSecurity/AMES | 0 | 0| 
| 20210404T21:56:37Z | Microbiome Analysis Powered By Recursive Quasi-species Networks: Uncovering rules of organization, competition, succession and exploitation | https://github.com/zeroknowledgediscovery/qbiome | 0 | 0| 
| 20210404T21:35:11Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9224 | 1492| 
| 20210404T19:42:11Z | This repository contains tools developed to hack CS:GO. | https://github.com/samdobsonDEV/csgo-exploits | 0 | 0| 
| 20210404T19:02:15Z | Le but de ce projet est de réaliser un mécanisme d’allocation / désallocation de mémoire inspiré du fameux couple malloc() / free() de la librairie standard. La gestion de l’espace libre (par exemple suite à la suppression de structures allouées) est un aspect important du projet. Le système devra s’appuyer sur une zone mémoire allouée en début de programme. Il y a donc 4 fonctions à écrire pour pouvoir l’utiliser : /* initialisation de la zone de travail */ int initMemory(int nBytes); /* allocation dynamique d’espace dans la zone */ void* myalloc(int nBytes); /* désallocation d’une zone adressée par un pointeur */ int myfree(void* p); /* recuperation de la zone initialement reservee */ int freeMemory(); | https://github.com/tbdev99/Projet-Systeme-d-exploitation-Allocation-Dynamique | 0 | 0| 
| 20210404T19:00:32Z | OSINT, Threat Hunting, Network and Web Recon, Discovery, Enumeration, Vulnerability Mapping, Exploitation, Reporting | https://github.com/aryanguenthner/365 | 7 | 4| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210404T23:10:49Z | Minecraft Server Backdoor Plugin | https://github.com/NeunXKILLER20/PluginPwn | 1 | 0| 
| 20210404T18:59:53Z | Det her er en DEMO af TeamKineser,s Server Filer bygget op på Devo Filer (NO BACKDOOR) | https://github.com/TeamKineser/TeamKineser-DEMO-Filer | 0 | 0| 
| 20210404T18:13:52Z | Invisible, customizable backdoor for Minecraft Spigot Plugins. | https://github.com/ThiccIndustries/Minecraft-Backdoor | 2 | 2| 
| 20210404T16:22:46Z | Thefatrat a massive exploiting tool : Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack and etc . This tool compiles a malware with popular payload and then the compiled malware can be execute on windows, android, mac . The malware that created with this tool also have an ability to bypass most AV software protection . | https://github.com/Screetsec/TheFatRat | 5109 | 1670| 
| 20210404T13:51:45Z | Null | https://github.com/NullCode13/Python-Backdoors | 0 | 0| 
| 20210404T12:54:46Z | Null | https://github.com/NullCode13/Python-Batch-Backdoors | 0 | 0| 
| 20210404T12:03:58Z | Null | https://github.com/password520/backdoorppt | 0 | 0| 
| 20210404T11:40:49Z | Null | https://github.com/password520/backdoor | 0 | 0| 
| 20210404T09:15:11Z | Null | https://github.com/kietbuiduc2020/reserve_backdoor-listener | 0 | 0| 
| 20210404T08:54:56Z | A simple python tool to hide backdoor in cookie | https://github.com/krishpranav/backcookie | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210404T12:27:58Z | CPython bytecode instrumentation and forkserver tools for fuzzing pure python and mixed python/c code using AFL | https://github.com/risicle/cpytraceafl | 15 | 2| 
| 20210404T11:55:26Z | My end of year project_ Not done yet ! | https://github.com/Rad-hi/Fuzzy_Fire_Detection | 0 | 0| 
| 20210404T11:48:50Z | Null | https://github.com/s9varesc/url-fuzzing-docker | 0 | 0| 
| 20210404T11:37:10Z | Null | https://github.com/Yin-Lynn-Htun/Fuzzy-shop | 0 | 0| 
| 20210404T10:57:50Z | PoC of fuzzing closed-source userspace binaries with KVM | https://github.com/klecko/kvm-fuzz | 1 | 0| 
| 20210404T10:43:32Z | ### ༒︎᯾𝐀𝐍𝐆𝐑𝐘 𝐅𝐔𝐙𝐙𝐄𝐑᯾༒︎  ### ✰𝙰𝙱𝙾𝚄𝚃✰ > Tools for information gathering,Discover hidden files and directories on a web server. The application tries to find url relative paths of the given website by comparing them with a given set .  ### ✰𝙵𝙴𝙰𝚁𝚄𝚁𝙴𝚂✰  > * Fuzz url set from an input file  > * Concurrent relative path search  > * Configurable number of fuzzing workers  > * Fuzz CMS ==> Wordpress,Durpal,Joomla  > * Generate reports of the valid paths  ### 𝙸𝙽𝚂𝚃𝙰𝙻𝙻𝙰𝚃𝙸𝙾𝙽 : ``` $ apt update && apt upgrade ``` ``` $ apt install git ``` ``` $ apt install python2 ``` ``` $ apt install python ``` ``` $ git clone https://github.com/ihebski/angryFuzzer ``` ``` $ cd angryFuzzer ``` ``` $ pip2 install -r requirements.txt ``` ``` $ pip2 install requests ``` ``` $ chmod +x * ```  ### 𝚄𝚜𝚊𝚐𝚎  : ``` $ python2 angryFuzzer.py -h ``` > It shows all options of this tool  ``` $ python2 angryFuzzer.py -u http:site.com ``` > Now it starts collecting target information...  ### ⚠️ 𝙻𝙴𝙶𝙰𝙻 𝙳𝙸𝚂𝙲𝙻𝙰𝙸𝙼𝙴𝚁 ⚠️  > Usage of Angry Fuzzer for attacking targets without prior mutual consent is illegal. It%s the end user%s responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program. | https://github.com/Zack-sys/AngryFuzzer-Tools-for-information-gathering-Discover-hidden-files-and-directories-on-a-web-server. | 1 | 0| 
| 20210404T10:36:59Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 1| 
| 20210404T10:12:28Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 46 | 6| 
| 20210404T09:03:08Z | fuzzeREST is an open-source hard fork of Unity%s Hot-Fuzz | https://github.com/sherbie/fuzzerest | 0 | 0| 
| 20210404T08:47:18Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6174 | 1248| 



# 日更新程序
