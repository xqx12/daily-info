# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210616 | 关于 Guacamole RCE 的那些事儿. | https://paper.seebug.org/1605/| 
| 20210616 | Windows Kernel Hijacking Is Not an Option: MemoryRanger Comes to the Rescue Again. | https://arxiv.org/abs/2106.06065| 
| 20210614 | 深入理解与检测 C2 框架 — BabyShark。 | https://nasbench.medium.com/understanding-detecting-c2-frameworks-babyshark-641be4595845| 
| 20210614 | 探讨武器系统中的安全漏洞。 | https://www.schneier.com/blog/archives/2021/06/vulnerabilities-in-weapons-systems.html| 
| 20210614 | 移动应用渗透测试备忘单。 | https://github.com/fuzz-security/MobileApp-Pentest-Cheatsheet| 
| 20210614 | NoSql 注入备忘单。 | https://nullsweep.com/nosql-injection-cheatsheet/| 
| 20210614 | iOS Malicious Bit Hunter - 一款适用于iOS应用程序的恶意软件检测引擎 | https://www.kitploit.com/2021/06/ios-malicious-bit-hunter-malicious-plug.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+PentestTools+%28PenTest+Tools%29| 
| 20210611 | EDR Evasion: Unhooking DLLs With C# | https://makosecblog.com/malware-dev/dll-unhooking-csharp/| 
| 20210611 | HaE - BurpSuite Highlighter and Extractor | https://github.com/gh0stkey/HaE| 
| 20210611 | al-khaser - 一款 PoC 恶意软件，集合了各类野外样本的技巧，可以用来评估反病毒系统的效果 | https://github.com/LordNoteworthy/al-khaser| 
| 20210611 | Hiding your syscalls - 利用 Frida 检测 Syscall 是否来自 NTDLL 可以检测 Direct Syscall。这篇 Blog 作者介绍如何 Bypass 这个检测逻辑。 | https://passthehashbrowns.github.io/hiding-your-syscalls| 
| 20210611 | 针对数据查询语言引擎 Datalog 的 Fuzz 测试 | https://numairmansur.github.io/papers/2021/FSE2021.pdf| 
| 20210611 | Proxy Windows Tooling via SOCKS | https://posts.specterops.io/proxy-windows-tooling-via-socks-c1af66daeef3?gi=f784c07f3c99| 
| 20210611 | 利用多个预装 App 的漏洞实现在三星设备上安装任意 App、访问敏感数据 | https://blog.oversecured.com/Two-weeks-of-securing-Samsung-devices-Part-1/| 
| 20210611 | Paper：Windows Kernel Hijacking Is Not an Option: MemoryRanger Comes to the Rescue Again | https://commons.erau.edu/jdfsl/vol16/iss1/4/#.YMIN60foJ0g.twitter| 
| 20210611 | 终端防护软件探针采集数据、行为关联、策略决策、事件响应（OODA）整个循环机制的实现 | http://jackson-t.ca/ooda-loops.html| 
| 20210611 | macOS Monterey 新版本系统【捷径】App 实现机制的简单分析 | https://sec.today/pulses/678189e6-09b7-45eb-a96b-134aa8243472/| 
| 20210611 | macOS Monterey 新版本系统【捷径】App 实现机制的简单分析 | https://theevilbit.github.io/posts/monterey_shortcuts/| 
| 20210610 | 匿名信使：木马隐蔽通信浅谈 | https://security.tencent.com/index.php/blog/msg/193| 
| 20210610 | Phishing for AWS credentials via AWS SSO device code authentication | https://blog.christophetd.fr/phishing-for-aws-credentials-via-aws-sso-device-code-authentication/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210618 | 针对接触者追踪系统实施虚假曝光通知攻击 | https://mp.weixin.qq.com/s/7ulSpgPQX5Uiiwhv_5b7eg| 
| 20210618 | 白说:php反序列化之pop链 | https://www.sec-in.com/article/1094| 
| 20210617 | 基于API亲密度分析的安卓恶意软件检测系统 | https://mp.weixin.qq.com/s/HmSjFNnaG4VtuR1MR2QjQA| 
| 20210617 | EXTRACTOR：从威胁报告中提取攻击行为信息 | https://mp.weixin.qq.com/s/Lm_yC0oD_BNiyA4E9TwX7A| 
| 20210617 | JavaScript 常见 AST 梳理 | https://mp.weixin.qq.com/s/biQt6cw05-4G-gkJS9fGTQ| 
| 20210616 | HT2114 Telnet 服务暴力破解 new | https://tools.xazlsec.com/index.php/HT2110/242.html| 
| 20210616 | HT2111 SSH 服务暴力枚举 | https://tools.xazlsec.com/index.php/HT2110/231.html| 
| 20210616 | HT1223 Go 版指纹识别工具 Webanalyze | https://tools.xazlsec.com/index.php/HT1220/215.html| 
| 20210616 | HT1221 Web 应用信息收集工具 WIG | https://tools.xazlsec.com/index.php/HT1220/207.html| 
| 20210616 | HT1218 网络测绘系统利用 | https://tools.xazlsec.com/index.php/HT1210/203.html| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210618T10:48:20Z | CVE-2020-25627 | Stored XSS via moodlenetprofile parameter in user profile | https://github.com/HoangKien1020/CVE-2020-25627 | The moodlenetprofile user profile field required extra sanitizing to prevent a stored XSS risk. This affects versions 3.9 to 3.9.1. Fixed in 3.9.2.| 
| 20210618T10:27:08Z | CVE-2021-0484 | PoC for exploiting CVE-2021-0484 : In readVector of IMediaPlayer.cpp, there is a possible read of uninitialized heap data due to a missing bounds check. This could lead to local information disclosure with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-9 Android-10 Android-11 Android-8.1Android ID: A-173720767 | https://github.com/PwnCast/CVE-2021-0484 | In readVector of IMediaPlayer.cpp, there is a possible read of uninitialized heap data due to a missing bounds check. This could lead to local information disclosure with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-9 Android-10 Android-11 Android-8.1Android ID: A-173720767| 
| 20210618T10:27:01Z | CVE-2020-11235 | PoC for exploiting CVE-2020-11235 : Buffer overflow might occur while parsing unified command due to lack of check of input data received in Snapdragon Auto, Snapdragon Compute, Snapdragon Connectivity, Snapdragon Consumer Electronics Connectivity, Snapdragon Consumer IOT, Snapdragon Industrial IOT, Snapdragon IoT, Snapdragon Mobile, Snapdragon Voice & Music, Snapdragon Wired Infrastructure and Networking | https://github.com/PwnCast/CVE-2020-11235 | Buffer overflow might occur while parsing unified command due to lack of check of input data received in Snapdragon Auto, Snapdragon Compute, Snapdragon Connectivity, Snapdragon Consumer Electronics Connectivity, Snapdragon Consumer IOT, Snapdragon Industrial IOT, Snapdragon IoT, Snapdragon Mobile, Snapdragon Voice & Music, Snapdragon Wired Infrastructure and Networking| 
| 20210618T10:26:54Z | CVE-2020-11238 | PoC for exploiting CVE-2020-11238 : Possible Buffer over-read in ARP/NS parsing due to lack of check of packet length received in Snapdragon Auto, Snapdragon Compute, Snapdragon Connectivity, Snapdragon Consumer Electronics Connectivity, Snapdragon Consumer IOT, Snapdragon Industrial IOT, Snapdragon Mobile, Snapdragon Voice & Music, Snapdragon Wired Infrastructure and Networking | https://github.com/PwnCast/CVE-2020-11238 | Possible Buffer over-read in ARP/NS parsing due to lack of check of packet length received in Snapdragon Auto, Snapdragon Compute, Snapdragon Connectivity, Snapdragon Consumer Electronics Connectivity, Snapdragon Consumer IOT, Snapdragon Industrial IOT, Snapdragon Mobile, Snapdragon Voice & Music, Snapdragon Wired Infrastructure and Networking| 
| 20210618T10:26:48Z | CVE-2020-11239 | PoC for exploiting CVE-2020-11239 : Use after free issue when importing a DMA buffer by using the CPU address of the buffer due to attachment is not cleaned up properly in Snapdragon Auto, Snapdragon Compute, Snapdragon Connectivity, Snapdragon Consumer IOT, Snapdragon Industrial IOT, Snapdragon Mobile, Snapdragon Voice & Music, Snapdragon Wearables | https://github.com/PwnCast/CVE-2020-11239 | Use after free issue when importing a DMA buffer by using the CPU address of the buffer due to attachment is not cleaned up properly in Snapdragon Auto, Snapdragon Compute, Snapdragon Connectivity, Snapdragon Consumer IOT, Snapdragon Industrial IOT, Snapdragon Mobile, Snapdragon Voice & Music, Snapdragon Wearables| 
| 20210618T10:26:40Z | CVE-2021-20728 | PoC for exploiting CVE-2021-20728 : Improper access control vulnerability in goo blog App for Android ver.1.2.25 and earlier and for iOS ver.1.3.3 and earlier allows a remote attacker to lead a user to access an arbitrary website via the vulnerable App. | https://github.com/PwnCast/CVE-2021-20728 | Improper access control vulnerability in goo blog App for Android ver.1.2.25 and earlier and for iOS ver.1.3.3 and earlier allows a remote attacker to lead a user to access an arbitrary website via the vulnerable App.| 
| 20210618T10:26:34Z | CVE-2021-0480 | PoC for exploiting CVE-2021-0480 : In createPendingIntent of SnoozeHelper.java, there is a possible broadcast intent containing a sensitive identifier. This could lead to local information disclosure with no additional execution privileges needed. User interaction is needed for exploitation.Product: AndroidVersions: Android-10 Android-11 Android-8.1 Android-9Android ID: A-174493336 | https://github.com/PwnCast/CVE-2021-0480 | In createPendingIntent of SnoozeHelper.java, there is a possible broadcast intent containing a sensitive identifier. This could lead to local information disclosure with no additional execution privileges needed. User interaction is needed for exploitation.Product: AndroidVersions: Android-10 Android-11 Android-8.1 Android-9Android ID: A-174493336| 
| 20210618T10:26:27Z | CVE-2021-0477 | PoC for exploiting CVE-2021-0477 : In notifyScreenshotError of ScreenshotNotificationsController.java, there is a possible permission bypass due to an unsafe PendingIntent. This could lead to local escalation of privilege with User execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-10 Android-11 Android-8.1 Android-9Android ID: A-178189250 | https://github.com/PwnCast/CVE-2021-0477 | In notifyScreenshotError of ScreenshotNotificationsController.java, there is a possible permission bypass due to an unsafe PendingIntent. This could lead to local escalation of privilege with User execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-10 Android-11 Android-8.1 Android-9Android ID: A-178189250| 
| 20210618T10:26:01Z | CVE-2020-7751 | PoC for exploiting CVE-2020-7751 : pathval before version 1.1.1 is vulnerable to prototype pollution. | https://github.com/PwnCast/CVE-2020-7751 | pathval before version 1.1.1 is vulnerable to prototype pollution.| 
| 20210618T10:25:54Z | CVE-2020-26137 | PoC for exploiting CVE-2020-26137 : urllib3 before 1.25.9 allows CRLF injection if the attacker controls the HTTP request method, as demonstrated by inserting CR and LF control characters in the first argument of putrequest(). NOTE: this is similar to CVE-2020-26116. | https://github.com/PwnCast/CVE-2020-26137 | urllib3 before 1.25.9 allows CRLF injection if the attacker controls the HTTP request method, as demonstrated by inserting CR and LF control characters in the first argument of putrequest(). NOTE: this is similar to CVE-2020-26116.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210618T11:20:53Z | An RTIC application analysis tool which uses KLEE to generate test cases | https://github.com/markhakansson/rauk | 0 | 0| 
| 20210618T09:38:41Z | Null | https://github.com/BajacDev/rust-klee-docker | 2 | 0| 
| 20210618T07:56:21Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1714 | 495| 
| 20210618T03:41:45Z | TInA is an automated, generic, verification-friendly and trustworthy lifting technique turning GNU-style inline assembly into semantically equivalent C code amenable to verification, in order to take advantage of existing C analyzers. | https://github.com/binsec/klee21-tina-artifact | 18 | 1| 
| 20210618T03:03:53Z | C library to support Map2Check Tool | https://github.com/hbgit/map2check-library | 0 | 0| 
| 20210618T01:44:07Z | Null | https://github.com/JaimePSantos/ResearchKlee | 0 | 0| 
| 20210617T20:17:51Z | An opiniated Next TypeScript powered starter which include Klee, emotion / styled-system, framer motion, jest and Cypress | https://github.com/Liinkiing/next-ts-klee-starter | 0 | 0| 
| 20210617T14:48:49Z | A RISC-V RV32 virtual prototype based on riscv-vp with symbolic execution support | https://github.com/agra-uni-bremen/symex-vp | 2 | 0| 
| 20210617T12:19:12Z | A library for concolic execution of RV32 instruction set simulators | https://github.com/agra-uni-bremen/clover | 1 | 0| 
| 20210617T11:14:16Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 150 | 14| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210618T02:35:02Z | Compiler for S2Engine architecure , an CNN accelerator | https://github.com/BUAA-CI-Lab/S2EngineCompiler | 1 | 1| 
| 20210615T13:59:11Z | Simulator for S2Engine architucture , a CNN accelerator | https://github.com/BUAA-CI-Lab/S2EngineSimulator | 1 | 1| 
| 20210614T17:07:29Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 134 | 31| 
| 20210603T23:31:01Z | Command line configuration & Test Tool for WIZnet Serial to Ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool | 7 | 3| 
| 20210602T08:47:12Z | S2E project | https://github.com/romanguerin/S2E | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210618T12:44:24Z | Some scripts to exploit my vulnerable web app | https://github.com/kitty14956590/vuln-webapp-scripts | 1 | 0| 
| 20210618T12:42:03Z | Rewrite in Go of the exploit from 0rphon for Remote Mouse 3.008 | https://github.com/pngouin/46697 | 0 | 0| 
| 20210618T12:35:13Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9565 | 1558| 
| 20210618T12:28:44Z | Rewrite in Go of the exploit from 0rphon for Remote Mouse 3.008 | https://github.com/pngouin/RemoteMouse-3.008 | 0 | 0| 
| 20210618T12:04:16Z | Null | https://github.com/th3ken-dev/TH3KEN-EDITON | 2 | 0| 
| 20210618T12:02:57Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 24 | 11| 
| 20210618T11:38:07Z | Exploit Development and Reverse Engineering with GDB Made Easy | https://github.com/pwndbg/pwndbg | 3742 | 544| 
| 20210618T11:37:24Z | CamRaptor is a tool that exploits several vulnerabilities in popular DVR cameras to obtain camera credentials. | https://github.com/EntySec/CamRaptor | 3 | 0| 
| 20210618T10:59:52Z | Container (Docker) escape exploits | https://github.com/duowen1/Container-escape-exps | 0 | 0| 
| 20210618T10:54:05Z | Labs to learn exploiting | https://github.com/aliakyurek/exploit_labs | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210618T11:07:38Z | a C++ backdoor using telegram bot as a C2 | https://github.com/kensh1ro/NativeTeleBackdoor | 0 | 0| 
| 20210618T10:44:55Z | SCP:SL simple server side backdoor | https://github.com/ggpabuk/ExiledBackdoor | 0 | 0| 
| 20210618T10:09:22Z | a simple backdoor in Nim | https://github.com/kensh1ro/NimTeleBackdoor | 10 | 1| 
| 20210618T07:37:03Z | shell backdoor buat peretas website, di jamin tembus di segala perang :) , sudah di test di beberapa  website bahkan server windows sekalipun rasanya ANJING BANGET | https://github.com/beruangsalju/shell | 0 | 3| 
| 20210618T03:50:13Z | Null | https://github.com/backdoor322/backdoor322github.io | 0 | 0| 
| 20210618T03:34:30Z | Null | https://github.com/diyalo-code/OwnReverseBackdoor | 0 | 0| 
| 20210618T00:17:32Z | Shell Backdoor Fron Noilesha | https://github.com/Noilesha/Noiesha-Backdoor | 0 | 0| 
| 20210617T20:48:27Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/Ghost | 1157 | 551| 
| 20210617T20:18:09Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 250 | 43| 
| 20210617T18:53:10Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 210 | 40| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210618T12:49:08Z | just a personal site~ | https://github.com/davelowqx/fuzzyfilms | 0 | 0| 
| 20210618T12:24:18Z | A JavaScript Engine Fuzzer | https://github.com/googleprojectzero/fuzzilli | 1231 | 219| 
| 20210618T12:15:17Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 9 | 5| 
| 20210618T12:01:53Z | Null | https://github.com/Uttirna/Fuzzy-Expert-System | 0 | 0| 
| 20210618T12:01:25Z | The code behind getfursu.it | https://github.com/veelkoov/fuzzrake | 6 | 0| 
| 20210618T11:59:05Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6383 | 1300| 
| 20210618T11:28:38Z | Null | https://github.com/danikirby/fuzzy-train | 0 | 0| 
| 20210618T11:12:38Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 3 | 1| 
| 20210618T11:01:33Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210618T11:00:22Z | Null | https://github.com/wiktor7245/ocenaProjektuFuzzyDLSZ | 0 | 0| 



# 日更新程序
