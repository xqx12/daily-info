# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210626T11:27:28Z | CVE-2021-35475 | Writeup for CVE-2021-35475; Stored Cross-Site Scripting(XSS) on SAS® Environment Manager 2.5 | https://github.com/saitamang/CVE-2021-35475 | SAS Environment Manager 2.5 allows XSS through the Name field when creating/editing a server. The XSS will prompt when editing the Configuration Properties.| 
| 20210626T11:25:35Z | CVE-2021-31955 | Null | https://github.com/mavillon1/CVE-2021-31955-POC | Windows Kernel Information Disclosure Vulnerability| 
| 20210626T09:44:57Z | CVE-2021-32537 | PoC for CVE-2021-32537: an out-of-bounds memory access that leads to pool corruption in the Windows kernel. | https://github.com/0vercl0k/CVE-2021-32537 | 未查询到CVE信息| 
| 20210626T09:24:14Z | CVE-2021-27850 | A Proof of concept for CVE-2021-27850 affecting Apache Tapestry and leading to unauthencticated remote code execution. | https://github.com/kahla-sec/CVE-2021-27850_POC | A critical unauthenticated remote code execution vulnerability was found all recent versions of Apache Tapestry. The affected versions include 5.4.5, 5.5.0, 5.6.2 and 5.7.0. The vulnerability I have found is a bypass of the fix for CVE-2019-0195. Recap: Before the fix of CVE-2019-0195 it was possible to download arbitrary class files from the classpath by providing a crafted asset file URL. An attacker was able to download the file `AppModule.class` by requesting the URL `http://localhost:8080/assets/something/services/AppModule.class` which contains a HMAC secret key. The fix for that bug was a blacklist filter that checks if the URL ends with `.class`, `.properties` or `.xml`. Bypass: Unfortunately, the blacklist solution can simply be bypassed by appending a `/` at the end of the URL: `http://localhost:8080/assets/something/services/AppModule.class/` The slash is stripped after the blacklist check and the file `AppModule.class` is loaded into the response. This class usually contains the HMAC secret key which is used to sign serialized Java objects. With the knowledge of that key an attacker can sign a Java gadget chain that leads to RCE (e.g. CommonsBeanUtils1 from ysoserial). Solution for this vulnerability: * For Apache Tapestry 5.4.0 to 5.6.1, upgrade to 5.6.2 or later. * For Apache Tapestry 5.7.0, upgrade to 5.7.1 or later.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T12:35:14Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9597 | 1569| 
| 20210626T12:20:02Z | exploit Huawei ONT device | https://github.com/0neday/Exploit-HS8545M-ONT | 0 | 0| 
| 20210626T12:09:47Z | SSRF search vulnerabilities exploitation extended. | https://github.com/duckstroms/ssrf-search | 12 | 3| 
| 20210626T12:02:54Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 25 | 12| 
| 20210626T11:50:17Z | Scripts (ServerSide and FE) | https://github.com/0WNEDU/Roblox-Misc-Scripts-Exploits | 0 | 0| 
| 20210626T11:18:39Z | Null | https://github.com/TheCrazzXz/Exploits-Lab | 0 | 0| 
| 20210626T10:53:31Z | Exploit distribution system for A&D competitions | https://github.com/pomo-mondreganto/neo | 1 | 1| 
| 20210626T10:20:45Z | GEF (GDB Enhanced Features) brings a modern experience for GDB with advanced debugging features for exploit developers & reverse engineers | https://github.com/hugsy/gef | 3694 | 512| 
| 20210626T10:19:55Z | A roblox server sided anti exploit capable of handling common exploits smoothly. Performance friendly, and reserves resources. The point of this anti exploit is to stop common exploits reliably with minimum performance impact, and rarely cause any false positive related problems. | https://github.com/SilentsReplacement/BoboFighter | 5 | 2| 
| 20210626T09:33:36Z | A helpful Java Deserialization exploit framework based on ysoserial | https://github.com/wh1t3p1g/ysomap | 419 | 37| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T11:36:01Z | ASP WEBSHELL BYPASS PHP SHELL BACKDOOR UNDETECTED! | https://github.com/webshell-archive/ASP | 1 | 0| 
| 20210626T11:35:46Z | PHP WEBSHELL BYPASS PHP SHELL BACKDOOR UNDETECTED! | https://github.com/webshell-archive/PHP | 1 | 0| 
| 20210626T10:02:30Z | Python backdoor | https://github.com/DianaNeumann/Porte_arriere | 0 | 0| 
| 20210626T09:59:16Z | Null | https://github.com/fmy266/Pytorch-Backdoor-Unlearning | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T08:22:56Z | Symbolic-execution-based verifier for the Viper intermediate verification language. | https://github.com/viperproject/silicon | 19 | 11| 
| 20210626T03:49:26Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2366 | 348| 
| 20210626T02:56:41Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 144 | 33| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T06:09:11Z | Original implementation of FlowPrint as in the NDSS %20 paper | https://github.com/Thijsvanede/FlowPrint | 49 | 18| 
| 20210626T02:22:29Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 15 | 2| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T12:32:31Z | This is a tool for fuzzing XSS vulnerabilities based on genetic algorithm. | https://github.com/Timofey21/darlene | 0 | 0| 
| 20210626T12:32:00Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210626T12:31:22Z | Null | https://github.com/DanielEbert/EmulatedFirmwareFuzzing | 0 | 0| 
| 20210626T12:26:56Z | This is a tool for fuzzing XSS vulnerabilities based on genetic algorithm. | https://github.com/Timofey21/GoXSSfuzz | 0 | 0| 
| 20210626T11:31:11Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210626T11:28:55Z | Null | https://github.com/AdaLogics/go-fuzz-headers | 2 | 1| 
| 20210626T09:53:40Z | DOM fuzzer | https://github.com/mevid93/domzzer | 0 | 0| 
| 20210626T09:28:43Z | Null | https://github.com/bolpuine/fuzzy-octo-palm-tree | 0 | 0| 
| 20210626T08:42:56Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6417 | 1303| 
| 20210626T08:29:19Z | Null | https://github.com/ukyouz/SublimeText-SimpleFuzzy | 0 | 0| 



# 日更新程序
