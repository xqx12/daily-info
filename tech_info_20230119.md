# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230119 | viettel安全的名为vudq4的安全研究员发布关于CVE-2022-21587 (Oracle E-Business Suite 未授权RCE)的细节.其主要通过oracle.apps.bne.framework.BneMultipartRequest中的doUploadFile函数,其处理文件名带有uue的文件时候会调用doUnZip,而该函数容易遭到ZipSlip的攻击造成文件上传.同时也介绍了如何编写可以在其工作的webshell,但是由于oracle.apps.fnd.security.WLFilter的限制.所以只能去考虑如何覆盖pl来进行执行,由于所有经过pl的都会经过weblogic.servlet.CGIServlet在调试的可以发现一个不重要的文件txkFNDWRR.pl(作用只有生成log),通过覆盖来实现webshell,完成RCE | https://blog.viettelcybersecurity.com/cve-2022-21587-oracle-e-business-suite-unauth-rce/| 
| 20230119 | Firefox 在野0day漏洞分析,CVE-2022-26485(RCE)+CVE-2022-26486(SBX) | https://weiyiling.cn/one/firefox_0day_case_analysis| 
| 20230119 | 如何利用本地提权漏洞（CVE-2021-3490）实现在5.15 之前的 Linux 内核版本进行容器逃逸。 | https://www.crowdstrike.com/blog/exploiting-cve-2021-3490-for-container-escapes/| 


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
| 20230119T13:12:29Z | CVE-2022-47966 | POC for CVE-2022-47966 affecting multiple ManageEngine products | https://github.com/horizon3ai/CVE-2022-47966 | | 
| 20230119T12:47:48Z | CVE-2022-46463 | CVE-2022-46463(Harbor 未授权) | https://github.com/nu0l/CVE-2022-46463 | | 
| 20230119T12:12:29Z | CVE-2022-45934 | Null | https://github.com/Trinadh465/linux-4.19.72_CVE-2022-45934 | | 
| 20230119T12:08:35Z | CVE-2023-0397 | A malicious / defect bluetooth controller can cause a Denial of Service due to unchecked input in le_read_buffer_size_complete. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0397 | | 
| 20230119T12:08:31Z | CVE-2022-4892 | A vulnerability was found in MyCMS. It has been classified as problematic. This affects the function build_view of the file lib/gener/view.php of the component Visitors Module. The manipulation of the argument original/converted leads to cross site scripting. It is possible to initiate the attack remotely. The name of  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4892 | | 
| 20230119T12:08:17Z | CVE-2023-0398 | Cross-Site Request Forgery (CSRF) in GitHub repository modoboa/modoboa prior to 2.0.4. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0398 | | 
| 20230119T11:50:21Z | CVE-2022-23521 | Truncated Allocation Leading to Out of Bounds Write Via Large Number of Attributes | https://github.com/0xDSousa/CVE-2022-23521 | | 
| 20230119T11:08:52Z | CVE-2021-31800 | A path traversal in smbserver.py allows an attacker to read/write arbitrary files on the server. | https://github.com/p0dalirius/CVE-2021-31800-Impacket-SMB-Server-Arbitrary-file-read-write | | 
| 20230119T10:41:26Z | CVE-2022-47966 | CVE-2022-47966 ManageEngine unauthenticated RCE exploit via the SAML request, | https://github.com/ralph-morrinson/CVE-2022-47966-RCE-PoC | | 
| 20230119T06:38:53Z | CVE-2022-27778 | A use of incorrectly resolved name vulnerability fixed in 7.83.1 might remove the wrong file when `--no-clobber` is used together with `--remove-on-error`. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-27778 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T12:18:24Z | Preprocessor for symbolic execution, extracted from KLEE | https://github.com/Generative-Program-Analysis/fs-linker | 2 | 0| 
| 20230119T10:15:34Z | A Max implementation of a shift register sequencer like the MTM Turing Machine or the Klee Sequencer | https://github.com/jakebeamish/max-shift-register-sequencer | 0 | 0| 
| 20230119T06:05:05Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10114 | 341| 
| 20230119T05:55:47Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 196 | 1| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T12:44:06Z | Reverse Shell as a Service | https://github.com/lukechilds/reverse-shell | 1597 | 226| 
| 20230119T12:43:34Z | A tool to identify and exploit sudo rules% misconfigurations and vulnerabilities within sudo for linux privilege escalation. | https://github.com/TH3xACE/SUDO_KILLER | 1715 | 218| 
| 20230119T12:03:23Z | Null | https://github.com/Lossless-Cash/exploit-db | 0 | 0| 
| 20230119T11:23:24Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) C2 and post-exploitation framework written in python and C | https://github.com/n1nj4sec/pupy | 7431 | 1770| 
| 20230119T11:03:50Z | This tool is created to search for sensitive files, sensitive information by exploiting google dorking techniques | https://github.com/Yohann76/DorkingTools | 0 | 0| 
| 20230119T10:41:26Z | CVE-2022-47966 ManageEngine unauthenticated RCE exploit via the SAML request, | https://github.com/ralph-morrinson/CVE-2022-47966-RCE-PoC | 0 | 0| 
| 20230119T09:06:03Z | This repository is primarily maintained by Omar Santos (@santosomar) and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 12610 | 2163| 
| 20230119T08:33:01Z | Base de données de films (MongoDB) à exploiter avec des requêtes et des tests unitaires | https://github.com/75andybermond/MflixMongoDB | 0 | 0| 
| 20230119T08:25:04Z | Script Python para detectar falhas em alvos SMB mal configurados. Enumera usuários, diretórios, arquivos e compartilhamentos.  | https://github.com/LucasMorato/SMBCheckerExploiter | 0 | 0| 
| 20230119T06:25:07Z | 威胁情报-漏洞存储库 | https://github.com/adminlove520/Poc-Monitor_v1.0.1 | 7 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T12:47:43Z | This tool is used for backdoor and shellcode generation for various architecture devices | https://github.com/doudoudedi/hackEmbedded | 27 | 2| 
| 20230119T11:23:24Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) C2 and post-exploitation framework written in python and C | https://github.com/n1nj4sec/pupy | 7431 | 1770| 
| 20230119T09:54:16Z | Anywhere is a powerful botnet that allows for the remote control of compromised devices | https://github.com/thisisnzed/Anywhere | 3 | 0| 
| 20230119T09:48:21Z | A Basic 100% Python RAT | https://github.com/sirmilann/TempoRat | 2 | 1| 
| 20230119T06:14:32Z | Implementation of XGBD: Explanation-Guided Backdoor Detection on Graphs | https://github.com/GuanZihan/GNN_backdoor_detection | 1 | 0| 
| 20230119T02:23:49Z | Null | https://github.com/Gabriel160204/Backdoor-Reverse-Shell | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T13:02:43Z | Bachelor thesis, attempting decompilation using symbolic execution | https://github.com/lokegustafsson/thesis-decompilation | 2 | 0| 
| 20230119T12:18:24Z | Preprocessor for symbolic execution, extracted from KLEE | https://github.com/Generative-Program-Analysis/fs-linker | 2 | 0| 
| 20230119T12:16:58Z | Open-source symbolic execution framework: https://maat.re | https://github.com/trailofbits/maat | 540 | 31| 
| 20230119T04:53:21Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3277 | 465| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230119T12:37:17Z | A backend framework for javascript | https://github.com/MohamedDerbali/FuzzyWuzzyJS | 0 | 0| 
| 20230119T11:34:21Z | Movimento Robo com Multi-Layer Perceptron, Fuzzy e Prolog | https://github.com/LeonardoJunio/robo-ia-mlp-fuzzy-prolog | 0 | 0| 
| 20230119T11:26:27Z | SPK dengan metode Fuzzy AHP | https://github.com/riyanandri/fuzzy_ahp | 0 | 0| 
| 20230119T11:22:15Z | Null | https://github.com/jhibongh/fuzzy-journey | 0 | 0| 
| 20230119T10:36:10Z | Null | https://github.com/chill-panda/fuzzy-rotary-phone.github.io | 0 | 0| 
| 20230119T10:30:07Z | Framework for Structure Aware Fuzzing. Allows to build own stamps that would convert pulp-data that came from fuzzer to data with structure you need | https://github.com/postgrespro/libblobstamper | 10 | 0| 
| 20230119T09:32:02Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 4524 | 1096| 
| 20230119T06:44:46Z | Tutorials, examples, discussions, research proposals, and other resources related to fuzzing | https://github.com/google/fuzzing | 2524 | 360| 
| 20230119T06:17:25Z | Esse repositório contém os códigos dos algoritmos  Gaussian Kernel Fuzzy Double K-Means (GKFDK), Gaussian Kernel Fuzzy Double K-Means Based on Global Adaptive Distance (GKFDK-GP) e Gaussian Kernel Fuzzy Double K-Means Based on Local Adaptive Distance (GKFDK-LP). Esses algoritmos são modelos de co-clustering. | https://github.com/Natandradesa/Kernel_Fuzzy_Co-clustering | 0 | 0| 
| 20230119T02:40:43Z | Null | https://github.com/OpenAutoIt/Fuzzing-Corpus | 1 | 0| 



# 日更新程序
