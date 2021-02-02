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
| 20210201 | 针对流行的开源软件包中的Web缓存中毒安全分析。 | https://snyk.io/blog/cache-poisoning-in-popular-open-source-packages/| 


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
| 20210201T18:50:08Z | CVE-2021-3156 | Null | https://github.com/SantiagoSerrao/ScannerCVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T16:52:28Z | CVE-2021-3156 | 复现别人家的CVEs系列 | https://github.com/Q4n/CVE-2021-3156 | | 
| 20210201T16:51:34Z | CVE-2021-3156 | Null | https://github.com/kal1gh0st/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T16:42:02Z | CVE-2021-3156 | CVE-2021-3156 | https://github.com/reverse-ex/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T15:19:14Z | CVE-2021-3345 | Null | https://github.com/MLGRadish/CVE-2021-3345 | _gcry_md_block_write in cipher/hash-common.c in Libgcrypt before 1.9.1 has a heap-based buffer overflow when the digest final function sets a large count value.| 
| 20210201T13:20:48Z | CVE-2020-7247 | This vulnerability exists in OpenBSD’s mail server OpenSMTPD’s “smtp_mailaddr()” function, and affects OpenBSD version 6.6. This allows an attacker to execute arbitrary shell commands like “sleep 66” as root user | https://github.com/jopraveen/CVE-2020-7247 | smtp_mailaddr in smtp_session.c in OpenSMTPD 6.6, as used in OpenBSD 6.6 and other products, allows remote attackers to execute arbitrary commands as root via a crafted SMTP session, as demonstrated by shell metacharacters in a MAIL FROM field. This affects the %uncommented% default configuration. The issue exists because of an incorrect return value upon failure of input validation.| 
| 20210201T11:24:51Z | CVE-2021-3156 | Patch Script for CVE-2021-3156 Heap Overflow | https://github.com/Ashish-dawani/CVE-2021-3156-Patch | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T08:16:06Z | CVE-2021-3156 | A docker environment to research CVE-2021-3156 | https://github.com/apogiatzis/docker-CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T06:40:02Z | CVE-2021-3156 | Notes regarding CVE-2021-3156: Heap-Based Buffer Overflow in Sudo | https://github.com/mbcrump/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T05:41:41Z | CVE-2021-3156 | Null | https://github.com/ltfafei/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210201T11:59:33Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 212 | 34| 
| 20210201T11:15:37Z | An open-source Chinese font derived from Fontworks% Klee One | https://github.com/lxgw/LxgwWenKai | 5 | 0| 
| 20210201T08:49:00Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1621 | 481| 
| 20210201T07:43:39Z | Null | https://github.com/jiseongg/klee_experiment | 0 | 0| 
| 20210201T05:01:53Z | Spring 2021 Geography 817 work folder  | https://github.com/klee12/klee12.github.io | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210201T04:58:11Z | s2e develop  | https://github.com/xqx12/xqx | 6 | 12| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210201T23:18:54Z | Exploit que executa o CFW automaticamente a cada reinício. Requer o Haxchi. | https://github.com/Nintendo-Homebrew/CBHC | 0 | 0| 
| 20210201T23:18:35Z | This is an integration between Twilio SMS services and api.ai.  | https://github.com/asanta27/Google-Voice-Twilio-Exploit | 2 | 0| 
| 20210201T23:14:16Z | Pillar is a multi channel real time communiaction app exploiting MERN stack%s full potential. The app is purposely crafted with the goal to facilitate efficient group communications | https://github.com/dabaojian1992/Pillar | 0 | 0| 
| 20210201T23:08:17Z | Null | https://github.com/sudo-von/reverse-engineering-and-binary-exploitation-experiments | 0 | 0| 
| 20210201T23:05:09Z | Exploit mais conhecido do Wii, recentemente ultrapassado, capaz de acessar uma brecha no mural de cartas do sistema. | https://github.com/Nintendo-Homebrew/LetterBomb | 0 | 0| 
| 20210201T23:01:12Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 8960 | 1438| 
| 20210201T22:45:35Z | Root shell exploit for several Xiaomi routers: 4A Gigabit, 4A 100M, 4, 4C, 3Gv2, 4Q, miWifi 3C... | https://github.com/acecilia/OpenWRTInvasion | 328 | 67| 
| 20210201T22:33:43Z | A game of spaceships exploiting astroids. | https://github.com/BlackLambert/astrominer | 0 | 0| 
| 20210201T21:55:26Z | Explorations and exploitations of the UWP platform | https://github.com/alexpisquared/UWP | 0 | 0| 
| 20210201T21:49:05Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 4 | 1| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210201T22:41:34Z | Open-Source PowerShell module to allow online play of Backdoors & Breaches card game devised by Black Hills Information Security | https://github.com/TheShiShiLion/BackdoorsAndBreaches | 4 | 0| 
| 20210201T21:21:20Z | A defense model against BadNets (Backdoored Neural Networks) | https://github.com/priyanka-shishodia/Backdoored-DNN-defense | 0 | 0| 
| 20210201T20:24:17Z | Pytorch implementation of Backdoor Attack against Speaker Verification | https://github.com/zhaitongqing233/Backdoor-attack-against-speaker-verification | 2 | 1| 
| 20210201T18:07:04Z | A Remote Administration Tool (RAT) | https://github.com/0xmanjoos/Pieta | 4 | 1| 
| 20210201T11:39:28Z | just a simple and easy to understand python backdoor | https://github.com/Tab135/simple-python-backdoor | 0 | 0| 
| 20210201T10:57:45Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 161 | 23| 
| 20210201T10:53:05Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 34 | 8| 
| 20210201T10:02:20Z | Installs a persistent backdoor binary on android devices with unlocked bootloader via TWRP that runs as system daemon with root permissions and without SELinux restrictions | https://github.com/LuigiVampa92/unlocked-bootloader-backdoor-demo | 0 | 0| 
| 20210201T09:15:42Z | Null | https://github.com/rabbitx1337/backdoor | 0 | 0| 
| 20210201T02:49:05Z | Null | https://github.com/SourceCode1037/Backdoor-Attacks | 1 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210201T23:54:56Z | REST API Fuzz Testing (RAFT): Source code for self-hosted service developed for Azure, including the API, orchestration engine, and default set of security tools (including MSR%s RESTler), that enables developers to embed security tooling into their CI/CD workflows | https://github.com/microsoft/rest-api-fuzz-testing | 95 | 11| 
| 20210201T23:50:17Z | This bot is an community open source discord bot. | https://github.com/nimit2801/fuzzy-bones | 0 | 0| 
| 20210201T23:31:40Z | Effortlessly fuzz libraries with large API surfaces | https://github.com/rust-fuzz/auto-fuzz-test | 33 | 1| 
| 20210201T23:21:58Z | Null | https://github.com/Juanosorio94/fuzzing-rdma | 0 | 0| 
| 20210201T22:52:45Z | Null | https://github.com/Linrisk/fuzzy-guacamole_portfolio | 1 | 0| 
| 20210201T22:31:25Z | Basic URL fuzzer written in GOLANG | https://github.com/nochhacks/DirFuzz | 0 | 0| 
| 20210201T22:21:20Z | final project for CS50 2020 | https://github.com/leztien/fuzzy_matching_project | 0 | 0| 
| 20210201T22:07:48Z | Lariat Rent-A-Car Presentation | https://github.com/WookieFan/fuzzy-lariat | 0 | 0| 
| 20210201T22:00:57Z | Null | https://github.com/puneet-07/Student-Performance-using-Fuzzy-Inference-System-FIS-MATLAB | 1 | 0| 
| 20210201T22:00:43Z | go-fuzz corpus data for Matt Layher%s projects. MIT Licensed. | https://github.com/mdlayher/fuzz-corpus | 2 | 1| 



# 日更新程序
