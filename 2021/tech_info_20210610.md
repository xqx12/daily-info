# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210610 | 匿名信使：木马隐蔽通信浅谈 | https://security.tencent.com/index.php/blog/msg/193| 
| 20210610 | Phishing for AWS credentials via AWS SSO device code authentication | https://blog.christophetd.fr/phishing-for-aws-credentials-via-aws-sso-device-code-authentication/| 
| 20210610 | Firefox 安全团队利用 ThreadSanitizer 工具检测 Data Race 条件竞争漏洞的实践 | https://blog.mozilla.org/attack-and-defense/2021/06/09/eliminating-data-races-in-firefox-a-technical-report/| 
| 20210610 | 近几年德国要求重点行业公司、组织要提高应对 APT 攻击的能力，这篇 Blog 分析攻击者可能的攻击入口 | https://s3cur3th1ssh1t.github.io/On-how-to-access-protected-networks/| 
| 20210610 | ESET 对 Gelsemium 攻击组织近期活动的追踪 | https://www.welivesecurity.com/2021/06/09/gelsemium-when-threat-actors-go-gardening/| 
| 20210610 | ALPACA Attack - 针对 TLS 的应用层内容混淆攻击，攻击者可以实现跨子域名间的网络流量重定向 | https://alpaca-attack.com/| 
| 20210610 | I got 99 problems but my NAC ain´t one | https://luemmelsec.github.io/I-got-99-problems-but-my-NAC-aint-one/| 
| 20210610 | 有研究员发现 Microsoft Teams 会将聊天内容保存到本地 Log 日志中 | https://infinitelogins.com/2021/06/06/your-microsoft-teams-chats-arent-as-private-as-you-think/| 
| 20210610 | Windows DWM、图形组件的两个本地提权漏洞的 PoC | https://github.com/mavillon1/CVE-2021-33739-POC| 
| 20210610 | Vcenter Server CVE-2021-21985 RCE PAYLOAD | https://sec.today/pulses/7a6d38df-aa78-4cd1-898c-ac1fea138f34/| 
| 20210610 | Vcenter Server CVE-2021-21985 RCE PAYLOAD | http://www.iswin.org/2021/06/02/Vcenter-Server-CVE-2021-21985-RCE-PAYLOAD/| 
| 20210610 | 利用 Linux 内核漏洞实现 Docker 逃逸 | https://paper.seebug.org/1602/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210610 | 开源 API 网关架构分析 | https://mp.weixin.qq.com/s/L3X3xfGggjf52a8GofFHEQ| 
| 20210610 | 钓鱼页面之无视浏览器URL栏 | https://mp.weixin.qq.com/s/F4GkG1MSOaz3iIGBmDzCTA| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210610T17:27:25Z | CVE-2020-8417 | CSRF Code snippet vulnerability CVE-2020-8417 | https://github.com/Vulnmachines/WordPress_CVE-2020-8417 | The Code Snippets plugin before 2.14.0 for WordPress allows CSRF because of the lack of a Referer check on the import menu.| 
| 20210610T17:26:47Z | CVE-2021-21975 | VMWare-CVE-2021-21975 SSRF vulnerability | https://github.com/Vulnmachines/VMWare-CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 
| 20210610T17:25:54Z | CVE-2020-9496 | Null | https://github.com/Vulnmachines/apache-ofbiz-CVE-2020-9496 | XML-RPC request are vulnerable to unsafe deserialization and Cross-Site Scripting issues in Apache OFBiz 17.12.03| 
| 20210610T17:24:57Z | CVE-2021-25646 | Null | https://github.com/Vulnmachines/Apache-Druid-CVE-2021-25646 | Apache Druid includes the ability to execute user-provided JavaScript code embedded in various types of requests. This functionality is intended for use in high-trust environments, and is disabled by default. However, in Druid 0.20.0 and earlier, it is possible for an authenticated user to send a specially-crafted request that forces Druid to run user-provided JavaScript code for that request, regardless of server configuration. This can be leveraged to execute code on the target machine with the privileges of the Druid server process.| 
| 20210610T05:44:21Z | CVE-2020-3452 | Null | https://github.com/sujaygr8/CVE-2020-3452 | A vulnerability in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct directory traversal attacks and read sensitive files on a targeted system. The vulnerability is due to a lack of proper input validation of URLs in HTTP requests processed by an affected device. An attacker could exploit this vulnerability by sending a crafted HTTP request containing directory traversal character sequences to an affected device. A successful exploit could allow the attacker to view arbitrary files within the web services file system on the targeted device. The web services file system is enabled when the affected device is configured with either WebVPN or AnyConnect features. This vulnerability cannot be used to obtain access to ASA or FTD system files or underlying operating system (OS) files.| 
| 20210610T03:57:06Z | CVE-2021-21985 | Null | https://github.com/testanull/Project_CVE-2021-21985_PoC | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210610T02:46:55Z | CVE-2020-1350 | HoneyPoC: Proof-of-Concept (PoC) script to exploit SIGRed (CVE-2020-1350). Achieves Domain Admin on Domain Controllers running Windows Server 2000 up to Windows Server 2019. | https://github.com/ZephrFish/CVE-2020-1350 | | 
| 20210610T01:39:54Z | CVE-2021-23388 | PoC for exploiting CVE-2021-23388 | https://github.com/JamesCVE/CVE-2021-23388 | The package forms before 1.2.1, from 1.3.0 and before 1.3.2 are vulnerable to Regular Expression Denial of Service (ReDoS) via email validation.| 
| 20210610T01:38:27Z | CVE-2021-24316 | PoC for exploiting CVE-2021-24316 | https://github.com/JamesCVE/CVE-2021-24316 | The search feature of the Mediumish WordPress theme through 1.0.47 does not properly sanitise it%s %s% GET parameter before output it back the page, leading to the Cross-SIte Scripting issue.| 
| 20210610T01:38:22Z | CVE-2020-1920 | PoC for exploiting CVE-2020-1920 | https://github.com/JamesCVE/CVE-2020-1920 | A regular expression denial of service (ReDoS) vulnerability in the validateBaseUrl function can cause the application to use excessive resources, become unresponsive, or crash. This was introduced in react-native version 0.59.0 and fixed in version 0.64.1.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210610T23:16:50Z | Config files for my GitHub profile. | https://github.com/klee111287/klee111287 | 0 | 0| 
| 20210610T22:51:58Z | Null | https://github.com/hellodwelling/clean-kleen-llc.com | 0 | 0| 
| 20210610T20:48:03Z | Null | https://github.com/JaimePSantos/ResearchKlee | 0 | 0| 
| 20210610T08:49:12Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 145 | 14| 
| 20210610T02:00:53Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1715 | 495| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210610T23:54:04Z | Essentials for Exploiters | https://github.com/littlepig453/-ROBLOX-Exploit-Essentials | 0 | 0| 
| 20210610T23:52:57Z | Writeup for exploit.education/nebula | https://github.com/vi11ain/nebula-writeup | 1 | 0| 
| 20210610T23:41:53Z | Root shell exploit for several Xiaomi routers: 4A Gigabit, 4A 100M, 4, 4C, 3Gv2, 4Q, miWifi 3C... | https://github.com/acecilia/OpenWRTInvasion | 444 | 93| 
| 20210610T23:32:24Z | Patch for Waterfall to improve performance during attacks and fix memory issues. | https://github.com/2lstudios-mc/FlameCord | 38 | 23| 
| 20210610T23:26:10Z | PS4 Host Exploits For 5.05 Firmware to 7.55 Firmware | https://github.com/Night-King-Host/Night-King-Host.github.io | 1 | 1| 
| 20210610T23:22:42Z |  :cookie: Modern XSS exploitation script. | https://github.com/ShinoNuma/snitchyScript | 1 | 1| 
| 20210610T22:06:32Z | A collection of scripts I%ve written, including automation, enumeration, exploitation, etc. | https://github.com/jessisec/scripts | 1 | 0| 
| 20210610T21:35:51Z | My writeups/solutions for the Modern Binary Exploitation 2015 course provided by Rensselaer Polytechnic Institute | https://github.com/0xYonas/CSCI-4968-WriteUps | 0 | 0| 
| 20210610T21:35:15Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9546 | 1553| 
| 20210610T20:53:10Z | Educational web application demonstrating techniques of binary exploitation (Front-end) | https://github.com/Pen-Test3rs/binary_exploits_frontend | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210610T23:47:33Z | Null | https://github.com/DaHoodScripts/BacKDoor | 0 | 0| 
| 20210610T21:40:02Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 77 | 12| 
| 20210610T21:14:05Z | This program is an non-object oriented opensource, hidden and undetectable backdoor/reverse shell/RAT for Windows made in Python 3 which contains many features such as multi-client support and cross-platform server. | https://github.com/hades-onion/descry | 0 | 0| 
| 20210610T20:00:25Z | SPY-RSB  / Simple Python Reverse Shell Backdoor  | https://github.com/ygorbittencourt/SPY-RSB | 0 | 0| 
| 20210610T19:42:04Z | unlock the advanced menu of Lenovo Yoga Slim 7 BIOS | https://github.com/esno/yoga-bios-unlock | 30 | 2| 
| 20210610T19:00:59Z | simple backdoor and port scanner | https://github.com/SrHaiki/lowly | 0 | 0| 
| 20210610T18:59:07Z | Python 3 IRC Bot / Botnet | https://github.com/trackmastersteve/HackServ | 21 | 17| 
| 20210610T18:17:02Z | Null | https://github.com/Wiilldd/backdoor | 0 | 0| 
| 20210610T17:26:54Z | A LKM rootkit targeting 4.x and 5.x kernel versions which opens a backdoor that can be used to spawn a reverse shell to a remote host and more. | https://github.com/h3xduck/Umbra | 10 | 1| 
| 20210610T12:19:58Z | Python AV Evasion Tools | https://github.com/G1ft3dC0d3/MsfMania | 144 | 31| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210610T22:49:51Z | This is a method to determine if the running time of an algorithm is feasible using fuzzy logic | https://github.com/DeveloperJose/Python-Fuzzy-Feasibility | 0 | 0| 
| 20210610T22:39:12Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210610T22:37:24Z | Null | https://github.com/XOMAv2/NeuroFuzzySystemsLabs | 0 | 0| 
| 20210610T22:34:13Z | Null | https://github.com/Adeelkaa/fuzzy-waddle | 0 | 0| 
| 20210610T22:23:45Z | Null | https://github.com/opimentel-github/fuzzy-tools | 0 | 0| 
| 20210610T21:27:44Z | Null | https://github.com/and88x/Fuzzy_control_of_the_TMRS_with_Simulink | 0 | 0| 
| 20210610T21:01:54Z | A light, eye-caring theme for VS Code | https://github.com/decameronn/fuzzy-theme | 0 | 0| 
| 20210610T20:59:51Z | Fuzzy charrs are fuzzy. | https://github.com/marenubium87/FuzzyCharr | 0 | 0| 
| 20210610T20:30:21Z | Null | https://github.com/ScientificJesus/fuzzy_system | 0 | 0| 
| 20210610T20:19:52Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 442 | 40| 



# 日更新程序
