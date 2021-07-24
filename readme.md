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


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210723 | 记一次促销活动中的业务安全对抗 | https://mp.weixin.qq.com/s/wX8Yo4YGTudRyft32HEeug| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210723T23:23:28Z | CVE-2020-0022 | This is a RCE bluetooth vulnerability on Android 8.0 and 9.0 | https://github.com/k3vinlusec/Bluefrag_CVE-2020-0022 | In reassemble_and_dispatch of packet_fragmenter.cc, there is possible out of bounds write due to an incorrect bounds calculation. This could lead to remote code execution over Bluetooth with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-8.0 Android-8.1 Android-9 Android-10Android ID: A-143894715| 
| 20210723T23:20:13Z | CVE-2020-15416 | https://www.zerodayinitiative.com/advisories/ZDI-20-712/ | https://github.com/k3vinlusec/R7000_httpd_BOF_CVE-2020-15416 | This vulnerability allows network-adjacent attackers to bypass authentication on affected installations of NETGEAR R6700 V1.0.4.84_10.0.58 routers. Authentication is not required to exploit this vulnerability. The specific flaw exists within the httpd service, which listens on TCP port 80 by default. The issue results from the lack of proper validation of the length of user-supplied data prior to copying it to a fixed-length, stack-based buffer. An attacker can leverage this vulnerability to execute code in the context of root. Was ZDI-CAN-9703.| 
| 20210723T19:14:21Z | CVE-2021-36934 | CVE-2021-36934 PowerShell scripts | https://github.com/bytesizedalex/CVE-2021-36934 | Windows Elevation of Privilege Vulnerability| 
| 20210723T17:19:17Z | CVE-2021-36934 | Windows Elevation of Privilege Vulnerability (SeriousSAM) | https://github.com/VertigoRay/CVE-2021-36934 | Windows Elevation of Privilege Vulnerability| 
| 20210723T15:46:41Z | CVE-2021-3156 | Sudo Baron Samedit Exploit | https://github.com/worawit/CVE-2021-3156 | | 
| 20210723T14:54:01Z | CVE-2020-14343 | Experimenting with the CVE-2020-14343 PyYAML vulnerability | https://github.com/raul23/pyyaml-CVE-2020-14343 | A vulnerability was discovered in the PyYAML library in versions before 5.4, where it is susceptible to arbitrary code execution when it processes untrusted YAML files through the full_load method or with the FullLoader loader. Applications that use the library to process untrusted input may be vulnerable to this flaw. This flaw allows an attacker to execute arbitrary code on the system by abusing the python/object/new constructor. This flaw is due to an incomplete fix for CVE-2020-1747.| 
| 20210723T12:44:28Z | CVE-2021-1675 | C# and Impacket implementation of PrintNightmare CVE-2021-1675/CVE-2021-34527 | https://github.com/cube0x0/CVE-2021-1675 | | 
| 20210723T12:23:45Z | CVE-2020-23934 | Python Implementation of CVE-2020-23934 | https://github.com/zyeinn/CVE-2020-23934 | An issue was discovered in RiteCMS 2.2.1. An authenticated user can directly execute system commands by uploading a php web shell in the %Filemanager% section.| 
| 20210723T12:19:19Z | CVE-2021-36934 | Fix for the CVE-2021-36934 | https://github.com/JoranSlingerland/CVE-2021-36934 | Windows Elevation of Privilege Vulnerability| 
| 20210723T08:34:08Z | 未知编号 | Null | https://github.com/haerin7427/CVE_2020_1938 | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210723T19:09:11Z | Null | https://github.com/JaimePSantos/ResearchKlee | 0 | 0| 
| 20210723T16:55:51Z | Whole Program LLVM: wllvm ported to go | https://github.com/SRI-CSL/gllvm | 143 | 21| 
| 20210723T09:19:08Z | Config files for my GitHub profile. | https://github.com/Kleem405/Kleem405 | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210723T14:58:37Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 144 | 34| 
| 20210723T02:37:08Z | Config files for my GitHub profile. | https://github.com/s2ensei/s2ensei | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210723T23:23:47Z | An automated, modular cryptanalysis tool; i.e., a Weapon of Math Destruction | https://github.com/nccgroup/featherduster | 897 | 129| 
| 20210723T23:20:49Z | Exploit Analysis of The WhatsApp Double-Free Vulnerability (CVE-2019-11932) Using the GEF-GDB Debugger | https://github.com/k3vinlusec/WhatsApp-Double-Free-Vulnerability_CVE-2019-11932 | 0 | 0| 
| 20210723T23:11:51Z | Null | https://github.com/dfclin073/exploits | 0 | 0| 
| 20210723T22:48:39Z | Meu exploit automatizado(recebe uma wordlist) faz o check se o host é vulneravel e exploita, codado em php para apache nifi | https://github.com/KnC0x00/ExploitApacheNIFI | 1 | 0| 
| 20210723T22:35:17Z | Binary exploits presented in web app | https://github.com/Pen-Test3rs/binary_exploits_examples | 0 | 0| 
| 20210723T22:23:09Z | Dossiers: fonctionnelle, Technique, Exploitation | https://github.com/dlparisato/Dossiers-OC-Pizza | 0 | 0| 
| 20210723T22:08:43Z | Funny exploit lol | https://github.com/Kami147/InstantMine | 18 | 3| 
| 20210723T22:04:26Z | Script  for downloading post exploitation scripts/tools | https://github.com/0xastraeus/Post-exploitation-tools | 0 | 0| 
| 20210723T21:35:14Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9764 | 1610| 
| 20210723T21:17:35Z | Null | https://github.com/MazX0p/FireBase-Finder-Exploit | 1 | 0| 


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


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210723T14:58:47Z | Original implementation of FlowPrint as in the NDSS %20 paper | https://github.com/Thijsvanede/FlowPrint | 51 | 18| 
| 20210723T14:58:42Z | Code for the paper %FlowLens: Enabling Efficient Flow Classification for ML-based Network Security Applications% [NDSS %21] | https://github.com/dmbb/FlowLens | 6 | 1| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210723T23:00:33Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210723T22:31:30Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210723T21:32:17Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 1918 | 383| 
| 20210723T21:14:18Z | Emulation based snapshot fuzzer | https://github.com/jaoeul/gingersnap | 0 | 0| 
| 20210723T20:41:39Z | Fuzz 403/401ing endpoints for bypasses | https://github.com/intrudir/403fuzzer | 181 | 22| 
| 20210723T20:30:29Z | REST API Fuzz Testing (RAFT): Source code for self-hosted service developed for Azure, including the API, orchestration engine, and default set of security tools (including MSR%s RESTler), that enables developers to embed security tooling into their CI/CD workflows | https://github.com/microsoft/rest-api-fuzz-testing | 185 | 27| 
| 20210723T20:27:59Z | Fuzzing C-Compilers with QuickCheck | https://github.com/m-schmidt/Fuzzer | 5 | 0| 
| 20210723T20:24:55Z | Null | https://github.com/Healer-fuzz/healer-fuzz | 0 | 0| 
| 20210723T20:06:00Z | Practice repository for binary exploitation and fuzzing | https://github.com/RickdeJager/binexp-practice | 0 | 0| 
| 20210723T19:17:28Z | A Rust toolkit to combine property-based testing and fuzzing. | https://github.com/facebookincubator/propfuzz | 106 | 2| 



# 日更新程序
