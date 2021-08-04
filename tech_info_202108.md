# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210803 | Rotten Apples: MacOS Codesigning Translocation Vulnerability | https://occamsec.com/rotten-apples-macos-codesigning-translocation-vulnerability/| 
| 20210803 | Windows Non-Paged-Pool 溢出漏洞的利用（CVE-2020-17087） | https://github.com/vp777/Windows-Non-Paged-Pool-Overflow-Exploitation| 
| 20210803 | 利用 CodeQL 检测 Jackson 中的反序列化漏洞 | https://blog.gypsyengineer.com/en/security/detecting-jackson-deserialization-vulnerabilities-with-codeql.html| 
| 20210803 | Linux 内核模块编程指南 | https://sysprog21.github.io/lkmpg/| 
| 20210803 | Universal Privilege Escalation and Persistence – Printer | https://pentestlab.blog/2021/08/02/universal-privilege-escalation-and-persistence-printer/| 
| 20210803 | 利用各类技术绕过 AV-EDR 检测的框架 | https://klezvirus.github.io/RedTeaming/AV_Evasion/CodeExeNewDotNet/| 
| 20210803 | macOS 应急响应与取证分析相关的部分资料 | https://gist.github.com/0xmachos/6e8b813cffc2035914606bd4cda491d2| 
| 20210803 | PyPI 仓库 GitHub Actions 配置不当导致的 pypi.org 任意代码执行漏洞 | https://blog.ryotak.me/post/pypi-potential-remote-code-execution-en/| 
| 20210803 | Kunyu(坤舆) - 更高效的企业资产收集工具演示视频。 | https://www.youtube.com/watch?v=R4wwMqEdaUI&feature=youtu.be| 
| 20210802 | SDR++，跨平台、开源的 SDK 分析软件 | https://github.com/AlexandreRouma/SDRPlusPlus| 
| 20210802 | BIAS: Bluetooth Impersonation AttackS | https://francozappa.github.io/about-bias/| 
| 20210802 | 打印机驱动 CVE-2021-3438 漏洞的逆向分析 | https://voidsec.com/root-cause-analysis-of-cve-2021-3438/| 
| 20210802 | Windows 10 KVAS and Software SMEP | https://wumb0.in/windows-10-kvas-and-software-smep.html| 
| 20210802 | V8 脚本引擎 Heap Sandbox 的设计文档 | https://docs.google.com/document/d/1FM4fQmIhEqPG8uGp5o9A-mnPB5BOeScZYpkHjo0KKA8/edit| 
| 20210802 | Fuzzing Windows RPC with RpcView | https://itm4n.github.io/fuzzing-windows-rpc-rpcview/| 
| 20210802 | Ninja - 一款用于渗透测试的开源的 C&C Server | https://github.com/ahmedkhlief/Ninja| 
| 20210802 | 智能电动车充电桩安全测试 | https://www.pentestpartners.com/security-blog/smart-car-chargers-plug-n-play-for-hackers/| 
| 20210802 | 重新编译旧的森海塞尔麦克风 -第4部分-PLL(锁相环) | https://vgnotepad.blogspot.com/2021/06/reprogramming-old-sennheiser-microphone_3.html| 
| 20210802 | 破解协议（缓冲区）：逆向工程分析 gRPC 二进制文件。 | https://labs.ioactive.com/2021/07/breaking-protocol-buffers-reverse.html| 
| 20210801 | Portable Executable Injection Study | https://malwareunicorn.org/workshops/peinjection.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210803 | Linux计划任务那点事儿 | https://mp.weixin.qq.com/s/KfeKpoPj-X7BRNR7O6QAcw| 
| 20210803 | Lazarus结合NDay投递VBA恶意远控的攻击分析 | https://mp.weixin.qq.com/s/x7L3R9iQdnrnEKpfop92Gg| 
| 20210802 | 如何利用多杀软结果归并恶意软件家族名称 | https://mp.weixin.qq.com/s/hOvqm0U7rc-NNdVjR0dAaA| 
| 20210802 | 做红队你需要学习“如何挖掘战壕”（三） | https://mp.weixin.qq.com/s/OO_VZ8QB_J5UY88qkpLXDg| 
| 20210802 | SecWiki周刊（第387期) | https://www.sec-wiki.com/weekly/387| 
| 20210802 | Attacking Active Directory: 0 to 0.9 | https://zer1t0.gitlab.io/posts/attacking_ad/| 
| 20210801 | 可信安全网络 —— 安全左移之DDoS对抗 | https://security.tencent.com/index.php/blog/msg/198| 
| 20210801 | 情报研究方法论——对情报收集工作的展望 | https://paper.seebug.org/1647/| 
| 20210801 | 知识图谱及其在安全领域的应用 | https://paper.seebug.org/1649/| 
| 20210801 | 从Github一开源项目ADSEC学习域渗透攻防基础 | https://www.anquanke.com/post/id/248030| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210804T01:33:05Z | CVE-2020-14343 | Experimenting with the CVE-2020-14343 PyYAML vulnerability | https://github.com/raul23/pyyaml-CVE-2020-14343 | A vulnerability was discovered in the PyYAML library in versions before 5.4, where it is susceptible to arbitrary code execution when it processes untrusted YAML files through the full_load method or with the FullLoader loader. Applications that use the library to process untrusted input may be vulnerable to this flaw. This flaw allows an attacker to execute arbitrary code on the system by abusing the python/object/new constructor. This flaw is due to an incomplete fix for CVE-2020-1747.| 
| 20210803T23:43:35Z | CVE-2020-9922 | Null | https://github.com/Wowfunhappy/Fix-Apple-Mail-CVE-2020-9922 | A logic issue was addressed with improved state management. This issue is fixed in macOS Catalina 10.15.6, Security Update 2020-004 Mojave, Security Update 2020-004 High Sierra. Processing a maliciously crafted email may lead to writing arbitrary files.| 
| 20210803T16:47:30Z | CVE-2021-37833 | CVE 2021-37833 Hotel Druid 3.0.2 Reflected Cross Site Scripting | https://github.com/dievus/CVE-2021-37833 | A reflected cross-site scripting (XSS) vulnerability exists in multiple pages in version 3.0.2 of the Hotel Druid application that allows for arbitrary execution of JavaScript commands.| 
| 20210803T16:31:30Z | CVE-2020-14321 | Course enrolments allowed privilege escalation from teacher role into manager role to RCE | https://github.com/HoangKien1020/CVE-2020-14321 | 未查询到CVE信息| 
| 20210803T15:55:43Z | CVE-2021-22204 | Null | https://github.com/AssassinUKG/CVE-2021-22204 | | 
| 20210803T14:48:30Z | CVE-2021-3492 | PoC for CVE-2021-3492 used at Pwn2Own 2021 | https://github.com/synacktiv/CVE-2021-3492 | Shiftfs, an out-of-tree stacking file system included in Ubuntu Linux kernels, did not properly handle faults occurring during copy_from_user() correctly. These could lead to either a double-free situation or memory not being freed at all. An attacker could use this to cause a denial of service (kernel memory exhaustion) or gain privileges via executing arbitrary code. AKA ZDI-CAN-13562.| 
| 20210803T13:55:23Z | CVE-2021-2394 | POC of CVE-2021-2394 | https://github.com/freeide/CVE-2021-2394 | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Core). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via T3, IIOP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210803T13:45:02Z | CVE-2021-37832 | CVE-2021-37832 - Hotel Druid 3.0.2 SQL Injection Vulnerability | https://github.com/dievus/CVE-2021-37832 | A SQL injection vulnerability exists in version 3.0.2 of Hotel Druid when SQLite is being used as the application database. A malicious attacker can issue SQL commands to the SQLite database through the vulnerable idappartamenti parameter.| 
| 20210803T11:51:20Z | CVE-2021-3560 | Polkit D-Bus Authentication Bypass Exploit | https://github.com/0dayNinja/CVE-2021-3560 | 未查询到CVE信息| 
| 20210803T11:00:50Z | CVE-2021-36934 | POC experiments with Volume Shadow copy Service (VSS) | https://github.com/grishinpv/poc_CVE-2021-36934 | Windows Elevation of Privilege Vulnerability| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210803T07:56:42Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 217 | 35| 
| 20210803T05:35:20Z | Config files for my GitHub profile. | https://github.com/JiwonKLee/JiwonKLee | 0 | 0| 
| 20210803T01:42:50Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2470 | 59| 
| 20210802T22:54:46Z | Null | https://github.com/santiagoHV/kleer-dojo-assessment-backend | 0 | 0| 
| 20210802T15:16:36Z | Null | https://github.com/pansilup/cgc-prgs-for-klee-seed-mode | 0 | 0| 
| 20210802T09:51:15Z | Null | https://github.com/coffee100percnt/KleeDiscordBomber | 4 | 0| 
| 20210802T02:07:51Z | Null | https://github.com/adamhumphriescs/TASE_KLEE | 0 | 0| 
| 20210801T22:09:32Z | Izrada novih algoritama za pretragu u okvriu alata za simboličko izvršavanje KLEE | https://github.com/MATF-Software-Verification/2020_03_Klee_Searcher | 0 | 0| 
| 20210801T13:35:53Z | ⬇️ File Upload/sharing application, used by thousands of webmasters since 2007.  | https://github.com/kleeja-official/kleeja | 126 | 36| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T11:21:56Z | Null | https://github.com/yuvalkirstain/s2e-coref | 11 | 4| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210804T01:49:56Z | Vulnerabilities% Risk of Exploitation | https://github.com/thiagofigcosta/V-REx-v2 | 0 | 0| 
| 20210804T01:47:03Z | A collection of kernel pwn challenges and writeups | https://github.com/fr33bug/PWN | 0 | 0| 
| 20210804T01:43:17Z | An introduction, explanation, and tutorial of various exploits for the heap of current and recent GNU libcs. | https://github.com/bstank/bstank.github.io | 0 | 0| 
| 20210804T01:14:58Z | The AWS exploitation framework, designed for testing the security of Amazon Web Services environments. | https://github.com/RhinoSecurityLabs/pacu | 2232 | 404| 
| 20210804T01:06:41Z | Use udp magic packets and an http server on ESP32 to boot computers remotely, dont use this for anything, it is easily exploitable | https://github.com/benschreyer/ESP32_WAKE_ON_WAN | 0 | 0| 
| 20210804T01:03:52Z | Reverse Engineering Exploit and Tool coding for Security Professionals by James C. Foster with Mike Price | https://github.com/giovannyortegon/SocketsShellcodePortingAndCoding | 0 | 0| 
| 20210804T01:03:15Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 29 | 15| 
| 20210804T00:52:09Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 19 | 12| 
| 20210804T00:39:05Z | Null | https://github.com/zYan666/Demon-Exploit | 0 | 0| 
| 20210804T00:33:42Z | A post exploitation utility for loading signed kernel drivers using both the undocumented NtLoadDriver function and by directly interfacing with the Windows Service Control Manager (SCM) | https://github.com/FULLSHADE/DrvLoader | 4 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210804T01:30:09Z | Null | https://github.com/GuyEditDev/backdoorpython | 0 | 0| 
| 20210803T22:54:02Z | The best backdoor scanner there is. | https://github.com/iK4oS/backdoor.exe | 1 | 1| 
| 20210803T21:54:17Z | During the exploitation phase of a pen test or ethical hacking engagement, you will ultimately need to try to cause code to run on target system computers. Whether accomplished by phishing emails, delivering a payload through an exploit, or social engineering, running code on target computers is part of most penetration tests. That means that you will need to be able to bypass antivirus software or other host-based protection for successful exploitation. The most effective way to avoid antivirus detection on your target%s computers is to create your own customized backdoor. Here is a simple way to evade anti-virus software when creating backdoors! | https://github.com/Kleptocratic/Anti-Virus-Evading-Payloads | 0 | 0| 
| 20210803T19:27:33Z | cool | https://github.com/Cakezl/backdoor | 0 | 0| 
| 20210803T17:49:16Z | Null | https://github.com/Joshua-David1/windows_backdoor | 0 | 0| 
| 20210803T16:14:11Z | Hacking tools pack & backdoors generator. | https://github.com/AdrMXR/KitHack | 575 | 79| 
| 20210803T15:17:41Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 273 | 50| 
| 20210803T13:02:01Z | Malika is a very simple malware for GNU/Linux written in Python for educational purpose only. | https://github.com/CalfCrusher/malika | 0 | 0| 
| 20210803T10:12:35Z | Mini Shell | https://github.com/Rzzky/Perindo-Shell-Backdoor | 0 | 0| 
| 20210803T10:06:26Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/Ghost | 1242 | 586| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210803T23:43:09Z | symbolic execution plugin for binary ninja | https://github.com/borzacchiello/seninja | 92 | 6| 
| 20210803T19:40:34Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2406 | 355| 
| 20210803T15:56:44Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1862 | 387| 
| 20210803T04:07:10Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1740 | 499| 
| 20210802T20:16:15Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 451 | 68| 
| 20210802T13:39:37Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 153 | 33| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210803T01:36:03Z | Original implementation of FlowPrint as in the NDSS %20 paper | https://github.com/Thijsvanede/FlowPrint | 52 | 18| 
| 20210802T10:52:04Z | Config files for my GitHub profile. | https://github.com/WlNDSS/WlNDSS | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210804T01:50:06Z | Null | https://github.com/Ubisam-Project-MASIDU/FuzzStoryWorld | 0 | 0| 
| 20210804T01:48:33Z | FuzzingStudy | https://github.com/qpalzmm22/FuzzingStudy | 0 | 0| 
| 20210804T01:42:35Z | Scalable fuzzing infrastructure. | https://github.com/google/clusterfuzz | 4537 | 453| 
| 20210804T01:39:50Z | Null | https://github.com/BartekBac/FuzzyFlink | 0 | 0| 
| 20210804T01:39:36Z | RESTler is the first stateful REST API fuzzing tool for automatically testing cloud services through their REST APIs and finding security and reliability bugs in these services. | https://github.com/microsoft/restler-fuzzer | 986 | 108| 
| 20210804T01:14:04Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6529 | 1328| 
| 20210804T01:12:01Z | Null | https://github.com/wearypossum4770/fuzzy-funicular | 0 | 0| 
| 20210804T00:25:21Z | Generator of random circuits | https://github.com/drom/circt-fuzzer | 1 | 0| 
| 20210804T00:05:58Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 21 | 8| 
| 20210803T23:59:29Z | Null | https://github.com/sarita1varanasi/fuzzy-octo-system | 0 | 0| 



# 日更新程序
