# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210629 | 利用 macOS CVE-2020-9971 XPC Services 提权漏洞逃逸 Microsoft Office App Sandbox | https://perception-point.io/using-cve-2020-9971-to-escape-microsoft-offices-app-sandbox/| 
| 20210629 | AEM CRX Bypass: The 0-day that took control over some enterprise AEM CRX Package Manager | https://labs.detectify.com/2021/06/28/aem-crx-bypass-0day-control-over-some-enterprise-aem-crx-package-manager/| 
| 20210629 | 惠普安全团队对 Snake Keylogger 的分析 | https://threatresearch.ext.hp.com/the-many-skins-of-snake-keylogger/| 
| 20210629 | Google ISC DHCP 软件随机数存在问题，导致攻击者可以通过网络攻击 Google Cloud Platform 虚拟机 | https://github.com/irsl/gcp-dhcp-takeover-code-exec| 
| 20210629 | ATM 机 NFC 模块固件存在漏洞，可通过手机 App 攻击 | https://arstechnica.com/information-technology/2021/06/nfc-flaws-let-researchers-hack-an-atm-by-waving-a-phone/| 
| 20210629 | 如何用 WinAFL 发现 Windows 图形设备接口 GDI+ 的 RCE 漏洞（CVE-2021-1665） | https://www.mcafee.com/blogs/other-blogs/mcafee-labs/analyzing-cve-2021-1665-remote-code-execution-vulnerability-in-windows-gdi/| 
| 20210629 | G DATA 研究团队发现微软为一个 Rootkit 驱动（Netfilter）签发了合法签名 | https://threatpost.com/microsoft-malicious-rootkit-gaming/167323/| 
| 20210629 | Adobe Acrobat Reader DC CVE-2020-9715 UAF 漏洞的分析和利用，来自 Exodus Intelligence | https://blog.exodusintel.com/2021/04/20/analysis-of-a-use-after-free-vulnerability-in-adobe-acrobat-reader-dc/?utm_source=rss&utm_medium=rss&utm_campaign=analysis-of-a-use-after-free-vulnerability-in-adobe-acrobat-reader-dc| 
| 20210629 | Certified Pre-Owned - Abusing Active Directory Certificate Services | https://www.specterops.io/assets/resources/Certified_Pre-Owned.pdf| 
| 20210629 | REVEN Vulnerability Research Automation Demo | https://blog.tetrane.com/2021/REVEN-Reverse-Engineering-Automation-Demo.html| 
| 20210629 | 微软官方发布第一个适用于 Windows 11 的 Insider Preview版本。 | https://blogs.windows.com/windows-insider/2021/06/28/announcing-the-first-insider-preview-for-windows-11/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210629 | “重门深锁”FormBook Crypter 执行隐匿技术精析 | https://mp.weixin.qq.com/s/bfILTCvuaBASdmWTd4BnoQ| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210629T23:58:09Z | CVE-2021-27850 | A Proof of concept for CVE-2021-27850 affecting Apache Tapestry and leading to unauthencticated remote code execution. | https://github.com/kahla-sec/CVE-2021-27850_POC | | 
| 20210629T21:09:43Z | CVE-2021-3560 | Null | https://github.com/AssassinUKG/Polkit-CVE-2021-3560 | 未查询到CVE信息| 
| 20210629T16:34:11Z | 未知编号 |  Microsoft  acknowledged a critical remote code execution  vulnerability (CVE – 2020 - 1350) existing in  Windows Domain Name System (DNS) when it  fails to properly handle requests. An adversary  who successfully exploits the vulnerability could  run arbitrary code or malicious code in the  context of the Local System Account. And this  vulnerability rests on the DNS client while it  handles specific requests. This means that an  attacker who does not perform an  authentication can gain control of an account  that exists locally on the system, even remotely.  This will allow the host to reach a complete  compromise. T | https://github.com/ejlevin99/CVE---2020---1350 | 未查询到CVE信息| 
| 20210629T15:10:28Z | cve-2021-22214 | Gitlab SSRF | https://github.com/Vulnmachines/gitlab-cve-2021-22214 | When requests to the internal network for webhooks are enabled, a server-side request forgery vulnerability in GitLab CE/EE affecting all versions starting from 10.5 was possible to exploit for an unauthenticated attacker even on a GitLab instance where registration is limited| 
| 20210629T14:26:28Z | CVE-2021-1675 | CVE-2021-1675 exploit | https://github.com/yu2u/CVE-2021-1675 | Windows Print Spooler Elevation of Privilege Vulnerability| 
| 20210629T13:44:10Z | CVE-2021-31955 | Null | https://github.com/mavillon1/CVE-2021-31955-POC | Windows Kernel Information Disclosure Vulnerability| 
| 20210629T12:20:58Z | CVE-2021-22911 | Pre-Auth Blind NoSQL Injection leading to Remote Code Execution in Rocket Chat 3.12.1 | https://github.com/CsEnox/CVE-2021-22911 | A improper input sanitization vulnerability exists in Rocket.Chat server 3.11, 3.12 & 3.13 that could lead to unauthenticated NoSQL injection, resulting potentially in RCE.| 
| 20210629T11:28:41Z | CVE-2020-3580 | Null | https://github.com/Hudi233/CVE-2020-3580 | Multiple vulnerabilities in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct cross-site scripting (XSS) attacks against a user of the web services interface of an affected device. The vulnerabilities are due to insufficient validation of user-supplied input by the web services interface of an affected device. An attacker could exploit these vulnerabilities by persuading a user of the interface to click a crafted link. A successful exploit could allow the attacker to execute arbitrary script code in the context of the interface or allow the attacker to access sensitive, browser-based information. Note: These vulnerabilities affect only specific AnyConnect and WebVPN configurations. For more information, see the Vulnerable Products section.| 
| 20210629T09:12:29Z | CVE-2021-32537 | PoC for CVE-2021-32537: an out-of-bounds memory access that leads to pool corruption in the Windows kernel. | https://github.com/0vercl0k/CVE-2021-32537 | 未查询到CVE信息| 
| 20210629T05:39:49Z | CVE-2021-35475 | Writeup for CVE-2021-35475; Stored Cross-Site Scripting(XSS) on SAS® Environment Manager 2.5 | https://github.com/saitamang/CVE-2021-35475 | SAS Environment Manager 2.5 allows XSS through the Name field when creating/editing a server. The XSS will prompt when editing the Configuration Properties.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T23:36:46Z | Whole Program LLVM: wllvm ported to go | https://github.com/SRI-CSL/gllvm | 138 | 21| 
| 20210629T14:30:31Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 151 | 14| 
| 20210629T00:31:42Z | Null | https://github.com/kleelab/kleelab.github.io | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T12:17:11Z | cicd logic and gitlab&github runner&jenkins agent container, centos base ,whith jdk/python/go, maven/npm,/kubectl/helm | https://github.com/chimeh/cicd-s2e-runner | 2 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T23:29:04Z | Project Carthage is a Roblox Exploit that inspired by code lyoko | https://github.com/DeletedUser0x96/Project-Carthage | 0 | 0| 
| 20210629T21:57:15Z | learning various heap exploitation techniques | https://github.com/izabela-am/Heap-Exploitation | 0 | 0| 
| 20210629T21:25:07Z | How to exploit BERT for detecting users% personality type based on some text they have posted, according to the Myers–Briggs Type Indicator (MBTI). | https://github.com/rcantini/BERT_personality_detection | 0 | 0| 
| 20210629T20:42:28Z | Modular penetration testing platform that enables you to write, test, and execute exploit code. | https://github.com/EntySec/HatSploit | 69 | 24| 
| 20210629T20:36:34Z | Asoiu online exam Telegram bot exploit  | https://github.com/rad1k4l/asoiuexambot-exploit-node | 0 | 0| 
| 20210629T20:32:13Z | Shader script for Roblox exploits. | https://github.com/LegitH3x0R/HackerShader | 0 | 0| 
| 20210629T20:27:09Z | This project was assigned to me by my teacher, I was instructed to copy the theme of popular online store Daraz PK & also to manipulate it with by using my own creativity skills. It took a week to complete this whole project, furthermore, I exploited BS4, CSS, Media Queries, Font Awesome Icons, etc. | https://github.com/Taha-Sheikh1/Daraz-Pakistan-Project | 1 | 0| 
| 20210629T20:16:57Z | script to interact with Ethereum, and use it to exploit the service via command injection | https://github.com/lnwza777/Chainsaw- | 0 | 0| 
| 20210629T20:12:58Z | Example of exploiting a buffer overflow vulnerability | https://github.com/seregeu/Lab-buffer-overflow | 0 | 0| 
| 20210629T19:47:51Z | exploit found on the irish goverements website, gov.ie.  | https://github.com/PeaceNIRA/wordpress-exploit | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T23:49:22Z | Code and data of the ACL 2021 paper %Turn the Combination Lock: Learnable Textual Backdoor Attacks via Word Substitution% | https://github.com/thunlp/BkdAtk-LWS | 3 | 0| 
| 20210629T22:52:32Z | PHP Backdoor is a web-based application that allows to execute terminal commands on a server directly from a browser. | https://github.com/psyll/PHP-Backdoor | 1 | 0| 
| 20210629T20:43:43Z | A papermc plugin that allows code execution without any permissions on the server for selected users. | https://github.com/TheSaltyBoys/backdoor-v4 | 0 | 1| 
| 20210629T18:30:24Z | A minecraft backdoor that uses the Java Discord API (JDA) to combine a discord bot with a minecraft papermc plugin | https://github.com/TheSaltyBoys/Backdoor-v5 | 0 | 0| 
| 20210629T17:07:02Z | This program will help you to detect errors in a keyboard and it also used as backdoor program. | https://github.com/cyrobotcoder/keylogger | 0 | 0| 
| 20210629T12:26:43Z | A static analysis tool to reveal backdoor threats in Ethereum smart contracts | https://github.com/SmartContractBackdoor/DPiper-tool | 2 | 0| 
| 20210629T09:13:27Z | A Python module for building botnet ,backdoor or trojan with Telegram control panel | https://github.com/onionj/pybotnet | 2 | 2| 
| 20210629T07:15:00Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 209 | 40| 
| 20210629T07:01:52Z | Encipher - Generate XOR encoded backdoors using Python | https://github.com/Revise7/Encipher | 0 | 0| 
| 20210629T06:59:17Z |  SniperSight - Listener, Backdoor & Keylogger Generator Developed & Maintained By revise7 | https://github.com/Revise7/SniperSight | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T21:04:21Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2368 | 348| 
| 20210629T19:49:44Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 145 | 33| 
| 20210629T11:08:06Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1724 | 495| 
| 20210629T02:57:53Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 14 | 3| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T09:53:05Z | Code to run the evaluation of our %Obfuscated Access and Search Patterns in Searchable Encryption%, NDSS%21 | https://github.com/simon-oya/NDSS21-osse-evaluation | 2 | 1| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T23:52:15Z | Network fuzzer for Slippi Online | https://github.com/altf4/slippi_fuzz | 2 | 0| 
| 20210629T23:42:57Z | An automatic fuzzing tool for ROS 2 C++ projects  | https://github.com/rosin-project/ros2_fuzz | 5 | 0| 
| 20210629T23:25:47Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 1851 | 370| 
| 20210629T23:17:30Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6431 | 1309| 
| 20210629T22:59:05Z | Fuzzy charrs are fuzzy. | https://github.com/marenubium87/FuzzyCharr | 0 | 0| 
| 20210629T22:43:33Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 3 | 1| 
| 20210629T22:37:27Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3576 | 831| 
| 20210629T22:36:07Z | These tests of libdwarf/dwarfdump include old object files, new ones, and many fuzzed object files. These are the definitive tests that things work.. Most people have no reason to run these tests. | https://github.com/davea42/libdwarf-regressiontests | 0 | 0| 
| 20210629T22:32:49Z | Fuzzy name matching with python | https://github.com/conjectures/fuzzy-name-matching | 0 | 0| 
| 20210629T22:32:46Z | Null | https://github.com/DanielEbert/EmulatedFirmwareFuzzing | 0 | 0| 



# 日更新程序
