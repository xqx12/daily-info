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
| 20210402 | 国内伪基站垃圾短信生态系统研究 | https://mp.weixin.qq.com/s/te4igYM_PHbf2xedXdmQxw| 
| 20210402 | 驱动病毒那些事(三)----APC注入 | https://www.sec-in.com/article/994| 
| 20210401 | 驱动病毒那些事(二)----回调 | https://www.sec-in.com/article/992| 
| 20210401 | 邬晓磊：基于关键词的大型红蓝对抗经验分享 | https://mp.weixin.qq.com/s/8boR_ZucLk5nMJwfi2UdGA| 
| 20210401 | 洞态IAST Agent正式开源 | https://mp.weixin.qq.com/s/iSHmK4Fbl0whDvIH-u8tag| 
| 20210401 | 鸠占鹊巢: Furucombo 攻击事件分析 | https://mp.weixin.qq.com/s/jDQhFNEeIMT_cdjHkggYjw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210403T12:10:03Z | CVE-2021-21972 | Null | https://github.com/password520/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210403T10:07:21Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210403T08:56:32Z | CVE-2021-21975 | [CVE-2021-21975] VMware vRealize Operations Manager API Server Side Request Forgery (SSRF) | https://github.com/murataydemir/CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 
| 20210403T02:35:05Z | CVE-2021-3156 | Sudo Baron Samedit Exploit | https://github.com/worawit/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210403T02:21:23Z | CVE-2021-21975 | Nmap script to check vulnerability CVE-2021-21975 | https://github.com/GuayoyoCyber/CVE-2021-21975 | | 
| 20210403T02:01:20Z | 未知编号 | Null | https://github.com/feihong-cs/Attacking_Shiro_with_CVE_2020_2555 | 未查询到CVE信息| 
| 20210402T19:12:54Z | CVE-2020-9922 | Null | https://github.com/Wowfunhappy/Fix-Apple-Mail-CVE-2020-9922 | A logic issue was addressed with improved state management. This issue is fixed in macOS Catalina 10.15.6, Security Update 2020-004 Mojave, Security Update 2020-004 High Sierra. Processing a maliciously crafted email may lead to writing arbitrary files.| 
| 20210402T11:30:27Z | CVE-2021-24098 | POC for CVE-2021-24098 | https://github.com/waleedassar/CVE-2021-24098 | Windows Console Driver Denial of Service Vulnerability| 
| 20210402T03:45:52Z | CVE-2021-1699 | POC for CVE-2021-1699 | https://github.com/waleedassar/CVE-2021-1699 | | 
| 20210402T03:06:32Z | CVE-2021-1732 | Null | https://github.com/ltfafei/CVE-2021-1732_exp | Windows Win32k Elevation of Privilege Vulnerability This CVE ID is unique from CVE-2021-1698.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210403T12:51:02Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 376 | 10| 
| 20210403T01:46:19Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 115 | 10| 
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
| 20210403T12:53:31Z | This repository is used to share the files need to complete the exercises in the book How Cybersecurity Really Works: A Hands-On Guide for Total Beginners. NOTE: The file for Chapter 4: Malware uses some real exploit code but is rendered completely benign. This allows for more authentic alsis. Still, it may set off Endpoint Security Software and should be used with caution. Download at your own risk.  | https://github.com/Grubbslinger/How-Cybersecurity-Really-Works | 0 | 0| 
| 20210403T12:32:47Z | Search for Unix binaries that can be exploited to bypass system security restrictions. | https://github.com/t0thkr1s/gtfo | 74 | 14| 
| 20210403T12:25:45Z | System Exploitation Fundamental | https://github.com/JiWonOck/DreamHack | 0 | 0| 
| 20210403T12:10:15Z | Config files for my GitHub profile. | https://github.com/Code-Jester/Roblox-Exploit | 1 | 0| 
| 20210403T12:02:48Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 14 | 7| 
| 20210403T11:56:10Z | Multi camera gathering and exploiting tool | https://github.com/M0tHs3C/Argo | 22 | 14| 
| 20210403T11:41:53Z | A module for Garry%s Mod that mitigates exploits on the Source engine. | https://github.com/danielga/gmsv_serversecure | 62 | 17| 
| 20210403T11:39:07Z | The official Exploit Database repository | https://github.com/offensive-security/exploitdb | 6000 | 1705| 
| 20210403T11:35:10Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9222 | 1491| 
| 20210403T11:31:27Z | if u know any stressers or u own a stresser using bootme leaked src, STOP using it there is backdoors and this script exploits them.  | https://github.com/X-x-X-0/bootme.club-RCE | 1 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210403T12:46:13Z | Fully Undetectable Malware Backdoor | https://github.com/raunvk/stealthware-backdoor | 4 | 2| 
| 20210403T11:31:27Z | if u know any stressers or u own a stresser using bootme leaked src, STOP using it there is backdoors and this script exploits them.  | https://github.com/X-x-X-0/bootme.club-RCE | 1 | 0| 
| 20210403T08:47:50Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 56 | 10| 
| 20210403T08:13:39Z | A pseudo C2 Server and backdoor to *simulate* the way usual C2 server works | https://github.com/alainpetit21/POLY_CY101_client_Server | 0 | 0| 
| 20210403T06:30:22Z | Null | https://github.com/rlarjsdn2313/backdoor | 0 | 0| 
| 20210403T06:00:26Z | I created this script to help make it easier for you to directly attack index.php on the website | https://github.com/penucuriCode/shell-backdoor | 1 | 1| 
| 20210403T01:11:51Z | Null | https://github.com/cranelab/backdoor-museum | 0 | 0| 
| 20210403T00:58:33Z | [Disclaimer FireROOT] This repository is for research purposes only, the use of this code is your responsibility. CONTACT ME: Attack@fireRootHacker.Ga | https://github.com/facenano/fireroothacker | 1 | 1| 
| 20210403T00:42:39Z | Null | https://github.com/ouldevloper/python-backdoor | 0 | 0| 
| 20210402T23:38:25Z | PCI Express DIY hacking toolkit for Xilinx SP605 | https://github.com/Cr4sh/s6_pcie_microblaze | 312 | 79| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210403T12:19:39Z | A mutation-based fuzzing engine for MQTT brokers. | https://github.com/PBearson/MosquittoByte | 0 | 0| 
| 20210403T12:15:12Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 1 | 0| 
| 20210403T11:53:26Z | Fake News Detection, Repository. | https://github.com/hrs2203/fuzzy-pancake | 0 | 0| 
| 20210403T11:05:39Z | Code themes in qualitative data with fuzzy matching | https://github.com/jag1g13/fuzzycoding | 0 | 0| 
| 20210403T10:51:27Z | Recent Fuzzing Paper | https://github.com/wcventure/FuzzingPaper | 797 | 133| 
| 20210403T10:43:24Z | Null | https://github.com/Yin-Lynn-Htun/Fuzzy-shop | 0 | 0| 
| 20210403T09:48:21Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6172 | 1248| 
| 20210403T09:42:32Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2299 | 122| 
| 20210403T08:32:00Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 1| 
| 20210403T08:26:51Z | Null | https://github.com/s9varesc/url-fuzzing-docker | 0 | 0| 



# 日更新程序
