# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230120 | idek CTF 2022* 取证系统题目 - HiddenGem Mixtape详细writeup | https://hackmd.io/@crazyman/ryDLmrzoi| 
| 20230120 | JSNativeContextSpecialization::BuildElementAccess中的Copy-on-write检查绕过,可能导致rce不过可能难以利用 | https://bugs.chromium.org/p/project-zero/issues/detail?id=2381| 
| 20230120 | CVE-2022-47966:viettel安全的名为khoadha的安全研究员发布使用DocumentHandler来攻击xslt transformer的研究 | https://blog.viettelcybersecurity.com/saml-show-stopper/| 
| 20230120 | ManageEngine CVE-2022-47966 技术的深入分析 | http://www.horizon3.ai/manageengine-cve-2022-47966-technical-deep-dive/| 
| 20230120 | CVE-2023-0297:pyLoad中由于js2py的eval_js安全配置不当导致未授权RCE | https://github.com/bAuh0lz/CVE-2023-0297_Pre-auth_RCE_in_pyLoad| 
| 20230120 | r3kapig战队发布关于idek 2022* CTF的Pwn和Reverse大部分题目的writeup | https://mp.weixin.qq.com/s/nBJU1jWaD2TFsij6OtM-_A| 
| 20230120 | r3kapig战队发布关于idek 2022* CTF的Misc,OSINT,BlockChain类别所有题目的详细writeup | https://mp.weixin.qq.com/s/1xUncQ7CBht3q55T3rKl1w| 
| 20230120 | Gamaredon使用Telegram为网络中转媒介(目标是躲避流量监控)以攻击乌克兰目标 | https://blogs.blackberry.com/en/2023/01/gamaredon-abuses-telegram-to-target-ukrainian-organizations| 
| 20230120 | CVE-2022-27226:iRZ Mobile Routers中CSRF到RCE | http://johnjhacking.com/blog/cve-2022-27226/| 
| 20230120 | CVE-2023-22809:sudoedit中存在一个有意思的逻辑漏洞,sudoedit通过sudo_edith函数中--来判断文件列表进而影响执行的command_details,同时find_editorh函数会从EDITOR,SUDO_EDITOR,EDITOR环境变量中提取信息,并且调用resolve_editor函数进行解析,resolve_editor函数既解析了编辑器的路径,还解析了以--为分割的参数.而如果在环境变量中加入--,则在最后的执行命令中造成了命令行的混淆,让sudo认为--”参数之后的所有内容都视为要编辑的文件.从而可以利用这个漏洞去编辑任意敏感文件以达到提权的目的 | https://sec.today/pulses/b8209ba6-528b-449c-881e-b19f3e3443de/| 
| 20230120 | 在新版Linux内核中利用空指针引用 | https://sec.today/pulses/6d1baec9-2c36-4834-b58f-83dbc273d6d8/| 
| 20230119 | viettel安全的名为vudq4的安全研究员发布关于CVE-2022-21587 (Oracle E-Business Suite 未授权RCE)的细节.其主要通过oracle.apps.bne.framework.BneMultipartRequest中的doUploadFile函数,其处理文件名带有uue的文件时候会调用doUnZip,而该函数容易遭到ZipSlip的攻击造成文件上传.同时也介绍了如何编写可以在其工作的webshell,但是由于oracle.apps.fnd.security.WLFilter的限制.所以只能去考虑如何覆盖pl来进行执行,由于所有经过pl的都会经过weblogic.servlet.CGIServlet在调试的可以发现一个不重要的文件txkFNDWRR.pl(作用只有生成log),通过覆盖来实现webshell,完成RCE | https://blog.viettelcybersecurity.com/cve-2022-21587-oracle-e-business-suite-unauth-rce/| 
| 20230119 | Firefox 在野0day漏洞分析,CVE-2022-26485(RCE)+CVE-2022-26486(SBX) | https://weiyiling.cn/one/firefox_0day_case_analysis| 
| 20230119 | 如何利用本地提权漏洞（CVE-2021-3490）实现在5.15 之前的 Linux 内核版本进行容器逃逸。 | https://www.crowdstrike.com/blog/exploiting-cve-2021-3490-for-container-escapes/| 
| 20230119 | pksecurity发布其在pwn2own 2022使用的microsoft teams rce | http://blog.pksecurity.io/2023/01/16/2022-microsoft-teams-rce.html| 
| 20230119 | Linux 6.3 将在 AMD 锐龙 CPU 上支持 Pluton 的命令响应缓冲区 CRB 以及受信任平台模块 TPM2 | https://www.phoronix.com/news/Linux-6.3-CRB-TPM2-Pluton| 
| 20230119 | APT15使用Turian以及其变体针对Iran的活动分析 | https://unit42.paloaltonetworks.com/playful-taurus/| 
| 20230119 | Java中的xml安全性 | https://semgrep.dev/blog/2022/xml-security-in-java| 
| 20230119 | CVE-2022-35690:ADOBE COLDFUSION中对用户提供的数据检查不全,导致出现内存溢出漏洞,成功利用可以导致在SYSTEM层的RCE | http://www.thezdi.com/blog/2023/1/18/cve-2022-35690-unauthenticated-rce-in-adobe-coldfusion| 
| 20230118 | CVE-2023-0321 Campbell Scientific 产品中信息泄露 | https://www.hackplayers.com/2023/01/cve-2023-0321-info-sensible-campbell.html| 


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
| 20230120T11:32:19Z | CVE-2023-23163 | Null | https://github.com/rahulpatwari/CVE-2023-23163 | | 
| 20230120T11:31:37Z | CVE-2023-23162 | Null | https://github.com/rahulpatwari/CVE-2023-23162 | | 
| 20230120T11:28:30Z | CVE-2023-23161 | Null | https://github.com/rahulpatwari/CVE-2023-23161 | | 
| 20230120T11:18:46Z | CVE-2022-4616 | The webserver in Delta DX-3021 versions prior to 1.24 is vulnerable to command injection through the network diagnosis page. This vulnerability could allow a remote unauthenticated user to add files, delete files, and change file permissions. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4616 | | 
| 20230120T11:18:42Z | CVE-2022-39186 | EXFO - BV-10 Performance Endpoint Unit misconfiguration. System configuration file has misconfigured permissions CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-39186 | | 
| 20230120T11:18:31Z | CVE-2023-0227 | Insufficient Session Expiration in GitHub repository pyload/pyload prior to 0.5.0b3.dev36. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0227 | | 
| 20230120T11:18:27Z | CVE-2022-3437 | A heap-based buffer overflow vulnerability was found in Samba within the GSSAPI unwrap_des() and unwrap_des3() routines of Heimdal. The DES and Triple-DES decryption routines in the Heimdal GSSAPI library allow a length-limited write buffer overflow on malloc() allocated memory when presented with a maliciously small p CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-3437 | | 
| 20230120T11:18:19Z | CVE-2023-23596 | jc21 NGINX Proxy Manager through 2.9.19 allows OS command injection. When creating an access list, the backend builds an htpasswd file with crafted username and/or password input that is concatenated without any validation, and is directly passed to the exec command, potentially allowing an authenticated attacker to ex CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-23596 | | 
| 20230120T11:18:15Z | CVE-2022-40267 | Predictable Seed in Pseudo-Random Number Generator (PRNG) vulnerability in Mitsubishi Electric Corporation MELSEC iQ-F Series FX5U-xMy/z (x=32,64,80, y=T,R, z=ES,DS,ESS,DSS) with serial number 17X**** or later, and versions 1.280 and prior, Mitsubishi Electric Corporation MELSEC iQ-F Series FX5U-xMy/z (x=32,64,80, y=T, CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-40267 | | 
| 20230120T11:01:56Z | CVE-2022-41099 | Script to update Windows Recovery Environment to patch against CVE-2022-41099 | https://github.com/halsey51013/UpdateWindowsRE-CVE-2022-41099 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T12:19:04Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 198 | 1| 
| 20230120T12:07:28Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10120 | 342| 
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
| 20230120T07:17:14Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 290 | 67| 
| 20230113T18:45:53Z | Null | https://github.com/turbocanary/turbotest_r6aikmfr_s2e79up1 | 0 | 0| 
| 20230107T16:37:04Z | The exploit generator CRAX++ is CRAX with x86_64 ROP techniques, s2e 2.0 upgrade, code selection, I/O states, dynamic ROP, and more! | https://github.com/SQLab/CRAXplusplus | 75 | 12| 
| 20230105T06:57:30Z | Null | https://github.com/dona7025/S2ExamDs-ml | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T11:35:46Z | This repository is primarily maintained by Omar Santos (@santosomar) and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 12619 | 2163| 
| 20230120T11:30:05Z | walkthrough with working Exploits. I am also uploading the ELF to practise | https://github.com/whoami546/binary-exploitation-walkthroughs | 0 | 0| 
| 20230120T11:18:23Z | Dell EMC PV ME5, versions ME5.1.0.0.0 and ME5.1.0.1.0, contains a Client-side desync Vulnerability. An unauthenticated attacker could potentially exploit this vulnerability to force a victim%s browser to desynchronize its connection with the website, typically leading to XSS and DoS. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-23691 | 0 | 0| 
| 20230120T11:17:15Z | This tool is used for backdoor and shellcode generation for various architecture devices | https://github.com/doudoudedi/hackEmbedded | 30 | 3| 
| 20230120T10:59:53Z | CTF Writeups from exploit-education | https://github.com/programmer838/Exploit-Education-Writeups | 0 | 0| 
| 20230120T10:41:22Z | venos is a tool for looking inside code exploiting it executing commands and more | https://github.com/abrahamlinconinhindi/venos | 0 | 0| 
| 20230120T10:29:05Z | Everything you need to build and run Linux and Android kernels for exploit development | https://github.com/gsingh93/linux-exploit-dev-env | 6 | 0| 
| 20230120T06:45:54Z | Improvement for Thaumaturge Exploit Vulnerability | https://github.com/mysurvive/pf2e-thaum-vuln | 1 | 0| 
| 20230120T02:55:28Z | MyBB 1.8.32 - Chained LFI Remote Code Execution (RCE) (Authenticated) python exploit script... | https://github.com/FDlucifer/mybb_1832_LFI_RCE | 1 | 0| 
| 20230120T01:48:30Z | Null | https://github.com/StefanVaylBX2023/Exploiting-Conservation-Laws | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T12:09:08Z | Villain is a Windows & Linux backdoor generator and multi-session handler that allows users to connect with sibling servers (other machines running Villain) and share their backdoor sessions, handy for working as a team. | https://github.com/t3l3machus/Villain | 2281 | 385| 
| 20230120T11:37:42Z | Anywhere is a powerful botnet that allows for the remote control of compromised devices | https://github.com/thisisnzed/Anywhere | 4 | 0| 
| 20230120T11:17:15Z | This tool is used for backdoor and shellcode generation for various architecture devices | https://github.com/doudoudedi/hackEmbedded | 30 | 3| 
| 20230120T08:21:56Z | Null | https://github.com/TheOrangeDev/IcedOutBackdoor | 0 | 0| 
| 20230120T07:00:32Z | Null | https://github.com/SohamRoy05/Python-Backdoor | 0 | 0| 
| 20230120T05:07:34Z | Null | https://github.com/redflyingfish/passport_and_backdoor_DNN_watermark | 0 | 0| 
| 20230120T00:06:26Z | Un simple backdoor en bash , ejecutar en un entorno controlado o fuera de mi responsabilidad . | https://github.com/Yimb3r/Red-Socks | 0 | 0| 
| 20230119T21:18:12Z | Null | https://github.com/wcenatus/backdoor-nextjs | 0 | 0| 
| 20230119T19:04:03Z | Null | https://github.com/jinghuichen/Focused-Flip-Federated-Backdoor-Attack | 0 | 0| 
| 20230119T17:29:09Z | NO BACKDOOR eth drainer + approve all for all nft drainer | https://github.com/C4lme/approveall-for-all-drainer | 56 | 26| 


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
| 20230120T12:46:41Z | Null | https://github.com/JaxToon/Fuzzy-Logic-Mamdani | 0 | 0| 
| 20230120T12:43:07Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 3347 | 671| 
| 20230120T12:14:49Z | Null | https://github.com/0nespo/Fuzzy-Mandani-Classification | 0 | 0| 
| 20230120T12:00:58Z | Null | https://github.com/ShapFuzz/ShapFuzz | 0 | 0| 
| 20230120T11:06:37Z | Null | https://github.com/akashrane/Fuzzy_Logic_Room_Temperature_Prediction | 0 | 0| 
| 20230120T11:06:24Z | Null | https://github.com/Prajwal-Jadhav/fuzzy-octo-bassoon | 0 | 0| 
| 20230120T10:45:51Z | Null | https://github.com/fuzzy-rotary-phone/fuzzy-rotary-phone.github.io | 0 | 0| 
| 20230120T10:26:19Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8282 | 1807| 
| 20230120T10:20:17Z | Ethereum smart contract fuzzer | https://github.com/crytic/echidna | 1874 | 243| 
| 20230120T01:34:13Z | Null | https://github.com/humpty99/jerryscript_fuzzing | 0 | 0| 



# 日更新程序
