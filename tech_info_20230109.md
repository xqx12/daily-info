# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230109 | Code4rena上top1 reseacher的演讲，介绍他如何在合约众测平台Code4rena成为第一人。 | https://www.youtube.com/watch?v=VRK2rLFPU0o| 
| 20230109 | 一个在macOS 11安装并使用GDB的教程。不支持M1 Mac。 | https://gist.github.com/mike-myers-tob/9a6013124bad7ff074d3297db2c98247| 
| 20230109 | 清华大学发布的130B规模的大模型，并声称其性能在davinci 和 text-davinci-001之间。 | https://huggingface.co/spaces/THUDM/GLM-130B| 
| 20230109 | 软件供应链安全的ATTCK | http://riskexplorer.endorlabs.com/| 
| 20230109 | 一个生成伪装成图片的钓鱼马的工具 | https://github.com/Tsuyoken/ImgBackdoor| 
| 20230109 | rwctf2023-ASTLIBRA的预期解 | https://github.com/wupco/rwctf2023-ASTLIBRA| 
| 20230109 | 警惕：魔改后的CIA攻击套件Hive进入黑灰产领域 | https://blog.netlab.360.com/warning-hive-variant-xdr33-is-coming_cn/| 
| 20230109 | Squirrel.Windows存在DLL劫持漏洞。 | https://archcloudlabs.com/projects/cve-2022-46330/| 
| 20230109 | 介绍 Foxit Reader 自己实现的内存管理细节 | http://paper.seebug.org/2039/| 
| 20230109 | 从原理、性能等角度对zkSNARKs、zkSTARKs这两种零知识证明的实现进行对比 | http://pseudotheos.mirror.xyz/_LAi4cCFz2gaC-3WgNmri1eTvckA32L7v31A8saJvqg| 
| 20230109 | TikTok的VMP保护分析 | https://www.reddit.com/r/ReverseEngineering/comments/107fqih/reverse_engineering_tiktoks_vm_obfuscation_part_2/| 
| 20230109 | VSCode扩展可以被用作攻击向量RCE开发者的电脑。 | https://thehackernews.com/2023/01/hackers-distributing-malicious-visual.html| 
| 20230109 | VMware Workstation Heap OOB 漏洞POC。 | https://github.com/s0duku/cve-2022-31705| 
| 20230109 | Linux Kernel UAF漏洞细节，该漏洞是由于加锁逻辑实现问题，导致可以通过条件竞争造成UAF漏洞。 | https://bugs.chromium.org/p/project-zero/issues/detail?id=2391| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230109 | AspectJWeaver利用链绕过serialKiller | https://sec-in.com/article/1993| 
| 20230109 | 测量俄罗斯对 Twitter 的大规模拦截 | https://mp.weixin.qq.com/s/omxYGYC1j4AAPs5W9Nh_ow| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230109T23:54:34Z | CVE-2023-0125 | A vulnerability was found in Control iD Panel. It has been declared as problematic. Affected by this vulnerability is an unknown functionality of the component Web Interface. The manipulation of the argument Nome leads to cross site scripting. The attack can be launched remotely. The exploit has been disclosed to the p CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0125 | | 
| 20230109T23:54:31Z | CVE-2022-43973 | An arbitrary code execution vulnerability exisits in Linksys WRT54GL Wireless-G Broadband Router with firmware <= 4.30.18.006. The Check_TSSI function within the httpd binary uses unvalidated user input in the construction of a system command. An authenticated attacker with administrator privileges can leverage this vu CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-43973 | | 
| 20230109T23:54:26Z | CVE-2022-43972 | A null pointer dereference vulnerability exists in Linksys WRT54GL Wireless-G Broadband Router with firmware <= 4.30.18.006. A null pointer dereference in the soap_action function within the upnp binary can be triggered by an unauthenticated attacker via a malicious POST request invoking the AddPortMapping action. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-43972 | | 
| 20230109T23:54:22Z | CVE-2022-43971 | An arbitrary code exection vulnerability exists in Linksys WUMC710 Wireless-AC Universal Media Connector with firmware <= 1.0.02 (build3). The do_setNTP function within the httpd binary uses unvalidated user input in the construction of a system command. An authenticated attacker with administrator privileges can lever CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-43971 | | 
| 20230109T23:54:18Z | CVE-2022-43970 | A buffer overflow vulnerability exists in Linksys WRT54GL Wireless-G Broadband Router with firmware <= 4.30.18.006. A stack-based buffer overflow in the Start_EPI function within the httpd binary allows an authenticated attacker with administrator privileges to execute arbitrary commands on the underlying Linux operati CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-43970 | | 
| 20230109T23:54:12Z | CVE-2021-36603 | Cross Site Scripting (XSS) in Tasmota firmware 6.5.0 allows remote attackers to inject JavaScript code via a crafted string in the field "Friendly Name 1". CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-36603 | | 
| 20230109T21:55:48Z | CVE-2020-13259 | PoC of Full Account Takeover on RAD SecFlow-1v  | https://github.com/UrielYochpaz/CVE-2020-13259 | | 
| 20230109T21:43:46Z | CVE-2022-4369 | The WP-Lister Lite for Amazon WordPress plugin before 2.4.4 does not sanitize and escapes a parameter before outputting it back in the page, leading to a Reflected Cross-Site Scripting which can be used against high-privilege users such as admin. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4369 | | 
| 20230109T21:43:42Z | CVE-2022-4351 | The Qe SEO Handyman WordPress plugin through 1.0 does not properly sanitize and escape a parameter before using it in a SQL statement, leading to a SQL injection exploitable by high privilege users such as admin CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4351 | | 
| 20230109T21:43:36Z | CVE-2022-4362 | The Popup Maker WordPress plugin before 1.16.9 does not validate and escape one of its shortcode attributes, which could allow users with a role as low as contributor to perform Stored Cross-Site Scripting attacks CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4362 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230109T20:03:46Z | Null | https://github.com/kleecollage/kleecollage | 0 | 0| 
| 20230109T19:39:07Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 9842 | 339| 
| 20230109T17:43:39Z | Collection of Kicad 6.0 symbols, footprints and 3D models useful in keyboard creation | https://github.com/crides/kleeb | 66 | 5| 
| 20230109T10:07:05Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 176 | 1| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230109T23:54:34Z | A vulnerability was found in Control iD Panel. It has been declared as problematic. Affected by this vulnerability is an unknown functionality of the component Web Interface. The manipulation of the argument Nome leads to cross site scripting. The attack can be launched remotely. The exploit has been disclosed to the p CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0125 | 0 | 0| 
| 20230109T23:40:04Z | Ronin is a free and Open Source Ruby toolkit for security research and development. Ronin also allows for the rapid development and distribution of code, exploits, payloads, etc, via 3rd party git repositories. | https://github.com/ronin-rb/ronin | 323 | 28| 
| 20230109T22:31:32Z | Block users that visit typical exploit urls or that use bad bots. | https://github.com/accentinteractive/laravel-blocker | 0 | 0| 
| 20230109T22:08:06Z | Popcorn Time 6.2 - %Update service% Unquoted Service Path | https://github.com/UrielYochpaz/Exploit-Popcorn-Time-6.2 | 0 | 0| 
| 20230109T22:05:31Z | WordPress Plugin DZS Zoomsounds 6.45 - Arbitrary File Read (Unauthenticated) | https://github.com/UrielYochpaz/Exploit-WordPress-Plugin-DZS-Zoomsounds | 0 | 0| 
| 20230109T21:43:42Z | The Qe SEO Handyman WordPress plugin through 1.0 does not properly sanitize and escape a parameter before using it in a SQL statement, leading to a SQL injection exploitable by high privilege users such as admin CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4351 | 0 | 0| 
| 20230109T21:43:22Z | The Qe SEO Handyman WordPress plugin through 1.0 does not properly sanitize and escape a parameter before using it in a SQL statement, leading to a SQL injection exploitable by high privilege users such as admin CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4352 | 0 | 0| 
| 20230109T20:57:32Z | Collection of useful PowerShell tools and exploits. | https://github.com/TuxStux/PowerShell | 0 | 0| 
| 20230109T19:10:41Z | EDuty/CyberVAL is a fully featured internal hack for Valorant written with C++. | https://github.com/Mt7zz/Valorant-Internal-Cheats-Aimbot-ESP | 2 | 0| 
| 20230109T18:50:22Z | 🌲Rust Easy to use Public Cheat  , Aimbot + Esp | https://github.com/Mt7zz/Rust-ESP-AIMBOT | 1 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230109T21:25:03Z | Null | https://github.com/Killian202/backdoorpython | 0 | 0| 
| 20230109T21:20:54Z | Null | https://github.com/Killian202/backdoor | 0 | 0| 
| 20230109T19:38:40Z | Resilient, Stealthy & Capable Windows Backdoor. Utilizing Telegram for command relays | https://github.com/whiterabb17/Shamanic | 1 | 0| 
| 20230109T19:23:28Z | all shell backdoor in the world | https://github.com/beruangsalju/shell-backdoor | 1 | 1| 
| 20230109T18:38:44Z | All OS commands | https://github.com/Maksaks/Backdoor | 0 | 0| 
| 20230109T18:27:54Z | Free Minecraft 1.8.9 Skript Backdoor (i just make it for fun) | https://github.com/LegendaryMichoX/Infinity | 1 | 0| 
| 20230109T15:10:41Z | User space level rootkit, which hooks successfully several glibc functions. Currently developing: hiding connection from %ss%, IPv6 support, improving backdoor trigger and SSL support. | https://github.com/armandomfdz/GrinchRootkit | 0 | 0| 
| 20230109T12:03:09Z | NO BACKDOOR eth drainer + approve all for all nft drainer | https://github.com/C4lme/approveall-for-all-drainer | 53 | 26| 
| 20230109T11:59:45Z | Uniswap & Seaport, Opensea NFT Drainer, ERC-20, ETH All in one No backdoor | https://github.com/C4lme/nft-stealer-drainer | 42 | 0| 
| 20230109T11:57:37Z | No backdoor ETH & ERC-20 & NFT stealer drains ETH + NFT Seaport, Uniswap Drainer | https://github.com/C4lme/token-nft-stealer | 31 | 21| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230109T11:21:55Z | Fork of SymEx-VP for specification-based symbolic execution of stateful network protocol implementations via SPS protocol specifications | https://github.com/agra-uni-bremen/sps-vp | 0 | 0| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230109T23:26:31Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8244 | 1797| 
| 20230109T23:00:24Z | Witcher is the first framework for using AFL to fuzz web applications. | https://github.com/sefcom/Witcher | 1 | 0| 
| 20230109T22:23:35Z | Evolutionary Coverage-guided Fuzzing engine | https://github.com/matt24smith/ecfuzz | 0 | 0| 
| 20230109T22:03:52Z | Null | https://github.com/Vladyslaviuss/homework_22__FuzzGenerator__V.Marakhovskyi | 0 | 0| 
| 20230109T17:58:53Z | Official repository  vuls Scan: 15000+PoCs; 23 kinds of application password crack; 7000+Web fingerprints; 146 protocols and 90000+ rules Port scanning; Fuzz, HW, awesome BugBounty( ͡° ͜ʖ ͡°)... | https://github.com/hktalent/scan4all | 3354 | 398| 
| 20230109T15:49:03Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2637 | 180| 
| 20230109T14:07:30Z | Null | https://github.com/sclauguico/adaptive-neuro-fuzzy-inference-system-on-aquaphotomics-development-for-aquaponic-water-nutrient | 0 | 0| 
| 20230109T13:46:53Z | Simple Echidna Fuzz Template | https://github.com/xternet/echidna-template | 0 | 0| 
| 20230109T13:45:16Z | Null | https://github.com/quinderbi/tuproFuzzification | 0 | 0| 
| 20230109T13:44:53Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 4508 | 1091| 



# 日更新程序
