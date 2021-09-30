# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210930 | 远程判断目标系统是否运行 Web Client service (WebDAV) 的工具 | http://github.com/xforcered/GetWebDAVStatus| 
| 20210930 | 天价手续费分析：我不是真土豪 | https://mp.weixin.qq.com/s?__biz=MzU4ODQ3NTM2OA==&mid=2247492157&idx=1&sn=791e7d52dbb9704ceb22e809be388454&chksm=fdde9cbacaa915ac5ef8f3041c9fdcffb926aa7e3c0025a141fa8d20f1c5adde55f07e8d44ec&token=1743499466&lang=zh_CN#rd| 
| 20210930 | FormBook 恶意软件已经集成了 Office 365 漏洞 CVE-2021-40444 | https://www.trendmicro.com/en_us/research/21/i/formbook-adds-latest-office-365-0-day-vulnerability-cve-2021-404.html| 
| 20210930 | Cisco Hyperflex: How We Got RCE Through Login Form and Other Findings | https://swarm.ptsecurity.com/cisco-hyperflex-how-we-got-rce-through-login-form-and-other-findings/| 
| 20210930 | Mariana Trench - Facebook 开源的一款 Android 静态漏洞扫描工具 | https://github.com/facebook/mariana-trench/| 
| 20210930 | TCTF 2021 quickjs Promise exploit writeup | https://mem2019.github.io/jekyll/update/2021/09/27/TCTF2021-Promise.html| 
| 20210930 | Apple AirTag 丢失报告网站发现 XSS 漏洞，特殊构造 AirTag 标识符可以将“拾金不昧”者重定向到钓鱼网站 | https://krebsonsecurity.com/2021/09/apple-airtag-bug-enables-good-samaritan-attack/| 
| 20210930 | PixStealer - 基于 Android Accessibility 服务编写的一款恶意软件 | https://research.checkpoint.com/2021/pixstealer-a-new-wave-of-android-banking-trojans-abusing-accessibility-services/| 
| 20210930 | 基于 Windows 的 RPC 接口实现反弹 Shell 的工具 | https://sensepost.com/blog/2021/building-an-offensive-rpc-interface/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210930 | 基于图神经网络的二进制代码相似性检测技术 | https://mp.weixin.qq.com/s/FU-G1L--_1vFlaR9Wx64JA| 
| 20210930 | 攻防演练之反序列化漏洞与内存马 | https://mp.weixin.qq.com/s/q3h8Lqby_LKZo-8wMYl7nw| 
| 20210930 | crawlergo 动态爬虫源码学习 | https://mp.weixin.qq.com/s/votEOvJafPjCka7gIB8DEA| 
| 20210930 | 通过主动学习和再生成技术来应对软件供应链中的威胁 | https://mp.weixin.qq.com/s/RNL_kuGvoPzYEPbJ2fYFRw| 
| 20210930 | 安全运营中心（SOC）技术框架 | https://mp.weixin.qq.com/s/4LmvqBYJeTOPa237-vaZeQ| 
| 20210930 | 基于腾讯云的分布式蜜罐开发实战 | https://mp.weixin.qq.com/s/C443I605MfAwBSxf0PP8sg| 
| 20210930 | semgrep:Find bug variants with patterns that look like sou... | https://github.com/returntocorp/semgrep| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210930T11:33:38Z | CVE-2021-34730 | Cisco RV110w UPnP stack overflow  | https://github.com/badmonkey7/CVE-2021-34730 | A vulnerability in the Universal Plug-and-Play (UPnP) service of Cisco Small Business RV110W, RV130, RV130W, and RV215W Routers could allow an unauthenticated, remote attacker to execute arbitrary code or cause an affected device to restart unexpectedly, resulting in a denial of service (DoS) condition. This vulnerability is due to improper validation of incoming UPnP traffic. An attacker could exploit this vulnerability by sending a crafted UPnP request to an affected device. A successful exploit could allow the attacker to execute arbitrary code as the root user on the underlying operating system or cause the device to reload, resulting in a DoS condition. Cisco has not released software updates that address this vulnerability.| 
| 20210930T11:09:28Z | CVE-2021-3493 | Ubuntu OverlayFS Local Privesc | https://github.com/briskets/CVE-2021-3493 | The overlayfs implementation in the linux kernel did not properly validate with respect to user namespaces the setting of file capabilities on files in an underlying file system. Due to the combination of unprivileged user namespaces along with a patch carried in the Ubuntu kernel to allow unprivileged overlay mounts, an attacker could use this to gain elevated privileges.| 
| 20210930T10:06:37Z | CVE-2021-22005 | CVE-2021-22005 - VMWare vCenter Server File Upload to RCE | https://github.com/r0ckysec/CVE-2021-22005 | The vCenter Server contains an arbitrary file upload vulnerability in the Analytics service. A malicious actor with network access to port 443 on vCenter Server may exploit this issue to execute code on vCenter Server by uploading a specially crafted file.| 
| 20210930T09:58:13Z | CVE-2021-22015 | Scanner for vScalation (CVE-2021-22015) a Local Privilege Escalation in VMWare vCenter | https://github.com/PenteraIO/vScalation-CVE-2021-22015 | The vCenter Server contains multiple local privilege escalation vulnerabilities due to improper permissions of files and directories. An authenticated local user with non-administrative privilege may exploit these issues to elevate their privileges to root on vCenter Server Appliance.| 
| 20210930T09:57:46Z | CVE-2021-40444 | CVE-2021-40444 - Fully Weaponized Microsoft Office Word RCE Exploit | https://github.com/klezVirus/CVE-2021-40444 | Microsoft MSHTML Remote Code Execution Vulnerability| 
| 20210930T08:21:05Z | CVE-2021-30632 | Null | https://github.com/Lagal1990/CVE-2021-30632 | 未查询到CVE信息| 
| 20210930T08:16:17Z | CVE-2021-22005 | Null | https://github.com/rwincey/CVE-2021-22005 | The vCenter Server contains an arbitrary file upload vulnerability in the Analytics service. A malicious actor with network access to port 443 on vCenter Server may exploit this issue to execute code on vCenter Server by uploading a specially crafted file.| 
| 20210930T07:14:32Z | CVE-2021-35211 | Simple Serv-U CVE-2021-35211 PoC | https://github.com/NattiSamson/Serv-U-CVE-2021-35211 | Microsoft discovered a remote code execution (RCE) vulnerability in the SolarWinds Serv-U product utilizing a Remote Memory Escape Vulnerability. If exploited, a threat actor may be able to gain privileged access to the machine hosting Serv-U Only. SolarWinds Serv-U Managed File Transfer and Serv-U Secure FTP for Windows before 15.2.3 HF2 are affected by this vulnerability.| 
| 20210930T07:06:07Z | CVE-2020-2950 | Null | https://github.com/tuo4n8/CVE-2020-2950 | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Fusion Middleware (component: Analytics Web General). Supported versions that are affected are 5.5.0.0.0, 11.1.1.9.0, 12.2.1.3.0 and 12.2.1.4.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle Business Intelligence Enterprise Edition. Successful attacks of this vulnerability can result in takeover of Oracle Business Intelligence Enterprise Edition. CVSS 3.0 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210930T01:44:17Z | CVE-2021-35211 | Simple Serv-U CVE-2021-35211 PoC | https://github.com/NattiSamson/erv-U-CVE-2021-35211 | Microsoft discovered a remote code execution (RCE) vulnerability in the SolarWinds Serv-U product utilizing a Remote Memory Escape Vulnerability. If exploited, a threat actor may be able to gain privileged access to the machine hosting Serv-U Only. SolarWinds Serv-U Managed File Transfer and Serv-U Secure FTP for Windows before 15.2.3 HF2 are affected by this vulnerability.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210930T03:53:45Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2804 | 75| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210930T05:07:03Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 163 | 37| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210930T11:58:00Z | This repository contains some resources for ethical hackers penetration tester 😊 This may contain some files, tools, books, and links that need to be used for good purposes only. Do not do any illegal work using these sources. | https://github.com/rng70/Hacking-Resources | 9 | 0| 
| 20210930T11:35:16Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 10151 | 1709| 
| 20210930T11:03:09Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 32 | 19| 
| 20210930T10:46:35Z | Collection of Discord hacking tools/fun stuff/exploits that is completely developed using NodeJS. | https://github.com/I2rys/ODiscord | 7 | 4| 
| 20210930T10:12:17Z | a few school exploits | https://github.com/whyisthesheep/ITExploits | 0 | 0| 
| 20210930T09:59:56Z | Cyber Threat Intelligence Data, Indicators, and Analysis | https://github.com/vuldb/cyber_threat_intelligence | 0 | 0| 
| 20210930T09:50:34Z | XSS | https://github.com/King-Sign/Javascript-Exploitation | 0 | 0| 
| 20210930T09:45:22Z | An introduction course to system exploitation based on pwnable.kr challenges | https://github.com/BenH11235/pwnable_writeup | 0 | 0| 
| 20210930T09:42:37Z | Roblox exploit under development | https://github.com/Unknown3958/UnknownExploit | 0 | 0| 
| 20210930T09:35:57Z | Null | https://github.com/ysfcndgr/Exploit-Gelistirme-WriteUp | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210930T01:18:13Z | Offensive RPC PoC | https://github.com/sensepost/offensive-rpc | 5 | 2| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210930T10:19:07Z | radius is a fast binary emulation and symbolic execution framework using radare2 | https://github.com/aemmitt-ns/radius | 101 | 7| 
| 20210930T07:38:35Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 476 | 75| 
| 20210930T05:07:03Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 163 | 37| 
| 20210930T01:01:40Z | A symbolic execution engine for Chisel circuits. | https://github.com/ekiwi/maltese | 0 | 1| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210930T11:18:03Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 26 | 5| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210930T11:57:59Z | Null | https://github.com/antonio-morales/Fuzzing101 | 405 | 38| 
| 20210930T11:52:02Z | Planning tool | https://github.com/HappyDustbunny/FuzzyFlexx | 1 | 0| 
| 20210930T11:43:30Z | Null | https://github.com/ShoaibShafiMir/fuzzy-octo-train | 0 | 0| 
| 20210930T11:35:29Z | Null | https://github.com/jimmyEllison/fuzzy-sniffle | 0 | 0| 
| 20210930T10:19:19Z | Null | https://github.com/afleissner2019/fuzzy-match | 0 | 0| 
| 20210930T09:53:37Z | Fuzz using Rust | https://github.com/cz7047/fur | 0 | 0| 
| 20210930T09:47:04Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3704 | 879| 
| 20210930T09:23:26Z | Recent Fuzzing Paper | https://github.com/wcventure/FuzzingPaper | 988 | 169| 
| 20210930T08:46:10Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 3 | 1| 
| 20210930T08:41:11Z | Null | https://github.com/PaulPextra/fuzzy-disco | 0 | 0| 



# 日更新程序
