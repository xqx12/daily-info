# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210601 | HITB 2021 AMS 会议议题，Android 混合应用（Hybrid Application）的新攻击模型，来自 Ce Qin | https://conference.hitb.org/hitbsecconf2021ams/materials/D2T1%20-%20A%20New%20Attack%20Model%20for%20Hybrid%20Mobile%20Applications%20-%20Ce%20Qin.pdf| 
| 20210601 | 西门子 PLC 代码执行漏洞分析（CVE-2020-15782） | https://claroty.com/2021/05/28/blog-research-race-to-native-code-execution-in-plcs/| 
| 20210601 | HITB 2021 AMS 会议议题 “Lightbranch: Binary Fuzzing with Snapshot-Assisted-Driven Comparison Branches Analysis” | https://conference.hitb.org/hitbsecconf2021ams/materials/D2T2%20-%20Binary%20Fuzzing%20with%20Snapshot-Assisted-Driven%20Comparison%20Branch%20Analysis%20-%20Kijong%20Son.pdf| 
| 20210601 | 来自 USENIX 的一篇 Paper，作者提出一种缓解内核漏洞（Bug）的 Workarounds 方法，以 undo 的方式缓解问题 syscall 带来的影响 | https://www.usenix.org/system/files/sec21fall-talebi.pdf| 
| 20210601 | Finding Memory Bugs with Google Address Sanitizer (ASAN) on Microcontrollers | https://mcuoneclipse.com/2021/05/31/finding-memory-bugs-with-google-address-sanitizer-asan-on-microcontrollers/| 
| 20210601 | Chrome 浏览器 AppCache 机制相关的跨域跳转 URL 泄露漏洞 | https://blog.lbherrera.me/posts/appcache-forgotten-tales/| 
| 20210601 | Pwn2Win CTF 2021 Writeup | https://ptr-yudai.hatenablog.com/entry/2021/05/31/232507| 
| 20210601 | INVSCOV - 这篇 paper 基于 LLVM 与 AFL++ 尝试解决 Fuzz 过程中基于覆盖率的反馈算法不足的问题 | http://www.s3.eurecom.fr/docs/usenixsec21_fioraldi.pdf| 
| 20210601 | Microsoft Hyper-V vmswitch.sys RCE 虚拟机逃逸漏洞 PoC（CVE-2021-28476） | https://github.com/0vercl0k/CVE-2021-28476| 
| 20210601 | 来自Readme的威胁｜疑似长达数年的供应链攻击分析 | https://sec.today/pulses/89023c4c-9ecc-4a28-82dc-8822e660710b/| 
| 20210601 | 来自Readme的威胁｜疑似长达数年的供应链攻击分析 | https://security.tencent.com/index.php/blog/msg/192| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210601 | 智能合约安全系列 -- 举一反三总结篇 | https://mp.weixin.qq.com/s/ZxrBHgZ5a_IuU0nNySIlwA| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210602T00:27:50Z | CVE-2021-28476 | PoC for CVE-2021-28476 a guest-to-host "Hyper-V Remote Code Execution Vulnerability" in vmswitch.sys. | https://github.com/0vercl0k/CVE-2021-28476 | Hyper-V Remote Code Execution Vulnerability| 
| 20210602T00:24:54Z | CVE-2021-29447 | Wordpress XXE injection 구축 자동화 및 PoC  | https://github.com/dnr6419/CVE-2021-29447 | Wordpress is an open source CMS. A user with the ability to upload files (like an Author) can exploit an XML parsing issue in the Media Library leading to XXE attacks. This requires WordPress installation to be using PHP 8. Access to internal files is possible in a successful XXE attack. This has been patched in WordPress version 5.7.1, along with the older affected versions via a minor release. We strongly recommend you keep auto-updates enabled.| 
| 20210601T19:16:35Z | CVE-2021-21985 | This script check the CVE-2021-21985 vulnerability and patch on vCenter Server. | https://github.com/mauricelambert/CVE-2021-21985 | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210601T18:17:17Z | CVE-2020-11978 | PoC of how to exploit a RCE vulnerability of the example DAGs in Apache Airflow <1.10.11  | https://github.com/pberba/CVE-2020-11978 | | 
| 20210601T13:55:26Z | CVE-2020-14882 | CVE-2020-14882_Exploit 支持12.2.X和10.3.6版本，12.2.x可回显 | https://github.com/nice0e3/CVE-2020-14882_Exploit_Gui | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210601T11:18:36Z | CVE-2021-2989 | test | https://github.com/dorisroot1/CVE-2021-2989 | 未查询到CVE信息| 
| 20210601T10:41:33Z | CVE-2021-3999 | CVE-2021-3999 | https://github.com/dorisroot1/CVE-2021-3999 | 未查询到CVE信息| 
| 20210601T09:37:59Z | CVE-2021-32620 | PoC for exploiting CVE-2021-32620 | https://github.com/JamesGeee/CVE-2021-32620 | ### Impact A user disabled on a wiki using email verification for registration can re-activate himself by using the activation link provided for his registration. ### Patches The problem has been patched in the following versions of XWiki: 11.10.13, 12.6.7, 12.10.2, 13.0. ### Workarounds It%s possible to workaround the issue by resetting the `validkey` property of the disabled XWiki users. This can be done by editing the user profile with object editor. ### References https://jira.xwiki.org/browse/XWIKI-17942 ### For more information If you have any questions or comments about this advisory: * Open an issue in [Jira](http://jira.xwiki.org) * Email us at [Security mailing-list](mailto:security@xwiki.org)| 
| 20210601T09:37:55Z | CVE-2021-29507 | PoC for exploiting CVE-2021-29507 | https://github.com/JamesGeee/CVE-2021-29507 | ### Impact _What kind of vulnerability is it? Who is impacted?_ The vulnerable component could be crashed when the configuration file is intentionally/ unintentionally containing the special characters. All the applications which are using could fail to generate their dlt logs in system. ### Patches _Has the problem been patched? What versions should users upgrade to?_ There is solution for the problem but the patch is not integrated yet. ### Workarounds _Is there a way for users to fix or remediate the vulnerability without upgrading?_ Check the integrity of information in configuration file manually. ### References _Are there any links users can visit to find out more?_ N/A ### For more information If you have any questions or comments about this advisory: * Open an issue in [ GENIVI/dlt-daemon ](https://github.com/GENIVI/dlt-daemon/issues) * Email us at [Mailinglist](mailto:https://lists.genivi.org/mailman/listinfo/genivi-diagnostic-log-and-trace_lists.genivi.org)| 
| 20210601T09:37:40Z | CVE-2021-29505 | PoC for exploiting CVE-2021-29505 | https://github.com/JamesGeee/CVE-2021-29505 | ### Impact The vulnerability may allow a remote attacker has sufficient rights to execute commands of the host only by manipulating the processed input stream. No user is affected, who followed the recommendation to setup XStream%s security framework with a whitelist limited to the minimal required types. ### Patches If you rely on XStream%s default blacklist of the Security Framework, you will have to use at least version 1.4.17. ### Workarounds See [workarounds](https://x-stream.github.io/security.html#workaround) for the different versions covering all CVEs. ### References See full information about the nature of the vulnerability and the steps to reproduce it in XStream%s documentation for [CVE-2021-xxxxx](https://x-stream.github.io/CVE-2021-xxxxx.html). ### Credits V3geB1rd, white hat hacker from Tencent Security Response Center found and reported the issue to XStream and provided the required information to reproduce it. ### For more information If you have any questions or comments about this advisory: * Open an issue in [XStream](https://github.com/x-stream/xstream/issues) * Email us at [XStream Google Group](https://groups.google.com/group/xstream-user)| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210602T00:50:02Z | Dodoco doko? | https://github.com/RiceFT/klee | 0 | 0| 
| 20210601T23:04:32Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210601T21:37:25Z | New portfolio website using react and material ui.  | https://github.com/collinkleest/kleest.io | 1 | 0| 
| 20210601T19:30:43Z | Null | https://github.com/nithinsai263/kleenacademy | 0 | 0| 
| 20210601T15:20:26Z | Config files for my GitHub profile. | https://github.com/MaxKleem/MaxKleem | 0 | 0| 
| 20210601T14:19:44Z | A RISC-V RV32 virtual prototype based on riscv-vp with symbolic execution support | https://github.com/agra-uni-bremen/symex-vp | 1 | 0| 
| 20210601T14:15:46Z | A library for concolic execution of RV32 instruction set simulators | https://github.com/agra-uni-bremen/clover | 0 | 0| 
| 20210601T08:30:57Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1708 | 494| 
| 20210601T02:37:36Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 641 | 15| 
| 20210601T00:42:00Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 10 | 1| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210602T01:21:46Z | Code refered to Diversight backend  aplication, realized by META-EXPLOIT team, on ioasys Camp - Fase 02. | https://github.com/META-EXPLOIT/backend-version | 0 | 0| 
| 20210602T01:09:09Z | Null | https://github.com/HarrysExploit/Harrys-exploit-script-hub | 0 | 0| 
| 20210602T01:02:48Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 24 | 11| 
| 20210602T01:01:06Z | A module for Garry%s Mod that mitigates exploits on the Source engine. | https://github.com/danielga/gmsv_serversecure | 65 | 18| 
| 20210602T00:58:23Z | Null | https://github.com/th3ken-dev/TH3KEN-EDITON | 2 | 0| 
| 20210602T00:51:22Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 16 | 11| 
| 20210602T00:41:40Z | Refactored exploit code for Gitstack version 2.3.10 | https://github.com/TBernard97/Gitstack-2.3.10-Exploit-Refactor | 0 | 0| 
| 20210601T23:26:28Z | Local file inclusion discovery and exploitation tool | https://github.com/hansmach1ne/lfimap | 2 | 0| 
| 20210601T22:52:11Z | EDL exploit for Motorola Moto E 2014 | https://github.com/Vicc2008/firehose_condor | 0 | 0| 
| 20210601T22:31:36Z | Server-Side Template Injection and Code Injection Detection and Exploitation Tool | https://github.com/epinna/tplmap | 2260 | 489| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210602T00:44:11Z | Simple console based Windows key-logger created in C++ | https://github.com/caffene-query/CPP-Key-Logger | 0 | 0| 
| 20210601T22:17:19Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 72 | 12| 
| 20210601T19:15:36Z | My personal unique wiki for hacking the router firmware used by (Telia)TG799vac Xtream v17.2-MINT delivered from Technicolor  | https://github.com/wuseman/TG799VAC-XTREME-17.2-MINT | 59 | 17| 
| 20210601T19:06:50Z | Python 3 IRC Bot / Botnet | https://github.com/trackmastersteve/HackServ | 21 | 17| 
| 20210601T18:49:48Z | A token logger for discord + steals Brave/Chrome passwords and usernames | https://github.com/CUPZYY/Backdoor-Machine | 8 | 1| 
| 20210601T18:30:22Z | Null | https://github.com/KoPlayz/BackdoorBot | 0 | 0| 
| 20210601T14:44:05Z | The BinCT backdoor bot https://github.com/BinCT/Protocol-Bot but updated so no fatal code error | https://github.com/XatoriN/Protocol-Bot-Updated | 0 | 0| 
| 20210601T14:36:21Z | PHP 8.1.0-dev Backdoor System Shell Script | https://github.com/flast101/php-8.1.0-dev-backdoor-rce | 6 | 2| 
| 20210601T14:32:12Z | Upload file / Access file / You are now admin. | https://github.com/JulioPotier/SecuPress-Backdoor-User | 74 | 29| 
| 20210601T13:54:02Z | this is advance py39 backdoor created to use in college project | https://github.com/Bhadresh-Malankiya/BackdoorPy3 | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210602T00:58:45Z | Null | https://github.com/jirayupiwon1/fuzzy-carnival | 0 | 0| 
| 20210602T00:06:37Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 8 | 5| 
| 20210601T23:43:18Z | Null | https://github.com/lacygoill/vim-fuzzy | 0 | 1| 
| 20210601T23:39:12Z | rfuzz: coverage-directed fuzzing for RTL research platform | https://github.com/ekiwi/rfuzz | 35 | 4| 
| 20210601T23:05:13Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 75 | 18| 
| 20210601T23:04:06Z | Null | https://github.com/dimon19991/fuzzy_sets | 0 | 0| 
| 20210601T22:53:23Z | Another one-off fuzzing repo that I only made to learn more | https://github.com/Benjins/OpenGLFuzz | 0 | 0| 
| 20210601T22:39:42Z | Written standups for remote teams. Inspired by Basecamp. | https://github.com/malikpiara/fuzzboard | 1 | 0| 
| 20210601T22:23:20Z | Fuzzinator Random Testing Framework | https://github.com/renatahodovan/fuzzinator | 172 | 38| 
| 20210601T21:40:17Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6345 | 1288| 



# 日更新程序
