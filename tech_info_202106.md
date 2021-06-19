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
| 20210618T16:55:05Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 10 | 1| 
| 20210618T14:00:38Z | I main Klee so here is information about her | https://github.com/ibelivekleesupremacy5/kleeismybeloved | 0 | 0| 
| 20210618T11:20:53Z | An RTIC application analysis tool which uses KLEE to generate test cases | https://github.com/markhakansson/rauk | 0 | 0| 
| 20210618T09:38:41Z | Null | https://github.com/BajacDev/rust-klee-docker | 2 | 0| 
| 20210618T07:56:21Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1714 | 495| 
| 20210618T03:41:45Z | TInA is an automated, generic, verification-friendly and trustworthy lifting technique turning GNU-style inline assembly into semantically equivalent C code amenable to verification, in order to take advantage of existing C analyzers. | https://github.com/binsec/klee21-tina-artifact | 18 | 1| 
| 20210618T03:03:53Z | C library to support Map2Check Tool | https://github.com/hbgit/map2check-library | 0 | 0| 
| 20210618T01:44:07Z | Null | https://github.com/JaimePSantos/ResearchKlee | 0 | 0| 
| 20210617T20:17:51Z | An opiniated Next TypeScript powered starter which include Klee, emotion / styled-system, framer motion, jest and Cypress | https://github.com/Liinkiing/next-ts-klee-starter | 0 | 0| 
| 20210617T14:48:49Z | A RISC-V RV32 virtual prototype based on riscv-vp with symbolic execution support | https://github.com/agra-uni-bremen/symex-vp | 2 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210618T15:49:13Z | Your S2E project management tools. Visit https://s2e.systems/docs to get started. | https://github.com/S2E/s2e-env | 73 | 31| 
| 20210618T15:48:55Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 135 | 31| 
| 20210618T02:35:02Z | Compiler for S2Engine architecure , an CNN accelerator | https://github.com/BUAA-CI-Lab/S2EngineCompiler | 1 | 1| 
| 20210615T13:59:11Z | Simulator for S2Engine architucture , a CNN accelerator | https://github.com/BUAA-CI-Lab/S2EngineSimulator | 1 | 1| 
| 20210603T23:31:01Z | Command line configuration & Test Tool for WIZnet Serial to Ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool | 7 | 3| 
| 20210602T08:47:12Z | S2E project | https://github.com/romanguerin/S2E | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210619T01:54:01Z | ps4h3x.xyz Trainer | https://github.com/PS4H3X-xyz/Trainer | 0 | 0| 
| 20210619T01:46:48Z | Null | https://github.com/yuvaly0/exploits | 2 | 0| 
| 20210619T01:39:22Z | exploit-database-papers | https://github.com/offensive-security/exploitdb-papers | 315 | 45| 
| 20210619T01:13:30Z | buffer overflow exploit for vulnserver, feel free to use. | https://github.com/injectmymalware/vulnserverexploit | 0 | 0| 
| 20210619T01:09:31Z | Exploits project Hacking Command Center | https://github.com/chacka0101/exploits | 6 | 8| 
| 20210619T01:02:55Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 24 | 11| 
| 20210619T01:01:26Z | CTF framework and exploit development library | https://github.com/Gallopsled/pwntools | 7975 | 1403| 
| 20210618T23:54:26Z | basket - An all-in-one Exploitation-Framework. | https://github.com/brows3r/basket | 0 | 0| 
| 20210618T22:48:42Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9568 | 1558| 
| 20210618T21:02:12Z | Script para usar el exploit de deteccion de vulnerabilidades de windows o dispositivos conectados (normalmente windows 7 o testeados) | https://github.com/xNetting/script-nmap-ms17-010 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210618T22:38:27Z | Backdoor Android programado en Phyton | https://github.com/Fr0il4nSierra/Backdoor_Phyton | 0 | 0| 
| 20210618T22:10:59Z | idk just for testing on virtual machine, don%t use this on your real machine ;p | https://github.com/ztbw/backdoor | 0 | 0| 
| 20210618T21:48:25Z | esse codifo em  python serve para facilitar a interação do usuario com o backdoor, o backdoor é feito por uma função em php que se chama ACCEPT_LANGUAGE sem validação | https://github.com/flaco0x01/interface-para-backdoor-python | 0 | 0| 
| 20210618T19:39:50Z | Creating more and more complexes backdoors | https://github.com/hugoreb/Backdoor | 0 | 0| 
| 20210618T17:24:18Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 251 | 43| 
| 20210618T17:12:11Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/Ghost | 1159 | 551| 
| 20210618T16:31:26Z | EcchiExploit Shell v1.0 | https://github.com/dmzhari/ecchi-shell | 0 | 0| 
| 20210618T15:42:28Z | Herramienta de ingeniería social (Creador de puerta trasera con Reverse Shell para Windows/Android) con Ngrok. | https://github.com/m4lal0/backdoorPhish | 0 | 0| 
| 20210618T14:52:36Z | A sample app to demonstrate how to create Xamarin UITests using the Page Object architecture, Backdoor Methods and App Links (aka Deep Linking) | https://github.com/brminnick/UITestSampleApp | 35 | 27| 
| 20210618T14:03:05Z | Rxploit | https://github.com/BeyondDevy/Rxploit | 3 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210619T01:19:09Z | Hein | https://github.com/Hughein/fuzzy-fortnight | 0 | 0| 
| 20210619T01:16:25Z | These tests of libdwarf/dwarfdump include old object files, new ones, and many fuzzed object files. These are the definitive tests that things work.. Most people have no reason to run these tests. | https://github.com/davea42/libdwarf-regressiontests | 0 | 0| 
| 20210619T00:59:48Z | Fuzzy Expert Systems in Python | https://github.com/jdvelasq/fuzzy-expert | 0 | 0| 
| 20210619T00:32:32Z | Null | https://github.com/FormulaT/fuzzy-train | 0 | 0| 
| 20210619T00:28:22Z | Null | https://github.com/opimentel-github/fuzzy-torch | 1 | 0| 
| 20210619T00:19:21Z | 渗透测试路径字典，爆破字典。内容来自互联网和实战积累。 | https://github.com/cpkkcb/fuzzDicts | 93 | 43| 
| 20210619T00:12:22Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210618T23:53:33Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6384 | 1300| 
| 20210618T23:21:52Z | Null | https://github.com/alfianhid/Plotting-Fuzzy-Logic-Graph-with-Python | 0 | 0| 
| 20210618T23:17:24Z | 🤖 Repeat tests. Repeat tests. Repeat tests. | https://github.com/ehmicky/test-each | 92 | 2| 



# 日更新程序
