# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230223 | Node.js 的 undici 库存在 CRLF 注入漏洞 | https://hackerone.com/reports/1820955| 
| 20230223 | Fuzzilli新增了一个用于将js代码转换成Fuzzili IR的工具。 | https://github.com/googleprojectzero/fuzzilli/commit/807625f0112df22bfe293aa4d36d67c31c4fb243| 
| 20230223 | 像使用IDA一样使用Ghidra的插件 | https://gist.github.com/NyaMisty/06e65d0f0268d456d9d086aee08952ee| 
| 20230223 | 这篇文章以实际案例展示了盲目信任第三方API会导致导致一系列安全问题 | https://www.codean.io/blog/vulnerability-write-up---%22dangerous-assumptions%22| 
| 20230223 | 苹果Lightning接口通信协议的逆向工程分享视频，视频中还用到了chatGPT来猜测可能的协议 | http://hackaday.com/2023/02/22/reverse-engineering-the-apple-lightning-connector/| 
| 20230223 | 一篇介绍macos自带安全机制的文章，讲的还是比较清楚。 | https://www.huntress.com/blog/built-in-macos-security-tools| 
| 20230223 | 使用NtQueueApcThreadEx向windows进程注入任意shellcode，可以用于bypass部分终端安全检测 | https://github.com/LloydLabs/ntqueueapcthreadex-ntdll-gadget-injection| 
| 20230223 | 使用OPENAI达芬奇模型(ChatGPT的背后模型)分析shellcode的功能 | https://www.archcloudlabs.com/projects/shellcode_gpt/| 
| 20230223 | Amazon的语言模型仅使用1 billion个参数就可以达到91.68%的准确率，超过了用了175 billion个参数的GPT-3.5（准确率75.17%），该模型已开源。 | https://arxiv.org/pdf/2302.00923.pdf| 
| 20230222 | 该工具可以将任意文件以视频形式存储，将视频上传到视频网站进而使用其免费的云存储 | https://github.com/DvorakDwarf/Infinite-Storage-Glitch| 
| 20230222 | 作者审计了vscode中的两款插件，利用插件中的XSS漏洞，以DNS rebind、dns-prefetch等方法绕过保护，从而达到泄露ssh私钥发送给攻击者的攻击效果。 | http://blog.trailofbits.com/2023/02/21/vscode-extension-escape-vulnerability/| 
| 20230222 | 解读 PoshC2 渗透框架代码实现 | https://www.reddit.com/r/netsec/comments/1185gd3/a_deep_dive_into_a_poshc2_implant/| 
| 20230222 | 微软对2022年DDoS攻击的趋势分析 | https://www.microsoft.com/en-us/security/blog/2023/02/21/2022-in-review-ddos-attack-trends-and-insights/| 
| 20230222 | Fortinet FortiNAC CVE-2022-39952的POC，未授权解压缩可导致任意文件写入，通过crontab实现RCE | https://github.com/horizon3ai/CVE-2022-39952| 
| 20230222 | 编写一个Chrome浏览器扩展，尽可能地窃取用户信息，包括cookie，浏览历史，tab截图等等。 | https://mattfrisbie.substack.com/p/spy-chrome-extension| 
| 20230221 | CVE-2022-24942 的 WP。HTTPsReq_HdrParse 函数在拷贝字符串时，没有考虑到长度是否超过了 buffer 的最大可用长度，导致堆溢出。 | https://bugprove.com/knowledge-hub/cve-2022-24942-heap-based-buffer-overflow-in-silicon-labs-gecko-sdk/| 
| 20230221 | python重写的DPAPI渗透工具 | https://www.reddit.com/r/netsec/comments/1179msr/github_zblurxdploot_dpapi_looting_remotely_in/| 
| 20230221 | Colossal-AI，开源语言模型，与ChatGPT使用相同的实现，使用个人可以负担得起的资源即可训练 | https://www.hpc-ai.tech/blog/colossal-ai-chatgpt| 
| 20230221 | 面向编译器开发者的安全知识库，包括内存破坏类攻击，侧信道攻击，物理攻击等 | https://llsoftsec.github.io/llsoftsecbook/| 
| 20230221 | TrueBot Analysis Part II - Static unpacker | https://malware.love/malware_analysis/reverse_engineering/2023/02/18/analyzing-truebot-static-unpacking.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230223 | 通过 Rank-1 相似性矩阵分解建模反病毒引擎共识演化 | https://mp.weixin.qq.com/s/_eLxhU_8b52RtAmNOqKgLw| 
| 20230223 | 从攻击视角探讨ChatGPT对网络安全的影响 | https://mp.weixin.qq.com/s/ph5GnQFIGcSzi-9H-YlJTA| 
| 20230223 | 2022年度反诈报告 | https://mp.weixin.qq.com/s/unvQR8lneWQVP3bHj3fOWA| 
| 20230223 | 2022网络金融黑产研究报告 | https://mp.weixin.qq.com/s/tQE0BtclxX6McZRoO5MKVg| 
| 20230223 | 一种基于网络流量风险数据聚类的APT攻击溯源方法 | https://mp.weixin.qq.com/s/Mg-eC9NOThERVu_fjBOzkw| 
| 20230222 | 精准EDR能力白皮书 | https://www.dwcon.cn/uploads/file/2023/02/21/1676967277745514.pdf| 
| 20230222 | 如何研究一家网络安全公司？ | https://mp.weixin.qq.com/s/YNuzTwVrINd3eSWlHGVMFQ| 
| 20230222 | 浅谈应用分发平台标准动态 | https://mp.weixin.qq.com/s/8sN0OBkwveVDQu9aQMXDfg| 
| 20230222 | 论坛·2022全球网空态势回顾 | https://mp.weixin.qq.com/s/UoQwrnXr8OTfjyDzOT6xmg| 
| 20230222 | ChatGPT在MITREATT&CK落地中的应用 | https://mp.weixin.qq.com/s/hehFQbR6lqAABEDhrxtIBg| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230224T01:58:18Z | CVE-2023-999992 | Null | https://github.com/yrtsec/CVE-2023-999992 | | 
| 20230224T01:54:40Z | CVE-2023-23752 | CVE-2023-23752 Joomla 未授权访问漏洞 poc | https://github.com/ifacker/CVE-2023-23752-Joomla | | 
| 20230224T01:33:55Z | CVE-2023-23752 | simple program for joomla CVE-2023-23752 scanner for pentesting and educational purpose | https://github.com/z3n70/CVE-2023-23752 | | 
| 20230224T01:33:15Z | CVE-2023-999993 | Null | https://github.com/yrtsec/CVE-2023-999993 | | 
| 20230223T22:42:07Z | CVE-2023-25136 | OpenSSH 9.1 vulnerability mass scan and exploit | https://github.com/Christbowel/CVE-2023-25136 | | 
| 20230223T21:08:53Z | CVE-2023-22974 | OpenEMR < 7.0.0 Arbitrary File Read | https://github.com/gbrsh/CVE-2023-22974 | | 
| 20230223T17:08:36Z | CVE-2020-0418 | Null | https://github.com/fernandodruszcz/CVE-2020-0418 | | 
| 20230223T16:13:47Z | CVE-2023-999991 | Null | https://github.com/yrtsec/CVE-2023-999991 | | 
| 20230223T15:10:49Z | CVE-2021-42756 | Null | https://github.com/3ndorph1n/CVE-2021-42756 | | 
| 20230223T12:48:12Z | CVE-2023-21839 | Null | https://github.com/DXask88MA/Weblogic-CVE-2023-21839 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230224T00:05:46Z | A project for the generation of synthetic data for research into social networks and NLP | https://github.com/forxiny/kleek | 0 | 0| 
| 20230223T22:14:59Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2166 | 606| 
| 20230223T19:21:45Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10786 | 349| 
| 20230222T14:21:54Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 217 | 2| 
| 20230220T17:33:01Z | Null | https://github.com/Peltorator/klees-measure-lower-bounds-repo | 0 | 0| 
| 20230219T23:57:26Z | An open-source Unified Ideograph (Extension) font derived from Fontworks% Klee One. | https://github.com/Des-Magmeta/PlanKai | 2 | 0| 
| 20230219T17:59:23Z | 基於 Klee One 改造的字型，以傳承字形風格為主。 | https://github.com/Ayaginu-Sue/Astalia | 2 | 0| 
| 20230219T09:21:14Z | Collection of Kicad 6.0 symbols, footprints and 3D models useful in keyboard creation | https://github.com/crides/kleeb | 74 | 6| 
| 20230218T22:54:48Z | Null | https://github.com/kleeeeea/kleeeeea.github.io | 1 | 0| 
| 20230217T00:08:13Z | Null | https://github.com/jswayman571/GetKleend | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230223T08:45:44Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 299 | 74| 
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
| 20230224T01:33:35Z | Just some exploit tools can be used in Grey Hack | https://github.com/thomasbad/GreyHackNoobTools | 0 | 0| 
| 20230224T01:10:58Z | Demystifying Exploitable Bugs in Smart Contracts | https://github.com/ZhangZhuoSJTU/Web3Bugs | 65 | 7| 
| 20230223T23:50:23Z | Null | https://github.com/codingcore12/SILENT-DOC-EXPLOIT-CLEAN-5m | 1 | 0| 
| 20230223T23:49:29Z | Null | https://github.com/codingcore12/SILENT-PDF-EXPLOIT-CLEAN-5m | 1 | 0| 
| 20230223T23:48:41Z | Null | https://github.com/codingcore12/SILENT-EXCEL-XLS-EXPLOIT-CLEAN-5m | 1 | 0| 
| 20230223T23:45:36Z | Soure code for the paper, entitled %Exploiting Semantic Localization in Highly Dynamic Wireless Networks using Deep Homoscedastic Domain Adaptation%  | https://github.com/Leo-Chu/SemanticLoc | 0 | 0| 
| 20230223T23:32:47Z | Latest PyTorch Implementation of DeltaGRU & DeltaLSTM that Exploits Temporal Sparsity in Sequential Data | https://github.com/gaochangw/DeltaRNN | 1 | 0| 
| 20230223T21:55:10Z | Latest Chrome PoC for RCE code execution | https://github.com/grandDancer/Chrome-CVE-PoC | 4 | 1| 
| 20230223T21:16:59Z | 🎯 Fortnite External Cheat Release  /  Feature Aimbot + Esp  | https://github.com/Serups/Fortnite-External | 86 | 39| 
| 20230223T13:33:40Z | Injections and exploits for ChatBots, a curated list of prompt commands | https://github.com/Cranot/chatbot-injections-exploits | 54 | 3| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230224T00:23:32Z | R package for backdoor criterion causal effect analysis  | https://github.com/ads303/causal.inf | 0 | 0| 
| 20230223T23:53:44Z | Jarbou3 is  rat  tool  coded in python with C&C which can accept multiple connections from clients | https://github.com/TheNewAttacker64/jarbou3 | 111 | 27| 
| 20230223T23:11:32Z | A curated list of trustworthy deep learning papers. Daily updating... | https://github.com/MinghuiChen43/awesome-trustworthy-deep-learning | 111 | 14| 
| 20230223T22:53:48Z | This tool is used for backdoor,shellcode generation,Information retrieval and POC arrangement for various architecture devices | https://github.com/doudoudedi/hackEmbedded | 103 | 18| 
| 20230223T20:58:06Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) C2 and post-exploitation framework written in python and C | https://github.com/n1nj4sec/pupy | 7499 | 1772| 
| 20230223T19:49:35Z | Null | https://github.com/V1C70RYG0D/Sphagetti-backdoor-2022 | 0 | 0| 
| 20230223T19:43:52Z | Null | https://github.com/V1C70RYG0D/Backdoor-Maze-Chase | 0 | 0| 
| 20230223T18:09:01Z | Null | https://github.com/justPa1nbro/Backdoor-made-by-musALLat | 1 | 0| 
| 20230223T05:38:52Z | Null | https://github.com/badboycxcc/IIS_Backdoor_Dll | 1 | 0| 
| 20230223T04:48:43Z | Null | https://github.com/wdbbsq/federated_backdoor | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230223T22:14:59Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2166 | 606| 
| 20230223T08:45:44Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 299 | 74| 
| 20230223T06:40:57Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3330 | 471| 
| 20230223T02:46:43Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 622 | 110| 
| 20230222T14:58:17Z | The symbolic execution engine powering the K Framework | https://github.com/runtimeverification/haskell-backend | 188 | 43| 
| 20230222T09:13:13Z | Unicorn: Symbolic Execution, Bounded Model Checking, and Code Optimization of RISC-V Code using Classical Solvers and Quantum Computers | https://github.com/cksystemsgroup/unicorn | 14 | 5| 
| 20230221T13:53:41Z | A symbolic execution engine in Prolog for C | https://github.com/LilyOSullivan/SymbolicExecutionForCWithParser | 3 | 0| 
| 20230221T03:55:08Z | A native symbolic execution engine for WebAssembly | https://github.com/HNYuuu/SeeWasm | 20 | 2| 
| 20230218T18:26:40Z | Quiver-Based Symbolic Execution | https://github.com/LostBitset/quiver_se | 3 | 0| 
| 20230218T11:48:35Z | ToolChain using Symbolic Execution for Malware Analysis. | https://github.com/csvl/SEMA-ToolChain | 16 | 8| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230223T16:29:03Z | Anomaly Detection in the Open World: Normality Shift Detection, Explanation, and Adaptation (NDSS%23). | https://github.com/dongtsi/OWAD | 9 | 1| 
| 20230220T13:49:50Z | Original implementation of FlowPrint as in the NDSS %20 paper | https://github.com/Thijsvanede/FlowPrint | 74 | 29| 
| 20230218T07:30:40Z | BARS: Local Robustness Certification for Deep Learning based Traffic Analysis Systems (NDSS%23) | https://github.com/KaiWangGitHub/BARS | 1 | 0| 
| 20230217T16:16:23Z | DroneSecurity (NDSS 2023) | https://github.com/RUB-SysSec/DroneSecurity | 2 | 0| 
| 20230217T02:13:33Z | Prototype implementation of Cash et al.%s NDSS%14 scheme PiBas. | https://github.com/AKarbas/PiBas-Implementation | 0 | 0| 
| 20230216T15:13:11Z | find relevant security papers published in the top-4 conferences (S&P, USENIX, CCS, NDSS) | https://github.com/Kyle-Kyle/top4grep | 37 | 3| 
| 20230211T05:58:44Z | ConfFuzz NDSS Data Set | https://github.com/conffuzz/conffuzz-ndss-data | 2 | 1| 
| 20230208T03:11:43Z | A Summary of Vulnerabilities Found in the BlockScope NDSS%23 Paper | https://github.com/VPRLab/BlkVulnReport | 3 | 0| 
| 20230203T10:28:34Z | A curated list of Meachine learning Security & Privacy papers published in security top-4 conferences (IEEE S&P, ACM CCS, USENIX Security and NDSS). | https://github.com/gnipping/Awesome-ML-SP-Papers | 27 | 2| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230224T01:25:48Z | Ethereum smart contract fuzzer | https://github.com/crytic/echidna | 1947 | 249| 
| 20230224T01:18:06Z | Null | https://github.com/RizzyFuzz/RizzyFuzz | 0 | 0| 
| 20230224T00:54:18Z | Null | https://github.com/jaggs79/fuzzy-spoon | 0 | 0| 
| 20230223T22:55:31Z | Shift Planning Tool | https://github.com/FelixRohr/fuzzy-carnival | 0 | 0| 
| 20230223T19:33:17Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 1279 | 170| 
| 20230223T19:07:51Z | Null | https://github.com/AlexCallenderInTimeTec/fuzzy-system | 0 | 0| 
| 20230223T13:24:10Z | Introduction to version control with Git (Applied) :]] | https://github.com/baarb02/-fuzzy-octo-waddle | 0 | 0| 
| 20230223T13:23:53Z | my first repository - test - itroduction to version control with Git | https://github.com/SofieBT2/fuzzy-lamp | 0 | 0| 
| 20230223T13:23:50Z | DOM fuzzer | https://github.com/googleprojectzero/domato | 1503 | 287| 
| 20230223T12:49:56Z | cool decription  | https://github.com/baarb02/fuzzy-octo-waddle | 0 | 0| 



# 日更新程序
