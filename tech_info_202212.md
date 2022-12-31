# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221230 | 介绍针对人工智能的提示词注入攻击，通过一些特殊技巧使 AI 的输出产生非预期情况。本文以 Notion AI 为例介绍了提示词注入攻击的具体细节。 | https://lspace.swyx.io/p/reverse-prompt-eng| 
| 20221230 | Google Project Zero研究员glazunov发现的一个mojo同步消息机制的沙箱进程UAF新攻击面，该类漏洞是在消息发送进程等待同步消息返回时，处理收到的其他传入消息导致的“重入”攻击，由于其临时变量大多使用了裸指针，因此很容易导致UAF。 | https://bugs.chromium.org/p/project-zero/issues/detail?id=2372| 
| 20221230 | PVS-Studio工具检测出的top 10 C++ bugs，第一名是std::clamp的错误使用，开发者误以为std::clamp会直接更新参数的值，实际上并不会，而是返回一个引用 | https://pvs-studio.com/en/blog/posts/cpp/1021/?utm_source=firefly&utm_medium=twitter| 
| 20221230 | Red Team Tactics: Writing Windows Kernel Drivers for Advanced Persistence (Part 1) | https://v3ded.github.io/redteam/red-team-tactics-writing-windows-kernel-drivers-for-advanced-persistence-part-1| 
| 20221230 | 今年 Flare-On 的一道题，.NET IL 在运行中被动态 patch，作者讲述了他如何拿到 JIT 后的汇编的过程 | http://daniao.ws/dumping-x86-assembly-of-csharp-dynamicmethod.html| 
| 20221229 | Rust 语言逆向工程学习笔记 | https://brightprogrammer.netlify.app/post/reverse-engineering-rustlang-binaries-0x1-empty-program/| 
| 20221229 | 总结了开发 Linux 内核漏洞利用时可能用到的结构体 | http://blog.csdn.net/panhewu9919/article/details/118112795| 
| 20221229 | Nunchucks HackTheBox Writeup | http://www.hackingarticles.in/nunchucks-hackthebox-walkthrough/| 
| 20221229 | 通过对华为手机EL2级别的安全保护程序HHEE的逆向分析，分析其对内核提取的多种通用保护机制。 | http://blog.impalabs.com/2212_huawei-security-hypervisor.html| 
| 20221229 | 零基础细致教学缓冲区溢出漏洞，从什么是缓冲区溢出漏洞以及如何产生的，到如何利用该漏洞，到最后如何修复该漏洞的全过程。 | https://ad2001.gitbook.io/a-noobs-guide-to-arm-exploitation/introduction-to-stack-buffer-overflows| 
| 20221229 | 介绍了GuLoader这一恶意软件的反侦察反分析手段 | https://gbhackers.com/guloader-malware-advanced-anti-analysis/| 
| 20221229 | 给出了一个有趣的针对GPT3/ChatGPT的提示词注入（Prompt Injection）用来扰乱AI的输入逻辑。 | https://www.reddit.com/r/ReverseEngineering/comments/zy1b9u/reverse_prompt_engineering_for_fun_and_no_profit/| 
| 20221229 | 展示了一个最新发现的勒索软件CatB，该软件通过处理器核心检查，物理内存大小检查和硬盘大小检查确定自己不被放置在虚拟机中，然后执行MSDTC 服务的DLL劫持绕过杀毒防御软件。 | http://minerva-labs.com/blog/new-catb-ransomware-employs-2-year-old-dll-hijacking-technique-to-evade-detection/| 
| 20221229 | Hacking in Parallel – Track 1 | http://streaming.media.ccc.de/jev22/hip1| 
| 20221229 | 一款通过分析rust二进制内模块并在本地构建相应模块以恢复stripped二进制符号的python工具 | https://www.reddit.com/r/ReverseEngineering/comments/zxlssk/cerberus_a_python_tool_to_recover_symbols_from/| 
| 20221229 | 借助rtld，利用单字节溢出实现ROP | https://hackmd.io/@pepsipu/ry-SK44pt?s=09| 
| 20221228 | 影响任天堂多款在线游戏的网络库缓冲区溢出漏洞的细节和poc公开，涉及ns，3ds，wiiu平台的多款游戏 | http://securityonline.info/cve-2022-47949-critical-rce-flaw-affects-multiple-nintendo-games/| 
| 20221228 | 2022年APT攻击洞察报告 | https://github.com/blackorbird/APT_REPORT/blob/master/summary/2023/2022_APT_TRENDS_INSIGHT_REPORT.pdf| 
| 20221228 | 供应链相关的攻击和缓解措施研究 | https://engineering.mercari.com/en/blog/entry/20221215-supplychain-security-reevaluation/| 
| 20221228 | 一个Linux的防火墙，以内核模块的形式实现，其主要亮点是可以像rootkit一样隐藏自己。 | https://antonio-cooler.gitbook.io/coolervoid-tavern/hidden-firewall-in-kernel| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221230 | Ysomap：一款适配于各类实际复杂环境的Java反序列化利用框架 | https://github.com/wh1t3p1g/ysomap| 
| 20221230 | TABBY：一款针对Java语言的静态代码分析工具 | https://github.com/wh1t3p1g/tabby| 
| 20221229 | [HTB] Jarvis Writeup | https://mp.weixin.qq.com/s/7eEGFMrYwfjK8ElNjvg6Lg| 
| 20221229 | 针对军工和教育行业的CNC组织“摆渡”木马分析 | https://mp.weixin.qq.com/s/uEjNpw-rtpjGGPacJS19WQ| 
| 20221229 | 2022年网络安全四大顶会论文录用列表(中国大陆) | https://mp.weixin.qq.com/s/o69IzRCRqlGtACVeeC-aRA| 
| 20221229 | 2022年网络安全四大顶会论文录用列表(中国大陆) | /news/30927| 
| 20221228 | 2022攻防演练木马专项分析报告 | http://report.threatbook.cn/2022.pdf| 
| 20221228 | 从开源项目和库的Issue和Bug报告中挖掘情报 | https://mp.weixin.qq.com/s/WaPpf20x7flfePP5-T7XIg| 
| 20221228 | 欧盟网络安全局 2022 年度威胁报告 | https://mp.weixin.qq.com/s/UDbOlnLfsD4pk_3PQCuGBw| 
| 20221228 | Yi: 项目监控工具 以及 Codeql 自动运行 | https://github.com/ZhuriLab/Yi| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20221230T17:33:09Z | CVE-2022-0847 | Null | https://github.com/pmihsan/-Dirty-Pipe-CVE-2022-0847 | | 
| 20221230T06:41:48Z | CVE-2022-35464 | OTFCC v0.10.4 was discovered to contain a heap-buffer overflow via /release-x64/otfccdump+0x6171b2. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-35464 | | 
| 20221230T06:41:44Z | CVE-2022-35463 | OTFCC v0.10.4 was discovered to contain a heap-buffer overflow via /release-x64/otfccdump+0x6b0478. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-35463 | | 
| 20221230T06:41:41Z | CVE-2022-35461 | OTFCC v0.10.4 was discovered to contain a heap-buffer overflow via /release-x64/otfccdump+0x6c0a32. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-35461 | | 
| 20221230T06:41:38Z | CVE-2022-35462 | OTFCC v0.10.4 was discovered to contain a heap-buffer overflow via /release-x64/otfccdump+0x6c0bc3. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-35462 | | 
| 20221230T06:41:34Z | CVE-2022-35460 | OTFCC v0.10.4 was discovered to contain a heap-buffer overflow via /release-x64/otfccdump+0x61731f. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-35460 | | 
| 20221230T06:41:31Z | CVE-2022-35456 | OTFCC v0.10.4 was discovered to contain a heap-buffer overflow via /release-x64/otfccdump+0x617087. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-35456 | | 
| 20221230T06:41:27Z | CVE-2022-35459 | OTFCC v0.10.4 was discovered to contain a heap-buffer overflow via /release-x64/otfccdump+0x6e412a. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-35459 | | 
| 20221230T06:41:24Z | CVE-2022-35458 | OTFCC v0.10.4 was discovered to contain a heap-buffer overflow via /release-x64/otfccdump+0x6b05ce. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-35458 | | 
| 20221230T06:41:20Z | CVE-2022-35455 | OTFCC v0.10.4 was discovered to contain a heap-buffer overflow via /release-x64/otfccdump+0x6b0d63. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-35455 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221230T05:40:38Z | Null | https://github.com/KleeUT/kleeut.com | 1 | 0| 
| 20221229T18:31:59Z | Null | https://github.com/fchamicapereira/maestro-klee | 0 | 0| 
| 20221227T15:23:28Z | chi-kleen cleaning company | https://github.com/adepeter1234/chi-kleen | 0 | 0| 
| 20221226T22:56:49Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 26 | 1| 
| 20221225T11:50:29Z | Config files for my GitHub profile. | https://github.com/SofiaArandiKlee/SofiaArandiKlee | 0 | 0| 
| 20221224T14:56:44Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2132 | 603| 
| 20221222T17:06:18Z | Klee for labels | https://github.com/OCamlPro/klee4labels | 0 | 0| 
| 20221221T20:52:56Z | Null | https://github.com/SlynkoDenis/KLEE-Tests-Generation | 0 | 0| 
| 20221221T19:13:20Z | Null | https://github.com/pjazdzewski1990/Klee | 0 | 0| 
| 20221221T14:57:59Z | Config files for my GitHub profile. | https://github.com/kleeblattdev/kleeblattdev | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221230T15:51:26Z | Spacecraft Simulation Environment Core codes | https://github.com/ut-issl/s2e-core | 26 | 8| 
| 20221230T01:35:01Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 283 | 66| 
| 20221223T06:50:27Z | GUI Configuration tool for WIZnet serial to ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool-GUI | 17 | 9| 
| 20221214T12:59:07Z | s2e-user | https://github.com/kai0722/s2e-user | 0 | 0| 
| 20221214T11:33:42Z | The Chef symbolic execution platform, based off S2E | https://github.com/dslab-epfl/chef | 7 | 2| 
| 20221212T05:54:12Z | Documents for Spacecraft Simulation Environment | https://github.com/ut-issl/s2e-documents | 6 | 6| 
| 20221205T08:13:33Z | Your S2E project management tools. Visit https://s2e.systems/docs to get started. | https://github.com/S2E/s2e-env | 84 | 45| 
| 20221204T02:10:12Z | S2E user side repository for Formation Flying study | https://github.com/ut-issl/s2e-ff | 3 | 1| 
| 20221201T07:39:12Z | S2erial_TcpServer_Long | https://github.com/liukai007/S2erial_TcpServer_Long | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221231T01:01:00Z | Null | https://github.com/AndresFDev/PS4Exploit900 | 1 | 0| 
| 20221230T23:29:16Z | Null | https://github.com/codingcore12/SILENT-DOC-EXPLOIT-CLEAN-7o | 1 | 0| 
| 20221230T23:27:38Z | Null | https://github.com/codingcore12/SILENT-EXCEL-XLS-EXPLOIT-CLEAN-7o | 1 | 0| 
| 20221230T23:26:21Z | Null | https://github.com/codingcore12/SILENT-PDF-EXPLOIT-CLEAN-7o | 1 | 0| 
| 20221230T21:36:51Z | A open-source exploit ui library for roblox, written in lua | https://github.com/swifttechpublicrepos/swiftui | 0 | 0| 
| 20221230T17:54:15Z | Collection of mods for devices vulnerable to the MacDirtyCow exploit (iOS 15-iOS 16.1.2). | https://github.com/aethercot/TrollMods | 5 | 0| 
| 20221230T13:34:23Z | Helium Android and may be registered. All other trademarks are the property of their | https://github.com/HeliumCoder/Android-Silent-JPG-Exploit-by-Helium-Coder | 4 | 1| 
| 20221230T13:06:03Z | This is an updated collection of discord exploits I found on github, all are unpatched for now dm 503#2500 on discord if one get patched | https://github.com/AxSnowz/discord-exploit-collection | 0 | 0| 
| 20221230T12:28:39Z | Script en bash que permite identificar la vulnerabilidad Log4j CVE-2021-44228 de forma remota. | https://github.com/julian911015/Log4j-Scanner-Exploit | 10 | 3| 
| 20221230T12:27:41Z | Cyber Security ALL-IN-ONE Platform | https://github.com/yaklang/yakit | 4836 | 702| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221230T19:12:18Z | a Backdoor for Android _ Based on AndroRAT | https://github.com/qLoganAniversity/GerdoRAT | 0 | 0| 
| 20221230T17:50:16Z | https://t.me/mintOnTop | https://github.com/BoomEnjoyer/MintLoader | 3 | 1| 
| 20221230T17:00:22Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/Ghost | 1875 | 800| 
| 20221230T16:04:00Z | not by me | https://github.com/EncryptedScripts/backdoor | 0 | 0| 
| 20221230T15:04:29Z | Null | https://github.com/DmodvGH/BackDoorBot | 5 | 0| 
| 20221230T02:43:08Z | Hola 👋,  hise esta script se trata de un simple backdoor hecho en bash , lo que hace es interactuar dentro del termux de la victima como si fueras el dueño jeje , SU USO NO ES MI RESPONSABILIDAD ATT.MRX~HACKS | https://github.com/MRX90902WX/Backip | 0 | 0| 
| 20221230T00:45:31Z | lazer is a backdoor for osu! | https://github.com/LMNYX/osu-scoreforger | 0 | 0| 
| 20221230T00:34:07Z | A unauthenticated backdoor exists in the configuration server functionality of Cosori Smart 5.8-Quart Air Fryer CS158-AF 1.1.0. A specially crafted JSON object can lead to code execution. An attacker can send a malicious packet to trigger this vulnerability. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-28593 | 0 | 0| 
| 20221229T23:52:12Z | The exotel (aka exotel-py) package in PyPI as of 0.1.6 includes a code execution backdoor inserted by a third party. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-38792 | 0 | 0| 
| 20221229T18:48:31Z | Null | https://github.com/Marat-terabyte/backdoor | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221230T13:45:11Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3261 | 459| 
| 20221230T12:54:28Z | A native symbolic execution engine for WebAssembly | https://github.com/HNYuuu/SeeWasm | 18 | 2| 
| 20221230T03:28:31Z | Fast symbolic execution engine | https://github.com/connorskees/symbolic-execution | 1 | 0| 
| 20221230T01:35:01Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 283 | 66| 
| 20221229T21:36:09Z | In vow, there is a possible information disclosure due to a symbolic link following. This could lead to local information disclosure with System execution privileges needed. User interaction is not needed for exploitation. Patch ID: ALPS06545473; Issue ID: ALPS06545473. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-26456 | 0 | 0| 
| 20221227T20:41:36Z | Open-source symbolic execution framework: https://maat.re | https://github.com/trailofbits/maat | 525 | 30| 
| 20221227T19:01:14Z | The npm package %tar% (aka node-tar) before versions 4.4.18, 5.0.10, and 6.1.9 has an arbitrary file creation/overwrite and arbitrary code execution vulnerability. node-tar aims to guarantee that any file whose location would be modified by a symbolic link is not extracted. This is, in part, achieved by ensuring that e CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-37712 | 0 | 0| 
| 20221227T19:01:10Z | The npm package %tar% (aka node-tar) before versions 4.4.16, 5.0.8, and 6.1.7 has an arbitrary file creation/overwrite and arbitrary code execution vulnerability. node-tar aims to guarantee that any file whose location would be modified by a symbolic link is not extracted. This is, in part, achieved by ensuring that ex CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-37701 | 0 | 0| 
| 20221227T16:08:14Z | There exists a path traversal vulnerability in the Android Google Search app. This is caused by the incorrect usage of uri.getLastPathSegment. A symbolic encoded string can bypass the path logic to get access to unintended directories. An attacker can manipulate paths that could lead to code execution on the device. We CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-29580 | 0 | 0| 
| 20221227T08:28:02Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 26 | 5| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221230T16:54:18Z | Statistics of acceptance rate for the top conferences: Oakland, CCS, USENIX Security, NDSS. | https://github.com/liupuz/Computer-Security-Conference-Acceptance-Rate | 2 | 2| 
| 20221229T09:25:47Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 66 | 15| 
| 20221227T01:55:03Z | Shell Extension para exibir os ícones de roms do Nintendo DS no Windows Explorer | https://github.com/pablorobert/NDSShellExtension | 0 | 0| 
| 20221224T12:55:54Z | ConfFuzz NDSS Data Set | https://github.com/conffuzz/conffuzz-ndss-data | 0 | 0| 
| 20221219T01:54:46Z | A curated list of Meachine learning Security & Privacy papers published in security top-4 conferences (IEEE S&P, ACM CCS, USENIX Security and NDSS). | https://github.com/gnipping/Awesome-ML-SP-Papers | 23 | 2| 
| 20221212T19:19:12Z | Dynamic Proof of Retrievability using Verifiable Computation and Error Correction Code (NDSS%23) | https://github.com/vt-asaplab/porla | 2 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221231T00:38:23Z | Null | https://github.com/duber000/fuzzy-octo-chainsaw | 0 | 0| 
| 20221230T23:10:45Z | Fast approximate string matching. | https://github.com/tomukmatthews/fuzzy-lightning | 1 | 0| 
| 20221230T22:18:42Z | Null | https://github.com/luigivezzoso/ws-fuzzer | 0 | 0| 
| 20221230T22:15:44Z | Null | https://github.com/ChekrounMohammed/Fuzzy-Labs-technical-test | 0 | 0| 
| 20221230T20:44:19Z | Null | https://github.com/rnphilp/fuzzy-goggles | 0 | 0| 
| 20221230T20:28:41Z | Null | https://github.com/akilaranabahu/Diagnosis-Heart-Disease-with-Fuzzy-Reasoning | 0 | 0| 
| 20221230T18:49:07Z | Null | https://github.com/kevinjurow375/fuzzy-umbrella | 0 | 0| 
| 20221230T16:35:33Z | Null | https://github.com/kamosah/fuzzy-memory | 0 | 0| 
| 20221230T15:20:11Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8210 | 1792| 
| 20221230T13:58:36Z | Null | https://github.com/Sookchand/Fuzzy-Logic-Washing-Machine | 0 | 0| 



# 日更新程序
