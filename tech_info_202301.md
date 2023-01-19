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
| 20230117 | r3kapig发布关于idek 2022* CTF取证部分的详细writeup | https://sec.today/pulses/81591b87-b420-476f-8c49-afa51cc03231/| 
| 20230117 | Crypto - Finite Realm of Random Writeup by grhkm21 | https://sec.today/pulses/92408033-1f9e-42ad-956a-016805c6baef/| 
| 20230117 | idek 2022* CTF Hardest Demon Bloodbath by Riot题目的writeup | https://sec.today/pulses/0195a0b3-6721-4236-b7ae-023fab555671/| 


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
| 20230119T13:41:10Z | CVE-2022-47966 | POC for CVE-2022-47966 affecting multiple ManageEngine products | https://github.com/horizon3ai/CVE-2022-47966 | | 
| 20230119T13:21:21Z | CVE-2022-45934 | Null | https://github.com/Trinadh465/linux-4.19.72_CVE-2022-45934 | | 
| 20230119T13:15:23Z | CVE-2023-23690 | Cloud Mobility for Dell EMC Storage, versions 1.3.0.X and below contains an Improper Check for Certificate Revocation vulnerability. A threat actor does not need any specific privileges to potentially exploit this vulnerability. An attacker could perform a man-in-the-middle attack and eavesdrop on encrypted communicati CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-23690 | | 
| 20230119T13:15:19Z | CVE-2022-3738 | The vulnerability allows a remote unauthenticated attacker to download a backup file, if one exists. That backup file might contain sensitive information like credentials and cryptographic material. A valid user has to create a backup after the last reboot for this attack to be successfull. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-3738 | | 
| 20230119T12:47:48Z | CVE-2022-46463 | CVE-2022-46463(Harbor 未授权) | https://github.com/nu0l/CVE-2022-46463 | | 
| 20230119T12:08:35Z | CVE-2023-0397 | A malicious / defect bluetooth controller can cause a Denial of Service due to unchecked input in le_read_buffer_size_complete. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0397 | | 
| 20230119T12:08:31Z | CVE-2022-4892 | A vulnerability was found in MyCMS. It has been classified as problematic. This affects the function build_view of the file lib/gener/view.php of the component Visitors Module. The manipulation of the argument original/converted leads to cross site scripting. It is possible to initiate the attack remotely. The name of  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4892 | | 
| 20230119T12:08:17Z | CVE-2023-0398 | Cross-Site Request Forgery (CSRF) in GitHub repository modoboa/modoboa prior to 2.0.4. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0398 | | 
| 20230119T11:50:21Z | CVE-2022-23521 | Truncated Allocation Leading to Out of Bounds Write Via Large Number of Attributes | https://github.com/0xDSousa/CVE-2022-23521 | | 
| 20230119T11:08:52Z | CVE-2021-31800 | A path traversal in smbserver.py allows an attacker to read/write arbitrary files on the server. | https://github.com/p0dalirius/CVE-2021-31800-Impacket-SMB-Server-Arbitrary-file-read-write | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T12:18:24Z | Preprocessor for symbolic execution, extracted from KLEE | https://github.com/Generative-Program-Analysis/fs-linker | 2 | 0| 
| 20230119T10:15:34Z | A Max implementation of a shift register sequencer like the MTM Turing Machine or the Klee Sequencer | https://github.com/jakebeamish/max-shift-register-sequencer | 0 | 0| 
| 20230119T06:05:05Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10114 | 341| 
| 20230119T05:55:47Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 196 | 1| 
| 20230118T23:02:27Z | Collection of Kicad 6.0 symbols, footprints and 3D models useful in keyboard creation | https://github.com/crides/kleeb | 69 | 6| 
| 20230118T16:26:28Z | 基於 Klee One 改造的字型，以傳承字形風格為主。 | https://github.com/Ayaginu-Sue/Astalia | 1 | 0| 
| 20230118T06:47:11Z | Null | https://github.com/fafrincs/KLEE-FLOAT | 0 | 0| 
| 20230116T05:26:06Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2140 | 604| 
| 20230115T09:30:31Z | Null | https://github.com/klee30810/klee30810 | 2 | 0| 
| 20230113T14:56:21Z | contains the code and data to accompany the publication of the pyKleeBarcode software (https://github.com/WandrilleD/pyKleeBarcode) | https://github.com/WandrilleD/pyKleeBarcode-publication-supporting-code-and-data | 0 | 0| 


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
| 20230119T13:41:32Z | A tool to identify and exploit sudo rules% misconfigurations and vulnerabilities within sudo for linux privilege escalation. | https://github.com/TH3xACE/SUDO_KILLER | 1719 | 218| 
| 20230119T13:37:41Z | 🖱️ , AUTOCLICKER MADE FOR MINECRAFT , UNDETECTED , BYPASS LUNAR CLIENT AND MORE  | https://github.com/Suldue/Minecraft-Autoclicker | 0 | 0| 
| 20230119T13:15:23Z | Cloud Mobility for Dell EMC Storage, versions 1.3.0.X and below contains an Improper Check for Certificate Revocation vulnerability. A threat actor does not need any specific privileges to potentially exploit this vulnerability. An attacker could perform a man-in-the-middle attack and eavesdrop on encrypted communicati CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-23690 | 0 | 0| 
| 20230119T12:44:06Z | Reverse Shell as a Service | https://github.com/lukechilds/reverse-shell | 1597 | 226| 
| 20230119T12:03:23Z | Null | https://github.com/Lossless-Cash/exploit-db | 0 | 0| 
| 20230119T11:23:24Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) C2 and post-exploitation framework written in python and C | https://github.com/n1nj4sec/pupy | 7431 | 1770| 
| 20230119T11:03:50Z | This tool is created to search for sensitive files, sensitive information by exploiting google dorking techniques | https://github.com/Yohann76/DorkingTools | 0 | 0| 
| 20230119T10:41:26Z | CVE-2022-47966 ManageEngine unauthenticated RCE exploit via the SAML request, | https://github.com/ralph-morrinson/CVE-2022-47966-RCE-PoC | 0 | 0| 
| 20230119T09:06:03Z | This repository is primarily maintained by Omar Santos (@santosomar) and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 12610 | 2163| 
| 20230119T08:33:01Z | Base de données de films (MongoDB) à exploiter avec des requêtes et des tests unitaires | https://github.com/75andybermond/MflixMongoDB | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T12:47:43Z | This tool is used for backdoor and shellcode generation for various architecture devices | https://github.com/doudoudedi/hackEmbedded | 27 | 2| 
| 20230119T11:23:24Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) C2 and post-exploitation framework written in python and C | https://github.com/n1nj4sec/pupy | 7431 | 1770| 
| 20230119T09:54:16Z | Anywhere is a powerful botnet that allows for the remote control of compromised devices | https://github.com/thisisnzed/Anywhere | 3 | 0| 
| 20230119T09:48:21Z | A Basic 100% Python RAT | https://github.com/sirmilann/TempoRat | 2 | 1| 
| 20230119T06:14:32Z | Implementation of XGBD: Explanation-Guided Backdoor Detection on Graphs | https://github.com/GuanZihan/GNN_backdoor_detection | 1 | 0| 
| 20230119T02:23:49Z | Null | https://github.com/Gabriel160204/Backdoor-Reverse-Shell | 0 | 0| 
| 20230118T23:09:05Z | The BackDoor of HIPHP gives you the power to control websites based on PHP using HTTP/HTTPS protocol. By sending files, tokens and commands through port 80%s POST/GET method, users can access a range of activities such as downloading and editing files. It also allows for connecting to Tor networks with password protection for extra security. | https://github.com/yasserbdj96/hiphp | 37 | 10| 
| 20230118T19:13:28Z | Official repository of paper BEAGLE: Forensics of Deep Learning Backdoor Attack for Better Defense | https://github.com/Megum1/BEAGLE | 3 | 0| 
| 20230118T15:01:24Z | This repository contains experiments for Masters Thesis of Computer Science on AGH University of Science. Topic of thesis was Attacks on image-processing neural networks. Backdoor patch attack was carried out on three neural networks trained with use of transfer learning. Attacks were launched with use of static and adaptive adversarial patches created with targeted deepfool algorithm.  | https://github.com/oreganko/Attacks-On-Image-Processing-Neural-Networks | 1 | 0| 
| 20230118T12:22:36Z | Automatic and dynamic Gmod lua backdoor | https://github.com/DoctorWhoFR/GBackDoor | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T13:02:43Z | Bachelor thesis, attempting decompilation using symbolic execution | https://github.com/lokegustafsson/thesis-decompilation | 2 | 0| 
| 20230119T12:18:24Z | Preprocessor for symbolic execution, extracted from KLEE | https://github.com/Generative-Program-Analysis/fs-linker | 2 | 0| 
| 20230119T12:16:58Z | Open-source symbolic execution framework: https://maat.re | https://github.com/trailofbits/maat | 540 | 31| 
| 20230119T04:53:21Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3277 | 465| 
| 20230118T20:49:45Z | A survey of literature and applications for symbolic execution tools | https://github.com/LinqLover/symbolic-execution-survey | 0 | 0| 
| 20230118T13:13:41Z | Symbolic Execution engine for finding bugs in EO programs | https://github.com/polystat/symex | 0 | 0| 
| 20230117T20:33:19Z | The symbolic execution engine powering the K Framework | https://github.com/runtimeverification/haskell-backend | 185 | 42| 
| 20230117T11:46:00Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 614 | 111| 
| 20230117T11:38:46Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2142 | 605| 
| 20230116T15:58:17Z | Unicorn: Symbolic Execution, Bounded Model Checking, and Code Optimization of RISC-V Code using Classical Solvers and Quantum Computers | https://github.com/cksystemsgroup/unicorn | 13 | 4| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230118T07:06:06Z | Anomaly Detection in the Open World: Normality Shift Detection, Explanation, and Adaptation (NDSS%23). | https://github.com/dongtsi/OWAD | 5 | 1| 
| 20230116T10:17:44Z | ConfFuzz NDSS Data Set | https://github.com/conffuzz/conffuzz-ndss-data | 1 | 1| 
| 20230115T02:56:21Z | A Summary of Vulnerabilities Found in the BlockScope NDSS%23 Paper | https://github.com/VPRLab/BlkVulnReport | 2 | 0| 
| 20230113T21:10:57Z | DroneSecurity (NDSS 2023) | https://github.com/RUB-SysSec/DroneSecurity | 1 | 0| 
| 20230112T19:39:31Z | find relevant security papers published in the top-4 conferences (S&P, USENIX, CCS, NDSS) | https://github.com/Kyle-Kyle/top4grep | 27 | 2| 
| 20230111T23:04:46Z | A Summary of Vulnerabilities Found in the BlockScope NDSS%23 Paper | https://github.com/VPRLab/BS_VulnReport | 2 | 0| 
| 20230110T22:12:59Z | Experiments from the Witcher NDSS submission  | https://github.com/sefcom/Witcher-experiment | 0 | 0| 
| 20230107T14:25:39Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 67 | 15| 
| 20230107T11:53:42Z | https://github.com/anonauthorsub/submission_code_ndss_f2022_545/tree/main/vkd_ozks | https://github.com/xiezy0/vkd_ozks | 0 | 0| 
| 20230103T18:15:20Z | The pre-processed Juliet, NDSS18 datasets for Assembly code summarization | https://github.com/L1NNA/Juliet-NDSS18-BinaryCodeSum | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T13:24:53Z | a web directory fuzzer with Go | https://github.com/CybersecSpirit/gofuzz | 0 | 0| 
| 20230119T12:37:17Z | A backend framework for javascript | https://github.com/MohamedDerbali/FuzzyWuzzyJS | 0 | 0| 
| 20230119T11:34:21Z | Movimento Robo com Multi-Layer Perceptron, Fuzzy e Prolog | https://github.com/LeonardoJunio/robo-ia-mlp-fuzzy-prolog | 0 | 0| 
| 20230119T11:26:27Z | SPK dengan metode Fuzzy AHP | https://github.com/riyanandri/fuzzy_ahp | 0 | 0| 
| 20230119T11:22:15Z | Null | https://github.com/jhibongh/fuzzy-journey | 0 | 0| 
| 20230119T10:36:10Z | Null | https://github.com/chill-panda/fuzzy-rotary-phone.github.io | 0 | 0| 
| 20230119T10:30:07Z | Framework for Structure Aware Fuzzing. Allows to build own stamps that would convert pulp-data that came from fuzzer to data with structure you need | https://github.com/postgrespro/libblobstamper | 10 | 0| 
| 20230119T09:32:02Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 4524 | 1096| 
| 20230119T06:44:46Z | Tutorials, examples, discussions, research proposals, and other resources related to fuzzing | https://github.com/google/fuzzing | 2524 | 360| 
| 20230119T06:17:25Z | Esse repositório contém os códigos dos algoritmos  Gaussian Kernel Fuzzy Double K-Means (GKFDK), Gaussian Kernel Fuzzy Double K-Means Based on Global Adaptive Distance (GKFDK-GP) e Gaussian Kernel Fuzzy Double K-Means Based on Local Adaptive Distance (GKFDK-LP). Esses algoritmos são modelos de co-clustering. | https://github.com/Natandradesa/Kernel_Fuzzy_Co-clustering | 0 | 0| 



# 日更新程序
