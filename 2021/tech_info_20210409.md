# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210409 | Hiding in the Particles: When Return-Oriented Programming Meets Program Obfuscation | https://arxiv.org/abs/2012.06658| 
| 20210409 | CVE-2021-1386：Cisco AMP、Immunet 和 ClamAV 本地提权漏洞。 | https://zeroperil.com/cisco-amp-and-immunet-local-privilege-escalation-vulnerability-cve-2021-1386/| 
| 20210409 | 针对 Symantec Endpoint Protection 的日志、隔离文件和上报引擎的研究。 | https://malwaremaloney.blogspot.com/p/all-things-symantec.html| 
| 20210409 | Check Point Research 报告了伊朗的 APT34（OilRig）针对黎巴嫩攻击的证据，并发现新的后门变种 SideTwist。 | https://research.checkpoint.com/2021/irans-apt34-returns-with-an-updated-arsenal/| 
| 20210409 | 记录一些有关内存注入检测的概念，并使用 TiETwAgent 测试一些检测用例。 | https://blog.redbluepurple.io/windows-security-research/kernel-tracing-injection-detection| 
| 20210409 | CVE-2021-29154：Linux 内核中 BPF JIT 由于 branch displacements 错误计算，存在内核提权漏洞。 | https://seclists.org/oss-sec/2021/q2/12| 
| 20210409 | 揭秘 Windows 减少攻击面（ASR：attack surface reduction）的细节。 | https://github.com/commial/experiments/tree/master/windows-defender/ASR| 
| 20210409 | kubesploit：基于 Golang 开发的 C&C HTTP/2 服务，专注容器环境。 | https://github.com/cyberark/kubesploit| 
| 20210409 | 提取 S3（ACPI 即高级配置与电源接口的模式之一） 启动脚本。 | https://labs.sentinelone.com/adventures-from-uefi-land-the-hunt-for-the-s3-boot-script/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210409 | 开始使用 Go | https://docs.microsoft.com/zh-cn/learn/paths/go-first-steps/| 
| 20210409 | Pwn2Own 2021全程（附结果和录像视频） | https://mp.weixin.qq.com/s/blwGELCaPKC1HTczBcWkfQ| 
| 20210409 | 从CTF比赛真题中学习压缩包伪加密与图片隐写术 | https://www.sec-in.com/article/1002| 
| 20210409 | 游戏业务DDoS攻防对抗案例分享 | https://security.tencent.com/index.php/blog/msg/186| 
| 20210409 | IDA Pro 分析 dyld_shared_cache | https://mp.weixin.qq.com/s/PGC7LKu-oC5ZaRxLFrhTsg| 
| 20210409 | 记一次完整的内网渗透经历 | https://xz.aliyun.com/t/9374| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210409T18:03:03Z | 未知编号 | Null | https://github.com/jessica0f0116/cve_2021_1732 | 未查询到CVE信息| 
| 20210409T16:21:07Z | CVE-2021-21402 | CVE-2021-21402-Jellyfin-任意文件读取 | https://github.com/jiaocoll/CVE-2021-21402-Jellyfin | Jellyfin is a Free Software Media System. In Jellyfin before version 10.7.1, with certain endpoints, well crafted requests will allow arbitrary file read from a Jellyfin server%s file system. This issue is more prevalent when Windows is used as the host OS. Servers that are exposed to the public Internet are potentially at risk. This is fixed in version 10.7.1. As a workaround, users may be able to restrict some access by enforcing strict security permissions on their filesystem, however, it is recommended to update as soon as possible.| 
| 20210409T16:20:21Z | CVE-2021-26295 | CVE-2021-26295-POC 利用DNSlog进行CVE-2021-26295的漏洞验证。  使用 poc：将目标放于target.txt后运行python poc.py即可。（Jdk环境需<12，否则ysoserial无法正常生成有效载荷）  exp：python exp.py https://baidu.com然后进入命令执行界面（无回显） | https://github.com/coolyin001/CVE-2021-26295-- | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 
| 20210409T09:37:11Z | CVE-2020-35729 | CVE-2020-35729 | https://github.com/Al1ex/CVE-2020-35729 | KLog Server 2.4.1 allows OS command injection via shell metacharacters in the actions/authenticate.php user parameter.| 
| 20210409T07:41:42Z | CVE-2020-9472 | Null | https://github.com/john-dooe/CVE-2020-9472-poisoned-plugin | Umbraco CMS 8.5.3 allows an authenticated file upload (and consequently Remote Code Execution) via the Install Package functionality.| 
| 20210409T07:38:09Z | CVE-2021-3317 | CVE-2021-3317 | https://github.com/Al1ex/CVE-2021-3317 | KLog Server through 2.4.1 allows authenticated command injection. async.php calls shell_exec() on the original value of the source parameter.| 
| 20210409T06:42:34Z | CVE-2021-21402 | CVE-2021-21402 | https://github.com/xiaoshu-bit/CVE-2021-21402 | Jellyfin is a Free Software Media System. In Jellyfin before version 10.7.1, with certain endpoints, well crafted requests will allow arbitrary file read from a Jellyfin server%s file system. This issue is more prevalent when Windows is used as the host OS. Servers that are exposed to the public Internet are potentially at risk. This is fixed in version 10.7.1. As a workaround, users may be able to restrict some access by enforcing strict security permissions on their filesystem, however, it is recommended to update as soon as possible.| 
| 20210409T00:52:13Z | cve-2021-34567 | Null | https://github.com/hu185396/cve-2021-34567 | 未查询到CVE信息| 
| 20210409T00:41:55Z | CVE-2020-14882 | Null | https://github.com/nice0e3/CVE-2020-14882_Exploit_Gui | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210409T21:40:26Z | Spring 2021 Geography 817 work folder  | https://github.com/klee12/klee12.github.io | 0 | 0| 
| 20210409T17:15:00Z | Null | https://github.com/yuexu-98/klee | 0 | 0| 
| 20210409T15:39:21Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 118 | 10| 
| 20210409T14:33:23Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1665 | 487| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210409T23:49:34Z | A Monaco fork for Roblox exploiting. All functions from LuaU and custom executor functions are present with documentation. | https://github.com/EthanMcBloxxer/Rosploco | 0 | 0| 
| 20210409T23:22:32Z | Null | https://github.com/WhoTippedMyCows/SoftwareExploitation | 0 | 0| 
| 20210409T22:53:32Z | Roblox Exploit GUI lol | https://github.com/TheMinecrafter05/FaceLesS | 0 | 0| 
| 20210409T22:46:50Z | X Attacker Tool ☣ Website Vulnerability Scanner & Auto Exploiter | https://github.com/Moham3dRiahi/XAttacker | 909 | 409| 
| 20210409T21:48:37Z | Null | https://github.com/PazonDiscord/FlunksExploit | 0 | 0| 
| 20210409T21:41:09Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9238 | 1494| 
| 20210409T21:25:43Z | Project Carthage is a Roblox Exploit that inspired by code lyoko | https://github.com/DeletedUser0x96/Project-Carthage | 0 | 0| 
| 20210409T20:50:35Z | Null | https://github.com/exploiteverythingtamil/exploiteverythingtamil.github.io | 0 | 1| 
| 20210409T20:49:42Z | An exploit to get root in vsftpd 2.3.4 (CVE-2011-2523) written in python | https://github.com/HerculesRD/vsftpd2.3.4PyExploit | 0 | 0| 
| 20210409T20:34:57Z | Windows Exploit Suggester - Next Generation | https://github.com/bitsadmin/wesng | 2271 | 356| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210409T21:23:55Z | Null | https://github.com/Wiilldd/backdoor | 0 | 0| 
| 20210409T16:07:22Z | 🤖An Evil and Smart Bot for Enslaving Windows. | https://github.com/wildonion/katyusha | 1 | 1| 
| 20210409T15:40:39Z | Reverse TCP trojan backdoor written in python | https://github.com/userlandkernel/Pyrovalerone | 3 | 0| 
| 20210409T15:32:14Z | Undetectable & Xor encrypting with custom KEY (FUD Metasploit Rat) bypass Top Antivirus like BitDefender,Malwarebytes,Avast,ESET-NOD32,AVG,... & Automatically Add ICON and MANIFEST to excitable | https://github.com/persianhydra/Xeexe-TopAntivirusEvasion | 424 | 100| 
| 20210409T14:57:48Z | Null | https://github.com/Delle9999/backdoor | 0 | 0| 
| 20210409T12:35:13Z | Dette er basic runcode. Brug CEVA eller noget andet til at test lortet. Tak til @servercfg for den orginalle backdoor da vi fik ideen ud fra dem.  | https://github.com/DerpIsInactive/VpsStealerFiveM | 2 | 1| 
| 20210409T08:58:15Z | haj | https://github.com/RehderK/Backdoor | 0 | 0| 
| 20210409T07:11:02Z | Un shell remoto (remote shell) es un programa que puede ejecutar comandos de shell como otro usuario desde otra computadora a través de la red, usando el modelo cliente-servidor. Cuando este programa no es legítimo o se utiliza para fines no permitidos o ilícitos, recibe el nombre de puerta trasera (backdoor). | https://github.com/Andres-Hernandez-Mata/Backdoor-Shell | 0 | 0| 
| 20210409T04:55:58Z | Backdoor/Malware test in C. Uses two segments - Backdoor and Server; Backdoor works on windows machines and Server on Linux. No masking yet. | https://github.com/dh00mk3tu/Sling | 6 | 0| 
| 20210409T04:33:06Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 206 | 34| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210409T23:37:20Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2312 | 124| 
| 20210409T22:46:01Z | Python scripts to fuzz test a MUD through telnet. | https://github.com/virthe/mudfuzz | 1 | 0| 
| 20210409T22:08:49Z | Group 4C Fuzzy Logic Medieval Chess AI Senior Project | https://github.com/arizonagranger/SeniorProjectFuzzyLogicChess | 1 | 1| 
| 20210409T21:07:00Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 1| 
| 20210409T21:05:20Z | Robust and versatile headless monkey (fuzz) testing for the web with reproducible steps, error alerts, strategy sharing and many other good things. | https://github.com/bell-lab-apps/fuzz-monkey | 0 | 0| 
| 20210409T21:03:48Z | Fast SublimeText-like fuzzy search for JavaScript. | https://github.com/farzher/fuzzysort | 2405 | 125| 
| 20210409T20:38:41Z | Null | https://github.com/gdepuydt/fuzzoz | 0 | 0| 
| 20210409T20:35:14Z | JQF + Zest: Coverage-guided semantic fuzzing for Java. | https://github.com/rohanpadhye/JQF | 343 | 47| 
| 20210409T20:24:59Z | The SMB Fuzzer fuzzes the Server  Message Block Protocol that enables file sharing, printing and IPC between Unix and Windows systems. | https://github.com/mellowCS/SMB_Fuzzer | 0 | 0| 
| 20210409T20:24:26Z | :mag: Fast autocomplete suggestion engine using approximate string matching | https://github.com/jeancroy/FuzzySearch | 150 | 26| 



# 日更新程序
