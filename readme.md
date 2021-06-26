# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210625 | iOS Malicious Bit Hunter - iOS App 恶意插件检测引擎 | http://github.com/alipay/ios-malicious-bithunter| 
| 20210625 | Java 静态分析框架 Soot 使用教程 | https://github.com/noidsirius/SootTutorial| 
| 20210625 | 今年 8 月份将要举办的 DEF CON 29 会议的大部分议题信息公开了，玄武实验室 3 个议题成功入选！ | https://defcon.org/html/defcon-29/dc-29-speakers.html| 
| 20210625 | DELL 设备 BIOS 连接 DELL 服务器检查更新时存在中间人劫持漏洞，129 款 DELL 设备受影响 | https://therecord.media/129-dell-models-including-secured-core-pcs-vulnerable-to-new-firmware-flaws/| 
| 20210625 | ClusterFuzz - Google 开源的可扩展 Fuzz 基础设施 | https://github.com/google/clusterfuzz| 
| 20210625 | 渗透测试时可以利用 Desired State Configurations 实现任意命令执行与常驻 | https://www.netspi.com/blog/technical/cloud-penetration-testing/azure-persistence-with-desired-state-configurations/| 
| 20210625 | Realtek RTKVHD64.sys 驱动越界访问漏洞分析（CVE-2021-32537） | https://github.com/0vercl0k/CVE-2021-32537| 
| 20210625 | 索尼 PlayStation 架构分析 | https://www.copetti.org/writings/consoles/playstation/| 
| 20210625 | Google 计划推动 OSV（开源漏洞数据库）采用统一规范的数据格式 | https://security.googleblog.com/2021/06/announcing-unified-vulnerability-schema.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+GoogleOnlineSecurityBlog+%28Google+Online+Security+Blog%29| 
| 20210625 | Checkpoint 对协作办公领域 Atlassian 公司多个产品漏洞的分析 | https://sec.today/pulses/968c38e2-9b47-4435-9d1f-91fb7322190c/| 
| 20210625 | Checkpoint 对协作办公领域 Atlassian 公司多个产品漏洞的分析 | https://research.checkpoint.com/2021/a-supply-chain-breach-taking-over-an-atlassian-account/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210625 | Java 命令执行之我见 | https://www.anquanke.com/post/id/243329| 
| 20210625 | 自研HIDS「洋葱」后台上云架构演进实践 | https://security.tencent.com/index.php/blog/msg/194| 
| 20210625 | PbootCms-3.04前台RCE挖掘过程 | https://www.anquanke.com/post/id/244821| 
| 20210625 | 供应链安全的学习笔记 | https://www.sec-un.org/%e4%be%9b%e5%ba%94%e9%93%be%e5%ae%89%e5%85%a8%e7%9a%84%e5%ad%a6%e4%b9%a0%e7%ac%94%e8%ae%b0/| 
| 20210625 | 针对语言翻译系统的数据投毒攻击 | https://www.anquanke.com/post/id/244126| 
| 20210625 | 傻瓜式 fuzzing 系列一 | https://paper.seebug.org/1615/| 
| 20210625 | MybatisPuls分页插件中的SQL注入 | https://www.sec-in.com/article/1088| 
| 20210625 | Java 供应链(依赖)安全检测实践 | https://mp.weixin.qq.com/s/1fnDelBE1HisEaopEyk8nQ| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210625T22:20:31Z | CVE-2021-33624 | Proof of Concept for CVE-2021-33624 | https://github.com/Kakashiiiiy/CVE-2021-33624 | In kernel/bpf/verifier.c in the Linux kernel before 5.12.13, a branch can be mispredicted (e.g., because of type confusion) and consequently an unprivileged BPF program can read arbitrary memory locations via a side-channel attack, aka CID-9183671af6db.| 
| 20210625T17:30:15Z | CVE-2021-32537 | PoC for CVE-2021-32537: an out-of-bounds memory access that leads to pool corruption in the Windows kernel. | https://github.com/0vercl0k/CVE-2021-32537 | 未查询到CVE信息| 
| 20210625T17:04:01Z | 未知编号 | Null | https://github.com/KZMachine/CVERT-2021 | 未查询到CVE信息| 
| 20210625T15:22:41Z | CVE-2021-27850 | A Proof of concept for CVE-2021-27850 affecting Apache Tapestry and leading to unauthencticated remote code execution. | https://github.com/kahla-sec/CVE-2021-27850_POC | A critical unauthenticated remote code execution vulnerability was found all recent versions of Apache Tapestry. The affected versions include 5.4.5, 5.5.0, 5.6.2 and 5.7.0. The vulnerability I have found is a bypass of the fix for CVE-2019-0195. Recap: Before the fix of CVE-2019-0195 it was possible to download arbitrary class files from the classpath by providing a crafted asset file URL. An attacker was able to download the file `AppModule.class` by requesting the URL `http://localhost:8080/assets/something/services/AppModule.class` which contains a HMAC secret key. The fix for that bug was a blacklist filter that checks if the URL ends with `.class`, `.properties` or `.xml`. Bypass: Unfortunately, the blacklist solution can simply be bypassed by appending a `/` at the end of the URL: `http://localhost:8080/assets/something/services/AppModule.class/` The slash is stripped after the blacklist check and the file `AppModule.class` is loaded into the response. This class usually contains the HMAC secret key which is used to sign serialized Java objects. With the knowledge of that key an attacker can sign a Java gadget chain that leads to RCE (e.g. CommonsBeanUtils1 from ysoserial). Solution for this vulnerability: * For Apache Tapestry 5.4.0 to 5.6.1, upgrade to 5.6.2 or later. * For Apache Tapestry 5.7.0, upgrade to 5.7.1 or later.| 
| 20210625T10:42:06Z | CVE-2020-3580 | Null | https://github.com/Hudi233/CVE-2020-3580 | Multiple vulnerabilities in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct cross-site scripting (XSS) attacks against a user of the web services interface of an affected device. The vulnerabilities are due to insufficient validation of user-supplied input by the web services interface of an affected device. An attacker could exploit these vulnerabilities by persuading a user of the interface to click a crafted link. A successful exploit could allow the attacker to execute arbitrary script code in the context of the interface or allow the attacker to access sensitive, browser-based information. Note: These vulnerabilities affect only specific AnyConnect and WebVPN configurations. For more information, see the Vulnerable Products section.| 
| 20210625T08:59:55Z | CVE-2021-35448 | Remote Mouse GUI 3.008 - Local Privilege Escalation | https://github.com/deathflash1411/CVE-2021-35448 | Emote Interactive Remote Mouse 3.008 on Windows allows attackers to execute arbitrary programs as Administrator by using the Image Transfer Folder feature to navigate to cmd.exe. It binds to local ports to listen for incoming connections.| 
| 20210625T06:11:02Z | CVE-2021-3156 | Null | https://github.com/donghyunlee00/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210625T06:09:17Z | CVE-2020-0041 | My implementation of CVE-2020-0041 | https://github.com/Byte-Master-101/CVE-2020-0041 | In binder_transaction of binder.c, there is a possible out of bounds write due to an incorrect bounds check. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android kernelAndroid ID: A-145988638References: Upstream kernel| 
| 20210625T05:38:20Z | CVE-2021-35475 | Writeup for CVE-2021-35475; Stored Cross-Site Scripting(XSS) on SAS® Environment Manager 2.5 | https://github.com/saitamang/CVE-2021-35475 | SAS Environment Manager 2.5 allows XSS through the Name field when creating/editing a server. The XSS will prompt when editing the Configuration Properties.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210625T07:16:21Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1722 | 495| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210625T23:59:26Z | Thi powershell script has got to run in remote windows host, even for pivoting | https://github.com/FabioDefilippo/winallenum | 3 | 1| 
| 20210625T23:55:35Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 15 | 4| 
| 20210625T23:28:41Z | Null | https://github.com/sheenieboy/ExploiterChat | 1 | 0| 
| 20210625T23:15:49Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9596 | 1569| 
| 20210625T22:16:58Z | Modular penetration testing platform that enables you to write, test, and execute exploit code. | https://github.com/EntySec/HatSploit | 64 | 22| 
| 20210625T21:38:33Z | Agent-Based Modelling of labour exploitation in textile supply chains | https://github.com/kwabenantim/textile-labour | 0 | 0| 
| 20210625T21:20:06Z | Resources for the Kr00k vulnerability (CVE-2019-15126) | https://github.com/raul23/Kr00k | 0 | 0| 
| 20210625T21:19:11Z | My personal writeup for Nebula from Andrew Griffits Exploit Education | https://github.com/Hacker5preme/Nebula-Writeup | 0 | 0| 
| 20210625T21:04:26Z | This is an open-source software for exploiting specifically Roblox games. This is designed for people who are looking for exploit softwares designed for MacOS. | https://github.com/bluehydrarblx-dev/rTyphoeusSploit | 0 | 0| 
| 20210625T20:30:02Z | DarkWare is a roblox exploit hub. | https://github.com/Yarik312/DarkWare | 1 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210625T19:05:51Z | vsftpd 2.3.4 Backdoor Exploit | https://github.com/nobodyatall648/CVE-2011-2523 | 0 | 0| 
| 20210625T18:16:40Z | Invisible, customizable backdoor for Minecraft Spigot Plugins. | https://github.com/ThiccIndustries/Minecraft-Backdoor | 9 | 4| 
| 20210625T17:32:17Z | TotallyNotABackDoorPlugin is a backdoor plugin for minecraft servers | https://github.com/SpicyHamBoi/TotallyNotABackDoorPlugin | 1 | 0| 
| 20210625T17:12:31Z | Null | https://github.com/alex54142/PHP-SHELL-backdoor | 0 | 0| 
| 20210625T17:10:15Z | A module for building botnet or back door with Python and Telegram control panel | https://github.com/onionj/pybotnet | 2 | 0| 
| 20210625T16:57:06Z | Backdoor Android programado en Phyton | https://github.com/Fr0il4nSierra/Backdoor_Phyton | 0 | 0| 
| 20210625T16:40:16Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/Ghost | 1170 | 556| 
| 20210625T13:05:53Z | Reverse-Shell | https://github.com/knight8645726/Backdoor | 0 | 0| 
| 20210625T11:24:37Z | Implementation of a native-code HatSploit membrane for unix-like systems, designed for portability, embeddability, and low resource utilization. | https://github.com/EntySec/membrane | 3 | 1| 
| 20210625T09:56:40Z | Null | https://github.com/snowfarin/backdoor-both-victim-and-attacker | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210625T15:07:37Z | This is the repository for Symbolic Execution engine for StateFlow (SESf) models | https://github.com/predragf/sesf | 0 | 0| 
| 20210625T13:03:41Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 14 | 3| 
| 20210625T09:33:24Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1829 | 381| 
| 20210625T07:16:21Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1722 | 495| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210625T08:49:43Z | Null | https://github.com/AnonymousCodeBaseA/NDSS22_Graph_Matching | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210625T23:44:50Z | Fuzzer for LP models in MPS | https://github.com/elefthei/lp-fuzzer | 0 | 0| 
| 20210625T23:38:44Z | A fuzzer without the fuzz (or the wait). | https://github.com/cyberrumor/sitemap | 0 | 0| 
| 20210625T22:14:21Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3571 | 830| 
| 20210625T21:37:34Z | Coursework and projects completed as part of Neural and Fuzzy Control Systems, 9th Semester, School of Electrical and Computer Engineering, NTUA. | https://github.com/YiorgosVasileiou/ECE_Fuzzy_Neural_Control | 0 | 0| 
| 20210625T20:49:11Z | Poke-a-square | https://github.com/nataliesmyth/fuzzy-octo-memory | 0 | 0| 
| 20210625T20:02:40Z | egg | https://github.com/Human727/fuzzy-enigma | 0 | 0| 
| 20210625T18:57:41Z | Null | https://github.com/DanielEbert/EmulatedFirmwareFuzzing | 0 | 0| 
| 20210625T18:47:11Z | Null | https://github.com/ukyouz/SublimeText-SimpleFuzzy | 0 | 0| 
| 20210625T18:46:47Z | FuzzBench - Fuzzer benchmarking as a service. | https://github.com/google/fuzzbench | 651 | 121| 
| 20210625T18:41:07Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 288 | 39| 



# 日更新程序
