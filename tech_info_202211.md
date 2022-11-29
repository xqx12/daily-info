# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221128 | 基于IO_FILE的高版本glibc利用链 | https://tttang.com/archive/1845/| 
| 20221128 | 基于污点分析的静态分析被应用于堆漏洞检测 | https://github.com/CoolerVoid/heap_detective| 
| 20221128 | 基于patch对TP-Link一处未初始化访问漏洞的分析和利用，并发现仍存在其他受此漏洞影响的固件版本。 | https://github.com/b1ack0wl/vulnerability-write-ups/blob/master/TP-Link/WR940N/112022/Part1.md| 
| 20221128 | Chrome浏览器Blink组件UAF漏洞（CVE-2022-3654）细节，由project-zero的glazunov发现，是由于CVE-2022-3199漏洞错误修复导致的补丁绕过。 | https://bugs.chromium.org/p/project-zero/issues/detail?id=2358| 
| 20221128 | 利用vBulletin的一个N-day对象注入漏洞实现任意PHP代码执行。 | https://www.reddit.com/r/netsec/comments/z5cql6/exploiting_an_nday_vbulletin_php_object_injection/| 
| 20221128 | Kubeeye，一款Kubernetes漏洞检测工具，能够给出修复建议，支持客制化。 | https://www.kitploit.com/2022/11/kubeeye-tool-to-find-various-problems.html| 
| 20221128 | Python的格式化字符串如果攻击者可控的话，可能会导致信息泄漏。 | http://lucumr.pocoo.org/2016/12/29/careful-with-str-format/| 
| 20221128 | 介绍了Jackalope的基本使用方法，对Damn Vulnerable C Program中的示例程序进行模糊测试 | https://www.youtube.com/watch?v=rXbaHSXiCtg&feature=youtu.be| 
| 20221128 | 详解JDK的Runtime.getRuntime().exec(String)的原理：会先将输入字符串以\x20\t\n\r\f进行split，之后再作为Process的argv进行命令执行。 | http://www.freebuf.com/vuls/350760.html| 
| 20221128 | Sock5 反向代理工具 | https://github.com/Coldzer0/ReverseSock5Proxy| 
| 20221128 | 攻击智能手表以使其显示自定义内容 | https://cybervelia.com/?p=1380| 
| 20221128 | 用Jenkins来自动化构建红队工具 | https://http418infosec.com/offsecops-using-jenkins-for-red-team-tooling/| 
| 20221128 | MITRE ATT&CK Version 12 新特性 | https://ahead.feedly.com/posts/introduction-to-mitre-attack-featuring-version-12-2022| 
| 20221128 | Koxic 勒索软件在韩国传播 | http://paper.seebug.org/2027/| 
| 20221128 | ThreatFox：开源威胁情报共享平台 | https://github.com/abusech/ThreatFox| 
| 20221128 | THREATINT_PROCESS_SYSCALL_USAGE：Windows 23H2 引入新的 ETW Event 缓解漏洞利用 | https://windows-internals.com/an-end-to-kaslr-bypasses/| 
| 20221128 | AWS AppSyncs的confused deputy problem漏洞的细节，该漏洞允许一个恶意租户通过AppSyncs的访问别的租户的资源 | https://thehackernews.com/2022/11/researchers-detail-appsync-cross-tenant.html| 
| 20221125 | 浅谈JspWebshell之编码 | https://tttang.com/archive/1840/| 
| 20221121 | ZK框架权限绕过导致R1Soft Server Backup Manager RCE并接管Agent | https://tttang.com/archive/1833/| 
| 20221121 | Wordpress 插件 woocommerce 插件 SQL 注入漏洞分析 | http://paper.seebug.org/2023/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221128 | AFL系模糊器中Havoc变异策略研究与改进 | https://mp.weixin.qq.com/s/A2Dk6WOZo7FZ_3bFRSsk-Q| 
| 20221128 | NAUTILUS：面向语法的灰盒模糊测试方法 | https://mp.weixin.qq.com/s/l-dpLkrB_GaiBkp_YHnIXQ| 
| 20221128 | 2022年中国安全技术成熟度曲线 | https://mp.weixin.qq.com/s/7nxdi3UlEcJXMi53gJOzSw| 
| 20221128 | SecWiki周刊（第456期) | https://www.sec-wiki.com/weekly/456| 
| 20221128 | CobaltStrike4.5 分析总结 | https://mp.weixin.qq.com/s/K47FXTMEWfB_474aHAGU5g| 
| 20221128 | MITRE ATT&CK 第五轮评估结果发布 | https://mp.weixin.qq.com/s/mEKMKfL3DjtkEvFCKYWNLA| 
| 20221127 | JAVA开发中涉及的基础安全问题和解决方法初探 | https://xz.aliyun.com/t/11890| 
| 20221126 | CVE-2022-42920 BCEL 任意文件写漏洞 | https://xz.aliyun.com/t/11866| 
| 20221126 | 美国开源软件安全评价方法体系分析 | https://mp.weixin.qq.com/s/q_R76IME0FnX0fwgS7R8Bw| 
| 20221125 | 图视角下的信息抽取技术研究 | https://mp.weixin.qq.com/s/EnsnauMumycUFo_iSWoyXQ| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20221129T02:30:37Z | CVE-2022-3236 | Unauthenticated rce in sophos User Portal and Webadmin components mass exploitation tool | https://github.com/Adynervi/CVE-2022-3236-MASS-RCE | | 
| 20221128T17:54:21Z | CVE-2020-0796 | PoC for triggering buffer overflow via CVE-2020-0796 | https://github.com/eerykitty/CVE-2020-0796-PoC | | 
| 20221128T14:38:12Z | CVE-2022-22965 | CVE-2022-22965 proof of concept | https://github.com/clemoregan/SSE4-CVE-2022-22965 | | 
| 20221128T14:28:07Z | CVE-2022-22965 | Null | https://github.com/ClemExp/CVE-2022-22965-PoC | | 
| 20221128T13:11:27Z | cve-2022-41352 | Zimbra <9.0.0.p27 RCE | https://github.com/Cr4ckC4t/cve-2022-41352-zimbra-rce | | 
| 20221128T09:23:41Z | CVE-2021-43258 | ChurchInfo 1.2.13-1.3.0 Remote Code Execution Exploit | https://github.com/MRvirusIR/CVE-2021-43258 | | 
| 20221128T09:23:36Z | CVE-2022-22971 | Null | https://github.com/tchize/CVE-2022-22971 | | 
| 20221128T09:23:26Z | CVE-2022-22963 | Null | https://github.com/dr6817/CVE-2022-22963 | | 
| 20221128T03:50:10Z | CVE-2021-33558 | CVE-2021-33558 POC | https://github.com/anldori/CVE-2021-33558 | | 
| 20221127T10:58:26Z | cve-2021-29447 | Null | https://github.com/mega8bit/exploit_cve-2021-29447 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221129T02:06:07Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 9460 | 322| 
| 20221129T01:48:54Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2115 | 598| 
| 20221128T11:57:51Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 268 | 49| 
| 20221128T05:36:33Z | Null | https://github.com/luckyjc8/logviewer_klee | 0 | 0| 
| 20221128T03:16:02Z | FastKLEE: Faster Symbolic Execution via Reducing Redundant Bound Checking of Type-Safe Pointers | https://github.com/haoxintu/FastKLEE | 12 | 1| 
| 20221127T12:27:03Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 147 | 1| 
| 20221127T12:16:35Z | Config files for my GitHub profile. | https://github.com/KleeSup/KleeSup | 0 | 0| 
| 20221127T04:19:59Z | हार्ड ड्राइव क्लीनर - चयनित हार्ड ड्राइव पर स्थान साफ़ करने के लिए PowerShell स्क्रिप्ट। | https://github.com/jimrtyler/hi-haard-draiv-kleenar | 0 | 0| 
| 20221126T15:22:50Z | Null | https://github.com/AnnaKopejkina/KLEE | 0 | 0| 
| 20221126T01:02:36Z | Null | https://github.com/ElRegioMau/KeepKleenAndroid | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221128T19:50:34Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 274 | 66| 
| 20221128T15:48:44Z | Calumet S2EBPR full-scale pilot | https://github.com/mckfarm/calumet_s2ebpr | 0 | 0| 
| 20221128T13:33:16Z | Null | https://github.com/wayline89/s2exo3 | 0 | 0| 
| 20221128T08:38:41Z | Spacecraft Simulation Environment Core codes | https://github.com/ut-issl/s2e-core | 25 | 4| 
| 20221125T07:18:48Z | Documents for Spacecraft Simulation Environment | https://github.com/ut-issl/s2e-documents | 6 | 3| 
| 20221124T12:21:32Z | Your S2E project management tools. Visit https://s2e.systems/docs to get started. | https://github.com/S2E/s2e-env | 83 | 45| 
| 20221123T16:17:12Z | Repository del progetto di test automatici per i partner mancanti, aggiornato alla versione uiPath-non legacy.  | https://github.com/AndreaMazzucchelliS2E/S2E_TestingAutomatico_PM_2.0 | 0 | 0| 
| 20221123T15:48:11Z |  Repository del progetto di test automatici per il partner BPB, aggiornato alla versione uiPath-non legacy. | https://github.com/AndreaMazzucchelliS2E/S2E_TestingAutomatico_BPB_2.0 | 0 | 0| 
| 20221107T13:09:33Z | ( Code = GitHub = Jenkins = EC2 = Docker ) a simple DevOps project which will require My Codes to be pushed GitHub which will then be passed for continuous build to Jenkins and then deployed to Amazon EC2 and then to Docker for containerization | https://github.com/skills59/DevOps-s2e2 | 0 | 0| 
| 20221107T09:16:04Z | The Chef symbolic execution platform, based off S2E | https://github.com/dslab-epfl/chef | 6 | 2| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221129T02:22:19Z | 🔫 Valorant Cheat External Public Relesase , Aimbot + Esp + Skin Changers  | https://github.com/Fnoberz/Valorant.External | 48 | 25| 
| 20221129T01:22:24Z | Hourly updated database of exploit and exploitation reports | https://github.com/gmatuz/inthewilddb | 114 | 11| 
| 20221129T01:09:18Z | Null | https://github.com/codingcore12/SILENT-DOC-EXPLOIT-CLEAN-2n | 1 | 0| 
| 20221129T01:07:45Z | Null | https://github.com/codingcore12/SILENT-EXCEL-XLS-EXPLOIT-CLEAN-2n | 1 | 0| 
| 20221129T01:06:32Z | Null | https://github.com/codingcore12/SILENT-PDF-EXPLOIT-CLEAN-2n | 1 | 0| 
| 20221129T00:24:09Z | KeyLess Nyve RobloxExploit Over 10 FEATURES | https://github.com/ahmicstasiow/Nyve-Keyless-Roblox-Premium-Exploit | 0 | 0| 
| 20221129T00:21:37Z | Useful functions for exploits | https://github.com/NinetyUnderScore/ExLib | 0 | 0| 
| 20221129T00:21:29Z | Roblox Eclipseware Exploits over 50 in one program | https://github.com/ahmicstasiow/EclipseWare-Free-Roblox-Exploits-v1.7 | 0 | 0| 
| 20221129T00:21:13Z | Create a .EXE archive from your file or convert an existing archive to the .XLS format with this Silent XLS Exploit Builder generator. You can either upload your file or provide us a URL that will point to a file or archive and the conversion to the .XLS format will start right away. | https://github.com/0x414141414/SILENT-XLL-EXCEL-EXPLOIT | 0 | 0| 
| 20221128T22:14:09Z | Null | https://github.com/Diana-fv/API_Exploitation | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221128T23:07:30Z | Hello/hi to all those who you see this repository!                                I share with you this ETH drainer for free (please use it for educational purposes), I am a teacher and I prefer to share my knowledge than to take profit from it, this one has no backdoors and is not obfuscated you can check it by yourself, I hope you will enjoy it ! | https://github.com/G2Ski/ETH-DrainerV4 | 0 | 0| 
| 20221128T22:35:05Z | Thefatrat a massive exploiting tool : Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack and etc . This tool compiles a malware with popular payload and then the compiled malware can be execute on windows, android, mac . The malware that created with this tool also have an ability to bypass most AV software protection . | https://github.com/screetsec/TheFatRat | 7127 | 2055| 
| 20221128T22:18:39Z | Invisible, customizable backdoor for Minecraft Spigot Plugins. | https://github.com/ThiccIndustries/Minecraft-Backdoor | 147 | 27| 
| 20221128T16:38:08Z | Defending Against Backdoor Attacks by Layer-wise Feature Analysis | https://github.com/anonymized1/DBALFA | 0 | 0| 
| 20221128T15:36:25Z | Creating a backdoor trojan to connect Ubuntu user to Kali Linux | https://github.com/sallyeo/ethicalHack | 0 | 0| 
| 20221128T14:16:42Z | Null | https://github.com/Timothek2112/LastBackdoor | 0 | 0| 
| 20221128T13:39:21Z | Null | https://github.com/Xoma-MDK/Backdoor-py | 0 | 0| 
| 20221128T12:54:51Z | Null | https://github.com/nyu-ce-projects/stealthy-syntactical-backdoor-attack | 2 | 0| 
| 20221128T12:53:22Z | Natural Backdoor Dataset, inclouding t-shirt, hat, apple, glass | https://github.com/backdoorrrr/Natural-Backdoor-Dataset | 0 | 0| 
| 20221128T02:32:00Z | Villain is a Windows & Linux backdoor generator and multi-session handler that allows users to connect with sibling servers (other machines running Villain) and share their backdoor sessions, handy for working as a team. | https://github.com/t3l3machus/Villain | 606 | 129| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221129T01:48:54Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2115 | 598| 
| 20221128T16:22:50Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 26 | 5| 
| 20221128T16:22:44Z | Compiled Sail ISA snapshots for the Isla symbolic execution tool | https://github.com/rems-project/isla-snapshots | 2 | 1| 
| 20221128T14:41:04Z | Symbolic execution engine for .NET Core | https://github.com/VSharp-team/VSharp | 34 | 21| 
| 20221128T11:36:15Z | Simple interpreter and symbolic executor designed for fast prototyping of symbolic execution algorithms. Cloned from https://gitlab.fi.muni.cz/xchalup4/slowbeast | https://github.com/staticafi/sbt-slowbeast | 0 | 0| 
| 20221128T10:12:05Z | The symbolic execution engine powering the K Framework | https://github.com/runtimeverification/haskell-backend | 180 | 44| 
| 20221128T08:35:27Z | Open-source symbolic execution framework: https://maat.re | https://github.com/trailofbits/maat | 505 | 28| 
| 20221128T07:42:07Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 595 | 106| 
| 20221128T03:16:02Z | FastKLEE: Faster Symbolic Execution via Reducing Redundant Bound Checking of Type-Safe Pointers | https://github.com/haoxintu/FastKLEE | 12 | 1| 
| 20221127T13:19:11Z | A combined disassembler/static analysis/symbolic execution/debugger framework. | https://github.com/marirs/vivisect-rs | 0 | 0| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221128T01:33:40Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 61 | 15| 
| 20221124T22:56:31Z | Null | https://github.com/bluescorpian/ndsscripts | 0 | 0| 
| 20221120T12:58:20Z | Source code for our NDSS%18 paper %Automated Website Fingerprinting through Deep Learning% | https://github.com/DistriNet/DLWF | 71 | 36| 
| 20221120T07:30:40Z | A curated list of Meachine learning Security & Privacy papers published in security top-4 conferences (IEEE S&P, ACM CCS, USENIX Security and NDSS). | https://github.com/gnipping/Awesome-ML-SP-Papers | 20 | 2| 
| 20221113T08:41:56Z | Null | https://github.com/Kitiyaparnnn/NDSS-Software | 0 | 0| 
| 20221110T05:25:19Z | Null | https://github.com/nosdsdfs/ndsssdss | 0 | 0| 
| 20221108T11:45:41Z | Statistics of acceptance rate for the top conferences: Oakland, CCS, USENIX Security, NDSS. | https://github.com/liupuz/Computer-Security-Conference-Acceptance-Rate | 2 | 0| 
| 20221107T09:35:54Z | Repository for synthCT framework (NDSS%22) | https://github.com/FPSG-UIUC/synthCT | 6 | 1| 
| 20221103T19:57:01Z | Home of the 2023 NDSS Workshop on Binary Analysis Research | https://github.com/bar2023/bar2023.github.io | 0 | 1| 
| 20221103T02:39:50Z | Null | https://github.com/sgwguagua/ndss | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221129T02:38:43Z | Null | https://github.com/vsviryd777/fuzzbuzz1 | 0 | 0| 
| 20221129T02:35:25Z | Null | https://github.com/Tiltedtable/fuzzy-lamp | 0 | 0| 
| 20221129T01:55:37Z | Null | https://github.com/wolfejw86/fuzzy-table | 0 | 0| 
| 20221129T01:53:10Z | Null | https://github.com/morgankn/fuzzy-funicular | 0 | 0| 
| 20221129T01:05:54Z | Null | https://github.com/stanmanga79/fuzzy-octo-dollop-project-11282022 | 0 | 0| 
| 20221129T00:49:33Z | Implementação de controlador Fuzzy - Desafio da disciplina Introdução à Inteligência Artificial pelo mestrado do Programa de Pós-Graduação em Mecatrônica da Universidade Federal da Bahia. | https://github.com/jhaidan42/controlador_fuzzy | 0 | 0| 
| 20221128T22:45:59Z | Null | https://github.com/mateus-ceccagno/futebol-americano-fuzzy | 0 | 0| 
| 20221128T14:54:04Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 77 | 22| 
| 20221128T13:45:39Z | TCP 3way handshake fuzzer in Python.312 with Scapy | https://github.com/zdanl/tcpcunt | 0 | 0| 
| 20221128T13:22:36Z | Null | https://github.com/dbouidaine/Fuzzy-C-Means | 0 | 0| 



# 日更新程序
