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
| 20210202T02:45:02Z | CVE-2021-3156 | Null | https://github.com/blasty/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210202T02:37:44Z | CVE-2021-3156 | PoC for CVE-2021-3156 (sudo heap overflow) | https://github.com/stong/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210202T02:33:03Z | CVE-2021-3156 | CVE-2021-3156 | https://github.com/reverse-ex/CVE-2021-3156 | | 
| 20210201T18:50:08Z | CVE-2021-3156 | Null | https://github.com/SantiagoSerrao/ScannerCVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T16:52:28Z | CVE-2021-3156 | 复现别人家的CVEs系列 | https://github.com/Q4n/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T16:51:34Z | CVE-2021-3156 | Null | https://github.com/kal1gh0st/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T15:19:14Z | CVE-2021-3345 | Null | https://github.com/MLGRadish/CVE-2021-3345 | _gcry_md_block_write in cipher/hash-common.c in Libgcrypt before 1.9.1 has a heap-based buffer overflow when the digest final function sets a large count value.| 
| 20210201T13:20:48Z | CVE-2020-7247 | This vulnerability exists in OpenBSD’s mail server OpenSMTPD’s “smtp_mailaddr()” function, and affects OpenBSD version 6.6. This allows an attacker to execute arbitrary shell commands like “sleep 66” as root user | https://github.com/jopraveen/CVE-2020-7247 | smtp_mailaddr in smtp_session.c in OpenSMTPD 6.6, as used in OpenBSD 6.6 and other products, allows remote attackers to execute arbitrary commands as root via a crafted SMTP session, as demonstrated by shell metacharacters in a MAIL FROM field. This affects the %uncommented% default configuration. The issue exists because of an incorrect return value upon failure of input validation.| 
| 20210201T11:24:51Z | CVE-2021-3156 | Patch Script for CVE-2021-3156 Heap Overflow | https://github.com/Ashish-dawani/CVE-2021-3156-Patch | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T08:16:06Z | CVE-2021-3156 | A docker environment to research CVE-2021-3156 | https://github.com/apogiatzis/docker-CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210202T02:42:02Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 1 | 0| 
| 20210202T02:15:00Z | Null | https://github.com/fontworks-fonts/Klee | 346 | 9| 
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
| 20210202T02:45:04Z | Null | https://github.com/0xturazzi/Um-Livrinho-Sobre-Exploit-Dev | 0 | 0| 
| 20210202T02:42:56Z | Shadow Strike is a exploitation framework that aids in information gathering, payload generation, payload delivery, and website exploitation. | https://github.com/diegomardian/ShadowStrike | 0 | 0| 
| 20210202T02:32:10Z | The best tool for finding one gadget RCE in libc.so.6 | https://github.com/david942j/one_gadget | 1276 | 109| 
| 20210202T02:15:08Z | This is my version of %Settlers of Catan%. The game is ostensibly complete with the exception of slow repainting when the robber is moved. Other than that, the game is functionally finished. The game plays best on a screen 1920x1080 as that enables status screens to be visible if 3-4 players are playing. A shortcut key has been implemented for cancellation of actions. Hold ALT_C when the Catan Board has focus, and this will enable an OptionPane to appear that allows for cancellation. And as for game additions I wanted to talk about, I have implemented a class system to the game that makes it more difficult (it is optional; choose the settler class if you want the standard game) as well as optional cataclysm events that can affect player resources at a 5% chance. As well, ports are optional as I%ve heard some people say they are too exploitable. Again, these three things are optional. And finally, all the image files used in this game are not my own. They are all sourced from Google Images (non-copyrighted, as far as I can tell). I will continue to work on the slow repaint issue in the future, but I will put this project down for a little while. (For whatever reason, I can%t put new lines in the description because of arbitrary code rules, so this jumbled mess of words is what I must put). | https://github.com/GitCaseyHub/SettlersOfCatan | 0 | 0| 
| 20210202T01:42:01Z | ASLR Evasion, Egghunters, SEH Overwrites | https://github.com/freddiebarrsmith/Advanced-Windows-Exploit-Development-Practice | 9 | 1| 
| 20210202T01:37:43Z | exploit-database-papers | https://github.com/offensive-security/exploitdb-papers | 277 | 39| 
| 20210202T01:32:27Z | A collection of tools used for exploiting Active Directory and Kerberos. | https://github.com/Pheelbert/ad_exploit_tools | 0 | 0| 
| 20210202T01:29:24Z | This if for Exploit docs | https://github.com/HunterAPI/ExploitDocs | 0 | 0| 
| 20210202T00:56:08Z | A bunch of scripts for minecraft exploitation (still under development). | https://github.com/ivfreire/mc_scripts | 0 | 0| 
| 20210202T00:49:56Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 7 | 4| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210202T00:50:11Z | Tool to find potential backdoor/security holes in your endpoint | https://github.com/subasgit/backdoorfinder | 1 | 0| 
| 20210202T00:33:30Z | Hacking tools pack & backdoors generator. | https://github.com/AdrMXR/KitHack | 333 | 57| 
| 20210201T22:41:34Z | Open-Source PowerShell module to allow online play of Backdoors & Breaches card game devised by Black Hills Information Security | https://github.com/TheShiShiLion/BackdoorsAndBreaches | 4 | 0| 
| 20210201T21:21:20Z | A defense model against BadNets (Backdoored Neural Networks) | https://github.com/priyanka-shishodia/Backdoored-DNN-defense | 0 | 0| 
| 20210201T20:24:17Z | Pytorch implementation of Backdoor Attack against Speaker Verification | https://github.com/zhaitongqing233/Backdoor-attack-against-speaker-verification | 2 | 1| 
| 20210201T18:07:04Z | A Remote Administration Tool (RAT) | https://github.com/0xmanjoos/Pieta | 4 | 1| 
| 20210201T11:39:28Z | just a simple and easy to understand python backdoor | https://github.com/Tab135/simple-python-backdoor | 0 | 0| 
| 20210201T10:57:45Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 161 | 23| 
| 20210201T10:53:05Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 34 | 8| 
| 20210201T10:02:20Z | Installs a persistent backdoor binary on android devices with unlocked bootloader via TWRP that runs as system daemon with root permissions and without SELinux restrictions | https://github.com/LuigiVampa92/unlocked-bootloader-backdoor-demo | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210202T02:39:59Z | HTTP Fuzzer backed with Machine Learning | https://github.com/karust/ml_http_fuzzer | 0 | 0| 
| 20210202T02:11:53Z | P2P platform for publishing content, self-hosting, decentralized curation, and more. | https://github.com/FuzzrNet/Fuzzr | 15 | 2| 
| 20210202T01:48:20Z | Fuzzy Logic SciKit (Toolkit for SciPy) | https://github.com/codediaz/fuzzy_logic | 1 | 0| 
| 20210202T01:06:41Z | Fuzz Tool and source code flags hunter. | https://github.com/viniciuspereiras/flagag | 0 | 0| 
| 20210202T00:53:57Z | Fuzzy matching publications for fatcat (wip). | https://github.com/miku/fuzzycat | 1 | 1| 
| 20210202T00:48:24Z | Null | https://github.com/james9348234/fuzzy-meme | 0 | 0| 
| 20210202T00:20:26Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 5833 | 1176| 
| 20210202T00:01:31Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2258 | 117| 
| 20210201T23:54:56Z | REST API Fuzz Testing (RAFT): Source code for self-hosted service developed for Azure, including the API, orchestration engine, and default set of security tools (including MSR%s RESTler), that enables developers to embed security tooling into their CI/CD workflows | https://github.com/microsoft/rest-api-fuzz-testing | 95 | 11| 
| 20210201T23:50:17Z | This bot is an community open source discord bot. | https://github.com/nimit2801/fuzzy-bones | 0 | 0| 



# 日更新程序
