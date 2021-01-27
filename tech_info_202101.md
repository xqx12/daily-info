# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210126 | Android Pentest: Deep Link Exploitation | https://www.hackingarticles.in/android-pentest-deep-link-exploitation/| 
| 20210126 | Cobalt-Strike 相关的一些工具以及使用 Tips | https://github.com/S1ckB0y1337/Cobalt-Strike-CheatSheet| 
| 20210126 | Fast web fuzzer written in Go | https://github.com/ffuf/ffuf| 
| 20210126 | VisualDoor: SonicWall SSL-VPN Exploit | https://darrenmartyn.ie/2021/01/24/visualdoor-sonicwall-ssl-vpn-exploit/| 
| 20210126 | dnspooq 缓存污染漏洞 Exploit(CVE-2020-25686, CVE-2020-25684, CVE-2020-25685) | https://github.com/knqyf263/dnspooq| 
| 20210126 | Catching Debuggers with Section Hashing | https://malwareandstuff.com/catching-debuggers-with-section-hashing/| 
| 20210126 | Windows 版本 NordVPN 消息 Handler RCE 漏洞分析 | https://hackerone.com/reports/1001255| 
| 20210126 | Google 发 Blog：朝鲜黑客在 Twitter 通过伪装账户社工安全研究员 | https://blog.google/threat-analysis-group/new-campaign-targeting-security-researchers/| 
| 20210126 | Creating Security Decision Trees With Graphviz | https://swagitda.com/blog/posts/security-decision-trees-with-graphviz/| 
| 20210126 | SonicWall厂商调查研究安全移动访问（SMA）100系列硬件中存在的零日漏洞威胁。 | https://threatpost.com/sonicwall-breach-zero-days-in-remote-access/163290/| 
| 20210125 | 用图的理论从日志中挖掘入侵的行为 | https://github.com/grapl-security/grapl| 
| 20210125 | AS_REP Roasting vs Kerberoasting | https://luemmelsec.github.io/Kerberoasting-VS-AS-REP-Roasting/| 
| 20210125 | The Secret Parameter, LFR, and Potential RCE in NodeJS Apps | https://blog.shoebpatel.com/2021/01/23/The-Secret-Parameter-LFR-and-Potential-RCE-in-NodeJS-Apps/| 
| 20210125 | Proxy QUAKE3 VM calls with Frida | https://azurda.github.io/posts/q3vm-hook/| 
| 20210125 | 基于 MSSQL 实现内网的横向渗透 | https://research.nccgroup.com/2021/01/21/mssql-lateral-movement/| 
| 20210125 | 绕过 Google MDM 对 iOS 越狱设备的检测 | https://insinuator.net/2021/01/having-fun-with-google-mdm-solution/| 
| 20210125 | USB 协议核心概念与实践 | https://evilpan.com/2021/01/24/usb-fun/| 
| 20210125 | BugHound - 基于 ElasticSearch 用数据挖掘的方法静态检测软件缺陷 | https://shells.systems/unveiling-bughound-a-static-code-analysis-tool-based-on-elasticsearch/| 
| 20210125 | Windows 7 TCP/IP hijacking | http://blog.pi3.com.pl/?p=850| 
| 20210124 | JavaScript编程学习30天挑战资源项目。 | https://github.com/Asabeneh/30-Days-Of-JavaScript| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210126 | 威胁狩猎：基于ELK的日志监控 | https://www.hetianlab.com/specialized/20210125144554| 
| 20210126 | 浅谈隧道搭建工具之Neo-reGeorg | https://www.anquanke.com/post/id/228917| 
| 20210126 | 宝塔面板Windows版提权方法 | https://github.com/Hzllaga/BT_Panel_Privilege_Escalation| 
| 20210126 | 容器环境定制的渗透测试工具 | https://github.com/cdk-team/CDK/wiki/CDK-Home-CN| 
| 20210126 | 两个有趣的DNS 安全问题研究 | https://xz.aliyun.com/t/9047| 
| 20210126 | Java安全02-从ClassLoader到冰蝎Java篇 | https://xz.aliyun.com/t/9050| 
| 20210126 | JavaWeb中的信息泄漏——H2 database | https://www.sec-in.com/article/827| 
| 20210126 | SSRF安全指北 | https://mp.weixin.qq.com/s/EYVFHgNClgNGrk_92PZ90A| 
| 20210126 | 信创产业：操作系统深度研究（PPT原文） | https://mp.weixin.qq.com/s/fA1xDbQ9qbV1L2AgitFXdw| 
| 20210126 | 全球网络反恐格局中的中国力量 | https://mp.weixin.qq.com/s/1dpbZO_rD4GSfaPqjw5Luw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210127T00:32:30Z | CVE-2021-3156 | Null | https://github.com/mr-r3b00t/CVE-2021-3156 | | 
| 20210126T23:02:27Z | CVE-2020-9484 | Null | https://github.com/AssassinUKG/CVE-2020-9484 | When using Apache Tomcat versions 10.0.0-M1 to 10.0.0-M4, 9.0.0.M1 to 9.0.34, 8.5.0 to 8.5.54 and 7.0.0 to 7.0.103 if a) an attacker is able to control the contents and name of a file on the server; and b) the server is configured to use the PersistenceManager with a FileStore; and c) the PersistenceManager is configured with sessionAttributeValueClassNameFilter=%null% (the default unless a SecurityManager is used) or a sufficiently lax filter to allow the attacker provided object to be deserialized; and d) the attacker knows the relative file path from the storage location used by FileStore to the file the attacker has control over; then, using a specifically crafted request, the attacker will be able to trigger remote code execution via deserialization of the file under their control. Note that all of conditions a) to d) must be true for the attack to succeed.| 
| 20210126T20:57:26Z | CVE-2021-3129 | Laravel debug rce | https://github.com/SNCKER/CVE-2021-3129 | | 
| 20210126T19:30:02Z | CVE-2020-8840 | Null | https://github.com/dpredrag/CVE-2020-8840 | FasterXML jackson-databind 2.0.0 through 2.9.10.2 lacks certain xbean-reflect/JNDI blocking, as demonstrated by org.apache.xbean.propertyeditor.JndiConverter.| 
| 20210126T14:57:51Z | CVE-2020-11851 | Remote Code Execution vulnerability on ArcSight Logger | https://github.com/ch1nghz/CVE-2020-11851 | Arbitrary code execution vulnerability on Micro Focus ArcSight Logger product, affecting all version prior to 7.1.1. The vulnerability could be remotely exploited resulting in the execution of arbitrary code.| 
| 20210126T14:31:14Z | CVE-2020-14883 | 用于对WebLogic(10.3.6.0.0 ;12.1.3.0.0 ;12.2.1.3.0; 12.2.1.4.0 ;14.1.1.0.0)进行验证及利用 | https://github.com/fan1029/CVE-2020-14883EXP | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows high privileged attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 7.2 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H).| 
| 20210125T16:12:02Z | CVE-2021-2109 | CVE-2021-2109 && Weblogic Server RCE via JNDI | https://github.com/Al1ex/CVE-2021-2109 | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows high privileged attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 7.2 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H).| 
| 20210125T13:24:56Z | CVE-2020-28488 | Denial of Service (DoS) - jQuery UI 1.12.1 - Exploit | https://github.com/rafaelcintralopes/CVE-2020-28488 | This affects all versions of package jquery-ui; all versions of package org.fujion.webjars:jquery-ui. When the %dialog% is injected into an HTML tag more than once, the browser and the application may crash.| 
| 20210125T12:55:40Z | CVE-2021-3129 | Null | https://github.com/SecPros-Team/laravel-CVE-2021-3129-EXP | Ignition before 2.5.2, as used in Laravel and other products, allows unauthenticated remote attackers to execute arbitrary code because of insecure usage of file_get_contents() and file_put_contents(). This is exploitable on sites using debug mode with Laravel before 8.4.2.| 
| 20210125T09:23:43Z | CVE-2020-24750 | This is a simple test for Jackson | https://github.com/Al1ex/CVE-2020-24750 | FasterXML jackson-databind 2.x before 2.9.10.6 mishandles the interaction between serialization gadgets and typing, related to com.pastdev.httpcomponents.configuration.JndiConfiguration.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210126T22:28:52Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1617 | 477| 
| 20210126T17:52:40Z | Null | https://github.com/fontworks-fonts/Klee | 332 | 10| 
| 20210126T13:41:16Z | Null | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210125T12:10:58Z | Null | https://github.com/balabeltmimi/kleeandtheirfriendsbutton | 0 | 0| 
| 20210125T09:56:25Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 102 | 6| 
| 20210124T22:00:59Z | Null | https://github.com/kleelab/kleelab.github.io | 0 | 0| 
| 20210124T21:16:02Z | Null | https://github.com/davidtr1037/klee-aaqc | 1 | 0| 
| 20210124T10:20:10Z | PROYECTO FINAL | https://github.com/OscarZavaleta23/KLEE-Symbolic-Execution-Engine- | 0 | 0| 
| 20210124T10:15:50Z | Proyecto final de la materia Lenguajes y Autómatas (COMPILADORES) | https://github.com/Llovas7/Symbolic-Virtual-Machine-Klee | 1 | 0| 
| 20210124T10:13:50Z | https://drive.google.com/file/d/1AeQOD62-VNszgIps0Hg4UinKkgOR52AW/view?usp=drivesdk | https://github.com/Daniel-28lv/klee | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210126T23:21:10Z | Your S2E project management tools. Visit https://s2e.systems/docs to get started. | https://github.com/S2E/s2e-env | 70 | 30| 
| 20210125T15:40:42Z | Null | https://github.com/yuvalkirstain/s2e-coref | 1 | 1| 
| 20210125T06:15:39Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 95 | 22| 
| 20210118T16:24:13Z | Null | https://github.com/sabasabzeh/s2Exercise | 0 | 0| 
| 20210111T14:49:47Z | Convert geojson to s2 region cells in different levels | https://github.com/ponlawat-w/uji_mt-s2encoding | 0 | 0| 
| 20210108T20:19:44Z | Robo Hazel is a robot prototype made using Arduino and WIZnet S2E module to advance industry 4.0 and solve the problem of message delivery. | https://github.com/hamzakhalidhk/RoboHazel | 0 | 0| 
| 20210108T15:14:31Z | Convert geojson to s2 region cells in different levels | https://github.com/ponlawat-w/uji_mt-geojson_s2encoding | 0 | 0| 
| 20210106T02:55:41Z | GUI Configuration tool for WIZnet serial to ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool-GUI | 11 | 7| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210127T01:12:05Z | !!!WORLD%S 🌍 #1🥇 TOR HACKING SUITE!!! Designed to scan and exploit vulnerabilities within Tor hidden services. Vigilante allows most tools to work as normal while resolving .onion  | https://github.com/MBHudson/Vigilante-Toolset | 15 | 7| 
| 20210127T01:10:53Z | Security and Hacking Tools, Exploits, Proof of Concepts, Shellcodes, Scripts. | https://github.com/nullsecuritynet/tools | 1303 | 447| 
| 20210127T01:02:35Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 1 | 3| 
| 20210127T00:49:51Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 7 | 4| 
| 20210127T00:11:47Z | Simple test to call javascript from c# exploiting services.AddNodeServices(); | https://github.com/ducciomugnaini/NodeServices | 0 | 0| 
| 20210127T00:00:21Z | Null | https://github.com/MTK-bypass/exploits_collection | 22 | 13| 
| 20210126T23:55:27Z | Thi powershell script has got to run in remote windows host, even for pivoting | https://github.com/FabioDefilippo/winallenum | 0 | 1| 
| 20210126T23:16:22Z | Null | https://github.com/Rilshrink/mCoreExploit | 0 | 0| 
| 20210126T22:36:37Z | Written in Java and Kotlin, Spring is an Android app that exploits a security vulnerability of an Indian music streaming service, allowing anyone to download any song without subscription or decrypt songs that are saved for offline use by subscribed users of that service. | https://github.com/sajalverma17/Spring | 1 | 0| 
| 20210126T21:59:30Z | I%m not an exploit dev. Just kicking some tires | https://github.com/DarkCasterX/python-virus | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210126T21:02:08Z | A Kotlin program used to analyse and discover backdoors in Minecraft Java 1.12.2 forge mods | https://github.com/Tigermouthbear/Theia | 69 | 8| 
| 20210126T19:34:24Z | Null | https://github.com/jorick93/opdracht_Backdoor | 0 | 0| 
| 20210126T19:28:46Z | Dashboard for conducting Backdoors and Breaches sessions over Zoom. | https://github.com/p3hndrx/B-B-Shuffle | 1 | 0| 
| 20210126T18:40:47Z | shell backdoor | https://github.com/hilmanXcode/shell | 0 | 0| 
| 20210126T15:37:51Z | Null | https://github.com/Shahtr1/reverse_backdoor | 0 | 0| 
| 20210126T15:26:58Z | Null | https://github.com/GoldenPalazzo/docker-backdoor-factory | 0 | 0| 
| 20210126T12:23:18Z | Simple Backdoor Hacking Tool | https://github.com/Mamun-Al-Babu-Shikder/Hacking-Tool | 0 | 0| 
| 20210126T11:36:22Z | Null | https://github.com/rabbitx1337/backdoor | 0 | 0| 
| 20210126T07:29:42Z | Null | https://github.com/Pytools786/backdoor_trojan | 0 | 0| 
| 20210126T06:38:15Z | A backdoor with a multitude of features. | https://github.com/thatcherclough/BetterBackdoor | 188 | 61| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210126T13:24:29Z | 搜索工具类;a searching-utils for what you saved | https://github.com/kc910521/MiniSearch | 4 | 0| 
| 20210126T13:19:13Z | Null | https://github.com/richardvogg/fuzzymatch | 0 | 0| 
| 20210126T13:10:41Z | Using Atheris to fuzz test | https://github.com/ramonmedeiros/fuzz_testing | 0 | 0| 
| 20210126T13:07:10Z | White-box fuzzer for Java bytecode | https://github.com/vorpal-research/kex | 6 | 5| 
| 20210126T12:57:49Z | Null | https://github.com/codesoverflow/fuzzy-search-hi-en-transliterate | 0 | 0| 
| 20210126T12:04:19Z | Null | https://github.com/SubhiJleilaty/FuzzyLogicRobotics-soem | 0 | 0| 
| 20210126T11:56:12Z | Null | https://github.com/Juanosorio94/fuzzing-rdma | 0 | 0| 
| 20210126T11:55:45Z | library for fuzzy search | https://github.com/AlfredDaimari/fuzz-search-js | 0 | 0| 
| 20210126T11:31:19Z | 📨 Email template generator. Making emails fun again. | https://github.com/luangjokaj/fuzzymail | 110 | 4| 
| 20210126T11:04:10Z | Rockyou for web fuzzing | https://github.com/six2dez/OneListForAll | 169 | 31| 



# 日更新程序
