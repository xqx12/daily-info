# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230128 | Obfuscation Detection 一个用于自动检查二进制文件中的混淆代码和状态机的脚本/工具/Binary Ninja插件 | https://github.com/mrphrazer/obfuscation_detection| 
| 20230128 | Malware Theory - How Packers Work, Polymorphism and Misconceptions | https://www.youtube.com/watch?v=ESLEf66EzDk&feature=youtu.be| 
| 20230128 | 绕过OGNL注入保护机制(包括Struts和Atlassian Confluence使用一些特殊的机制) | http://github.blog/2023-01-27-bypassing-ognl-sandboxes-for-fun-and-charities/| 
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
| 20230129T02:18:13Z | CVE-2023-0563 | A vulnerability classified as problematic has been found in PHPGurukul Bank Locker Management System 1.0. This affects an unknown part of the file add-locker-form.php of the component Assign Locker. The manipulation of the argument ahname leads to cross site scripting. It is possible to initiate the attack remotely. Th CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0563 | | 
| 20230129T02:18:09Z | CVE-2023-0562 | A vulnerability was found in PHPGurukul Bank Locker Management System 1.0. It has been rated as critical. Affected by this issue is some unknown functionality of the file index.php of the component Login. The manipulation of the argument username leads to sql injection. The attack may be launched remotely. The identifi CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0562 | | 
| 20230129T02:18:05Z | CVE-2021-4315 | A vulnerability has been found in NYUCCL psiTurk up to 3.2.0 and classified as critical. This vulnerability affects unknown code of the file psiturk/experiment.py. The manipulation of the argument mode leads to improper neutralization of special elements used in a template engine. The exploit has been disclosed to the  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-4315 | | 
| 20230128T19:42:56Z | CVE-2023-0561 | A vulnerability, which was classified as critical, was found in SourceCodester Online Tours & Travels Management System 1.0. Affected is an unknown function of the file /user/s.php. The manipulation of the argument id leads to sql injection. It is possible to launch the attack remotely. The exploit has been disclosed t CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0561 | | 
| 20230128T19:42:52Z | CVE-2023-0560 | A vulnerability, which was classified as critical, has been found in SourceCodester Online Tours & Travels Management System 1.0. This issue affects some unknown processing of the file admin/practice_pdf.php. The manipulation of the argument id leads to sql injection. The attack may be initiated remotely. The exploit h CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0560 | | 
| 20230128T19:42:48Z | CVE-2020-16093 | In LemonLDAP::NG (aka lemonldap-ng) through 2.0.8, validity of the X.509 certificate is not checked by default when connecting to remote LDAP backends, because the default configuration of the Net::LDAPS module for Perl is used. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-16093 | | 
| 20230128T18:54:44Z | CVE-2022-23935 | CVE-2022-23935 exploit PoC exiftool version 12.37 | https://github.com/dpbe32/CVE-2022-23935-PoC-Exploit | | 
| 20230128T11:16:53Z | CVE-2021-43798 | This script implements a lab automation where I exploit CVE-2021-43798 to steal user secrets and then gain privileges on a Linux system. | https://github.com/mauricelambert/LabAutomationCVE-2021-43798 | | 
| 20230128T11:01:56Z | CVE-2022-44789 | Null | https://github.com/alalng/CVE-2022-44789 | | 
| 20230128T06:40:57Z | CVE-2020-24371 | lgc.c in Lua 5.4.0 mishandles the interaction between barriers and the sweep phase, leading to a memory access violation involving collectgarbage. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-24371 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230129T02:16:19Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10256 | 343| 
| 20230128T20:35:19Z | Null | https://github.com/EliasPeeters/kleeschulte-landing-page | 0 | 0| 
| 20230128T19:58:31Z | An open-source Chinese font derived from Klee One and Ysabeau and LXGW WenKai.一款适合中日文混排的开源中文字体，基于 Ysabeau、 Klee One、霞鹜文楷衍生。 | https://github.com/NoHeartPen/QiushuiShotai | 13 | 0| 
| 20230127T15:36:18Z | 「缝合楷」：将「霞鹜文楷 GB」「芫荽」「Klee One」等字体相互合并制成的以各地字形为主的 Klee One 衍生字体。 | https://github.com/lxgw/FusionKai | 20 | 0| 
| 20230127T14:59:20Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 27 | 2| 
| 20230127T14:43:54Z | Kleenapp | https://github.com/spookyman69/kleenapp | 0 | 0| 
| 20230127T08:51:25Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 201 | 1| 
| 20230127T02:30:22Z | Null | https://github.com/ArnavAmbe/ARNAVCS1KLEE | 0 | 0| 
| 20230123T23:27:26Z | ⬇️ File Upload/sharing application, used by thousands of webmasters since 2007.  | https://github.com/kleeja-official/kleeja | 168 | 50| 
| 20230122T11:55:43Z | Null | https://github.com/Hvoya/klee-presense-bot | 0 | 0| 


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
| 20230129T02:18:05Z | A vulnerability has been found in NYUCCL psiTurk up to 3.2.0 and classified as critical. This vulnerability affects unknown code of the file psiturk/experiment.py. The manipulation of the argument mode leads to improper neutralization of special elements used in a template engine. The exploit has been disclosed to the  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-4315 | 0 | 0| 
| 20230129T00:50:55Z | Roblox NYveeee Private Exploit Leak3D WITH 50 FEATURES | https://github.com/Padamatto/Roblox-NYveeee-Private-Exploit-Leak3D | 29 | 0| 
| 20230129T00:50:50Z | DF2 DeaD Frontier2 PrivateCheat INCLUDING AIMBOT SOFTAIM ESP AND MORE | https://github.com/Padamatto/DF2-DeaD-Frontier2-PrivateCheat | 29 | 0| 
| 20230129T00:50:35Z | et3nol RobloxBloxFruitPrivateCheatExploitScript  | https://github.com/Watanabbe/et3nol-RobloxBloxFruitPrivateCheatExploitScript | 29 | 0| 
| 20230129T00:50:33Z | AutoFarm SonicSpeed Exploit made by hks0r3ty | https://github.com/Watanabbe/AutoFarm-SonicSpeed-Exploit | 29 | 0| 
| 20230129T00:27:41Z | These are some resources I use to exploit my brain on a daily basis | https://github.com/CY83R-3X71NC710N/Brain-Biohacking | 0 | 0| 
| 20230129T00:25:31Z | Bookmarklet exploit that can force-disable extensions installed on Chrome. Also has a very fancy GUI to manage all extensions! | https://github.com/3kh0/ext-remover | 155 | 143| 
| 20230128T23:34:31Z | Null | https://github.com/codingcore12/SILENT-DOC-EXPLOIT-CLEAN-mm | 1 | 0| 
| 20230128T23:33:44Z | Null | https://github.com/codingcore12/SILENT-PDF-EXPLOIT-CLEAN-mm | 1 | 0| 
| 20230128T23:32:48Z | Null | https://github.com/codingcore12/SILENT-EXCEL-XLS-EXPLOIT-CLEAN-mm | 1 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230129T02:51:13Z | /root/.ssh/authorized_keys evil file watchdog with ebpf tracepoint hook. | https://github.com/Esonhugh/sshd_backdoor | 108 | 12| 
| 20230128T21:10:36Z | Null | https://github.com/DerekSip/BackDoor-Exploit | 1 | 0| 
| 20230128T18:04:53Z | Null | https://github.com/nalarsawung/backdoor | 0 | 0| 
| 20230128T16:21:03Z | Carbon Crypter / Packer | https://github.com/carboncryptt/CarbonCrypt | 1 | 0| 
| 20230128T15:27:20Z | Quick RDP/VPS Config Tools , Change Password, Create Hidden User, Create Backdoor, Disable or Enable Task Manager, Google Chrome Install, Disable Computer Management | https://github.com/fhnirob888/RDP-VPS-Tools-by-FHNirob | 1 | 0| 
| 20230128T08:08:59Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 389 | 74| 
| 20230128T03:10:33Z | [ICLR2023] Distilling Cognitive Backdoor Patterns within an Image | https://github.com/HanxunH/CognitiveDistillation | 5 | 0| 
| 20230127T20:42:00Z | SpyMax 4.0 is and RAT Software For Remote Android Device and has alot of Features (Remote cam, Remote files and live Seceen Recoing, and More Features. This RAT Software Requires NetFrameWork 3.5 and 4 and 4.5 (For Educational Purposes Only) | https://github.com/SoftwaresForPC/SpyMax-4.0-Activated-Cracked-Download | 0 | 1| 
| 20230127T18:27:08Z | AsyncRat_v0.5.6 Latest Version+Source Code Download (AsyncRAT_v0.5.6 The Most PowerFul Remote Administration Tool Ever it Can Remote any Windows Machine + Disabling Windows 10&11 Defender For Ever and Also Other Windows Defeders For All Versions Of Windows System.Educational Purposes Use it For Fun.Requiers NetFrameWork 3.5 and 4 and 4.5 | https://github.com/SoftwaresForPC/AsyncRAT_v0.5.6-Latest-Version-Source-Code | 0 | 0| 
| 20230127T16:25:09Z | Null | https://github.com/dchruscielski/backdoors-zip | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230127T18:33:44Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 614 | 111| 
| 20230127T15:32:00Z | Symbolic Execution engine for finding bugs in EO programs | https://github.com/polystat/symex | 0 | 0| 
| 20230127T05:00:44Z | Concolic (Dynamic Symbolic Execution) with Angr demo on a simple binary. | https://github.com/bobby-valenzuela/AngrConcolicDemo | 0 | 0| 
| 20230126T13:42:11Z | Bachelor thesis, attempting decompilation using symbolic execution | https://github.com/lokegustafsson/thesis-decompilation | 3 | 0| 
| 20230126T10:28:22Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3287 | 468| 
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
| 20230129T02:38:24Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8300 | 1807| 
| 20230129T02:29:52Z | Null | https://github.com/Bosmade008/fuzzy-fiesta | 0 | 0| 
| 20230129T02:25:55Z | Using GPT-3 as a back-end, called via HTML attributes. | https://github.com/yoheinakajima/fuzzy.js | 1 | 0| 
| 20230129T02:20:21Z | Null | https://github.com/moomoomoo123/fuzzy-tribble | 0 | 0| 
| 20230129T01:34:23Z | Null | https://github.com/aatifkazmi/fuzzy | 0 | 0| 
| 20230129T01:07:10Z | A tiny, efficient fuzzy search that doesn%t suck | https://github.com/leeoniya/uFuzzy | 2033 | 34| 
| 20230128T23:49:43Z | Null | https://github.com/kazitipu/fuzzy-happiness | 0 | 0| 
| 20230128T19:41:14Z | brute force get requests to specified number | https://github.com/natementze/directory_fuzzing_in_c | 1 | 0| 
| 20230128T18:39:28Z | MSU Marketplace web app | https://github.com/spectrumstrike/fuzzy-fortnight | 0 | 0| 
| 20230128T18:18:02Z | Null | https://github.com/Mbuyamba/fuzzy-fortnight | 0 | 0| 



# 日更新程序
