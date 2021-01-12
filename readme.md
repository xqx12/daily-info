# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210111 | An Outlook parasite for stealth persistence | https://vanmieghem.io/stealth-outlook-persistence/| 
| 20210111 | Parent Process vs. Creator Process - Windows 进程父子关系分析 | https://scorpiosoftware.net/2021/01/10/parent-process-vs-creator-process/| 
| 20210111 | Display Miniport Hooking | https://aviadshamriz.medium.com/part-2-display-miniport-hooking-e1a54661d2e1| 
| 20210111 | Chi Zhou 在 RealWordCTF 的议题“See No Eval: Runtime Dynamic Code Execution in Objective-C” | https://speakerdeck.com/chichou/see-no-eval-runtime-dynamic-code-execution-in-objective-c| 
| 20210111 | OSR’s Code-Level ExAllocatePoolZero Mitigation | https://www.osr.com/blog/2021/01/07/mitigations-exallocatepoolzero-security-vulnerability/| 
| 20210111 | VB2020 localhost 会议的视频公开了 | https://www.youtube.com/playlist?list=PLffioUnqXWkdzWcZXH-bzPVgcs2R4r7iS| 
| 20210111 | 从分析 C&C 流量模型的角度检测恶意软件 | https://marcoramilli.com/2021/01/09/c2-traffic-patterns-personal-notes/| 
| 20210111 | Google Chrome V8 CVE-2020-15999 字体加载堆溢出漏洞的利用过程 | https://starlabs.sg/blog/2021/01/chrome-1-day-hunting-uncovering-and-exploiting-cve-2020-15999/| 
| 20210111 | EMOTET：通过电子邮件传播方式对其溯源。 | https://github.com/cecio/EMOTET-2020-Reversing| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210111 | 组策略限制3389登录的绕过方式 | https://mp.weixin.qq.com/s/4eDNmiiXp7afLKdYzHeb3Q| 
| 20210111 | SecWiki周刊（第358期) | https://www.sec-wiki.com/weekly/358| 
| 20210111 | 拯救圣诞世界 | https://www.sec-in.com/article/766| 
| 20210111 | G.O.S.S.I.P 安全学术会议排行榜（2020版） | https://feysh.com/ranking/2020/| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210111T20:53:19Z | cve-2020-16012 | PoC for CVE-2020-16012, a timing side channel in drawImage in Firefox & Chrome | https://github.com/aleksejspopovs/cve-2020-16012 | 未查询到CVE信息| 
| 20210111T20:46:48Z | CVE-2020-36179 | CVE-2020-36179~82  Jackson-databind SSRF&RCE | https://github.com/Al1ex/CVE-2020-36179 | FasterXML jackson-databind 2.x before 2.9.10.8 mishandles the interaction between serialization gadgets and typing, related to oadd.org.apache.commons.dbcp.cpdsadapter.DriverAdapterCPDS.| 
| 20210111T19:37:48Z | CVE-2020-7048 | Null | https://github.com/ElmouradiAmine/CVE-2020-7048 | The WordPress plugin, WP Database Reset through 3.1, contains a flaw that allowed any unauthenticated user to reset any table in the database to the initial WordPress set-up state (deleting all site content stored in that table), as demonstrated by a wp-admin/admin-post.php?db-reset-tables[]=comments URI.| 
| 20210111T18:50:46Z | CVE-2020-3452 | CISCO CVE-2020-3452 Scanner & Exploiter | https://github.com/darklotuskdb/CISCO-CVE-2020-3452-Scanner-Exploiter | A vulnerability in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct directory traversal attacks and read sensitive files on a targeted system. The vulnerability is due to a lack of proper input validation of URLs in HTTP requests processed by an affected device. An attacker could exploit this vulnerability by sending a crafted HTTP request containing directory traversal character sequences to an affected device. A successful exploit could allow the attacker to view arbitrary files within the web services file system on the targeted device. The web services file system is enabled when the affected device is configured with either WebVPN or AnyConnect features. This vulnerability cannot be used to obtain access to ASA or FTD system files or underlying operating system (OS) files.| 
| 20210111T09:18:48Z | CVE-2020-11851 | Remote Code Execution vulnerability on ArcSight Logger | https://github.com/ch1nghz/CVE-2020-11851 | Arbitrary code execution vulnerability on Micro Focus ArcSight Logger product, affecting all version prior to 7.1.1. The vulnerability could be remotely exploited resulting in the execution of arbitrary code.| 
| 20210111T08:44:50Z | CVE-2021-3019 | CVE-2021-3019 lanproxy目录遍历任意文件读取漏洞探测POC | https://github.com/FanqXu/CVE-2021-3019 | ffay lanproxy 0.1 allows Directory Traversal to read /../conf/config.properties to obtain credentials for a connection to the intranet.| 
| 20210111T08:05:53Z | CVE-2020-36184 | CVE-2020-36184 && Jackson-databind  RCE | https://github.com/Al1ex/CVE-2020-36184 | FasterXML jackson-databind 2.x before 2.9.10.8 mishandles the interaction between serialization gadgets and typing, related to org.apache.tomcat.dbcp.dbcp2.datasources.PerUserPoolDataSource.| 
| 20210111T04:58:17Z | CVE-2020-0796 | local exploit | https://github.com/alexa872/CVE-2020-0796 | A remote code execution vulnerability exists in the way that the Microsoft Server Message Block 3.1.1 (SMBv3) protocol handles certain requests, aka %Windows SMBv3 Client/Server Remote Code Execution Vulnerability%.| 
| 20210111T04:37:45Z | CVE-2020-17519 | CVE-2020-17519 | https://github.com/hoanx4/CVE-2020-17519 | A change introduced in Apache Flink 1.11.0 (and released in 1.11.1 and 1.11.2 as well) allows attackers to read any file on the local filesystem of the JobManager through the REST interface of the JobManager process. Access is restricted to files accessible by the JobManager process. All users should upgrade to Flink 1.11.3 or 1.12.0 if their Flink instance(s) are exposed. The issue was fixed in commit b561010b0ee741543c3953306037f00d7a9f0801 from apache/flink:master.| 
| 20210111T02:11:51Z | CVE-2021-1056 | PoC for CVE-2021-1056 | https://github.com/pokerfaceSad/CVE-2021-1056 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210111T09:21:40Z | Null | https://github.com/markhakansson/klee-tutorial | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210111T14:49:47Z | Convert geojson to s2 region cells in different levels | https://github.com/ponlawat-w/uji_mt-s2encoding | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210111T23:40:09Z | Various ASM, C and C++ tools, shellcodes and exploit experiments. | https://github.com/forrest-orr/ExploitDev | 30 | 2| 
| 20210111T23:19:40Z | Thi powershell script has got to run in remote windows host, even for pivoting | https://github.com/FabioDefilippo/winallenum | 0 | 1| 
| 20210111T22:56:14Z | This repository will feature my scripts, research and documentation on Pokémon engines, glitches and exploits. | https://github.com/RETIREglitch/Pokemon-Research | 2 | 3| 
| 20210111T22:31:22Z | Sécurité des logiciels et exploitation de vulnérabilités | https://github.com/ppepos/inf600c | 2 | 0| 
| 20210111T22:23:19Z | Null | https://github.com/zer0exp/exploits | 0 | 0| 
| 20210111T22:00:24Z | A series of CTF/hacking challenge solutions for binary exploitation(or pwn)/reverse engineering/vulnerability research/memory corruption(or whatever term you use) | https://github.com/docfate111/binary-exploitation-solution-scripts | 0 | 0| 
| 20210111T21:54:14Z | Vulnerabilities% Risk of Exploitation | https://github.com/thiagofigcosta/V-REx | 0 | 0| 
| 20210111T21:38:39Z | a fixed version of this dudes shitty ass remote spy designed to work for sentinel, protosmasher & some free exploits | https://github.com/CoochieSlayer6372/SimpleSpyFixed | 0 | 0| 
| 20210111T21:22:18Z | This website chronicles the exploits of a fledgling indie developer as well as serving as his online resume and portfolio. Topics covered include, but are not limited to Game Development, Programming, 3D Modeling, Computer Graphics, and all visual or audible art in general! | https://github.com/tetrachord-dev/tetrachord-dev.github.io | 0 | 0| 
| 20210111T21:14:44Z | Open-Sourced Free Exploit | https://github.com/OpenGamerTips/Xenon | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210111T23:10:55Z | TheGremlinLinuxBackdoor Project, still in making do not use for now ! | https://github.com/k0rup710n/GremlinLinux-Backdoor | 0 | 0| 
| 20210111T21:40:26Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 28 | 5| 
| 20210111T21:13:07Z | Null | https://github.com/MadsKaiser/backdoor | 0 | 0| 
| 20210111T20:15:51Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 162 | 30| 
| 20210111T18:32:31Z | Hides the sethc.exe backdoor by faking the original window. | https://github.com/PGgamer2/sethc-backdoor-hider | 1 | 3| 
| 20210111T15:00:45Z | Simple remote administration tool | https://github.com/Monst3red/Backdoor | 0 | 0| 
| 20210111T13:47:46Z | TCP server + Web app for managing active backdoors | https://github.com/hacefresko/Mothership | 0 | 0| 
| 20210111T13:20:47Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 144 | 21| 
| 20210111T10:25:42Z | Enter the club from the backdoor | https://github.com/ClementWalter/leparisien-abo | 0 | 0| 
| 20210111T06:34:59Z | Analysis of SunBurst (SolarWinds) embedded backdoor | https://github.com/conikeec/sunburst-analysis | 1 | 1| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210111T23:51:09Z | Null | https://github.com/aminelch/fuzzy-enigma | 0 | 0| 
| 20210111T23:23:43Z | Windows USB drivers fuzzing using UDE technology | https://github.com/0x123456789/UDEFuzz | 1 | 0| 
| 20210111T23:07:39Z | The Art, Science, and Engineering of Fuzzing: A Survey | https://github.com/SoftSec-KAIST/Fuzzing-Survey | 112 | 15| 
| 20210111T23:07:04Z | Null | https://github.com/sebalesraim/FuzzyNetworkFeat | 0 | 0| 
| 20210111T22:49:46Z | FuzzBench - Fuzzer benchmarking as a service. | https://github.com/google/fuzzbench | 578 | 92| 
| 20210111T22:48:47Z | FormatFuzzer is a framework for high-efficiency, high-quality generation and parsing of binary inputs. | https://github.com/uds-se/FormatFuzzer | 115 | 12| 
| 20210111T22:04:33Z | Code for fuzzy Dark matter research, mainly visualization but some manipulation too | https://github.com/LaurelinTheGold/fuzzyDM | 0 | 0| 
| 20210111T21:55:34Z | implementation of a tiny fuzzy clasifier | https://github.com/AlmuHS/FuzzyClasifier_Exercise | 1 | 2| 
| 20210111T21:43:13Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2244 | 113| 
| 20210111T21:28:32Z | Null | https://github.com/fragment137/fuzzy-enigma | 0 | 0| 



# 日更新程序
