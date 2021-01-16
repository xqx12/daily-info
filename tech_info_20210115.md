# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210115 | 前段时间爆出 Apple 在新版本 macOS 网络防火墙中为自家 App 开绿灯的问题已被解决 | https://www.zdnet.com/article/apple-removes-feature-that-allowed-its-apps-to-bypass-macos-firewalls-and-vpns/| 
| 20210115 | nsjail - Google 开源的一个 Linux 平台进程隔离工具 | https://github.com/google/nsjail| 
| 20210115 | What is IOMMU and how it can be used? | https://blog.3mdeb.com/2021/2021-01-13-iommu/| 
| 20210115 | 利用 VSCode 扩展实现 macOS Post-Exploitation 阶段的代码执行 | https://www.mdsec.co.uk/2021/01/macos-post-exploitation-shenanigans-with-vscode-extensions/| 
| 20210115 | Everything Old is New Again: Binary Security of WebAssembly | https://www.usenix.org/system/files/sec20-lehmann.pdf| 
| 20210115 | PlayStation 4 WebKit IP6_EXTHDR_CHECK Double Free 漏洞 | https://hackerone.com/reports/943231| 
| 20210115 | XNU 内核 Hook 框架，基于 checkra1n pongoOS | https://github.com/jsherman212/xnuspy| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210115 | 2020年勒索病毒疫情分析报告 | http://zt.360.cn/1101061855.php?dtid=1101062360&did=610740603| 
| 20210115 | 初探 Python Flask+Jinja2 SSTI | https://www.anquanke.com/post/id/226900| 
| 20210115 | BORG ：一个快速进化的僵尸网络 | https://security.tencent.com/index.php/blog/msg/175| 
| 20210115 | 通过 OpenVPN 实现流量审计 | https://green-m.me//2021/01/12/audit-traffic-through-openvpn/| 
| 20210115 | SharePoint Rce 系列分析（三） | https://mp.weixin.qq.com/s/Z2hDtlsu0zgKY8YWhDBS7g| 
| 20210115 | SharePoint Rce 系列分析（二） | https://mp.weixin.qq.com/s/ZLSFXUoNNAFxqeiD9RpYZg| 
| 20210115 | 浅谈绕过disable_functions的部分方法的原理 | https://www.anquanke.com/post/id/228712| 
| 20210115 | JSON DataSet for macOS mapped to MITRE ATT&CK Tactics | https://github.com/sbousseaden/macOS-ATTACK-DATASET| 
| 20210115 | Js文件追踪到未授权访问 | https://www.sec-in.com/article/806| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210115T22:27:13Z | CVE-2020-6207 | PoC for CVE-2020-6207  (Missing Authentication Check in SAP Solution Manager) | https://github.com/chipik/SAP_EEM_CVE-2020-6207 | SAP Solution Manager (User Experience Monitoring), version- 7.2, due to Missing Authentication Check does not perform any authentication for a service resulting in complete compromise of all SMDAgents connected to the Solution Manager.| 
| 20210115T19:26:56Z | CVE-2020-7200 | Null | https://github.com/alexfrancow/CVE-2020-7200 | A potential security vulnerability has been identified in HPE Systems Insight Manager (SIM) version 7.6. The vulnerability could be exploited to allow remote code execution.| 
| 20210115T18:12:09Z | CVE-2020-9484 | Apache Tomcat RCE (CVE-2020-9484) | https://github.com/Proxysec/-CVE-2020-9484 | When using Apache Tomcat versions 10.0.0-M1 to 10.0.0-M4, 9.0.0.M1 to 9.0.34, 8.5.0 to 8.5.54 and 7.0.0 to 7.0.103 if a) an attacker is able to control the contents and name of a file on the server; and b) the server is configured to use the PersistenceManager with a FileStore; and c) the PersistenceManager is configured with sessionAttributeValueClassNameFilter=%null% (the default unless a SecurityManager is used) or a sufficiently lax filter to allow the attacker provided object to be deserialized; and d) the attacker knows the relative file path from the storage location used by FileStore to the file the attacker has control over; then, using a specifically crafted request, the attacker will be able to trigger remote code execution via deserialization of the file under their control. Note that all of conditions a) to d) must be true for the attack to succeed.| 
| 20210115T17:59:25Z | CVE-2020-9484 | Apache Tomcat RCE (CVE-2020-9484) | https://github.com/Proxysec/-CVE-2020-9484- | When using Apache Tomcat versions 10.0.0-M1 to 10.0.0-M4, 9.0.0.M1 to 9.0.34, 8.5.0 to 8.5.54 and 7.0.0 to 7.0.103 if a) an attacker is able to control the contents and name of a file on the server; and b) the server is configured to use the PersistenceManager with a FileStore; and c) the PersistenceManager is configured with sessionAttributeValueClassNameFilter=%null% (the default unless a SecurityManager is used) or a sufficiently lax filter to allow the attacker provided object to be deserialized; and d) the attacker knows the relative file path from the storage location used by FileStore to the file the attacker has control over; then, using a specifically crafted request, the attacker will be able to trigger remote code execution via deserialization of the file under their control. Note that all of conditions a) to d) must be true for the attack to succeed.| 
| 20210115T15:12:42Z | CVE-2020-8165 | CVE-2020-8165 exploit automation | https://github.com/macosta-42/CVE-2020-8165 | A deserialization of untrusted data vulnernerability exists in rails < 5.2.4.3, rails < 6.0.3.1 that can allow an attacker to unmarshal user-provided objects in MemCacheStore and RedisCacheStore potentially resulting in an RCE.| 
| 20210115T10:52:00Z | CVE-2020-7961 | Exploit script for CVE-2020-7961 | https://github.com/ShutdownRepo/CVE-2020-7961 | Deserialization of Untrusted Data in Liferay Portal prior to 7.2.1 CE GA2 allows remote attackers to execute arbitrary code via JSON web services (JSONWS).| 
| 20210115T10:09:05Z | CVE-2020-8165 | PoC for CVE-2020-8165 | https://github.com/progfay/CVE-2020-8165 | A deserialization of untrusted data vulnernerability exists in rails < 5.2.4.3, rails < 6.0.3.1 that can allow an attacker to unmarshal user-provided objects in MemCacheStore and RedisCacheStore potentially resulting in an RCE.| 
| 20210115T09:07:12Z | 未知编号 | 2020l4web-campaign-DanCvejn created by GitHub Classroom | https://github.com/pslib-cz/2020l4web-campaign-DanCvejn | 未查询到CVE信息| 
| 20210115T08:59:48Z | CVE-2020-13937 | Apache Kylin API未授权访问漏洞;CVE-2020-13937;Apache Kylin漏洞 | https://github.com/yaunsky/CVE-2020-13937 | Apache Kylin 2.0.0, 2.1.0, 2.2.0, 2.3.0, 2.3.1, 2.3.2, 2.4.0, 2.4.1, 2.5.0, 2.5.1, 2.5.2, 2.6.0, 2.6.1, 2.6.2, 2.6.3, 2.6.4, 2.6.5, 2.6.6, 3.0.0-alpha, 3.0.0-alpha2, 3.0.0-beta, 3.0.0, 3.0.1, 3.0.2, 3.1.0, 4.0.0-alpha has one restful api which exposed Kylin%s configuration information without any authentication, so it is dangerous because some confidential information entries will be disclosed to everyone.| 
| 20210115T05:09:03Z | CVE-2020-27368 | SKYWORTH GN542VF Hardware Version 2.0 and Software Version 2.0.0.16 Directory Indexing Vulnerability | https://github.com/swzhouu/CVE-2020-27368 | Directory Indexing in Login Portal of Login Portal of TOTOLINK-A702R-V1.0.0-B20161227.1023 allows attacker to access /icons/ directories via GET Parameter.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210115T14:31:53Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 101 | 6| 
| 20210115T09:26:05Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1602 | 477| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210115T23:43:24Z | random stuff for exploit dev practice | https://github.com/C-Brown/exploit_dev_practice | 0 | 0| 
| 20210115T23:36:57Z | A python package built by zachkaupp for use in various CTFs | https://github.com/zachkaupp/exploit_pack | 0 | 0| 
| 20210115T23:23:57Z | Xiongmai Exploitation Toolkit | https://github.com/redcodefinal/xet | 3 | 0| 
| 20210115T22:49:12Z | Null | https://github.com/shmueluzan/Exploit | 0 | 0| 
| 20210115T21:26:29Z | This is a roblox exploit I made, simply download an extract the zip file and open the main exe file | https://github.com/Avrxsted/AcidFlow-LUA-Executor- | 0 | 0| 
| 20210115T21:09:27Z | this is a mass exploit by following the latest 0day update | https://github.com/justakazh/LazyXploit | 0 | 0| 
| 20210115T21:00:47Z | Null | https://github.com/aaronyan0328/Bandits-and-Exploration-Exploitation | 0 | 0| 
| 20210115T20:55:23Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 8893 | 1410| 
| 20210115T20:48:16Z | Router Exploitation Tools. Checks for WinBox Authentication Bypass Disclosure, RouterOS Jailbreak, Chimney-Blue SMB BufferOverflow & ByTheWay RCE | https://github.com/s1l3nt78/MkCheck | 57 | 16| 
| 20210115T20:29:05Z | A phased, evasive Path Traversal + LFI scanning & exploitation tool in Python | https://github.com/VainlyStrain/Vailyn | 85 | 2| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210115T21:34:16Z | Tool to find potential backdoor/security holes in your endpoint | https://github.com/subasgit/backdoorfinder | 1 | 0| 
| 20210115T21:10:46Z | Allows full access to the target system | https://github.com/maurya-bitlegacy/reverse-backdoor | 0 | 0| 
| 20210115T15:16:09Z | Null | https://github.com/EjHvorSerDuVildUdJim/backdoor | 0 | 0| 
| 20210115T14:23:53Z | Null | https://github.com/Wiilldd/backdoor | 0 | 0| 
| 20210115T14:01:02Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 148 | 22| 
| 20210115T13:13:45Z | a python backdoor with a lot of features | https://github.com/zenux-dev/backdoor | 0 | 0| 
| 20210115T10:07:34Z | Null | https://github.com/rabbitx1337/backdoor | 0 | 0| 
| 20210115T09:05:22Z | Backdoors Framework for Deep Learning and Federated Learning. A light-weight tool to conduct your research on backdoors. | https://github.com/ebagdasa/backdoors101 | 45 | 8| 
| 20210115T02:20:44Z | Null | https://github.com/SEUEvan/Backdoor_NLP | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210115T23:33:33Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 5793 | 1159| 
| 20210115T23:10:19Z | Thesis Dissertation | https://github.com/mchara01/webFuzz_Thesis | 0 | 0| 
| 20210115T23:06:17Z | A fork and successor of the Sulley Fuzzing Framework | https://github.com/jtpereyda/boofuzz | 1136 | 233| 
| 20210115T22:50:09Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 230 | 31| 
| 20210115T22:30:30Z | Fuzzy matching publications for fatcat (wip). | https://github.com/miku/fuzzycat | 1 | 1| 
| 20210115T21:17:22Z | {golang, ptrace, snapshot}-based fuzzer | https://github.com/geeksonsecurity/snapandgo | 0 | 0| 
| 20210115T21:11:37Z | Bazel Starlark extensions for defining fuzz tests in Bazel projects | https://github.com/bazelbuild/rules_fuzzing | 8 | 2| 
| 20210115T21:09:52Z | MQTT service for intent recognition with fuzzywuzzy using the Hermes protocol | https://github.com/rhasspy/rhasspy-fuzzywuzzy-hermes | 0 | 1| 
| 20210115T21:09:49Z | Intent recognition library for Rhasspy using fuzzywuzzy | https://github.com/rhasspy/rhasspy-fuzzywuzzy | 0 | 3| 
| 20210115T20:43:15Z | Null | https://github.com/TimArnettThales/FuzzyAsteroids | 0 | 0| 



# 日更新程序
