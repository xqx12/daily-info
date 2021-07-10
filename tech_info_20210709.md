# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210709 | 基于 Ghidra 实现的 Code Property Graph (CPG) Frontend | https://github.com/joernio/ghidra2cpg| 
| 20210709 | InlineExecute-Assembly - 以 Beacon Object File (BOF) 方式实现进程内 .NET Assembly Execution 的 PoC 代码 | https://github.com/xforcered/InlineExecute-Assembly| 
| 20210709 | HyperDbg - Windows 平台的一款开源调试器，充分利用 Hypervisor 特性，支持用户态和内核态调试，主要为逆向分析、调试、Fuzz 设计使用 | https://github.com/HyperDbg/HyperDbg| 
| 20210709 | XNU IPC Mach messages 的数据结构介绍 | https://dmcyk.xyz/post/xnu_ipc_i_mach_messages/| 
| 20210709 | Process Creation is Dead, Long Live Process Creation — Adding BOFs Support to PEzor | https://iwantmore.pizza/posts/PEzor4.html| 
| 20210709 | API 安全设计之认证（Authentication）过程常犯的 5 个错误 | https://securityboulevard.com/2021/07/api-security-need-to-know-top-5-authentication-pitfalls/?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+SecurityBloggersNetwork+%28Security+Bloggers+Network%29| 
| 20210709 | 针对能源及其供应链行业的钓鱼攻击行动 | https://www.intezer.com/blog/research/global-phishing-campaign-targets-energy-sector-and-its-suppliers/| 
| 20210709 | Microsoft SharePoint Server 远程任意 .NET 代码执行漏洞分析（CVE-2021-28474） | https://www.thezdi.com/blog/2021/7/7/cve-2021-28474-sharepoint-remote-code-execution-via-server-side-control-interpretation-conflict| 
| 20210709 | TenSEAL - 这篇 Paper 开源了一套针对机器学习的工具库，用于解决机器学习过程中为隐私和敏感数据脱敏而又不影响训练的问题 | https://arxiv.org/abs/2104.03152| 
| 20210709 | SEVerity - 这篇 Paper 研究 AMD 的安全加密虚拟化（SEV）技术并提出了一种代码注入攻击 | https://sec.today/pulses/56634493-7e3a-4756-b0b8-d5bbe0c867e5/| 
| 20210709 | SEVerity - 这篇 Paper 研究 AMD 的安全加密虚拟化（SEV）技术并提出了一种代码注入攻击 | https://arxiv.org/abs/2105.13824| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210709 | CVE-2021-1675远程RCE复现 | https://www.sec-in.com/article/1110| 
| 20210709 | 零信任实践分享 | http://ckev.in/j/ztcn/| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210709T19:38:43Z | CVE-2021-21974 | POC for CVE-2021-21974 VMWare ESXi RCE Exploit | https://github.com/Shadow0ps/CVE-2021-21974 | OpenSLP as used in ESXi (7.0 before ESXi70U1c-17325551, 6.7 before ESXi670-202102401-SG, 6.5 before ESXi650-202102101-SG) has a heap-overflow vulnerability. A malicious actor residing within the same network segment as ESXi who has access to port 427 may be able to trigger the heap-overflow issue in OpenSLP service resulting in remote code execution.| 
| 20210709T14:17:43Z | CVE-2021-1675 | Null | https://github.com/corelight/CVE-2021-1675 | Windows Print Spooler Elevation of Privilege Vulnerability| 
| 20210709T10:21:14Z | CVE-2021-525 | D-Link credentials decryption tool poc | https://github.com/full-disclosure/FDEU-CVE-2021-525A | 未查询到CVE信息| 
| 20210709T09:46:16Z | CVE-2021-34527 | Null | https://github.com/dywhoami/CVE-2021-34527-Scanner-Based-On-cube0x0-POC | Windows Print Spooler Remote Code Execution Vulnerability| 
| 20210709T09:17:54Z | CVE-2020-15368 | How to exploit a vulnerable windows driver. Exploit for AsrDrv104.sys | https://github.com/stong/CVE-2020-15368 | AsrDrv103.sys in the ASRock RGB Driver does not properly restrict access from user space, as demonstrated by triggering a triple fault via a request to zero CR3.| 
| 20210709T05:18:47Z | CVE-2021-21985 | Null | https://github.com/haiclover/CVE-2021-21985 | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210709T04:39:59Z | CVE-2021-22911 | Pre-Auth Blind NoSQL Injection leading to Remote Code Execution in Rocket Chat 3.12.1 | https://github.com/CsEnox/CVE-2021-22911 | A improper input sanitization vulnerability exists in Rocket.Chat server 3.11, 3.12 & 3.13 that could lead to unauthenticated NoSQL injection, resulting potentially in RCE.| 
| 20210709T04:30:38Z | CVE-2020-14321 | Python script to exploit CVE-2020-14321 - Moodle 3.9 - Course enrollments allowed privilege escalation from teacher role into manager role to RCE. | https://github.com/lanzt/CVE-2020-14321 | 未查询到CVE信息| 
| 20210709T03:54:14Z | CVE-2021-34527 | Mitigation for CVE-2021-34527 RCE by setting WRITE ACLs | https://github.com/WidespreadPandemic/CVE-2021-34527_ACL_mitigation | Windows Print Spooler Remote Code Execution Vulnerability| 
| 20210709T02:12:35Z | CVE-2020-22222 | CVE-2020-22222 | https://github.com/arch3rPro/CVE-2020-22222 | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210709T14:09:51Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 708 | 16| 
| 20210709T09:46:08Z | Null | https://github.com/thierry-tct/KLEE-SEMu | 3 | 2| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210709T23:50:29Z | A modern exploiting solution, built for Roblox and Rojo | https://github.com/richie0866/Rostruct | 3 | 1| 
| 20210709T22:49:42Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9684 | 1590| 
| 20210709T21:22:49Z | Since not everyone has access to Visual Studio at all times, this repository aims to have some useful compiled windows exploits/binaries that can be used while performing penetration testing. I do not take responsibility for any of the exploits nor do I own them, I would highly suggest to first test them in a Virtual Machine before actually running them against your target. | https://github.com/sidchn/Windows-Compiled-Exploits | 0 | 0| 
| 20210709T20:21:10Z | Null | https://github.com/ParagonExploit/exploit | 0 | 0| 
| 20210709T20:16:59Z | Practice repository for binary exploitation and fuzzing | https://github.com/RickdeJager/binexp-practice | 0 | 0| 
| 20210709T20:16:28Z | Null | https://github.com/Whomever0/exploit-scripts | 0 | 0| 
| 20210709T19:57:07Z | ExploitDev Practice  | https://github.com/ryanvillarreal/ExploitDev | 0 | 0| 
| 20210709T19:49:30Z | Educational web application demonstrating techniques of binary exploitation - (Back-end) | https://github.com/Pen-Test3rs/binary_exploits_backend | 0 | 0| 
| 20210709T19:45:29Z | An anti-exploit attempt for Fabric | https://github.com/samolego/GolfIV | 26 | 5| 
| 20210709T19:44:35Z | Hack/Exploits for https://krunker.io/ | https://github.com/glixzzy/krunker.io-hacks | 6 | 35| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210709T23:13:54Z | Yet Another PHP Shell | https://github.com/Nickguitar/YAPS | 4 | 0| 
| 20210709T22:19:52Z | Backdoor using nc, in c++ with persistence mode | https://github.com/Utobih/Ngrok_backdoor_auto_update_with_persistence | 0 | 0| 
| 20210709T18:08:02Z | EcchiExploit Shell v1.0 | https://github.com/dmzhari/ecchi-shell | 0 | 1| 
| 20210709T16:49:40Z | PHP Backdoor is a web-based application that allows to execute terminal commands on a server directly from a browser. | https://github.com/psyll/PHP-Backdoor | 1 | 0| 
| 20210709T15:58:48Z | Null | https://github.com/iK4oS/PremiumBackdoor.exe | 0 | 1| 
| 20210709T12:23:55Z | Null | https://github.com/AakashBanik/backdoor-tools | 0 | 0| 
| 20210709T11:10:39Z | A Python module for building botnet ,backdoor or trojan with Telegram control panel | https://github.com/onionj/pybotnet | 4 | 3| 
| 20210709T09:05:34Z | Null | https://github.com/FierzaEriez/Mini-Shell-Backdoor | 1 | 0| 
| 20210709T08:09:56Z | Null | https://github.com/FierzaEriez/FX-Super-Mini-Shell-Backdoor | 0 | 0| 
| 20210709T07:45:04Z | Simple Web Shell Backdoor can Bypass All Server with WAF instead | https://github.com/willygoid/H4x0rShell | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210709T19:49:48Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 146 | 33| 
| 20210709T14:06:16Z | Symbolic-execution-based verifier for the Viper intermediate verification language. | https://github.com/viperproject/silicon | 19 | 11| 
| 20210709T12:35:09Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2380 | 349| 
| 20210709T11:53:16Z | FuSeBMC is a White-Box Fuzzer that combines FUzzing with Symbolic Execution via Bounded Model Checking to verify intricate properties in real-world C programs. | https://github.com/kaled-alshmrany/FuSeBMC | 18 | 1| 
| 20210709T10:08:20Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 14 | 3| 
| 20210709T07:58:21Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 433 | 67| 
| 20210709T03:18:10Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1838 | 385| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210709T22:32:44Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210709T22:01:37Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210709T20:59:39Z | Null | https://github.com/drtychai/fuzzing-templates | 0 | 0| 
| 20210709T20:53:23Z | A passive diode fuzz Eurorack module with switches for changing which diodes are included | https://github.com/rahji/fivefingerfuzz | 0 | 0| 
| 20210709T20:19:14Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 482 | 48| 
| 20210709T20:16:59Z | Practice repository for binary exploitation and fuzzing | https://github.com/RickdeJager/binexp-practice | 0 | 0| 
| 20210709T20:04:28Z | Fuzzinator Random Testing Framework | https://github.com/renatahodovan/fuzzinator | 177 | 38| 
| 20210709T19:38:02Z | Ongoing development of the Fuzzball MUCK server software and associated functionality. | https://github.com/fuzzball-muck/fuzzball | 34 | 23| 
| 20210709T19:32:20Z | Null | https://github.com/UnisinosContinentais/ContinentalFuzzyLibrary | 1 | 0| 
| 20210709T19:31:27Z | Gentoo overlay | https://github.com/lferra/fuzzy-potato | 0 | 0| 



# 日更新程序
