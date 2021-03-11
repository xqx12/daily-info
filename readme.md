# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210311 | 自己搭建一个渗透测试 Red & Blue Team Homelab | https://hausec.com/2021/03/04/creating-a-red-blue-team-home-lab/| 
| 20210311 | HackerOne 发布《The 2021 Hacker Report》 | https://www.hackerone.com/resources/reporting/the-2021-hacker-report| 
| 20210311 | git 发布发版本更新，修复 CVE-2021-21300 git clone 过程的代码执行漏洞 | https://www.openwall.com/lists/oss-security/2021/03/09/3| 
| 20210311 | 利用 Qualcomm msm 内核驱动的漏洞实现 Android 内核代码执行 | https://securitylab.github.com/research/one_day_short_of_a_fullchain_android/| 
| 20210311 | McAfee ATR Capture the Flag Writeup | https://github.com/advanced-threat-research/ATR_HAX_CTF| 
| 20210311 | 利用 R2Frida 和 ESILSolve 工具对移动 App 实现符号执行分析 | https://www.nowsecure.com/blog/2021/03/10/how-to-perform-symbolic-execution-of-mobile-apps-with-r2frida-esilsolve/| 
| 20210311 | Issue 2126: F5 Big IP - TMM uri_normalize_host infoleak and out-of-bounds write | https://bugs.chromium.org/p/project-zero/issues/detail?id=2126| 
| 20210311 | Issue 2132: F5 Big IP - ASM stack-based buffer overflow in is_hdr_criteria_matches | https://bugs.chromium.org/p/project-zero/issues/detail?id=2132| 
| 20210311 | Profiling C++ code with Frida | https://lief.quarkslab.com/blog/2021-03-10-profiling-cpp-code-with-frida/| 
| 20210311 | 搭建环境，通过版本对比重现 Microsoft Exchange Proxylogon 漏洞 | https://sec.today/pulses/d27e11fb-9f97-4ffa-982c-a26708d72b94/| 
| 20210311 | 搭建环境，通过版本对比重现 Microsoft Exchange Proxylogon 漏洞 | https://www.praetorian.com/blog/reproducing-proxylogon-exploit/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210311 | 通达 OA 11.7 组合拳 RCE 利用分析 | 通达 OA 11.7 组合拳 RCE 利用分析| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210311T13:48:41Z | CVE-2021-26882 | PoC | https://github.com/songjianyang/CVE-2021-26882 | 未查询到CVE信息| 
| 20210311T13:42:11Z | CVE-2021-26855 | CVE-2021-26855 SSRF Exchange Server | https://github.com/Udyz/CVE-2021-26855 | | 
| 20210311T11:57:24Z | CVE-2021-26855 | Null | https://github.com/h4x0r-dz/CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210311T10:02:11Z | 未知编号 | Null | https://github.com/shacojx/CVE_2021_26855_Exploit_Hub | 未查询到CVE信息| 
| 20210311T10:01:59Z | CVE-2021-21300 | Null | https://github.com/Kirill89/CVE-2021-21300 | Git is an open-source distributed revision control system. In affected versions of Git a specially crafted repository that contains symbolic links as well as files using a clean/smudge filter such as Git LFS, may cause just-checked out script to be executed while cloning onto a case-insensitive file system such as NTFS, HFS+ or APFS (i.e. the default file systems on Windows and macOS). Note that clean/smudge filters have to be configured for that. Git for Windows configures Git LFS by default, and is therefore vulnerable. The problem has been patched in the versions published on Tuesday, March 9th, 2021. As a workaound, if symbolic link support is disabled in Git (e.g. via `git config --global core.symlinks false`), the described attack won%t work. Likewise, if no clean/smudge filters such as Git LFS are configured globally (i.e. _before_ cloning), the attack is foiled. As always, it is best to avoid cloning repositories from untrusted sources. The earliest impacted version is 2.14.2. The fix versions are: 2.30.1, 2.29.3, 2.28.1, 2.27.1, 2.26.3, 2.25.5, 2.24.4, 2.23.4, 2.22.5, 2.21.4, 2.20.5, 2.19.6, 2.18.5, 2.17.62.17.6.| 
| 20210311T09:23:35Z | CVE-2021-21972 | CVE-2021-21972 Exploit | https://github.com/NS-Sp4ce/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210311T08:25:51Z | CVE-2021-26855 | PoC for CVE-2021-26855 -Just a checker- | https://github.com/0xAbdullah/CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210311T08:21:06Z | cve-2021-21972 | Null | https://github.com/d3sh1n/cve-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210311T08:14:32Z | CVE-2021-3019 | [CVE-2021-3019] LanProxy Directory Traversal | https://github.com/murataydemir/CVE-2021-3019 | ffay lanproxy 0.1 allows Directory Traversal to read /../conf/config.properties to obtain credentials for a connection to the intranet.| 
| 20210311T06:42:01Z | CVE-2021-26855 | Null | https://github.com/alt3kx/CVE-2021-26855_PoC | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210311T11:31:53Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 109 | 7| 
| 20210311T11:25:22Z | Null | https://github.com/dhanyavittaldas/kleen-tidy-master | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210311T13:53:20Z | Apache ActiveMQ Remote Code Execution Exploit | https://github.com/cyberaguiar/CVE-2016-3088 | 0 | 0| 
| 20210311T13:48:56Z | bespoke tooling for offensive security%s Windows Usermode Exploit Dev course (OSED) | https://github.com/epi052/osed-scripts | 0 | 0| 
| 20210311T13:29:53Z | Null | https://github.com/SammyKrosoft/Exchange-Vulnerability-02March2021-HAFNIUM-targeting-Exchange-Servers-with-0-day-exploits | 1 | 0| 
| 20210311T13:24:50Z | Null | https://github.com/th3ken-dev/TH3KEN-EDITON | 2 | 0| 
| 20210311T13:15:41Z | Null | https://github.com/mike-hilton/binary-exploitation | 0 | 0| 
| 20210311T13:06:38Z | Null | https://github.com/faizxn/events-exploit-logs | 0 | 0| 
| 20210311T13:02:30Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 10 | 5| 
| 20210311T12:59:08Z | The project aims at building an effective regression model using regularization (i.e. advanced linear regression: Ridge and Lasso regression) in order to predict the actual value of the prospective housing properties and decide whether to invest in them or not. The goal of this project is to exploit the data insights using data analytics to purchase houses at a price below their actual values and flip them on at a higher price. | https://github.com/ChaitanyaC22/House-Price-Prediction-Project-for-a-US-based-housing-company | 0 | 0| 
| 20210311T12:39:35Z | -------> RAFEL<------  Android Rat  Written in Java With WebPanel For Controlling Victims | https://github.com/swagkarna/Rafel-Rat | 9 | 5| 
| 20210311T12:11:44Z | This repository contains the code for %Exploiting Cloze Questions for Few-Shot Text Classification and Natural Language Inference% | https://github.com/timoschick/pet | 781 | 111| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210311T12:02:01Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 179 | 33| 
| 20210311T11:42:48Z | Tool to find potential backdoor/security holes in your endpoint | https://github.com/subasgit/backdoorfinder | 3 | 0| 
| 20210311T11:23:49Z | Backdoor Open Source | https://github.com/kadzicuh/Backdoor | 0 | 1| 
| 20210311T10:52:44Z | Linux Kernel module-less implant (backdoor) | https://github.com/milabs/kopycat | 23 | 10| 
| 20210311T10:05:40Z | A Simple android remote administration tool using sockets. It uses java on the client side and python on the server side | https://github.com/karma9874/AndroRAT | 181 | 79| 
| 20210311T07:29:51Z | Another backdoor. Unlike SpiderBackdoor, my other backdoor project, Swordfish is being built with feature density and real application in mind. | https://github.com/CMPLXapps/Swordfish | 0 | 0| 
| 20210311T05:58:34Z |   Python Backdoor Daemon | https://github.com/lucie-cupcakes/pybd | 0 | 0| 
| 20210311T04:50:12Z | Null | https://github.com/nocanvas/backdoorfinance | 0 | 0| 
| 20210311T02:34:51Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 187 | 31| 
| 20210311T00:41:03Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. Ghost Framework gives you the power and convenience of remote Android device administration. | https://github.com/EntySec/ghost | 978 | 485| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210311T02:35:01Z | Null | https://github.com/FDU-Program-Analysis/chunk-fuzzer-pass | 0 | 0| 
| 20210311T02:29:03Z | Scalable fuzzing infrastructure. | https://github.com/google/clusterfuzz | 4457 | 424| 
| 20210311T02:27:19Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6030 | 1211| 
| 20210311T02:15:18Z | FuzzBench - Fuzzer benchmarking as a service. | https://github.com/google/fuzzbench | 608 | 103| 
| 20210311T01:45:03Z | Null | https://github.com/gabejw/fuzzy-guide | 0 | 0| 
| 20210311T00:11:52Z | CS 4152 Project | https://github.com/nicbarone/Fuzzy-Kiwi | 0 | 0| 
| 20210311T00:09:44Z | Null | https://github.com/mike-ada/Ada-Fuzzball-Slam-Game-Logic | 0 | 0| 



# 日更新程序
