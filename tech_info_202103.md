# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210302 | What’s Your Game Plan? Leveraging Apple’s Game Engine to Detect Threats | https://www.rsaconference.com/library/Presentation/USA/2019/whats-your-game-plan-leveraging-apples-game-engine-to-detect-threats-3?utm_source=twitter&utm_medium=social&utm_content=whats-your-game-plan-leveraging-apples-game-engine-to-detect-threats-presentation&utm_campaign=march-20201-rsac365&postID=4532250272| 
| 20210302 | Apple 正在为 ISA 指针提供 PAC 保护，iOS 代码执行更加艰难 | https://www.vice.com/en/article/pkd4kg/apple-is-going-to-make-it-harder-to-hack-iphones-with-zero-click-attacks| 
| 20210302 | iOS 降级工具 futurerestore 更新 v194 版本 | https://github.com/marijuanARM/futurerestore/releases/tag/194| 
| 20210302 | libkrw - 为不同越狱工具提供一个 iOS kernel 读写 API 接口 | https://github.com/Siguza/libkrw| 
| 20210302 | 训练 Robust Trees 检测 Twitter spam | https://surrealyz.medium.com/robust-trees-for-security-577061177320| 
| 20210302 | Finding Evil Go Packages | https://michenriksen.com/blog/finding-evil-go-packages/| 
| 20210302 | CVE-2020-28243 SaltStack Minion 命令行注入本地提权漏洞 | https://sec.stealthcopter.com/cve-2020-28243/| 
| 20210301 | 去年 Black Hat USA 2020 会议的议题视频全部公开了 | https://www.youtube.com/playlist?list=PLH15HpR5qRsXE_4kOSy_SXwFkFQre4AV_| 
| 20210301 | BlackHat USA 2020 会议 “iOS Kernel PAC, One Year Later” 议题的视频 | https://www.youtube.com/watch?v=7zCBOFxATFs&feature=youtu.be| 
| 20210301 | 研究员 Hardik Shah 在 Grayhat 2020 会议的 Fuzzing Workshop 资料 | https://github.com/hardik05/Conferences/tree/main/Grayhat2020| 
| 20210301 | HMDM - 基于 physmeme 项目，将未签名代码直接映射到内核的工具，可以用于漏洞研究学习 | https://githacks.org/_xeroxz/hmdm| 
| 20210301 | Linux 内核 CVE-2020-14381 漏洞的分析 | https://blog.frizn.fr/linux-kernel/cve-2020-14381| 
| 20210301 | Cosmopolitan Libc - 将 C 代码真正编译成跨平台执行的库，一次编译，支持在 Linux + Mac + Windows + FreeBSD + OpenBSD + NetBSD + BIOS 直接 Native 执行。 | https://ahgamut.github.io/c/2021/02/27/ape-cosmo/| 
| 20210301 | Apple 漏洞致谢数全球第一背后的新攻击面 & 一洞攻破 Safari | https://paper.seebug.org/1490/| 
| 20210301 | SaltStack 远程执行代码存在多个高危漏洞分析（CVE-2021-25281 ，CVE-2021-25282， CVE-2021-25283） | https://sec.today/pulses/1bd5fa4b-65f8-4f7a-8ad3-3f339022a1a1/| 
| 20210301 | SaltStack 远程执行代码存在多个高危漏洞分析（CVE-2021-25281 ，CVE-2021-25282， CVE-2021-25283） | https://paper.seebug.org/1491/| 
| 20210301 | 进行对Kernsomware勒索软件分析溯源。 | https://cert-agid.gov.it/news/kernsomware/| 
| 20210301 | 使用WinAFL进行模糊处理和查找漏洞视频。 | https://www.youtube.com/watch?v=m7tJkeW6H58&t=394s| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210302 | 红蓝对抗中的云原生漏洞挖掘及利用实录 | https://mp.weixin.qq.com/s/Aq8RrH34PTkmF8lKzdY38g| 
| 20210302 | PCAP-ATTACK: PCAP Samples for Different Post Exploitation ... | https://github.com/sbousseaden/PCAP-ATTACK| 
| 20210302 | VMware vCenter RCE (CVE-2021-21972) 漏洞复现与 Exp 编写 | https://mp.weixin.qq.com/s/2pvaQborwMM8UHnWS_CeXA| 
| 20210302 | IOT安全（二）——再探stm32 | https://www.anquanke.com/post/id/231440| 
| 20210301 | SecWiki周刊（第365期) | https://www.sec-wiki.com/weekly/365| 
| 20210301 | 恶意软件分析工具集成环境 | https://mp.weixin.qq.com/s/WMWQUWu8dt45iQsrcLfSxg| 
| 20210301 | 大白话解释拟态安全 | https://mp.weixin.qq.com/s/UR0XbF02JJmo7RbNF1CYVw| 
| 20210301 | 浅谈如何有效落地DevSecOps | https://mp.weixin.qq.com/s/5eX3-SCfvFfRitb9_onjvw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210302T12:54:02Z | CVE-2021-21315 | CVE 2021-21315 PoC | https://github.com/ForbiddenProgrammer/CVE-2021-21315-PoC | The System Information Library for Node.JS (npm package %systeminformation%) is an open source collection of functions to retrieve detailed hardware, system and OS information. In systeminformation before version 5.3.1 there is a command injection vulnerability. Problem was fixed in version 5.3.1. As a workaround instead of upgrading, be sure to check or sanitize service parameters that are passed to si.inetLatency(), si.inetChecksite(), si.services(), si.processLoad() ... do only allow strings, reject any arrays. String sanitation works as expected.| 
| 20210302T12:52:49Z | CVE-2021-27246 | Null | https://github.com/synacktiv/CVE-2021-27246_Pwn2Own2020 | 未查询到CVE信息| 
| 20210302T12:47:52Z | CVE-2021-21972 | Nmap script to check vulnerability CVE-2021-21972 | https://github.com/GuayoyoLabs/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210302T10:11:28Z | CVE-2021-21972 | CVE-2021-21972 Exploit | https://github.com/NS-Sp4ce/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210302T10:10:10Z | CVE-2021-21972 | CVE-2021-21972 | https://github.com/milo2012/CVE-2021-21972 | | 
| 20210302T10:06:41Z | CVE-2021-9999 | Null | https://github.com/GG-o1/CVE-2021-9999 | 未查询到CVE信息| 
| 20210302T10:02:08Z | CVE-2021-25281 | Chaining CVE-2021-25281 and CVE-2021-25282 to exploit a SaltStack | https://github.com/Immersive-Labs-Sec/CVE-2021-25281 | An issue was discovered in through SaltStack Salt before 3002.5. salt-api does not honor eauth credentials for the wheel_async client. Thus, an attacker can remotely run any wheel modules on the master.| 
| 20210302T08:11:29Z | CVE-2021-21972 | Null | https://github.com/QmF0c3UK/CVE-2021-21972-vCenter-6.5-7.0-RCE-POC | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210302T07:55:24Z | CVE-2021-21972 | Proof of Concept Exploit for vCenter CVE-2021-21972 | https://github.com/horizon3ai/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210301T23:20:52Z | CVE-2021-21972 | VMware vCenter CVE-2021-21972 Tools | https://github.com/robwillisinfo/VMware_vCenter_CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210302T08:46:04Z | a leetcode question each day, your salary increment $100 per day | https://github.com/guoxiangCN/kLeetcode | 0 | 0| 
| 20210302T06:24:14Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 109 | 4| 
| 20210301T15:33:25Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210301T11:45:19Z | Null | https://github.com/fontworks-fonts/Klee | 370 | 10| 
| 20210301T10:06:41Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1637 | 483| 
| 20210301T04:28:58Z | Null | https://github.com/abbykleespie/A2AbbyKleespie.appstudio | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210302T13:26:06Z | exploiting and defending neural networks(神经网络攻防专栏) | https://github.com/AIPwn/HackingNeuralNetworks | 2 | 0| 
| 20210302T13:02:28Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 9 | 4| 
| 20210302T12:40:34Z | Just a temporary website to post my ctf writeups and journey into binary exploitation/malware analysis/exploit development | https://github.com/blackbeard666/blackbeard666.github.io | 0 | 0| 
| 20210302T12:12:45Z | An example that shows ANTLR syntax features for specification and usage rules attributes, return values, parameters etc | https://github.com/dhmhgreCompilersII/RulesFeaturesExploitationCSV | 0 | 0| 
| 20210302T11:56:45Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9073 | 1460| 
| 20210302T11:49:18Z | A thorough library database to assist with binary exploitation tasks. | https://github.com/0xb0bb/karkinos | 170 | 16| 
| 20210302T11:43:27Z | Ronin is a Ruby platform for vulnerability research and exploit development. Ronin allows for the rapid development and distribution of code, Exploits or Payloads, Scanners, etc, via Repositories. | https://github.com/ronin-rb/ronin | 216 | 19| 
| 20210302T11:36:04Z | Ready, Aim, Fire. | https://github.com/Fricciolosa-Red-Team/mobile-heavy-artillery | 1 | 0| 
| 20210302T11:33:21Z | xcube is a Python package for generating and exploiting data cubes powered by xarray, dask, and zarr. | https://github.com/dcs4cop/xcube | 70 | 12| 
| 20210302T11:31:27Z | Unnamed PS1 save game backup loader thing | https://github.com/socram8888/PS1SaveExploit | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210302T13:15:10Z | Null | https://github.com/Wiilldd/backdoor | 0 | 0| 
| 20210302T12:49:37Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 183 | 26| 
| 20210302T08:45:25Z | Null | https://github.com/iK4oS/PremiumBackdoor.exe | 0 | 1| 
| 20210302T08:39:49Z | Thefatrat a massive exploiting tool : Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack and etc . This tool compiles a malware with popular payload and then the compiled malware can be execute on windows, android, mac . The malware that created with this tool also have an ability to bypass most AV software protection . | https://github.com/Screetsec/TheFatRat | 4992 | 1644| 
| 20210302T08:26:20Z | 🤖 AI based Backdoor Written for Windows using Telegram-bot as Its Back-ends. | https://github.com/wildonion/katyusha | 1 | 1| 
| 20210301T21:26:11Z | Null | https://github.com/EjHvorSerDuVildUdJim/backdoor | 0 | 0| 
| 20210301T18:22:09Z | Null | https://github.com/ph-luffy/Backdoor | 1 | 1| 
| 20210301T17:12:01Z | backdoor uiuiuiui | https://github.com/zeru2/backdoor | 0 | 0| 
| 20210301T16:50:18Z | Fud Persistent Windows Backdoor developed purely in python | https://github.com/swagkarna/Chuvi-Botnet | 13 | 5| 
| 20210301T16:31:58Z | Null | https://github.com/angelo1104/backdoor-node | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210302T13:05:37Z | Null | https://github.com/lacygoill/vim-fuzzy | 0 | 0| 
| 20210302T13:05:03Z | A fuzzer that generates random Go programs | https://github.com/ALTree/microsmith | 7 | 0| 
| 20210302T12:48:36Z | Ethereum smart contract fuzzer | https://github.com/crytic/echidna | 557 | 95| 
| 20210302T12:24:54Z | Null | https://github.com/erdifajarf/PMDK_FuzzyAHP | 0 | 0| 
| 20210302T12:18:16Z | The Book %Generating Software Tests% | https://github.com/uds-se/fuzzingbook | 533 | 106| 
| 20210302T12:17:41Z | Fuzzy C-Means Clustering | https://github.com/NIZAMM383/Fuzzy-C-Means-Clustering-on-Iris-Dataset | 0 | 0| 
| 20210302T12:14:45Z | White-box fuzzer for Java bytecode | https://github.com/vorpal-research/kex | 6 | 5| 
| 20210302T12:14:44Z | PoC of fuzzing closed-source userspace binaries with KVM | https://github.com/klecko/kvm-fuzz | 0 | 0| 
| 20210302T12:12:17Z | Implementation of Wang-Mende and Takagi-Sugeno fuzzy structures in virtual flow sensor. | https://github.com/SebastianParzych/Fuzzy-logic | 0 | 0| 
| 20210302T11:57:38Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3382 | 777| 



# 日更新程序
