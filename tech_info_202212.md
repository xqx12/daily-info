# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221219 | 条件竞争导致的macOS本地提权漏洞（CVE-2022-46689）细节及POC。 | http://securityonline.info/cve-2022-46689-poc-macos-privilege-escalation-vulnerability/| 
| 20221219 | 如何基于PostMessage配置问题，在Google Docs域上发现一个XSS漏洞。 | http://blog.geekycat.in/google-vrp-hijacking-your-screenshots/| 
| 20221219 | 开源工具 laZzzy 实现了多种常见的 Shellcode 执行和混淆技术 | https://www.kitploit.com/2022/12/lazzzy-shellcode-loader-developed-using.html| 
| 20221219 | 关于敏感资源权限设置不当产生的漏洞模式，如CVE-2022-29527，aws中对于sudoers文件权限设置不当漏洞 | https://cwe.mitre.org/data/definitions/732.html| 
| 20221219 | Apache Dubbo Hession反序列化漏洞的利用，引用了一篇使用ByteCodeDL寻找CTF题目利用链的文章，ByteCodeDL是一个类似CodeQL的声明式静态分析工具，优势是支持直接分析字节码 | https://xz.aliyun.com/t/11961| 
| 20221219 | 使用ChatGPT对CVE-2022-23093（FreeBSD ping 栈溢出漏洞）进行补丁分析 | https://www.youtube.com/watch?v=bkkVClq9aGw| 
| 20221219 | 使用无人机定位建筑内WiFi设备：作者通过利用两个WiFi特性，先获得所要探测设备的Mac地址，然后计算回包延时并进行测距 | https://www.kaspersky.co.uk/blog/wi-peep-wireless-localization/25325/?reseller=gb_kdaily-blog_acq_ona_smm__all_b2c_some_sma_______&utm_source=twitter&utm_medium=social&utm_campaign=gl_kdaily-social_ag0241&utm_content=sm-post&utm_term=gl_twitter_organic_td241ocldmfitjo| 
| 20221219 | Shennina：利用AI进行自动地漏洞扫描、分析和利用 | https://www.kitploit.com/2022/12/shennina-automating-host-exploitation.html| 
| 20221219 | TP-Link AX1800 WiFi 6 Router的tdpServer在向一个固定大小的数组中写值时未做边界检查导致栈溢出 | http://research.nccgroup.com/2022/12/19/meshyjson-a-tp-link-tdpserver-json-stack-overflow/| 
| 20221219 | Windows UMPD 驱动UAF漏洞（CVE-2022-41050）的POC及相关信息公开了。 | http://ssd-disclosure.com/win32k-user-mode-printer-drivers-startdoc-uaf/?twclid=22e3s9xl58l68awwilrgs24vb7| 
| 20221219 | Kaspersky发布了捕获到的ProxyNotShell攻击事件细节，其中包括MS Exchange两个漏洞，一个是SSRF漏洞（CVE-2022-41040），另一个是RCE漏洞（CVE-2022-41082）。 | https://securelist.com/cve-2022-41040-and-cve-2022-41082-zero-days-in-ms-exchange/108364/?reseller=usa_regular-sm_acq_ona_smm__onl_b2c_twi_story_sm-team______&utm_source=twitter&utm_medium=social&utm_campaign=us_regular-sm_en0177&utm_content=sm-post&utm_term=us_twitter_organic_zj177kbuwubuokz| 
| 20221218 | mandiant发布关于签名恶意驱动程序的狩猎与分析 | https://www.mandiant.com/resources/blog/hunting-attestation-signed-malware| 
| 20221218 | HTB: Support 通关 Writeup | https://0xdf.gitlab.io/2022/12/17/htb-support.html| 
| 20221218 | 在KPTI enable的情况下，用户态的页表仍然有entry_SYSCALL_64 的mapping。由于entry_SYSCALL_64的地址与内核基地址之间的offset固定，因此攻击者可以通过频繁调用系统调用来将entry_SYSCALL_64送入TLB，并使用prefetch侧信道泄漏内核基地址。 | http://seclists.org/oss-sec/2022/q4/198| 
| 20221216 | 一个利用文件包含漏洞的教程 | https://infosecwriteups.com/how-to-exploit-file-inclusion-vulnerabilities-a-beginners-introduction-stackzero-a55267b5fafb?gi=79d58db6233c&source=rss----7b722bfd1b8d---4| 
| 20221216 | Foxit PDF Reader UAF漏洞分析和RCE利用。 | http://hacksys.io/blogs/foxit-reader-uaf-rce-jit-spraying-cve-2022-28672| 
| 20221216 | 一个讲文件格式hacking的PPT，比如如何构造一个同时是图片和Jar的文件 | https://speakerdeck.com/ange/technical-challenges-with-file-formats| 
| 20221216 | 一个APIKey的数据集，标记了市面上常见API厂商的APIkey的正则，这个数据集还附带一个小工具：输入一个APIKey，通过正则匹配获取这个APIKey可能属于的API厂商。 | https://github.com/daffainfo/all-about-apikey| 
| 20221216 | CVE-2022-45451：ngscan驱动访问控制实现缺陷，攻击者可利用该漏洞实现任意文件读取以及敏感注册表项修改 | https://github.com/alfarom256/CVE-2022-45451| 
| 20221216 | Team82团队发现并利用 CVE-2022-1361 SQLi漏洞的详情。在研究过程中发现一种利用数据库JSON特性来绕过WAF中常用的SQL语法黑名单的攻击手法，并在多款WAF上发现了这一问题，最终也将该方法加入到最新版本的SQLMap工具中。 | http://okt.to/2Nm4F9| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221219 | 静态程序分析框架“太阿”的设计之道 | https://www.bilibili.com/video/BV1XP4y1S7cP/| 
| 20221219 | 2022 年 Recorded Future C&C 服务器跟踪报告 | https://mp.weixin.qq.com/s/aJTcub12byRW3JmcKBm-Bg| 
| 20221216 | DarkAngel: 一款全自动白帽漏洞扫描器 | https://github.com/Bywalks/DarkAngel| 
| 20221216 | Project Achilles：使用 RNN 对 Java 源代码进行静态漏洞检测... | https://mp.weixin.qq.com/s/U0sZwPc5otIg1-amv12BEg| 
| 20221215 | 杀伤链视域下的算法战审思 | https://mp.weixin.qq.com/s/9rvZVolcyZ3R8-ZWQvRgAA| 
| 20221215 | EMS：试验数据驱动的高效变异模糊测试系统 | https://mp.weixin.qq.com/s/vb1Gq8B55y-sTom06hqUfA| 
| 20221215 | 电力行业网络安全等级保护管理办法 | https://mp.weixin.qq.com/s/9IgOGdBKS0a2d778cVRZGA| 
| 20221215 | 全量安全资产管理-进阶实践 | https://mp.weixin.qq.com/s/b8W-FtTy4B8cGtPfp_2uRw| 
| 20221214 | SPEL注入流程分析及CTF中如何使用 | https://sec-in.com/article/1988| 
| 20221213 | uuWAF: 免费、高性能、高扩展开源WAF | https://github.com/Safe3/uuWAF| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20221220T01:56:02Z | CVE-2021-21809 | CVE-2021-21809 POC | https://github.com/anldori/CVE-2021-21809 | | 
| 20221220T00:47:30Z | CVE-2021-45010 | 🐍 Python Exploit for CVE-2021-45010 | https://github.com/BKreisel/CVE-2021-45010 | | 
| 20221220T00:29:28Z | CVE-2022-28672 | Foxit PDF Reader Remote Code Execution Exploit | https://github.com/hacksysteam/CVE-2022-28672 | | 
| 20221219T23:26:07Z | CVE-2020-17382 | The MSI AmbientLink MsIo64 driver 1.0.0.8 has a Buffer Overflow (0x80102040, 0x80102044, 0x80102050,and 0x80102054). | https://github.com/Exploitables/CVE-2020-17382 | | 
| 20221219T13:55:14Z | CVE-2022-45451 | PoC for Acronis Arbitrary File Read - CVE-2022-45451 | https://github.com/alfarom256/CVE-2022-45451 | | 
| 20221219T10:10:54Z | CVE-2022-44215 | Null | https://github.com/wh-gov/CVE-2022-44215 | | 
| 20221219T09:34:49Z | CVE-2022-44215 | Public disclosure of TitanFTP 19.X Open Redirection vulnerability | https://github.com/JBalanza/CVE-2022-44215 | | 
| 20221219T06:10:11Z | CVE-2022-0847 | Dirty Pipe - CVE-2022-0847 | https://github.com/tmoneypenny/CVE-2022-0847 | | 
| 20221219T05:25:40Z | CVE-2022-43680 | Null | https://github.com/nidhihcl/external_expat_2.1.0_CVE-2022-43680 | | 
| 20221218T19:52:22Z | CVE-2021-34527 | PrintNightmare (CVE-2021-34527) PoC Exploit | https://github.com/m8sec/CVE-2021-34527 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221219T22:36:31Z | An experimental unit test generator for C programs based on KLEE | https://github.com/liuzikai/klee-unit | 0 | 0| 
| 20221219T19:34:08Z | Null | https://github.com/katyushapolye/KleeMains | 0 | 0| 
| 20221219T14:30:09Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 269 | 50| 
| 20221219T14:14:33Z | Null | https://github.com/kleeblattdev/kleeblattdev-html_codeflow_lev1_3_ol-ul | 0 | 0| 
| 20221219T13:46:43Z | toolchain for klee | https://github.com/mojyack/klee-buildenv | 0 | 0| 
| 20221219T12:18:44Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2126 | 603| 
| 20221219T10:21:24Z | Null | https://github.com/KleePaimon/KleePaimon.github.io | 1 | 0| 
| 20221219T03:56:34Z | Collection of Kicad 6.0 symbols, footprints and 3D models useful in keyboard creation | https://github.com/crides/kleeb | 53 | 3| 
| 20221218T10:37:00Z | Minecraft Mod. Allows breaking only one half of a double slab block. | https://github.com/TwelveIterationMods/KleeSlabs | 11 | 6| 
| 20221218T10:11:47Z | Null | https://github.com/KleePaimon/KleePaimon.github.io1 | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221219T02:36:14Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 279 | 66| 
| 20221218T05:38:25Z | Spacecraft Simulation Environment Core codes | https://github.com/ut-issl/s2e-core | 26 | 7| 
| 20221214T12:59:07Z | s2e-user | https://github.com/kai0722/s2e-user | 0 | 0| 
| 20221214T11:33:42Z | The Chef symbolic execution platform, based off S2E | https://github.com/dslab-epfl/chef | 7 | 2| 
| 20221213T06:33:44Z | GUI Configuration tool for WIZnet serial to ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool-GUI | 17 | 9| 
| 20221212T05:54:12Z | Documents for Spacecraft Simulation Environment | https://github.com/ut-issl/s2e-documents | 6 | 6| 
| 20221205T08:13:33Z | Your S2E project management tools. Visit https://s2e.systems/docs to get started. | https://github.com/S2E/s2e-env | 84 | 45| 
| 20221204T02:10:12Z | S2E user side repository for Formation Flying study | https://github.com/ut-issl/s2e-ff | 3 | 1| 
| 20221201T07:39:12Z | S2erial_TcpServer_Long | https://github.com/liukai007/S2erial_TcpServer_Long | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221220T02:08:28Z | Null | https://github.com/0x414141414/New-Silent-Excel-Exploit-2023 | 0 | 0| 
| 20221220T02:07:35Z | Null | https://github.com/0x414141414/Silent-Word-DOC-DOCX-Exploit-2023 | 0 | 0| 
| 20221220T02:07:04Z | Null | https://github.com/0x414141414/New-Silent-PDF-Exploit-2023 | 0 | 0| 
| 20221220T02:06:19Z | Null | https://github.com/0x414141414/JPEG-Silent-Exploit-Builder-2023 | 0 | 0| 
| 20221220T01:35:36Z | Null | https://github.com/cryocet/Mika-Exploit | 0 | 0| 
| 20221220T00:47:30Z | 🐍 Python Exploit for CVE-2021-45010 | https://github.com/BKreisel/CVE-2021-45010 | 0 | 0| 
| 20221220T00:17:13Z | [Award winning solutionSmart at Vivatech%s hackathon] SMARTMOVE is an application and a Dashboard aiming to show all the alternatives to car ownership. The goal: to decongest cities, and reduce one%s carbon footprint, by exploiting all the resources of one%s city for mobility 🛴🌱 | https://github.com/Duckiduc/smartmove | 0 | 0| 
| 20221219T23:12:00Z | Kernel exploits | https://github.com/ReverseThrottle/KernelExploitation | 0 | 0| 
| 20221219T22:19:51Z | Exploit Development and Reverse Engineering with GDB Made Easy | https://github.com/pwndbg/pwndbg | 5137 | 716| 
| 20221219T22:10:24Z | Houdini is a container escape artist. Test your container security frameworks against known exploits. | https://github.com/willfindlay/houdini | 2 | 1| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221220T02:17:02Z | this is my personal Leux backdoor config folder **Stronk AC* | https://github.com/Skewice/Leuxbackdoor-Config | 0 | 0| 
| 20221220T02:11:16Z | Leux Backdoor Latest Version Clean Obfuscated Jar | https://github.com/Skewice/CLEAN-Leux-Backdoor-0.9.8-OBF | 2 | 0| 
| 20221220T02:00:54Z | Villain is a Windows & Linux backdoor generator and multi-session handler that allows users to connect with sibling servers (other machines running Villain) and share their backdoor sessions, handy for working as a team. | https://github.com/t3l3machus/Villain | 1954 | 335| 
| 20221220T01:55:40Z | Venom is a library that meant to perform evasive communication using stolen browser socket | https://github.com/Idov31/Venom | 211 | 26| 
| 20221219T23:30:47Z | Null | https://github.com/Anonimo055x/Backdoor-MGRV2-ProxySSH-Ransonware-8 | 0 | 0| 
| 20221219T22:33:59Z | Null | https://github.com/navyajammalamadaka/Final-Project--Targeted-Backdoor-Attacks-Against-Deep-Learning-Systems-with-DeepFace-By-Backdoor-Po | 0 | 1| 
| 20221219T20:02:05Z | PSC %Backdoors sur des NLP% | https://github.com/Devaccount2/PSC-ML | 0 | 0| 
| 20221219T13:41:16Z | Tutorial Deface, Download shell backdoor, exploit lainnya | https://github.com/bellpwn/netxploit | 1 | 0| 
| 20221219T12:30:16Z | hiphp - free & open source project for create a BackDoor to control PHP-based sites. 🚪🔑🙂 | https://github.com/yasserbdj96/hiphp | 25 | 9| 
| 20221219T06:20:39Z | Null | https://github.com/0xn4utilus/backdoor22 | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221220T02:10:35Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2127 | 602| 
| 20221219T21:53:55Z | Symbolic-execution-based verifier for the Viper intermediate verification language. | https://github.com/viperproject/silicon | 52 | 25| 
| 20221219T18:55:21Z | Symbolical Execution for MiniMal Assembler | https://github.com/wadoon/mima-symbex | 0 | 0| 
| 20221219T08:34:35Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3247 | 457| 
| 20221219T03:53:30Z | Optik is a set of symbolic execution tools that assist smart-contract fuzzers | https://github.com/crytic/optik | 49 | 7| 
| 20221218T17:17:28Z | Open-source symbolic execution framework: https://maat.re | https://github.com/trailofbits/maat | 522 | 30| 
| 20221218T02:04:26Z | Symbolic Execution Over Processor Traces | https://github.com/carter-yagemann/ARCUS | 82 | 17| 
| 20221217T01:12:34Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 602 | 111| 
| 20221215T14:00:21Z | Symbolic execution engine written for the OOX language | https://github.com/tjausm/Jip | 0 | 0| 
| 20221214T23:23:44Z | Use angr in Ghidra | https://github.com/Nalen98/AngryGhidra | 410 | 37| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221219T01:54:46Z | A curated list of Meachine learning Security & Privacy papers published in security top-4 conferences (IEEE S&P, ACM CCS, USENIX Security and NDSS). | https://github.com/gnipping/Awesome-ML-SP-Papers | 23 | 2| 
| 20221215T16:22:48Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 65 | 15| 
| 20221212T19:19:12Z | Dynamic Proof of Retrievability using Verifiable Computation and Error Correction Code (NDSS%23) | https://github.com/vt-asaplab/porla | 2 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221220T02:35:30Z | Null | https://github.com/Saaswath-Upendran/Travel-Recommendation-using-fuzzy-logic | 0 | 0| 
| 20221220T01:35:37Z | Testing echidna vs. forge fuzzing | https://github.com/clabby/echidna-vs-forge | 11 | 1| 
| 20221220T01:25:23Z | Null | https://github.com/Leo-roc/fuzzy-succotash | 0 | 0| 
| 20221220T01:16:03Z | Null | https://github.com/DTI22/Fuzz-Foam | 1 | 0| 
| 20221220T00:33:41Z | Null | https://github.com/johnleoharkins/fuzzy-chainsaw | 0 | 0| 
| 20221220T00:16:22Z | Null | https://github.com/DTI22/Fuzz-Foam- | 0 | 0| 
| 20221219T23:19:57Z | Null | https://github.com/bacon-tomato-spaghetti/XRDP-Fuzzer | 0 | 0| 
| 20221219T23:19:14Z | Null | https://github.com/bacon-tomato-spaghetti/FreeRDP-RDPGFX-Fuzzer | 0 | 0| 
| 20221219T22:53:26Z | Explore  | https://github.com/jeffBigSmile/fuzzy-adventure | 0 | 0| 
| 20221219T22:12:42Z | *A simple way to upload files in the database using C# application that analyze and extract keywords from the text and the frequency of keywords using simple fuzzy algorithms and encrypt the file content and stored in the database to allow users to search for a word within the files and the program reviews all the files that contain The word and arranged in descending order *The search algorithm works on both Arabic and English *SQL server 2014 used for DBMS *visual Studio 2013 update 5 used for programming C# App | https://github.com/Mgdd/Fuzzy-Search-Scheme | 2 | 1| 



# 日更新程序
