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
| 20230118 | CVE-2023-0321 Campbell Scientific 产品中信息泄露 | https://www.hackplayers.com/2023/01/cve-2023-0321-info-sensible-campbell.html| 
| 20230118 | 360发布的2022年全球高级持续性威胁（APT）研究报告 | https://github.com/blackorbird/APT_REPORT/blob/master/summary/2023/360_APT_Annual_Research_Report_2022.pdf| 
| 20230118 | X41 team对Git项目的审计报告，其中包括了两个高危漏洞的越界写漏洞细节（CVE-2022-23521、CVE-2022-41903） | http://www.x41-dsec.de/security/research/news/2023/01/17/git-security-audit-ostif/| 
| 20230118 | 使用aflfuzz fuzz php | https://www.tripwire.com/state-of-security/fuzzing-php-for-fun-and-profit| 
| 20230117 | 疑似Kasablanka组织近期针对俄罗斯的攻击活动分析 | https://mp.weixin.qq.com/s/b0FSKQ6D3MvlA8yX3v4IUg| 
| 20230117 | JDK-Xalan的XSLT整数截断漏洞利用构造 | https://mp.weixin.qq.com/s/xxAtjFvk9RxWiY-pwGf8Ow| 
| 20230117 | 记录一下从编译的角度还原VMP的思路 | https://bbs.kanxue.com/thread-275796.htm| 
| 20230117 | 一个高度可定制化的JNDI和Java反序列化利用工具 | https://mp.weixin.qq.com/s/-OE1MlqaCUl7gmSPVNBr7g| 
| 20230117 | 2022 Q4 季度俄乌双方 DDoS 攻击分析报告 | https://ti.qianxin.com/blog/articles/2022-Q4-DDoS-Activities-between-Russia-and-Ukriane-camps/| 
| 20230117 | Windows 上的 clash_for_windows 在 0.20.12 在订阅一个恶意链接时存在远程命令执行漏洞。因为对订阅文件中 rule-providers 的 path 的不安全处理导致 cfw-setting.yaml 会被覆盖，cfw-setting.yaml 中 parsers 的 js代码将会被执行 | https://github.com/Fndroid/clash_for_windows_pkg/issues/3891| 
| 20230117 | HTB: Shoppy Writeup | https://0xdf.gitlab.io/2023/01/14/htb-shoppy.html| 
| 20230117 | cve-2022-21881用于chrome SBX利用链的windows提权poc,曾经用于天府杯的chrome sbx部分 | https://github.com/dbgsymbol/windows_lpe_pocs/blob/main/cve-2022-21881-io_completion-poc.cpp| 
| 20230117 | idek 2022* CTF task manager预期解rce部分的writeup | https://github.com/Myldero/ctf-writeups/tree/master/idekCTF%202022/task%20manager| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230119 | 顶会论文写作建议（上）：宏观布局，避免“hard to follow” | https://mp.weixin.qq.com/s/kberQa8ss7l2gh9PAx_cSQ| 
| 20230119 | 从CISA KEV看海量漏洞管理方法 | https://mp.weixin.qq.com/s/X5J4gYanCGrGMJ9Yp6J8tQ| 
| 20230119 | 基于代码属性图的自动化漏洞挖掘实践 | https://blog.0kami.cn/blog/2023/%E5%9F%BA%E4%BA%8E%E4%BB%A3%E7%A0%81%E5%B1%9E%E6%80%A7%E5%9B%BE%E7%9A%84%E8%87%AA%E5%8A%A8%E5%8C%96%E6%BC%8F%E6%B4%9E%E6%8C%96%E6%8E%98%E5%AE%9E%E8%B7%B5/| 
| 20230119 | mqtt攻击面和挖掘思路浅析 | https://vul.360.net/archives/649| 
| 20230119 | 一种 Foxit Reader 漏洞利用思路探索 | https://vul.360.net/archives/648| 
| 20230118 | 开源软件安全性分析 | https://mp.weixin.qq.com/s/dDHmQkWhSchnD7kTBtKymw| 
| 20230118 | 利用空间测绘进行威胁分析 | https://mp.weixin.qq.com/s/b-rynWs2xX3ft48QFx8NBg| 
| 20230118 | 2022年全球高级持续性威胁（APT）研究报告 | https://cdn.isc.360.com/iscvideo-bucket/360_APT_Annual_Research_Report_2022.pdf| 
| 20230117 | 玩转CodeQLpy之用友GRP-U8漏洞挖掘 | https://mp.weixin.qq.com/s/hYPdNN6skbikC3FFYRlbrQ| 
| 20230117 | 关于大模型时代软件智能化开发的一点展望 | https://mp.weixin.qq.com/s/UTcnFq53JjIMsShmKtQvDw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230120T01:20:24Z | CVE-2023-22745 | tpm2-tss is an open source software implementation of the Trusted Computing Group (TCG) Trusted Platform Module (TPM) 2 Software Stack (TSS2). In affected versions `Tss2_RC_SetHandler` and `Tss2_RC_Decode` both index into `layer_handler` with an 8 bit layer number, but the array only has `TPM2_ERROR_TSS2_RC_LAYER_COUNT CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-22745 | | 
| 20230120T01:20:20Z | CVE-2022-46476 | D-Link DIR-859 A1 1.05 was discovered to contain a command injection vulnerability via the service= variable in the soapcgi_main function. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46476 | | 
| 20230120T01:20:17Z | CVE-2022-31901 | Buffer overflow in function Notepad_plus::addHotSpot in Notepad++ v8.4.3 and earlier allows attackers to crash the application via two crafted files. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-31901 | | 
| 20230120T00:14:51Z | CVE-2023-0126 | Pre-authentication path traversal vulnerability in SMA1000 firmware version 12.4.2, which allows an unauthenticated attacker to access arbitrary files and directories stored outside the web root directory. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0126 | | 
| 20230120T00:14:48Z | CVE-2022-47766 | PopojiCMS v2.0.1 backend plugin function has a file upload vulnerability. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-47766 | | 
| 20230120T00:14:44Z | CVE-2022-46890 | Weak access control in NexusPHP before 1.7.33 allows a remote authenticated user to edit any post in the forum (this is caused by a lack of checks performed by the /forums.php?action=post page). CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46890 | | 
| 20230120T00:14:40Z | CVE-2022-46889 | A persistent cross-site scripting (XSS) vulnerability in NexusPHP before 1.7.33 allows remote authenticated attackers to permanently inject arbitrary web script or HTML via the title parameter used in /subtitles.php. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46889 | | 
| 20230120T00:14:36Z | CVE-2022-46888 | Multiple reflective cross-site scripting (XSS) vulnerabilities in NexusPHP before 1.7.33 allow remote attackers to inject arbitrary web script or HTML via the secret parameter in /login.php; q parameter in /user-ban-log.php; query parameter in /log.php; text parameter in /moresmiles.php; q parameter in myhr.php; or id  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46888 | | 
| 20230120T00:14:32Z | CVE-2022-46887 | Multiple SQL injection vulnerabilities in NexusPHP before 1.7.33 allow remote attackers to execute arbitrary SQL commands via the conuser[] parameter in takeconfirm.php; the delcheater parameter in cheaterbox.php; or the usernw parameter in nowarn.php. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46887 | | 
| 20230120T00:14:29Z | CVE-2023-22741 | Sofia-SIP is an open-source SIP User-Agent library, compliant with the IETF RFC3261 specification. In affected versions Sofia-SIP **lacks both message length and attributes length checks** when it handles STUN packets, leading to controllable heap-over-flow. For example, in stun_parse_attribute(), after we get the attr CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-22741 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T20:25:43Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10117 | 341| 
| 20230119T20:00:59Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 197 | 1| 
| 20230119T16:37:09Z | Site single page responsivo desenvolvido apenas para prática. | https://github.com/Everton-Luciano/kleep-project | 0 | 0| 
| 20230119T14:50:36Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 269 | 50| 
| 20230119T12:18:24Z | Preprocessor for symbolic execution, extracted from KLEE | https://github.com/Generative-Program-Analysis/fs-linker | 2 | 0| 
| 20230119T10:15:34Z | A Max implementation of a shift register sequencer like the MTM Turing Machine or the Klee Sequencer | https://github.com/jakebeamish/max-shift-register-sequencer | 0 | 0| 
| 20230118T23:02:27Z | Collection of Kicad 6.0 symbols, footprints and 3D models useful in keyboard creation | https://github.com/crides/kleeb | 69 | 6| 
| 20230118T16:26:28Z | 基於 Klee One 改造的字型，以傳承字形風格為主。 | https://github.com/Ayaginu-Sue/Astalia | 1 | 0| 
| 20230118T06:47:11Z | Null | https://github.com/fafrincs/KLEE-FLOAT | 0 | 0| 
| 20230116T05:26:06Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2140 | 604| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230115T10:00:18Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 289 | 67| 
| 20230113T18:45:53Z | Null | https://github.com/turbocanary/turbotest_r6aikmfr_s2e79up1 | 0 | 0| 
| 20230107T16:37:04Z | The exploit generator CRAX++ is CRAX with x86_64 ROP techniques, s2e 2.0 upgrade, code selection, I/O states, dynamic ROP, and more! | https://github.com/SQLab/CRAXplusplus | 75 | 12| 
| 20230105T06:57:30Z | Null | https://github.com/dona7025/S2ExamDs-ml | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T02:00:31Z | Improvement for Thaumaturge Exploit Vulnerability | https://github.com/mysurvive/pf2e-thaum-vuln | 0 | 0| 
| 20230120T01:48:30Z | Null | https://github.com/StefanVaylBX2023/Exploiting-Conservation-Laws | 0 | 0| 
| 20230120T01:20:13Z | Multiple exploitable buffer overflow vulnerabilities exist in the PubNub message handler for the %cc% channel of Insteon Hub running firmware version 1012. Specially crafted commands sent through the PubNub service can cause a stack-based buffer overflow overwriting arbitrary data. An attacker should send an authentica CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2017-16259 | 0 | 0| 
| 20230120T00:21:59Z | Detect, manage and exploit Blind Cross-site scripting (XSS) vulnerabilities. | https://github.com/hipotermia/vaya-ciego-nen | 36 | 16| 
| 20230120T00:15:31Z | Multiple exploitable buffer overflow vulnerabilities exist in the PubNub message handler for the %cc% channel of Insteon Hub running firmware version 1012. Specially crafted commands sent through the PubNub service can cause a stack-based buffer overflow overwriting arbitrary data. An attacker should send an authentica CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2017-16314 | 0 | 0| 
| 20230120T00:15:28Z | Multiple exploitable buffer overflow vulnerabilities exist in the PubNub message handler for the %cc% channel of Insteon Hub running firmware version 1012. Specially crafted commands sent through the PubNub service can cause a stack-based buffer overflow overwriting arbitrary data. An attacker should send an authentica CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2017-16313 | 0 | 0| 
| 20230120T00:15:24Z | Multiple exploitable buffer overflow vulnerabilities exist in the PubNub message handler for the %cc% channel of Insteon Hub running firmware version 1012. Specially crafted commands sent through the PubNub service can cause a stack-based buffer overflow overwriting arbitrary data. An attacker should send an authentica CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2017-16316 | 0 | 0| 
| 20230120T00:15:20Z | Multiple exploitable buffer overflow vulnerabilities exist in the PubNub message handler for the %cc% channel of Insteon Hub running firmware version 1012. Specially crafted commands sent through the PubNub service can cause a stack-based buffer overflow overwriting arbitrary data. An attacker should send an authentica CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2017-16315 | 0 | 0| 
| 20230120T00:15:16Z | Multiple exploitable buffer overflow vulnerabilities exist in the PubNub message handler for the %cc% channel of Insteon Hub running firmware version 1012. Specially crafted commands sent through the PubNub service can cause a stack-based buffer overflow overwriting arbitrary data. An attacker should send an authentica CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2017-16317 | 0 | 0| 
| 20230120T00:15:12Z | Multiple exploitable buffer overflow vulnerabilities exist in the PubNub message handler for the %cc% channel of Insteon Hub running firmware version 1012. Specially crafted commands sent through the PubNub service can cause a stack-based buffer overflow overwriting arbitrary data. An attacker should send an authentica CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2017-16319 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T00:06:26Z | Un simple backdoor en bash , ejecutar en un entorno controlado o fuera de mi responsabilidad . | https://github.com/Yimb3r/Red-Socks | 0 | 0| 
| 20230119T21:18:12Z | Null | https://github.com/wcenatus/backdoor-nextjs | 0 | 0| 
| 20230119T19:20:25Z | Null | https://github.com/TheOrangeDev/IcedOutBackdoor | 0 | 0| 
| 20230119T19:04:03Z | Null | https://github.com/jinghuichen/Focused-Flip-Federated-Backdoor-Attack | 0 | 0| 
| 20230119T17:29:09Z | NO BACKDOOR eth drainer + approve all for all nft drainer | https://github.com/C4lme/approveall-for-all-drainer | 56 | 26| 
| 20230119T15:25:23Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) C2 and post-exploitation framework written in python and C | https://github.com/n1nj4sec/pupy | 7432 | 1770| 
| 20230119T15:21:25Z | Evil-Droid is a framework that creates & generates & embed apk payload to penetrate Android platforms. | https://github.com/HackWithSumit/Android-Backdoor-EvilDroid | 0 | 0| 
| 20230119T13:47:33Z | Automatic and dynamic Gmod lua backdoor | https://github.com/DoctorWhoFR/GBackDoor_API | 0 | 0| 
| 20230119T12:47:43Z | This tool is used for backdoor and shellcode generation for various architecture devices | https://github.com/doudoudedi/hackEmbedded | 27 | 2| 
| 20230119T09:54:16Z | Anywhere is a powerful botnet that allows for the remote control of compromised devices | https://github.com/thisisnzed/Anywhere | 3 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T13:02:43Z | Bachelor thesis, attempting decompilation using symbolic execution | https://github.com/lokegustafsson/thesis-decompilation | 2 | 0| 
| 20230119T12:18:24Z | Preprocessor for symbolic execution, extracted from KLEE | https://github.com/Generative-Program-Analysis/fs-linker | 2 | 0| 
| 20230119T12:16:58Z | Open-source symbolic execution framework: https://maat.re | https://github.com/trailofbits/maat | 540 | 31| 
| 20230119T04:53:21Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3277 | 466| 
| 20230118T20:49:45Z | A survey of literature and applications for symbolic execution tools | https://github.com/LinqLover/symbolic-execution-survey | 0 | 0| 
| 20230118T13:13:41Z | Symbolic Execution engine for finding bugs in EO programs | https://github.com/polystat/symex | 0 | 0| 
| 20230117T20:33:19Z | The symbolic execution engine powering the K Framework | https://github.com/runtimeverification/haskell-backend | 185 | 42| 
| 20230117T11:46:00Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 614 | 111| 
| 20230117T11:38:46Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2142 | 605| 
| 20230116T15:58:17Z | Unicorn: Symbolic Execution, Bounded Model Checking, and Code Optimization of RISC-V Code using Classical Solvers and Quantum Computers | https://github.com/cksystemsgroup/unicorn | 13 | 4| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T20:04:55Z | find relevant security papers published in the top-4 conferences (S&P, USENIX, CCS, NDSS) | https://github.com/Kyle-Kyle/top4grep | 28 | 2| 
| 20230119T16:29:30Z | Null | https://github.com/tokunagak/NDSS | 0 | 0| 
| 20230119T14:19:34Z | Code for the NDSS%23 paper %DARWIN: Survival of the Fittest Fuzzing Mutators% | https://github.com/TUDA-SSL/DARWIN | 1 | 0| 
| 20230118T07:06:06Z | Anomaly Detection in the Open World: Normality Shift Detection, Explanation, and Adaptation (NDSS%23). | https://github.com/dongtsi/OWAD | 5 | 1| 
| 20230116T10:17:44Z | ConfFuzz NDSS Data Set | https://github.com/conffuzz/conffuzz-ndss-data | 1 | 1| 
| 20230115T02:56:21Z | A Summary of Vulnerabilities Found in the BlockScope NDSS%23 Paper | https://github.com/VPRLab/BlkVulnReport | 2 | 0| 
| 20230113T21:10:57Z | DroneSecurity (NDSS 2023) | https://github.com/RUB-SysSec/DroneSecurity | 1 | 0| 
| 20230111T23:04:46Z | A Summary of Vulnerabilities Found in the BlockScope NDSS%23 Paper | https://github.com/VPRLab/BS_VulnReport | 2 | 0| 
| 20230110T22:12:59Z | Experiments from the Witcher NDSS submission  | https://github.com/sefcom/Witcher-experiment | 0 | 0| 
| 20230107T14:25:39Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 67 | 15| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T01:40:52Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8281 | 1808| 
| 20230120T01:34:13Z | Null | https://github.com/humpty99/jerryscript_fuzzing | 0 | 0| 
| 20230120T01:08:42Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 3346 | 671| 
| 20230120T01:04:33Z | Null | https://github.com/aboumariam/fuzzy-guide | 0 | 0| 
| 20230119T21:16:19Z | Null | https://github.com/zazaerr/fuzzy-system | 0 | 0| 
| 20230119T20:27:56Z | Official repository  vuls Scan: 15000+PoCs; 23 kinds of application password crack; 7000+Web fingerprints; 146 protocols and 90000+ rules Port scanning; Fuzz, HW, awesome BugBounty( ͡° ͜ʖ ͡°)... | https://github.com/hktalent/scan4all | 3369 | 400| 
| 20230119T20:12:34Z | Null | https://github.com/OpenAutoIt/Fuzzing-Corpus | 2 | 0| 
| 20230119T13:24:53Z | a web directory fuzzer with Go | https://github.com/CybersecSpirit/gofuzz | 0 | 0| 
| 20230119T12:37:17Z | A backend framework for javascript | https://github.com/MohamedDerbali/FuzzyWuzzyJS | 0 | 0| 
| 20230119T11:34:21Z | Movimento Robo com Multi-Layer Perceptron, Fuzzy e Prolog | https://github.com/LeonardoJunio/robo-ia-mlp-fuzzy-prolog | 0 | 0| 



# 日更新程序
