# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210723 | 存在于浏览器缓存中的 “The Master and Parasite Attack” （Paper） | https://arxiv.org/abs/2107.06415| 
| 20210723 | CVE-2021-30551: Chrome Type Confusion in V8 | https://googleprojectzero.github.io/0days-in-the-wild/0day-RCAs/2021/CVE-2021-30551.html| 
| 20210723 | Kunlun-Mirror - 源代码安全审计工具，支持检测多种开发语言的漏洞 | https://github.com/LoRexxar/Kunlun-M| 
| 20210723 | 用于检测 Kubernetes Clusters 安全问题的工具 | https://github.com/aquasecurity/kube-hunter| 
| 20210723 | Akamai DNS 故障，影响 PlayStation、AWS、Google 等多家企业的服务 | https://www.bleepingcomputer.com/news/security/akamai-dns-global-outage-takes-down-major-websites-online-services/| 
| 20210723 | GitHub 上多家用户企业的 Repo 被发现存在 “Dependency Confusion Attacks” 问题 | https://redhuntlabs.com/blog/top-organizations-on-github-vulnerable-to-dependency-confusion-attack.html| 
| 20210723 | SIM 卡编程 | https://radioactive.blog/2021/07/22/sim_program_with_adm_key/| 
| 20210723 | 腾讯安全科恩实验室发布的“以人造扰动欺骗车道线检测系统” 的 Paper | https://keenlab.tencent.com/zh/whitepapers/Tricking-Lane-Detection-pre-publication.pdf| 
| 20210723 | Windows 恶意 NetFilter 驱动的检测 | https://research.nccgroup.com/2021/07/16/detecting-and-hunting-for-the-malicious-netfilter-driver/| 
| 20210722 | New Attacks on Kubernetes via Misconfigured Argo Workflows | https://www.intezer.com/blog/container-security/new-attacks-on-kubernetes-via-misconfigured-argo-workflows/| 
| 20210722 | NPM 市场的 “nodejs_net_server” 软件包被发现窃取用户数据 | https://www.tensorbugs.in/2021/07/npm-package-nodejsnetserver-caught.html| 
| 20210722 | libPeConv - 用于加载、修改、Dump PE 文件的工具库 | https://github.com/hasherezade/libpeconv| 
| 20210722 | 2021 Pwn2Own Chromium 浏览器 CVE-2021-21220 RCE 漏洞的细节公开了 | https://bugs.chromium.org/p/chromium/issues/detail?id=1196683| 
| 20210722 | Apple 发布 iOS 14.7 版本漏洞公告 | https://support.apple.com/zh-cn/HT212601| 
| 20210722 | iOS RE 4 beginners 2 - 静态链接&&动态链接 | https://o0xmuhe.github.io/2021/07/14/iOS-RE-4-beginners-2/| 
| 20210722 | Attacking the DevTools | https://microsoftedge.github.io/edgevr/posts/attacking-the-devtools/| 
| 20210722 | Fuzzing Modern UDP Game Protocols With Snapshot-based Fuzzers | http://blog.ret2.io/2021/07/21/wtf-snapshot-fuzzing/| 
| 20210722 | Windows 用于实现云存储的驱动 cldflt.sys 被发现整数下溢漏洞（CVE-2021-31969） | https://www.thezdi.com/blog/2021/7/19/cve-2021-31969-underflowing-in-the-clouds| 
| 20210722 | 知名恶意软件 Formbook 最近新增对 macOS 平台的支持 | https://sec.today/pulses/75405d62-c257-4e2c-b4d7-bcae6ea20955/| 
| 20210722 | 知名恶意软件 Formbook 最近新增对 macOS 平台的支持 | https://research.checkpoint.com/2021/top-prevalent-malware-with-a-thousand-campaigns-migrates-to-macos/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210723 | 记一次促销活动中的业务安全对抗 | https://mp.weixin.qq.com/s/wX8Yo4YGTudRyft32HEeug| 
| 20210722 | 对“超高能力网空威胁行为体”系列分析回顾 | https://mp.weixin.qq.com/s/RGIfplSiDK8_AQekn-nImA| 
| 20210721 | 基于用户态虚拟化的物联网设备仿真方法 | https://blog.lyle.ac.cn/2021/07/09/uemu/| 
| 20210721 | 浅谈云安全之K8S | https://www.anquanke.com/post/id/245526| 
| 20210721 | 应急响应的神兵利器 | https://www.anquanke.com/post/id/246290| 
| 20210721 | NGLite-基于区块链网络的匿名跨平台远控程序 | https://www.anquanke.com/post/id/247454| 
| 20210721 | 利用pocsuite3框架编写poc实战案例 | https://mp.weixin.qq.com/s/LN5gJnKpunfWGJ6yQQtHuw| 
| 20210721 | 某工控设备固件提取及分析 | http://blog.nsfocus.net/vxwork-qnx/| 
| 20210721 | 攻防启示：Chromium组件风险剖析与收敛 | https://mp.weixin.qq.com/s/f0aFLEKyABpYDobPN2b6tQ| 
| 20210721 | [翻译] 通过不安全的动态加载获得获得反射 XSS | https://mp.weixin.qq.com/s/MyC527oZVqT1ZDjlUZ_gYw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210723T23:23:28Z | CVE-2020-0022 | This is a RCE bluetooth vulnerability on Android 8.0 and 9.0 | https://github.com/k3vinlusec/Bluefrag_CVE-2020-0022 | In reassemble_and_dispatch of packet_fragmenter.cc, there is possible out of bounds write due to an incorrect bounds calculation. This could lead to remote code execution over Bluetooth with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-8.0 Android-8.1 Android-9 Android-10Android ID: A-143894715| 
| 20210723T23:20:13Z | CVE-2020-15416 | https://www.zerodayinitiative.com/advisories/ZDI-20-712/ | https://github.com/k3vinlusec/R7000_httpd_BOF_CVE-2020-15416 | This vulnerability allows network-adjacent attackers to bypass authentication on affected installations of NETGEAR R6700 V1.0.4.84_10.0.58 routers. Authentication is not required to exploit this vulnerability. The specific flaw exists within the httpd service, which listens on TCP port 80 by default. The issue results from the lack of proper validation of the length of user-supplied data prior to copying it to a fixed-length, stack-based buffer. An attacker can leverage this vulnerability to execute code in the context of root. Was ZDI-CAN-9703.| 
| 20210723T22:42:08Z | CVE-2021-33909 | Sequoia exploit (7/20/21) | https://github.com/Liang2580/CVE-2021-33909 | fs/seq_file.c in the Linux kernel 3.16 through 5.13.x before 5.13.4 does not properly restrict seq buffer allocations, leading to an integer overflow, an Out-of-bounds Write, and escalation to root by an unprivileged user, aka CID-8cae8cd89f05.| 
| 20210723T19:14:21Z | CVE-2021-36934 | CVE-2021-36934 PowerShell scripts | https://github.com/bytesizedalex/CVE-2021-36934 | | 
| 20210723T17:19:17Z | CVE-2021-36934 | Windows Elevation of Privilege Vulnerability (SeriousSAM) | https://github.com/VertigoRay/CVE-2021-36934 | Windows Elevation of Privilege Vulnerability| 
| 20210723T15:46:41Z | CVE-2021-3156 | Sudo Baron Samedit Exploit | https://github.com/worawit/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210723T14:54:01Z | CVE-2020-14343 | Experimenting with the CVE-2020-14343 PyYAML vulnerability | https://github.com/raul23/pyyaml-CVE-2020-14343 | A vulnerability was discovered in the PyYAML library in versions before 5.4, where it is susceptible to arbitrary code execution when it processes untrusted YAML files through the full_load method or with the FullLoader loader. Applications that use the library to process untrusted input may be vulnerable to this flaw. This flaw allows an attacker to execute arbitrary code on the system by abusing the python/object/new constructor. This flaw is due to an incomplete fix for CVE-2020-1747.| 
| 20210723T12:44:28Z | CVE-2021-1675 | C# and Impacket implementation of PrintNightmare CVE-2021-1675/CVE-2021-34527 | https://github.com/cube0x0/CVE-2021-1675 | | 
| 20210723T12:23:45Z | CVE-2020-23934 | Python Implementation of CVE-2020-23934 | https://github.com/zyeinn/CVE-2020-23934 | An issue was discovered in RiteCMS 2.2.1. An authenticated user can directly execute system commands by uploading a php web shell in the %Filemanager% section.| 
| 20210723T12:19:19Z | CVE-2021-36934 | Fix for the CVE-2021-36934 | https://github.com/JoranSlingerland/CVE-2021-36934 | Windows Elevation of Privilege Vulnerability| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210724T00:53:58Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2253 | 52| 
| 20210723T19:09:11Z | Null | https://github.com/JaimePSantos/ResearchKlee | 0 | 0| 
| 20210723T16:55:51Z | Whole Program LLVM: wllvm ported to go | https://github.com/SRI-CSL/gllvm | 143 | 21| 
| 20210723T09:19:08Z | Config files for my GitHub profile. | https://github.com/Kleem405/Kleem405 | 0 | 0| 
| 20210722T21:48:12Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 165 | 15| 
| 20210722T12:59:38Z | Projet SensioTv de formation Symfony 5 Klee Interactive, stack en Docksal et WSL2 windows | https://github.com/404Panky/formation-sf5 | 0 | 1| 
| 20210721T15:54:50Z | Personal portfolio website built with React | https://github.com/collinkleest/kleest.io | 0 | 0| 
| 20210721T10:43:16Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210721T10:25:30Z | Report PPT template for CS students  | https://github.com/Fishermanykx/paper_reading_report_template | 1 | 0| 
| 20210721T10:12:29Z | Null | https://github.com/xenoney/kleee | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210723T14:58:37Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 144 | 34| 
| 20210723T02:37:08Z | Config files for my GitHub profile. | https://github.com/s2ensei/s2ensei | 0 | 0| 
| 20210722T10:37:33Z | Null | https://github.com/Feddouuu/s2e_federico | 0 | 0| 
| 20210722T09:13:59Z | Null | https://github.com/Djeufo/22GithubTestProject_S2E | 0 | 0| 
| 20210722T09:13:59Z | Null | https://github.com/Chanel-B/22GithubTestProject_S2E | 0 | 0| 
| 20210721T14:56:09Z | Automatic Exploit Generation (AEG) tool based on S2E 2.X | https://github.com/aesophor/baphomet | 3 | 0| 
| 20210716T08:48:51Z | Season 2, Episode 1 - In this episode we look at how to correctly host your HTML files, and reverse proxy the ws/ (Websocket) connections back to the Asterisk Service. It%s all done on a single local instance so we are using a self signed certificate. | https://github.com/InnovateAsterisk/S2E1 | 0 | 0| 
| 20210714T02:13:53Z | GUI Configuration tool for WIZnet serial to ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool-GUI | 13 | 8| 
| 20210713T19:49:07Z | Null | https://github.com/yuvalkirstain/s2e-coref | 9 | 4| 
| 20210703T18:52:28Z | Null | https://github.com/hichem840/s2ee | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210724T00:53:16Z | PS4 Exploit 7.55 (Add additional cleanup spray after the exploit) | https://github.com/Buzbee/Buzbee3 | 0 | 0| 
| 20210724T00:52:02Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 17 | 12| 
| 20210724T00:06:06Z | Null | https://github.com/jwardsmith/Active-Directory-Exploitation | 1 | 0| 
| 20210724T00:03:15Z | Null | https://github.com/HarrysExploit/Harrys-exploit-api-v2 | 0 | 0| 
| 20210724T00:03:15Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 28 | 14| 
| 20210723T23:23:47Z | An automated, modular cryptanalysis tool; i.e., a Weapon of Math Destruction | https://github.com/nccgroup/featherduster | 897 | 129| 
| 20210723T23:20:49Z | Exploit Analysis of The WhatsApp Double-Free Vulnerability (CVE-2019-11932) Using the GEF-GDB Debugger | https://github.com/k3vinlusec/WhatsApp-Double-Free-Vulnerability_CVE-2019-11932 | 0 | 0| 
| 20210723T23:11:51Z | Null | https://github.com/dfclin073/exploits | 0 | 0| 
| 20210723T22:48:39Z | Meu exploit automatizado(recebe uma wordlist) faz o check se o host é vulneravel e exploita, codado em php para apache nifi | https://github.com/KnC0x00/ExploitApacheNIFI | 1 | 0| 
| 20210723T22:35:17Z | Binary exploits presented in web app | https://github.com/Pen-Test3rs/binary_exploits_examples | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210723T23:39:04Z | :rocket: Simple Backdoor writted in  Python  | https://github.com/anonik9900/BackFucker | 0 | 0| 
| 20210723T21:16:35Z | You have a Front Door, a Backdoor, why not a SideD00r... | https://github.com/Aaron-Akhtar/SideD00r | 0 | 0| 
| 20210723T20:23:58Z | This is a reverse shell coded in Python, similar to my C backdoor, but doesn%t allow for persistence and just allows command prompt commands. | https://github.com/Calastrophe/Reverse-Shell | 0 | 0| 
| 20210723T19:14:06Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 88 | 15| 
| 20210723T18:18:49Z | A module-based repository for testing and evaluating backdoor attacks and defenses. | https://github.com/SewoongLab/backdoor-suite | 1 | 0| 
| 20210723T18:01:40Z | Implementation of a native-code HatSploit membrane for unix-like systems, designed for portability, embeddability, and low resource utilization. | https://github.com/EntySec/membrane | 6 | 3| 
| 20210723T18:01:24Z | Paranoid is a web interface and dashboard, configured for managing HatSploit sessions via built-in REST API. | https://github.com/EntySec/Paranoid | 2 | 0| 
| 20210723T17:58:52Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/Ghost | 1222 | 580| 
| 20210723T17:07:44Z | Null | https://github.com/FierzaEriez/Mini-Shell-Backdoor | 1 | 1| 
| 20210723T14:59:39Z | [ENG] A small exploit-library using the HIkvision-backdoor exploit. [DE] Kleine Python-Scripte, um die Backdoor in Hikvision-Kameras auszunutzen. | https://github.com/MatrixEditor/hikvision-sdk-cam | 1 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210723T21:08:20Z | A tool for generating nonlinear numerical invariants for C and Java programs.  DIG uses dynamic analysis to infer invariants over program execution traces and applies symbolic execution to inferred invariants. | https://github.com/unsat/dig | 4 | 4| 
| 20210723T19:58:26Z | A symbolic execution engine for LLVM IR | https://github.com/insufficiently-caffeinated/caffeine | 7 | 4| 
| 20210723T12:57:08Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 152 | 33| 
| 20210723T07:55:55Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 444 | 67| 
| 20210722T21:06:01Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1849 | 388| 
| 20210722T15:23:36Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 14 | 3| 
| 20210722T14:53:43Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2393 | 352| 
| 20210722T12:52:30Z | A toy symbolic execution engine, supporting the blog article ... | https://github.com/synacktiv/toy-wasm-symbexp | 0 | 0| 
| 20210722T11:20:12Z | Monster is a symbolic execution engine for 64-bit RISC-U code | https://github.com/cksystemsgroup/monster | 6 | 3| 
| 20210722T06:31:27Z | symbolic execution plugin for binary ninja | https://github.com/borzacchiello/seninja | 91 | 6| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210723T14:58:47Z | Original implementation of FlowPrint as in the NDSS %20 paper | https://github.com/Thijsvanede/FlowPrint | 51 | 18| 
| 20210723T14:58:42Z | Code for the paper %FlowLens: Enabling Efficient Flow Classification for ML-based Network Security Applications% [NDSS %21] | https://github.com/dmbb/FlowLens | 6 | 1| 
| 20210714T18:32:46Z | A penetration testing tool for finding file upload bugs (NDSS 2020) | https://github.com/WSP-LAB/FUSE | 158 | 37| 
| 20210707T02:42:39Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 17 | 2| 
| 20210701T12:57:09Z | Easier Way For Get PDF Of Papers On NDSS Website | https://github.com/tbbatbb/NDSS_Downloader | 0 | 0| 
| 20210701T11:50:34Z | Auxiliary material for NDSS%20 paper: On Using Application-Layer Middlebox Protocols for Peeking Behind NAT Gateways | https://github.com/RUB-SysSec/MiddleboxProtocolStudy | 2 | 2| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210724T00:58:18Z | Null | https://github.com/joseffaghihi/Causal-fuzzy-CEVAE | 1 | 1| 
| 20210724T00:45:45Z | Null | https://github.com/Sam-damn/Fuzzy-Clustering | 0 | 0| 
| 20210724T00:41:40Z | A small application to extract @Route annotations from PHP code and generate a Swagger / OpenAPI specification after that | https://github.com/JuKu/php-route-extractor-fuzzer | 0 | 0| 
| 20210724T00:21:24Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6505 | 1320| 
| 20210723T23:00:33Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210723T22:31:30Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210723T22:01:39Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210723T21:32:17Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 1918 | 383| 
| 20210723T21:14:18Z | Emulation based snapshot fuzzer | https://github.com/jaoeul/gingersnap | 0 | 0| 
| 20210723T20:41:39Z | Fuzz 403/401ing endpoints for bypasses | https://github.com/intrudir/403fuzzer | 181 | 22| 



# 日更新程序
