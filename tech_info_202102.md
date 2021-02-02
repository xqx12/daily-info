# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210202 | Exploiting insecure WebSocket Communication | https://gupta-bless.medium.com/exploiting-insecure-websocket-communication-90554f5e43fe| 
| 20210202 | PortSwigger 发起的 2020 年的 Top 10 web hacking techniques 投票 | https://portswigger.net/polls/top-10-web-hacking-techniques-2020| 
| 20210202 | The Art Of Mac Malware: Analysis | https://taomm.org/vol1/analysis.html| 
| 20210202 | 如何自己编译 macOS 11.2 (Intel + Apple Silicon) 版本的 XNU 内核 | https://kernelshaman.blogspot.com/2021/02/building-xnu-for-macos-112-intel-apple.html| 
| 20210202 | BurpSuiteSharpener - BurpSuite 插件，用于提供多个易用性功能 | https://github.com/mdsecresearch/BurpSuiteSharpener| 
| 20210202 | Apple 发布 macOS Big Sur 11.2 版本，修复大量漏洞 | https://support.apple.com/en-us/HT212147| 
| 20210202 | 利用 Electron JS 浏览器自动化挖掘 XSS 漏洞 | https://github.com/RenwaX23/XSSTRON| 
| 20210202 | WebKit 将引入 Private Click Measurement 保护机制，用于防止广告对用户的大规模追踪 | https://webkit.org/blog/11529/introducing-private-click-measurement-pcm/| 
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
| 20210202 | 技术分享 , 锦行杯比赛 Writeup | https://mp.weixin.qq.com/s/mYCDsbERsgph5zu-4-lyKQ| 
| 20210202 | 代码审计 PHP基础（二） | https://www.sec-in.com/article/855| 
| 20210202 | 九阴真经：iOS黑客攻防秘籍 | /book/71| 
| 20210201 | 代码审计 PHP基础（一） | https://www.sec-in.com/article/848| 
| 20210201 | 浅谈溯源思维 | https://www.anquanke.com/post/id/229474| 
| 20210201 | 2020网络金融黑产研究报告 | https://mp.weixin.qq.com/s/B_pREKw4SJQjpbVbQLl33w| 
| 20210201 | 智能终端隐私防跟踪技术实践 | https://mp.weixin.qq.com/s/II5q4tYyZ3JUD4vHy1Fx6A| 
| 20210201 | 云安全架构连载之一-Azure整体架构及安全亮点详解 | https://mp.weixin.qq.com/s/QNBlsBJaWNXsZLEuNRQcvQ| 
| 20210201 | python编译后的pyd爆破 | https://mp.weixin.qq.com/s/JvQ38Isf1xXcGOe5wDgXWw| 
| 20210201 | 基于复杂图的 DDoS 攻击团伙发现与跟踪 | https://mp.weixin.qq.com/s/xz3XDHVg2jzMc6Sv-o8YTw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210202T13:36:42Z | CVE-2021-3156 | Null | https://github.com/blasty/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210202T13:02:37Z | CVE-2021-3156 | PoC for CVE-2021-3156 (sudo heap overflow) | https://github.com/stong/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210202T12:48:28Z | CVE-2021-3156 | Null | https://github.com/ltfafei/CVE-2021-3156 | | 
| 20210202T10:10:15Z | CVE-2021-3156 | 复现别人家的CVEs系列 | https://github.com/Q4n/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210202T03:14:16Z | CVE-2021-3156 | CVE-2021-3156 | https://github.com/reverse-ex/CVE-2021-3156 | | 
| 20210201T18:50:08Z | CVE-2021-3156 | Null | https://github.com/SantiagoSerrao/ScannerCVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T16:51:34Z | CVE-2021-3156 | Null | https://github.com/kal1gh0st/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210201T15:19:14Z | CVE-2021-3345 | Null | https://github.com/MLGRadish/CVE-2021-3345 | _gcry_md_block_write in cipher/hash-common.c in Libgcrypt before 1.9.1 has a heap-based buffer overflow when the digest final function sets a large count value.| 
| 20210201T13:20:48Z | CVE-2020-7247 | This vulnerability exists in OpenBSD’s mail server OpenSMTPD’s “smtp_mailaddr()” function, and affects OpenBSD version 6.6. This allows an attacker to execute arbitrary shell commands like “sleep 66” as root user | https://github.com/jopraveen/CVE-2020-7247 | smtp_mailaddr in smtp_session.c in OpenSMTPD 6.6, as used in OpenBSD 6.6 and other products, allows remote attackers to execute arbitrary commands as root via a crafted SMTP session, as demonstrated by shell metacharacters in a MAIL FROM field. This affects the %uncommented% default configuration. The issue exists because of an incorrect return value upon failure of input validation.| 
| 20210201T11:24:51Z | CVE-2021-3156 | Patch Script for CVE-2021-3156 Heap Overflow | https://github.com/Ashish-dawani/CVE-2021-3156-Patch | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210202T12:24:29Z | An open-source Chinese font derived from Fontworks% Klee One | https://github.com/lxgw/LxgwWenKai | 5 | 0| 
| 20210202T11:53:01Z | Null | https://github.com/alsoknownaszac/Kleekit-Webpage | 0 | 0| 
| 20210202T11:11:03Z | Null | https://github.com/fontworks-fonts/Klee | 348 | 9| 
| 20210202T04:27:41Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 1 | 0| 
| 20210201T11:59:33Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 212 | 34| 
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
| 20210202T13:23:55Z | smtp exploit script | https://github.com/M4chin3M4N/SMTPython | 0 | 0| 
| 20210202T13:22:28Z | PatrowlHears - Vulnerability Intelligence Center / Exploits | https://github.com/Patrowl/PatrowlHears | 25 | 8| 
| 20210202T13:15:00Z | Null | https://github.com/EmperorParzival/ExploitScripts | 0 | 0| 
| 20210202T13:14:58Z | Pentest important small exploitation scripts  | https://github.com/cyberjatin/mynotes | 0 | 0| 
| 20210202T13:02:33Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 5 | 3| 
| 20210202T12:49:57Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 7 | 4| 
| 20210202T12:42:53Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 8962 | 1440| 
| 20210202T12:05:37Z | CTF framework and exploit development library | https://github.com/Gallopsled/pwntools | 7493 | 1347| 
| 20210202T11:50:13Z | The detection of irony and sarcasm is one of the most insidious challenges in the field of Natural Language Processing. Over the years, several techniques have been studied to analyze these rhetorical figures, trying to identify the elements that discriminate, in a significant way, what is sarcastic or ironic from what is not. Within this study, some models that are state of the art are analyzed. As far as Machine Learning is concerned, the most discriminating features such as part of speech, pragmatic particles and sentiment are studied. Subsequently, these models are optimized, comparing Bayesian optimization techniques and random search. Once, the best hyperparameters are identified, ensemble methods such as Bayesian Model Averaging (BMA) are exploited. In relation to Deep Learning, two main models are analyzed: DeepMoji, developed by MIT, and a model called Transformer Based, which exploits the generalization power of Roberta Transformer. As soon as these models are compared, the main goal is to identify a new system able to better capture the two rhetorical figures. To this end, two models composed of attention mechanisms are proposed, exploiting the principle of Transfer Learning, using Bert Tweet Model and DeepMoji Model as feature extractors. After identifying the various architectures, an ensemble method is applied on the set of approaches proposed, in order to identify the best combination of algorithms that can achieve satisfactory results. Frameworks used: Pytorch, TF 2.0, Scikit Learn, Scikit-Optimize, Transformers | https://github.com/lorenzofamiglini/Irony-Sarcasm-Detection-Task | 0 | 0| 
| 20210202T11:39:03Z | The detection of irony and sarcasm is one of the most insidious challenges in the field of Natural Language Processing. Over the years, several techniques have been studied to analyze these rhetorical figures, trying to identify the elements that discriminate, in a significant way, what is sarcastic or ironic from what is not. Within this study, some models that are state of the art are analyzed. As far as Machine Learning is concerned, the most discriminating features such as part of speech, pragmatic particles and sentiment are studied. Subsequently, these models are optimized, comparing Bayesian optimization techniques and random search. Once, the best hyperparameters are identified, ensemble methods such as Bayesian Model Averaging (BMA) are exploited. In relation to Deep Learning, two main models are analyzed: DeepMoji, developed by MIT, and a model called Transformer Based, which exploits the generalization power of Roberta Transformer. As soon as these models are compared, the main goal is to identify a new system able to better capture the two rhetorical figures. To this end, two models composed of attention mechanisms are proposed, exploiting the principle of Transfer Learning, using Bert Tweet Model and DeepMoji Model as feature extractors. After identifying the various architectures, an ensemble method is applied on the set of approaches proposed, in order to identify the best combination of algorithms that can achieve satisfactory results.  | https://github.com/lorenzofamiglini/Irony-Sarcasm-Detection | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210202T13:06:30Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 162 | 23| 
| 20210202T13:05:44Z | Pytorch implementation of Backdoor Attack against Speaker Verification | https://github.com/zhaitongqing233/Backdoor-attack-against-speaker-verification | 3 | 2| 
| 20210202T13:02:40Z | Hacking tools pack & backdoors generator. | https://github.com/AdrMXR/KitHack | 334 | 57| 
| 20210202T12:37:29Z | Null | https://github.com/mikkelskov1/backdoor2 | 0 | 0| 
| 20210202T12:34:06Z | Null | https://github.com/rabbitx1337/backdoor | 0 | 0| 
| 20210202T11:39:02Z | Remote Access Trojan (RAT) backdoor generator and server project. *Educational purposes only | https://github.com/fordlarman/J0n3sy_Cat | 0 | 0| 
| 20210202T09:43:29Z | Python3 backdoor for Wndows and Linux | https://github.com/aryansofficial/Python3-Backdoor | 0 | 0| 
| 20210202T09:28:13Z | Null | https://github.com/EjHvorSerDuVildUdJim/backdoor | 0 | 0| 
| 20210202T04:43:59Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 34 | 8| 
| 20210202T03:37:26Z | A static analysis tool to detect potential backdoors hidden in Ethereum smart contracts. | https://github.com/renardbebe/backdoorDetector | 1 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210202T13:27:54Z | Ethereum smart contract fuzzer | https://github.com/crytic/echidna | 540 | 92| 
| 20210202T13:24:03Z | Null | https://github.com/fuzzsa/fuzzsa-bugs | 0 | 0| 
| 20210202T12:00:33Z | Null | https://github.com/Juanosorio94/fuzzing-rdma | 0 | 0| 
| 20210202T11:50:21Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 4 | 1| 
| 20210202T11:29:53Z | Fuzzy matching publications for fatcat (wip). | https://github.com/miku/fuzzycat | 1 | 1| 
| 20210202T11:06:57Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3329 | 769| 
| 20210202T10:48:25Z | Null | https://github.com/s9varesc/url-fuzzing | 0 | 0| 
| 20210202T10:46:06Z | Null | https://github.com/Sentinel-One/efi_fuzz | 60 | 7| 
| 20210202T10:23:38Z | Null | https://github.com/feixiangdejiahao/Fuzzing-Testing-of-JVM-Implementations | 0 | 0| 
| 20210202T10:23:29Z | Simple fuzzer for OpenAPI 3 specification based APIs | https://github.com/vwt-digital/openapi3-fuzzer | 5 | 2| 



# 日更新程序
