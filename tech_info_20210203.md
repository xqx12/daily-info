# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210203 | 研究员 pwn0rz 公开了一个影响 macOS Fairplay 的越界读漏洞的 PoC（CVE-2021-1791） | https://gist.github.com/pwn0rz/e34ab9f6e46956621a9d4f98cf222320| 
| 20210203 | Spoofing and Attacking With Skype | https://blog.thecybersecuritytutor.com/spoofing-and-attacking-with-skype/| 
| 20210203 | 利用开源工具 Falco 实现对 MITRE ATT&CK 的检测 | https://sysdig.com/blog/mitre-defense-evasion-falco/| 
| 20210203 | INFILTRATE20 会议研究员 0xdea 关于 Solaris 操作系统多个漏洞研究的分享 | https://github.com/0xdea/raptor_infiltrate20| 
| 20210203 | Injecting Rogue DNS Records Using DHCP | https://www.trustedsec.com/blog/injecting-rogue-dns-records-using-dhcp/?utm_campaign=Blog%20Posts&utm_content=153064925&utm_medium=social&utm_source=twitter&hss_channel=tw-403811306| 
| 20210203 | ESET 对针对 Linux 系操作系统恶意软件 Kobalos 的分析报告 | https://www.welivesecurity.com/wp-content/uploads/2021/01/ESET_Kobalos.pdf| 
| 20210203 | Project Zero Maddie Stone 对 2020 年野外漏洞利用情况的综述 | https://github.com/maddiestone/ConPresentations/blob/master/Enigma2021.StateOf0day.pdf| 
| 20210203 | NCC Group 2020 年度研究报告，可以看到多个不同方向的研究成果 | https://research.nccgroup.com/2021/01/31/2020-annual-research-report/amp/| 
| 20210203 | 容器与云的碰撞——一次对MinIO的测试 | https://www.leavesongs.com/PENETRATION/the-collision-of-containers-and-the-cloud-pentesting-a-MinIO.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210203 | Metasploit 的 payload 特征 | https://mp.weixin.qq.com/s/C8jHikFag_CulJIcq0filg| 
| 20210203 | 安卓Native层共享库fuzzing技术思路及实践 | https://mp.weixin.qq.com/s/eqYj385SGCUo5errVx2CZg| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210203T23:30:21Z | CVE-2021-3156 | Root shell PoC for CVE-2021-3156 | https://github.com/CptGibbon/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210203T14:19:22Z | CVE-2021-3156 | Null | https://github.com/leterts/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210203T12:53:53Z | CVE-2021-3345 | Null | https://github.com/MLGRadish/CVE-2021-3345 | _gcry_md_block_write in cipher/hash-common.c in Libgcrypt version 1.9.0 has a heap-based buffer overflow when the digest final function sets a large count value. It is recommended to upgrade to 1.9.1 or later.| 
| 20210203T10:58:41Z | CVE-2021-3156 | CVE-2021-3156 Vagrant Lab | https://github.com/dinhbaouit/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210203T09:04:14Z | CVE-2021-3156 | Null | https://github.com/cdeletre/Serpentiel-CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210203T06:15:15Z | CVE-2020-27194 | my exp for CVE-2020-27194, tested on linux kernel 5.8.14. | https://github.com/xmzyshypnc/CVE-2020-27194 | An issue was discovered in the Linux kernel before 5.8.15. scalar32_min_max_or in kernel/bpf/verifier.c mishandles bounds tracking during use of 64-bit values, aka CID-5b9fbeb75b6a.| 
| 20210203T06:01:40Z | CVE-2020-1938 | Modified version of auxiliary/admin/http/tomcat_ghostcat, it can  Read any file | https://github.com/YU5Z8X2CvH1fv4ep/CVE-2020-1938-MSF-MODULE | When using the Apache JServ Protocol (AJP), care must be taken when trusting incoming connections to Apache Tomcat. Tomcat treats AJP connections as having higher trust than, for example, a similar HTTP connection. If such connections are available to an attacker, they can be exploited in ways that may be surprising. In Apache Tomcat 9.0.0.M1 to 9.0.0.30, 8.5.0 to 8.5.50 and 7.0.0 to 7.0.99, Tomcat shipped with an AJP Connector enabled by default that listened on all configured IP addresses. It was expected (and recommended in the security guide) that this Connector would be disabled if not required. This vulnerability report identified a mechanism that allowed: - returning arbitrary files from anywhere in the web application - processing any file in the web application as a JSP Further, if the web application allowed file upload and stored those files within the web application (or the attacker was able to control the content of the web application by some other means) then this, along with the ability to process a file as a JSP, made remote code execution possible. It is important to note that mitigation is only required if an AJP port is accessible to untrusted users. Users wishing to take a defence-in-depth approach and block the vector that permits returning arbitrary files and execution as JSP may upgrade to Apache Tomcat 9.0.31, 8.5.51 or 7.0.100 or later. A number of changes were made to the default AJP Connector configuration in 9.0.31 to harden the default configuration. It is likely that users upgrading to 9.0.31, 8.5.51 or 7.0.100 or later will need to make small changes to their configurations.| 
| 20210203T04:53:47Z | CVE-2021-3156 | Null | https://github.com/SantiagoSerrao/ScannerCVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210203T23:57:42Z | An open-source Chinese font derived from Fontworks% Klee One | https://github.com/lxgw/LxgwWenKai | 6 | 0| 
| 20210203T18:23:13Z | The compiler inputs a PDDL benchmark of the Carpark planning problem and converts it to an equivalent C code which is used for solving the planning problem by program verification tools such as KLEE/TracerX. | https://github.com/daneshvar-amrollahi/Carpark-PDDL2C | 0 | 0| 
| 20210203T17:05:50Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1622 | 482| 
| 20210203T16:03:55Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 5 | 1| 
| 20210203T13:52:48Z | Null | https://github.com/fontworks-fonts/Klee | 350 | 9| 
| 20210203T11:34:32Z | Null | https://github.com/alsoknownaszac/kleekit | 0 | 0| 
| 20210203T11:08:33Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 212 | 34| 
| 20210203T07:33:42Z | Null | https://github.com/jiseongg/klee_experiment | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210203T23:47:27Z | A repository containing code from Hacking: Art of Exploitation to understand overflow vulnerabilities. | https://github.com/nightfuryninja/overflows | 0 | 0| 
| 20210203T23:43:18Z | Exploit Database | https://github.com/todordonev/exploitdb | 0 | 0| 
| 20210203T23:28:44Z | Various ASM, C and C++ tools, shellcodes and exploit experiments. | https://github.com/forrest-orr/ExploitDev | 33 | 2| 
| 20210203T22:21:37Z | OWASP Benchmark is a test suite designed to verify the speed and accuracy of software vulnerability detection tools. A fully runnable web app written in Java, it supports analysis by Static (SAST), Dynamic (DAST), and Runtime (IAST) tools that support Java. The idea is that since it is fully runnable and all the vulnerabilities are actually exploitable, it’s a fair test for any kind of vulnerability detection tool.  For more details on this project, please see the OWASP Benchmark Project home page. | https://github.com/OWASP/Benchmark | 331 | 228| 
| 20210203T22:10:38Z | Pillar is a multi channel real time communiaction app exploiting MERN stack%s full potential. The app is purposely crafted with the goal to facilitate efficient group communications | https://github.com/dabaojian1992/Pillar | 0 | 0| 
| 20210203T21:36:47Z | Multi camera gathering and exploiting tool | https://github.com/M0tHs3C/Argo | 21 | 12| 
| 20210203T21:27:09Z | A console based exploit template for ROBLOX. | https://github.com/dubbxq/RCONSOLE | 0 | 0| 
| 20210203T21:24:21Z | Exploit para dar deface em sites vulneraveis | https://github.com/devspray/MassDeface | 0 | 0| 
| 20210203T21:21:48Z | Roblox Exploit with various custom function. Stable and Free to use. | https://github.com/ExoticN01/RektSploit | 1 | 0| 
| 20210203T21:10:16Z | An attack/exploit Detector that utilizes Polymorphism and Diversity | https://github.com/polyverse/zerotect | 21 | 1| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210203T20:53:17Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 36 | 8| 
| 20210203T20:01:28Z | %Socialx% is a Social Engineering And Remote Access Trojan Tool. You can generate fud backdoor and you can embed any file you want inside of the exe file. | https://github.com/AzizKpln/Social_X | 47 | 16| 
| 20210203T13:10:07Z | Null | https://github.com/angelo1104/backdoor-client | 0 | 0| 
| 20210203T12:46:18Z | Null | https://github.com/angelo1104/backdoor-server | 0 | 0| 
| 20210203T12:32:04Z | This is a python program backdoor embeded with a game for reverse connection from the victim to understand the use visit our youtube channel STRANGE LEARNINGS  | https://github.com/EnriqueStrange/Advanced-Backdoor | 0 | 0| 
| 20210203T10:13:02Z | Null | https://github.com/k0rup710n/Python-Backdoor | 0 | 0| 
| 20210203T03:24:54Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 162 | 23| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210203T23:34:18Z | Open Enclave specific security automation projects (CodeQL static analysis, Fuzzing and binary analysis). | https://github.com/openenclave/openenclave-security | 0 | 1| 
| 20210203T23:32:59Z | FuzzBench - Fuzzer benchmarking as a service. | https://github.com/google/fuzzbench | 592 | 98| 
| 20210203T23:19:00Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 5837 | 1178| 
| 20210203T22:52:51Z | Generate code for json encoders/decoders, codecs, fuzzers, generators, and more | https://github.com/MartinSStewart/elm-review-todo-it-for-me | 0 | 0| 
| 20210203T22:39:30Z | RESTler is the first stateful REST API fuzzing tool for automatically testing cloud services through their REST APIs and finding security and reliability bugs in these services. | https://github.com/microsoft/restler-fuzzer | 653 | 61| 
| 20210203T22:24:15Z | Fuzzy diagnosis of oil-related thermal failure in power transformers | https://github.com/dromero1/fuzzy-diagnosis-thermal-failure | 0 | 0| 
| 20210203T22:07:20Z | {golang, ptrace, snapshot}-based fuzzer | https://github.com/geeksonsecurity/snapandgo | 2 | 0| 
| 20210203T21:40:32Z | Operations on fuzzy sets (program implemented as part of programming engineering studies) | https://github.com/Pomianowski/Fuzzy | 0 | 0| 
| 20210203T21:37:48Z | Null | https://github.com/dusha1248/fuzzy-sets | 0 | 0| 
| 20210203T21:24:39Z | Fuzzy and Neural network | https://github.com/Dsraj007/fuzzy | 0 | 0| 



# 日更新程序
