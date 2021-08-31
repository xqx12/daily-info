# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210831 | NCCGroup 对 NFC 芯片安全的安全研究 | https://research.nccgroup.com/2021/08/30/the-abcs-of-nfc-chip-security/| 
| 20210831 | Apache Dubbo 被发现多个安全漏洞 | https://securitylab.github.com/advisories/GHSL-2021-094-096-apache-dubbo/| 
| 20210831 | Pwn2Own 比赛中所使用的 TP-Link Archer A7 路由器的漏洞的分析 | https://www.synacktiv.com/sites/default/files/2021-08/Pwn2Owning_the_TP-Link_Archer_A7.pdf| 
| 20210831 | Exploiting GraphQL | https://blog.assetnote.io/2021/08/29/exploiting-graphql/| 
| 20210831 | Windows (ETW) TimerCallbackContext 对象 UAF 漏洞分析（CVE-2021-34486） | https://www.pixiepointsecurity.com/blog/cve-2021-34486.html| 
| 20210831 | 用于处理 Intel Atom Microcode 的 Ghidra 插件 | https://github.com/pietroborrello/ghidra-atom-microcode| 
| 20210831 | Apple Remote Invocation (ARI) 协议的 Wireshark 解析脚本 | https://github.com/seemoo-lab/aristoteles| 
| 20210831 | ProxyToken: An Authentication Bypass in Microsoft Exchange Server | https://www.thezdi.com/blog/2021/8/30/proxytoken-an-authentication-bypass-in-microsoft-exchange-server| 
| 20210831 | CVE-2021-39165: 从一个Laravel SQL注入漏洞开始的Bug Bounty之旅 | https://www.leavesongs.com/PENETRATION/cachet-from-laravel-sqli-to-bug-bounty.html| 
| 20210831 | 利用 PetitPotam 的 NTLM relay 获取域管理员权限 | https://sec.today/pulses/bfbb1a8a-4bc5-43cd-bc5d-f0149b5e9421/| 
| 20210831 | 利用 PetitPotam 的 NTLM relay 获取域管理员权限 | https://blog.truesec.com/2021/08/05/from-stranger-to-da-using-petitpotam-to-ntlm-relay-to-active-directory/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210831 | 我是如何捡到Jetty CVE的 | https://mp.weixin.qq.com/s/Uj-gwD2QNer-6CnyR9DW7A| 
| 20210831 | 中央集采安全软件列表及报价 | https://mp.weixin.qq.com/s/Yni5Yw6SOLOJEvRbiSSRVg| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210831T10:50:50Z | CVE-2021-3490 | Null | https://github.com/chompie1337/Linux_LPE_eBPF_CVE-2021-3490 | The eBPF ALU32 bounds tracking for bitwise ops (AND, OR and XOR) in the Linux kernel did not properly update 32-bit bounds, which could be turned into out of bounds reads and writes in the Linux kernel and therefore, arbitrary code execution. This issue was fixed via commit 049c4e13714e (%bpf: Fix alu32 const subreg bound tracking on bitwise operations%) (v5.13-rc4) and backported to the stable kernels in v5.12.4, v5.11.21, and v5.10.37. The AND/OR issues were introduced by commit 3f50f132d840 (%bpf: Verifier, do explicit ALU32 bounds tracking%) (5.7-rc1) and the XOR variant was introduced by 2921c90d4718 (%bpf:Fix a verifier failure with xor%) ( 5.10-rc1).| 
| 20210831T06:30:30Z | CVE-2021-32804 | Null | https://github.com/yamory/CVE-2021-32804 | The npm package %tar% (aka node-tar) before versions 6.1.1, 5.0.6, 4.4.14, and 3.3.2 has a arbitrary File Creation/Overwrite vulnerability due to insufficient absolute path sanitization. node-tar aims to prevent extraction of absolute file paths by turning absolute paths into relative paths when the `preservePaths` flag is not set to `true`. This is achieved by stripping the absolute path root from any absolute file paths contained in a tar file. For example `/home/user/.bashrc` would turn into `home/user/.bashrc`. This logic was insufficient when file paths contained repeated path roots such as `////home/user/.bashrc`. `node-tar` would only strip a single path root from such paths. When given an absolute file path with repeating path roots, the resulting path (e.g. `///home/user/.bashrc`) would still resolve to an absolute path, thus allowing arbitrary file creation and overwrite. This issue was addressed in releases 3.2.2, 4.4.14, 5.0.6 and 6.1.1. Users may work around this vulnerability without upgrading by creating a custom `onentry` method which sanitizes the `entry.path` or a `filter` method which removes entries with absolute paths. See referenced GitHub Advisory for details. Be aware of CVE-2021-32803 which fixes a similar bug in later versions of tar.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210831T12:26:44Z | Backend application for running static analysis of rust-based programs | https://github.com/LedgerProject/safepkt_backend | 0 | 1| 
| 20210831T12:25:34Z | Web application for running static analysis of rust-based programs | https://github.com/LedgerProject/safepkt | 0 | 1| 
| 20210831T10:38:19Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2689 | 68| 
| 20210831T00:05:01Z | Null | https://github.com/kleelab/kleelab.github.io | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210831T12:52:31Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 22 | 14| 
| 20210831T12:51:31Z | Auto IP range scanner & exploit tool for BlueKeep metasploit module | https://github.com/ind3p3nd3nt/BlueRDPSploit | 13 | 8| 
| 20210831T12:47:28Z | Null | https://github.com/7ten7/WorkflowServiceXml-Exploit | 0 | 0| 
| 20210831T12:35:12Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9956 | 1665| 
| 20210831T12:26:44Z | OpenNetAdmin 18.1.1 - Exploit - Remote Code Execution | https://github.com/d4t4s3c/OpenNetAdmin18.1.1RCE | 6 | 2| 
| 20210831T12:19:29Z | Exploiting Pokemon API | https://github.com/macklark/Pokemon-pod | 0 | 0| 
| 20210831T12:09:27Z | Simple Roblox Exploit Using WRD API | https://github.com/Sorted1/ArchSploit | 0 | 0| 
| 20210831T12:03:22Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 29 | 15| 
| 20210831T11:46:46Z | Null | https://github.com/VictorSuraj/php-exploit | 1 | 0| 
| 20210831T11:31:51Z | Bug fixes for the Exploit-DB | https://github.com/Re4son/exploitdb-ng | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210831T11:25:50Z | Simple PHP backdoor | https://github.com/afrzlfa/Simple-PHP-Backdoor | 0 | 0| 
| 20210831T09:48:08Z | This is an advanced backdoor, created with Python | https://github.com/NoamHarush/Backdoor | 0 | 0| 
| 20210831T09:26:15Z | Unofficial pytorch implementation of RobNet(Defense-Resistant Backdoor Attacks on DNN) | https://github.com/dhkim2810/RobNet | 0 | 0| 
| 20210831T08:52:29Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 292 | 55| 
| 20210831T06:39:09Z | Null | https://github.com/henil0604/backdoor-boiler | 0 | 0| 
| 20210831T05:29:39Z | Bilingual PhishingKit. TigerShark intergrates a vast array of various phishing tools and frameworks, from C2 servers, backdoors and delivery methods in multiple scripting languages in order to suit whatever your deployment needs may be. | https://github.com/s1l3nt78/TigerShark | 289 | 46| 
| 20210831T05:29:04Z | A simple remote tool written in C#.    一个简单的c#远控 | https://github.com/qwqdanchun/DcRat | 338 | 124| 
| 20210831T05:06:54Z | Null | https://github.com/nourdemille/backdoor | 0 | 0| 
| 20210831T02:32:07Z | Simples Backdoor Camuflada em um Programa. | https://github.com/KnC0x00/BackdoorSUID | 1 | 0| 
| 20210831T01:05:48Z | Ethical Remote Acces Tool Client and Server for W10 and Linux Persist functionality | https://github.com/PolGs/Persistent-Backdoor | 4 | 2| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210831T11:29:02Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2438 | 362| 
| 20210831T10:10:30Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 157 | 34| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210831T12:49:56Z | java coding exercises | https://github.com/jeortizquan/fuzzy-octo-sniffle | 0 | 0| 
| 20210831T12:33:14Z | CRLF and open redirect fuzzer | https://github.com/BountyStrike/Injectus | 79 | 24| 
| 20210831T12:21:15Z | Contains mathematica code for solving SP eqn | https://github.com/devarshee97/Vector-Fuzzy-Dark-matter | 0 | 0| 
| 20210831T12:12:58Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6592 | 1349| 
| 20210831T12:03:15Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210831T11:59:48Z | Null | https://github.com/joshdianz/fuzzy-engine | 0 | 0| 
| 20210831T11:51:41Z | Rapid fuzzy string matching in Python using various string metrics | https://github.com/maxbachmann/RapidFuzz | 1035 | 46| 
| 20210831T11:05:34Z | IDOR bypass fuzz 权限绕过burp 插件 fuzz （shiro 等） | https://github.com/guguyu1/IDOR-bypass-fuzz | 8 | 1| 
| 20210831T10:57:35Z | Null | https://github.com/Kanzuzbwu/fuzzy-giggle | 0 | 0| 
| 20210831T10:57:18Z | Null | https://github.com/nhsd-exeter/dos-service-fuzzy-search-api | 1 | 0| 



# 日更新程序
