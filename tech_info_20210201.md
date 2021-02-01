# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210201 | 安恒对黑客利用 VS 工程渗透安全研究员事件的分析 | https://ti.dbappsecurity.com.cn/blog/index.php/2021/01/26/lazarus-new-campaign/| 
| 20210201 | BitLocker touch-device lockscreen bypass | https://secret.club/2021/01/29/touch-lockscreen-bypass.html| 
| 20210201 | 上周推送的 sudo 溢出漏洞的 Exploit | https://github.com/r4j0x00/exploits/tree/master/CVE-2021-3156| 
| 20210201 | 有研究员发表 paper 指出，Google 基于 UDP 实现的 QUIC 协议更容易通过 Web 指纹技术泄露用户隐私 | https://www.theregister.com/2021/01/30/quic_fingerprinting_flaw/| 
| 20210201 | Google 如何利用漏洞报告计划（VRP）等来源数据加强 Android 安全性 | https://security.googleblog.com/2021/01/data-driven-security-hardening-in.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+GoogleOnlineSecurityBlog+%28Google+Online+Security+Blog%29| 
| 20210201 | 利用 MediaTek BootROM Exploit 恢复变砖的 Android 手机 | https://tinyhack.com/2021/01/31/dissecting-a-mediatek-bootrom-exploit/| 
| 20210201 | Detecting the Leverage of INF-SCT Fetch & Execute Techniques | https://0xbandar.medium.com/detecting-the-leverage-of-inf-sct-fetch-execute-techniques-beca55e24d50?source=social.tw| 
| 20210201 | Windows 平台 EDR 产品绕过方法总结 | https://s3cur3th1ssh1t.github.io/A-tale-of-EDR-bypass-methods/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210201 | 代码审计 PHP基础（一） | https://www.sec-in.com/article/848| 
| 20210201 | 浅谈溯源思维 | https://www.anquanke.com/post/id/229474| 
| 20210201 | 2020网络金融黑产研究报告 | https://mp.weixin.qq.com/s/B_pREKw4SJQjpbVbQLl33w| 
| 20210201 | 智能终端隐私防跟踪技术实践 | https://mp.weixin.qq.com/s/II5q4tYyZ3JUD4vHy1Fx6A| 
| 20210201 | 云安全架构连载之一-Azure整体架构及安全亮点详解 | https://mp.weixin.qq.com/s/QNBlsBJaWNXsZLEuNRQcvQ| 
| 20210201 | python编译后的pyd爆破 | https://mp.weixin.qq.com/s/JvQ38Isf1xXcGOe5wDgXWw| 
| 20210201 | 基于复杂图的 DDoS 攻击团伙发现与跟踪 | https://mp.weixin.qq.com/s/xz3XDHVg2jzMc6Sv-o8YTw| 
| 20210201 | SecWiki周刊（第361期) | https://www.sec-wiki.com/weekly/361| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210201T13:31:15Z | CVE-2021-3156 | Null | https://github.com/blasty/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T13:22:55Z | CVE-2021-3156 | PoC for CVE-2021-3156 (sudo heap overflow) | https://github.com/stong/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T13:20:48Z | CVE-2020-7247 | This vulnerability exists in OpenBSD’s mail server OpenSMTPD’s “smtp_mailaddr()” function, and affects OpenBSD version 6.6. This allows an attacker to execute arbitrary shell commands like “sleep 66” as root user | https://github.com/jopraveen/CVE-2020-7247 | smtp_mailaddr in smtp_session.c in OpenSMTPD 6.6, as used in OpenBSD 6.6 and other products, allows remote attackers to execute arbitrary commands as root via a crafted SMTP session, as demonstrated by shell metacharacters in a MAIL FROM field. This affects the %uncommented% default configuration. The issue exists because of an incorrect return value upon failure of input validation.| 
| 20210201T11:24:51Z | CVE-2021-3156 | Patch Script for CVE-2021-3156 Heap Overflow | https://github.com/Ashish-dawani/CVE-2021-3156-Patch | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T11:24:20Z | CVE-2021-3156 | CVE-2021-3156 | https://github.com/reverse-ex/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T08:16:06Z | CVE-2021-3156 | A docker environment to research CVE-2021-3156 | https://github.com/apogiatzis/docker-CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T07:25:43Z | CVE-2021-3156 | Null | https://github.com/kal1gh0st/CVE-2021-3156 | | 
| 20210201T06:40:02Z | CVE-2021-3156 | Notes regarding CVE-2021-3156: Heap-Based Buffer Overflow in Sudo | https://github.com/mbcrump/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T05:41:41Z | CVE-2021-3156 | Null | https://github.com/ltfafei/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T05:02:49Z | CVE-2021-3156 | Null | https://github.com/teamtopkarl/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210201T11:59:33Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 212 | 34| 
| 20210201T11:15:37Z | An open-source Chinese font derived from Fontworks% Klee One | https://github.com/lxgw/LxgwWenKai | 5 | 0| 
| 20210201T08:49:00Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1621 | 481| 
| 20210201T07:43:39Z | Null | https://github.com/jiseongg/klee_experiment | 0 | 0| 
| 20210201T05:01:53Z | Spring 2021 Geography 817 work folder  | https://github.com/klee12/klee12.github.io | 0 | 0| 
| 20210201T01:00:26Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 1 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210201T04:58:11Z | s2e develop  | https://github.com/xqx12/xqx | 6 | 12| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210201T13:30:22Z | Vulmap 是一款 web 漏洞扫描和验证工具, 可对 webapps 进行漏洞扫描, 并且具备漏洞利用功能 | https://github.com/zhzyker/vulmap | 858 | 155| 
| 20210201T13:30:13Z | Some tools and exploits for the NVIDIA Falcon v5 TSEC engines.  | https://github.com/CAmadeus/falcon-tools | 9 | 1| 
| 20210201T13:24:24Z | CDK is an open-sourced container penetration toolkit, offering stable exploitation in different slimmed containers without any OS dependency. It comes with penetration tools and many powerful PoCs/EXPs helps you to escape container and takeover K8s cluster easily. | https://github.com/cdk-team/CDK | 1028 | 139| 
| 20210201T13:19:55Z | SSH bruteforce because I don%t like the one on exploit-db.  | https://github.com/ghostr3con/ssh-brute | 0 | 0| 
| 20210201T13:17:00Z | TryHackMe CTFs writeups, notes, dratfs, scrabbles, files and solutions. | https://github.com/edoardottt/tryhackme-ctf | 9 | 7| 
| 20210201T13:05:21Z | Security patch for the XBox Live Gamertag exploit | https://github.com/SynHCF/AntiXBLExploit | 2 | 0| 
| 20210201T12:53:58Z | Exploit of CVE-2019-8942 and CVE-2019-8943  | https://github.com/v0lck3r/CVE-2019-8943 | 0 | 0| 
| 20210201T12:49:56Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 7 | 4| 
| 20210201T12:20:12Z | exp for useful vuln | https://github.com/saucer-man/exploit | 0 | 0| 
| 20210201T12:15:46Z | ASLR Evasion, Egghunters, SEH Overwrites | https://github.com/freddiebarrsmith/Advanced-Windows-Exploit-Development-Practice | 9 | 1| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210201T11:48:08Z | Pytorch implementation of our paper Backdoor Attack against Speaker Verification | https://github.com/zhaitongqing233/Backdoor-attack-against-speaker-verification | 1 | 1| 
| 20210201T11:39:28Z | just a simple and easy to understand python backdoor | https://github.com/Tab135/simple-python-backdoor | 0 | 0| 
| 20210201T10:57:45Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 161 | 23| 
| 20210201T10:53:05Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 34 | 8| 
| 20210201T10:02:20Z | Installs a persistent backdoor binary on android devices with unlocked bootloader via TWRP that runs as system daemon with root permissions and without SELinux restrictions | https://github.com/LuigiVampa92/unlocked-bootloader-backdoor-demo | 0 | 0| 
| 20210201T09:15:42Z | Null | https://github.com/rabbitx1337/backdoor | 0 | 0| 
| 20210201T02:49:05Z | Null | https://github.com/SourceCode1037/Backdoor-Attacks | 1 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210201T12:56:05Z | А procedural macro to be used for testing/fuzzing stateful models against a semantically equivalent but obviously correct implementation | https://github.com/jakubadamw/rutenspitz | 42 | 3| 
| 20210201T12:55:46Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3327 | 769| 
| 20210201T12:51:45Z | Null | https://github.com/juanjomendez/FuzzyLogicTest | 0 | 0| 
| 20210201T12:41:16Z | Histogram Method of Image Binarization Based on Fuzzy Pixel Representation | https://github.com/abustaoglu/ImageBinarization-FuzzyPixelRepresentation | 0 | 0| 
| 20210201T12:39:53Z | A JavaScript Engine Fuzzer | https://github.com/googleprojectzero/fuzzilli | 1140 | 198| 
| 20210201T11:50:07Z | Null | https://github.com/kinzhong/fuzzing-automation-tools | 0 | 0| 
| 20210201T11:38:44Z | Operations on fuzzy sets (program implemented as part of programming engineering studies) | https://github.com/Pomianowski/Fuzzy | 0 | 0| 
| 20210201T11:33:23Z | Null | https://github.com/ethereum/solidity-fuzzing-corpus | 10 | 4| 
| 20210201T10:20:10Z | Null | https://github.com/MRNOBODY-ZST/fuzzy-lamp | 0 | 0| 
| 20210201T10:00:35Z | {golang, ptrace, snapshot}-based fuzzer | https://github.com/geeksonsecurity/snapandgo | 2 | 0| 



# 日更新程序
