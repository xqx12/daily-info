# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210526 | ESXi OpenSLP heap-overflow (CVE-2021–21974) 漏洞 PoC 的构造 | https://straightblast.medium.com/my-poc-walkthrough-for-cve-2021-21974-a266bcad14b9| 
| 20210526 | 通过探测 http://burp/ 域名的存在判断访问者是否在挂着 Burp 代理 | https://mp.weixin.qq.com/s/V0WdN9CMrTqo6qInuwyR6g| 
| 20210526 | Finding bugs in TypeScript code (chrono-node) using fuzzing (jsfuzz)（视频） | https://www.youtube.com/watch?v=PUZyYcMMgM4| 
| 20210526 | SharpCollection - 有人将很多 C# 写的攻击工具做了一个集合 | https://github.com/Flangvik/SharpCollection| 
| 20210526 | Reverse Engineering Bare Metal Firmware Images — Part 2 | https://ragnarsecurity.medium.com/reverse-engineering-bare-metal-kernel-images-part-2-6a52a4afa3ef| 
| 20210526 | macOS 昨天修复了一个 TCC Bypass 漏洞，已经有恶意软件滥用该漏洞实现无限制的截屏 | https://www.jamf.com/blog/zero-day-tcc-bypass-discovered-in-xcsset-malware/| 
| 20210526 | 利用 InvisibilityCloak 工具逃逸安全软件基于特征的检测 | https://securityintelligence.com/posts/invisibility-cloak-obfuscate-c-tools-evade-signature-based-detection/| 
| 20210526 | nginx DNS Resolver Off-by-One Heap Write Vulnerability | https://x41-dsec.de/lab/advisories/x41-2021-002-nginx-resolver-copy/| 
| 20210526 | Ubiquiti EdgeRouter 路由器更新逻辑存在中间人劫持漏洞 | https://www.zerodayinitiative.com/blog/2021/5/24/cve-2021-22909-digging-into-a-ubiquiti-firmware-update-bug| 
| 20210526 | Half-Double - Rowhammer 内存反转攻击的新技术，Google 团队经过研究发现了一种影响非相邻 Row 的方式 | https://sec.today/pulses/3d8184f6-25a5-43aa-aa84-e3daef48d804/| 
| 20210526 | Half-Double - Rowhammer 内存反转攻击的新技术，Google 团队经过研究发现了一种影响非相邻 Row 的方式 | https://security.googleblog.com/2021/05/introducing-half-double-new-hammering.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+GoogleOnlineSecurityBlog+%28Google+Online+Security+Blog%29| 
| 20210526 | 安全威胁猎人日志 -检测C2服务器的安全性方法。 | https://www.paloaltonetworks.com/blog/security-operations/from-the-hunter-diaries-detecting-c2-servers/| 
| 20210526 | SSH登陆的正确安全配置方法。 | https://blog.zsec.uk/locking-down-ssh-the-right-way/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210526 | 靶场建设与攻防人才培养实践 | https://mp.weixin.qq.com/s/bWFv7xa1OCYqoKrvzzJkGg| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210526T18:05:01Z | CVE-2021-22893 | Proof-of-Concept (PoC) script to exploit Pulse Secure CVE-2021-22893.  | https://github.com/ZephrFish/CVE-2021-22893 | Pulse Connect Secure 9.0R3/9.1R1 and higher is vulnerable to an authentication bypass vulnerability exposed by the Windows File Share Browser and Pulse Secure Collaboration features of Pulse Connect Secure that can allow an unauthenticated user to perform remote arbitrary code execution on the Pulse Connect Secure gateway. This vulnerability has been exploited in the wild.| 
| 20210526T03:06:30Z | CVE-2021-20914 | POC for CVE2021-2091 VMWare ESXi RCE Exploit | https://github.com/Shadow0ps/CVE-2021-20914 | 未查询到CVE信息| 
| 20210526T03:01:08Z | CVE-2020-27216 | PoC for exploiting CVE-2020-27216 | https://github.com/JamesGeee/CVE-2020-27216 | In Eclipse Jetty versions 1.0 thru 9.4.32.v20200930, 10.0.0.alpha1 thru 10.0.0.beta2, and 11.0.0.alpha1 thru 11.0.0.beta2O, on Unix like systems, the system%s temporary directory is shared between all users on that system. A collocated user can observe the process of creating a temporary sub directory in the shared temporary directory and race to complete the creation of the temporary subdirectory. If the attacker wins the race then they will have read and write permission to the subdirectory used to unpack web applications, including their WEB-INF/lib jar files and JSP files. If any code is ever executed out of this temporary directory, this can lead to a local privilege escalation vulnerability.| 
| 20210526T03:00:28Z | CVE-2021-28112 | PoC for exploiting CVE-2021-28112 | https://github.com/JamesGeee/CVE-2021-28112 | Draeger X-Dock Firmware before 03.00.13 has Active Debug Code on a debug port, leading to remote code execution by an authenticated attacker.| 
| 20210526T03:00:24Z | CVE-2021-28111 | PoC for exploiting CVE-2021-28111 | https://github.com/JamesGeee/CVE-2021-28111 | Draeger X-Dock Firmware before 03.00.13 has Hard-Coded Credentials, leading to remote code execution by an authenticated attacker.| 
| 20210526T03:00:21Z | CVE-2021-33574 | PoC for exploiting CVE-2021-33574 | https://github.com/JamesGeee/CVE-2021-33574 | | 
| 20210526T03:00:18Z | CVE-2021-33570 | PoC for exploiting CVE-2021-33570 | https://github.com/JamesGeee/CVE-2021-33570 | Postbird 0.8.4 allows stored XSS via the onerror attribute of an IMG element in any PostgreSQL database table. This can result in reading local files via vectors involving XMLHttpRequest and open of a file:/// URL, or discovering PostgreSQL passwords via vectors involving Window.localStorage and savedConnections.| 
| 20210526T03:00:15Z | CVE-2021-22667 | PoC for exploiting CVE-2021-22667 | https://github.com/JamesGeee/CVE-2021-22667 | BB-ESWGP506-2SFP-T versions 1.01.09 and prior is vulnerable due to the use of hard-coded credentials, which may allow an attacker to gain unauthorized access and permit the execution of arbitrary code on the BB-ESWGP506-2SFP-T (versions 1.01.01 and prior).| 
| 20210526T03:00:11Z | CVE-2021-33575 | PoC for exploiting CVE-2021-33575 | https://github.com/JamesGeee/CVE-2021-33575 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210526T15:44:31Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 632 | 14| 
| 20210526T12:50:27Z | Null | https://github.com/KleePaimon/KleePaimon.github.io | 0 | 0| 
| 20210526T07:51:58Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1700 | 494| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210526T08:22:25Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 127 | 31| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210526T23:55:03Z | Developing and backtesting performance of a market neutral trading strategy which aims to exploit temporary anomalies in correlation between 2 pair of assets. | https://github.com/Naharul98/Pairs-Trading-Highly-Correlated-Assets | 0 | 0| 
| 20210526T23:22:06Z | Null | https://github.com/SxnwDev/Exploit | 0 | 0| 
| 20210526T23:15:44Z | Null | https://github.com/Mehvix/cryptotrunks-exploit | 0 | 0| 
| 20210526T23:08:53Z | A tool to identify and exploit sudo rules% misconfigurations and vulnerabilities within sudo for linux privilege escalation. | https://github.com/TH3xACE/SUDO_KILLER | 1145 | 161| 
| 20210526T23:06:46Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9490 | 1536| 
| 20210526T22:55:01Z | This is where I will put my open source admin commands project. Feel free to suggest ideas or report bugs/exploits. | https://github.com/captainbboy/Roblox-Admin-Commands-Open-Source | 0 | 0| 
| 20210526T22:14:35Z | Tools and Exploits | https://github.com/abundov/exploits | 0 | 0| 
| 20210526T22:10:34Z | Project Carthage is a Roblox Exploit that inspired by code lyoko | https://github.com/DeletedUser0x96/Project-Carthage | 0 | 0| 
| 20210526T21:18:42Z | x64 Windows privilege elevation using anycall | https://github.com/kkent030315/anyelevate | 0 | 0| 
| 20210526T20:51:41Z | Null | https://github.com/thecasual/exploits | 1 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210526T23:56:08Z | Python Backdoor for the INE course | https://github.com/Ioan93Andrei/Python-Backdoor | 0 | 0| 
| 20210526T23:34:46Z | The Project is mainly based on Sockets , File Handling and subprocess library for Creating backdoors For Hacking into one%s Computer (Any OS-Platform Service)   and listening on your computer and waiting for Connections and Running system Commands from Your Computer to the target Computer for which Output will be Displayed On your Computer.  | https://github.com/shivdon/Socket-Backdoor-and-Listener | 1 | 1| 
| 20210526T22:39:28Z | PCI Express DIY hacking toolkit for Xilinx SP605 | https://github.com/Cr4sh/s6_pcie_microblaze | 358 | 88| 
| 20210526T22:15:34Z | Backend for our cyber security forum - %Backdoor% | https://github.com/backdoor-epics/backdoor-backend | 0 | 1| 
| 20210526T17:32:00Z | Simple POST Request Shell Command Execution | https://github.com/dmzhari/hidden-shell | 0 | 0| 
| 20210526T17:20:57Z | Null | https://github.com/ritesh-joshi1337/backdoor | 0 | 0| 
| 20210526T16:52:13Z | A batch script for taking information. A bit overdeveloped, and kind of useless. | https://github.com/Takaovi/BatchStealer | 6 | 1| 
| 20210526T15:16:16Z | with this tool you can create a python backdoor undetectable by AV | https://github.com/rek292/fudpy | 0 | 0| 
| 20210526T12:11:36Z | Null | https://github.com/Qeisi/7-ZipBackdoor | 0 | 0| 
| 20210526T11:51:00Z | Scky python botnet-based backdoor | https://github.com/ctg-group/scky | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210526T12:51:56Z | Null | https://github.com/Sambigeara/fuzzynote | 3 | 1| 
| 20210526T12:49:37Z | Null | https://github.com/nisamaulia/fuzzylogic-restaurant_quality | 0 | 0| 
| 20210526T12:40:01Z | Null | https://github.com/Tuahdnnadld/fuzzy-guacamole | 0 | 0| 
| 20210526T12:24:30Z | oss-fuzz-base-images-hub | https://github.com/xxrz/oss-fuzz-base-images-hub | 0 | 0| 
| 20210526T12:22:54Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6332 | 1283| 
| 20210526T12:15:15Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 7 | 5| 
| 20210526T12:01:43Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 431 | 36| 
| 20210526T11:57:25Z | Null | https://github.com/me-mazandarani/Fuzzy-Logic | 0 | 0| 
| 20210526T11:50:10Z | Null | https://github.com/me-mazandarani/Fuzzy-Logic-System | 0 | 0| 
| 20210526T11:38:09Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3524 | 817| 



# 日更新程序
