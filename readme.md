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


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210415 | CobaltStrike上线Chrome 0day | https://misakikata.github.io/2021/04/CobaltStrike%E4%B8%8A%E7%BA%BFChrome-0day/| 
| 20210415 | 深入 .NET ViewState 反序列化及其利用 | https://mp.weixin.qq.com/s/RlY5HL_ak4G8EdcXyevWDg| 
| 20210415 | 推特Chrome 0.5day漏洞分析 | https://mp.weixin.qq.com/s/O81Kw-ujcbjY_1S6dFKpxQ| 
| 20210415 | “域前置Cobalt Strike”之踩坑 | https://mp.weixin.qq.com/s/Wh-A3qiyrjPv0KzYeAS-Xw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210415T12:46:56Z | CVE-2021-24086 | Proof of concept for CVE-2021-24086, a NULL dereference in tcpip.sys triggered remotely. | https://github.com/0vercl0k/CVE-2021-24086 | Windows TCP/IP Denial of Service Vulnerability| 
| 20210415T12:03:59Z | CVE-2021-25646 | CVE-2021-25646 Apache Druid 远程代码执行漏洞 Wker脚本 | https://github.com/givemefivw/CVE-2021-25646 | Apache Druid includes the ability to execute user-provided JavaScript code embedded in various types of requests. This functionality is intended for use in high-trust environments, and is disabled by default. However, in Druid 0.20.0 and earlier, it is possible for an authenticated user to send a specially-crafted request that forces Druid to run user-provided JavaScript code for that request, regardless of server configuration. This can be leveraged to execute code on the target machine with the privileges of the Druid server process.| 
| 20210415T11:20:53Z | CVE-2020-14882 | Null | https://github.com/nice0e3/CVE-2020-14882_Exploit_Gui | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210415T10:10:15Z | cve-2020-13777 | Zeek script to detect servers vulnerable to CVE-2020-13777 | https://github.com/0xxon/cve-2020-13777 | GnuTLS 3.6.x before 3.6.14 uses incorrect cryptography for encrypting a session ticket (a loss of confidentiality in TLS 1.2, and an authentication bypass in TLS 1.3). The earliest affected version is 3.6.4 (2018-09-24) because of an error in a 2018-09-18 commit. Until the first key rotation, the TLS server always uses wrong data in place of an encryption key derived from an application.| 
| 20210415T10:07:36Z | cve-2020-0601 | Zeek package to detect CVE-2020-0601 | https://github.com/0xxon/cve-2020-0601 | A spoofing vulnerability exists in the way Windows CryptoAPI (Crypt32.dll) validates Elliptic Curve Cryptography (ECC) certificates.An attacker could exploit the vulnerability by using a spoofed code-signing certificate to sign a malicious executable, making it appear the file was from a trusted, legitimate source, aka %Windows CryptoAPI Spoofing Vulnerability%.| 
| 20210415T09:44:20Z | CVE-2020-25078 | Null | https://github.com/S0por/CVE-2020-25078 | An issue was discovered on D-Link DCS-2530L before 1.06.01 Hotfix and DCS-2670L through 2.02 devices. The unauthenticated /config/getuser endpoint allows for remote administrator password disclosure.| 
| 20210415T09:43:53Z | CVE-2021-26295 | Null | https://github.com/S0por/CVE-2021-26295-Apache-OFBiz-EXP | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 
| 20210415T09:27:37Z | CVE-2021-22192 | CVE-2021-22192 靶场： 未授权用户 RCE 漏洞 | https://github.com/lyy289065406/CVE-2021-22192 | An issue has been discovered in GitLab CE/EE affecting all versions starting from 13.2 allowing unauthorized authenticated users to execute arbitrary code on the server.| 
| 20210415T07:07:10Z | CVE-2020-7461 | PoC for DHCP vulnerability (NAME:WRECK) in FreeBSD | https://github.com/knqyf263/CVE-2020-7461 | In FreeBSD 12.1-STABLE before r365010, 11.4-STABLE before r365011, 12.1-RELEASE before p9, 11.4-RELEASE before p3, and 11.3-RELEASE before p13, dhclient(8) fails to handle certain malformed input related to handling of DHCP option 119 resulting a heap overflow. The heap overflow could in principle be exploited to achieve remote code execution. The affected process runs with reduced privileges in a Capsicum sandbox, limiting the immediate impact of an exploit.| 
| 20210415T03:06:06Z | cve-2021-29627 | Trigger-only for CVE-2021-29627 | https://github.com/raymontag/cve-2021-29627 | In FreeBSD 13.0-STABLE before n245050, 12.2-STABLE before r369525, 13.0-RC4 before p0, and 12.2-RELEASE before p6, listening socket accept filters implementing the accf_create callback incorrectly freed a process supplied argument string. Additional operations on the socket can lead to a double free or use after free.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210415T10:17:46Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1672 | 489| 
| 20210415T02:12:28Z | Spring 2021 Geography 817 work folder  | https://github.com/klee12/klee12.github.io | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210415T12:56:22Z | linux post-exploitation framework made by linux user | https://github.com/jm33-m0/emp3r0r | 446 | 83| 
| 20210415T12:50:47Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 12 | 8| 
| 20210415T12:48:44Z | Educational platform to present and exploit three attacks : Arp Poisoning, DHCP Spoofing and VoIP Eavesdropping.  | https://github.com/khoukhi2021/Attacks-on-virtual-machines | 0 | 0| 
| 20210415T12:42:36Z | Windows Exploit Development Tutorial Series | https://github.com/whichbuffer/WindowsExploitDev | 0 | 1| 
| 20210415T12:42:28Z | Exploit_Scripts | https://github.com/wendy9593/Exploit_Scripts | 1 | 0| 
| 20210415T12:40:15Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9273 | 1502| 
| 20210415T12:30:56Z | Computer Network Exploitation (CNE) Field Manual | https://github.com/mzet-/z-field-manual | 2 | 2| 
| 20210415T12:02:42Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 21 | 8| 
| 20210415T11:53:16Z | Exploit allowing to load arbitrary code on the PSX using only a memory card (no game needed) | https://github.com/brad-lin/FreePSXBoot | 142 | 12| 
| 20210415T11:20:53Z | Null | https://github.com/nice0e3/CVE-2020-14882_Exploit_Gui | 10 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210415T11:44:18Z | Hidden backdoor attack on NMT | https://github.com/chichidd/HiddenBackdoorNMT | 0 | 0| 
| 20210415T11:11:46Z | Null | https://github.com/lishaofeng/NLP_Backdoor | 0 | 0| 
| 20210415T09:41:43Z | Null | https://github.com/SwartzSego/BackDoor | 0 | 0| 
| 20210415T08:17:19Z | Backdoor is going to be an interactive web console for Elixir & Phoenix projects | https://github.com/amberbit/backdoor | 2 | 1| 
| 20210415T07:38:11Z | Defense-resistant backdoor attacks with model-dependent trigger | https://github.com/chenyanjiao-zju/Defense-Resistant-Backdoor | 1 | 0| 
| 20210415T07:22:51Z | 🤖An Evil and Smart Bot for Enslaving Windows. | https://github.com/wildonion/katyusha | 3 | 1| 
| 20210415T01:30:47Z | Threat Emulation and Red Teaming Framework, The Hacking Software for normal people. | https://github.com/quantumcored/remote_hacker_probe | 40 | 5| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210415T12:42:14Z | Null | https://github.com/DEEPAKKK07/fuzzy-enigma | 0 | 0| 
| 20210415T12:40:48Z | Null | https://github.com/Edelweislk/UTS-SimulasiFuzzyLogic | 0 | 0| 
| 20210415T12:39:07Z | Null | https://github.com/Edelweislk/Simulasi-Fuzzy-Logic | 0 | 0| 
| 20210415T12:20:11Z | Coverage-guided, in-process fuzzing for the JVM | https://github.com/CodeIntelligenceTesting/jazzer | 279 | 15| 
| 20210415T12:19:37Z | This is a mini project i am currently working on to show my skills as a web dev. My friend suggested me to use github to show code to others so, I uploaded all the work i%ve done so far(except cloudinary file which contains credentials). there is still some work to do. | https://github.com/tisaravind/fuzzy-waddle | 0 | 0| 
| 20210415T12:16:26Z | Golf totems | https://github.com/simonproudfoot/fuzzy-golf | 0 | 0| 
| 20210415T12:16:03Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 2 | 3| 
| 20210415T11:48:08Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6200 | 1250| 
| 20210415T11:34:08Z | Fuzzing, analysis response and detect vulnerability web application | https://github.com/hoangthanhnguyen/bigdig | 0 | 0| 
| 20210415T11:31:29Z | A case study of a fuzzer in the Java Language | https://github.com/fuzzing-unb/jfuzzer | 1 | 1| 



# 日更新程序
