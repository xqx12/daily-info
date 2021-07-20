# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210719 | MVT - 通过取证信息分析 iOS/Android 手机是否已被入侵的工具 | https://github.com/mvt-project/mvt| 
| 20210719 | A Journey to understand LLVM-IR | https://un-devs.github.io/low-level-exploration/journey-to-understanding-llvm-ir/| 
| 20210719 | PetitPotam - 强制 Windows 通过 MS-EFSRPC EfsRpcOpenFileRaw 函数认证其他机器的工具 | https://github.com/topotam/PetitPotam| 
| 20210719 | Swimming In The (Kernel) Pool，内核内存 Pool 漏洞实现任意地址读写的利用方法 | https://connormcgarr.github.io/swimming-in-the-kernel-pool-part-2/| 
| 20210719 | Rewind - Snapshot-based coverage-guided windows kernel fuzzer | https://github.com/quarkslab/rewind| 
| 20210719 | macOS TCC 隐私保护机制不限制对 Home 目录进行访问，SSH 密钥等其他一些敏感信息可被直接访问 | https://cedowens.medium.com/initial-access-checks-on-macos-531dd2d0cee6| 
| 20210719 | Forensic Methodology Report: How to catch NSO Group’s Pegasus | https://www.amnesty.org/en/latest/research/2021/07/forensic-methodology-report-how-to-catch-nso-groups-pegasus/| 
| 20210719 | ZecOps 团队经过分析发现，前段时间 iOS WiFi SSID 格式化字符串拒绝服务漏洞可以实现 RCE | https://blog.zecops.com/research/meet-wifidemon-ios-wifi-rce-0-day-vulnerability-and-a-zero-click-vulnerability-that-was-silently-patched/| 
| 20210719 | Google 对 3 个野外浏览器 0Day 漏洞被利用过程的简单介绍 | https://blog.google/threat-analysis-group/how-we-protect-users-0-day-attacks/| 
| 20210719 | Google CTF 比赛一道没被解出的上传文件泄露 flag 题 | https://gist.github.com/terjanq/458d8ec1148e96f7ccbdccfd908c56f6| 
| 20210719 | Windows: WFP Default Rules AppContainer Capability Bypass EoP，该问题微软表示不会修复 | https://bugs.chromium.org/p/project-zero/issues/detail?id=2207| 
| 20210719 | Google CTF 2021 Linux 内核 eBPF 挑战题的 Writeup | https://mem2019.github.io/jekyll/update/2021/07/19/GCTF2021-eBPF.html| 
| 20210719 | 戴尔的系统管理和监控应用 OpenManage Enterprise 被发现 20 多个高危漏洞 | https://pierrekim.github.io/blog/2021-07-19-dell-openmanage-enterprise-0day-vulnerabilities.html| 
| 20210719 | iOS 越狱环境检测、Frida 环境检测 | https://www.romainthomas.fr/post/21-07-pokemongo-anti-frida-jailbreak-bypass/| 
| 20210719 | Windows Pool OverFlow 漏洞的利用方法 | http://vul.360.net/archives/83| 
| 20210719 | capa 更新 2.0 版本，capa 是 FireEye 开源的自动化分析恶意软件行为 Capabilities 的工具 | https://www.fireeye.com/blog/threat-research/2021/07/capa-2-better-stronger-faster.html| 
| 20210719 | FiberHome HG6245D 路由器多个高危漏洞的分析 | https://pierrekim.github.io/blog/2021-01-12-fiberhome-ont-0day-vulnerabilities.html| 
| 20210719 | 针对Turla APT团队恶意软件“SilentMoon“”分析溯源。 | https://0xthreatintel.medium.com/analyzing-silentmoon-turla-trojan-fc34b49fe726| 
| 20210719 | 在虚拟机的VMI 模式下与调试器模式下的远程调试。 | https://sec.today/pulses/74cc64b1-6a30-4729-8860-32567670ac88/| 
| 20210719 | I/O Extended 2021 系列: Chrome DevTools & Web Vitals. | https://sec.today/pulses/35605fdd-35b1-4a8a-953e-0954af02e620/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210719 | SecWiki周刊（第385期) | https://www.sec-wiki.com/weekly/385| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210719T20:24:53Z | CVE-2021-21551 | An extended proof-of-concept for the CVE-2021-21551 Dell ‘dbutil_2_3.sys’ Kernel Exploit. | https://github.com/mzakocs/CVE-2021-21551-POC | Dell dbutil_2_3.sys driver contains an insufficient access control vulnerability which may lead to escalation of privileges, denial of service, or information disclosure. Local authenticated user access is required.| 
| 20210719T20:05:52Z | cve-2021-22555 | Null | https://github.com/cgwalters/container-cve-2021-22555 | A heap out-of-bounds write affecting Linux since v2.6.19-rc1 was discovered in net/netfilter/x_tables.c. This allows an attacker to gain privileges or cause a DoS (via heap memory corruption) through user name space| 
| 20210719T15:48:51Z | CVE-2021-34527 | PrintNightmare - Windows Print Spooler RCE/LPE Vulnerability (CVE-2021-34527, CVE-2021-1675) proof of concept exploits | https://github.com/nemo-wq/PrintNightmare-CVE-2021-34527 | Windows Print Spooler Remote Code Execution Vulnerability| 
| 20210719T14:20:41Z | CVE-2021-33560 | Tool to check whether a PGP client is affected by CVE-2021-33560 | https://github.com/IBM/PGP-client-checker-CVE-2021-33560 | Libgcrypt before 1.8.8 and 1.9.x before 1.9.3 mishandles ElGamal encryption because it lacks exponent blinding to address a side-channel attack against mpi_powm, and the window size is not chosen appropriately. (There is also an interoperability problem because the selection of the k integer value does not properly consider the differences between basic ElGamal encryption and generalized ElGamal encryption.) This, for example, affects use of ElGamal in OpenPGP.| 
| 20210719T12:23:22Z | CVE-2021-22555 | CVE-2021-22555 Exploit | https://github.com/JustYoomoon/CVE-2021-22555-Exploit | A heap out-of-bounds write affecting Linux since v2.6.19-rc1 was discovered in net/netfilter/x_tables.c. This allows an attacker to gain privileges or cause a DoS (via heap memory corruption) through user name space| 
| 20210719T07:01:22Z | CVE-2020-9483 | PoC of SQL Injection vul(CVE-2020-9483,Apache SkyWalking) | https://github.com/Neko2sh1ro/CVE-2020-9483 | **Resolved** When use H2/MySQL/TiDB as Apache SkyWalking storage, the metadata query through GraphQL protocol, there is a SQL injection vulnerability, which allows to access unpexcted data. Apache SkyWalking 6.0.0 to 6.6.0, 7.0.0 H2/MySQL/TiDB storage implementations don%t use the appropriate way to set SQL parameters.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210719T13:56:53Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 163 | 15| 
| 20210719T08:08:56Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1732 | 498| 
| 20210719T03:57:56Z | Null | https://github.com/johanfajar/klee-puzzle | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210719T14:19:27Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 142 | 33| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210719T23:46:32Z | Null | https://github.com/TheCrazzXz/Exploits-Lab | 0 | 0| 
| 20210719T23:35:58Z | Patch for Waterfall to improve performance during attacks and fix memory issues. | https://github.com/2lstudios-mc/FlameCord | 52 | 31| 
| 20210719T23:22:05Z | Agent-Based Modelling of labour exploitation in textile supply chains | https://github.com/kwabenantim/textile-labour | 1 | 0| 
| 20210719T22:18:23Z | exploiter le potentiel des logiciels de reconnaissance d’objets pour identifier et compter tous les types de véhicules dans des flux vidéos des caméras de videosurveillance | https://github.com/fabmob/open_trafic | 1 | 0| 
| 20210719T22:11:06Z | Null | https://github.com/zYan666/Demon-Exploit | 0 | 0| 
| 20210719T21:51:57Z | Old and new CTFs about Linux kernel exploitation. | https://github.com/MaherAzzouzi/LinuxKernelExploitation | 9 | 2| 
| 20210719T21:08:32Z | The purpose of this script is to automate the web enumeration process and search for exploits | https://github.com/V1n1v131r4/webdiscover | 0 | 0| 
| 20210719T20:24:53Z | An extended proof-of-concept for the CVE-2021-21551 Dell ‘dbutil_2_3.sys’ Kernel Exploit. | https://github.com/mzakocs/CVE-2021-21551-POC | 0 | 0| 
| 20210719T20:23:09Z | All about pwning, reversing, and the road to exploit development | https://github.com/NimishMishra/exploit-dev | 0 | 0| 
| 20210719T19:42:53Z | Educational web application demonstrating techniques of binary exploitation (Front-end) | https://github.com/Pen-Test3rs/binary_exploits_frontend | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210719T22:24:04Z | killer v 1 multi shell backdoors builder  | https://github.com/ABDO10DZ/shell-killer | 2 | 3| 
| 20210719T17:55:45Z | Yet Another PHP Shell | https://github.com/Nickguitar/YAPS | 16 | 2| 
| 20210719T17:28:25Z | Paranoid is a web interface and dashboard, configured for managing HatSploit sessions via built-in REST API. | https://github.com/EntySec/Paranoid | 2 | 0| 
| 20210719T17:13:23Z | Poweshell backdoor metasploit  | https://github.com/crypt0n-root/powershell-backdoor | 1 | 0| 
| 20210719T16:49:23Z | Python remote server(backdoor) | https://github.com/KalenMajic/python-remote-server | 0 | 0| 
| 20210719T14:47:18Z | test backdoor | https://github.com/navithejatboy/juspaybd | 0 | 0| 
| 20210719T13:01:06Z | shell backdoor | https://github.com/m0nd4y99/shellbackdoorr | 0 | 0| 
| 20210719T12:36:30Z | 🤖An Evil and Smart Bot for Enslaving Windows Written in Rust and Python | https://github.com/wildonion/katyusha | 3 | 1| 
| 20210719T11:53:35Z | Small collection of bash scripts that take advantage of the .bashrc file and inject various payloads into it in order to escalate privileges or steal credentials. | https://github.com/Naqwa/Bashrc-Backdoors | 1 | 0| 
| 20210719T10:13:06Z | Backdoor in Python | https://github.com/M4UR9/Backdoor | 1 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210719T19:13:29Z | A symbolic execution engine for LLVM IR | https://github.com/insufficiently-caffeinated/caffeine | 7 | 4| 
| 20210719T17:29:44Z | FuSeBMC is a White-Box Fuzzer that combines FUzzing with Symbolic Execution via Bounded Model Checking to verify intricate properties in real-world C programs. | https://github.com/kaled-alshmrany/FuSeBMC | 19 | 1| 
| 20210719T16:27:16Z | Symbolic-execution-based verifier for the Viper intermediate verification language. | https://github.com/viperproject/silicon | 19 | 11| 
| 20210719T13:54:06Z | SymQEMU: Compilation-based symbolic execution for binaries | https://github.com/eurecom-s3/symqemu | 156 | 20| 
| 20210719T12:01:23Z | Monster is a symbolic execution engine for 64-bit RISC-U code | https://github.com/cksystemsgroup/monster | 6 | 3| 
| 20210719T08:08:56Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1732 | 498| 
| 20210719T07:44:58Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1845 | 386| 
| 20210719T04:11:52Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2390 | 352| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210719T23:32:18Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210719T23:21:58Z | Null | https://github.com/stuartelimu/fuzzy-octo-carnival | 0 | 0| 
| 20210719T22:55:29Z | Null | https://github.com/lzhfromustc/goFuzz | 0 | 0| 
| 20210719T22:48:07Z | Null | https://github.com/Bagdjdd/fuzzy-journey | 0 | 0| 
| 20210719T22:31:51Z | Fuzzinator Random Testing Framework | https://github.com/renatahodovan/fuzzinator | 177 | 38| 
| 20210719T22:18:57Z | Config files for my GitHub profile. | https://github.com/fuzzysaucer/fuzzysaucer | 0 | 0| 
| 20210719T22:02:22Z | a fuzzier graph plotting method | https://github.com/autumnull/fuzzyplot | 0 | 0| 
| 20210719T21:26:51Z | Null | https://github.com/13jojo/fuzzy_search | 0 | 0| 
| 20210719T21:21:51Z | A GUI fuzzing tool that works by recording the user and making scenarios out of it | https://github.com/MrVoustache/GUI-Mimic | 0 | 0| 
| 20210719T21:16:36Z | Fuzzy based segmentation of remotely sensed images using an Adaptive Neuro Fuzzy Inference System (ANFIS). | https://github.com/andmon97/FuzzyRemoteSensingSegmentation | 8 | 0| 



# 日更新程序
