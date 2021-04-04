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
| 20210403 | 网络空间资产测绘(CAM)能力指南 | https://mp.weixin.qq.com/s/p3LwmZq7nrGOy5qy7p9SDQ| 
| 20210403 | 安全是一门语言的艺术：威胁调查分析语言概述 | https://mp.weixin.qq.com/s/U8E4JxMDeL5IeVGAh9fuiQ| 
| 20210403 | 对美军新近发展作战理念的梳理与思考 | https://mp.weixin.qq.com/s/D8T6ImssRi8sjDqD4_bGpg| 
| 20210403 | DGA域名检测的工程实践 | https://mp.weixin.qq.com/s/GlWqTWQzBfoXt8J8uJAPRQ| 
| 20210403 | CVE-2016-0165 Win32k漏洞分析笔记 | https://xz.aliyun.com/t/9348| 
| 20210402 | 国内伪基站垃圾短信生态系统研究 | https://mp.weixin.qq.com/s/te4igYM_PHbf2xedXdmQxw| 
| 20210402 | 驱动病毒那些事(三)----APC注入 | https://www.sec-in.com/article/994| 
| 20210401 | 驱动病毒那些事(二)----回调 | https://www.sec-in.com/article/992| 
| 20210401 | 邬晓磊：基于关键词的大型红蓝对抗经验分享 | https://mp.weixin.qq.com/s/8boR_ZucLk5nMJwfi2UdGA| 
| 20210401 | 洞态IAST Agent正式开源 | https://mp.weixin.qq.com/s/iSHmK4Fbl0whDvIH-u8tag| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210404T00:15:45Z | CVE-2021-21975 | Nmap script to check vulnerability CVE-2021-21975 | https://github.com/GuayoyoCyber/CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 
| 20210403T23:47:22Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210403T21:17:20Z | CVE-2021-24098 | POC for CVE-2021-24098 | https://github.com/waleedassar/CVE-2021-24098 | Windows Console Driver Denial of Service Vulnerability| 
| 20210403T16:23:43Z | 未知编号 | Null | https://github.com/CyberCommands/CVE2021-21975 | 未查询到CVE信息| 
| 20210403T13:53:06Z | CVE-2020-25213 | Null | https://github.com/piruprohacking/CVE-2020-25213 | The File Manager (wp-file-manager) plugin before 6.9 for WordPress allows remote attackers to upload and execute arbitrary PHP code because it renames an unsafe example elFinder connector file to have the .php extension. This, for example, allows attackers to run the elFinder upload (or mkfile and put) command to write PHP code into the wp-content/plugins/wp-file-manager/lib/files/ directory. This was exploited in the wild in August and September 2020.| 
| 20210403T13:50:42Z | CVE-2020-17453 | PoC (Proof of Concept) - CVE-2020-17453 | https://github.com/JHHAX/CVE-2020-17453-PoC | 未查询到CVE信息| 
| 20210403T12:56:38Z | CVE-2021-22986 | CVE-2021-22986 & F5 BIG-IP RCE | https://github.com/Al1ex/CVE-2021-22986 | On BIG-IP versions 16.0.x before 16.0.1.1, 15.1.x before 15.1.2.1, 14.1.x before 14.1.4, 13.1.x before 13.1.3.6, and 12.1.x before 12.1.5.3 amd BIG-IQ 7.1.0.x before 7.1.0.3 and 7.0.0.x before 7.0.0.2, the iControl REST interface has an unauthenticated remote command execution vulnerability. Note: Software versions which have reached End of Software Development (EoSD) are not evaluated.| 
| 20210403T12:10:03Z | CVE-2021-21972 | Null | https://github.com/password520/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210403T08:56:32Z | CVE-2021-21975 | [CVE-2021-21975] VMware vRealize Operations Manager API Server Side Request Forgery (SSRF) | https://github.com/murataydemir/CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 
| 20210403T02:35:05Z | CVE-2021-3156 | Sudo Baron Samedit Exploit | https://github.com/worawit/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210403T13:51:43Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 377 | 9| 
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
| 20210404T01:02:32Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 14 | 7| 
| 20210404T00:44:21Z | Null | https://github.com/Shrewk/exploit | 0 | 0| 
| 20210404T00:34:20Z | This is a plugin for Minecraft that aids in building, as it gives the player creative mode and charges them for each block they place. All exploits are patched as well. | https://github.com/bsalha1/Printer | 2 | 4| 
| 20210404T00:13:25Z | Thefatrat a massive exploiting tool : Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack and etc . This tool compiles a malware with popular payload and then the compiled malware can be execute on windows, android, mac . The malware that created with this tool also have an ability to bypass most AV software protection . | https://github.com/Screetsec/TheFatRat | 5106 | 1670| 
| 20210403T23:30:19Z | Null | https://github.com/capnhowdie11/OnlyFans-exploit | 0 | 0| 
| 20210403T22:53:06Z | Le but de ce projet est de réaliser un mécanisme d’allocation / désallocation de mémoire inspiré du fameux couple malloc() / free() de la librairie standard. La gestion de l’espace libre (par exemple suite à la suppression de structures allouées) est un aspect important du projet. Le système devra s’appuyer sur une zone mémoire allouée en début de programme. Il y a donc 4 fonctions à écrire pour pouvoir l’utiliser : /* initialisation de la zone de travail */ int initMemory(int nBytes); /* allocation dynamique d’espace dans la zone */ void* myalloc(int nBytes); /* désallocation d’une zone adressée par un pointeur */ int myfree(void* p); /* recuperation de la zone initialement reservee */ int freeMemory(); | https://github.com/tbdev99/Projet-Systeme-d-exploitation-Allocation-Dynamique | 0 | 0| 
| 20210403T22:45:36Z | PS4 Exploit Host | https://github.com/Night-King-Host/Night-King-Host.github.io | 6 | 3| 
| 20210403T22:41:10Z | PS1 savegame exploit | https://github.com/socram8888/tonyhax | 230 | 6| 
| 20210403T22:38:45Z | exploit/unix/selea/authenticated_command_execution | https://github.com/enty8080/selea_authenticated_rce | 1 | 0| 
| 20210403T22:35:28Z | Swiss Boot Memory Cards and Game Save Hacks a la GCMM | https://github.com/GameCubeHomebrew/GameSave-Exploits | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210404T01:08:08Z | Null | https://github.com/password520/Advanced-Backdoor | 0 | 0| 
| 20210404T01:01:51Z | if u know any stressers or u own a stresser using bootme leaked src, STOP using it there is backdoors and this script exploits them.  | https://github.com/X-x-X-0/bootme.club-RCE | 3 | 0| 
| 20210404T00:13:25Z | Thefatrat a massive exploiting tool : Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack and etc . This tool compiles a malware with popular payload and then the compiled malware can be execute on windows, android, mac . The malware that created with this tool also have an ability to bypass most AV software protection . | https://github.com/Screetsec/TheFatRat | 5106 | 1670| 
| 20210403T22:14:59Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 56 | 10| 
| 20210403T21:11:39Z | Fully Undetectable Malware Backdoor | https://github.com/raunvk/stealthware-backdoor | 10 | 5| 
| 20210403T20:31:05Z | Null | https://github.com/Wiilldd/backdoor | 0 | 0| 
| 20210403T08:13:39Z | A pseudo C2 Server and backdoor to *simulate* the way usual C2 server works | https://github.com/alainpetit21/POLY_CY101_client_Server | 0 | 0| 
| 20210403T06:30:22Z | Null | https://github.com/rlarjsdn2313/backdoor | 0 | 0| 
| 20210403T06:00:26Z | I created this script to help make it easier for you to directly attack index.php on the website | https://github.com/penucuriCode/shell-backdoor | 1 | 1| 
| 20210403T01:11:51Z | Null | https://github.com/cranelab/backdoor-museum | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210404T01:02:09Z | My end of year project_ Not done yet ! | https://github.com/Rad-hi/Fuzzy_Fire_Detection | 0 | 0| 
| 20210404T00:08:42Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 1| 
| 20210404T00:05:10Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 1 | 0| 
| 20210404T00:05:01Z | CS 4152 Project | https://github.com/nicbarone/Fuzzy-Kiwi | 0 | 0| 
| 20210403T23:28:23Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 42 | 4| 
| 20210403T22:52:33Z | Fuzzy matching for Neovim | https://github.com/amirrezaask/fuzzy.nvim | 23 | 1| 
| 20210403T22:38:53Z | Null | https://github.com/Juanosorio94/fuzzing-rdma | 0 | 0| 
| 20210403T22:35:48Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 269 | 37| 
| 20210403T22:05:40Z | https://github.com/wcventure/FuzzingPaper | https://github.com/mishmashclone/wcventure-FuzzingPaper | 5 | 1| 
| 20210403T22:00:53Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 4 | 1| 



# 日更新程序
