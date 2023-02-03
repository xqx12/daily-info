# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230202 | MYSQL JDBC反序列化攻击介绍 | https://tttang.com/archive/1877/| 
| 20230202 | Dompdf的URI验证可通过字母大写进行绕过，导致漏洞产生 | http://securityonline.info/cve-2023-23924-critical-severity-rce-flaw-found-in-popular-dompdf-library/| 
| 20230202 | Cisco系列产品中出现高危漏洞。CVE-2023-20076：远程命令注入，需要身份认证；CSCwc67015：任意文件写，可导致代码执行。 | https://www.darkreading.com/ics-ot/command-injection-bug-cisco-industrial-gear-devices-complete-takeover| 
| 20230202 | Mimikatz Bypass Credential Guard的记录 | https://xz.aliyun.com/t/12097| 
| 20230202 | 红队入门级介绍，利用 Crackmapexec 和 mimikatz 绕过 LSA 进行Windows 域渗透，建议和文中提到的“上一篇博客”一起阅读 | https://infosecwriteups.com/unlocking-the-secrets-of-lsa-5bd29d5c6927?gi=069b8f50c100&source=rss----7b722bfd1b8d---4| 
| 20230202 | Adobe Acrobat Reader UAF漏洞（CVE-2023-21608）利用代码 | https://github.com/hacksysteam/CVE-2023-21608| 
| 20230201 | 使用ipatables命令对Android应用抓包分析。 | https://mp.weixin.qq.com/s/P0ESUUXBmq2aQnrqDHsDaw| 
| 20230201 | Dell dbutil_2_3.sys 驱动提权漏洞的exp | https://github.com/nanabingies/CVE-2021-21551| 
| 20230201 | WordPress漏洞整理 | http://sucur.it/3JxrIl4| 
| 20230201 | 一款X64二进制混淆工具，介绍了一些二进制混淆的方法和原理 | http://securityonline.info/alcatraz-x64-binary-obfuscator/| 
| 20230201 | Firebird Internal CTF 2023 Writeup | http://mystiz.hk/posts/2023/2023-01-30-firebird-internal-ctf/| 
| 20230201 | OSS-Fuzz后续研究计划，将从提升贡献者奖金、增加更多语言Fuzz支持、FuzzIntrospector支持等方面进行改进。 | https://security.googleblog.com/2023/02/taking-next-step-oss-fuzz-in-2023.html?m=1| 
| 20230201 | F5 BIG-IP的blind format string漏洞，可导致服务崩溃甚至RCE | https://www.rapid7.com/blog/post/2023/02/01/cve-2023-22374-f5-big-ip-format-string-vulnerability/| 
| 20230201 | 网络安全研究人员披露了开源 ImageMagick 中两个安全漏洞的细节，这些漏洞可能导致拒绝服务（DoS）和信息泄露。 | https://thehackernews.com/2023/02/researchers-uncover-new-bugs-in-popular.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230201 | 九阶段太空攻击研究与战术分析框架和七层美国防太空架构 | https://mp.weixin.qq.com/s/TvEZKKzyRyb1_jVU1YeEMg| 
| 20230201 | 2022年度APT高级威胁报告 | https://book.yunzhan365.com/tkgd/ftku/mobile/index.html| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230203T02:06:16Z | CVE-2023-0634 | An uncontrolled process operation was found in the newgrp command provided by the shadow-utils package. This issue could cause the execution of arbitrary code provided by a user when running the newgrp command. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0634 | | 
| 20230203T02:06:10Z | CVE-2023-0658 | A vulnerability, which was classified as critical, was found in Multilaser RE057 and RE170 2.1/2.2. This affects an unknown part of the file /param.file.tgz of the component Backup File Handler. The manipulation leads to information disclosure. It is possible to initiate the attack remotely. The identifier VDB-220053 w CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0658 | | 
| 20230203T02:06:06Z | CVE-2022-38389 | IBM Tivoli Workload Scheduler 9.4, 9.5, and 10.1 is vulnerable to an XML External Entity Injection (XXE) attack when processing XML data. A remote attacker could exploit this vulnerability to expose sensitive information or consume memory resources. IBM X-Force ID: 233975. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-38389 | | 
| 20230203T02:06:03Z | CVE-2022-22486 | IBM Tivoli Workload Scheduler 9.4, 9.5, and 10.1 is vulnerable to an XML External Entity Injection (XXE) attack when processing XML data. A remote attacker could exploit this vulnerability to expose sensitive information or consume memory resources. IBM X-Force ID: 226328. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-22486 | | 
| 20230202T23:55:13Z | CVE-2022-48114 | RuoYi up to v4.7.5 was discovered to contain a SQL injection vulnerability via the component /tool/gen/createTable. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-48114 | | 
| 20230202T23:55:10Z | CVE-2022-48113 | A vulnerability in TOTOLINK N200RE_v5 firmware V9.3.5u.6139 allows unauthenticated attackers to access the telnet service via a crafted POST request. Attackers are also able to leverage this vulnerability to login as root via hardcoded credentials. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-48113 | | 
| 20230202T23:55:06Z | CVE-2020-15654 | When in an endless loop, a website specifying a custom cursor using CSS could make it look like the user is interacting with the user interface, when they are not. This could lead to a perceived broken state, especially when interactions with existing browser dialogs and warnings do not work. This vulnerability affects CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-15654 | | 
| 20230202T23:55:03Z | CVE-2020-15653 | An iframe sandbox element with the allow-popups flag could be bypassed when using noopener links. This could have led to security issues for websites relying on sandbox configurations that allowed popups and hosted arbitrary content. This vulnerability affects Firefox ESR < 78.1, Firefox < 79, and Thunderbird < 78.1. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-15653 | | 
| 20230202T23:54:59Z | CVE-2020-15656 | JIT optimizations involving the Javascript arguments object could confuse later optimizations. This risk was already mitigated by various precautions in the code, resulting in this bug rated at only moderate severity. This vulnerability affects Firefox ESR < 78.1, Firefox < 79, and Thunderbird < 78.1. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-15656 | | 
| 20230202T23:54:48Z | CVE-2020-29396 | A sandboxing issue in Odoo Community 11.0 through 13.0 and Odoo Enterprise 11.0 through 13.0, when running with Python 3.6 or later, allows remote authenticated users to execute arbitrary code, leading to privilege escalation. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-29396 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T01:31:43Z | Null | https://github.com/LuiKlee/LuiKlee.github.io | 0 | 0| 
| 20230202T19:25:20Z | ⬇️ File Upload/sharing application, used by thousands of webmasters since 2007.  | https://github.com/kleeja-official/kleeja | 169 | 50| 
| 20230202T10:48:24Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 16 | 51| 
| 20230202T08:56:49Z | Collection of Kicad 6.0 symbols, footprints and 3D models useful in keyboard creation | https://github.com/crides/kleeb | 72 | 6| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230202T13:38:52Z | Spacecraft Simulation Environment Core codes | https://github.com/ut-issl/s2e-core | 26 | 8| 
| 20230201T13:08:21Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 293 | 73| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T02:06:06Z | IBM Tivoli Workload Scheduler 9.4, 9.5, and 10.1 is vulnerable to an XML External Entity Injection (XXE) attack when processing XML data. A remote attacker could exploit this vulnerability to expose sensitive information or consume memory resources. IBM X-Force ID: 233975. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-38389 | 0 | 0| 
| 20230203T02:06:03Z | IBM Tivoli Workload Scheduler 9.4, 9.5, and 10.1 is vulnerable to an XML External Entity Injection (XXE) attack when processing XML data. A remote attacker could exploit this vulnerability to expose sensitive information or consume memory resources. IBM X-Force ID: 226328. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-22486 | 0 | 0| 
| 20230203T00:40:13Z | A Security Assessment Report for a website%s source code and database with an exploit. | https://github.com/odd509/Security-Assessment-Report | 0 | 0| 
| 20230202T23:55:56Z | An exploitable use-after-free vulnerability exists in the JavaScript engine of Foxit Software%s Foxit PDF Reader version 9.2.0.9297. A specially crafted PDF document can trigger a previously freed object in memory to be reused, resulting in arbitrary code execution. An attacker needs to trick the user to open the malic CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2018-3993 | 0 | 0| 
| 20230202T23:55:53Z | An exploitable use-after-free vulnerability exists in the JavaScript engine of Foxit Software%s PDF Reader, version 9.2.0.9297. A specially crafted PDF document can trigger a previously freed object in memory to be reused, resulting in arbitrary code execution. An attacker needs to trick the user to open the malicious  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2018-3995 | 0 | 0| 
| 20230202T23:55:49Z | An exploitable use-after-free vulnerability exists in the JavaScript engine of Foxit Software%s Foxit PDF Reader version 9.2.0.9297. A specially crafted PDF document can trigger a previously freed object in memory to be reused, resulting in arbitrary code execution. An attacker needs to trick the user to open the malic CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2018-3994 | 0 | 0| 
| 20230202T23:55:46Z | An exploitable use-after-free vulnerability exists in the JavaScript engine of Foxit Software%s PDF Reader, version 9.2.0.9297. A specially crafted PDF document can trigger a previously freed object in memory to be reused, resulting in arbitrary code execution. An attacker needs to trick the user to open the malicious  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2018-3996 | 0 | 0| 
| 20230202T23:55:42Z | An exploitable use-after-free vulnerability exists in the JavaScript engine of Foxit Software%s PDF Reader version 9.1.0.5096. A specially crafted PDF document can trigger a previously freed object in memory to be reused, resulting in arbitrary code execution. An attacker needs to trick the user to open the malicious f CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2018-3946 | 0 | 0| 
| 20230202T23:55:38Z | An exploitable use-after-free vulnerability exists in the JavaScript engine of Foxit Software%s Foxit PDF Reader version 9.1.0.5096. A specially crafted PDF document can trigger a previously freed object in memory to be reused, resulting in arbitrary code execution. An attacker needs to trick the user to open the malic CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2018-3945 | 0 | 0| 
| 20230202T23:55:35Z | An exploitable use-after-free vulnerability exists in the JavaScript engine of Foxit Software%s PDF Reader, version 9.1.0.5096. A specially crafted PDF document can trigger a previously freed object in memory to be reused, resulting in arbitrary code execution. An attacker needs to trick the user to open the malicious  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2018-3943 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230202T23:27:42Z | Ferramenta que Mescla Backdoor Metasploit em Apps Android | https://github.com/Cyber-Root0/JoinePayload | 1 | 0| 
| 20230202T23:04:26Z | Null | https://github.com/rama1277/shell-backdoor-rama | 0 | 0| 
| 20230202T18:05:33Z | FLIP: A Provable Defense Framework for Backdoor Mitigation in Federated Learning (ICLR 2023) | https://github.com/KaiyuanZh/FLIP | 2 | 0| 
| 20230202T17:54:14Z | client-server-nat | https://github.com/LIBERTY-D/backdoor | 0 | 0| 
| 20230202T13:36:49Z | A Python based Backdoor for Windows | https://github.com/BeastCodZ/Backdoor | 0 | 0| 
| 20230202T09:44:30Z | A shell script that mimics sudo and sends you back the password | https://github.com/nisay759/sudo-backdoor | 15 | 7| 
| 20230202T09:11:06Z | /root/.ssh/authorized_keys evil file watchdog with ebpf tracepoint hook. | https://github.com/Esonhugh/sshd_backdoor | 233 | 24| 
| 20230202T07:49:35Z | Null | https://github.com/isha1701/ReverseBackdoor | 4 | 0| 
| 20230202T07:45:02Z | This has been fixed backdoor  | https://github.com/MallisC5/L4-POWERFULL-CAN-BYPASS-OVH | 0 | 0| 
| 20230202T06:52:14Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 198 | 52| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230202T19:56:19Z | Null | https://github.com/data-storage-lab/Symbolic-Execution | 1 | 0| 
| 20230202T09:25:05Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 617 | 111| 
| 20230202T06:37:05Z | A C# analyzer which performs symbolic execution on users% code | https://github.com/twoltjer/SymbolicExecutionAnalyzer | 1 | 0| 
| 20230201T13:08:21Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 293 | 73| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T02:36:05Z | REcollapse is a helper tool for black-box regex fuzzing to bypass validations and discover normalizations in web applications | https://github.com/0xacb/recollapse | 385 | 32| 
| 20230203T02:23:54Z | Fuzz Introspector -- introspect, extend and optimise fuzzers | https://github.com/ossf/fuzz-introspector | 237 | 34| 
| 20230203T02:21:26Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8322 | 1813| 
| 20230203T00:32:46Z | Null | https://github.com/data-storage-lab/Fuzzing | 0 | 0| 
| 20230203T00:25:23Z | Null | https://github.com/alissaleigh/fuzzy-spoon | 0 | 0| 
| 20230203T00:14:18Z | Official repository  vuls Scan: 15000+PoCs; 23 kinds of application password crack; 7000+Web fingerprints; 146 protocols and 90000+ rules Port scanning; Fuzz, HW, awesome BugBounty( ͡° ͜ʖ ͡°)... | https://github.com/hktalent/scan4all | 3390 | 407| 
| 20230202T23:11:36Z | Null | https://github.com/HauHuynh90/fuzzy-chainsaw-november | 0 | 0| 
| 20230202T22:47:00Z | DA/DS projects | https://github.com/Rouss57/fuzzy-giggle | 0 | 0| 
| 20230202T22:43:44Z | Web-Fuzzer made in python | https://github.com/1momo7/m1-Fuzzer | 0 | 0| 
| 20230202T22:20:55Z | Null | https://github.com/gjf2a/fuzzy_demo | 0 | 0| 



# 日更新程序
