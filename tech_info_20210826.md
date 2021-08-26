# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210826 | Pwn2Own Vancouver 2021 比赛上 Exchange Server 中间人劫持 RCE 漏洞分析 | https://srcincite.io/blog/2021/08/25/pwn2own-vancouver-2021-microsoft-exchange-server-remote-code-execution.html| 
| 20210826 | Ghostscript Interpreter 9.50 版本 0Day 漏洞分析 | https://www.slideshare.net/neexemil/hotpics-2021| 
| 20210826 | 利用 Frida 绕过各类 Windows 反调试的方法 | http://www.layakk.com/blog/practical-examples-with-fridafrida-vs-anti-debug-techniques-on-windows-ii/| 
| 20210826 | Escape from chrome sandbox to root | https://vul.360.net/archives/217| 
| 20210826 | APT 组织 SparklingGoblin 使用的 SideWalk 后门的分析 | https://www.welivesecurity.com/2021/08/24/sidewalk-may-be-as-dangerous-as-crosswalk/| 
| 20210826 | TEMPEST 攻击 - 利用电源 LED 指示灯还原声音 | https://www.nassiben.com/glowworm-attack| 
| 20210826 | 以在线购物为目标的 Magecart 组织利用 Recaptcha.tech 域名发起的攻击 | https://www.perimeterx.com/tech-blog/2021/evolution-of-a-magecart-attack-leveraging-recaptcha-tech-domain/| 
| 20210826 | ghidra2frida - 为 Ghidra 静态分析工具写一个与 Frida 交互的工具，利用 Frida 动态分析的数据提升静态分析效果 | https://security.humanativaspa.it/ghidra2frida-the-new-bridge-between-ghidra-and-frida/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210826 | Escape from chrome sandbox to root | https://vul.360.net/archives/217?continueFlag=b9e944728e53a56fa7ff39d24c55dc4a| 
| 20210826 | Weaponizing Middleboxes for TCP Reflected Amplification | https://geneva.cs.umd.edu/posts/usenix21-weaponizing-censors/?continueFlag=b9e944728e53a56fa7ff39d24c55dc4a| 
| 20210826 | [HTB] Admirer Writeup | https://mp.weixin.qq.com/s/8scaoLaiENuL_L5eLM7hYg| 
| 20210826 | 面向开放域的无监督实体对齐 | https://mp.weixin.qq.com/s/gH1VNCUVT5Hd5lGaGvEO2w| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210826T11:23:58Z | CVE-2021-3490 | Null | https://github.com/chompie1337/Linux_LPE_eBPF_CVE-2021-3490 | The eBPF ALU32 bounds tracking for bitwise ops (AND, OR and XOR) in the Linux kernel did not properly update 32-bit bounds, which could be turned into out of bounds reads and writes in the Linux kernel and therefore, arbitrary code execution. This issue was fixed via commit 049c4e13714e (%bpf: Fix alu32 const subreg bound tracking on bitwise operations%) (v5.13-rc4) and backported to the stable kernels in v5.12.4, v5.11.21, and v5.10.37. The AND/OR issues were introduced by commit 3f50f132d840 (%bpf: Verifier, do explicit ALU32 bounds tracking%) (5.7-rc1) and the XOR variant was introduced by 2921c90d4718 (%bpf:Fix a verifier failure with xor%) ( 5.10-rc1).| 
| 20210826T05:39:41Z | CVE-2020-8169 | Null | https://github.com/madhans23/curl-curl-7_64_1_CVE-2020-8169_noPatch | curl 7.62.0 through 7.70.0 is vulnerable to an information disclosure vulnerability that can lead to a partial password being leaked over the network and to the DNS server(s).| 
| 20210826T04:44:03Z | CVE-2021-39379 | Null | https://github.com/security-n/CVE-2021-39379 | | 
| 20210826T04:40:46Z | CVE-2021-39378 | Null | https://github.com/security-n/CVE-2021-39378 | 未查询到CVE信息| 
| 20210826T04:35:34Z | CVE-2021-39377 | Null | https://github.com/security-n/CVE-2021-39377 | | 
| 20210826T02:59:58Z | CVE-2021-30551 | my exp for chrome V8 CVE-2021-30551 | https://github.com/xmzyshypnc/CVE-2021-30551 | Type confusion in V8 in Google Chrome prior to 91.0.4472.101 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page.| 
| 20210826T02:25:15Z | CVE-2021-39281 | Documentation for cve-2021-39281 | https://github.com/grahamhelton/CVE-2021-39281 | 未查询到CVE信息| 
| 20210826T02:09:11Z | CVE-2021-3441 | CVE-2021-3441 CVE Check is a python script to search targets for indicators of compromise to CVE-2021-3441 | https://github.com/tcbutler320/CVE-2021-3441-check | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210826T12:54:00Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2657 | 68| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210826T12:57:05Z | Moving Object Segmentation in 3D LiDAR Data: A Learning-based Approach Exploiting Sequential Data (RAL/IROS 2021) | https://github.com/PRBonn/LiDAR-MOS | 139 | 22| 
| 20210826T12:52:56Z | Use a system call dependency graph to detect malware and analyze their behavior. The system calls are extracted and collected by Fredrickson and et al.[1] it contains two sets of benchmarks: the malware and the regular software set. The malware set comprises 2631 samples pre-classified into 48 families and 11 types. The regular software set comprises 35 samples. A dependency graph is built from these system calls and a set of features for each software is extracted to specify the software behavior. A feature selection method is implemented to reduce the number of features by clustering them. Machine learning algorithms such as Decision Tree, Random Forest, K-Nearest Neighbors, Support Vector Machines, and Neural Networks are exploited to build two prediction models. The first model is a two-class model that classifies software into malware and regular software. The second model is a multi-class model, which identifies the type of malware, in addition to classifying the software to malware and regular software.  [1] Matt Fredrikson, Somesh Jha, Mihai Christodorescu, Reiner Sailer, and Xifeng Yan. Synthesizing near-optimal malware specifications from suspicious behaviors. In Security and Privacy (SP), 2010 IEEE Symposium on, pages 45–60. IEEE, 2010.  | https://github.com/MahsaSinaei/Malware-detection-by-system-call-graph-using-Machine-Learning | 0 | 0| 
| 20210826T12:52:26Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 21 | 13| 
| 20210826T12:35:12Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9923 | 1658| 
| 20210826T12:28:24Z | Random one liner scripts for use in reversing, exploit development etc. | https://github.com/keremenci/OneLiners | 0 | 0| 
| 20210826T12:11:49Z | XSS payloads for exploiting Markdown syntax | https://github.com/yousufislam/Markdown-XSS-Payloads | 0 | 0| 
| 20210826T12:03:02Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 29 | 15| 
| 20210826T12:02:57Z | Exploit-db (is NOT the official APP). | https://github.com/gaiththewolf/Exploitdb | 1 | 0| 
| 20210826T11:52:20Z | NOTES AND EXPLOITS | https://github.com/NITIN911/BOUNTY_HUNTER-HACK-THE-BOX | 0 | 0| 
| 20210826T11:45:36Z | My notes from doing https://exploit.education/nebula/ | https://github.com/cgolian/nebula-notes | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210826T10:33:46Z | 100% Undetectable NodeJS reverse shell backdoor virus that autoruns on startup. | https://github.com/I2rys/NRSBackdoor | 1 | 0| 
| 20210826T10:19:02Z | pybotnet -   A Python Library for building Botnet , Trojan or BackDoor for windows and linux with Telegram control panel  | https://github.com/onionj/pybotnet | 13 | 8| 
| 20210826T09:32:59Z | Min backdoor | https://github.com/XmXTheDev/backdoor | 0 | 0| 
| 20210826T09:17:12Z | Python malware trojan that was written in educational purposes only. It take your data and give remote access to your PC. Now only with VK. Later will add HTTP/TELEGRAM. | https://github.com/kirillzhosul/python-malware-trojan | 5 | 0| 
| 20210826T03:55:16Z | python backdoor | https://github.com/brookelee1/python-backdoor | 1 | 0| 
| 20210826T02:31:03Z | Sample backdoor with python | https://github.com/aaron-padilla-14/Backdoor-with-python | 0 | 0| 
| 20210826T02:24:38Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 93 | 16| 
| 20210826T01:38:23Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 289 | 54| 
| 20210826T00:13:14Z | A Hidden and Undetectable Remote Access Tool written in C++ and Server in Python3 | https://github.com/Ryan-AW/Windows-Backdoor | 17 | 4| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210826T03:16:09Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 458 | 69| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210826T12:54:28Z | NDSS 2020 - HYPER-CUBE: High-Dimensional Hypervisor Fuzzing | https://github.com/RUB-SysSec/Hypercube | 3 | 0| 
| 20210826T01:16:38Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 20 | 4| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210826T12:54:28Z | NDSS 2020 - HYPER-CUBE: High-Dimensional Hypervisor Fuzzing | https://github.com/RUB-SysSec/Hypercube | 3 | 0| 
| 20210826T12:51:13Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210826T12:48:30Z | USENIX 2021 - Nyx: Greybox Hypervisor Fuzzing using Fast Snapshots and Affine Types | https://github.com/RUB-SysSec/Nyx | 21 | 1| 
| 20210826T12:15:13Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 22 | 9| 
| 20210826T12:11:03Z | The first open-source AI-driven tool for automatically generating system-level test cases (also known as fuzzing) for web/enterprise applications. Currently targeting whitebox and blackbox testing of REST APIs. | https://github.com/EMResearch/EvoMaster | 179 | 36| 
| 20210826T11:51:38Z | Null | https://github.com/nhsd-exeter/dos-service-fuzzy-search-api | 1 | 0| 
| 20210826T11:50:28Z | This is a tool for fuzzing XSS vulnerabilities. It%s based on genetic algorithm. | https://github.com/Timofey21/darlene | 4 | 0| 
| 20210826T11:47:46Z | Take the current implementation and turning a microservice architecture | https://github.com/ccesarrod/FuzzyMicrosrvices | 0 | 0| 
| 20210826T11:43:41Z | Our solution for ICIAR 2018 Grand Challenge BACH dataset | https://github.com/subhankar01/fuzzyBACH | 2 | 0| 
| 20210826T11:30:10Z | Fuzzing tool for the 14th institute | https://github.com/Radon10043/fuzzing-tool-14 | 0 | 2| 



# 日更新程序
