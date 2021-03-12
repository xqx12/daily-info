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
| 20210311 | 在Android11使用Scudo分配器介绍 | https://zhuanlan.zhihu.com/p/353784014| 
| 20210311 | Exchange 攻击链 CVE-2021-26855&CVE-2021-27065安全漏洞分析 | https://paper.seebug.org/1501/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210311 | 通达 OA 11.7 组合拳 RCE 利用分析 | 通达 OA 11.7 组合拳 RCE 利用分析| 
| 20210311 | Google内部开源组件的风险治理框架与工作流程窥探 | https://zhuanlan.zhihu.com/p/356415256| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210311T23:57:13Z | CVE-2020-1034 | PoC demonstrating the use of cve-2020-1034 for privilege escalation | https://github.com/yardenshafir/CVE-2020-1034 | An elevation of privilege vulnerability exists in the way that the Windows Kernel handles objects in memory, aka %Windows Kernel Elevation of Privilege Vulnerability%.| 
| 20210311T23:55:00Z | CVE-2021-26855 | Null | https://github.com/achabahe/CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210311T23:44:35Z | CVE-2021-26855 | CVE-2021-26855 SSRF Exchange Server | https://github.com/Udyz/CVE-2021-26855 | | 
| 20210311T23:10:01Z | CVE-2021-26882 | PoC | https://github.com/songjianyang/CVE-2021-26882 | Remote Access API Elevation of Privilege Vulnerability| 
| 20210311T23:05:11Z | CVE-2021-26855 | CVE-2021-26855, also known as Proxylogon, is a server-side request forgery (SSRF) vulnerability in Exchange that allows an attacker to send arbitrary HTTP requests and authenticate as the Exchange server. According to Orange Tsai, the researcher who discovered the vulnerabilities, CVE-2021-26855 allows code execution when chained with CVE-2021-27065 (see below). A successful exploit chain would allow an unauthenticated attacker to "execute arbitrary commands on Microsoft Exchange Server through only an open 443 port." More information and a disclosure timeline are available at https://proxylogon.com. | https://github.com/raheel0x01/CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210311T16:12:58Z | CVE-2020-29134 | Exploit CVE-2020-29134 - TOTVS Fluig Platform - Path Traversal | https://github.com/lucxssouza/CVE-2020-29134 | TOTVS Fluig Platform allows directory traversal via a base64 encoded in paremeter %file=../% to a volume/stream/ URI. This affects: Fluig Lake 1.7.0-210217, Fluig Lake 1.7.0-210209, Fluig Lake 1.7.0-210112, Fluig Lake 1.7.0-201222, Fluig Lake 1.7.0-201215, Fluig Lake 1.7.0-201201,Fluig Lake 1.7.0-201124, Fluig Lake 1.7.0-201117, Fluig Lake 1.7.0-201103, Fluig Lake 1.7.0-201027, Fluig Lake 1.7.0-201020, Fluig Lake 1.7.0-201013, Fluig Lake 1.7.0-201006, Fluig Lake 1.7.0-200915, Fluig Lake 1.7.0-200907, Fluig Lake 1.7.0-200901, Fluig Lake 1.7.0-200825, Fluig Lake 1.7.0-200818, Fluig Lake 1.7.0-200804, Fluig Lake 1.7.0-200616), Fluig 1.6.5-200915, Fluig 1.6.5-200128, Fluig 1.6.5-191029, and Fluig 1.6.4-181026.| 
| 20210311T11:57:24Z | CVE-2021-26855 | Null | https://github.com/h4x0r-dz/CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210311T10:02:11Z | 未知编号 | Null | https://github.com/shacojx/CVE_2021_26855_Exploit_Hub | 未查询到CVE信息| 
| 20210311T10:01:59Z | CVE-2021-21300 | Null | https://github.com/Kirill89/CVE-2021-21300 | Git is an open-source distributed revision control system. In affected versions of Git a specially crafted repository that contains symbolic links as well as files using a clean/smudge filter such as Git LFS, may cause just-checked out script to be executed while cloning onto a case-insensitive file system such as NTFS, HFS+ or APFS (i.e. the default file systems on Windows and macOS). Note that clean/smudge filters have to be configured for that. Git for Windows configures Git LFS by default, and is therefore vulnerable. The problem has been patched in the versions published on Tuesday, March 9th, 2021. As a workaound, if symbolic link support is disabled in Git (e.g. via `git config --global core.symlinks false`), the described attack won%t work. Likewise, if no clean/smudge filters such as Git LFS are configured globally (i.e. _before_ cloning), the attack is foiled. As always, it is best to avoid cloning repositories from untrusted sources. The earliest impacted version is 2.14.2. The fix versions are: 2.30.1, 2.29.3, 2.28.1, 2.27.1, 2.26.3, 2.25.5, 2.24.4, 2.23.4, 2.22.5, 2.21.4, 2.20.5, 2.19.6, 2.18.5, 2.17.62.17.6.| 
| 20210311T09:23:35Z | CVE-2021-21972 | CVE-2021-21972 Exploit | https://github.com/NS-Sp4ce/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210311T19:44:10Z | Kleene algebra, regular expressions | https://github.com/phadej/kleene | 27 | 1| 
| 20210311T18:28:05Z | The Kleenex programming language | https://github.com/diku-kmc/kleenexlang | 46 | 4| 
| 20210311T17:06:26Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 109 | 8| 
| 20210311T16:40:04Z | Spring 2021 Geography 817 work folder  | https://github.com/klee12/klee12.github.io | 0 | 0| 
| 20210311T11:25:22Z | Null | https://github.com/dhanyavittaldas/kleen-tidy-master | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210311T19:51:08Z | Source of Sonic Eclipse, a romhack of Sonic 2 for Sega Master System circa 2018. http://sonicresearch.org/community/index.php?threads/sonic-eclipse.5524/ | https://github.com/mrcat-pixel/s2eclipse | 2 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210311T23:50:30Z | Fix exploits on anarchy minecraft servers | https://github.com/moom0o/AnarchyExploitFixes | 15 | 7| 
| 20210311T23:28:09Z | A quick and dirty express app with exploits used for demonstration purposes. | https://github.com/TacticalLimit/exploitable | 0 | 0| 
| 20210311T23:05:11Z | CVE-2021-26855, also known as Proxylogon, is a server-side request forgery (SSRF) vulnerability in Exchange that allows an attacker to send arbitrary HTTP requests and authenticate as the Exchange server. According to Orange Tsai, the researcher who discovered the vulnerabilities, CVE-2021-26855 allows code execution when chained with CVE-2021-27065 (see below). A successful exploit chain would allow an unauthenticated attacker to %execute arbitrary commands on Microsoft Exchange Server through only an open 443 port.% More information and a disclosure timeline are available at https://proxylogon.com. | https://github.com/raheel0x01/CVE-2021-26855 | 1 | 0| 
| 20210311T22:40:44Z | Null | https://github.com/0xturazzi/Um-Livrinho-Sobre-Exploit-Dev | 0 | 0| 
| 20210311T22:39:05Z | Simple ROBLOX exploit. | https://github.com/DjWolffe/DJWSploit | 0 | 0| 
| 20210311T22:00:59Z | Null | https://github.com/SL-Exploit/exploit | 0 | 0| 
| 20210311T21:30:37Z | SockStress DoS (Denial of Service) exploit written in Python3 (Source: pan0pt1c0n/Python-SockStress) | https://github.com/meirmichaeli/Python-SockStress | 0 | 0| 
| 20210311T21:23:57Z | Sécurité des logiciels et exploitation de vulnérabilités | https://github.com/ppepos/inf600c | 4 | 1| 
| 20210311T21:12:57Z | Basic services enumeration and exploitation | https://github.com/dar3k93/Basic-service-enumeration | 0 | 1| 
| 20210311T20:54:01Z | exploits for vm phoenix of exploit education https://exploit.education/phoenix/ | https://github.com/gu1mas/exploit-education_writeups | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210311T22:04:08Z | Backdoor | https://github.com/kadzicuh/Backdoor | 0 | 1| 
| 20210311T19:41:45Z | A general-purpose All-in-One backdoor for ethical hacking. Made with utility in mind. | https://github.com/CMPLXapps/Swordfish | 0 | 0| 
| 20210311T19:01:07Z | C# Backdoor & Mapper/Proxy tool (backdoor & proxy tool working in memory only) | https://github.com/DamonMohammadbagher/NativePayload_MP | 1 | 0| 
| 20210311T17:59:51Z | Extension of my previous backdoor | https://github.com/BecomeTheVoid/server-for-backdoor | 0 | 0| 
| 20210311T17:57:26Z | My first homemade backdoor for win10 | https://github.com/BecomeTheVoid/windows-backdoor | 0 | 0| 
| 20210311T17:54:00Z | Null | https://github.com/ph-luffy/Backdoor | 1 | 1| 
| 20210311T15:33:35Z | kumpulan shell backdoor | https://github.com/FRMFOX/SH3LL-BKDR | 0 | 0| 
| 20210311T15:24:32Z | A backdoor/RAT code created in python and php that allows full control over a linux based device..... (Including webcam) | https://github.com/rpd-512/backJack | 0 | 0| 
| 20210311T13:59:31Z | Null | https://github.com/Delle9999/backdoor | 0 | 0| 
| 20210311T12:02:01Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 179 | 33| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210311T23:48:26Z | This repository is for testing a number of open source applications for vulnerabilities using multiple fuzzers. | https://github.com/bartholomewHarris/fuzzingNode.jsApplications | 0 | 0| 
| 20210311T23:02:02Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 259 | 36| 
| 20210311T22:53:28Z | Null | https://github.com/cbawebdesign/fuzzy-winner | 0 | 0| 
| 20210311T22:48:36Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 0| 
| 20210311T22:47:02Z | CS 4152 Project | https://github.com/nicbarone/Fuzzy-Kiwi | 0 | 0| 
| 20210311T22:39:30Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 11 | 1| 
| 20210311T22:26:49Z | 💹 Projeto para Fuzzy Trader desenvolvido em ReactJS | https://github.com/hugo-marcelo/fuzzy-trader-web | 0 | 0| 
| 20210311T20:34:57Z | Seminarski rad iz predmeta Računarska Inteligencija na Matematičkom fakultetu. | https://github.com/djanluka/FuzzyClassification | 0 | 0| 
| 20210311T20:26:49Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3403 | 782| 
| 20210311T19:48:50Z | Null | https://github.com/DarkShinobi100/BehaviourTreesvsFuzzy | 0 | 0| 



# 日更新程序
