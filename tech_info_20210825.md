# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210825 | 智能合约语言 Solidity 的静态分析工具 | https://github.com/crytic/slither| 
| 20210825 | Quantum Attack Resource Estimate: Using Shor’s Algorithm to Break RSA vs DH/DSA VS ECC | https://research.kudelskisecurity.com/2021/08/24/quantum-attack-resource-estimate-using-shors-algorithm-to-break-rsa-vs-dh-dsa-vs-ecc/| 
| 20210825 | 医疗设备 B. Braun 输液泵被发现多个安全漏洞 | https://www.mcafee.com/blogs/enterprise/mcafee-enterprise-atr/mcafee-enterprise-atr-uncovers-vulnerabilities-in-globally-used-b-braun-infusion-pump/| 
| 20210825 | Samsung S10+/S9 4.14 内核地址信息泄露漏洞分析 | https://ssd-disclosure.com/ssd-advisory-samsung-s10-s9-kernel-4-14-android-10-kernel-function-address-text-and-heap-address-information-leak/| 
| 20210825 | 5.14 版本的 Linux 内核新增了一个 memfd_secret 系统调用，用于解决地址空间共享相关的安全问题。 | http://lwn.net/Articles/865256/| 
| 20210825 | 利用符号执行工具 KLEE 为 Linux 内核的 Rust for Linux Repo 提供形式化验证支持 | https://project-oak.github.io/rust-verification-tools/2021/08/22/rust-on-linux-1.html| 
| 20210825 | 昨天推送过 Windows 插入雷蛇鼠标可以实现 Windows EoP 的漏洞，之后有研究员发现赛睿（SteelSeries）外设也存在相同问题 | http://0xsp.com/security%20research%20&%20development%20(SRD)/local-administrator-is-not-just-with-razer-it-is-possible-for-all| 
| 20210825 | 第三方重打包的 WhatsApp App 被发现嵌入 Triada 木马 | https://securelist.com/triada-trojan-in-whatsapp-mod/103679/| 
| 20210825 | Google 研究员 Natalie 在 BlackHat 会议上对多款即时通讯 App 的远程漏洞的分析 | https://i.blackhat.com/USA21/Wednesday-Handouts/us-21-Can-You-Hear-Me-Now-Remote-Eavesdropping-Vulnerabilities-In-Mobile-Messaging-Applications.pdf| 
| 20210825 | Windows系统编程视频教程：基础入门知识。 | https://www.pentesteracademy.com/course?id=51| 
| 20210825 | MESH: A Memory-Efficient Safe Heap for C/C++ | https://arxiv.org/abs/2108.08683| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210825 | 海量恶意样本下高性能 Yara 检测方案 | https://mp.weixin.qq.com/s/vtmrhjXzL3gj8m_1uwgtmw| 
| 20210825 | learning-codeql: CodeQL Java 全网最全的中文学习资料 | https://github.com/SummerSec/learning-codeql| 
| 20210825 | seed-emulator: A Python framework for creating emulation o... | https://github.com/seed-labs/seed-emulator| 
| 20210825 | 浅谈云上攻防——对象存储服务访问策略评估机制研究 | https://mp.weixin.qq.com/s/ncWGrMsIAvh9HEK1QC5IGQ| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210825T17:41:16Z | CVE-2021-39475 | Found multiple XSS vulnerabilities within PhoenixCart 1.0.8.0 | https://github.com/W4RCL0UD/CVE-2021-39475 | 未查询到CVE信息| 
| 20210825T17:39:15Z | CVE-2021-39476 | Null | https://github.com/W4RCL0UD/CVE-2021-39476 | 未查询到CVE信息| 
| 20210825T17:22:58Z | CVE-2021-37589 | Exploit to Virtua Software.  | https://github.com/LucaRibeiro/CVE-2021-37589 | 未查询到CVE信息| 
| 20210825T16:17:25Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210825T04:26:10Z | CVE-2021-39512 | Unauthenticated CSRF Account TakeOver in BigTreeCMS v4.4.14 | https://github.com/guusec/CVE-2021-39512-BigTreeCMS-v4.4.14-AccountTakeOver | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210825T15:10:27Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2653 | 68| 
| 20210825T11:30:19Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 220 | 36| 
| 20210825T11:27:00Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 172 | 19| 
| 20210825T09:21:22Z | A RISC-V RV32 virtual prototype based on riscv-vp with symbolic execution support | https://github.com/agra-uni-bremen/symex-vp | 2 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210825T23:44:28Z | GEF (GDB Enhanced Features) - a modern experience for GDB with advanced debugging features for exploit developers & reverse engineers ☢ | https://github.com/hugsy/gef | 3847 | 532| 
| 20210825T23:41:37Z | Exploits that I have written either on my own or inspired by other POCs | https://github.com/VWolt/Other-Exploits | 0 | 0| 
| 20210825T23:27:21Z | Root shell exploit for several Xiaomi routers: 4A Gigabit, 4A 100M, 4, 4C, 3Gv2, 4Q, miWifi 3C... | https://github.com/acecilia/OpenWRTInvasion | 510 | 108| 
| 20210825T23:20:00Z | Null | https://github.com/smokeroots/EXPLOIT-BUFFER-OVERFLOW | 0 | 0| 
| 20210825T21:52:53Z | A series of CTF/hacking challenge solutions for binary exploitation(or pwn)/reverse engineering/vulnerability research/memory corruption(or whatever term you use) | https://github.com/docfate111/binary_exploitation | 0 | 0| 
| 20210825T21:35:12Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9920 | 1656| 
| 20210825T21:27:19Z | This repository contains codes of ICCV2021 paper: SO-Pose: Exploiting Self-Occlusion for Direct 6D Pose Estimation | https://github.com/shangbuhuan13/SO-Pose | 5 | 1| 
| 20210825T20:58:58Z | Null | https://github.com/DevKitteny/exploits | 0 | 0| 
| 20210825T20:56:51Z | Exploit-db (is NOT the official APP). | https://github.com/gaiththewolf/Exploitdb | 1 | 0| 
| 20210825T20:16:32Z | Null | https://github.com/TheCrazzXz/Exploits-Lab | 0 | 1| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210825T18:24:34Z |  Access ADB On Browsers (: | https://github.com/jxroot/adbwebkit | 2 | 0| 
| 20210825T14:09:42Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 92 | 16| 
| 20210825T13:49:20Z | Windoor is a Windows Backdoor that uses ssh to gain access to the windows machine.  | https://github.com/Talhamehar007/windoor-ssh | 0 | 0| 
| 20210825T11:16:00Z | Keeping it simple - PHP backdoors. | https://github.com/F-Masood/php-backdoors | 0 | 0| 
| 20210825T11:14:10Z | Mini Shell PDI Perjuangan | https://github.com/Rzzky/PDIP-Shell-Backdoor | 0 | 0| 
| 20210825T09:25:47Z | Applying backdoor attacks to BadNet on MNIST and ResNet on CIFAR10 (for personal use). | https://github.com/vtu81/backdoor_attack | 0 | 0| 
| 20210825T05:36:42Z | Golang package for pentest | https://github.com/iIIusi0n/backkit | 3 | 0| 
| 20210825T03:51:54Z | 0.9 | https://github.com/Notme11/LeuxBackdoor | 1 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210825T17:33:05Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2435 | 361| 
| 20210825T16:42:50Z | A symbolic execution engine for LLVM IR | https://github.com/insufficiently-caffeinated/caffeine | 7 | 4| 
| 20210825T14:24:57Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 17 | 3| 
| 20210825T14:06:13Z | Symbolica%s open-source symbolic execution engine. | https://github.com/SymbolicaDev/Symbolica | 4 | 0| 
| 20210825T09:21:22Z | A RISC-V RV32 virtual prototype based on riscv-vp with symbolic execution support | https://github.com/agra-uni-bremen/symex-vp | 2 | 0| 
| 20210825T07:43:43Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1877 | 390| 
| 20210825T01:04:49Z | SymQEMU: Compilation-based symbolic execution for binaries | https://github.com/eurecom-s3/symqemu | 161 | 20| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210825T23:36:13Z | JQF + Zest: Coverage-guided semantic fuzzing for Java. | https://github.com/rohanpadhye/JQF | 389 | 56| 
| 20210825T23:31:55Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210825T23:29:17Z | 32-bit x86 OS capable of running console user application. | https://github.com/scopeInfinity/FuzzyOS | 1 | 0| 
| 20210825T22:47:23Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6576 | 1344| 
| 20210825T22:29:34Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 2001 | 397| 
| 20210825T22:23:02Z | Null | https://github.com/AdaLogics/fuzz-headers | 1 | 0| 
| 20210825T20:58:31Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210825T20:45:39Z | Fuzzinator Random Testing Framework | https://github.com/renatahodovan/fuzzinator | 178 | 38| 
| 20210825T20:41:40Z | USENIX 2021 - Nyx: Greybox Hypervisor Fuzzing using Fast Snapshots and Affine Types | https://github.com/RUB-SysSec/Nyx | 1 | 0| 
| 20210825T19:32:42Z | Find the ideal fuzz targets in a Rust codebase | https://github.com/trailofbits/siderophile | 120 | 9| 



# 日更新程序
