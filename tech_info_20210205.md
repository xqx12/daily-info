# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210205 | Chainalysis 团队从区块链的角度分析发现 2020 年最大的 4 起勒索软件攻击实现存在关联 | https://blog.chainalysis.com/reports/ransomware-connections-maze-egregor-suncrypt-doppelpaymer| 
| 20210205 | Windows API IsDebuggerPresent 的实现分析 | https://medium.com/ax1al/isdebuggerpresent-internals-7be4ea642d33| 
| 20210205 | Abusing Google Chrome extension syncing for data exfiltration and C&C | https://isc.sans.edu/forums/diary/Abusing+Google+Chrome+extension+syncing+for+data+exfiltration+and+CC/27066/| 
| 20210205 | Tailoring Cobalt Strike on Target | https://blog.xpnsec.com/tailoring-cobalt-strike-on-target/| 
| 20210205 | 恢复成砖的 SSD | https://fmad.io/blog-ssd-bricked-restore.html| 
| 20210205 | Issue 2114: Apple CoreText libType1Scaler.dylib heap buffer overflow in Counter Control Hints | https://bugs.chromium.org/p/project-zero/issues/detail?id=2114| 
| 20210205 | A Look at CVE-2020-17087 | https://ch3rn0byl.com/2021/02/a-look-at-cve-2020-17087/| 
| 20210205 | 据 ENKI 研究员分析，朝鲜黑客除了利用 Chrome 漏洞攻击黑客，还使用了 IE 0Day | https://enki.co.kr/blog/2021/02/04/ie_0day.html| 
| 20210205 | 0day Exploit Root Cause Analyses | https://googleprojectzero.blogspot.com/p/rca.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210205 | 让网络空间测绘技术不再那么飘忽不定 | https://mp.weixin.qq.com/s/lr39F9kNOfHlMimgymzVwg| 
| 20210205 | gatekeeper: First open-source DDoS protection system | https://github.com/AltraMayor/gatekeeper| 
| 20210205 | Mitre Att&ck detection coverage tracking with Kibana | https://hmnguyen1201.github.io/Mitre-Att-ck-table/| 
| 20210205 | 2020全球高级持续性威胁APT研究报告 | https://zt.360.cn/1101061855.php?dtid=1101062360&did=211138962| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210205T22:20:18Z | CVE-2021-3156 | PoC for CVE-2021-3156 (sudo heap overflow) | https://github.com/stong/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210205T18:33:48Z | CVE-2021-3156 | Null | https://github.com/blasty/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210205T14:51:49Z | cve-2020-17523 | shiro-cve-2020-17523 漏洞的两种绕过姿势分析（带漏洞环境） | https://github.com/jweny/shiro-cve-2020-17523 | 未查询到CVE信息| 
| 20210205T11:22:31Z | CVE-2021-3156 | Root shell PoC for CVE-2021-3156 | https://github.com/CptGibbon/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210205T09:07:20Z | CVE-2021-3157 | Null | https://github.com/Y3rbit4/CVE-2021-3157 | 未查询到CVE信息| 
| 20210205T07:50:37Z | CVE-2020-14181 | Poc for CVE-2020-14181 | https://github.com/bk-rao/CVE-2020-14181 | Affected versions of Atlassian Jira Server and Data Center allow an unauthenticated user to enumerate users via an Information Disclosure vulnerability in the /ViewUserHover.jspa endpoint. The affected versions are before version 7.13.6, from version 8.0.0 before 8.5.7, and from version 8.6.0 before 8.12.0.| 
| 20210205T03:55:00Z | CVE-2021-25646 | CSharp CVE-2021-25646-GUI | https://github.com/AirEvan/CVE-2021-25646-GUI | Apache Druid includes the ability to execute user-provided JavaScript code embedded in various types of requests. This functionality is intended for use in high-trust environments, and is disabled by default. However, in Druid 0.20.0 and earlier, it is possible for an authenticated user to send a specially-crafted request that forces Druid to run user-provided JavaScript code for that request, regardless of server configuration. This can be leveraged to execute code on the target machine with the privileges of the Druid server process.| 
| 20210205T01:10:50Z | CVE-2020-17527 | Null | https://github.com/forse01/CVE-2020-17527-Tomcat | While investigating bug 64830 it was discovered that Apache Tomcat 10.0.0-M1 to 10.0.0-M9, 9.0.0-M1 to 9.0.39 and 8.5.0 to 8.5.59 could re-use an HTTP request header value from the previous stream received on an HTTP/2 connection for the request associated with the subsequent stream. While this would most likely lead to an error and the closure of the HTTP/2 connection, it is possible that information could leak between requests.| 
| 20210205T00:01:23Z | CVE-2020-25213 | Null | https://github.com/forse01/CVE-2020-25213-Wordpress | The File Manager (wp-file-manager) plugin before 6.9 for WordPress allows remote attackers to upload and execute arbitrary PHP code because it renames an unsafe example elFinder connector file to have the .php extension. This, for example, allows attackers to run the elFinder upload (or mkfile and put) command to write PHP code into the wp-content/plugins/wp-file-manager/lib/files/ directory. This was exploited in the wild in August and September 2020.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210205T10:16:53Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1623 | 482| 
| 20210205T08:46:22Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 107 | 6| 
| 20210205T02:11:25Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 5 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210205T10:16:49Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 95 | 22| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210205T23:46:45Z | free aram boost | https://github.com/devshadows/aram-exploit | 0 | 0| 
| 20210205T23:43:27Z | EternalBlue suite remade in C/C++ which includes: MS17-010 Exploit, EternalBlue vulnerability detector, DoublePulsar detector and DoublePulsar Shellcode & DLL uploader | https://github.com/bhassani/EternalBlueC | 306 | 77| 
| 20210205T23:29:13Z | windows and linux streams for post exploitation | https://github.com/kymb0/post_exploitation | 1 | 0| 
| 20210205T23:25:37Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 8975 | 1440| 
| 20210205T23:16:43Z | Escalate as Administrator bypassing the UAC affecting administrator accounts only. | https://github.com/0xyg3n/UAC_Exploit | 70 | 20| 
| 20210205T23:01:05Z | A game of spaceships exploiting astroids. | https://github.com/BlackLambert/astrominer | 0 | 0| 
| 20210205T22:18:16Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 4 | 1| 
| 20210205T21:32:06Z | A modern cLVM script execution exploit challenging Roblox%s new security and integrity checks. | https://github.com/AmirAgassi/exWare | 0 | 0| 
| 20210205T21:19:20Z | An open-source post-exploitation framework for students, researchers and developers. | https://github.com/malwaredllc/byob | 5842 | 1292| 
| 20210205T19:42:06Z | Null | https://github.com/MLD3/deep-learning-applied-to-chest-x-rays-exploiting-and-preventing-shortcuts | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210205T23:51:26Z | Motorola NC1500 Backdoor Password | https://github.com/billchaison/nc1500 | 2 | 0| 
| 20210205T21:24:36Z | Null | https://github.com/EjHvorSerDuVildUdJim/backdoor | 0 | 0| 
| 20210205T21:07:53Z | Backdoor for Garry`s Mod | https://github.com/luajscss/gbackdoor | 0 | 0| 
| 20210205T18:29:31Z | Dashboard for conducting Backdoors and Breaches sessions over Zoom. | https://github.com/p3hndrx/B-B-Shuffle | 1 | 0| 
| 20210205T18:16:59Z | FUD cross-platform python2 backdoor with C2 | https://github.com/7h3w4lk3r/pyback | 15 | 5| 
| 20210205T17:38:32Z | Null | https://github.com/ph-luffy/Backdoor | 1 | 1| 
| 20210205T15:48:00Z | Three sub-projects of different backdoor attack configurations scaling in complexity, with server and client implementations. | https://github.com/BrunoScaglione/Backdoor-Attack-Simulation | 0 | 0| 
| 20210205T14:29:04Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) remote administration and post-exploitation tool mainly written in python | https://github.com/n1nj4sec/pupy | 6124 | 1577| 
| 20210205T14:00:40Z | 使用投毒posion的方式backdoor攻击LeNet-5网络，使用MNIST手写数据集 | https://github.com/AgentGuo/Backdoor_Attack_LeNet5_MNIST | 0 | 0| 
| 20210205T11:32:58Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 164 | 23| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210205T12:53:15Z | Null | https://github.com/opimentel-github/fuzzy-torch | 0 | 0| 
| 20210205T12:51:35Z | An advances web fuzzing tool | https://github.com/agpriyansh/orbit | 0 | 0| 
| 20210205T12:50:03Z | Null | https://github.com/code-evince/Traffic-Lights-Fuzzy-Logic | 0 | 0| 
| 20210205T12:31:12Z | Null | https://github.com/TomLloyd92/FuzzyLogic | 0 | 0| 
| 20210205T12:29:46Z | CSFuzz: Call Sequence-based Greybox Fuzzing Tool | https://github.com/csfuzz/CSFuzz | 0 | 0| 
| 20210205T12:20:09Z | Null | https://github.com/Rizwana-coder/Fuzzy-Engine | 0 | 0| 
| 20210205T11:58:32Z | Null | https://github.com/fuzzsa/fuzzsa-bugs | 0 | 1| 
| 20210205T11:41:23Z | Fuzzing powered by grammar coverage | https://github.com/havrikov/tribble | 0 | 0| 
| 20210205T11:39:22Z | A groovy/java tabular Data (from CSV,SQL,JSON) processing library that supports fuzzy column matching,tranformations/merging/querying | https://github.com/kayr/fuzzy-csv | 7 | 6| 
| 20210205T11:27:22Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 4 | 1| 



# 日更新程序
