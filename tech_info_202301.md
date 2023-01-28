# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230127 | CVE-2023-24055:KeePass 配置文件具有写入权限的攻击者可以修改它并注入恶意触发器,可以泄露密码 | https://github.com/alt3kx/CVE-2023-24055_PoC| 
| 20230127 | 利用 Windows CryptoAPI 中的欺骗漏洞(CVE-2022-34689),Poc的攻击分为两种:一种利用 Chrome v48,另一种侧重于crypt32.dll中易受攻击的MD5 | https://github.com/akamai/akamai-security-research/tree/main/PoCs/CVE-2022-34689| 
| 20230127 | openemr中的未授权任意读取漏洞以及未授权rce的漏洞分析(XSS鉴权,文件上传+LFI) | https://www.sonarsource.com/blog/openemr-remote-code-execution-in-your-healthcare-system/| 
| 20230127 | 通过利用一些硬编码在Yellowfin BI里的秘钥信息(例如私钥),用其生成后完成鉴权实现RCE | http://blog.assetnote.io/2023/01/24/yellowfin-auth-bypass-to-rce/| 
| 20230127 | MyBB <= 1.8.31中的RCE利用链:先通过留言板xss让admin的账号发search API的请求触发sqli注入 再通过修改template实现RCE | https://swarm.ptsecurity.com/mybb-1-8-31-remote-code-execution-chain/| 
| 20230127 | 通过TpAllocWork,TpPostWork,TpReleaseWork间接回调调用LoadLibrary以规避ETWTI堆栈跟踪 | http://0xdarkvortex.dev/proxying-dll-loads-for-hiding-etwti-stack-tracing/| 
| 20230125 | 激活上下文的缓存中毒:利用 CSRSS 进行权限提升的一种新的攻击面类型 | http://www.zerodayinitiative.com/blog/2023/1/23/activation-context-cache-poisoning-exploiting-csrss-for-privilege-escalation| 
| 20230125 | CVE-2021-39793:Arm Mali GPU 驱动程序JIT中的一个UAF漏洞,本文详细介绍了漏洞成因以及后续利用的细节 | https://www.reddit.com/r/netsec/comments/10jnjkq/pwning_the_all_google_phone_with_a_nongoogle_bug/| 
| 20230125 | CVE-2023-23504:XNU dlil.c中的堆写入漏洞 | http://adamdoupe.com/blog/2023/01/23/cve-2023-23504-xnu-heap-underwrite-in-dlil-dot-c/| 
| 20230125 | CVE-2022-42845:XNU ndrv.c中存在20年的UAF漏洞 | http://adamdoupe.com/blog/2022/12/13/cve-2022-42845-xnu-use-after-free-vulnerability-in-ndrv-dot-c/| 
| 20230125 | FBI 确认 Lazarus Group 对 Harmony 的 Horizo​​n Bridge 货币盗窃负责 | https://www.fbi.gov/news/press-releases/fbi-confirms-lazarus-group-apt38-cyber-actors-responsible-for-harmonys-horizon-bridge-currency-theft| 
| 20230125 | CVE-2023-0210:KSMBD 中的 Linux 内核未经身份验证的堆溢出漏洞 | https://sysdig.com/blog/cve-2023-0210-linux-kernel-unauthenticated-remote-heap-overflow/| 
| 20230125 | CVE-2021-39793:Arm Mali GPU 驱动程序JIT中的一个UAF漏洞,本文详细介绍了漏洞成因以及后续利用的细节 | http://github.blog/2023-01-23-pwning-the-all-google-phone-with-a-non-google-bug/| 
| 20230123 | idekCTF2022 - Pwn题目 Coroutine 的详细Writeup | https://kiprey.github.io/2023/01/idek_coroutine/| 
| 20230123 | 详细分析 CVE-2022-34718 漏洞包含其逆向补丁,协议的所有细节过程,包括纠正Numen Cyber Labs blog中的一些不准确的地方.并成功实现dos.以及概述讲解如何将原语转换为后续rce的一些步骤 | https://securityintelligence.com/posts/dissecting-exploiting-tcp-ip-rce-vulnerability-evilesp/| 
| 20230123 | U-Boot – USB DFU 中未经检查下载内容的大小和来源造成堆栈溢出 (CVE-2022-2347) | http://research.nccgroup.com/2023/01/20/technical-advisory-u-boot-unchecked-download-size-and-direction-in-usb-dfu-cve-2022-2347/| 
| 20230123 | bi0sCTF 2022 jsc题目b3typer的offical writeup | https://blog.bi0s.in/2023/01/23/Pwn/bi0sCTF22-b3typer/| 
| 20230123 | 入门级堆利用教学系列，目前共发布7篇 | https://infosecwriteups.com/the-toddlers-introduction-to-heap-exploitation-unsafe-unlink-part-4-3-75e00e1b0c68?gi=3c811b00aa50| 
| 20230123 | 手把手教你如何用 ROP 绕过数据执行保护（Data Execution Prevention，DEP）。利用 QuoteDB 在 Windows 平台上进行调试教学。 | http://cybergeeks.tech/a-step-by-step-introduction-to-the-use-of-rop-gadgets-to-bypass-dep/| 
| 20230122 | HTB: UpDown Writeup | https://0xdf.gitlab.io/2023/01/21/htb-updown.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230126 | 记一次Webshell检测引擎绕过测试 | https://tttang.com/archive/1875/| 
| 20230125 | Fiora：漏洞PoC框架Nuclei的图形版 | https://github.com/bit4woo/Fiora| 
| 20230125 | 各种架构ELF后门生成工具 | https://xz.aliyun.com/t/12054| 
| 20230125 | DARPA的可解释人工智能程序 | https://mp.weixin.qq.com/s/F9Dtvrlu8AU15HhTVQQojQ| 
| 20230124 | SecWiki周刊（第464期) | https://www.sec-wiki.com/weekly/464| 
| 20230124 | CVE-2022-41080_41082 Microsoft Exchange Server OWASSRF远程... | https://mp.weixin.qq.com/s/Fl7oz6VXI8k5Qn0MOk61aw| 
| 20230124 | 自动化提取恶意文档中的shellcode | https://mp.weixin.qq.com/s/xEHnaBmpH0zrhMKBvjxoGw| 
| 20230119 | 顶会论文写作建议（上）：宏观布局，避免“hard to follow” | https://mp.weixin.qq.com/s/kberQa8ss7l2gh9PAx_cSQ| 
| 20230119 | 从CISA KEV看海量漏洞管理方法 | https://mp.weixin.qq.com/s/X5J4gYanCGrGMJ9Yp6J8tQ| 
| 20230119 | 基于代码属性图的自动化漏洞挖掘实践 | https://blog.0kami.cn/blog/2023/%E5%9F%BA%E4%BA%8E%E4%BB%A3%E7%A0%81%E5%B1%9E%E6%80%A7%E5%9B%BE%E7%9A%84%E8%87%AA%E5%8A%A8%E5%8C%96%E6%BC%8F%E6%B4%9E%E6%8C%96%E6%8E%98%E5%AE%9E%E8%B7%B5/| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230127T23:53:13Z | CVE-2020-17366 | An issue was discovered in NLnet Labs Routinator 0.1.0 through 0.7.1. It allows remote attackers to bypass intended access restrictions or to cause a denial of service on dependent routing systems by strategically withholding RPKI Route Origin Authorisation ".roa" files or X509 Certificate Revocation List files from th CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-17366 | | 
| 20230127T23:53:09Z | CVE-2022-48107 | D-Link DIR_878_FW1.30B08 was discovered to contain a command injection vulnerability via the component /setnetworksettings/IPAddress. This vulnerability allows attackers to escalate privileges to root via a crafted payload. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-48107 | | 
| 20230127T23:53:06Z | CVE-2023-0555 | The Quick Restaurant Menu plugin for WordPress is vulnerable to authorization bypass due to a missing capability check on its AJAX actions in versions up to, and including, 2.0.2. This makes it possible for authenticated attackers, with subscriber-level permissions and above, to invoke those actions intended for admini CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0555 | | 
| 20230127T23:53:02Z | CVE-2023-0554 | The Quick Restaurant Menu plugin for WordPress is vulnerable to Cross-Site Request Forgery in versions up to, and including, 2.0.2. This is due to missing or incorrect nonce validation on its AJAX actions. This makes it possible for unauthenticated attackers to update menu items, via forged request granted they can tri CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0554 | | 
| 20230127T23:52:59Z | CVE-2023-0553 | The Quick Restaurant Menu plugin for WordPress is vulnerable to Stored Cross-Site Scripting via its settings parameters in versions up to, and including, 2.0.2 due to insufficient input sanitization and output escaping. This makes it possible for authenticated attackers, with administrator-level permissions and above,  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0553 | | 
| 20230127T23:52:56Z | CVE-2023-0550 | The Quick Restaurant Menu plugin for WordPress is vulnerable to Insecure Direct Object Reference in versions up to, and including, 2.0.2. This is due to the fact that during menu item deletion/modification, the plugin does not verify that the post ID provided to the AJAX action is indeed a menu item. This makes it poss CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0550 | | 
| 20230127T23:52:52Z | CVE-2022-48108 | D-Link DIR_878_FW1.30B08 was discovered to contain a command injection vulnerability via the component /SetNetworkSettings/SubnetMask. This vulnerability allows attackers to escalate privileges to root via a crafted payload. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-48108 | | 
| 20230127T23:52:49Z | CVE-2022-39380 | Wire web-app is part of Wire communications. Versions prior to 2022-11-02 are subject to Improper Handling of Exceptional Conditions. In the wire-webapp, certain combinations of Markdown formatting can trigger an unhandled error in the conversion to HTML representation. The error makes it impossible to display the affe CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-39380 | | 
| 20230127T23:52:41Z | CVE-2023-0558 | The ContentStudio plugin for WordPress is vulnerable to authorization bypass due to an unsecure token check that is susceptible to type juggling in versions up to, and including, 1.2.5. This makes it possible for unauthenticated attackers to execute functions intended for use by users with proper API keys. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0558 | | 
| 20230127T23:52:37Z | CVE-2023-0557 | The ContentStudio plugin for WordPress is vulnerable to Sensitive Information Exposure in versions up to, and including, 1.2.5. This could allow unauthenticated attackers to obtain a nonce needed for the creation of posts. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0557 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230128T00:10:59Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10232 | 342| 
| 20230127T15:36:18Z | 「缝合楷」：将「霞鹜文楷 GB」「芫荽」「Klee One」等字体相互合并制成的以各地字形为主的 Klee One 衍生字体。 | https://github.com/lxgw/FusionKai | 20 | 0| 
| 20230127T14:59:20Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 27 | 2| 
| 20230127T14:43:54Z | Kleenapp | https://github.com/spookyman69/kleenapp | 0 | 0| 
| 20230127T08:51:25Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 201 | 1| 
| 20230127T02:30:22Z | Null | https://github.com/ArnavAmbe/ARNAVCS1KLEE | 0 | 0| 
| 20230123T23:27:26Z | ⬇️ File Upload/sharing application, used by thousands of webmasters since 2007.  | https://github.com/kleeja-official/kleeja | 168 | 50| 
| 20230122T11:55:43Z | Null | https://github.com/Hvoya/klee-presense-bot | 0 | 0| 
| 20230121T06:51:03Z | Null | https://github.com/rajashekharpendli/kleeteam | 0 | 0| 
| 20230121T06:19:52Z | Null | https://github.com/rajashekharpendli/klee | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230127T05:07:52Z | Spacecraft Simulation Environment Core codes | https://github.com/ut-issl/s2e-core | 26 | 8| 
| 20230125T18:14:21Z | Null | https://github.com/en0c-026/tensor-s2e | 0 | 0| 
| 20230124T10:31:54Z | paper code | https://github.com/GMC-DRL/S2E-GA | 0 | 0| 
| 20230122T00:41:22Z | Created with StackBlitz ⚡️ | https://github.com/natanbr/Alice-in-borderland---acid-game-s2e6- | 0 | 0| 
| 20230121T12:01:48Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 291 | 69| 
| 20230113T18:45:53Z | Null | https://github.com/turbocanary/turbotest_r6aikmfr_s2e79up1 | 0 | 0| 
| 20230107T16:37:04Z | The exploit generator CRAX++ is CRAX with x86_64 ROP techniques, s2e 2.0 upgrade, code selection, I/O states, dynamic ROP, and more! | https://github.com/SQLab/CRAXplusplus | 75 | 12| 
| 20230105T06:57:30Z | Null | https://github.com/dona7025/S2ExamDs-ml | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230128T00:11:09Z | Just a simple free script for first person shooting in cars, features patched exploits such as use of radio while shooting. | https://github.com/K7AKEN/fivem-firstpersonshootingcars | 0 | 0| 
| 20230128T00:00:34Z | writeups for web exploitations challenges  | https://github.com/olaayman999/PicoCTF_writeups | 1 | 0| 
| 20230127T23:41:13Z | This is a repo hosting an exploit featuring Mojo | https://github.com/Chromium-Workshop/k1llswitch-chromium | 1 | 0| 
| 20230127T23:22:01Z | A simple CLI to setup a basic C++ development environment based on task statements from the judge platform (https://judge.science.unitn.it/), exploiting VSCode shortcuts through npm to compile and run in no time! | https://github.com/Seba-T/MontresorBuilder | 0 | 0| 
| 20230127T22:33:31Z | Null | https://github.com/codingcore12/SILENT-DOC-EXPLOIT-CLEAN-ii | 1 | 0| 
| 20230127T22:31:59Z | Null | https://github.com/codingcore12/SILENT-PDF-EXPLOIT-CLEAN-ii | 1 | 0| 
| 20230127T22:30:44Z | Null | https://github.com/codingcore12/SILENT-EXCEL-XLS-EXPLOIT-CLEAN-ii | 1 | 0| 
| 20230127T21:41:03Z | This vulnerability allows remote attackers to execute arbitrary code on affected installations of PDF-XChange Editor. User interaction is required to exploit this vulnerability in that the target must visit a malicious page or open a malicious file. The specific flaw exists within the parsing of PDF files. Crafted data CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-42400 | 0 | 0| 
| 20230127T20:16:54Z | PoC contract for exploiting solana logs | https://github.com/jarry-xiao/logspammer | 0 | 0| 
| 20230127T17:53:03Z | Open source custom DLL exploit for Roblox with custom functions, level 8 execution, multi Roblox injection, and a key system. | https://github.com/plusgiant5/TaaprWareV2 | 8 | 2| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230127T22:30:01Z | /root/.ssh/authorized_keys file watchdog and changer with ebpf tracepoint hook. | https://github.com/Esonhugh/sshd_backdoor | 2 | 0| 
| 20230127T20:42:00Z | SpyMax 4.0 is and RAT Software For Remote Android Device and has alot of Features (Remote cam, Remote files and live Seceen Recoing, and More Features. This RAT Software Requires NetFrameWork 3.5 and 4 and 4.5 (For Educational Purposes Only) | https://github.com/SoftwaresForPC/SpyMax-4.0-Activated-Cracked-Download | 0 | 0| 
| 20230127T20:28:15Z | Carbon Crypter / Packer | https://github.com/carboncryptt/CarbonCrypt | 0 | 0| 
| 20230127T18:27:08Z | AsyncRat_v0.5.6 Latest Version+Source Code Download (AsyncRAT_v0.5.6 The Most PowerFul Remote Administration Tool Ever it Can Remote any Windows Machine + Disabling Windows 10&11 Defender For Ever and Also Other Windows Defeders For All Versions Of Windows System.Educational Purposes Use it For Fun.Requiers NetFrameWork 3.5 and 4 and 4.5 | https://github.com/SoftwaresForPC/AsyncRAT_v0.5.6-Latest-Version-Source-Code | 0 | 0| 
| 20230127T16:25:09Z | Null | https://github.com/dchruscielski/backdoors-zip | 0 | 0| 
| 20230127T16:13:47Z | Null | https://github.com/simranhacks/backdoor_python | 1 | 0| 
| 20230127T13:39:11Z | 👺 Backdoor Scanner for FiveM (not a addon) | https://github.com/MasterChad/backdoor-finder-fivem | 0 | 0| 
| 20230127T06:09:59Z | [ICLR2023] Distilling Cognitive Backdoor Patterns within an Image | https://github.com/HanxunH/CognitiveDistillation | 4 | 0| 
| 20230127T04:50:28Z | Null | https://github.com/brahmaputra7/allow-backdoor | 0 | 0| 
| 20230126T22:11:00Z | A port of BHIS%s Backdoors & Breaches for playingcards.io | https://github.com/FirmGuardian/backdoors-and-breaches-pcio | 47 | 5| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230127T18:33:44Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 614 | 111| 
| 20230127T15:32:00Z | Symbolic Execution engine for finding bugs in EO programs | https://github.com/polystat/symex | 0 | 0| 
| 20230127T05:00:44Z | Concolic (Dynamic Symbolic Execution) with Angr demo on a simple binary. | https://github.com/bobby-valenzuela/AngrConcolicDemo | 0 | 0| 
| 20230126T13:42:11Z | Bachelor thesis, attempting decompilation using symbolic execution | https://github.com/lokegustafsson/thesis-decompilation | 3 | 0| 
| 20230126T10:28:22Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3287 | 467| 
| 20230126T09:13:04Z | ToolChain using Symbolic Execution for Malware Analysis. | https://github.com/csvl/SEMA-ToolChain | 14 | 8| 
| 20230125T20:06:10Z | Symbolic-execution-based verifier for the Viper intermediate verification language. | https://github.com/viperproject/silicon | 54 | 25| 
| 20230124T21:24:51Z | GenSym, a compiler for parallel symbolic execution of LLVM IR | https://github.com/Generative-Program-Analysis/GenSym | 42 | 2| 
| 20230124T17:00:45Z | The symbolic execution engine powering the K Framework | https://github.com/runtimeverification/haskell-backend | 187 | 42| 
| 20230124T13:06:36Z | Experiments with Graph Neural Networks and symbolic execution | https://github.com/katyacyfra/symbolic_exec_GNN | 0 | 0| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230127T06:02:42Z | StealthyIMU: Stealing Permission-protected Private Information From Smartphone Voice Assistant Using Zero-Permission Sensors, NDSS 2023 | https://github.com/Samsonsjarkal/StealthyIMU | 7 | 1| 
| 20230125T10:44:12Z | find relevant security papers published in the top-4 conferences (S&P, USENIX, CCS, NDSS) | https://github.com/Kyle-Kyle/top4grep | 30 | 2| 
| 20230119T16:29:30Z | Null | https://github.com/tokunagak/NDSS | 0 | 0| 
| 20230119T14:19:34Z | Code for the NDSS%23 paper %DARWIN: Survival of the Fittest Fuzzing Mutators% | https://github.com/TUDA-SSL/DARWIN | 1 | 0| 
| 20230118T07:06:06Z | Anomaly Detection in the Open World: Normality Shift Detection, Explanation, and Adaptation (NDSS%23). | https://github.com/dongtsi/OWAD | 5 | 1| 
| 20230116T10:17:44Z | ConfFuzz NDSS Data Set | https://github.com/conffuzz/conffuzz-ndss-data | 1 | 1| 
| 20230115T02:56:21Z | A Summary of Vulnerabilities Found in the BlockScope NDSS%23 Paper | https://github.com/VPRLab/BlkVulnReport | 2 | 0| 
| 20230113T21:10:57Z | DroneSecurity (NDSS 2023) | https://github.com/RUB-SysSec/DroneSecurity | 1 | 0| 
| 20230111T23:04:46Z | A Summary of Vulnerabilities Found in the BlockScope NDSS%23 Paper | https://github.com/VPRLab/BS_VulnReport | 2 | 0| 
| 20230110T22:12:59Z | Experiments from the Witcher NDSS submission  | https://github.com/sefcom/Witcher-experiment | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230128T00:42:38Z | RESTler is the first stateful REST API fuzzing tool for automatically testing cloud services through their REST APIs and finding security and reliability bugs in these services. | https://github.com/microsoft/restler-fuzzer | 1858 | 215| 
| 20230127T23:40:21Z | SeamFuzz Artifact repository for ICSE 2023 | https://github.com/kupl/SeamFuzz-Artifact | 0 | 0| 
| 20230127T23:20:15Z | Full Stack Developer, Open-source Maintainer & Contributor, Software Engineer  | https://github.com/shivalinggg/fuzzy-dollop | 0 | 0| 
| 20230127T22:26:40Z | Fuzzy logic tech blog | https://github.com/mesies/fuzzy-logic | 0 | 0| 
| 20230127T21:42:49Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8297 | 1807| 
| 20230127T21:01:21Z | fuzzy clock | https://github.com/adamjedrzejewski/fuzzy | 0 | 0| 
| 20230127T20:38:10Z | Null | https://github.com/mahrukhaleem70/fuzzy-octo-umbrella | 0 | 0| 
| 20230127T18:58:45Z | Semantic LiDAR Fuzzer | https://github.com/less-lab-uva/semLidarFuzz | 2 | 0| 
| 20230127T13:48:21Z | Welcome to Hoyt%s Windows Fuzzing Repo | https://github.com/xsscx/windows | 3 | 0| 
| 20230127T13:46:04Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 3365 | 675| 



# 日更新程序
