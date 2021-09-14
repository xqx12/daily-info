# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210913 | 利用 Microsoft Graph API 实现基于 Outlook 的 C&C 命令控制 | https://github.com/boku7/azureOutlookC2| 
| 20210913 | 利用 AWS 环境 IAM 的错误配置实现提权 | https://labs.bishopfox.com/tech-blog/iam-vulnerable-an-aws-iam-privilege-escalation-playground| 
| 20210913 | Cross-Account Container Takeover in Azure Container Instances | https://unit42.paloaltonetworks.com/azure-container-instances/| 
| 20210913 | 利用 WMI 机制与 Windows 注册表交互 | https://0xinfection.github.io/posts/wmi-registry-part-3/| 
| 20210913 | 近期出现野外利用的 MSHTML CVE-2021-40444 漏洞的复现及分析过程 | https://xret2pwn.github.io/CVE-2021-40444-Analysis-and-Exploit/| 
| 20210913 | Safer Usage Of C++ | https://docs.google.com/document/d/e/2PACX-1vRZr-HJcYmf2Y76DhewaiJOhRNpjGHCxliAQTBhFxzv1QTae9o8mhBmDl32CRIuaWZLt5kVeH9e9jXv/pub| 
| 20210913 | Windows DNS Server Signature RRs RCE 漏洞分析（CVE-2021-26897） | https://www.coresecurity.com/core-labs/articles/analysis-cve-2021-26897-dns-server-rce| 
| 20210913 | Fuzz ICS 工控协议 | https://dreamlab.net/en/blog/post/fuzzing-ics-protocols/| 
| 20210913 | Change home directory and bypass TCC aka CVE-2020-27937 | https://wojciechregula.blog/post/change-home-directory-and-bypass-tcc-aka-cve-2020-27937/| 
| 20210913 | 最全的逆向工程资源集合。 | https://pewpewthespells.com/blog/re.html| 
| 20210913 | 蚂蚁安全光年实验室 Usenix Security 2021 中稿论文解读. | https://paper.seebug.org/1706/| 
| 20210913 | Black Hat USA 2021 议题分享——莫比乌斯环：探索 Hyper-V 攻击面 | https://paper.seebug.org/1705/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210913 | Squid 场景绕过之一: URN bypass ACL | https://github.com/CHYbeta/OddProxyDemo/tree/master/squid/demo1| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210913T20:46:21Z | CVE-2021-40346 | Null | https://github.com/alikarimi999/CVE-2021-40346 | An integer overflow exists in HAProxy 2.0 through 2.5 in htx_add_header that can be exploited to perform an HTTP request smuggling attack, allowing an attacker to bypass all configured http-request HAProxy ACLs and possibly other ACLs.| 
| 20210913T15:29:28Z | CVE-2021-40444 | Null | https://github.com/Lagal1990/CVE-2021-40444-docx-Generate | 未查询到CVE信息| 
| 20210913T12:16:01Z | CVE-2021-40222 | Remote Code Execution at Rittal | https://github.com/asang17/CVE-2021-40222 | Rittal CMC PU III Web management Version affected: V3.11.00_2. Version fixed: V3.17.10 is affected by a remote code execution vulnerablity. It is possible to introduce shell code to create a reverse shell in the PU-Hostname field of the TCP/IP Configuration dialog. Web application fails to sanitize user input on Network TCP/IP configuration page. This allows the attacker to inject commands as root on the device which will be executed once the data is received.| 
| 20210913T12:15:32Z | CVE-2021-40223 | XSS Vulnerability in Rittal | https://github.com/asang17/CVE-2021-40223 | Rittal CMC PU III Web management (version V3.11.00_2) fails to sanitize user input on several parameters of the configuration (User Configuration dialog, Task Configuration dialog and set logging filter dialog). This allows an attacker to backdoor the device with HTML and browser-interpreted content (such as JavaScript or other client-side scripts). The XSS payload will be triggered when the user accesses some specific sections of the application.| 
| 20210913T12:14:49Z | CVE-2021-34527 | PrintNightmare - Windows Print Spooler RCE/LPE Vulnerability (CVE-2021-34527, CVE-2021-1675) proof of concept exploits | https://github.com/nemo-wq/PrintNightmare-CVE-2021-34527 | Windows Print Spooler Remote Code Execution Vulnerability| 
| 20210913T11:07:12Z | CVE-2021-24499 | Mass exploitation of CVE-2021-24499 unauthenticated upload leading to remote code execution in Workreap theme. | https://github.com/RyouYoo/CVE-2021-24499 | The Workreap WordPress theme before 2.2.2 AJAX actions workreap_award_temp_file_uploader and workreap_temp_file_uploader did not perform nonce checks, or validate that the request is from a valid user in any other way. The endpoints allowed for uploading arbitrary files to the uploads/workreap-temp directory. Uploaded files were neither sanitized nor validated, allowing an unauthenticated visitor to upload executable code such as php scripts.| 
| 20210913T09:46:04Z | CVE-2021-40444 | POC for CVE-2021-40444 | https://github.com/khoaduynu/CVE-2021-40444 | 未查询到CVE信息| 
| 20210913T09:16:55Z | CVE-2021-1234 | Null | https://github.com/sDreamForZzQ/CVE-2021-1234 | 未查询到CVE信息| 
| 20210913T09:13:55Z | CVE-2021-40346 | CVE-2021-40346 integer overflow enables http smuggling | https://github.com/donky16/CVE-2021-40346-POC | An integer overflow exists in HAProxy 2.0 through 2.5 in htx_add_header that can be exploited to perform an HTTP request smuggling attack, allowing an attacker to bypass all configured http-request HAProxy ACLs and possibly other ACLs.| 
| 20210913T05:22:28Z | CVE-2021-40845 | Null | https://github.com/ricardojoserf/CVE-2021-40845 | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210913T18:47:18Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 183 | 19| 
| 20210913T08:14:51Z | Null | https://github.com/JwayLo/klee | 0 | 0| 
| 20210913T04:30:39Z | Repositorio del proyecto Kleema | https://github.com/svelezp/Kleema | 0 | 0| 
| 20210913T00:32:52Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2754 | 74| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210913T23:59:46Z | Exploit Development and Reverse Engineering with GDB Made Easy | https://github.com/pwndbg/pwndbg | 3950 | 565| 
| 20210913T23:27:12Z | Supported: SynapseX, KRNL, ScriptWare, and other shitsploits | https://github.com/XJMI/LuaU-Scripts | 0 | 0| 
| 20210913T22:04:32Z | I found a way to exploit the rotation minecraft applies to certain Blocks to reconstruct coordinates from them | https://github.com/DerBejijing/BlockRotationExploit | 6 | 0| 
| 20210913T21:28:00Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 10029 | 1680| 
| 20210913T21:16:42Z | Pseudo shells for different Lambda Runtime Environments & Lambda persistency exploits | https://github.com/Djkusik/Lambda-sHell | 0 | 0| 
| 20210913T20:28:32Z | Desenvolvendo exploits x86 para linux | https://github.com/git-cardoso/Desenvolvimento_exploits_x86 | 0 | 0| 
| 20210913T20:01:25Z | Mass Exploit Multi Threading Candy CBT V.2.7.0.r0  | https://github.com/Jevil36239/Mass-Candy-CBT | 0 | 0| 
| 20210913T19:11:01Z | Shell Script that runs the BlueBomb exploit of FullMetal5 for Wii  | https://github.com/ianes-gm1/Ianis-Bluebomb-Helper | 0 | 0| 
| 20210913T18:09:57Z | 🎻 Modularized exploit generation framework | https://github.com/aesophor/requiem | 5 | 0| 
| 20210913T17:56:57Z | Un simple portefeuille qui vous laissera exploiter le STI2D a votre guise. | https://github.com/sti2d-company/wallet | 0 | 2| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210913T15:59:12Z | This script will parse an input PCAP file, pull out certificates, and analyze them. Reverse https shells can be hard to detect because unlike TCP and HTTP, the content is encrypted. To get around this and attempt some level of detection, we can analyze the handshake at the start of the connection. Meterpreter reverse https shells have randomly generated certificates, so if the issuer/domain are random charcters then we know the server is not legitimate and could be a reverse https back door | https://github.com/shailu-coder/https-backdoors | 0 | 0| 
| 20210913T15:32:16Z | backdoor | https://github.com/Emilia-ZX/backdoor | 0 | 0| 
| 20210913T15:31:33Z | This is an advanced backdoor, created with Python | https://github.com/Senc3951/Backdoor | 1 | 1| 
| 20210913T15:09:38Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 315 | 57| 
| 20210913T13:26:58Z | Command Center for multiple Windows targets gained access through Backdoor | https://github.com/ardmm/CommandCenter | 0 | 0| 
| 20210913T11:46:08Z | Goes through every company on the list and checks how much traffic they have by exploiting a backdoor in Similar Web%s API(needs Selenium). Could have been more elegant(Paying for their API), but meh | https://github.com/Infinime/similar-web | 1 | 0| 
| 20210913T10:34:52Z | Remote control software | https://github.com/h1zzz/purewater | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210913T16:25:44Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1887 | 392| 
| 20210913T15:21:26Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 466 | 73| 
| 20210913T14:16:31Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2450 | 363| 
| 20210913T08:53:38Z | Monster is a symbolic execution engine for 64-bit RISC-U code | https://github.com/cksystemsgroup/monster | 6 | 3| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210913T14:00:15Z | NDSS 2020 - HYPER-CUBE: High-Dimensional Hypervisor Fuzzing | https://github.com/RUB-SysSec/Hypercube | 11 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210913T23:57:32Z | Scalable fuzzing infrastructure. | https://github.com/google/clusterfuzz | 4563 | 459| 
| 20210913T23:52:14Z | Null | https://github.com/tmwatchanan/FuzzySets.jl | 0 | 0| 
| 20210913T23:44:35Z | Locally searching in Swift made simple (and fuzzily) | https://github.com/nerdsupremacist/Fuzzi | 8 | 0| 
| 20210913T23:43:18Z | domato but as a website | https://github.com/GawdOfROFL/rofl-fuzzer | 0 | 0| 
| 20210913T22:53:29Z | Just some random things that i%m working on. Feel free to fuzz around and do something with it. | https://github.com/ttoledo00/random_things | 0 | 0| 
| 20210913T22:13:36Z | An investigation of American Fuzzy Lop++ as a fuzzer | https://github.com/hark130/hardy-remix | 0 | 0| 
| 20210913T22:11:16Z | Null | https://github.com/MrP4n1c/fuzzy-octo-winner | 0 | 0| 
| 20210913T21:54:54Z | A groovy/java tabular Data (from CSV,SQL,JSON) processing library that supports fuzzy column matching,tranformations/merging/querying | https://github.com/kayr/fuzzy-csv | 9 | 6| 
| 20210913T21:49:01Z | Null | https://github.com/dawsonrichey/fuzzy-disco | 0 | 0| 
| 20210913T21:45:59Z | Null | https://github.com/koltiradw/FuzzingFerm | 0 | 0| 



# 日更新程序
