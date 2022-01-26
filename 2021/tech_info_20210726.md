# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210726 | Python 正则表达式 re.match 匹配存在被绕过的问题 | https://www.secjuice.com/python-re-match-bypass-technique/| 
| 20210726 | Beanshooter - 检测 JMX endpoints 常见漏洞的工具 | http://github.com/qtc-de/beanshooter| 
| 20210726 | Kernel Forge library - 方便开启 Windows Virtualization-based Security (VBS) 的系统开发 Kernel Payload 的工具库 | https://github.com/Cr4sh/KernelForge| 
| 20210726 | 利用浏览器 WebAssembly 端口扫描的结果实现用户指纹识别 | https://avi-lumelsky.medium.com/identify-website-users-by-client-port-scanning-using-webassembly-and-go-e9798b4aa05c| 
| 20210726 | From RPC to RCE - Workstation Takeover via RBCD and MS-RPChoose | https://gist.github.com/gladiatx0r/1ffe59031d42c08603a3bde0ff678feb| 
| 20210726 | Relaying Potatoes - 利用 Windows RPC 协议漏洞结合 NTLM relaying 实现特权提升 | https://labs.sentinelone.com/relaying-potatoes-dce-rpc-ntlm-relay-eop/| 
| 20210726 | CVE-2021-30798: TCC Bypass Again, Inspired By XCSSET | https://jhftss.github.io/CVE-2021-30798-TCC-Bypass-Again-Inspired-By-XCSSET/| 
| 20210726 | OWASP 开源的一款 IoT 固件，故意集成了多个漏洞，方便开发者学习 IoT 固件漏洞 | https://github.com/OWASP/IoTGoat| 
| 20210726 | D-Link DIR 3040 从信息泄露到RCE。 | https://paper.seebug.org/1650/| 
| 20210726 | 使用CyberChef工具对BASE85在线解密演示视频。 | https://www.youtube.com/watch?v=Xb_4n8e1OfE| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210726 | 针对Web缓存欺骗(WCD)攻击的大规模测试的论文【英文】 | https://www.usenix.org/conference/usenixsecurity20/presentation/mirheidari| 
| 20210726 | 安全建设-攻防思路与实践（一） | https://mp.weixin.qq.com/s/mnHGLZ_e3tWkxCL-DPAAvQ| 
| 20210726 | SecWiki周刊（第386期) | https://www.sec-wiki.com/weekly/386| 
| 20210726 | LuminousMoth样本分析报告 | https://mp.weixin.qq.com/s/BmLHQaiprcIxvRSacMFv_Q| 
| 20210726 | 论文-调查软件开发中方法命名情况 | https://mp.weixin.qq.com/s/bGyGUdJhru5BJuRY-k0pfg| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210726T23:42:27Z | CVE-2021-3156 | Null | https://github.com/dock0d1/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210726T20:07:04Z | CVE-2020-35846 | Python PoC for CVE-2020-35846 targeting Cockpit 0.11.1 | https://github.com/JohnHammond/CVE-2020-35846 | Agentejo Cockpit before 0.11.2 allows NoSQL injection via the Controller/Auth.php check function.| 
| 20210726T18:49:30Z | CVE-2021-21972 | Null | https://github.com/haiclover/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210726T15:03:49Z | CVE-2020-14343 | Experimenting with the CVE-2020-14343 PyYAML vulnerability | https://github.com/raul23/pyyaml-CVE-2020-14343 | A vulnerability was discovered in the PyYAML library in versions before 5.4, where it is susceptible to arbitrary code execution when it processes untrusted YAML files through the full_load method or with the FullLoader loader. Applications that use the library to process untrusted input may be vulnerable to this flaw. This flaw allows an attacker to execute arbitrary code on the system by abusing the python/object/new constructor. This flaw is due to an incomplete fix for CVE-2020-1747.| 
| 20210726T10:21:51Z | cve-2021-33909 | This module fixes an issue in the kernels filesystem layer (CVE-2021-33909) by kprobe-replacing vulnerable functions during runtime | https://github.com/baerwolf/cve-2021-33909 | fs/seq_file.c in the Linux kernel 3.16 through 5.13.x before 5.13.4 does not properly restrict seq buffer allocations, leading to an integer overflow, an Out-of-bounds Write, and escalation to root by an unprivileged user, aka CID-8cae8cd89f05.| 
| 20210726T08:37:39Z | CVE-2021-37152 | Exploit Accsess network clients by sending packets in wirless TP-LINK and preparing for a mitm attack | https://github.com/lhashashinl/CVE-2021-37152 | 未查询到CVE信息| 
| 20210726T08:30:31Z | CVE-2021-33909 | Exploit code for CVE-2021-33909,Just a dump of removed https://github.com/AmIAHuman/ repo | https://github.com/bbinfosec43/CVE-2021-33909 | fs/seq_file.c in the Linux kernel 3.16 through 5.13.x before 5.13.4 does not properly restrict seq buffer allocations, leading to an integer overflow, an Out-of-bounds Write, and escalation to root by an unprivileged user, aka CID-8cae8cd89f05.| 
| 20210726T08:18:37Z | CVE-2021-36934 | Null | https://github.com/0x0D1n/CVE-2021-36934 | Windows Elevation of Privilege Vulnerability| 
| 20210726T07:12:07Z | CVE-2021-3560 | CVE-2021-3560 (Polkit - Local Privilege Escalation) | https://github.com/deathflash1411/CVE-2021-3560 | 未查询到CVE信息| 
| 20210726T07:11:48Z | CVE-2021-35448 | CVE-2021-35448 (Remote Mouse GUI 3.008 - Local Privilege Escalation) | https://github.com/deathflash1411/CVE-2021-35448 | Emote Interactive Remote Mouse 3.008 on Windows allows attackers to execute arbitrary programs as Administrator by using the Image Transfer Folder feature to navigate to cmd.exe. It binds to local ports to listen for incoming connections.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210726T19:32:48Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 15 | 45| 
| 20210726T17:56:23Z | Whole Program LLVM: wllvm ported to go | https://github.com/SRI-CSL/gllvm | 143 | 22| 
| 20210726T15:37:57Z | Null | https://github.com/vitaliiomelchenko/kleene | 0 | 0| 
| 20210726T02:55:52Z | klee+nme for user space aeg | https://github.com/jqhong/klee-nme-aeg | 1 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210726T07:22:48Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 145 | 35| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210726T23:52:45Z | Similar to the other binary exploitation exploits lab, but this time for web, exploiting with python ! | https://github.com/TheCrazzXz/Webexploits-Lab | 0 | 0| 
| 20210726T22:56:14Z | Exploit is Finished dudee | https://github.com/FobHus/FobHus-Phobos-Exploit | 0 | 0| 
| 20210726T22:52:19Z | vuln scanner, web spider, web scanner, auto exploiter, fuzzer, dll injector, shellcoder, backdoors, rootkits, debugger framework | https://github.com/irackit/softkeys | 0 | 0| 
| 20210726T22:23:12Z | Exploit Privado | https://github.com/whaomi23/Update-Defender | 0 | 0| 
| 20210726T22:21:18Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9770 | 1614| 
| 20210726T22:10:28Z | Null | https://github.com/GreenToxicAura/exploits | 0 | 0| 
| 20210726T22:03:34Z | Someone was using a very large powerful system to remotely access a clients system: This will uninstall malicious programs and DLL files based on a library of Heuristics and Machine Pattern learning: do not use if you use this if you have programs that match the profile | https://github.com/Sparrrow2020/Ara-s-Anti-RemotreAccesss-Exploit-patch-Beta- | 0 | 0| 
| 20210726T21:46:34Z | Thi powershell script has got to run in remote windows host, even for pivoting | https://github.com/FabioDefilippo/winallenum | 4 | 1| 
| 20210726T21:43:44Z | Just a pretty good multi api exploit I am working on. | https://github.com/7enDev/7enX | 0 | 0| 
| 20210726T21:23:33Z | Repository For RBX Exploits Created By SigmaTech | https://github.com/SigmaEG/RBXExploits | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210726T23:06:07Z | pybotnet -  Library for building botnet ,backdoor or trojan with Telegram control panel | https://github.com/onionj/pybotnet | 9 | 5| 
| 20210726T22:52:19Z | vuln scanner, web spider, web scanner, auto exploiter, fuzzer, dll injector, shellcoder, backdoors, rootkits, debugger framework | https://github.com/irackit/softkeys | 0 | 0| 
| 20210726T21:08:10Z | Null | https://github.com/HersonRuiz/Targeted-Backdoor-Attacks-on-Deep-Learning-Systems-Using-Data-Poisoning- | 0 | 0| 
| 20210726T17:21:58Z | Null | https://github.com/FierzaEriez/Mini-Shell-Backdoor | 1 | 1| 
| 20210726T16:28:26Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 87 | 16| 
| 20210726T15:05:01Z | A Backdoor Attack against 3D Point Cloud Classifiers | https://github.com/zhenxianglance/PCBA | 0 | 0| 
| 20210726T13:54:25Z | A simple remote tool written in C#.    一个简单的c#远控 | https://github.com/qwqdanchun/DcRat | 263 | 104| 
| 20210726T12:13:22Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 269 | 51| 
| 20210726T12:02:53Z | Nguontol Shell Backdoor  - Recoded By RzkyO | https://github.com/RzkyO/Nguontol-Shell | 0 | 0| 
| 20210726T05:32:47Z | Null | https://github.com/Samira-Valifakhr/reverse-backdoor | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210726T18:45:07Z | A tool for generating nonlinear numerical invariants for C and Java programs.  DIG uses dynamic analysis to infer invariants over program execution traces and applies symbolic execution to inferred invariants. | https://github.com/unsat/dig | 4 | 4| 
| 20210726T18:27:45Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 153 | 33| 
| 20210726T14:52:13Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2393 | 353| 
| 20210726T11:30:36Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1852 | 388| 
| 20210726T09:24:17Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 448 | 67| 
| 20210726T03:21:08Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 17 | 3| 
| 20210726T02:26:06Z | A toy symbolic execution engine, supporting the blog article ... | https://github.com/synacktiv/toy-wasm-symbexp | 2 | 0| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210726T22:04:21Z | Network data storage servlet (NDSS) is a tool to store any information you wish and to make it available for you and your applications. It could be, ie. a storage for your application properties. You can access your properties, using its name and your application id, both defined by you. Each property within one application id has to be unique. You can have as many properties and applications as you wish. Maximum size of property name is 35 characters and maximum size of its value is 10kB (10240 characters). | https://github.com/mabalew/ndss | 0 | 0| 
| 20210726T05:04:11Z | Null | https://github.com/vanzeunu/ndssss | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210726T23:26:19Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210726T23:04:27Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210726T23:01:29Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210726T22:57:48Z | Null | https://github.com/TemmieInstaller/fuzzy-octo-system.net | 0 | 0| 
| 20210726T22:52:19Z | vuln scanner, web spider, web scanner, auto exploiter, fuzzer, dll injector, shellcoder, backdoors, rootkits, debugger framework | https://github.com/irackit/softkeys | 0 | 0| 
| 20210726T21:43:30Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 506 | 48| 
| 20210726T21:35:35Z | Fuzzbuzz Using Node and React | https://github.com/darshanaslp/fuzzbuzz_assignmnet | 0 | 0| 
| 20210726T20:49:30Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 87 | 23| 
| 20210726T20:47:54Z | 🏆 Collection of bugs uncovered by fuzzing Rust code | https://github.com/rust-fuzz/trophy-case | 238 | 38| 
| 20210726T20:44:13Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 3 | 1| 



# 日更新程序
