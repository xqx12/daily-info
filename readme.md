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
| 20230127 | 隐藏于USB介质中的PlugX变体 | https://unit42.paloaltonetworks.com/plugx-variants-in-usbs/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


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
| 20230127T15:36:18Z | 「缝合楷」：将「霞鹜文楷 GB」「芫荽」「Klee One」等字体相互合并制成的以各地字形为主的 Klee One 衍生字体。 | https://github.com/lxgw/FusionKai | 20 | 0| 
| 20230127T14:59:20Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 27 | 2| 
| 20230127T14:43:54Z | Kleenapp | https://github.com/spookyman69/kleenapp | 0 | 0| 
| 20230127T08:51:25Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 201 | 1| 
| 20230127T02:30:22Z | Null | https://github.com/ArnavAmbe/ARNAVCS1KLEE | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230127T05:07:52Z | Spacecraft Simulation Environment Core codes | https://github.com/ut-issl/s2e-core | 26 | 8| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230127T23:41:13Z | This is a repo hosting an exploit featuring Mojo | https://github.com/Chromium-Workshop/k1llswitch-chromium | 1 | 0| 
| 20230127T23:22:01Z | A simple CLI to setup a basic C++ development environment based on task statements from the judge platform (https://judge.science.unitn.it/), exploiting VSCode shortcuts through npm to compile and run in no time! | https://github.com/Seba-T/MontresorBuilder | 0 | 0| 
| 20230127T22:33:31Z | Null | https://github.com/codingcore12/SILENT-DOC-EXPLOIT-CLEAN-ii | 1 | 0| 
| 20230127T22:31:59Z | Null | https://github.com/codingcore12/SILENT-PDF-EXPLOIT-CLEAN-ii | 1 | 0| 
| 20230127T22:30:44Z | Null | https://github.com/codingcore12/SILENT-EXCEL-XLS-EXPLOIT-CLEAN-ii | 1 | 0| 
| 20230127T21:41:03Z | This vulnerability allows remote attackers to execute arbitrary code on affected installations of PDF-XChange Editor. User interaction is required to exploit this vulnerability in that the target must visit a malicious page or open a malicious file. The specific flaw exists within the parsing of PDF files. Crafted data CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-42400 | 0 | 0| 
| 20230127T20:16:54Z | PoC contract for exploiting solana logs | https://github.com/jarry-xiao/logspammer | 0 | 0| 
| 20230127T17:53:03Z | Open source custom DLL exploit for Roblox with custom functions, level 8 execution, multi Roblox injection, and a key system. | https://github.com/plusgiant5/TaaprWareV2 | 8 | 3| 
| 20230127T13:57:30Z | This repo contain Python POC of Pentesterlab. | https://github.com/virus0devil/Pentesterlab-Exploit-POC | 0 | 0| 
| 20230127T13:57:01Z | A vulnerability, which was classified as critical, was found in SourceCodester Online Tours & Travels Management System 1.0. This affects an unknown part of the file admin/expense_report.php. The manipulation of the argument to_date leads to sql injection. It is possible to initiate the attack remotely. The exploit has CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0534 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230127T20:42:00Z | SpyMax 4.0 is and RAT Software For Remote Android Device and has alot of Features (Remote cam, Remote files and live Seceen Recoing, and More Features. This RAT Software Requires NetFrameWork 3.5 and 4 and 4.5 (For Educational Purposes Only) | https://github.com/SoftwaresForPC/SpyMax-4.0-Activated-Cracked-Download | 0 | 0| 
| 20230127T20:28:15Z | Carbon Crypter / Packer | https://github.com/carboncryptt/CarbonCrypt | 0 | 0| 
| 20230127T18:27:08Z | AsyncRat_v0.5.6 Latest Version+Source Code Download (AsyncRAT_v0.5.6 The Most PowerFul Remote Administration Tool Ever it Can Remote any Windows Machine + Disabling Windows 10&11 Defender For Ever and Also Other Windows Defeders For All Versions Of Windows System.Educational Purposes Use it For Fun.Requiers NetFrameWork 3.5 and 4 and 4.5 | https://github.com/SoftwaresForPC/AsyncRAT_v0.5.6-Latest-Version-Source-Code | 0 | 0| 
| 20230127T16:25:09Z | Null | https://github.com/dchruscielski/backdoors-zip | 0 | 0| 
| 20230127T16:13:47Z | Null | https://github.com/simranhacks/backdoor_python | 1 | 0| 
| 20230127T13:39:11Z | 👺 Backdoor Scanner for FiveM (not a addon) | https://github.com/MasterChad/backdoor-finder-fivem | 0 | 0| 
| 20230127T06:09:59Z | [ICLR2023] Distilling Cognitive Backdoor Patterns within an Image | https://github.com/HanxunH/CognitiveDistillation | 4 | 0| 
| 20230127T04:50:28Z | Null | https://github.com/brahmaputra7/allow-backdoor | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230127T18:33:44Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 614 | 111| 
| 20230127T15:32:00Z | Symbolic Execution engine for finding bugs in EO programs | https://github.com/polystat/symex | 0 | 0| 
| 20230127T05:00:44Z | Concolic (Dynamic Symbolic Execution) with Angr demo on a simple binary. | https://github.com/bobby-valenzuela/AngrConcolicDemo | 0 | 0| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230127T19:26:53Z | find relevant security papers published in the top-4 conferences (S&P, USENIX, CCS, NDSS) | https://github.com/Kyle-Kyle/top4grep | 31 | 2| 
| 20230127T06:02:42Z | StealthyIMU: Stealing Permission-protected Private Information From Smartphone Voice Assistant Using Zero-Permission Sensors, NDSS 2023 | https://github.com/Samsonsjarkal/StealthyIMU | 7 | 1| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230127T23:40:21Z | SeamFuzz Artifact repository for ICSE 2023 | https://github.com/kupl/SeamFuzz-Artifact | 0 | 0| 
| 20230127T23:20:15Z | Full Stack Developer, Open-source Maintainer & Contributor, Software Engineer  | https://github.com/shivalinggg/fuzzy-dollop | 0 | 0| 
| 20230127T22:26:40Z | Fuzzy logic tech blog | https://github.com/mesies/fuzzy-logic | 0 | 0| 
| 20230127T21:01:21Z | fuzzy clock | https://github.com/adamjedrzejewski/fuzzy | 0 | 0| 
| 20230127T20:38:10Z | Null | https://github.com/mahrukhaleem70/fuzzy-octo-umbrella | 0 | 0| 
| 20230127T18:58:45Z | Semantic LiDAR Fuzzer | https://github.com/less-lab-uva/semLidarFuzz | 2 | 0| 
| 20230127T13:48:21Z | Welcome to Hoyt%s Windows Fuzzing Repo | https://github.com/xsscx/windows | 3 | 0| 
| 20230127T13:46:04Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 3365 | 675| 
| 20230127T12:17:33Z | Null | https://github.com/Fiorela141/fuzzy-eureka | 0 | 0| 
| 20230127T11:52:50Z | Custom Scripts write on Python for scaning, fuzzing, enumeration, etc... | https://github.com/RobertMuriel/Pentesting_Python_Scripts | 0 | 0| 



# 日更新程序
