# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210901 | Deception in Depth - LSASS Injection | https://blog.spookysec.net/DnD-LSASS-Injection/| 
| 20210901 | libssh 密钥交换过程被发现存在一个堆缓冲区溢出漏洞（CVE-2021-3634) | https://bugzilla.redhat.com/show_bug.cgi?id=1978810| 
| 20210901 | SPARROW - 利用 LTE, 5G 信号的广播信号实现隐蔽通信 | https://arxiv.org/pdf/2108.12161.pdf| 
| 20210901 | 本田雅阁、思域等多款车存在密钥重放攻击安全漏洞 | https://github.com/hackingintoyourheart/unoriginal-rice-patty| 
| 20210901 | Thinkst 安全团队对近期多个安全会议以及 Paper 的研究总结报告 | https://thinkst.com/ts/ThinkstScapes-2021-Q3-a.pdf| 
| 20210901 | frida-swift-bridge - 在 Frida 中操作 Swift 的工具 | https://github.com/hot3eed/frida-swift-bridge| 
| 20210901 | GCC、Clang、Visual Studio 编译器支持的一些安全特性 | https://airbus-seclab.github.io/c-compiler-security/| 
| 20210901 | Fix for CVE-2021-1748 itms scheme XSS vulnerability | https://github.com/tihmstar/itmsBlock| 
| 20210901 | 利用 QBDL 工具在 Linux 平台运行 NVIDIA NGX SDK | https://sec.today/pulses/3f45ee47-7442-449b-9111-123c6b4e3f6e/| 
| 20210901 | Android 内核 ARM Mali GPU 驱动里的一个逻辑漏洞的分析 | https://sec.today/pulses/9f476fd9-02a8-4fcb-be8f-33552b6b3e94/| 
| 20210901 | 利用 QBDL 工具在 Linux 平台运行 NVIDIA NGX SDK | http://blog.quarkslab.com/introducing-qbdl-how-to-run-the-nvidia-ngx-sdk-under-linux.html| 
| 20210901 | Android 内核 ARM Mali GPU 驱动里的一个逻辑漏洞的分析 | https://vul.360.net/archives/263| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210901 | 源码解析angr的模拟执行 | https://www.anquanke.com/post/id/251983| 
| 20210901 | 二进制角度构造Java反序列化Payload | https://www.anquanke.com/post/id/252024| 
| 20210901 | A-Journey-into-Synology-NAS-系列——群晖NAS介绍 | https://www.anquanke.com/post/id/251883| 
| 20210901 | GitHub Pull Request业务逻辑风险 | https://mp.weixin.qq.com/s/Fo0OhNb-MP-GqKM-ASCXsg| 
| 20210901 | CVE-2021-39165: 从一个Laravel SQL注入漏洞开始的Bug Bounty... | https://www.leavesongs.com/PENETRATION/cachet-from-laravel-sqli-to-bug-bounty.html| 
| 20210901 | 利用TCP反射放大攻击将中间件武器化 | https://blog.csdn.net/weixin_49393427/article/details/120025179| 
| 20210901 | GSLibrary: 轻量级知识库&POC管理平台 | https://github.com/G-Security-Team/GSLibrary| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210901T13:15:28Z | CVE-2021-1675 | PrintNightMare LPE提权漏洞的CS 反射加载插件。开箱即用、通过内存加载、混淆加载的驱动名称来ByPass Defender/EDR。 | https://github.com/mstxq17/CVE-2021-1675_RDL_LPE | Windows Print Spooler Elevation of Privilege Vulnerability| 
| 20210901T13:02:56Z | CVE-2021-26084 | Confluence Server Webwork OGNL injection | https://github.com/h3v0x/CVE-2021-26084_Confluence | In affected versions of Confluence Server and Data Center, an OGNL injection vulnerability exists that would allow an authenticated user, and in some instances an unauthenticated user, to execute arbitrary code on a Confluence Server or Data Center instance. The vulnerable endpoints can be accessed by a non-administrator user or unauthenticated user if ‘Allow people to sign up to create their account’ is enabled. To check whether this is enabled go to COG > User Management > User Signup Options. The affected versions are before version 6.13.23, from version 6.14.0 before 7.4.11, from version 7.5.0 before 7.11.6, and from version 7.12.0 before 7.12.5.| 
| 20210901T12:58:35Z | CVE-2021-26084 | Remote Code Execution on Confluence Servers : CVE-2021-26084 | https://github.com/Vulnmachines/Confluence_CVE-2021-26084 | In affected versions of Confluence Server and Data Center, an OGNL injection vulnerability exists that would allow an authenticated user, and in some instances an unauthenticated user, to execute arbitrary code on a Confluence Server or Data Center instance. The vulnerable endpoints can be accessed by a non-administrator user or unauthenticated user if ‘Allow people to sign up to create their account’ is enabled. To check whether this is enabled go to COG > User Management > User Signup Options. The affected versions are before version 6.13.23, from version 6.14.0 before 7.4.11, from version 7.5.0 before 7.11.6, and from version 7.12.0 before 7.12.5.| 
| 20210901T12:55:11Z | CVE-2021-26084 | Atlassian Confluence Pre-Auth RCE | https://github.com/Udyz/CVE-2021-26084 | In affected versions of Confluence Server and Data Center, an OGNL injection vulnerability exists that would allow an authenticated user, and in some instances an unauthenticated user, to execute arbitrary code on a Confluence Server or Data Center instance. The vulnerable endpoints can be accessed by a non-administrator user or unauthenticated user if ‘Allow people to sign up to create their account’ is enabled. To check whether this is enabled go to COG > User Management > User Signup Options. The affected versions are before version 6.13.23, from version 6.14.0 before 7.4.11, from version 7.5.0 before 7.11.6, and from version 7.12.0 before 7.12.5.| 
| 20210901T12:51:04Z | CVE-2021-26084 | 批量检测 | https://github.com/tangxiaofeng7/CVE-2021-26084 | | 
| 20210901T12:29:57Z | CVE-2021-26084 | CVE-2021-26084 Remote Code Execution on Confluence Servers | https://github.com/Osyanina/westone-CVE-2021-26084-scanner | In affected versions of Confluence Server and Data Center, an OGNL injection vulnerability exists that would allow an authenticated user, and in some instances an unauthenticated user, to execute arbitrary code on a Confluence Server or Data Center instance. The vulnerable endpoints can be accessed by a non-administrator user or unauthenticated user if ‘Allow people to sign up to create their account’ is enabled. To check whether this is enabled go to COG > User Management > User Signup Options. The affected versions are before version 6.13.23, from version 6.14.0 before 7.4.11, from version 7.5.0 before 7.11.6, and from version 7.12.0 before 7.12.5.| 
| 20210901T11:41:38Z | CVE-2021-26084 | CVE-2021-26084 - Confluence Pre-Auth RCE  OGNL injection 回显 | https://github.com/r0ckysec/CVE-2021-26084_Confluence | In affected versions of Confluence Server and Data Center, an OGNL injection vulnerability exists that would allow an authenticated user, and in some instances an unauthenticated user, to execute arbitrary code on a Confluence Server or Data Center instance. The vulnerable endpoints can be accessed by a non-administrator user or unauthenticated user if ‘Allow people to sign up to create their account’ is enabled. To check whether this is enabled go to COG > User Management > User Signup Options. The affected versions are before version 6.13.23, from version 6.14.0 before 7.4.11, from version 7.5.0 before 7.11.6, and from version 7.12.0 before 7.12.5.| 
| 20210901T10:57:25Z | CVE-2021-26084 | Null | https://github.com/alt3kx/CVE-2021-26084_PoC | In affected versions of Confluence Server and Data Center, an OGNL injection vulnerability exists that would allow an authenticated user, and in some instances an unauthenticated user, to execute arbitrary code on a Confluence Server or Data Center instance. The vulnerable endpoints can be accessed by a non-administrator user or unauthenticated user if ‘Allow people to sign up to create their account’ is enabled. To check whether this is enabled go to COG > User Management > User Signup Options. The affected versions are before version 6.13.23, from version 6.14.0 before 7.4.11, from version 7.5.0 before 7.11.6, and from version 7.12.0 before 7.12.5.| 
| 20210901T10:53:31Z | CVE-2021-26084 | Null | https://github.com/dinhbaouit/CVE-2021-26084 | | 
| 20210901T10:39:16Z | CVE-2021-26084 | CVE-2021-26084 Remote Code Execution on Confluence Servers | https://github.com/FanqXu/CVE-2021-26084 | In affected versions of Confluence Server and Data Center, an OGNL injection vulnerability exists that would allow an authenticated user, and in some instances an unauthenticated user, to execute arbitrary code on a Confluence Server or Data Center instance. The vulnerable endpoints can be accessed by a non-administrator user or unauthenticated user if ‘Allow people to sign up to create their account’ is enabled. To check whether this is enabled go to COG > User Management > User Signup Options. The affected versions are before version 6.13.23, from version 6.14.0 before 7.4.11, from version 7.5.0 before 7.11.6, and from version 7.12.0 before 7.12.5.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210901T09:41:25Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2696 | 68| 
| 20210901T08:58:11Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 173 | 19| 
| 20210901T01:26:04Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 12 | 1| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210901T13:17:09Z | Null | https://github.com/RAYTRAClNG/Exploits | 0 | 0| 
| 20210901T13:16:06Z | Exploit for Elastix 2.2.0 and FreePBX 2.10.0 based on CVE-2012-4869 vulnerability working on Python3 | https://github.com/bitc0de/Elastix-Remote-Code-Execution | 0 | 0| 
| 20210901T13:03:08Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 29 | 15| 
| 20210901T12:52:32Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 22 | 14| 
| 20210901T12:39:31Z | Replication materials for the paper %Understanding Managers% Trade-offs between Exploration and Exploitation%, forthcoming in Marketing Science | https://github.com/alinafere/managerial_exploration_exploitation_tradeoffs | 0 | 0| 
| 20210901T12:35:59Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9963 | 1667| 
| 20210901T12:21:13Z | Um exploit escrito para o site da minha antiga escola :) | https://github.com/kn1pnc/etelg-ph | 0 | 0| 
| 20210901T12:15:17Z | Null | https://github.com/deadlyappache55/King-Exploits | 0 | 1| 
| 20210901T12:13:13Z | Null | https://github.com/ARO7I/exploit.py | 0 | 0| 
| 20210901T12:05:49Z | Practice repository for binary exploitation and fuzzing | https://github.com/RickdeJager/binexp-practice | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210901T11:50:49Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 300 | 56| 
| 20210901T10:28:12Z | A Hidden and Undetectable Remote Access Tool written in C++ and Server in Python3 | https://github.com/Ryan-AW/Windows-Backdoor | 17 | 4| 
| 20210901T07:14:39Z | A Simple Ruby Websocket Backdoor And Ruby Command Line Listener | https://github.com/krishpranav/browserexploit | 1 | 1| 
| 20210901T05:33:52Z | This is an advanced backdoor, created with Python | https://github.com/NoamHarush/Backdoor | 1 | 1| 
| 20210901T05:32:01Z | Just a simple test using modules to make an apache2 backdoor | https://github.com/impugnus/simple_apache2_backdoor | 1 | 1| 
| 20210901T05:00:06Z | Null | https://github.com/mohdhumaid/BackdoorPython27 | 0 | 0| 
| 20210901T04:01:29Z | DDoor - cross platform backdoor using dns txt records | https://github.com/rek7/ddoor | 173 | 50| 
| 20210901T02:14:15Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 95 | 16| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210901T09:10:26Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 157 | 34| 
| 20210901T06:41:32Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2441 | 362| 
| 20210901T05:29:01Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1881 | 390| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210901T13:20:58Z | Classic robust fuzzy rough set models（经典的鲁棒模糊粗糙集模型） | https://github.com/BigYellowTiger/Robust_Fuzzy_rough_set | 0 | 0| 
| 20210901T13:14:36Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6596 | 1351| 
| 20210901T13:10:56Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210901T13:08:09Z | Null | https://github.com/mongoloidkhulmikuki366385/fuzzy-waddle | 0 | 0| 
| 20210901T12:52:25Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210901T12:36:05Z | Enhancing Smart Contract Fuzzing with Static and Dynamic Analyses | https://github.com/SoftSec-KAIST/Smartian | 0 | 0| 
| 20210901T12:35:20Z | Color-based superpixel algorithm for image segmentation. | https://github.com/abdelrahman-0/Fuzzy-Simple-Linear-Iterative-Clustering | 0 | 0| 
| 20210901T12:12:36Z | Project description and methodology outlined | https://github.com/devarshee97/Vector-Fuzzy-Dark-matter | 0 | 0| 
| 20210901T12:05:49Z | Practice repository for binary exploitation and fuzzing | https://github.com/RickdeJager/binexp-practice | 0 | 0| 
| 20210901T11:46:11Z | fuzz payload(持续更新) | https://github.com/kill02lc/fuzz-then-bypass-dict | 0 | 0| 



# 日更新程序
