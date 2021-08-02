# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210802 | SDR++，跨平台、开源的 SDK 分析软件 | https://github.com/AlexandreRouma/SDRPlusPlus| 
| 20210802 | BIAS: Bluetooth Impersonation AttackS | https://francozappa.github.io/about-bias/| 
| 20210802 | 打印机驱动 CVE-2021-3438 漏洞的逆向分析 | https://voidsec.com/root-cause-analysis-of-cve-2021-3438/| 
| 20210802 | Windows 10 KVAS and Software SMEP | https://wumb0.in/windows-10-kvas-and-software-smep.html| 
| 20210802 | V8 脚本引擎 Heap Sandbox 的设计文档 | https://docs.google.com/document/d/1FM4fQmIhEqPG8uGp5o9A-mnPB5BOeScZYpkHjo0KKA8/edit| 
| 20210802 | Fuzzing Windows RPC with RpcView | https://itm4n.github.io/fuzzing-windows-rpc-rpcview/| 
| 20210802 | Ninja - 一款用于渗透测试的开源的 C&C Server | https://github.com/ahmedkhlief/Ninja| 
| 20210802 | 智能电动车充电桩安全测试 | https://www.pentestpartners.com/security-blog/smart-car-chargers-plug-n-play-for-hackers/| 
| 20210801 | Portable Executable Injection Study | https://malwareunicorn.org/workshops/peinjection.html| 
| 20210801 | Pre-Auth RCE in Moodle Part I - PHP Object Injection in Shibboleth | https://www.reddit.com/r/netsec/comments/osnbgl/preauth_rce_in_moodle_part_i_php_object_injection/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210802 | 如何利用多杀软结果归并恶意软件家族名称 | https://mp.weixin.qq.com/s/hOvqm0U7rc-NNdVjR0dAaA| 
| 20210802 | 做红队你需要学习“如何挖掘战壕”（三） | https://mp.weixin.qq.com/s/OO_VZ8QB_J5UY88qkpLXDg| 
| 20210802 | SecWiki周刊（第387期) | https://www.sec-wiki.com/weekly/387| 
| 20210802 | Attacking Active Directory: 0 to 0.9 | https://zer1t0.gitlab.io/posts/attacking_ad/| 
| 20210801 | 可信安全网络 —— 安全左移之DDoS对抗 | https://security.tencent.com/index.php/blog/msg/198| 
| 20210801 | 情报研究方法论——对情报收集工作的展望 | https://paper.seebug.org/1647/| 
| 20210801 | 知识图谱及其在安全领域的应用 | https://paper.seebug.org/1649/| 
| 20210801 | 从Github一开源项目ADSEC学习域渗透攻防基础 | https://www.anquanke.com/post/id/248030| 
| 20210801 | Linksys EA6100 固件解密分析 | https://www.anquanke.com/post/id/246659| 
| 20210801 | Apache2+Perl 造成的 CRLF 注入问题 | https://lightless.me/archives/httpd_perl_crlf.html| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210802T12:22:04Z | CVE-2021-3490 | Null | https://github.com/chompie1337/Linux_LPE_eBPF_CVE-2021-3490 | The eBPF ALU32 bounds tracking for bitwise ops (AND, OR and XOR) in the Linux kernel did not properly update 32-bit bounds, which could be turned into out of bounds reads and writes in the Linux kernel and therefore, arbitrary code execution. This issue was fixed via commit 049c4e13714e (%bpf: Fix alu32 const subreg bound tracking on bitwise operations%) (v5.13-rc4) and backported to the stable kernels in v5.12.4, v5.11.21, and v5.10.37. The AND/OR issues were introduced by commit 3f50f132d840 (%bpf: Verifier, do explicit ALU32 bounds tracking%) (5.7-rc1) and the XOR variant was introduced by 2921c90d4718 (%bpf:Fix a verifier failure with xor%) ( 5.10-rc1).| 
| 20210802T11:20:06Z | CVE-2021-2394 | POC of CVE-2021-2394 | https://github.com/lz2y/CVE-2021-2394 | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Core). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via T3, IIOP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210802T10:07:25Z | cve-2021-1480 | Null | https://github.com/xmco/sdwan-cve-2021-1480 | Multiple vulnerabilities in Cisco SD-WAN vManage Software could allow an unauthenticated, remote attacker to execute arbitrary code or allow an authenticated, local attacker to gain escalated privileges on an affected system. For more information about these vulnerabilities, see the Details section of this advisory.| 
| 20210802T09:16:45Z | CVE-2021-22204 | Null | https://github.com/PenTestical/CVE-2021-22204 | Improper neutralization of user data in the DjVu file format in ExifTool versions 7.44 and up allows arbitrary code execution when parsing the malicious image| 
| 20210802T08:34:20Z | CVE-2021-21300 | Null | https://github.com/xiaofeihahah/CVE-2021-21300 | Git is an open-source distributed revision control system. In affected versions of Git a specially crafted repository that contains symbolic links as well as files using a clean/smudge filter such as Git LFS, may cause just-checked out script to be executed while cloning onto a case-insensitive file system such as NTFS, HFS+ or APFS (i.e. the default file systems on Windows and macOS). Note that clean/smudge filters have to be configured for that. Git for Windows configures Git LFS by default, and is therefore vulnerable. The problem has been patched in the versions published on Tuesday, March 9th, 2021. As a workaound, if symbolic link support is disabled in Git (e.g. via `git config --global core.symlinks false`), the described attack won%t work. Likewise, if no clean/smudge filters such as Git LFS are configured globally (i.e. _before_ cloning), the attack is foiled. As always, it is best to avoid cloning repositories from untrusted sources. The earliest impacted version is 2.14.2. The fix versions are: 2.30.1, 2.29.3, 2.28.1, 2.27.1, 2.26.3, 2.25.5, 2.24.4, 2.23.4, 2.22.5, 2.21.4, 2.20.5, 2.19.6, 2.18.5, 2.17.62.17.6.| 
| 20210802T07:24:04Z | CVE-2021-33624 | Proof of Concept for CVE-2021-33624 | https://github.com/Kakashiiiiy/CVE-2021-33624 | In kernel/bpf/verifier.c in the Linux kernel before 5.12.13, a branch can be mispredicted (e.g., because of type confusion) and consequently an unprivileged BPF program can read arbitrary memory locations via a side-channel attack, aka CID-9183671af6db.| 
| 20210802T04:48:27Z | CVE-2021-31630 | Exploit for Authenticated Remote Code Execution on OpenPLC v3 Webserver | https://github.com/h3v0x/CVE-2021-31630-OpenPLC_RCE | 未查询到CVE信息| 
| 20210802T01:56:39Z | CVE-2020-36287 | The dashboard gadgets preference resource of the Atlassian gadgets plugin used in Jira Server and Jira Data Center before version 8.13.5, and from version 8.14.0 before version 8.15.1 allows remote anonymous attackers to obtain gadget related settings via a missing permissions check. | https://github.com/f4rber/CVE-2020-36287 | The dashboard gadgets preference resource of the Atlassian gadgets plugin used in Jira Server and Jira Data Center before version 8.13.5, and from version 8.14.0 before version 8.15.1 allows remote anonymous attackers to obtain gadget related settings via a missing permissions check.| 
| 20210802T01:26:24Z | 未知编号 | Null | https://github.com/zeronohacker/CVE-2018-20250 | 未查询到CVE信息| 
| 20210801T21:03:33Z | CVE-2020-23934 | Python Implementation of CVE-2020-23934 | https://github.com/zyeinn/CVE-2020-23934 | An issue was discovered in RiteCMS 2.2.1. An authenticated user can directly execute system commands by uploading a php web shell in the %Filemanager% section.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T11:44:14Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2465 | 59| 
| 20210802T10:26:17Z | Null | https://github.com/pansilup/cgc-prgs-for-klee-seed-mode | 0 | 0| 
| 20210802T09:51:15Z | Null | https://github.com/coffee100percnt/KleeDiscordBomber | 4 | 0| 
| 20210802T02:07:51Z | Null | https://github.com/adamhumphriescs/TASE_KLEE | 0 | 0| 
| 20210801T22:09:32Z | Izrada novih algoritama za pretragu u okvriu alata za simboličko izvršavanje KLEE | https://github.com/MATF-Software-Verification/2020_03_Klee_Searcher | 0 | 0| 
| 20210801T13:35:53Z | ⬇️ File Upload/sharing application, used by thousands of webmasters since 2007.  | https://github.com/kleeja-official/kleeja | 126 | 36| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T11:21:56Z | Null | https://github.com/yuvalkirstain/s2e-coref | 11 | 4| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T12:29:29Z | From prototype to production, BCFG works closely with projects through the complete development cycle to identify security issues and recommend best practices. With recurring exploitations, rugpulls and hacks infiltrating the Decentralised Finance sector, our mission is to mitigate and pinpoint all possible security risks and flaws within each line of code.  | https://github.com/BCFG-Audit/Smart_Contract_Security_Audits | 0 | 0| 
| 20210802T12:27:23Z | Vulnerabilities of Goby supported with exploitation. | https://github.com/gobysec/GobyVuls | 217 | 38| 
| 20210802T12:23:11Z | My n-day exploit for CVE-2019-18634 (local privilege escalation) | https://github.com/aesophor/CVE-2019-18634 | 2 | 0| 
| 20210802T12:05:55Z | Google Chrome 86.0.4240 V8 - Remote Code Execution | https://github.com/dock0d1/Exploit-Google-Chrome-86.0.4240_V8_RCE | 4 | 3| 
| 20210802T12:02:58Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 29 | 14| 
| 20210802T11:52:01Z | exploit Huawei ONT device | https://github.com/0neday/Exploit-HS8545M-ONT | 2 | 2| 
| 20210802T11:49:19Z | Null | https://github.com/omerfaruktuna/exploiting-epistemic-uncertainty | 0 | 0| 
| 20210802T10:54:17Z | Exploitation of security vulnerabilities found in poorly designed token-weighted governance protocols, using AAVE flash loans to gain unfair voting power. | https://github.com/Elisik/Token-Weighted-Governance-Security-Exploit-Using-AAVE-Flash-Loans | 1 | 0| 
| 20210802T10:41:26Z | The first pixel strike 3d hack made in python. | https://github.com/poggersbutnot/Pixel-Strike-Hack | 1 | 0| 
| 20210802T10:26:43Z | Local exploit for CVE-2021-1675 | https://github.com/tacbliw/PrintNightmare-LPE | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T12:29:52Z | Light-weight UNIX backdoor | https://github.com/phath0m/JadedWraith | 15 | 1| 
| 20210802T08:36:44Z | Patch PE, ELF, Mach-O binaries with shellcode new version in development, available only to sponsors | https://github.com/secretsquirrel/the-backdoor-factory | 2820 | 760| 
| 20210802T07:38:28Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/Ghost | 1241 | 586| 
| 20210802T03:26:40Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 270 | 50| 
| 20210801T14:59:27Z | Null | https://github.com/BackdoorTech/BackdoorTech | 0 | 0| 
| 20210801T12:41:34Z | Null | https://github.com/s3q/backdoor_c | 0 | 0| 
| 20210801T11:58:35Z | A Simple android remote administration tool using sockets. It uses java on the client side and python on the server side | https://github.com/karma9874/AndroRAT | 293 | 130| 
| 20210801T10:58:44Z | Null | https://github.com/lhysgithub/MI-and-Backdoor-on-FL | 0 | 0| 
| 20210801T06:41:19Z | Yet Another PHP Shell | https://github.com/Nickguitar/YAPS | 17 | 2| 
| 20210801T00:42:08Z | example backdoor malware in C explained | https://github.com/lukasbalazik123/h34vy-backdoor | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T10:46:07Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2403 | 355| 
| 20210802T07:25:45Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1738 | 499| 
| 20210802T04:08:56Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1861 | 387| 
| 20210801T01:28:56Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 450 | 68| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T10:52:04Z | Config files for my GitHub profile. | https://github.com/WlNDSS/WlNDSS | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210802T12:03:48Z | FuzzingStudy | https://github.com/qpalzmm22/FuzzingStudy | 0 | 0| 
| 20210802T12:02:37Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210802T11:56:25Z | A Codice Fiscale Generator | https://github.com/tonyarris/codice-fuzzcale | 0 | 0| 
| 20210802T11:48:20Z | Code of fuzzing book | https://github.com/jiniljeil/Fuzzing | 0 | 0| 
| 20210802T11:44:22Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 292 | 39| 
| 20210802T11:39:14Z | Fuzzy Logic Controller implemented in motorola HCS12 microcontroller | https://github.com/rredha/HCS12---Fuzzy-Logic-Control | 0 | 0| 
| 20210802T11:33:37Z | Implementacija algoritama fuzzy klasterovanja, njihova primena na odredjenim skupovima podataka i uporedjivanje sa drugim algoritmima klasterovanja. | https://github.com/markobabic8/Fuzzy-clustering | 0 | 1| 
| 20210802T10:54:20Z | Fuzzy completion provider for Julia | https://github.com/JunoLab/FuzzyCompletions.jl | 6 | 2| 
| 20210802T09:56:20Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6521 | 1327| 
| 20210802T09:33:26Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 1940 | 384| 



# 日更新程序
