# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210301 | 去年 Black Hat USA 2020 会议的议题视频全部公开了 | https://www.youtube.com/playlist?list=PLH15HpR5qRsXE_4kOSy_SXwFkFQre4AV_| 
| 20210301 | BlackHat USA 2020 会议 “iOS Kernel PAC, One Year Later” 议题的视频 | https://www.youtube.com/watch?v=7zCBOFxATFs&feature=youtu.be| 
| 20210301 | 研究员 Hardik Shah 在 Grayhat 2020 会议的 Fuzzing Workshop 资料 | https://github.com/hardik05/Conferences/tree/main/Grayhat2020| 
| 20210301 | HMDM - 基于 physmeme 项目，将未签名代码直接映射到内核的工具，可以用于漏洞研究学习 | https://githacks.org/_xeroxz/hmdm| 
| 20210301 | Linux 内核 CVE-2020-14381 漏洞的分析 | https://blog.frizn.fr/linux-kernel/cve-2020-14381| 
| 20210301 | Cosmopolitan Libc - 将 C 代码真正编译成跨平台执行的库，一次编译，支持在 Linux + Mac + Windows + FreeBSD + OpenBSD + NetBSD + BIOS 直接 Native 执行。 | https://ahgamut.github.io/c/2021/02/27/ape-cosmo/| 
| 20210301 | Apple 漏洞致谢数全球第一背后的新攻击面 & 一洞攻破 Safari | https://paper.seebug.org/1490/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210301 | SecWiki周刊（第365期) | https://www.sec-wiki.com/weekly/365| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210301T13:01:34Z | CVE-2020-9484 | Null | https://github.com/DXY0411/CVE-2020-9484 | When using Apache Tomcat versions 10.0.0-M1 to 10.0.0-M4, 9.0.0.M1 to 9.0.34, 8.5.0 to 8.5.54 and 7.0.0 to 7.0.103 if a) an attacker is able to control the contents and name of a file on the server; and b) the server is configured to use the PersistenceManager with a FileStore; and c) the PersistenceManager is configured with sessionAttributeValueClassNameFilter=%null% (the default unless a SecurityManager is used) or a sufficiently lax filter to allow the attacker provided object to be deserialized; and d) the attacker knows the relative file path from the storage location used by FileStore to the file the attacker has control over; then, using a specifically crafted request, the attacker will be able to trigger remote code execution via deserialization of the file under their control. Note that all of conditions a) to d) must be true for the attack to succeed.| 
| 20210301T12:16:59Z | CVE-2020-14882 | CVE-2020-14882 | https://github.com/milo2012/CVE-2020-14882 | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210301T10:42:55Z | CVE-2020-11883 | vue-storefront-api | https://github.com/0ndras3k/CVE-2020-11883 | | 
| 20210301T10:23:24Z | CVE-2021-21972 | CVE-2021-21972 Exploit | https://github.com/NS-Sp4ce/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210301T09:33:40Z | CVE-2021-25281 | Chaining CVE-2021-25281 and CVE-2021-25282 to exploit a SaltStack | https://github.com/Immersive-Labs-Sec/CVE-2021-25281 | An issue was discovered in through SaltStack Salt before 3002.5. salt-api does not honor eauth credentials for the wheel_async client. Thus, an attacker can remotely run any wheel modules on the master.| 
| 20210301T07:09:34Z | CVE-2021-21972 | Proof of Concept Exploit for vCenter CVE-2021-21972 | https://github.com/horizon3ai/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210301T06:58:35Z | CVE-2021-21972 | CVE-2021-21972 | https://github.com/milo2012/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210301T02:39:27Z | CVE-2021-21017 | Null | https://github.com/ZeusBox/CVE-2021-21017 | Acrobat Reader DC versions versions 2020.013.20074 (and earlier), 2020.001.30018 (and earlier) and 2017.011.30188 (and earlier) are affected by a heap-based buffer overflow vulnerability. An unauthenticated attacker could leverage this vulnerability to achieve arbitrary code execution in the context of the current user. Exploitation of this issue requires user interaction in that a victim must open a malicious file.| 
| 20210301T02:10:46Z | CVE-2021-21972 | Null | https://github.com/QmF0c3UK/CVE-2021-21972-vCenter-6.5-7.0-RCE-POC | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210301T11:45:19Z | Null | https://github.com/fontworks-fonts/Klee | 370 | 10| 
| 20210301T10:06:41Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1637 | 483| 
| 20210301T08:13:39Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 107 | 4| 
| 20210301T04:28:58Z | Null | https://github.com/abbykleespie/A2AbbyKleespie.appstudio | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210301T13:02:25Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 9 | 4| 
| 20210301T12:55:59Z | CTF竞赛权威指南(Pwn篇) | https://github.com/firmianay/CTF-All-In-One | 2365 | 481| 
| 20210301T12:31:13Z | this bash script is for remote linux hosts hacked! | https://github.com/FabioDefilippo/linuxallenum | 9 | 0| 
| 20210301T11:35:12Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9068 | 1457| 
| 20210301T11:26:57Z | CTF framework and exploit development library | https://github.com/Gallopsled/pwntools | 7576 | 1359| 
| 20210301T11:04:08Z | Pwn misconfigured sites running ShareX custom image uploader API | https://github.com/ecriminal/PwnX.py | 10 | 2| 
| 20210301T10:52:36Z | Thi powershell script has got to run in remote windows host, even for pivoting | https://github.com/FabioDefilippo/winallenum | 2 | 1| 
| 20210301T10:43:20Z | Router Exploitation Tools. Checks for WinBox Authentication Bypass Disclosure, RouterOS Jailbreak, Chimney-Blue SMB BufferOverflow & ByTheWay RCE | https://github.com/s1l3nt78/MkCheck | 91 | 18| 
| 20210301T09:52:54Z | exploiting and defending neural networks(神经网络攻防专栏) | https://github.com/AIPwn/HackingNeuralNetworks | 2 | 0| 
| 20210301T09:39:13Z | ---working on | https://github.com/BloxiYT/Exploits | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210301T11:37:00Z | Thefatrat a massive exploiting tool : Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack and etc . This tool compiles a malware with popular payload and then the compiled malware can be execute on windows, android, mac . The malware that created with this tool also have an ability to bypass most AV software protection . | https://github.com/Screetsec/TheFatRat | 4987 | 1644| 
| 20210301T11:34:00Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) remote administration and post-exploitation tool mainly written in python | https://github.com/n1nj4sec/pupy | 6177 | 1585| 
| 20210301T11:32:37Z | Null | https://github.com/ph-luffy/Backdoor | 1 | 1| 
| 20210301T09:21:29Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. Ghost Framework gives you the power and convenience of remote Android device administration. | https://github.com/EntySec/ghost | 966 | 485| 
| 20210301T08:29:00Z | Null | https://github.com/Wiilldd/backdoor | 0 | 0| 
| 20210301T07:39:22Z | Pegasus backdoor adalah tools Pegasus dalam meretas sistem. Memiliki beberapa fitur yang diperlukan dalam defacing dan pemasangan suatu sistem baru. Anda bisa maintaincing dengan mudahnya menggunakan Pegasus Backdoor | https://github.com/sobri3195/pegasus-backdoor | 0 | 0| 
| 20210301T03:21:00Z | Fud Persistent Windows Backdoor developed purely in python | https://github.com/swagkarna/Chuvi-Botnet | 12 | 5| 
| 20210301T02:15:38Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 172 | 31| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210301T02:06:38Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 5976 | 1200| 
| 20210301T02:00:03Z | FuzzBench - Fuzzer benchmarking as a service. | https://github.com/google/fuzzbench | 603 | 102| 
| 20210301T00:09:11Z | Fast web fuzzer written in Go | https://github.com/ffuf/ffuf | 4028 | 481| 



# 日更新程序
