# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210326 | 程序分析（Program Analysis）相关的资料整理 | https://gist.github.com/MattPD/00573ee14bf85ccac6bed3c0678ddbef| 
| 20210326 | systemd-resolved varlink 接口类型混淆漏洞分析 | https://securitylab.github.com/advisories/GHSL-2021-049-systemd-resolved-varlink/| 
| 20210326 | GLib 整数溢出漏洞分析（CVE-2021-27219） | https://securitylab.github.com/advisories/GHSL-2021-045-g_bytes_new/| 
| 20210326 | Microsoft Exchange 漏洞（CVE-2021-26855）在野扫描分析报告 | http://blog.netlab.360.com/microsoft-exchange-vulnerability-cve-2021-26855-scan-analysis/| 
| 20210326 | NetSPI 将之前的 Linux 渗透测试学习环境整合成了一个 Docker | https://blog.netspi.com/dockerizing-the-netspi-linux-labs/| 
| 20210326 | Google 正在推动建立 Android Ready SE 联盟，用于 SE 安全芯片标准的研发 | https://security.googleblog.com/2021/03/announcing-android-ready-se-alliance.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+GoogleOnlineSecurityBlog+%28Google+Online+Security+Blog%29| 
| 20210326 | BITTER APT 组织所使用的 win32k CVE-2021-1732 越界访问漏洞分析 | https://iamelli0t.github.io/2021/03/25/CVE-2021-1732.html| 
| 20210326 | 以实际案例介绍从流量分析的角度发现 APT 攻击线索 | https://igor-blue.github.io/2021/03/24/apt1.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210326 | 浅析软件供应链攻击之包抢注低成本钓鱼 | https://mp.weixin.qq.com/s/JWSjKZWyuSvXdzYhU0INmQ| 
| 20210326 | Kscan：轻量级的资产发现工具 | https://github.com/lcvvvv/kscan| 
| 20210326 | 国内网络安全信息与事件管理类产品研究与测试报告（2021年） | http://www.caict.ac.cn/kxyj/qwfb/ztbg/202103/P020210324512102846900.pdf| 
| 20210326 | 中国网络安全行业全景图（2021年3月第八版） | https://mp.weixin.qq.com/s/Z3rIpxl9ZOVuZzTABAojvg| 
| 20210326 | A Year in the Life of a Compiler Fuzzing Campaign | https://blog.trailofbits.com/2021/03/23/a-year-in-the-life-of-a-compiler-fuzzing-campaign/| 
| 20210326 | 一些网络空间搜索引擎相关的资料 | https://github.com/EXHades/CyberSpaceSearchEngine-Research| 
| 20210326 | 一些webshell免杀的技巧 | https://xz.aliyun.com/t/9290| 
| 20210326 | 蓝队溯源与反制 | https://xz.aliyun.com/t/9316| 
| 20210326 | 记一次跌宕起伏的白盒审计到RCE | https://xz.aliyun.com/t/9319| 
| 20210326 | MSSQL 数据库攻击实战指北—防守方攻略 | https://mp.weixin.qq.com/s/uENvpPan7aVd7MbSoAT9Dg| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210326T12:59:44Z | CVE-2021-21123 | 🐱‍💻 👍 Google Chrome - File System Access API - vulnerabilities reported by Maciej Pulikowski , Total Bug Bounty Reward: $5.000 , CVE-2021-21123 and 5 more... | https://github.com/Puliczek/CVE-2021-21123-PoC-Google-Chrome | Insufficient data validation in File System API in Google Chrome prior to 88.0.4324.96 allowed a remote attacker to bypass filesystem restrictions via a crafted HTML page.| 
| 20210326T12:34:20Z | cve-2021-3449 | CVE-2021-3449 PoC exploit | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210326T10:02:15Z | CVE-2021-22986 | F5 BIG-IP/BIG-IQ iControl Rest API SSRF to RCE | https://github.com/Udyz/CVE-2021-22986-SSRF2RCE | | 
| 20210326T07:54:15Z | cve-2021-22986 | F5 BIG-IP远程代码执行；cve-2021-22986，批量检测；命令执行利用 | https://github.com/yaunsky/CVE-202122986-EXP | 未查询到CVE信息| 
| 20210326T07:49:06Z | CVE-2021-22986 | CVE-2021-22986 & F5 BIG-IP RCE | https://github.com/Al1ex/CVE-2021-22986 | 未查询到CVE信息| 
| 20210326T06:31:29Z | CVE-2021-26295 | Null | https://github.com/yumusb/CVE-2021-26295-POC | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210326T11:59:29Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1653 | 487| 
| 20210326T06:39:17Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 6 | 0| 
| 20210326T05:18:37Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 357 | 9| 
| 20210326T01:51:13Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210326T05:12:52Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 110 | 24| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210326T12:50:32Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 9 | 5| 
| 20210326T12:46:14Z | A tool for embedding XXE/XML exploits into different filetypes | https://github.com/BuffaloWill/oxml_xxe | 794 | 213| 
| 20210326T12:30:46Z | Vulnerability Notes, PoC Exploits and Write-Ups for security issues disclosed by tintinweb | https://github.com/tintinweb/pub | 217 | 122| 
| 20210326T12:02:26Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 13 | 6| 
| 20210326T11:55:11Z | The Browser Exploitation Framework Project | https://github.com/beefproject/beef | 5590 | 1331| 
| 20210326T11:42:51Z | Null | https://github.com/ro-per/VS-Lab2_Memory_Exploits_in_C | 0 | 0| 
| 20210326T11:35:11Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9186 | 1478| 
| 20210326T11:34:15Z | A Collection of Various Discord Bugs, Exploits, Un-Documented Parts of the Discord API, and Other Discord Related Miscellaneous Stuff. | https://github.com/DevEntro/discord-bugs-exploits | 9 | 0| 
| 20210326T11:26:11Z | Modular penetration testing platform that enables you to write, test, and execute exploit code. | https://github.com/EntySec/HatSploit | 23 | 7| 
| 20210326T11:23:01Z | Building upon the Dirichlet-multinomial regression framework, we develop an high-dimensional Bayesian hierarchical model for microbiota analysis that exploits subject-specific regression coefficients to simultaneously borrow strength across districts and include complex interactions between diet and clinical factors if supported by the data.  | https://github.com/mattpedone/subject-specific-dm-reg | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210326T11:20:49Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. Ghost Framework gives you the power and convenience of remote Android device administration. | https://github.com/EntySec/ghost | 1006 | 494| 
| 20210326T08:11:43Z | Simple lua backdoor, Dong, watheck, jayboy  | https://github.com/IncognitoBasePlate/Backdoor-test-for-roblox | 0 | 0| 
| 20210326T07:42:43Z | PCI Express DIY hacking toolkit for Xilinx SP605 | https://github.com/Cr4sh/s6_pcie_microblaze | 303 | 76| 
| 20210326T07:23:48Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) remote administration and post-exploitation tool mainly written in python | https://github.com/n1nj4sec/pupy | 6236 | 1597| 
| 20210326T04:20:48Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 200 | 34| 
| 20210326T04:18:24Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 56 | 9| 
| 20210326T04:00:06Z | Worst Panel/Script | https://github.com/sumsspiffy/worst-wtf | 1 | 0| 
| 20210326T01:11:03Z | Backdoors Framework for Deep Learning and Federated Learning. A light-weight tool to conduct your research on backdoors. | https://github.com/ebagdasa/backdoors101 | 59 | 10| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210326T12:55:50Z | This tool is based on web directory fuzzing. | https://github.com/vivashu27/WebFUZZ | 2 | 0| 
| 20210326T12:51:48Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 263 | 37| 
| 20210326T12:47:50Z | SSL and TLS protocol test suite and fuzzer | https://github.com/tlsfuzzer/tlsfuzzer | 348 | 86| 
| 20210326T12:33:16Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 1| 
| 20210326T12:26:51Z | A differential fuzzer for x86 decoders | https://github.com/trailofbits/mishegos | 139 | 21| 
| 20210326T12:03:09Z | Coverage-guided, in-process fuzzing for the JVM | https://github.com/CodeIntelligenceTesting/jazzer | 264 | 12| 
| 20210326T11:50:28Z | Null | https://github.com/nhsd-exeter/dos-service-fuzzy-search-api | 0 | 0| 
| 20210326T11:25:35Z | PoC of fuzzing closed-source userspace binaries with KVM | https://github.com/klecko/kvm-fuzz | 1 | 0| 
| 20210326T11:11:31Z | Potentially dangerous files | https://github.com/Bo0oM/fuzz.txt | 1387 | 260| 
| 20210326T11:01:23Z | C++/QML simulation of robot movement, which is controlled by fuzzy controller (Simulink). | https://github.com/JWarcholC/mobile-fuzzy-robot | 0 | 0| 



# 日更新程序
