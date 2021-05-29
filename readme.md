# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210528 | 编写 Ghidra Processor Module 分析 V8 字节码 | http://swarm.ptsecurity.com/creating-a-ghidra-processor-module-in-sleigh-using-v8-bytecode-as-an-example/| 
| 20210528 | CVE-2021-33564 Argument Injection in Ruby Dragonfly | https://zxsecurity.co.nz/research/argunment-injection-ruby-dragonfly/| 
| 20210528 | wowGrail - HITB 会议演讲，逆向分析 WOW64 兼容层以及如何利用它实现杀软检测逃逸 | https://github.com/aaaddress1/wowGrail| 
| 20210528 | 这篇 Blog 讨论如何检测杀软逃逸技术中经常使用的 DLL unhooking | https://passthehashbrowns.github.io/hook-integrity-checks| 
| 20210528 | 利用无监督的机器学习与 KQL 检测 C&C Beacon | https://mergene.medium.com/enterprise-scale-threat-hunting-network-beacon-detection-with-unsupervised-ml-and-kql-part-2-bff46cfc1e7e| 
| 20210528 | 俄罗斯 APT29 组织利用选举诈骗相关主题邮件发起攻击 | https://www.volexity.com/blog/2021/05/27/suspected-apt29-operation-launches-election-fraud-themed-phishing-campaigns/| 
| 20210528 | PlayStation 5 SMAP 内核保护机制 Bypass 漏洞分析 | https://hackerone.com/reports/1048322| 
| 20210528 | FireEye 发了一篇 Blog：Re-Checking Your Pulse: Updates on Chinese APT Actors Compromising Pulse Secure VPN Devices | https://www.fireeye.com/blog/threat-research/2021/05/updates-on-chinese-apt-compromising-pulse-secure-vpn-devices.html| 
| 20210528 | CVE-2021-31440: An Incorrect Bounds Calculation in the Linux Kernel eBPF Verifier | https://www.thezdi.com/blog/2021/5/26/cve-2021-31440-an-incorrect-bounds-calculation-in-the-linux-kernel-ebpf-verifier| 
| 20210528 | macOS 版本 TeamViewer Distributed Objects IPC 机制本地提权漏洞分析 | https://sec.today/pulses/8088061a-8ebb-4530-914a-49805892648d/| 
| 20210528 | macOS 版本 TeamViewer Distributed Objects IPC 机制本地提权漏洞分析 | https://theevilbit.github.io/posts/teamviewer_lpe/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210528 | 拿下靶机ColddWorld: Immersion | https://www.sec-in.com/article/1046| 
| 20210528 | 一站式Apache Kafka集群指标监控与运维管控平台 | https://github.com/didi/Logi-KafkaManager| 
| 20210528 | 隐藏源IP，提高溯源难度的几种方案 | https://mp.weixin.qq.com/s/cFK73WyHm7uE3L5aRa2D5w| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210528T23:42:13Z | CVE-2021-33564 | Argument Injection in Dragonfly Ruby Gem | https://github.com/mlr0p/CVE-2021-33564 | 未查询到CVE信息| 
| 20210528T18:08:15Z | CVE-2020-8813 | Cacti v1.2.8 Unauthenticated Remote Code Execution | https://github.com/hexcowboy/CVE-2020-8813 | | 
| 20210528T16:54:31Z | CVE-2021-29629 | PoC for exploiting CVE-2021-29629 | https://github.com/JamesGeee/CVE-2021-29629 | In FreeBSD 13.0-STABLE before n245765-bec0d2c9c841, 12.2-STABLE before r369859, 11.4-STABLE before r369866, 13.0-RELEASE before p1, 12.2-RELEASE before p7, and 11.4-RELEASE before p10, missing message validation in libradius(3) could allow malicious clients or servers to trigger denial of service in vulnerable servers or clients respectively.| 
| 20210528T16:54:26Z | CVE-2020-27208 | PoC for exploiting CVE-2020-27208 | https://github.com/JamesGeee/CVE-2020-27208 | The flash read-out protection (RDP) level is not enforced during the device initialization phase of the SoloKeys Solo 4.0.0 & Somu and the Nitrokey FIDO2 token. This allows an adversary to downgrade the RDP level and access secrets such as private ECC keys from SRAM via the debug interface.| 
| 20210528T16:54:25Z | CVE-2021-29628 | PoC for exploiting CVE-2021-29628 | https://github.com/JamesGeee/CVE-2021-29628 | In FreeBSD 13.0-STABLE before n245764-876ffe28796c, 12.2-STABLE before r369857, 13.0-RELEASE before p1, and 12.2-RELEASE before p7, a system call triggering a fault could cause SMAP protections to be disabled for the duration of the system call. This weakness could be combined with other kernel bugs to craft an exploit.| 
| 20210528T16:54:21Z | CVE-2020-12061 | PoC for exploiting CVE-2020-12061 | https://github.com/JamesGeee/CVE-2020-12061 | An issue was discovered in Nitrokey FIDO U2F firmware through 1.1. Communication between the microcontroller and the secure element transmits credentials in plain. This allows an adversary to eavesdrop the communication and derive the secrets stored in the microcontroller. As a result, the attacker is able to arbitrarily manipulate the firmware of the microcontroller.| 
| 20210528T16:54:20Z | CVE-2021-33516 | PoC for exploiting CVE-2021-33516 | https://github.com/JamesGeee/CVE-2021-33516 | An issue was discovered in GUPnP before 1.0.7 and 1.1.x and 1.2.x before 1.2.5. It allows DNS rebinding. A remote web server can exploit this vulnerability to trick a victim%s browser into triggering actions against local UPnP services implemented using this library. Depending on the affected service, this could be used for data exfiltration, data tempering, etc.| 
| 20210528T16:47:25Z | CVE-2020-14295 | Proof of Concept for CVE-2020-14295. | https://github.com/mrg3ntl3m4n/poc-CVE-2020-14295 | A SQL injection issue in color.php in Cacti 1.2.12 allows an admin to inject SQL via the filter parameter. This can lead to remote command execution because the product accepts stacked queries.| 
| 20210528T14:35:20Z | CVE-2021-3156 | CVE-2021-3156: Sudo heap overflow exploit for Debain 10 | https://github.com/0xdevil/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210528T08:37:46Z | CVE-2021-21551 | Script to patch your domain computers about the CVE-2021-21551. Privesc on machines that have the driver dbutil_2_3.sys, installed by some DELL tools (BIOS updater, SupportAssist...) | https://github.com/arnaudluti/PS-CVE-2021-21551 | Dell dbutil_2_3.sys driver contains an insufficient access control vulnerability which may lead to escalation of privileges, denial of service, or information disclosure. Local authenticated user access is required.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210528T21:00:59Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 14 | 44| 
| 20210528T19:09:28Z | New portfolio website using react and material ui.  | https://github.com/collinkleest/kleest.io | 1 | 0| 
| 20210528T13:32:45Z | Null | https://github.com/KleePaimon/KleePaimon.github.io | 0 | 0| 
| 20210528T07:13:24Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1704 | 494| 
| 20210528T04:41:55Z | Null | https://github.com/sanghu1790/KLEEMA | 0 | 0| 
| 20210528T03:31:15Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 635 | 15| 
| 20210528T00:55:07Z | Null | https://github.com/JaimePSantos/ResearchKlee | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210528T23:53:40Z | The generalized normal distribution is ruled by a parameter %beta% and comprises famous distributions, such as normal (beta=2) and Laplace (beta=1). The uniform distribution is also included, as beta diverges. Current implementation in R package gnorm exploits relation with gamma distribution to simulate random draws. This implementation is proner to break down as beta diverges. For beta >= 1, the GN density is log-concave, so I propose a rng based on Devroye%s method. This alternative implementation does not break down as beta diverges. It is also provides an educational example of application for Devroye%s elegant and general method. | https://github.com/mlambardi/gnorm | 0 | 0| 
| 20210528T22:57:42Z | PS1 savegame exploit | https://github.com/socram8888/tonyhax | 286 | 8| 
| 20210528T21:52:07Z | A tool to identify and exploit sudo rules% misconfigurations and vulnerabilities within sudo for linux privilege escalation. | https://github.com/TH3xACE/SUDO_KILLER | 1153 | 161| 
| 20210528T21:35:13Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9506 | 1538| 
| 20210528T21:19:06Z | An R package of data from the Kootenay Lake Exploitation Study | https://github.com/poissonconsulting/klexdatr | 0 | 1| 
| 20210528T21:14:23Z | A general purpose memory allocator that implements an isolation security strategy to mitigate memory safety issues while maintaining good performance | https://github.com/struct/isoalloc | 152 | 10| 
| 20210528T19:57:47Z | Null | https://github.com/ArianeBlow/exploit-eyesofnetwork5.3.10 | 0 | 0| 
| 20210528T19:25:55Z | Public Crash Lobby Exploit | https://github.com/flowd1337/crash-lobby-exploit | 0 | 0| 
| 20210528T18:54:45Z | Developing and backtesting performance of a market neutral trading strategy which aims to exploit temporary anomalies in correlation between 2 pair of assets. | https://github.com/Naharul98/Pairs-Trading-Highly-Correlated-Assets | 0 | 0| 
| 20210528T18:51:20Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 16 | 11| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210528T23:06:51Z | We find most existing triggers of backdoor attacks in deep learning contain severe artifacts in the frequency domain. This Repo. explores how we can use these artifacts to develop stronger backdoor defenses and attacks. | https://github.com/YiZeng623/frequency-backdoor | 2 | 0| 
| 20210528T22:46:25Z | Create a backdoor to a WordPress website. | https://github.com/majidamiri70/backdoor_for_wp | 0 | 0| 
| 20210528T18:12:55Z | Null | https://github.com/PesAdam/backdoors | 0 | 0| 
| 20210528T16:51:16Z | Python 3 IRC Bot / Botnet | https://github.com/trackmastersteve/HackServ | 21 | 17| 
| 20210528T15:54:17Z | Actually run a given promise or mock its outcome based on a given input value | https://github.com/johanfive/backdoor | 1 | 0| 
| 20210528T13:36:41Z | this is advance py39 backdoor created to use in college project | https://github.com/Bhadresh-Malankiya/BackdoorPy3 | 0 | 0| 
| 20210528T12:19:12Z | Null | https://github.com/Timcore-programmer/backdoor | 0 | 0| 
| 20210528T07:21:21Z | Null | https://github.com/danchik1155/BackdoorIstok | 0 | 0| 
| 20210528T04:45:39Z | Code for the paper Explanation-Guided Backdoor Poisoning Attacks Against Malware Classifiers | https://github.com/ClonedOne/MalwareBackdoors | 4 | 1| 
| 20210528T03:13:43Z | Null | https://github.com/xpf/Backdoor-Learning-arXiv | 1 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210528T12:49:17Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 1774 | 349| 
| 20210528T12:44:59Z | Flanged 90 degrees elbow  | https://github.com/Chemutaiselim/fuzzy-octo-telegram | 0 | 0| 
| 20210528T12:43:27Z | Null | https://github.com/kemsdahsdhah217/fuzzy-disco | 0 | 0| 
| 20210528T12:18:44Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 434 | 37| 
| 20210528T12:15:13Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 7 | 5| 
| 20210528T11:43:06Z | 渗透测试路径字典，爆破字典。内容来自互联网和实战积累。 | https://github.com/cpkkcb/fuzzDicts | 88 | 42| 
| 20210528T11:32:48Z | Real firmware fuzz-tested with uEmu | https://github.com/MCUSec/uEmu-real_world_firmware | 2 | 1| 
| 20210528T11:08:58Z | Neuro-fuzzy systems course | https://github.com/qwerfah/neuro-fuzzy-systems | 0 | 0| 
| 20210528T10:43:10Z | dumb Vulnerable server fuzzer  | https://github.com/kallepalliraviteja/vulnserverfuzzer | 0 | 0| 
| 20210528T10:32:07Z | PerformanceFuzzer | https://github.com/KKimj/PerformanceFuzzer | 1 | 0| 



# 日更新程序
