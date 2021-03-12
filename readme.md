# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210312 | Playing in the (Windows) Sandbox | https://research.checkpoint.com/2021/playing-in-the-windows-sandbox/| 
| 20210312 | Regexploit: DoS-able Regular Expressions | https://blog.doyensec.com//2021/03/11/regexploit.html| 
| 20210312 | Whitelist Me, Maybe? 有攻击者组织 “Netbounce” 给 Fortinet 发邮件请求将被 误报的软件加入白名单 | https://www.fortinet.com/blog/threat-research/netbounce-threat-actor-tries-bold-approach-to-evade-detection?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+fortinet%2Fblog%2Fthreat-research+%28Fortinet+Threat+Research+Blog%29| 
| 20210312 | The Battle Between White Box and Black Box Bug Hunting in Wireless Routers | https://www.thezdi.com/blog/2021/3/11/the-battle-between-white-box-and-black-box-bug-hunting-in-wireless-routers| 
| 20210312 | Windows 内核 CVE-2020-1034 漏洞利用的新思路 | http://windows-internals.com/exploiting-a-simple-vulnerability-part-2-what-if-we-made-exploitation-harder/?utm_source=rss| 
| 20210312 | 利用 GNU GRUB 漏洞实现特权命令执行 | https://ssd-disclosure.com/ssd-advisory-gnu-grub-command-injection/| 
| 20210312 | Windows Windbg 调试系列视频教程 | https://www.youtube.com/watch?v=8zBpqc3HkSE&list=PLhx7-txsG6t6n_E2LgDGqgvJtCHPL7UFu| 
| 20210312 | POC 2020 会议关于利用 CodeQL 静态审计代码的议题（视频） | https://www.youtube.com/watch?v=XmAEgl8bVhg| 
| 20210312 | VMware vCenter RCE 漏洞踩坑实录 | https://paper.seebug.org/1500/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210312 | JavaScript反调试技巧 | https://mp.weixin.qq.com/s/NMJd91AmuGEANz00sZELfw| 
| 20210312 | 资产管理的难点 | https://mp.weixin.qq.com/s/DqtIzNdDvB7pYjXmoP1quQ| 
| 20210312 | Japan Security Analyst Conference 2021 -1st Track- | https://blogs.jpcert.or.jp/en/2021/03/jsac2021report3.html| 
| 20210312 | Examining Exchange Exploitation and its Lessons for Defend... | https://www.domaintools.com/resources/blog/examining-exchange-exploitation-and-its-lessons-for-defenders| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210312T13:05:30Z | CVE-2021-26855 | CVE-2021-26855 SSRF Exchange Server | https://github.com/Udyz/CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210312T12:56:43Z | CVE-2021-26855 | PoC of proxylogon chain SSRF(CVE-2021-26855) to write file by testanull, censored by github | https://github.com/hackerschoice/CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210312T12:55:59Z | CVE-2021-26855 | Scanner and PoC for CVE-2021-26855  | https://github.com/KotSec/CVE-2021-26855-Scanner | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210312T11:58:20Z | CVE-2020-29134 | Exploit CVE-2020-29134 - TOTVS Fluig Platform - Path Traversal | https://github.com/lucxssouza/CVE-2020-29134 | TOTVS Fluig Platform allows directory traversal via a base64 encoded in paremeter %file=../% to a volume/stream/ URI. This affects: Fluig Lake 1.7.0-210217, Fluig Lake 1.7.0-210209, Fluig Lake 1.7.0-210112, Fluig Lake 1.7.0-201222, Fluig Lake 1.7.0-201215, Fluig Lake 1.7.0-201201,Fluig Lake 1.7.0-201124, Fluig Lake 1.7.0-201117, Fluig Lake 1.7.0-201103, Fluig Lake 1.7.0-201027, Fluig Lake 1.7.0-201020, Fluig Lake 1.7.0-201013, Fluig Lake 1.7.0-201006, Fluig Lake 1.7.0-200915, Fluig Lake 1.7.0-200907, Fluig Lake 1.7.0-200901, Fluig Lake 1.7.0-200825, Fluig Lake 1.7.0-200818, Fluig Lake 1.7.0-200804, Fluig Lake 1.7.0-200616), Fluig 1.6.5-200915, Fluig 1.6.5-200128, Fluig 1.6.5-191029, and Fluig 1.6.4-181026.| 
| 20210312T10:44:01Z | 未知编号 | Null | https://github.com/shacojx/CVE_2021_26855_Exploit_Hub | 未查询到CVE信息| 
| 20210312T08:44:53Z | CVE-2021-26855 | CVE-2021-26855, also known as Proxylogon, is a server-side request forgery (SSRF) vulnerability in Exchange that allows an attacker to send arbitrary HTTP requests and authenticate as the Exchange server. According to Orange Tsai, the researcher who discovered the vulnerabilities, CVE-2021-26855 allows code execution when chained with CVE-2021-27065 (see below). A successful exploit chain would allow an unauthenticated attacker to "execute arbitrary commands on Microsoft Exchange Server through only an open 443 port." More information and a disclosure timeline are available at https://proxylogon.com. | https://github.com/raheel0x01/CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210312T08:30:49Z | CVE-2021-26855 | Null | https://github.com/XairGit/CVE-2021-26855 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-26412, CVE-2021-26854, CVE-2021-26857, CVE-2021-26858, CVE-2021-27065, CVE-2021-27078.| 
| 20210312T08:30:29Z | 未知编号 | 2020l4web-app-mockup-DanCvejn created by GitHub Classroom | https://github.com/pslib-cz/2020l4web-app-mockup-DanCvejn | 未查询到CVE信息| 
| 20210312T07:20:22Z | CVE-2021-21300 | Null | https://github.com/CppXL/CVE-2021-21300 | Git is an open-source distributed revision control system. In affected versions of Git a specially crafted repository that contains symbolic links as well as files using a clean/smudge filter such as Git LFS, may cause just-checked out script to be executed while cloning onto a case-insensitive file system such as NTFS, HFS+ or APFS (i.e. the default file systems on Windows and macOS). Note that clean/smudge filters have to be configured for that. Git for Windows configures Git LFS by default, and is therefore vulnerable. The problem has been patched in the versions published on Tuesday, March 9th, 2021. As a workaound, if symbolic link support is disabled in Git (e.g. via `git config --global core.symlinks false`), the described attack won%t work. Likewise, if no clean/smudge filters such as Git LFS are configured globally (i.e. _before_ cloning), the attack is foiled. As always, it is best to avoid cloning repositories from untrusted sources. The earliest impacted version is 2.14.2. The fix versions are: 2.30.1, 2.29.3, 2.28.1, 2.27.1, 2.26.3, 2.25.5, 2.24.4, 2.23.4, 2.22.5, 2.21.4, 2.20.5, 2.19.6, 2.18.5, 2.17.62.17.6.| 
| 20210312T03:49:56Z | 未知编号 | Null | https://github.com/0xmahmoudJo0/Check_Emails_For_CVE_2021_26855 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210312T12:35:29Z | The Kleenex programming language | https://github.com/diku-kmc/kleenexlang | 46 | 4| 
| 20210312T11:46:34Z | Null | https://github.com/dhanyavittaldas/kleen-tidy-master | 0 | 0| 
| 20210312T11:26:04Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 109 | 8| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210312T13:06:28Z | This repository contains multiple tools and methods that can be used to hack CS:GO. | https://github.com/samdobsonDEV/csgo-exploits | 0 | 0| 
| 20210312T13:02:26Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 10 | 6| 
| 20210312T13:01:57Z | Additional material for the paper %MoralStrength: Exploiting a Moral Lexicon and Embedding Similarity for Moral Foundations Prediction% | https://github.com/oaraque/moral-foundations | 17 | 7| 
| 20210312T12:51:15Z | PwnXSS: Vulnerability (XSS) scanner exploit | https://github.com/pwn0sec/PwnXSS | 278 | 63| 
| 20210312T12:50:22Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 9 | 5| 
| 20210312T12:49:29Z | CDK is an open-sourced container penetration toolkit, offering stable exploitation in different slimmed containers without any OS dependency. It comes with penetration tools and many powerful PoCs/EXPs helps you to escape container and takeover K8s cluster easily. | https://github.com/cdk-team/CDK | 1250 | 176| 
| 20210312T12:34:47Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 9 | 1| 
| 20210312T12:03:22Z | Repo for testing some exploits | https://github.com/RobertFent/exploits | 0 | 0| 
| 20210312T11:58:20Z | Exploit CVE-2020-29134 - TOTVS Fluig Platform - Path Traversal | https://github.com/lucxssouza/CVE-2020-29134 | 0 | 0| 
| 20210312T11:30:45Z | MSPoreU-net: A novel U-net architecture to exploit multi-scale pores in segmentation of digital rock images  | https://github.com/mohsenkondori/MSPoreUnet | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210312T12:21:16Z | Null | https://github.com/Delle9999/backdoor | 0 | 0| 
| 20210312T09:47:54Z | Linux Kernel module-less implant (backdoor) | https://github.com/milabs/kopycat | 24 | 10| 
| 20210312T08:36:35Z | C# Backdoor & Mapper/Proxy tool (backdoor & proxy tool working in memory only) | https://github.com/DamonMohammadbagher/NativePayload_MP | 2 | 0| 
| 20210312T06:56:34Z | A Simple android remote administration tool using sockets. It uses java on the client side and python on the server side | https://github.com/karma9874/AndroRAT | 182 | 80| 
| 20210312T05:27:17Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 50 | 8| 
| 20210312T03:03:44Z | This repository contains a detailed list of commands and instructions used to facilitate a backdoor exploitation through a controlled environment. | https://github.com/dorianeSF/Backdoor_Simulation | 0 | 0| 
| 20210312T02:25:30Z | A sample app to demonstrate how to create Xamarin UITests using the Page Object architecture, Backdoor Methods and App Links (aka Deep Linking) | https://github.com/brminnick/UITestSampleApp | 34 | 25| 
| 20210312T00:59:22Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. Ghost Framework gives you the power and convenience of remote Android device administration. | https://github.com/EntySec/ghost | 978 | 486| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210312T12:52:08Z | Some sort of a social network using react js, hello from 2004 :) | https://github.com/androranogajec/fuzzy-social-network | 0 | 0| 
| 20210312T12:47:04Z | Coverage-guided, in-process fuzzing for the JVM | https://github.com/CodeIntelligenceTesting/jazzer | 232 | 10| 
| 20210312T12:44:50Z | Null | https://github.com/s9varesc/url-fuzzing | 0 | 0| 
| 20210312T12:40:10Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 0| 
| 20210312T12:22:57Z | Null | https://github.com/AdamKorcz/go-fuzz-headers | 0 | 0| 
| 20210312T12:17:16Z | Port of npm%s fuzzy-search | https://github.com/doomium-chloride/fuzzy-search-py | 0 | 0| 
| 20210312T12:10:51Z | Project page for %The Fuzzing Book% | https://github.com/uds-se/fuzzingbook | 546 | 109| 
| 20210312T11:40:36Z | Null | https://github.com/LucidPep/fuzzy | 0 | 0| 
| 20210312T11:29:33Z | Null | https://github.com/revault/cosignerd_fuzz_corpus | 0 | 0| 
| 20210312T11:27:56Z | A Fuzzy logic system example for Matlab | https://github.com/Madrant/fuzzy_logic_example | 0 | 0| 



# 日更新程序
