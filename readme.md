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
| 20210601T11:26:54Z | CVE-2021-29447 | Wordpress XXE injection 구축 자동화 및 PoC  | https://github.com/dnr6419/CVE-2021-29447 | Wordpress is an open source CMS. A user with the ability to upload files (like an Author) can exploit an XML parsing issue in the Media Library leading to XXE attacks. This requires WordPress installation to be using PHP 8. Access to internal files is possible in a successful XXE attack. This has been patched in WordPress version 5.7.1, along with the older affected versions via a minor release. We strongly recommend you keep auto-updates enabled.| 
| 20210601T11:18:36Z | CVE-2021-2989 | test | https://github.com/dorisroot1/CVE-2021-2989 | 未查询到CVE信息| 
| 20210601T10:41:33Z | CVE-2021-3999 | CVE-2021-3999 | https://github.com/dorisroot1/CVE-2021-3999 | 未查询到CVE信息| 
| 20210601T09:37:59Z | CVE-2021-32620 | PoC for exploiting CVE-2021-32620 | https://github.com/JamesGeee/CVE-2021-32620 | ### Impact A user disabled on a wiki using email verification for registration can re-activate himself by using the activation link provided for his registration. ### Patches The problem has been patched in the following versions of XWiki: 11.10.13, 12.6.7, 12.10.2, 13.0. ### Workarounds It%s possible to workaround the issue by resetting the `validkey` property of the disabled XWiki users. This can be done by editing the user profile with object editor. ### References https://jira.xwiki.org/browse/XWIKI-17942 ### For more information If you have any questions or comments about this advisory: * Open an issue in [Jira](http://jira.xwiki.org) * Email us at [Security mailing-list](mailto:security@xwiki.org)| 
| 20210601T09:37:55Z | CVE-2021-29507 | PoC for exploiting CVE-2021-29507 | https://github.com/JamesGeee/CVE-2021-29507 | | 
| 20210601T09:37:40Z | CVE-2021-29505 | PoC for exploiting CVE-2021-29505 | https://github.com/JamesGeee/CVE-2021-29505 | ### Impact The vulnerability may allow a remote attacker has sufficient rights to execute commands of the host only by manipulating the processed input stream. No user is affected, who followed the recommendation to setup XStream%s security framework with a whitelist limited to the minimal required types. ### Patches If you rely on XStream%s default blacklist of the Security Framework, you will have to use at least version 1.4.17. ### Workarounds See [workarounds](https://x-stream.github.io/security.html#workaround) for the different versions covering all CVEs. ### References See full information about the nature of the vulnerability and the steps to reproduce it in XStream%s documentation for [CVE-2021-xxxxx](https://x-stream.github.io/CVE-2021-xxxxx.html). ### Credits V3geB1rd, white hat hacker from Tencent Security Response Center found and reported the issue to XStream and provided the required information to reproduce it. ### For more information If you have any questions or comments about this advisory: * Open an issue in [XStream](https://github.com/x-stream/xstream/issues) * Email us at [XStream Google Group](https://groups.google.com/group/xstream-user)| 
| 20210601T09:37:36Z | CVE-2021-29492 | PoC for exploiting CVE-2021-29492 | https://github.com/JamesGeee/CVE-2021-29492 | ### Description Envoy does not decode escaped slash sequences `%2F` and `%5C` in HTTP URL paths in versions 1.18.2 and before. A remote attacker may craft a path with escaped slashes, e.g. `/something%2F..%2Fadmin`, to bypass access control, e.g. a block on `/admin`. A backend server could then decode slash sequences and normalize path and provide an attacker access beyond the scope provided for by the access control policy. ### Impact Escalation of Privileges when using RBAC or JWT filters with enforcement based on URL path. Users with back end servers that interpret `%2F` and `/` and `%5C` and `\` interchangeably are impacted. ### Attack Vector URL paths containing escaped slash characters delivered by untrusted client. ### Patches Envoy versions 1.18.3, 1.17.3, 1.16.4, 1.15.5 contain new path normalization option to decode escaped slash characters. ### Workarounds If back end servers treat `%2F` and `/` and `%5C` and `\` interchangeably and a URL path based access control is configured, we recommend reconfiguring back end server to not treat `%2F` and `/` and `%5C` and `\` interchangeably if feasible. ### Credit Ruilin Yang (ruilin.yrl@gmail.com) ### References https://blog.envoyproxy.io https://github.com/envoyproxy/envoy/releases ### For more information If you have any questions or comments about this advisory: * Open an issue in [Envoy repo](https://github.com/envoyproxy/envoy/issues) * Email us at [envoy-security](mailto:envoy-security@googlegroups.com)| 
| 20210601T09:37:32Z | CVE-2020-36375 | PoC for exploiting CVE-2020-36375 | https://github.com/JamesGeee/CVE-2020-36375 | Stack overflow vulnerability in parse_equality Cesanta MJS 1.20.1, allows remote attackers to cause a Denial of Service (DoS) via a crafted file.| 
| 20210601T09:37:29Z | CVE-2020-36374 | PoC for exploiting CVE-2020-36374 | https://github.com/JamesGeee/CVE-2020-36374 | Stack overflow vulnerability in parse_comparison Cesanta MJS 1.20.1, allows remote attackers to cause a Denial of Service (DoS) via a crafted file.| 
| 20210601T09:37:25Z | CVE-2020-36373 | PoC for exploiting CVE-2020-36373 | https://github.com/JamesGeee/CVE-2020-36373 | Stack overflow vulnerability in parse_shifts Cesanta MJS 1.20.1, allows remote attackers to cause a Denial of Service (DoS) via a crafted file.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210601T08:30:57Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1708 | 494| 
| 20210601T02:37:36Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 641 | 15| 
| 20210601T00:42:00Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 10 | 1| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210601T13:07:34Z | Repository for the ICML21 submission: %Exploiting Domain-Specific Features to Enhance Domain Generalization%. | https://github.com/manhhabui/mDSDI | 0 | 0| 
| 20210601T13:05:16Z | A helpful Java Deserialization exploit framework based on ysoserial | https://github.com/wh1t3p1g/ysomap | 383 | 32| 
| 20210601T13:02:49Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 24 | 11| 
| 20210601T12:48:34Z | ExOgonExploit_KeySystem | https://github.com/Nvoth48/ExOgonExploit | 0 | 0| 
| 20210601T11:59:10Z | Experimental Go language CSGO exploit proof-of-concept. | https://github.com/jamesmoriarty/gohack | 21 | 4| 
| 20210601T11:49:05Z | E3C is a freely available multilingual corpus (Italian, English, French, Spanish, and Basque) of semantically annotated clinical narratives to allow for the linguistic analysis, benchmarking, and training of information extraction systems. It consists of two types of annotations: (i) clinical entities: pathologies, symptoms, procedures, body parts, etc., according to standard clinical taxonomies (i.e. SNOMED-CT, ICD-10); and (ii) temporal information and factuality: events, time expressions, and temporal relations according to the THYME standard. The corpus is organised into three layers, with different purposes. Layer 1: about 25K tokens per language with full manual annotation of clinical entities, temporal information and factuality, for benchmarkingand linguistic analysis. Layer 2: 50-100K tokens per language with semi-automatic annotations of clinical entities, to be used to train baseline systems. Layer 3: about 1M tokens per language of non-annotated medical documents to be exploited by semi-supervised approaches. Researchers can use the benchmark training and test splits of our corpus to develop and test their own models. We trained several deep learning based models and provide baselines using the benchmark. Both the corpus and the built models will be available through the ELG platform.  | https://github.com/hltfbk/E3C-Corpus | 0 | 1| 
| 20210601T11:14:43Z |  :cookie: Modern XSS exploitation script. | https://github.com/ShinoNuma/snitchyScript | 0 | 0| 
| 20210601T11:09:01Z | Null | https://github.com/Username132131231/exploit | 0 | 0| 
| 20210601T10:56:40Z | A Go library for manipulating Windows processes. | https://github.com/jamesmoriarty/gomem | 9 | 1| 
| 20210601T10:36:31Z | Null | https://github.com/TheCrazzXz/Exploits-Lab | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210601T12:48:11Z | Supplementary material for the paper %Towards Practical Early-Bird Tickets against Backdoor Attacks% | https://github.com/Anonymous-s-s/supplementary-material | 0 | 0| 
| 20210601T12:34:43Z | This a simple python backdoor/reverse shell/payload for Windows. It contains a lot of features including executing all windows commands, taking screenshot of target machine, etc. | https://github.com/vishnuz1611/Python-Backdoor-Windows | 0 | 0| 
| 20210601T10:41:45Z | Null | https://github.com/huynhquynh-dev/backdoor_python | 0 | 0| 
| 20210601T09:36:36Z | this is advance py39 backdoor created to use in college project | https://github.com/Bhadresh-Malankiya/BackdoorPy3 | 0 | 0| 
| 20210601T09:29:10Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 244 | 42| 
| 20210601T06:09:10Z | PHP Backdoor for Injection your code into site (Useless for encrypted sites) | https://github.com/kotoff-studio/PHPInjectorBackdoor | 0 | 0| 
| 20210601T05:53:49Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 72 | 12| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210601T12:58:36Z | Fuzzy Logic but with Sugeno model for defuzzification | https://github.com/rafiffausta/Fuzzy-Logic-Sugeno-Model | 0 | 0| 
| 20210601T12:41:54Z | A vulnerability fuzzing tool written in bash, it contains the most commonly used tools to perform vulnerability scan | https://github.com/R0X4R/Pinaak | 40 | 5| 
| 20210601T12:19:31Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6344 | 1287| 
| 20210601T12:17:15Z | Coverage-guided, in-process fuzzing for the JVM | https://github.com/CodeIntelligenceTesting/jazzer | 308 | 20| 
| 20210601T12:16:01Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 1783 | 353| 
| 20210601T12:15:19Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 8 | 5| 
| 20210601T11:07:01Z | Null | https://github.com/AlexanderBrese/fuzzy-octo-engine | 0 | 0| 
| 20210601T09:56:59Z | A Pl/Sql fuzzing tool demo | https://github.com/RAMMVIER/PLFuzzer_demo | 1 | 0| 
| 20210601T09:52:27Z | Fuzzer and metamorphic tester for C++ libraries | https://github.com/PollyLabs/library-metamorphic-testing | 1 | 2| 
| 20210601T09:33:50Z | Repository with examples for Fuzzing | https://github.com/mejo1024/Fuzzing-Examples | 0 | 0| 



# 日更新程序
