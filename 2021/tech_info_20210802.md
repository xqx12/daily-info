# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210802 | SDR++，跨平台、开源的 SDK 分析软件 | https://github.com/AlexandreRouma/SDRPlusPlus| 
| 20210802 | BIAS: Bluetooth Impersonation AttackS | https://francozappa.github.io/about-bias/| 
| 20210802 | 打印机驱动 CVE-2021-3438 漏洞的逆向分析 | https://voidsec.com/root-cause-analysis-of-cve-2021-3438/| 
| 20210802 | Windows 10 KVAS and Software SMEP | https://wumb0.in/windows-10-kvas-and-software-smep.html| 
| 20210802 | V8 脚本引擎 Heap Sandbox 的设计文档 | https://docs.google.com/document/d/1FM4fQmIhEqPG8uGp5o9A-mnPB5BOeScZYpkHjo0KKA8/edit| 
| 20210802 | Fuzzing Windows RPC with RpcView | https://itm4n.github.io/fuzzing-windows-rpc-rpcview/| 
| 20210802 | Ninja - 一款用于渗透测试的开源的 C&C Server | https://github.com/ahmedkhlief/Ninja| 
| 20210802 | 智能电动车充电桩安全测试 | https://www.pentestpartners.com/security-blog/smart-car-chargers-plug-n-play-for-hackers/| 
| 20210802 | 重新编译旧的森海塞尔麦克风 -第4部分-PLL(锁相环) | https://vgnotepad.blogspot.com/2021/06/reprogramming-old-sennheiser-microphone_3.html| 
| 20210802 | 破解协议（缓冲区）：逆向工程分析 gRPC 二进制文件。 | https://labs.ioactive.com/2021/07/breaking-protocol-buffers-reverse.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210802 | 如何利用多杀软结果归并恶意软件家族名称 | https://mp.weixin.qq.com/s/hOvqm0U7rc-NNdVjR0dAaA| 
| 20210802 | 做红队你需要学习“如何挖掘战壕”（三） | https://mp.weixin.qq.com/s/OO_VZ8QB_J5UY88qkpLXDg| 
| 20210802 | SecWiki周刊（第387期) | https://www.sec-wiki.com/weekly/387| 
| 20210802 | Attacking Active Directory: 0 to 0.9 | https://zer1t0.gitlab.io/posts/attacking_ad/| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210802T20:11:18Z | CVE-2021-22204 | Null | https://github.com/AssassinUKG/CVE-2021-22204 | Improper neutralization of user data in the DjVu file format in ExifTool versions 7.44 and up allows arbitrary code execution when parsing the malicious image| 
| 20210802T17:46:02Z | CVE-2021-21972 | Null | https://github.com/haiclover/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210802T16:05:56Z | CVE-2021-22204 | Null | https://github.com/PenTestical/CVE-2021-22204 | Improper neutralization of user data in the DjVu file format in ExifTool versions 7.44 and up allows arbitrary code execution when parsing the malicious image| 
| 20210802T14:50:39Z | cve-2021-1480 | PoC materials to exploit the CVE-2021-1480 on Cico SD-WAN. | https://github.com/xmco/sdwan-cve-2021-1480 | Multiple vulnerabilities in Cisco SD-WAN vManage Software could allow an unauthenticated, remote attacker to execute arbitrary code or allow an authenticated, local attacker to gain escalated privileges on an affected system. For more information about these vulnerabilities, see the Details section of this advisory.| 
| 20210802T13:51:42Z | CVE-2021-36934 | POC experiments with Volume Shadow copy Service (VSS) | https://github.com/grishinpv/poc_CVE-2021-36934 | Windows Elevation of Privilege Vulnerability| 
| 20210802T13:13:28Z | CVE-2020-27955 | Null | https://github.com/whitetea2424/CVE-2020-27955-LFS-main | Git LFS 2.12.0 allows Remote Code Execution.| 
| 20210802T12:22:04Z | CVE-2021-3490 | Null | https://github.com/chompie1337/Linux_LPE_eBPF_CVE-2021-3490 | The eBPF ALU32 bounds tracking for bitwise ops (AND, OR and XOR) in the Linux kernel did not properly update 32-bit bounds, which could be turned into out of bounds reads and writes in the Linux kernel and therefore, arbitrary code execution. This issue was fixed via commit 049c4e13714e (%bpf: Fix alu32 const subreg bound tracking on bitwise operations%) (v5.13-rc4) and backported to the stable kernels in v5.12.4, v5.11.21, and v5.10.37. The AND/OR issues were introduced by commit 3f50f132d840 (%bpf: Verifier, do explicit ALU32 bounds tracking%) (5.7-rc1) and the XOR variant was introduced by 2921c90d4718 (%bpf:Fix a verifier failure with xor%) ( 5.10-rc1).| 
| 20210802T08:34:20Z | CVE-2021-21300 | Null | https://github.com/xiaofeihahah/CVE-2021-21300 | Git is an open-source distributed revision control system. In affected versions of Git a specially crafted repository that contains symbolic links as well as files using a clean/smudge filter such as Git LFS, may cause just-checked out script to be executed while cloning onto a case-insensitive file system such as NTFS, HFS+ or APFS (i.e. the default file systems on Windows and macOS). Note that clean/smudge filters have to be configured for that. Git for Windows configures Git LFS by default, and is therefore vulnerable. The problem has been patched in the versions published on Tuesday, March 9th, 2021. As a workaound, if symbolic link support is disabled in Git (e.g. via `git config --global core.symlinks false`), the described attack won%t work. Likewise, if no clean/smudge filters such as Git LFS are configured globally (i.e. _before_ cloning), the attack is foiled. As always, it is best to avoid cloning repositories from untrusted sources. The earliest impacted version is 2.14.2. The fix versions are: 2.30.1, 2.29.3, 2.28.1, 2.27.1, 2.26.3, 2.25.5, 2.24.4, 2.23.4, 2.22.5, 2.21.4, 2.20.5, 2.19.6, 2.18.5, 2.17.62.17.6.| 
| 20210802T07:24:04Z | CVE-2021-33624 | Proof of Concept for CVE-2021-33624 | https://github.com/Kakashiiiiy/CVE-2021-33624 | In kernel/bpf/verifier.c in the Linux kernel before 5.12.13, a branch can be mispredicted (e.g., because of type confusion) and consequently an unprivileged BPF program can read arbitrary memory locations via a side-channel attack, aka CID-9183671af6db.| 
| 20210802T04:48:27Z | CVE-2021-31630 | Exploit for Authenticated Remote Code Execution on OpenPLC v3 Webserver | https://github.com/h3v0x/CVE-2021-31630-OpenPLC_RCE | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T22:54:46Z | Null | https://github.com/santiagoHV/kleer-dojo-assessment-backend | 0 | 0| 
| 20210802T15:16:36Z | Null | https://github.com/pansilup/cgc-prgs-for-klee-seed-mode | 0 | 0| 
| 20210802T09:51:15Z | Null | https://github.com/coffee100percnt/KleeDiscordBomber | 4 | 0| 
| 20210802T02:07:51Z | Null | https://github.com/adamhumphriescs/TASE_KLEE | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T11:21:56Z | Null | https://github.com/yuvalkirstain/s2e-coref | 11 | 4| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T23:39:25Z | I will be uploading all the exploit UIs i make for the community here. Thank you for visiting! | https://github.com/airp0dz/open-source-exploit | 0 | 0| 
| 20210802T23:16:54Z | Simple stuffs (exploit, extentions) for habboz.ws a french habbo game | https://github.com/Miisaakii/Habboz.ws-stuffs | 0 | 0| 
| 20210802T22:45:52Z | Basic Exploit Essentials is a multi-script, consisting of many great features! | https://github.com/Nextrixcs/Basic-Exploit-Essentials | 0 | 1| 
| 20210802T22:33:45Z | bad robox ui lib | https://github.com/ceat-ceat/ScriptPanelv2 | 0 | 0| 
| 20210802T22:03:47Z | Vulnerabilities% Risk of Exploitation | https://github.com/thiagofigcosta/V-REx-v2 | 0 | 0| 
| 20210802T21:35:14Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9803 | 1622| 
| 20210802T21:24:00Z | Exploit Development and Reverse Engineering with GDB Made Easy | https://github.com/pwndbg/pwndbg | 3842 | 553| 
| 20210802T21:23:15Z | The optimization field suffers from the metaphor-based “pseudo-novel” or “fancy” optimizers. Most of these cliché methods mimic animals% searching trends and possess a small contribution to the optimization process itself. Most of these cliché methods suffer from the locally efficient performance, biased verification methods on easy problems, and high similarity between their components% interactions. This study attempts to go beyond the traps of metaphors and introduce a novel metaphor-free population-based optimization method based on the mathematical foundations and ideas of the Runge Kutta (RK) method widely well-known in mathematics. The proposed RUNge Kutta optimizer (RUN) was developed to deal with various types of optimization problems in the future. The RUN utilizes the logic of slope variations computed by the RK method as a promising and logical searching mechanism for global optimization. This search mechanism benefits from two active exploration and exploitation phases for exploring the promising regions in the feature space and constructive movement toward the global best solution. Furthermore, an enhanced solution quality (ESQ) mechanism is employed to avoid the local optimal solutions and increase convergence speed. The RUN algorithm%s efficiency was evaluated by comparing with other metaheuristic algorithms in 50 mathematical test functions and four real-world engineering problems. The RUN provided very promising and competitive results, showing superior exploration and exploitation tendencies, fast convergence rate, and local optima avoidance. In optimizing the constrained engineering problems, the metaphor-free RUN demonstrated its suitable performance as well. The authors invite the community for extensive evaluations of this deep-rooted optimizer as a promising tool for real-world optimization. The source codes, supplementary materials, and guidance for the developed method will be publicly available at different hubs at http://imanahmadianfar.com and http://aliasgharheidari.com/RUN.html. | https://github.com/imahmadian/Runge-Kutta-Optimization-RUN- | 0 | 0| 
| 20210802T21:19:31Z | Infinite Yield ID2 is a %port% of the popular exploit script Infinite Yield for normal Roblox game scripts (Identity 2) | https://github.com/Nextrixcs/infinite-yield-id2 | 0 | 0| 
| 20210802T21:12:03Z | When it comes to exploiting web application security, this is a methodology. Enumeration and Networking guidelines are also listed to help while on a Pentest/CTF.  | https://github.com/Mdot0/Pentesting-Methodology- | 1 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T22:05:10Z | Malika is a very simple malware for GNU/Linux written in Python for educational purpose only. | https://github.com/CalfCrusher/malika | 0 | 0| 
| 20210802T18:41:46Z | Use me to create a corrupted cookie capable of creating a backdoor on the webserver node which uses the %serialize% function | https://github.com/DrBlackWolf/Node-Serialize-WebServer-Backdoor | 0 | 0| 
| 20210802T17:32:09Z | Null | https://github.com/FierzaEriez/Mini-Shell-Backdoor | 1 | 1| 
| 20210802T17:16:19Z | WIP (anti backdoor thing for the blox) | https://github.com/Deniied/Roblox-Developer-Security-Essentials | 0 | 0| 
| 20210802T16:53:48Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/Ghost | 1242 | 586| 
| 20210802T16:00:37Z | The given Python code is for a Reverse-Backdoor, that grants a User, Remote Code Execution access to a target computer. | https://github.com/iamKushGupta/Reverse-Backdoor-with-Listener | 0 | 0| 
| 20210802T15:58:15Z | Invisible, customizable backdoor for Minecraft Spigot Plugins. | https://github.com/ThiccIndustries/Minecraft-Backdoor | 21 | 7| 
| 20210802T13:07:39Z | Null | https://github.com/BackdoorTech/BackdoorTech | 0 | 0| 
| 20210802T08:36:44Z | Patch PE, ELF, Mach-O binaries with shellcode new version in development, available only to sponsors | https://github.com/secretsquirrel/the-backdoor-factory | 2820 | 760| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T23:39:26Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1739 | 499| 
| 20210802T22:55:51Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2405 | 355| 
| 20210802T20:16:15Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 451 | 68| 
| 20210802T13:39:37Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 153 | 33| 
| 20210802T04:08:56Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1861 | 387| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T10:52:04Z | Config files for my GitHub profile. | https://github.com/WlNDSS/WlNDSS | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T23:54:28Z | Null | https://github.com/opimentel-github/fuzzy-tools | 0 | 0| 
| 20210802T22:41:41Z | Scalable fuzzing infrastructure. | https://github.com/google/clusterfuzz | 4537 | 453| 
| 20210802T22:38:36Z | Fuzzer for Dolt repositories | https://github.com/dolthub/fuzzer | 2 | 0| 
| 20210802T22:17:03Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 292 | 39| 
| 20210802T21:39:03Z | A ground-truth fuzzing benchmark suite based on real programs with real bugs. | https://github.com/HexHive/magma | 130 | 39| 
| 20210802T21:26:34Z | Repository holding database dumps from getfursu.it | https://github.com/veelkoov/fuzzrake-data | 0 | 0| 
| 20210802T21:14:27Z | Collected fuzzing payloads from different resources  | https://github.com/osamahamad/FUZZING | 8 | 5| 
| 20210802T20:58:28Z | The code behind getfursu.it | https://github.com/veelkoov/fuzzrake | 6 | 0| 
| 20210802T19:44:54Z | Null | https://github.com/huycool/fuzzy-lamp | 0 | 0| 
| 20210802T19:16:28Z | A library of fuzzy rough machine learning algorithms | https://github.com/oulenz/fuzzy-rough-learn | 7 | 2| 



# 日更新程序
