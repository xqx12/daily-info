# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230128 | Obfuscation Detection 一个用于自动检查二进制文件中的混淆代码和状态机的脚本/工具/Binary Ninja插件 | https://github.com/mrphrazer/obfuscation_detection| 
| 20230127 | CVE-2023-24055:KeePass 配置文件具有写入权限的攻击者可以修改它并注入恶意触发器,可以泄露密码 | https://github.com/alt3kx/CVE-2023-24055_PoC| 
| 20230127 | 利用 Windows CryptoAPI 中的欺骗漏洞(CVE-2022-34689),Poc的攻击分为两种:一种利用 Chrome v48,另一种侧重于crypt32.dll中易受攻击的MD5 | https://github.com/akamai/akamai-security-research/tree/main/PoCs/CVE-2022-34689| 
| 20230127 | openemr中的未授权任意读取漏洞以及未授权rce的漏洞分析(XSS鉴权,文件上传+LFI) | https://www.sonarsource.com/blog/openemr-remote-code-execution-in-your-healthcare-system/| 
| 20230127 | 通过利用一些硬编码在Yellowfin BI里的秘钥信息(例如私钥),用其生成后完成鉴权实现RCE | http://blog.assetnote.io/2023/01/24/yellowfin-auth-bypass-to-rce/| 
| 20230127 | MyBB <= 1.8.31中的RCE利用链:先通过留言板xss让admin的账号发search API的请求触发sqli注入 再通过修改template实现RCE | https://swarm.ptsecurity.com/mybb-1-8-31-remote-code-execution-chain/| 
| 20230127 | 通过TpAllocWork,TpPostWork,TpReleaseWork间接回调调用LoadLibrary以规避ETWTI堆栈跟踪 | http://0xdarkvortex.dev/proxying-dll-loads-for-hiding-etwti-stack-tracing/| 
| 20230127 | 隐藏于USB介质中的PlugX变体 | https://unit42.paloaltonetworks.com/plugx-variants-in-usbs/| 
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


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230128 | 成体系：大论文的另一关键环节 | https://mp.weixin.qq.com/s/GK6VncT-WbHz0Euuf7drZA| 
| 20230126 | 记一次Webshell检测引擎绕过测试 | https://tttang.com/archive/1875/| 
| 20230125 | Fiora：漏洞PoC框架Nuclei的图形版 | https://github.com/bit4woo/Fiora| 
| 20230125 | 各种架构ELF后门生成工具 | https://xz.aliyun.com/t/12054| 
| 20230125 | DARPA的可解释人工智能程序 | https://mp.weixin.qq.com/s/F9Dtvrlu8AU15HhTVQQojQ| 
| 20230124 | SecWiki周刊（第464期) | https://www.sec-wiki.com/weekly/464| 
| 20230124 | CVE-2022-41080_41082 Microsoft Exchange Server OWASSRF远程... | https://mp.weixin.qq.com/s/Fl7oz6VXI8k5Qn0MOk61aw| 
| 20230124 | 自动化提取恶意文档中的shellcode | https://mp.weixin.qq.com/s/xEHnaBmpH0zrhMKBvjxoGw| 
| 20230119 | 顶会论文写作建议（上）：宏观布局，避免“hard to follow” | https://mp.weixin.qq.com/s/kberQa8ss7l2gh9PAx_cSQ| 
| 20230119 | 从CISA KEV看海量漏洞管理方法 | https://mp.weixin.qq.com/s/X5J4gYanCGrGMJ9Yp6J8tQ| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230128T11:16:53Z | CVE-2021-43798 | This script implements a lab automation where I exploit CVE-2021-43798 to steal user secrets and then gain privileges on a Linux system. | https://github.com/mauricelambert/LabAutomationCVE-2021-43798 | | 
| 20230128T11:01:56Z | CVE-2022-44789 | Null | https://github.com/alalng/CVE-2022-44789 | | 
| 20230128T06:40:57Z | CVE-2020-24371 | lgc.c in Lua 5.4.0 mishandles the interaction between barriers and the sweep phase, leading to a memory access violation involving collectgarbage. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-24371 | | 
| 20230128T06:35:39Z | CVE-2020-14947 | OCS Inventory NG 2.7 allows Remote Command Execution via shell metacharacters to require/commandLine/CommandLine.php because mib_file in plugins/main_sections/ms_config/ms_snmp_config.php is mishandled in get_mib_oid. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-14947 | | 
| 20230128T06:35:25Z | CVE-2023-23014 | Cross Site Scripting (XSS) vulnerability in InventorySystem thru commit e08fbbe17902146313501ed0b5feba81d58f455c (on Apr 23, 2021) via edit_store_name and edit_active inputs in file InventorySystem.php. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-23014 | | 
| 20230128T06:35:21Z | CVE-2023-23010 | Cross Site Scripting (XSS) vulnerability in Ecommerce-CodeIgniter-Bootstrap thru commit d5904379ca55014c5df34c67deda982c73dc7fe5 (on Dec 27, 2022), allows attackers to execute arbitrary code via the languages and trans_load parameters in file add_product.php. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-23010 | | 
| 20230128T06:35:17Z | CVE-2022-45748 | An issue was discovered with assimp 5.1.4, a use after free occurred in function ColladaParser::ExtractDataObjectFromChannel in file /code/AssetLib/Collada/ColladaParser.cpp. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-45748 | | 
| 20230128T06:35:13Z | CVE-2022-47012 | Use of uninitialized variable in function gen_eth_recv in GNS3 dynamips 0.2.21. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-47012 | | 
| 20230128T06:35:10Z | CVE-2022-42410 | This vulnerability allows remote attackers to execute arbitrary code on affected installations of PDF-XChange Editor. User interaction is required to exploit this vulnerability in that the target must visit a malicious page or open a malicious file. The specific flaw exists within the parsing of PGM files. Crafted data CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-42410 | | 
| 20230128T06:35:06Z | CVE-2022-42409 | This vulnerability allows remote attackers to disclose sensitive information on affected installations of PDF-XChange Editor. User interaction is required to exploit this vulnerability in that the target must visit a malicious page or open a malicious file. The specific flaw exists within the parsing of PDF files. Craf CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-42409 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230128T13:31:27Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10246 | 343| 
| 20230128T09:06:09Z | An open-source Chinese font derived from Klee One and Ysabeau and LXGW WenKai.一款适合中日文混排的开源中文字体，基于 Ysabeau、 Klee One、霞鹜文楷衍生。 | https://github.com/NoHeartPen/QiushuiShotai | 12 | 0| 
| 20230127T15:36:18Z | 「缝合楷」：将「霞鹜文楷 GB」「芫荽」「Klee One」等字体相互合并制成的以各地字形为主的 Klee One 衍生字体。 | https://github.com/lxgw/FusionKai | 20 | 0| 
| 20230127T14:59:20Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 27 | 2| 
| 20230127T14:43:54Z | Kleenapp | https://github.com/spookyman69/kleenapp | 0 | 0| 
| 20230127T08:51:25Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 201 | 1| 
| 20230127T02:30:22Z | Null | https://github.com/ArnavAmbe/ARNAVCS1KLEE | 0 | 0| 
| 20230123T23:27:26Z | ⬇️ File Upload/sharing application, used by thousands of webmasters since 2007.  | https://github.com/kleeja-official/kleeja | 168 | 50| 
| 20230122T11:55:43Z | Null | https://github.com/Hvoya/klee-presense-bot | 0 | 0| 
| 20230121T06:51:03Z | Null | https://github.com/rajashekharpendli/kleeteam | 0 | 0| 


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
| 20230128T13:33:56Z | Null | https://github.com/codingcore12/SILENT-EXCEL-XLS-EXPLOIT-CLEAN-fd | 1 | 0| 
| 20230128T13:33:06Z | Null | https://github.com/codingcore12/SILENT-PDF-EXPLOIT-CLEAN-fd | 1 | 0| 
| 20230128T13:32:05Z | Null | https://github.com/codingcore12/SILENT-DOC-EXPLOIT-CLEAN-fd | 1 | 0| 
| 20230128T13:32:04Z | Null | https://github.com/Alfie6193/Alfies-exploit | 0 | 0| 
| 20230128T13:30:08Z | Alfies exxploit is a exploit made by Alfie | https://github.com/Alfie6193/Alfies-exxploit | 0 | 0| 
| 20230128T12:11:20Z | hi my discord name: Cips#9611 my youtube name: @_Cathe my dicord server: https://discord.gg/zzxF82DHpX | https://github.com/RobloxExploitScripter/RobloxExploitScripts | 1 | 0| 
| 20230128T11:16:53Z | This script implements a lab automation where I exploit CVE-2021-43798 to steal user secrets and then gain privileges on a Linux system. | https://github.com/mauricelambert/LabAutomationCVE-2021-43798 | 0 | 0| 
| 20230128T10:48:18Z | Null | https://github.com/vegaban/drp-exploits | 0 | 0| 
| 20230128T09:07:18Z | my first exploit i made  | https://github.com/Br4ubrunru/my-roblox-script-GUI | 0 | 0| 
| 20230128T02:58:01Z | An all-in-one hacking tool to remotely exploit Android devices using ADB and Metasploit-Framework to get a Meterpreter session. | https://github.com/AzeemIdrisi/PhoneSploit-Pro | 401 | 64| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230128T13:37:31Z | /root/.ssh/authorized_keys evil file watchdog with ebpf tracepoint hook. | https://github.com/Esonhugh/sshd_backdoor | 63 | 8| 
| 20230128T08:08:59Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 389 | 74| 
| 20230128T05:15:17Z | Quick RDP/VPS Config Tools , Change Password, Create Hidden User, Create Backdoor, Disable or Enable Task Manager, Google Chrome Install, Disable Computer Management | https://github.com/fhnirob888/RDP-VPS-Tools-by-FHNirob | 0 | 0| 
| 20230128T03:10:33Z | [ICLR2023] Distilling Cognitive Backdoor Patterns within an Image | https://github.com/HanxunH/CognitiveDistillation | 5 | 0| 
| 20230127T20:42:00Z | SpyMax 4.0 is and RAT Software For Remote Android Device and has alot of Features (Remote cam, Remote files and live Seceen Recoing, and More Features. This RAT Software Requires NetFrameWork 3.5 and 4 and 4.5 (For Educational Purposes Only) | https://github.com/SoftwaresForPC/SpyMax-4.0-Activated-Cracked-Download | 0 | 0| 
| 20230127T20:28:15Z | Carbon Crypter / Packer | https://github.com/carboncryptt/CarbonCrypt | 0 | 0| 
| 20230127T18:27:08Z | AsyncRat_v0.5.6 Latest Version+Source Code Download (AsyncRAT_v0.5.6 The Most PowerFul Remote Administration Tool Ever it Can Remote any Windows Machine + Disabling Windows 10&11 Defender For Ever and Also Other Windows Defeders For All Versions Of Windows System.Educational Purposes Use it For Fun.Requiers NetFrameWork 3.5 and 4 and 4.5 | https://github.com/SoftwaresForPC/AsyncRAT_v0.5.6-Latest-Version-Source-Code | 0 | 0| 
| 20230127T16:25:09Z | Null | https://github.com/dchruscielski/backdoors-zip | 0 | 0| 
| 20230127T16:13:47Z | Null | https://github.com/simranhacks/backdoor_python | 1 | 0| 
| 20230127T13:39:11Z | 👺 Backdoor Scanner for FiveM (not a addon) | https://github.com/MasterChad/backdoor-finder-fivem | 0 | 0| 


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
| 20230128T11:15:06Z | StealthyIMU: Stealing Permission-protected Private Information From Smartphone Voice Assistant Using Zero-Permission Sensors, NDSS 2023 | https://github.com/Samsonsjarkal/StealthyIMU | 8 | 1| 
| 20230128T03:32:16Z | A curated list of Meachine learning Security & Privacy papers published in security top-4 conferences (IEEE S&P, ACM CCS, USENIX Security and NDSS). | https://github.com/gnipping/Awesome-ML-SP-Papers | 24 | 2| 
| 20230127T19:26:53Z | find relevant security papers published in the top-4 conferences (S&P, USENIX, CCS, NDSS) | https://github.com/Kyle-Kyle/top4grep | 31 | 2| 
| 20230119T16:29:30Z | Null | https://github.com/tokunagak/NDSS | 0 | 0| 
| 20230119T14:19:34Z | Code for the NDSS%23 paper %DARWIN: Survival of the Fittest Fuzzing Mutators% | https://github.com/TUDA-SSL/DARWIN | 1 | 0| 
| 20230118T07:06:06Z | Anomaly Detection in the Open World: Normality Shift Detection, Explanation, and Adaptation (NDSS%23). | https://github.com/dongtsi/OWAD | 5 | 1| 
| 20230116T10:17:44Z | ConfFuzz NDSS Data Set | https://github.com/conffuzz/conffuzz-ndss-data | 1 | 1| 
| 20230115T02:56:21Z | A Summary of Vulnerabilities Found in the BlockScope NDSS%23 Paper | https://github.com/VPRLab/BlkVulnReport | 2 | 0| 
| 20230113T21:10:57Z | DroneSecurity (NDSS 2023) | https://github.com/RUB-SysSec/DroneSecurity | 1 | 0| 
| 20230111T23:04:46Z | A Summary of Vulnerabilities Found in the BlockScope NDSS%23 Paper | https://github.com/VPRLab/BS_VulnReport | 2 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230128T12:50:51Z | Fuzzy Logic Operations Toolkit | https://github.com/yibocat/FuzzyKit | 0 | 0| 
| 20230128T12:46:17Z | Null | https://github.com/bumchenko/fuzzy-journey | 0 | 0| 
| 20230128T12:37:37Z | Null | https://github.com/Nyanjuimarvin/Fuzz | 0 | 0| 
| 20230128T11:57:18Z | PID vs Fuzzy Logic Cruise Control comparison for a car with Tesla model 3 properties. | https://github.com/Athok98/PID_vs_Fuzzy_Logic_Cruise_Control_comparison | 0 | 0| 
| 20230128T11:38:00Z | Null | https://github.com/Hamzasaleem7773/fuzzy-octo-winner | 0 | 0| 
| 20230128T11:22:36Z | Null | https://github.com/SALVIN77/fuzzy-octo-carnival-salvinkj | 0 | 0| 
| 20230128T10:16:53Z | Null | https://github.com/JOpFuzzer/JOpFuzzer-demo | 0 | 0| 
| 20230128T06:10:41Z | Null | https://github.com/amatoria/fuzzy-fortnight | 1 | 0| 
| 20230128T04:11:23Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8299 | 1807| 
| 20230128T02:34:39Z | For this project, we will create a MySQL database utilizing the Maven Fuzzy Factory dataset. By utilizing SQL, we will gather, analyze, and evaluate the website traffic and performance data of a simulated e-commerce business. Our goal is to evaluate the effectiveness of different marketing strategies to optimize expenses and raise the revenue. | https://github.com/sh-jain/MySQL_MavenFuzzyFactory_Project | 0 | 0| 



# 日更新程序
