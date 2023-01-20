# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230119 | viettel安全的名为vudq4的安全研究员发布关于CVE-2022-21587 (Oracle E-Business Suite 未授权RCE)的细节.其主要通过oracle.apps.bne.framework.BneMultipartRequest中的doUploadFile函数,其处理文件名带有uue的文件时候会调用doUnZip,而该函数容易遭到ZipSlip的攻击造成文件上传.同时也介绍了如何编写可以在其工作的webshell,但是由于oracle.apps.fnd.security.WLFilter的限制.所以只能去考虑如何覆盖pl来进行执行,由于所有经过pl的都会经过weblogic.servlet.CGIServlet在调试的可以发现一个不重要的文件txkFNDWRR.pl(作用只有生成log),通过覆盖来实现webshell,完成RCE | https://blog.viettelcybersecurity.com/cve-2022-21587-oracle-e-business-suite-unauth-rce/| 
| 20230119 | Firefox 在野0day漏洞分析,CVE-2022-26485(RCE)+CVE-2022-26486(SBX) | https://weiyiling.cn/one/firefox_0day_case_analysis| 
| 20230119 | 如何利用本地提权漏洞（CVE-2021-3490）实现在5.15 之前的 Linux 内核版本进行容器逃逸。 | https://www.crowdstrike.com/blog/exploiting-cve-2021-3490-for-container-escapes/| 
| 20230119 | pksecurity发布其在pwn2own 2022使用的microsoft teams rce | http://blog.pksecurity.io/2023/01/16/2022-microsoft-teams-rce.html| 
| 20230119 | Linux 6.3 将在 AMD 锐龙 CPU 上支持 Pluton 的命令响应缓冲区 CRB 以及受信任平台模块 TPM2 | https://www.phoronix.com/news/Linux-6.3-CRB-TPM2-Pluton| 
| 20230119 | APT15使用Turian以及其变体针对Iran的活动分析 | https://unit42.paloaltonetworks.com/playful-taurus/| 
| 20230119 | Java中的xml安全性 | https://semgrep.dev/blog/2022/xml-security-in-java| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230119 | 顶会论文写作建议（上）：宏观布局，避免“hard to follow” | https://mp.weixin.qq.com/s/kberQa8ss7l2gh9PAx_cSQ| 
| 20230119 | 从CISA KEV看海量漏洞管理方法 | https://mp.weixin.qq.com/s/X5J4gYanCGrGMJ9Yp6J8tQ| 
| 20230119 | 基于代码属性图的自动化漏洞挖掘实践 | https://blog.0kami.cn/blog/2023/%E5%9F%BA%E4%BA%8E%E4%BB%A3%E7%A0%81%E5%B1%9E%E6%80%A7%E5%9B%BE%E7%9A%84%E8%87%AA%E5%8A%A8%E5%8C%96%E6%BC%8F%E6%B4%9E%E6%8C%96%E6%8E%98%E5%AE%9E%E8%B7%B5/| 
| 20230119 | mqtt攻击面和挖掘思路浅析 | https://vul.360.net/archives/649| 
| 20230119 | 一种 Foxit Reader 漏洞利用思路探索 | https://vul.360.net/archives/648| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230119T22:03:20Z | CVE-2022-0863 | The WP SVG Icons WordPress plugin through 3.2.3 does not properly validate uploaded custom icon packs, allowing an high privileged user like an admin to upload a zip file containing malicious php code, leading to remote code execution. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-0863 | | 
| 20230119T22:02:26Z | CVE-2023-20522 | Insufficient input validation in ASP may allow an attacker with a malicious BIOS to potentially cause a denial of service. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-20522 | | 
| 20230119T21:51:23Z | cve-2022-0847 | Resources required for building Pluralsight CVE-2022-0847 lab | https://github.com/Turzum/ps-lab-cve-2022-0847 | | 
| 20230119T19:52:14Z | CVE-2022-40697 | Auth. (admin+) Stored Cross-Site Scripting (XSS) vulnerability in 3com – Asesor de Cookies para normativa española plugin <= 3.4.3 versions. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-40697 | | 
| 20230119T19:52:10Z | CVE-2022-39167 | IBM Spectrum Virtualize 8.5, 8.4, 8.3, 8.2, and 7.8, under certain configurations, could disclose sensitive information to an attacker using man-in-the-middle techniques. IBM X-Force ID: 235408. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-39167 | | 
| 20230119T19:52:06Z | CVE-2022-1676 | ** REJECT ** DO NOT USE THIS CANDIDATE NUMBER. ConsultIDs: none. Reason: This candidate was withdrawn by its CNA. Further investigation showed that it was not a security issue. Notes: none. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-1676 | | 
| 20230119T19:52:02Z | CVE-2020-1713 | ** REJECT ** DO NOT USE THIS CANDIDATE NUMBER. ConsultIDs: none. Reason: The CNA or individual who requested this candidate did not associate it with any vulnerability during 2020. Notes: none. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-1713 | | 
| 20230119T19:51:58Z | CVE-2022-4874 | Authentication bypass in Netcomm router models NF20MESH, NF20, and NL1902 allows an unauthenticated user to access content. In order to serve static content, the application performs a check for the existence of specific characters in the URL (.css, .png etc). If it exists, it performs a "fake login" to give the reques CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4874 | | 
| 20230119T19:51:55Z | CVE-2022-4873 | On Netcomm router models NF20MESH, NF20, and NL1902 a stack based buffer overflow affects the sessionKey parameter. By providing a specific number of bytes, the instruction pointer is able to be overwritten on the stack and crashes the application at a known location. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4873 | | 
| 20230119T19:51:51Z | CVE-2022-4415 | A vulnerability was found in systemd. This security flaw can cause a local information leak due to systemd-coredump not respecting the fs.suid_dumpable kernel setting. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4415 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T20:25:43Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10117 | 341| 
| 20230119T20:00:59Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 197 | 1| 
| 20230119T16:37:09Z | Site single page responsivo desenvolvido apenas para prática. | https://github.com/Everton-Luciano/kleep-project | 0 | 0| 
| 20230119T14:50:36Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 269 | 50| 
| 20230119T12:18:24Z | Preprocessor for symbolic execution, extracted from KLEE | https://github.com/Generative-Program-Analysis/fs-linker | 2 | 0| 
| 20230119T10:15:34Z | A Max implementation of a shift register sequencer like the MTM Turing Machine or the Klee Sequencer | https://github.com/jakebeamish/max-shift-register-sequencer | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T23:33:51Z | A FiveM Cheat undetected (for now) feel free to add features, has esp aimbot and no recoil | https://github.com/BaraX0/FiveM-Cheat-ESP-Aim-and-Admin-exploit-mods | 4 | 0| 
| 20230119T23:03:22Z | Null | https://github.com/kdRajKit/EXPLOIT-DEVELOPMENT | 0 | 0| 
| 20230119T22:42:00Z | Null | https://github.com/lunalandtest/eXploitBecauseICan | 0 | 1| 
| 20230119T21:14:23Z | Null | https://github.com/R3tr074/exploits | 4 | 0| 
| 20230119T13:58:19Z | This repository is primarily maintained by Omar Santos (@santosomar) and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 12611 | 2163| 
| 20230119T13:55:03Z | 🔥 , Cheat with a simple GUI made for Rust , UNDETECTED , AIMBOT , ESP , FLY , NO RECOIL , INFINITE AMMO , MORE | https://github.com/Suldue/Rust-Cheat | 0 | 0| 
| 20230119T13:51:42Z | 🖥️ / HWID Spoofer for games like: Warzone 2, Rust, Valorant, R6, GTA5, Fortnite, Fivem, Overwatch etc | https://github.com/Suldue/HWID-Spoofer | 0 | 0| 
| 20230119T13:47:39Z | 💥 , FORTNITE Softaim that gives you insane aim and reduces your bloom , UNDETECTED | https://github.com/Suldue/Fortnite-Softaim | 0 | 0| 
| 20230119T13:44:08Z | 💉,  Fivem Executor , UNDETECTED , DUMPER | https://github.com/Suldue/Fivem-Executor | 0 | 0| 
| 20230119T13:41:32Z | A tool to identify and exploit sudo rules% misconfigurations and vulnerabilities within sudo for linux privilege escalation. | https://github.com/TH3xACE/SUDO_KILLER | 1719 | 218| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T21:18:12Z | Null | https://github.com/wcenatus/backdoor-nextjs | 0 | 0| 
| 20230119T19:20:25Z | Null | https://github.com/TheOrangeDev/IcedOutBackdoor | 0 | 0| 
| 20230119T19:04:03Z | Null | https://github.com/jinghuichen/Focused-Flip-Federated-Backdoor-Attack | 0 | 0| 
| 20230119T17:29:09Z | NO BACKDOOR eth drainer + approve all for all nft drainer | https://github.com/C4lme/approveall-for-all-drainer | 56 | 26| 
| 20230119T15:25:23Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) C2 and post-exploitation framework written in python and C | https://github.com/n1nj4sec/pupy | 7432 | 1770| 
| 20230119T15:21:25Z | Evil-Droid is a framework that creates & generates & embed apk payload to penetrate Android platforms. | https://github.com/HackWithSumit/Android-Backdoor-EvilDroid | 0 | 0| 
| 20230119T13:47:33Z | Automatic and dynamic Gmod lua backdoor | https://github.com/DoctorWhoFR/GBackDoor_API | 0 | 0| 
| 20230119T12:47:43Z | This tool is used for backdoor and shellcode generation for various architecture devices | https://github.com/doudoudedi/hackEmbedded | 27 | 2| 
| 20230119T09:54:16Z | Anywhere is a powerful botnet that allows for the remote control of compromised devices | https://github.com/thisisnzed/Anywhere | 3 | 0| 
| 20230119T09:48:21Z | A Basic 100% Python RAT | https://github.com/sirmilann/TempoRat | 2 | 1| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T13:02:43Z | Bachelor thesis, attempting decompilation using symbolic execution | https://github.com/lokegustafsson/thesis-decompilation | 2 | 0| 
| 20230119T12:18:24Z | Preprocessor for symbolic execution, extracted from KLEE | https://github.com/Generative-Program-Analysis/fs-linker | 2 | 0| 
| 20230119T12:16:58Z | Open-source symbolic execution framework: https://maat.re | https://github.com/trailofbits/maat | 540 | 31| 
| 20230119T04:53:21Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3277 | 466| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T20:04:55Z | find relevant security papers published in the top-4 conferences (S&P, USENIX, CCS, NDSS) | https://github.com/Kyle-Kyle/top4grep | 28 | 2| 
| 20230119T16:29:30Z | Null | https://github.com/tokunagak/NDSS | 0 | 0| 
| 20230119T14:19:34Z | Code for the NDSS%23 paper %DARWIN: Survival of the Fittest Fuzzing Mutators% | https://github.com/TUDA-SSL/DARWIN | 1 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T22:42:18Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 3345 | 671| 
| 20230119T21:50:01Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8280 | 1808| 
| 20230119T21:16:19Z | Null | https://github.com/zazaerr/fuzzy-system | 0 | 0| 
| 20230119T20:12:34Z | Null | https://github.com/OpenAutoIt/Fuzzing-Corpus | 2 | 0| 
| 20230119T13:24:53Z | a web directory fuzzer with Go | https://github.com/CybersecSpirit/gofuzz | 0 | 0| 
| 20230119T12:37:17Z | A backend framework for javascript | https://github.com/MohamedDerbali/FuzzyWuzzyJS | 0 | 0| 
| 20230119T11:34:21Z | Movimento Robo com Multi-Layer Perceptron, Fuzzy e Prolog | https://github.com/LeonardoJunio/robo-ia-mlp-fuzzy-prolog | 0 | 0| 
| 20230119T11:26:27Z | SPK dengan metode Fuzzy AHP | https://github.com/riyanandri/fuzzy_ahp | 0 | 0| 
| 20230119T11:22:15Z | Null | https://github.com/jhibongh/fuzzy-journey | 0 | 0| 
| 20230119T10:36:10Z | Null | https://github.com/chill-panda/fuzzy-rotary-phone.github.io | 0 | 0| 



# 日更新程序
