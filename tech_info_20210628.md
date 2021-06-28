# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210628 | HITB 会议一篇关于 5G 安全的议题 “5G Networks and Interconnect Threats” | https://conference.hitb.org/hitbsecconf2021ams/materials/D2%20COMMSEC%20-%205G%20Networks%20and%20Interconnect%20Threats%20-%20Martin%20Kacer.pdf| 
| 20210628 | Low Level PC/Server Attack & Defense | https://darkmentor.com/timeline.html| 
| 20210628 | Developers Under Attack - 检测攻击者利用包名 “Typosquatting” 问题挖矿的行为 | https://www.vdoo.com/blog/leveraging-typosquatting-crypto-mining/| 
| 20210628 | MODeflattener - 用于处理 “Control Flow Flattenning” 的反混淆工具 | https://mrt4ntr4.github.io/MODeflattener/| 
| 20210628 | iOS CVE-2021-1757、AppleH10CamIn OOB Write 两个内核漏洞的 PoC | https://github.com/b1n4r1b01/n-days| 
| 20210628 | 2021 年上半年全球勒索软件趋势报告 | https://ti.dbappsecurity.com.cn/blog/articles/2021/06/25/2021-half-year-ramsomware/| 
| 20210628 | CVE-2021-31955 Windows 内核信息泄露漏洞 PoC | https://github.com/mavillon1/CVE-2021-31955-POC| 
| 20210628 | Blocking Remote Memory Forensics Like An EDR | https://passthehashbrowns.github.io/blocking-remote-memory-forensics/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210628 | SecWiki周刊（第382期) | https://www.sec-wiki.com/weekly/382| 
| 20210628 | 如何使用 VirusTotal 狩猎恶意软件 | https://mp.weixin.qq.com/s/JtnHqNx5PSER8WgpZS3Vag| 
| 20210628 | 法律视角解读首个打击虚拟货币交易的司法文件 | https://www.chainnews.com/articles/003119950198.htm| 
| 20210628 | 基于人工智能的网络空间安全防御战略研究 | http://www.engineering.org.cn/ch/10.15302/J-SSCAE-2021.03.003| 
| 20210628 | 利用PHAR协议进行PHP反序列化攻击 | https://mp.weixin.qq.com/s/w2wUl_9BjAaqhbVJTGxRjA| 
| 20210628 | D3FEND网络安全对策知识图谱 | https://mp.weixin.qq.com/s/jgN5PjzFEc9Hy3TvA6Nmvw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210628T09:59:37Z | CVE-2020-3580 | Null | https://github.com/Hudi233/CVE-2020-3580 | Multiple vulnerabilities in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct cross-site scripting (XSS) attacks against a user of the web services interface of an affected device. The vulnerabilities are due to insufficient validation of user-supplied input by the web services interface of an affected device. An attacker could exploit these vulnerabilities by persuading a user of the interface to click a crafted link. A successful exploit could allow the attacker to execute arbitrary script code in the context of the interface or allow the attacker to access sensitive, browser-based information. Note: These vulnerabilities affect only specific AnyConnect and WebVPN configurations. For more information, see the Vulnerable Products section.| 
| 20210628T09:57:42Z | CVE-2021-32537 | PoC for CVE-2021-32537: an out-of-bounds memory access that leads to pool corruption in the Windows kernel. | https://github.com/0vercl0k/CVE-2021-32537 | 未查询到CVE信息| 
| 20210628T09:23:32Z | CVE-2021-31955 | Null | https://github.com/mavillon1/CVE-2021-31955-POC | Windows Kernel Information Disclosure Vulnerability| 
| 20210628T08:16:39Z | CVE-2021-27850 | A Proof of concept for CVE-2021-27850 affecting Apache Tapestry and leading to unauthencticated remote code execution. | https://github.com/kahla-sec/CVE-2021-27850_POC | A critical unauthenticated remote code execution vulnerability was found all recent versions of Apache Tapestry. The affected versions include 5.4.5, 5.5.0, 5.6.2 and 5.7.0. The vulnerability I have found is a bypass of the fix for CVE-2019-0195. Recap: Before the fix of CVE-2019-0195 it was possible to download arbitrary class files from the classpath by providing a crafted asset file URL. An attacker was able to download the file `AppModule.class` by requesting the URL `http://localhost:8080/assets/something/services/AppModule.class` which contains a HMAC secret key. The fix for that bug was a blacklist filter that checks if the URL ends with `.class`, `.properties` or `.xml`. Bypass: Unfortunately, the blacklist solution can simply be bypassed by appending a `/` at the end of the URL: `http://localhost:8080/assets/something/services/AppModule.class/` The slash is stripped after the blacklist check and the file `AppModule.class` is loaded into the response. This class usually contains the HMAC secret key which is used to sign serialized Java objects. With the knowledge of that key an attacker can sign a Java gadget chain that leads to RCE (e.g. CommonsBeanUtils1 from ysoserial). Solution for this vulnerability: * For Apache Tapestry 5.4.0 to 5.6.1, upgrade to 5.6.2 or later. * For Apache Tapestry 5.7.0, upgrade to 5.7.1 or later.| 
| 20210628T08:15:06Z | CVE-2020-27368 | TOTOLINK-A702R-V1.0.0-B20161227.1023 Directory Indexing Vulnerability | https://github.com/swzhouu/CVE-2020-27368 | Directory Indexing in Login Portal of Login Portal of TOTOLINK-A702R-V1.0.0-B20161227.1023 allows attacker to access /icons/ directories via GET Parameter.| 
| 20210628T01:34:34Z | CVE-2021-23383 | Check the conditions for exploiting CVE-2021-23383 through the handlebars library version assessment. | https://github.com/dn9uy3n/Check-CVE-2021-23383 | The package handlebars before 4.7.7 are vulnerable to Prototype Pollution when selecting certain compiling options to compile templates coming from an untrusted source.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210628T12:29:06Z | Null | https://github.com/kleelab/kleelab.github.io | 0 | 0| 
| 20210628T11:43:45Z | Null | https://github.com/thierry-tct/KLEE-SEMu | 3 | 2| 
| 20210628T05:46:21Z | About Klee | https://github.com/Snowable-GA/Genshin_Impact-Klee | 0 | 0| 
| 20210628T01:14:23Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 15 | 45| 
| 20210628T01:13:41Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1723 | 495| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210628T05:36:01Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 137 | 32| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210628T12:25:19Z | exploit Huawei ONT device | https://github.com/0neday/Exploit-HS8545M-ONT | 0 | 0| 
| 20210628T12:20:41Z | S3Exploits is a script that automates to find out the AWS misconfigured S3 buckets that can lead pentester to exposed many vulnerabilities (XSS, phishing, site deface, many more). | https://github.com/Aju100/s3-exploit | 2 | 0| 
| 20210628T12:02:56Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 25 | 12| 
| 20210628T11:29:08Z | Exploit geliştirme 101 | https://github.com/SaykQ-system/Exploit-development-101 | 0 | 0| 
| 20210628T10:55:25Z | BioCCP.jl exploits the Coupon Collector Problem for sample size determination in combinatorial biotechnology. | https://github.com/kirstvh/BioCCP | 2 | 0| 
| 20210628T10:49:48Z | Perform buffer overflow vuln testing and exploit | https://github.com/souvikhaldar/goffer | 0 | 0| 
| 20210628T10:46:18Z | Null | https://github.com/nccgroup/exploit_mitigations | 0 | 0| 
| 20210628T10:42:02Z | eXploit is designed to perform various social engineering attacks. | https://github.com/agnath18K/eXploit | 0 | 0| 
| 20210628T10:19:43Z | This repository contains hints to exploit and capture flag of  CTF machines from various platforms. this isn%t a detailed walk-through. from some boxes which I hunt. | https://github.com/nibrasmuhamed/CTF-Walkthrough | 0 | 0| 
| 20210628T09:27:55Z | Writeups, scripts and solutions for CTFs, Hack the Box, Vulnhub, exploit challenges, pwnables, crackmes, etc. Anything goes. | https://github.com/alichtman/writeups | 5 | 1| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210628T10:03:46Z | You can make reverse shells ^-^ | https://github.com/6icada/BackDoorAccess | 0 | 0| 
| 20210628T09:29:27Z | Une simple Backdoor, donnant accés à l%ensemble des fichiers d%un ordinateur. | https://github.com/billythegoat356/F0rs4k3n | 6 | 0| 
| 20210628T08:58:19Z | This is a python backdoor project. This is for educational purposes only. | https://github.com/TKLinux966/B4cKD00R | 0 | 0| 
| 20210628T07:48:33Z | kumpulan shell backdoor | https://github.com/anggixxx1/backdoor | 0 | 0| 
| 20210628T07:25:02Z | Adversarial Backdoor Attack | https://github.com/ZQ-Struggle/AdvDoor | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210628T10:04:45Z | Symbolic-execution-based verifier for the Viper intermediate verification language. | https://github.com/viperproject/silicon | 19 | 11| 
| 20210628T07:18:38Z | Use angr in Ghidra | https://github.com/Nalen98/AngryGhidra | 306 | 21| 
| 20210628T07:02:14Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 421 | 62| 
| 20210628T01:27:42Z | A symbolic execution engine for LLVM IR | https://github.com/insufficiently-caffeinated/caffeine | 7 | 4| 
| 20210628T01:13:41Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1723 | 495| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210628T12:27:27Z | Fuzz for sensitive directories without killing the host using ffuf | https://github.com/R0X4R/Fuzzy | 26 | 7| 
| 20210628T12:15:16Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 13 | 6| 
| 20210628T12:02:42Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210628T11:50:28Z | FormatFuzzer is a framework for high-efficiency, high-quality generation and parsing of binary inputs. | https://github.com/uds-se/FormatFuzzer | 133 | 13| 
| 20210628T11:19:40Z | Null | https://github.com/corootine/fuzzy | 0 | 0| 
| 20210628T10:53:51Z | Simple CI program for running fuzzing over TezEdge. | https://github.com/tezedge/fuzzing-ci | 5 | 0| 
| 20210628T10:37:02Z | An algorithm framework integrating fuzzy decision trees and fuzzy ensemble trees. | https://github.com/ZhaoqingLiu/FuzzyTrees | 0 | 0| 
| 20210628T10:06:41Z | Null | https://github.com/MTRNord/matrix-rust-sdk-fuzz-target | 0 | 0| 
| 20210628T09:53:23Z | Fuzzy Extractors in Java | https://github.com/ThexXTURBOXx/FuzzyExtractors | 1 | 0| 
| 20210628T09:41:19Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 465 | 41| 



# 日更新程序
