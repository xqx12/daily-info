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
| 20210405 | GAN的前世今生 | https://mp.weixin.qq.com/s/CGngRxjVtOKHNsTrXBiD7w| 
| 20210405 | 硬件安全技术研究 | https://mp.weixin.qq.com/s/YuYmMryfgFi0XqD96WelHg| 
| 20210405 | SecWiki周刊（第370期) | https://www.sec-wiki.com/weekly/370| 
| 20210404 | 技术分享 , Git-RCE：CVE-2021-21300 | https://mp.weixin.qq.com/s/VO2dHNVbPcpZQtnBRMNNag| 
| 20210403 | 网络空间资产测绘(CAM)能力指南 | https://mp.weixin.qq.com/s/p3LwmZq7nrGOy5qy7p9SDQ| 
| 20210403 | 安全是一门语言的艺术：威胁调查分析语言概述 | https://mp.weixin.qq.com/s/U8E4JxMDeL5IeVGAh9fuiQ| 
| 20210403 | 对美军新近发展作战理念的梳理与思考 | https://mp.weixin.qq.com/s/D8T6ImssRi8sjDqD4_bGpg| 
| 20210403 | DGA域名检测的工程实践 | https://mp.weixin.qq.com/s/GlWqTWQzBfoXt8J8uJAPRQ| 
| 20210403 | CVE-2016-0165 Win32k漏洞分析笔记 | https://xz.aliyun.com/t/9348| 
| 20210402 | 国内伪基站垃圾短信生态系统研究 | https://mp.weixin.qq.com/s/te4igYM_PHbf2xedXdmQxw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210405T10:35:01Z | CVE-2021-3156 | Exploit for Sudo heap overflow (CVE-2021-3156) on Debain 10 | https://github.com/0xdevil/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210405T10:20:40Z | CVE-2021-30109 | Froala Persistent XSS | https://github.com/Hackdwerg/CVE-2021-30109 | 未查询到CVE信息| 
| 20210405T09:36:12Z | CVE-2021-26295 | CVE-2021-26295 Apache OFBiz POC | https://github.com/ltfafei/CVE-2021-26295_Apache_OFBiz_POC | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 
| 20210405T02:43:23Z | 未知编号 | Null | https://github.com/shacojx/CVE_2021_26855_SSRF | 未查询到CVE信息| 
| 20210405T02:36:52Z | CVE-2021-26855 | Null | https://github.com/shacojx/CVE-2021-26855-exploit-Exchange | | 
| 20210405T01:19:25Z | CVE-2021-21975 | Nmap script to check vulnerability CVE-2021-21975 | https://github.com/GuayoyoCyber/CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 
| 20210404T17:29:51Z | CVE-2021-22986 | CVE-2021-22986 & F5 BIG-IP RCE | https://github.com/Al1ex/CVE-2021-22986 | On BIG-IP versions 16.0.x before 16.0.1.1, 15.1.x before 15.1.2.1, 14.1.x before 14.1.4, 13.1.x before 13.1.3.6, and 12.1.x before 12.1.5.3 amd BIG-IQ 7.1.0.x before 7.1.0.3 and 7.0.0.x before 7.0.0.2, the iControl REST interface has an unauthenticated remote command execution vulnerability. Note: Software versions which have reached End of Software Development (EoSD) are not evaluated.| 
| 20210404T15:15:32Z | CVE-2021-3156 | Null | https://github.com/dock0d1/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210404T07:56:06Z | CVE-2020-21224 | 浪潮ClusterEngineV4.0 远程命令执行漏洞扫描脚本。 | https://github.com/MzzdToT/CVE-2020-21224 | A Remote Code Execution vulnerability has been found in Inspur ClusterEngine V4.0. A remote attacker can send a malicious login packet to the control server| 
| 20210404T02:56:12Z | cve-2020-1337 | Null | https://github.com/password520/cve-2020-1337-poc | An elevation of privilege vulnerability exists when the Windows Print Spooler service improperly allows arbitrary writing to the file system, aka %Windows Print Spooler Elevation of Privilege Vulnerability%.| 


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
| 20210405T12:56:30Z | Null | https://github.com/THECyb0rgLab/Exploit-Development | 0 | 0| 
| 20210405T12:55:06Z | Null | https://github.com/r4j0x00/exploits | 426 | 100| 
| 20210405T12:50:39Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 12 | 8| 
| 20210405T12:50:23Z | Herramienta para usar The Browser Exploitation Framework fuera de LAN, con diferentes opciones para hacking | https://github.com/tony23x/beef-for-cerberus | 0 | 0| 
| 20210405T12:49:08Z | JUlia Moon Phase (JuMP) is a Julia script that calculates the moon phase in a given date from the user. It exploits the module %mphase% in the library AstroLib. | https://github.com/robertobastone/JuMP | 0 | 0| 
| 20210405T12:45:48Z | CDK is an open-sourced container penetration toolkit, offering stable exploitation in different slimmed containers without any OS dependency. It comes with penetration tools and many powerful PoCs/EXPs helps you to escape container and takeover K8s cluster easily. | https://github.com/cdk-team/CDK | 1302 | 183| 
| 20210405T12:45:17Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 16 | 7| 
| 20210405T12:35:14Z | A python script file to forensically investigate and analyse binary files for buffer overflow exploits. | https://github.com/BroadbentT/BIN-MASTER | 0 | 0| 
| 20210405T12:35:11Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9225 | 1492| 
| 20210405T12:29:31Z | Random scripts and exploits I used or modified | https://github.com/0iphor13/Scripts-and-Exploits | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210405T12:48:07Z | Obsidian no me pegues por eso xd | https://github.com/NKz32/LeuxBackdoor-0.6-craked- | 0 | 0| 
| 20210405T12:02:40Z | Null | https://github.com/xpf/Backdoor-Learning-arXiv | 1 | 0| 
| 20210405T06:54:13Z | Null | https://github.com/NullCode13/Python-Backdoors | 0 | 0| 
| 20210405T06:36:09Z | I created this script to help make it easier for you to directly attack index.php on the website | https://github.com/penucuriCode/shell-backdoor | 1 | 1| 
| 20210405T01:43:25Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 201 | 34| 
| 20210404T23:10:49Z | Minecraft Server Backdoor Plugin | https://github.com/NeunXKILLER20/PluginPwn | 1 | 0| 
| 20210404T18:59:53Z | Det her er en DEMO af TeamKineser,s Server Filer bygget op på Devo Filer (NO BACKDOOR) | https://github.com/TeamKineser/TeamKineser-DEMO-Filer | 0 | 0| 
| 20210404T18:13:52Z | Invisible, customizable backdoor for Minecraft Spigot Plugins. | https://github.com/ThiccIndustries/Minecraft-Backdoor | 2 | 2| 
| 20210404T16:22:46Z | Thefatrat a massive exploiting tool : Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack and etc . This tool compiles a malware with popular payload and then the compiled malware can be execute on windows, android, mac . The malware that created with this tool also have an ability to bypass most AV software protection . | https://github.com/Screetsec/TheFatRat | 5109 | 1671| 
| 20210404T12:54:46Z | Null | https://github.com/NullCode13/Python-Batch-Backdoors | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210405T12:15:12Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 1 | 0| 
| 20210405T12:15:10Z | Null | https://github.com/s9varesc/url-fuzzing-docker | 0 | 0| 
| 20210405T12:13:51Z | revault_tx fuzz testing corpus | https://github.com/revault/revault_tx_corpus | 0 | 0| 
| 20210405T12:12:19Z | fuzzy-engine | https://github.com/solveforce/fuzzy-engine | 0 | 0| 
| 20210405T12:12:02Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 4 | 1| 
| 20210405T12:06:01Z | Null | https://github.com/s9varesc/url-fuzzing | 1 | 1| 
| 20210405T11:36:07Z | fuzzy-meme | https://github.com/solveforce/fuzzy-meme | 1 | 0| 
| 20210405T11:32:05Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 1| 
| 20210405T11:16:14Z | fuzzeREST is an open-source hard fork of Unity%s Hot-Fuzz | https://github.com/sherbie/fuzzerest | 0 | 0| 
| 20210405T11:15:42Z | Some sort of a social network using react js, hello from 2004 :) | https://github.com/androranogajec/fuzzy-social-network | 0 | 0| 



# 日更新程序
