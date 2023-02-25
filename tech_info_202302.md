# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230224 | 绕过 ESP32 芯片的 Flash 加密功能 | http://raelize.com/blog/espressif-systems-esp32-bypassing-flash-encryption/| 
| 20230224 | 不使用 EFI bootkit，通过开启内核调试模式来关闭 windows 的 PatchGuard | https://hexderef.com/patchguard-bypass| 
| 20230224 | 一种黑盒检测原型链污染的方法。 | http://www.intruder.io/research/server-side-prototype-pollution| 
| 20230224 | 一个可以显示Git仓库详细信息的工具，可以离线使用。 | https://github.com/o2sh/onefetch| 
| 20230224 | 微软MSRC官网的XSS漏洞的发现过程。 | https://m3ez.medium.com/how-i-found-dom-based-xss-on-microsoft-msrc-and-how-they-fixed-it-8b71a6020c82| 
| 20230223 | Node.js 的 undici 库存在 CRLF 注入漏洞 | https://hackerone.com/reports/1820955| 
| 20230223 | Fuzzilli新增了一个用于将js代码转换成Fuzzili IR的工具。 | https://github.com/googleprojectzero/fuzzilli/commit/807625f0112df22bfe293aa4d36d67c31c4fb243| 
| 20230223 | 像使用IDA一样使用Ghidra的插件 | https://gist.github.com/NyaMisty/06e65d0f0268d456d9d086aee08952ee| 
| 20230223 | 这篇文章以实际案例展示了盲目信任第三方API会导致导致一系列安全问题 | https://www.codean.io/blog/vulnerability-write-up---%22dangerous-assumptions%22| 
| 20230223 | 苹果Lightning接口通信协议的逆向工程分享视频，视频中还用到了chatGPT来猜测可能的协议 | http://hackaday.com/2023/02/22/reverse-engineering-the-apple-lightning-connector/| 
| 20230223 | 一篇介绍macos自带安全机制的文章，讲的还是比较清楚。 | https://www.huntress.com/blog/built-in-macos-security-tools| 
| 20230223 | 使用NtQueueApcThreadEx向windows进程注入任意shellcode，可以用于bypass部分终端安全检测 | https://github.com/LloydLabs/ntqueueapcthreadex-ntdll-gadget-injection| 
| 20230223 | 使用OPENAI达芬奇模型(ChatGPT的背后模型)分析shellcode的功能 | https://www.archcloudlabs.com/projects/shellcode_gpt/| 
| 20230223 | Amazon的语言模型仅使用1 billion个参数就可以达到91.68%的准确率，超过了用了175 billion个参数的GPT-3.5（准确率75.17%），该模型已开源。 | https://arxiv.org/pdf/2302.00923.pdf| 
| 20230223 | 安全研究员Man Yue Mo通过分析调试时出现的GPU执行错误，发现了一个由于CPU缓存和物理内存不一致导致的信息泄露漏洞，该漏洞通过读取物理内存中的脏数据导致可以泄露用户态、内核数据，本文中介绍了一种如何利用该漏洞绕过KASLR 的方法。 | http://github.blog/2023-02-23-the-code-that-wasnt-there-reading-memory-on-an-android-device-by-accident/| 
| 20230222 | 该工具可以将任意文件以视频形式存储，将视频上传到视频网站进而使用其免费的云存储 | https://github.com/DvorakDwarf/Infinite-Storage-Glitch| 
| 20230222 | 作者审计了vscode中的两款插件，利用插件中的XSS漏洞，以DNS rebind、dns-prefetch等方法绕过保护，从而达到泄露ssh私钥发送给攻击者的攻击效果。 | http://blog.trailofbits.com/2023/02/21/vscode-extension-escape-vulnerability/| 
| 20230222 | 解读 PoshC2 渗透框架代码实现 | https://www.reddit.com/r/netsec/comments/1185gd3/a_deep_dive_into_a_poshc2_implant/| 
| 20230222 | 微软对2022年DDoS攻击的趋势分析 | https://www.microsoft.com/en-us/security/blog/2023/02/21/2022-in-review-ddos-attack-trends-and-insights/| 
| 20230222 | Fortinet FortiNAC CVE-2022-39952的POC，未授权解压缩可导致任意文件写入，通过crontab实现RCE | https://github.com/horizon3ai/CVE-2022-39952| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230224 | [HTB] NodeBlog Writeup | https://mp.weixin.qq.com/s/YHFuh42FvDWSx3j4kzwhqw| 
| 20230224 | 2022年度BOTNET趋势报告 | https://book.yunzhan365.com/tkgd/ikxy/mobile/index.html| 
| 20230224 | 个人信息出境标准合同办法 | https://mp.weixin.qq.com/s/5T7pCReDif6tzCd56m3zKA| 
| 20230223 | 通过 Rank-1 相似性矩阵分解建模反病毒引擎共识演化 | https://mp.weixin.qq.com/s/_eLxhU_8b52RtAmNOqKgLw| 
| 20230223 | 从攻击视角探讨ChatGPT对网络安全的影响 | https://mp.weixin.qq.com/s/ph5GnQFIGcSzi-9H-YlJTA| 
| 20230223 | 2022年度反诈报告 | https://mp.weixin.qq.com/s/unvQR8lneWQVP3bHj3fOWA| 
| 20230223 | 2022网络金融黑产研究报告 | https://mp.weixin.qq.com/s/tQE0BtclxX6McZRoO5MKVg| 
| 20230223 | 一种基于网络流量风险数据聚类的APT攻击溯源方法 | https://mp.weixin.qq.com/s/Mg-eC9NOThERVu_fjBOzkw| 
| 20230222 | 精准EDR能力白皮书 | https://www.dwcon.cn/uploads/file/2023/02/21/1676967277745514.pdf| 
| 20230222 | 如何研究一家网络安全公司？ | https://mp.weixin.qq.com/s/YNuzTwVrINd3eSWlHGVMFQ| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230225T02:08:52Z | CVE-2023-21839 | Weblogic CVE-2023-21839 RCE (无需Java依赖一键RCE) | https://github.com/4ra1n/CVE-2023-21839 | | 
| 20230225T01:05:40Z | CVE-2023-25136 | OpenSSH 9.1 vulnerability mass scan and exploit | https://github.com/Christbowel/CVE-2023-25136 | | 
| 20230224T15:47:28Z | CVE-2023-23752 | simple program for joomla CVE-2023-23752 scanner for pentesting and educational purpose | https://github.com/z3n70/CVE-2023-23752 | | 
| 20230224T11:44:49Z | CVE-2020-14882 | 综合利用工具 | https://github.com/Serendipity-Lucky/CVE-2020-14882_ALL | | 
| 20230224T08:44:27Z | CVE-2023-21839 | Weblogic CVE-2023-21839 RCE | https://github.com/hacats/CVE-2023-21839 | | 
| 20230224T02:34:31Z | CVE-2022-25765 | Exploit for CVE-2022–25765 (pdfkit) - Command Injection | https://github.com/UNICORDev/exploit-CVE-2022-25765 | | 
| 20230224T01:58:18Z | CVE-2023-999992 | Null | https://github.com/yrtsec/CVE-2023-999992 | | 
| 20230224T01:54:40Z | CVE-2023-23752 | CVE-2023-23752 Joomla 未授权访问漏洞 poc | https://github.com/ifacker/CVE-2023-23752-Joomla | | 
| 20230224T01:33:15Z | CVE-2023-999993 | Null | https://github.com/yrtsec/CVE-2023-999993 | | 
| 20230223T21:08:53Z | CVE-2023-22974 | OpenEMR < 7.0.0 Arbitrary File Read | https://github.com/gbrsh/CVE-2023-22974 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230225T02:18:29Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10798 | 349| 
| 20230224T14:10:15Z | An open-source Unified Ideograph (Extension) font derived from Fontworks% Klee One. | https://github.com/Des-Magmeta/PlanKai | 2 | 0| 
| 20230224T13:37:39Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2169 | 606| 
| 20230224T00:05:46Z | A project for the generation of synthetic data for research into social networks and NLP | https://github.com/forxiny/kleek | 0 | 0| 
| 20230222T14:21:54Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 217 | 2| 
| 20230220T17:33:01Z | Null | https://github.com/Peltorator/klees-measure-lower-bounds-repo | 0 | 0| 
| 20230219T17:59:23Z | 基於 Klee One 改造的字型，以傳承字形風格為主。 | https://github.com/Ayaginu-Sue/Astalia | 2 | 0| 
| 20230219T09:21:14Z | Collection of Kicad 6.0 symbols, footprints and 3D models useful in keyboard creation | https://github.com/crides/kleeb | 74 | 6| 
| 20230218T22:54:48Z | Null | https://github.com/kleeeeea/kleeeeea.github.io | 1 | 0| 
| 20230217T00:08:13Z | Null | https://github.com/jswayman571/GetKleend | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230225T00:41:05Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 299 | 74| 
| 20230224T14:32:12Z | Bachelor%s thesis: developing symbolic execution for Rlang using Chef and S2E | https://github.com/SoptikHa2/bachelors-thesis | 1 | 0| 
| 20230218T14:11:14Z | Exercise S2 - Pham Viet Duc | https://github.com/vietduc218/s2exercise | 0 | 0| 
| 20230217T07:05:16Z | Spacecraft Simulation Environment Core codes | https://github.com/ut-issl/s2e-core | 27 | 8| 
| 20230216T18:27:56Z | Null | https://github.com/SKyletoft/s2e-autocxx-error | 0 | 0| 
| 20230214T13:52:13Z | Null | https://github.com/MetadataGitTesting/S2eJej9r | 0 | 0| 
| 20230209T15:55:48Z | Null | https://github.com/uweDF7823D/s2ewgs21g3a | 0 | 0| 
| 20230209T08:59:46Z | WIZnet Serial to Ethernet(S2E) module based on W7500 chip, WIZ107/108SR S2E compatible device | https://github.com/Wiznet/WIZ750SR | 14 | 15| 
| 20230209T08:18:08Z | GUI Configuration tool for WIZnet serial to ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool-GUI | 18 | 10| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230225T01:58:53Z | Exploit Development and Reverse Engineering with GDB Made Easy | https://github.com/pwndbg/pwndbg | 5294 | 735| 
| 20230225T01:12:20Z | The Browser Exploitation Framework Project | https://github.com/beefproject/beef | 8169 | 1889| 
| 20230225T00:48:36Z | A bash script I use when I am performing any return oriented programming exploits | https://github.com/dilldylanpickle/ROPchecker | 0 | 0| 
| 20230225T00:20:11Z | Null | https://github.com/codingcore12/SILENT-DOC-EXPLOIT-CLEAN-2k | 1 | 0| 
| 20230225T00:19:08Z | Null | https://github.com/codingcore12/SILENT-PDF-EXPLOIT-CLEAN-2k | 1 | 0| 
| 20230225T00:18:18Z | Null | https://github.com/codingcore12/SILENT-EXCEL-XLS-EXPLOIT-CLEAN-2k | 1 | 0| 
| 20230224T23:41:57Z | Welcome to this tutorial series on ARM assembly basics. This is the preparation for the followup tutorial series on ARM exploit development. Before we can dive into creating ARM shellcode and build ROP chains, we need to cover some ARM Assembly basics first. | https://github.com/guyb27/asm_arm_with_Azeria | 0 | 0| 
| 20230224T23:28:19Z | Null | https://github.com/1337x0/rExploit | 0 | 0| 
| 20230224T22:57:36Z | Null | https://github.com/aarora4/Exploit-DoS-8803 | 0 | 0| 
| 20230224T22:33:57Z | Simple Copy Exploit/Trick Demonstration  | https://github.com/djamysh/SimpleCopyExploitDemonstration | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230224T23:11:48Z | (2/24/23) this is my first discord bot, its a backdoor, in order for a victim to execute it they would need the filelink url, simply drop the .py file onto discord and copy it, before you paste the url put %curl% and after put %-o main.py && py main.py% | https://github.com/qoudaq/first-malware | 0 | 0| 
| 20230224T21:50:01Z | Jarbou3 is  rat  tool  coded in python with C&C which can accept multiple connections from clients | https://github.com/TheNewAttacker64/jarbou3 | 112 | 28| 
| 20230224T21:01:12Z | A curated list of trustworthy deep learning papers. Daily updating... | https://github.com/MinghuiChen43/awesome-trustworthy-deep-learning | 113 | 14| 
| 20230224T20:25:55Z | Null | https://github.com/ain-soph/nas_backdoor | 0 | 0| 
| 20230224T18:19:55Z | backdoor simples (não finalizado) usando a biblioteca socket | https://github.com/boloto1979/v01_backdoor | 0 | 0| 
| 20230224T16:39:14Z | Defending Against Backdoor Attacks by Layer-wise Feature Analysis | https://github.com/NajeebJebreel/DBALFA | 2 | 0| 
| 20230224T16:37:55Z | Null | https://github.com/Carlos-CodeBot/Backdoor | 0 | 0| 
| 20230224T05:17:03Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) C2 and post-exploitation framework written in python and C | https://github.com/n1nj4sec/pupy | 7500 | 1772| 
| 20230224T00:25:12Z | A collection of malwares found on the internet. | https://github.com/Princekin/malware-database | 14 | 7| 
| 20230224T00:23:32Z | R package for backdoor criterion causal effect analysis  | https://github.com/ads303/causal.inf | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230225T00:41:05Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 299 | 74| 
| 20230224T14:32:12Z | Bachelor%s thesis: developing symbolic execution for Rlang using Chef and S2E | https://github.com/SoptikHa2/bachelors-thesis | 1 | 0| 
| 20230224T13:37:39Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2169 | 606| 
| 20230223T06:40:57Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3330 | 471| 
| 20230223T02:46:43Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 622 | 110| 
| 20230222T14:58:17Z | The symbolic execution engine powering the K Framework | https://github.com/runtimeverification/haskell-backend | 188 | 43| 
| 20230222T09:13:13Z | Unicorn: Symbolic Execution, Bounded Model Checking, and Code Optimization of RISC-V Code using Classical Solvers and Quantum Computers | https://github.com/cksystemsgroup/unicorn | 14 | 5| 
| 20230221T13:53:41Z | A symbolic execution engine in Prolog for C | https://github.com/LilyOSullivan/SymbolicExecutionForCWithParser | 3 | 0| 
| 20230221T03:55:08Z | A native symbolic execution engine for WebAssembly | https://github.com/HNYuuu/SeeWasm | 20 | 2| 
| 20230218T18:26:40Z | Quiver-Based Symbolic Execution | https://github.com/LostBitset/quiver_se | 3 | 0| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230224T12:09:49Z | A Summary of Vulnerabilities Found in the BlockScope NDSS%23 Paper | https://github.com/VPRLab/BlkVulnReport | 4 | 0| 
| 20230224T09:05:30Z | Anomaly Detection in the Open World: Normality Shift Detection, Explanation, and Adaptation (NDSS%23). | https://github.com/dongtsi/OWAD | 10 | 1| 
| 20230220T13:49:50Z | Original implementation of FlowPrint as in the NDSS %20 paper | https://github.com/Thijsvanede/FlowPrint | 74 | 29| 
| 20230218T07:30:40Z | BARS: Local Robustness Certification for Deep Learning based Traffic Analysis Systems (NDSS%23) | https://github.com/KaiWangGitHub/BARS | 1 | 0| 
| 20230217T16:16:23Z | DroneSecurity (NDSS 2023) | https://github.com/RUB-SysSec/DroneSecurity | 2 | 0| 
| 20230217T02:13:33Z | Prototype implementation of Cash et al.%s NDSS%14 scheme PiBas. | https://github.com/AKarbas/PiBas-Implementation | 0 | 0| 
| 20230216T15:13:11Z | find relevant security papers published in the top-4 conferences (S&P, USENIX, CCS, NDSS) | https://github.com/Kyle-Kyle/top4grep | 37 | 3| 
| 20230211T05:58:44Z | ConfFuzz NDSS Data Set | https://github.com/conffuzz/conffuzz-ndss-data | 2 | 1| 
| 20230203T10:28:34Z | A curated list of Meachine learning Security & Privacy papers published in security top-4 conferences (IEEE S&P, ACM CCS, USENIX Security and NDSS). | https://github.com/gnipping/Awesome-ML-SP-Papers | 27 | 2| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230225T01:24:44Z | An extremely fast and flexible web fuzzer | https://github.com/henshin/filebuster | 200 | 51| 
| 20230225T00:26:14Z | Ethereum smart contract fuzzer | https://github.com/crytic/echidna | 1950 | 250| 
| 20230224T22:27:07Z | Null | https://github.com/robot-tie/fuzzy | 0 | 0| 
| 20230224T20:45:51Z | autofz: Automated Fuzzer Composition at Runtime | https://github.com/sslab-gatech/autofz | 2 | 0| 
| 20230224T20:36:25Z | Null | https://github.com/pbaity/fuzzy-barnacle | 0 | 0| 
| 20230224T19:54:09Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 1280 | 171| 
| 20230224T19:45:50Z | Rockyou for web fuzzing | https://github.com/six2dez/OneListForAll | 1658 | 320| 
| 20230224T19:05:35Z | Fuzzy approach to solving Traveling Salesman Problem | https://github.com/Via-R/fuzzy-tsp | 0 | 0| 
| 20230224T17:36:57Z | A tiny, efficient fuzzy search that doesn%t suck | https://github.com/leeoniya/uFuzzy | 2094 | 34| 
| 20230224T17:23:33Z | Official repository  vuls Scan: 15000+PoCs; 23 kinds of application password crack; 7000+Web fingerprints; 146 protocols and 90000+ rules Port scanning; Fuzz, HW, awesome BugBounty( ͡° ͜ʖ ͡°)... | https://github.com/hktalent/scan4all | 3425 | 413| 



# 日更新程序
