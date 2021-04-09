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
| 20210409T12:56:05Z | CVE-2021-24086 | Proof of concept for CVE-2021-24086, a NULL dereference in tcpip.sys triggered remotely. | https://github.com/0vercl0k/CVE-2021-24086 | Windows TCP/IP Denial of Service Vulnerability| 
| 20210409T10:08:27Z | CVE-2021-21402 | CVE-2021-21402-Jellyfin-任意文件读取 | https://github.com/jiaocoll/CVE-2021-21402-Jellyfin | Jellyfin is a Free Software Media System. In Jellyfin before version 10.7.1, with certain endpoints, well crafted requests will allow arbitrary file read from a Jellyfin server%s file system. This issue is more prevalent when Windows is used as the host OS. Servers that are exposed to the public Internet are potentially at risk. This is fixed in version 10.7.1. As a workaround, users may be able to restrict some access by enforcing strict security permissions on their filesystem, however, it is recommended to update as soon as possible.| 
| 20210409T09:37:11Z | CVE-2020-35729 | CVE-2020-35729 | https://github.com/Al1ex/CVE-2020-35729 | KLog Server 2.4.1 allows OS command injection via shell metacharacters in the actions/authenticate.php user parameter.| 
| 20210409T07:41:42Z | CVE-2020-9472 | Null | https://github.com/john-dooe/CVE-2020-9472-poisoned-plugin | Umbraco CMS 8.5.3 allows an authenticated file upload (and consequently Remote Code Execution) via the Install Package functionality.| 
| 20210409T07:38:09Z | CVE-2021-3317 | CVE-2021-3317 | https://github.com/Al1ex/CVE-2021-3317 | KLog Server through 2.4.1 allows authenticated command injection. async.php calls shell_exec() on the original value of the source parameter.| 
| 20210409T06:42:34Z | CVE-2021-21402 | CVE-2021-21402 | https://github.com/xiaoshu-bit/CVE-2021-21402 | Jellyfin is a Free Software Media System. In Jellyfin before version 10.7.1, with certain endpoints, well crafted requests will allow arbitrary file read from a Jellyfin server%s file system. This issue is more prevalent when Windows is used as the host OS. Servers that are exposed to the public Internet are potentially at risk. This is fixed in version 10.7.1. As a workaround, users may be able to restrict some access by enforcing strict security permissions on their filesystem, however, it is recommended to update as soon as possible.| 
| 20210409T00:52:13Z | cve-2021-34567 | Null | https://github.com/hu185396/cve-2021-34567 | 未查询到CVE信息| 
| 20210409T00:41:55Z | CVE-2020-14882 | Null | https://github.com/nice0e3/CVE-2020-14882_Exploit_Gui | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210409T09:21:49Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1662 | 487| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210409T12:59:45Z | Null | https://github.com/hendrash/SolidityExploits | 0 | 0| 
| 20210409T12:51:27Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9236 | 1494| 
| 20210409T12:51:02Z | A python script file to forensically investigate and analyse binary files for buffer overflow exploits. | https://github.com/BroadbentT/BINARY-MASTER | 0 | 0| 
| 20210409T12:50:42Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 12 | 8| 
| 20210409T12:48:55Z | Exploit for RakNet | https://github.com/DevClancy/raknet_fucker | 1 | 0| 
| 20210409T12:44:44Z | The Best multi tool with unique features to exploit discord :p | https://github.com/acedontop/Okuru-Multi-Tool | 1 | 0| 
| 20210409T12:35:13Z | Dette er basic runcode. Brug CEVA eller noget andet til at test lortet. Tak til @servercfg for den orginalle backdoor da vi fik ideen ud fra dem.  | https://github.com/DerpIsInactive/VpsStealerFiveM | 2 | 1| 
| 20210409T12:25:19Z | Deep dive into Function, Predicate, Consumer, and Supplier. Understand how these functional interfaces are exploited by Java Stream and combinator pattern.  | https://github.com/davidmbochi/JavaFunctionalProgramming | 0 | 0| 
| 20210409T12:19:32Z | This tool can help you to see the real IP behind CloudFlare protected websites. | https://github.com/zidansec/CrimeFlare | 29 | 9| 
| 20210409T12:15:58Z | SikAl Exploit | https://github.com/rodirodi12/Script-Hub | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210409T12:35:13Z | Dette er basic runcode. Brug CEVA eller noget andet til at test lortet. Tak til @servercfg for den orginalle backdoor da vi fik ideen ud fra dem.  | https://github.com/DerpIsInactive/VpsStealerFiveM | 2 | 1| 
| 20210409T08:58:15Z | haj | https://github.com/RehderK/Backdoor | 0 | 0| 
| 20210409T07:11:02Z | Un shell remoto (remote shell) es un programa que puede ejecutar comandos de shell como otro usuario desde otra computadora a través de la red, usando el modelo cliente-servidor. Cuando este programa no es legítimo o se utiliza para fines no permitidos o ilícitos, recibe el nombre de puerta trasera (backdoor). | https://github.com/Andres-Hernandez-Mata/Backdoor-Shell | 0 | 0| 
| 20210409T04:55:58Z | Backdoor/Malware test in C. Uses two segments - Backdoor and Server; Backdoor works on windows machines and Server on Linux. No masking yet. | https://github.com/dh00mk3tu/Sling | 6 | 0| 
| 20210409T04:33:06Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 206 | 34| 
| 20210409T01:41:13Z | Reverse TCP trojan backdoor written in python | https://github.com/userlandkernel/Pyrovalerone | 3 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210409T12:05:04Z | Using different tools to fuzz audit deamon | https://github.com/punnal/Audit-Fuzzing | 1 | 1| 
| 20210409T11:52:20Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2311 | 124| 
| 20210409T11:40:52Z | 📨 Responsive email template generator. | https://github.com/luangjokaj/fuzzymail | 114 | 4| 
| 20210409T11:16:19Z | Python scripts to fuzz test a MUD through telnet. | https://github.com/virthe/mudfuzz | 1 | 0| 
| 20210409T11:13:46Z | Fuzzing, analysis response and detect vulnerability web application | https://github.com/hoangthanhnguyen/bigdig | 0 | 0| 
| 20210409T11:11:48Z | Fuzzy Quantification of Common and Rare Species in Ecological Communities | https://github.com/Ligophorus/FuzzyQ | 0 | 0| 
| 20210409T10:50:30Z | Python-based code for estimation of highway bottleneck probability using speed transition matrices.  | https://github.com/tisljaricleo/fuzzy-highway-bottleneck-python | 0 | 0| 
| 20210409T10:39:26Z | Generic plugin based web application security fuzzing for anomalies by Slándáil Research Limited | https://github.com/maK-/scanomaly | 9 | 1| 
| 20210409T10:34:41Z | Null | https://github.com/VigilGLC/fuzzy-match | 0 | 0| 
| 20210409T10:33:21Z | Fuzzy Match a name with a standard list | https://github.com/India-Alliance/Fuzzy-Matcher | 2 | 0| 



# 日更新程序
