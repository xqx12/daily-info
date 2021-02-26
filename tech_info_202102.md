# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210225 | Top 10 web hacking techniques of 2020 | https://portswigger.net/research/top-10-web-hacking-techniques-of-2020| 
| 20210225 | Issue 1144662: Bypassing ASLR using Oilpan’s conservative garbage collector | https://bugs.chromium.org/p/chromium/issues/detail?id=1144662| 
| 20210225 | VMware vCenter RCE 漏洞的分析（CVE-2021-21972） | https://swarm.ptsecurity.com/unauth-rce-vmware/| 
| 20210225 | Google 赞助 Linux 内核开发者，加强对内核安全的重视 | https://linuxfoundation.org/en/press-release/google-funds-linux-kernel-developers-to-focus-exclusively-on-security/?utm_content=155274503&utm_medium=social&utm_source=twitter&hss_channel=tw-14706299| 
| 20210225 | 微软更新了一些基于 Intel CET 的保护机制 | https://techcommunity.microsoft.com/t5/windows-kernel-internals/developer-guidance-for-hardware-enforced-stack-protection/ba-p/2163340| 
| 20210225 | Riscure 安全团队对三星 TEE、TrustZone 的研究 | https://www.riscure.com/blog/samsung-investigation-part1| 
| 20210225 | Issue 2122: Chrome: OOB-read in network DataElement struct traits | https://bugs.chromium.org/p/project-zero/issues/detail?id=2122| 
| 20210225 | Who’s Debugging the Debuggers? Exposing DebugInformation Bugs in Optimized Binaries | https://download.vusec.net/papers/debug2_asplos21.pdf| 
| 20210225 | Kali Linux 2021.1发行版 | https://www.kali.org/blog/kali-linux-2021-1-release/| 
| 20210225 | 2020年的PHPWind RCE漏洞复现视频。 | https://blog.orange.tw/2021/02/a-journey-combining-web-and-binary-exploitation.html| 
| 20210224 | VMware官方揭露了vSphere套件在HTML5客户端中的存在严重漏洞。 | https://www.theregister.com/2021/02/23/vmware_vsphere_critical_bugs/| 
| 20210224 | 由CrowdStrike威胁情报团队发布的《 CrowdStrike 2021年全球威胁报告》 | https://www.crowdstrike.com/resources/reports/global-threat-report/| 
| 20210224 | 研究人员近期发现一种新颖“”影子攻击”，并破坏数字签名PDF文档的安全性。 | https://thehackernews.com/2021/02/shadow-attacks-let-attackers-replace.html| 
| 20210224 | 学习如何解压缩ASPack恶意软件视频教程。 | https://www.youtube.com/watch?v=L0NwUMU-Pj4| 
| 20210223 | 有开发者开源的一款 macOS、iOS 日志可视化和日志共享工具 | https://github.com/kean/Pulse| 
| 20210223 | Farming for Red Teams: Harvesting NetNTLM | https://www.mdsec.co.uk/2021/02/farming-for-red-teams-harvesting-netntlm/| 
| 20210223 | 去年天府杯 Chrome Full Chain Exploit 代码公开了 | https://bugs.chromium.org/p/chromium/issues/detail?id=1146670| 
| 20210223 | 据 Checkpoint 报告，APT31 在 NSA 方程式 CVE-2017-0005 0day 泄露之前就使用了该漏洞 | https://research.checkpoint.com/2021/the-story-of-jian/| 
| 20210223 | 攻击者利用 Accellion FTA 文件传输应用的 0Day 窃取数据 | https://www.fireeye.com/blog/threat-research/2021/02/accellion-fta-exploited-for-data-theft-and-extortion.html| 
| 20210223 | Windows 注册表中 RpcEptMapper 键权限设置不当导致可以实现本地提权 | https://itm4n.github.io/windows-registry-rpceptmapper-exploit/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210225 | 业务安全的上岸体历 | https://www.sec-in.com/article/890| 
| 20210224 | f8x: 红/蓝队环境自动化部署工具 | https://github.com/ffffffff0x/f8x| 
| 20210224 | JAVA安全基础（二）-- 反射机制 | https://xz.aliyun.com/t/9117| 
| 20210224 | DA14531芯片固件逆向系列（2）- 操作系统底层机制分析 | https://xz.aliyun.com/t/9186| 
| 20210224 | 红蓝对抗之邮件伪造 | https://mp.weixin.qq.com/s/tOOBZ1aC6SsjslCM70WKBQ| 
| 20210224 | 钓鱼基础设施的应用分析 | https://www.anquanke.com/post/id/231444| 
| 20210224 | Angr源码阅读笔记01 | https://www.anquanke.com/post/id/231460| 
| 20210224 | 如何隐蔽你的C2 | https://www.anquanke.com/post/id/231448| 
| 20210224 | 恶意代码检测的本质性思考 | https://zhuanlan.zhihu.com/p/352004681| 
| 20210224 | A Cyber Threat Intelligence Self-Study Plan: Part 1 | https://medium.com/katies-five-cents/a-cyber-threat-intelligence-self-study-plan-part-1-968b5a8daf9a| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210226T02:40:21Z | CVE-2021-21972 | Null | https://github.com/QmF0c3UK/CVE-2021-21972-vCenter-6.5-7.0-RCE-POC | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210226T02:38:42Z | CVE-2021-00092 | Null | https://github.com/taomujian/CVE-2021-00092 | 未查询到CVE信息| 
| 20210226T02:35:14Z | CVE-2021-21972 | VMware vCenter 未授权RCE（CVE-2021-21972） | https://github.com/conjojo/VMware_vCenter_UNAuthorized_RCE_CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210226T02:34:11Z | CVE-2021-21972 | CVE-2021-21972 Exploit | https://github.com/NS-Sp4ce/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210226T02:13:58Z | CVE-2022-0109 | Null | https://github.com/taomujian/CVE-2022-0109 | 未查询到CVE信息| 
| 20210226T01:57:28Z | CVE-2021-21972 | Null | https://github.com/L-pin/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210226T01:42:04Z | CVE-2021-21972 | Proof of Concept Exploit for vCenter CVE-2021-21972 | https://github.com/horizon3ai/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210226T01:35:52Z | CVE-2021-21972 | CVE-2021-21972 | https://github.com/milo2012/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210225T23:30:14Z | CVE-2021-21972 | Null | https://github.com/alt3kx/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210225T21:08:18Z | CVE-2021-21972 | VMware vCenter Server远程代码执行漏洞 (CVE-2021-21972)批量检测脚本 | https://github.com/B1anda0/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210225T21:55:49Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210225T17:50:52Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 109 | 7| 
| 20210225T16:36:23Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 5 | 1| 
| 20210225T13:44:58Z | Null | https://github.com/pushkarkishore/klee_test | 0 | 0| 
| 20210225T10:49:07Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1634 | 483| 
| 20210225T01:40:47Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 102 | 4| 
| 20210224T21:09:42Z | Null | https://github.com/abbykleespie/LAWeek4AbbyKleespie.appstudio | 0 | 0| 
| 20210224T10:01:07Z | a leetcode question each day, your salary increment $100 per day | https://github.com/guoxiangCN/kLeetcode | 0 | 0| 
| 20210224T09:27:44Z | Safe KLEE API for Rust | https://github.com/markhakansson/klee-rs | 0 | 0| 
| 20210224T05:56:00Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 6 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210220T17:34:12Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 97 | 22| 
| 20210219T07:34:16Z | Null | https://github.com/Anubhab1997/s2ecomm | 0 | 0| 
| 20210214T11:48:35Z | S2E website (s2e.systems) | https://github.com/S2E2/s2e2.github.io | 0 | 0| 
| 20210214T11:46:48Z | Your S2E project management tools. Visit https://s2e.systems/docs to get started. | https://github.com/S2E/s2e-env | 71 | 30| 
| 20210201T04:58:11Z | s2e develop  | https://github.com/xqx12/xqx | 6 | 12| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210226T02:02:43Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 9 | 4| 
| 20210226T01:21:34Z | CTF framework and exploit development library | https://github.com/Gallopsled/pwntools | 7568 | 1359| 
| 20210226T01:00:10Z | forked version of funtuna, a homebrew ps2 app launcher designed to ease the pain of getting a stable exploit for those that have a console uncompatible with FreeMcBoot that doesnt have a modchip | https://github.com/israpps/Funtuna-Fork | 2 | 0| 
| 20210226T00:52:32Z | A C# Version Of Checkra1n That Is Able To Esculate User Privilleges Based On The Checkm8 BootRom Exploit. | https://github.com/0x422/SharpRa1n | 0 | 0| 
| 20210226T00:50:12Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 7 | 5| 
| 20210226T00:37:49Z | Kill any Android VPN in the browser, and expose the client%s real IP address. | https://github.com/noarchwastaken/vpn_killer | 0 | 0| 
| 20210226T00:37:15Z | Exploits for Sync-Breeze  | https://github.com/laordenhacker/Sync-Breeze | 0 | 0| 
| 20210226T00:14:22Z | This is a chrome extension that removes the psychological exploit that is Reddit Karma | https://github.com/BeckTimothy/reddit-volition | 0 | 0| 
| 20210226T00:11:49Z | Collection of bash scripts I wrote to make my life easier or test myself that you may find useful. | https://github.com/tobor88/Bash | 11 | 4| 
| 20210225T23:23:44Z | Xiongmai Exploitation Toolkit | https://github.com/redcodefinal/xet | 3 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210226T01:08:20Z | Python Backdoor Generator | https://github.com/grenoxx/Back-X | 5 | 1| 
| 20210225T20:44:22Z | Null | https://github.com/Wiilldd/backdoor | 0 | 0| 
| 20210225T20:07:49Z | Trojan backdoor made in python and Tkinter framework | https://github.com/sehji/Backdoor-Trojan-Virus | 0 | 0| 
| 20210225T18:07:01Z | backdoor uiuiuiui | https://github.com/zeru2/backdoor | 0 | 0| 
| 20210225T15:29:51Z | 🔌 Minecraft plugin which allow you to execute OS commands | https://github.com/L1ghtM4n/BackdoorPlugin | 1 | 0| 
| 20210225T14:36:25Z | Full-featured C2 framework which silently persists on webserver with a single-line PHP backdoor | https://github.com/nil0x42/phpsploit | 1165 | 332| 
| 20210225T14:02:41Z | A sample app to demonstrate how to create Xamarin UITests using the Page Object architecture, Backdoor Methods and App Links (aka Deep Linking) | https://github.com/brminnick/UITestSampleApp | 33 | 25| 
| 20210225T13:38:16Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 177 | 26| 
| 20210225T08:51:53Z | Inject backdoor payload inside windows process id. | https://github.com/th1k/payload-inject0r | 0 | 0| 
| 20210225T08:49:12Z | Cross Platform Java Remote Access And Post Exploitation Framework targeting Windows with a multitude of features. Built for Penetration Testers. | https://github.com/quantumcored/remote_hacker_probe | 19 | 5| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210226T02:32:55Z | Null | https://github.com/guardstrikelab/fuzzx_cpp_demo | 0 | 0| 
| 20210226T02:30:11Z | Scalable fuzzing infrastructure. | https://github.com/google/clusterfuzz | 4440 | 421| 
| 20210226T02:22:30Z | We conducted a Controlled Experiment on Blackbox Fuzzing of Ethereum Smart Contracts. | https://github.com/TechBeatle/EthereumControlledExperimentBlackBoxFuzzing | 0 | 0| 
| 20210226T02:21:35Z | This is the main website and system for Ball Fuzz Tennis Center. | https://github.com/Ball-Fuzz-Tennis-Center/tennis-system | 0 | 0| 
| 20210226T01:55:45Z | Fuzzy AHP Scholarship Desicion | https://github.com/zekhoi/fuzzyahp | 0 | 0| 
| 20210226T01:34:00Z | Null | https://github.com/Pluviophile-BT/MK_FUZZ | 0 | 0| 
| 20210226T01:12:29Z | Fuzzing Based on Seed Importance By Interprocedural Control Flow Graph | https://github.com/xiaoxiongwang/FunAFL | 0 | 0| 
| 20210226T00:47:35Z | Null | https://github.com/mpos2m/fuzzy-octo-palm-tree | 0 | 0| 
| 20210226T00:39:41Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 6 | 1| 
| 20210226T00:35:25Z | Fast web fuzzer written in Go | https://github.com/ffuf/ffuf | 3993 | 474| 



# 日更新程序
