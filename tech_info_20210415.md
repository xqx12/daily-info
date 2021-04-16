# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210415 | 讲解 BinaryNinja 2.3 版本中的两个新功能， Type 和 Variable Cross-References（xrefs）。 | https://binary.ninja/2021/04/12/type-and-variable-xrefs.html| 
| 20210415 | RDMA is Turing complete, we just did not know it yet! | https://arxiv.org/pdf/2103.13351.pdf| 
| 20210415 | 黑客利用 SEO（搜索引擎优化）策略将商业用户引导到由黑客控制看似合法的 Google 站点，并感染 RAT 木马。 | https://threatpost.com/google-sites-solarmarket-rat/165396/| 
| 20210415 | 继 Android 支持 Rust 开发之后，Android 团队探讨 Rust 在 Linux kernel 中的开发。 | https://security.googleblog.com/2021/04/rust-in-linux-kernel.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+GoogleOnlineSecurityBlog+%28Google+Online+Security+Blog%29| 
| 20210415 | Samsung TEE 安全研究系列：利用特权驱动程序的漏洞，将 TEE 的内存映射到 Android 应用中，实现可读可写。 | https://www.riscure.com/blog/samsung-investigation-part3| 
| 20210415 | 与 CVE-2021-21220 和 CVE-2021-21206 具有相似原理和利用的漏洞分析。 | https://abiondo.me/2019/01/02/exploiting-math-expm1-v8/| 
| 20210415 | CVE-2021-24027：Android WhatsApp 的 MitD（Man-in-the-Disk）远程利用漏洞的分析。 | https://census-labs.com/news/2021/04/14/whatsapp-mitd-remote-exploitation-CVE-2021-24027/| 
| 20210415 | pyMalleableC2：用于解析 Cobalt Strike Malleable C2 配置文件的 Python 库。 | https://github.com/Porchetta-Industries/pyMalleableC2| 
| 20210415 | CVE-2021-1647：Windows Defender（mpengine.dll）远程代码执行 | https://googleprojectzero.github.io/0days-in-the-wild//0day-RCAs/2021/CVE-2021-1647.html| 
| 20210415 | 利用ngrok传播样本挖矿溯源。 | https://blog.netlab.360.com/miner-delivery-sample-via-ngrok-tunnel/| 
| 20210415 | Chrome 远程代码执行漏洞（CVE-2021-21220）. | https://paper.seebug.org/1556/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210415 | CobaltStrike上线Chrome 0day | https://misakikata.github.io/2021/04/CobaltStrike%E4%B8%8A%E7%BA%BFChrome-0day/| 
| 20210415 | 深入 .NET ViewState 反序列化及其利用 | https://mp.weixin.qq.com/s/RlY5HL_ak4G8EdcXyevWDg| 
| 20210415 | 推特Chrome 0.5day漏洞分析 | https://mp.weixin.qq.com/s/O81Kw-ujcbjY_1S6dFKpxQ| 
| 20210415 | “域前置Cobalt Strike”之踩坑 | https://mp.weixin.qq.com/s/Wh-A3qiyrjPv0KzYeAS-Xw| 
| 20210415 | 网络空间测绘：IP洞察 | https://mp.weixin.qq.com/s/gVTyhwgxC-UUxhB4YdXKeg| 
| 20210415 | 英国网络作战力量浅析 | https://mp.weixin.qq.com/s/z7Uq5vYotZBNk1yqJqAHxw| 
| 20210415 | Chromium V8 JavaScript引擎远程代码执行漏洞分析讨论 | http://noahblog.360.cn/chromium_v8_remote_code_execution_vulnerability_analysis/| 
| 20210415 | Java执行shellcode的几种方法 | https://mp.weixin.qq.com/s/p74WQwOfkSSZlsuRDke8jw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210415T23:34:04Z | CVE-2020-7461 | PoC for DHCP vulnerability (NAME:WRECK) in FreeBSD | https://github.com/knqyf263/CVE-2020-7461 | In FreeBSD 12.1-STABLE before r365010, 11.4-STABLE before r365011, 12.1-RELEASE before p9, 11.4-RELEASE before p3, and 11.3-RELEASE before p13, dhclient(8) fails to handle certain malformed input related to handling of DHCP option 119 resulting a heap overflow. The heap overflow could in principle be exploited to achieve remote code execution. The affected process runs with reduced privileges in a Capsicum sandbox, limiting the immediate impact of an exploit.| 
| 20210415T23:11:26Z | CVE-2021-24086 | Proof of concept for CVE-2021-24086, a NULL dereference in tcpip.sys triggered remotely. | https://github.com/0vercl0k/CVE-2021-24086 | Windows TCP/IP Denial of Service Vulnerability| 
| 20210415T16:18:46Z | CVE-2021-22986 | Null | https://github.com/nice0e3/CVE-2021-22986_F5_BIG_IP_GUI_Exploit | On BIG-IP versions 16.0.x before 16.0.1.1, 15.1.x before 15.1.2.1, 14.1.x before 14.1.4, 13.1.x before 13.1.3.6, and 12.1.x before 12.1.5.3 amd BIG-IQ 7.1.0.x before 7.1.0.3 and 7.0.0.x before 7.0.0.2, the iControl REST interface has an unauthenticated remote command execution vulnerability. Note: Software versions which have reached End of Software Development (EoSD) are not evaluated.| 
| 20210415T15:51:18Z | CVE-2021-21402 | Null | https://github.com/somatrasss/CVE-2021-21402 | Jellyfin is a Free Software Media System. In Jellyfin before version 10.7.1, with certain endpoints, well crafted requests will allow arbitrary file read from a Jellyfin server%s file system. This issue is more prevalent when Windows is used as the host OS. Servers that are exposed to the public Internet are potentially at risk. This is fixed in version 10.7.1. As a workaround, users may be able to restrict some access by enforcing strict security permissions on their filesystem, however, it is recommended to update as soon as possible.| 
| 20210415T14:19:10Z | CVE-2021-26295 | Null | https://github.com/S0por/CVE-2021-26295-Apache-OFBiz-EXP | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 
| 20210415T14:19:01Z | CVE-2020-25078 | Null | https://github.com/S0por/CVE-2020-25078 | An issue was discovered on D-Link DCS-2530L before 1.06.01 Hotfix and DCS-2670L through 2.02 devices. The unauthenticated /config/getuser endpoint allows for remote administrator password disclosure.| 
| 20210415T12:03:59Z | CVE-2021-25646 | CVE-2021-25646 Apache Druid 远程代码执行漏洞 Wker脚本 | https://github.com/givemefivw/CVE-2021-25646 | Apache Druid includes the ability to execute user-provided JavaScript code embedded in various types of requests. This functionality is intended for use in high-trust environments, and is disabled by default. However, in Druid 0.20.0 and earlier, it is possible for an authenticated user to send a specially-crafted request that forces Druid to run user-provided JavaScript code for that request, regardless of server configuration. This can be leveraged to execute code on the target machine with the privileges of the Druid server process.| 
| 20210415T11:20:53Z | CVE-2020-14882 | Null | https://github.com/nice0e3/CVE-2020-14882_Exploit_Gui | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210415T10:10:15Z | cve-2020-13777 | Zeek script to detect servers vulnerable to CVE-2020-13777 | https://github.com/0xxon/cve-2020-13777 | GnuTLS 3.6.x before 3.6.14 uses incorrect cryptography for encrypting a session ticket (a loss of confidentiality in TLS 1.2, and an authentication bypass in TLS 1.3). The earliest affected version is 3.6.4 (2018-09-24) because of an error in a 2018-09-18 commit. Until the first key rotation, the TLS server always uses wrong data in place of an encryption key derived from an application.| 
| 20210415T10:07:36Z | cve-2020-0601 | Zeek package to detect CVE-2020-0601 | https://github.com/0xxon/cve-2020-0601 | A spoofing vulnerability exists in the way Windows CryptoAPI (Crypt32.dll) validates Elliptic Curve Cryptography (ECC) certificates.An attacker could exploit the vulnerability by using a spoofed code-signing certificate to sign a malicious executable, making it appear the file was from a trusted, legitimate source, aka %Windows CryptoAPI Spoofing Vulnerability%.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210415T22:13:51Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210415T16:35:20Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 123 | 12| 
| 20210415T10:17:46Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1672 | 489| 
| 20210415T02:12:28Z | Spring 2021 Geography 817 work folder  | https://github.com/klee12/klee12.github.io | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210415T23:52:38Z | A collection of challenge writeups, CVE POC%s, and explanations | https://github.com/0xmanjoos/Exploit-Development | 1 | 1| 
| 20210415T23:42:54Z | A simple exploit that I wrote for my old school website :)) | https://github.com/kn1pnc/etelg-ph | 0 | 0| 
| 20210415T22:59:32Z | Sécurité des logiciels et exploitation de vulnérabilités | https://github.com/ppepos/inf600c | 4 | 0| 
| 20210415T22:43:18Z | Extra goodies for GEF: Open repository for unfiltered contributions to the project. | https://github.com/hugsy/gef-extras | 56 | 25| 
| 20210415T22:32:32Z | my https://exploit.education/ writeups | https://github.com/amirr0r/exploit-exercises | 0 | 0| 
| 20210415T22:22:03Z | A python script file to statically and dynamically investigate and analyse binary files for buffer overflow exploits. | https://github.com/BroadbentT/BINARY-MASTER | 4 | 0| 
| 20210415T22:21:49Z | Jenkins exploit for Servers without authentication | https://github.com/Hacker5preme/jenkins-exploit | 0 | 0| 
| 20210415T21:43:58Z | Various ASM, C and C++ tools, shellcodes and exploit experiments. | https://github.com/forrest-orr/ExploitDev | 5 | 0| 
| 20210415T21:35:12Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9279 | 1504| 
| 20210415T21:31:21Z | Exploit distribution system for A&D competitions | https://github.com/pomo-mondreganto/neo | 1 | 1| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210415T19:15:10Z | A simple java backdoor | https://github.com/mav8557/JavaBackdoor | 0 | 0| 
| 20210415T18:58:55Z | A webshell that can bypass some system security | https://github.com/22XploiterCrew-Team/Gel4y-Mini-Shell-Backdoor | 25 | 5| 
| 20210415T18:02:33Z | Reverse TCP trojan backdoor written in python | https://github.com/userlandkernel/Pyrovalerone | 3 | 0| 
| 20210415T17:32:19Z | A demo and explanation of how backdoor poisoning in the form of a Trojan work in neural networks | https://github.com/adit-bala/Introduction-to-Trojans-in-AI | 0 | 0| 
| 20210415T17:16:06Z | Null | https://github.com/Wrench56/Backdoor | 0 | 0| 
| 20210415T14:51:29Z | A Potato-themed backdoor developed in C#.  | https://github.com/malwaredetective/spudnet | 0 | 0| 
| 20210415T14:16:43Z | Abrir um backdoor utilizando o ESP32 e Arduino Leonardo Pro Micro | https://github.com/unifgabsantos/Backdoor_USB | 0 | 0| 
| 20210415T11:44:18Z | Hidden backdoor attack on NMT | https://github.com/chichidd/HiddenBackdoorNMT | 0 | 0| 
| 20210415T11:11:46Z | Null | https://github.com/lishaofeng/NLP_Backdoor | 0 | 0| 
| 20210415T09:41:43Z | Null | https://github.com/SwartzSego/BackDoor | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210415T23:38:20Z | SSL and TLS protocol test suite and fuzzer | https://github.com/tlsfuzzer/tlsfuzzer | 374 | 87| 
| 20210415T23:08:12Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 1| 
| 20210415T23:06:12Z | A demo chat bot interface. | https://github.com/Chuabacca/FuzzyChatBot | 0 | 0| 
| 20210415T23:02:43Z | Fuzzing on JSON parsers. | https://github.com/Kanatoko/jsonfuzz | 0 | 0| 
| 20210415T22:51:09Z | Null | https://github.com/gabrielcramer/fuzzy-calculator | 0 | 0| 
| 20210415T22:23:49Z | A cross-platform browser fuzzing framework | https://github.com/MozillaSecurity/grizzly | 235 | 31| 
| 20210415T21:48:11Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2315 | 124| 
| 20210415T21:40:13Z | Null | https://github.com/forallfuzzers/fuzzers | 0 | 1| 
| 20210415T21:20:51Z | Usermode code for the ARM OS fuzzer project | https://github.com/jprx/arm-os-fuzzer-usercode | 0 | 0| 
| 20210415T20:57:03Z | Null | https://github.com/sudomakeinstall2/fuzzgoat-js | 0 | 0| 



# 日更新程序
