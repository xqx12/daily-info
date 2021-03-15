# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210315 | 利用 Differential Fuzzing 的方法挖掘正则表达式的漏洞 | https://defparam.medium.com/finding-issues-in-regular-expression-logic-using-differential-fuzzing-30d78d4cb1d5| 
| 20210315 | Hacking Windows HTTP Server - IIS | https://drive.google.com/file/d/1O0IARjqP4Pwa-ae1nAP8Nr9qb0ai2XPu/view| 
| 20210315 | Java 序列化开源组件 XStream 被发现多个高危漏洞 | http://x-stream.github.io/security.html| 
| 20210315 | Vajra - Web 渗透测试自动化的信息收集工具 | https://github.com/r3curs1v3-pr0xy/vajra| 
| 20210315 | Windows 2020 年的补丁的提权与 Diff 分析 | https://wumb0.in/extracting-and-diffing-ms-patches-in-2020.html| 
| 20210315 | BSidesSF CTF 2021 Writeup | https://blog.skullsecurity.org/2021/bsidessf-ctf-2021-author-writeup-shellcode-primer-runme-runme2-and-runme3| 
| 20210315 | Red Hat Linux iSCSI Subsystem Vulnerability Report | https://versprite.com/blog/threat-intelligence/red-hat-linux-iscsi-subsystem-vulnerability/| 
| 20210315 | Google 对 Spectre CPU 漏洞的研究进展：实现了一个 JS 版本的更快的 PoC 泄露浏览器内存 | https://security.googleblog.com/2021/03/a-spectre-proof-of-concept-for-spectre.html?m=1| 
| 20210315 | 国内开源堡垒机 JumpServer 远程命令执行你可能不知道的点 | https://mp.weixin.qq.com/s/lbcYzNsiOYZRwQzAIYxg3g| 
| 20210315 | Linux内核AF_VSOCK套接字条件竞争漏洞（CVE-2021-26708）分析 | https://sec.today/pulses/5c53e308-dc18-4d09-b5ae-4b7b0614b77e/| 
| 20210315 | Linux内核AF_VSOCK套接字条件竞争漏洞（CVE-2021-26708）分析 | https://mp.weixin.qq.com/s/WMFkPJOd29yOiGoC92QFJA| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210315 | 隐蔽信道：隐形网络 | https://www.sec-in.com/article/57| 
| 20210315 | SecWiki周刊（第367期) | https://www.sec-wiki.com/weekly/367| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210315T11:50:31Z | CVE-2021-26855 | CVE-2021-26855: PoC (Not a HoneyPoC for once!) | https://github.com/ZephrFish/Exch-CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210315T11:21:18Z | CVE-2021-26855 | PoC of proxylogon chain SSRF(CVE-2021-26855) to write file by testanull, censored by github | https://github.com/hackerschoice/CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210315T11:14:21Z | CVE-2020-0096 | CVE-2020-0096-StrandHogg2 复现 | https://github.com/tea9/CVE-2020-0096-StrandHogg2 | In startActivities of ActivityStartController.java, there is a possible escalation of privilege due to a confused deputy. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-8.0 Android-8.1 Android-9Android ID: A-145669109| 
| 20210315T10:14:58Z | CVE-2021-26855 | RCE exploit for ProxyLogon vulnerability in Microsoft Exchange | https://github.com/mil1200/ProxyLogon-CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210315T09:43:02Z | 未知编号 | Null | https://github.com/0xmahmoudJo0/Check_Emails_For_CVE_2021_26855 | 未查询到CVE信息| 
| 20210315T06:48:15Z | CVE-2021-229861 | CVE-2021-229861 | https://github.com/adminwaf/CVE-2021-229861 | | 
| 20210315T06:45:24Z | CVE-2021-22986 | CVE-2021-22986 | https://github.com/adminwaf/CVE-2021-22986 | 未查询到CVE信息| 
| 20210315T05:30:16Z | cve-2021-21300 | Null | https://github.com/ETOCheney/cve-2021-21300 | Git is an open-source distributed revision control system. In affected versions of Git a specially crafted repository that contains symbolic links as well as files using a clean/smudge filter such as Git LFS, may cause just-checked out script to be executed while cloning onto a case-insensitive file system such as NTFS, HFS+ or APFS (i.e. the default file systems on Windows and macOS). Note that clean/smudge filters have to be configured for that. Git for Windows configures Git LFS by default, and is therefore vulnerable. The problem has been patched in the versions published on Tuesday, March 9th, 2021. As a workaound, if symbolic link support is disabled in Git (e.g. via `git config --global core.symlinks false`), the described attack won%t work. Likewise, if no clean/smudge filters such as Git LFS are configured globally (i.e. _before_ cloning), the attack is foiled. As always, it is best to avoid cloning repositories from untrusted sources. The earliest impacted version is 2.14.2. The fix versions are: 2.30.1, 2.29.3, 2.28.1, 2.27.1, 2.26.3, 2.25.5, 2.24.4, 2.23.4, 2.22.5, 2.21.4, 2.20.5, 2.19.6, 2.18.5, 2.17.62.17.6.| 
| 20210315T03:12:08Z | CVE-2021-26855 | CVE-2021-26855, also known as Proxylogon, is a server-side request forgery (SSRF) vulnerability in Exchange that allows an attacker to send arbitrary HTTP requests and authenticate as the Exchange server. According to Orange Tsai, the researcher who discovered the vulnerabilities, CVE-2021-26855 allows code execution when chained with CVE-2021-27065 (see below). A successful exploit chain would allow an unauthenticated attacker to "execute arbitrary commands on Microsoft Exchange Server through only an open 443 port." More information and a disclosure timeline are available at https://proxylogon.com. | https://github.com/raheel0x01/CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210315T02:54:24Z | CVE-2021-26855 | Null | https://github.com/alt3kx/CVE-2021-26855_PoC | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210315T11:08:46Z | klee.js is a (data driven) generator and wrapper for the magnificent three.js | https://github.com/trenc/klee.js | 1 | 0| 
| 20210315T10:25:06Z | 程序员哥哥，你是来找可莉玩的吗？可莉语音包，适用于 vscode-rainbow-fart 拓展。 | https://github.com/Ran-ying/Klee-rainbow-fart | 3 | 0| 
| 20210315T08:05:25Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 332 | 7| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210315T12:19:15Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 99 | 24| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210315T12:23:43Z | CAUTION - Malicious files | https://github.com/Am0rphous/Malware | 18 | 6| 
| 20210315T12:15:26Z | forked version of funtuna, a homebrew ps2 app launcher designed to ease the pain of getting a stable exploit for those that have a console uncompatible with FreeMcBoot | https://github.com/israpps/Funtuna-Fork | 3 | 0| 
| 20210315T12:13:52Z | Secure systems engineering course assignments and exploits | https://github.com/adithyasrinivas11/Secure_Systems_IITM | 0 | 0| 
| 20210315T12:13:18Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 11 | 6| 
| 20210315T12:09:11Z | Exploit Development on my road to OSCP | https://github.com/macosta-42/Exploit-Development | 0 | 0| 
| 20210315T12:02:55Z | Zerologon Check and Exploit - Discovered by Tom Tervoort of Secura and expanded on @Dirkjanm%s cve-2020-1472 coded example | https://github.com/sho-luv/zerologon | 1 | 0| 
| 20210315T11:43:08Z | Vulnerabilities% Risk of Exploitation | https://github.com/thiagofigcosta/V-REx | 0 | 0| 
| 20210315T11:42:08Z | IoC determination for exploitation of CVE-2021-26855, CVE-2021-26857, CVE-2021-26858 and CVE-2021-27065. | https://github.com/sgnls/exchange-0days-202103 | 5 | 4| 
| 20210315T11:40:06Z | Thi powershell script has got to run in remote windows host, even for pivoting | https://github.com/FabioDefilippo/winallenum | 2 | 1| 
| 20210315T11:35:14Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9130 | 1470| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210315T10:38:12Z | Python KeyLogger | https://github.com/sak110/backdoor | 0 | 0| 
| 20210315T08:12:27Z | Protect your server against backdoors. | https://github.com/Xalalau/backdoor-shield | 1 | 0| 
| 20210315T05:58:12Z | Injectra injects shellcode payloads into MacOS applications and package installers. | https://github.com/Taguar258/injectra | 10 | 3| 
| 20210315T03:57:17Z | An implementation of using self attention to detect the backdoor of RNN | https://github.com/Flynn-ML2019/Detection-of-RNN-backdoor-with-self-attention | 2 | 1| 
| 20210315T00:52:18Z | A Remote Administration Tool (RAT) | https://github.com/0xmanjoos/Pieta | 4 | 1| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210315T11:56:23Z | The Official Fuzzy Britches Repository. | https://github.com/ThePapaw/fuzzybritches | 0 | 0| 
| 20210315T11:46:55Z | Null | https://github.com/JumGame44/fuzz-build | 0 | 0| 
| 20210315T11:46:05Z | Towards fuzzing ROS 2 automatically | https://github.com/JnxF/automatic_fuzzing | 0 | 0| 
| 20210315T11:39:07Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 0| 
| 20210315T11:14:34Z | Attila%s website on GitHub | https://github.com/attilavajdaxyz/fuzzy-engine | 0 | 0| 
| 20210315T10:51:07Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6074 | 1216| 
| 20210315T10:16:36Z | Rockyou for web fuzzing | https://github.com/six2dez/OneListForAll | 213 | 45| 
| 20210315T09:49:18Z | Null | https://github.com/TheCloverly/fuzzy-train | 0 | 0| 
| 20210315T09:10:08Z | Null | https://github.com/HaoJame/FuzzAFL | 0 | 0| 
| 20210315T08:50:44Z | Jan%s Fuzzy System (JFS) | https://github.com/inniyah/jfs-fuzzy | 0 | 0| 



# 日更新程序
