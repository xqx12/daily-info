# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221219 | 条件竞争导致的macOS本地提权漏洞（CVE-2022-46689）细节及POC。 | http://securityonline.info/cve-2022-46689-poc-macos-privilege-escalation-vulnerability/| 
| 20221219 | 如何基于PostMessage配置问题，在Google Docs域上发现一个XSS漏洞。 | http://blog.geekycat.in/google-vrp-hijacking-your-screenshots/| 
| 20221219 | 开源工具 laZzzy 实现了多种常见的 Shellcode 执行和混淆技术 | https://www.kitploit.com/2022/12/lazzzy-shellcode-loader-developed-using.html| 
| 20221219 | 关于敏感资源权限设置不当产生的漏洞模式，如CVE-2022-29527，aws中对于sudoers文件权限设置不当漏洞 | https://cwe.mitre.org/data/definitions/732.html| 
| 20221219 | Apache Dubbo Hession反序列化漏洞的利用，引用了一篇使用ByteCodeDL寻找CTF题目利用链的文章，ByteCodeDL是一个类似CodeQL的声明式静态分析工具，优势是支持直接分析字节码 | https://xz.aliyun.com/t/11961| 
| 20221219 | 使用ChatGPT对CVE-2022-23093（FreeBSD ping 栈溢出漏洞）进行补丁分析 | https://www.youtube.com/watch?v=bkkVClq9aGw| 
| 20221218 | mandiant发布关于签名恶意驱动程序的狩猎与分析 | https://www.mandiant.com/resources/blog/hunting-attestation-signed-malware| 
| 20221218 | HTB: Support 通关 Writeup | https://0xdf.gitlab.io/2022/12/17/htb-support.html| 
| 20221218 | 在KPTI enable的情况下，用户态的页表仍然有entry_SYSCALL_64 的mapping。由于entry_SYSCALL_64的地址与内核基地址之间的offset固定，因此攻击者可以通过频繁调用系统调用来将entry_SYSCALL_64送入TLB，并使用prefetch侧信道泄漏内核基地址。 | http://seclists.org/oss-sec/2022/q4/198| 
| 20221216 | 一个利用文件包含漏洞的教程 | https://infosecwriteups.com/how-to-exploit-file-inclusion-vulnerabilities-a-beginners-introduction-stackzero-a55267b5fafb?gi=79d58db6233c&source=rss----7b722bfd1b8d---4| 
| 20221216 | Foxit PDF Reader UAF漏洞分析和RCE利用。 | http://hacksys.io/blogs/foxit-reader-uaf-rce-jit-spraying-cve-2022-28672| 
| 20221216 | 一个讲文件格式hacking的PPT，比如如何构造一个同时是图片和Jar的文件 | https://speakerdeck.com/ange/technical-challenges-with-file-formats| 
| 20221216 | 一个APIKey的数据集，标记了市面上常见API厂商的APIkey的正则，这个数据集还附带一个小工具：输入一个APIKey，通过正则匹配获取这个APIKey可能属于的API厂商。 | https://github.com/daffainfo/all-about-apikey| 
| 20221216 | CVE-2022-45451：ngscan驱动访问控制实现缺陷，攻击者可利用该漏洞实现任意文件读取以及敏感注册表项修改 | https://github.com/alfarom256/CVE-2022-45451| 
| 20221216 | Team82团队发现并利用 CVE-2022-1361 SQLi漏洞的详情。在研究过程中发现一种利用数据库JSON特性来绕过WAF中常用的SQL语法黑名单的攻击手法，并在多款WAF上发现了这一问题，最终也将该方法加入到最新版本的SQLMap工具中。 | http://okt.to/2Nm4F9| 
| 20221216 | 提供了CVE-2022-41050的POC，影响Windows 8及以上版本，且易于利用 | http://ssd-disclosure.com/win32k-user-mode-printer-drivers-startdoc-uaf/| 
| 20221215 | BSL2022关于如何在windows下使用rootkits进行进程隐藏等恶意行为的演讲视频 | https://www.youtube.com/watch?v=GM9WQMrSkWk&feature=youtu.be| 
| 20221215 | Linux 内核蓝牙模块 ”net/bluetooth/l2cap_core.c“ 中的 l2cap_parse_conf_req 函数存在信息泄露漏洞，可远程泄露内核指针 | http://seclists.org/oss-sec/2022/q4/190| 
| 20221215 | Ruby on Rails 的 Rails::Html::SafeListSanitizer 过滤器中某些 tag 可被绕过，可导致 XSS 攻击 | https://hackerone.com/reports/1656627| 
| 20221215 | 对抗入侵检测，DEFCON 30 workshop 混淆入门课 | https://www.youtube.com/watch?v=wvKwk1wcXvM| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221219 | 静态程序分析框架“太阿”的设计之道 | https://www.bilibili.com/video/BV1XP4y1S7cP/| 
| 20221219 | 2022 年 Recorded Future C&C 服务器跟踪报告 | https://mp.weixin.qq.com/s/aJTcub12byRW3JmcKBm-Bg| 
| 20221216 | DarkAngel: 一款全自动白帽漏洞扫描器 | https://github.com/Bywalks/DarkAngel| 
| 20221216 | Project Achilles：使用 RNN 对 Java 源代码进行静态漏洞检测... | https://mp.weixin.qq.com/s/U0sZwPc5otIg1-amv12BEg| 
| 20221215 | 杀伤链视域下的算法战审思 | https://mp.weixin.qq.com/s/9rvZVolcyZ3R8-ZWQvRgAA| 
| 20221215 | EMS：试验数据驱动的高效变异模糊测试系统 | https://mp.weixin.qq.com/s/vb1Gq8B55y-sTom06hqUfA| 
| 20221215 | 电力行业网络安全等级保护管理办法 | https://mp.weixin.qq.com/s/9IgOGdBKS0a2d778cVRZGA| 
| 20221215 | 全量安全资产管理-进阶实践 | https://mp.weixin.qq.com/s/b8W-FtTy4B8cGtPfp_2uRw| 
| 20221214 | SPEL注入流程分析及CTF中如何使用 | https://sec-in.com/article/1988| 
| 20221213 | uuWAF: 免费、高性能、高扩展开源WAF | https://github.com/Safe3/uuWAF| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20221219T13:36:11Z | CVE-2022-28672 | Foxit PDF Reader Remote Code Execution Exploit | https://github.com/hacksysteam/CVE-2022-28672 | | 
| 20221219T11:22:56Z | CVE-2022-45451 | PoC for Acronis Arbitrary File Read - CVE-2022-45451 | https://github.com/alfarom256/CVE-2022-45451 | | 
| 20221219T10:10:54Z | CVE-2022-44215 | Null | https://github.com/wh-gov/CVE-2022-44215 | | 
| 20221219T09:34:49Z | CVE-2022-44215 | Public disclosure of TitanFTP 19.X Open Redirection vulnerability | https://github.com/JBalanza/CVE-2022-44215 | | 
| 20221219T07:02:25Z | CVE-2020-17382 | The MSI AmbientLink MsIo64 driver 1.0.0.8 has a Buffer Overflow (0x80102040, 0x80102044, 0x80102050,and 0x80102054). | https://github.com/Exploitables/CVE-2020-17382 | | 
| 20221219T06:10:11Z | CVE-2022-0847 | Dirty Pipe - CVE-2022-0847 | https://github.com/tmoneypenny/CVE-2022-0847 | | 
| 20221219T05:25:40Z | CVE-2022-43680 | Null | https://github.com/nidhihcl/external_expat_2.1.0_CVE-2022-43680 | | 
| 20221218T19:52:22Z | CVE-2021-34527 | PrintNightmare (CVE-2021-34527) PoC Exploit | https://github.com/m8sec/CVE-2021-34527 | | 
| 20221218T10:49:59Z | CVE-2020-2555 | Weblogic com.tangosol.util.extractor.ReflectionExtractor RCE | https://github.com/Y4er/CVE-2020-2555 | | 
| 20221218T08:03:14Z | CVE-2022-29464 | Null | https://github.com/devengpk/CVE-2022-29464 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221219T12:18:44Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2126 | 603| 
| 20221219T12:18:36Z | Null | https://github.com/kleeblattdev/kleeblattdev-html_codeflow_lev1_3_ol-ul | 0 | 0| 
| 20221219T10:21:24Z | Null | https://github.com/KleePaimon/KleePaimon.github.io | 1 | 0| 
| 20221219T03:56:34Z | Collection of Kicad 6.0 symbols, footprints and 3D models useful in keyboard creation | https://github.com/crides/kleeb | 53 | 3| 
| 20221218T10:37:00Z | Minecraft Mod. Allows breaking only one half of a double slab block. | https://github.com/TwelveIterationMods/KleeSlabs | 11 | 6| 
| 20221218T10:11:47Z | Null | https://github.com/KleePaimon/KleePaimon.github.io1 | 0 | 0| 
| 20221217T19:10:11Z | Config files for my GitHub profile. | https://github.com/Kleemer/Kleemer | 0 | 0| 
| 20221216T19:37:55Z | klee44 | https://github.com/klee718/klee44 | 0 | 0| 
| 20221215T11:56:52Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 268 | 50| 
| 20221215T01:34:21Z | my hexo blog | https://github.com/kleeper914/kleeper914.github.io | 1 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221219T02:36:14Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 279 | 66| 
| 20221218T05:38:25Z | Spacecraft Simulation Environment Core codes | https://github.com/ut-issl/s2e-core | 26 | 7| 
| 20221214T12:59:07Z | s2e-user | https://github.com/kai0722/s2e-user | 0 | 0| 
| 20221214T11:33:42Z | The Chef symbolic execution platform, based off S2E | https://github.com/dslab-epfl/chef | 7 | 2| 
| 20221213T06:33:44Z | GUI Configuration tool for WIZnet serial to ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool-GUI | 17 | 9| 
| 20221212T05:54:12Z | Documents for Spacecraft Simulation Environment | https://github.com/ut-issl/s2e-documents | 6 | 6| 
| 20221205T08:13:33Z | Your S2E project management tools. Visit https://s2e.systems/docs to get started. | https://github.com/S2E/s2e-env | 84 | 45| 
| 20221204T02:10:12Z | S2E user side repository for Formation Flying study | https://github.com/ut-issl/s2e-ff | 3 | 1| 
| 20221201T07:39:12Z | S2erial_TcpServer_Long | https://github.com/liukai007/S2erial_TcpServer_Long | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221219T13:41:16Z | Tutorial Deface, Download shell backdoor, exploit lainnya | https://github.com/bellpwn/netxploit | 1 | 0| 
| 20221219T13:27:18Z | The Browser Exploitation Framework Project | https://github.com/beefproject/beef | 7953 | 1839| 
| 20221219T12:49:20Z | Null | https://github.com/Skelian/ScriptExploitationAD | 0 | 0| 
| 20221219T12:11:18Z | Kameleon PS4 9.00FW Manual Exploit Host | https://github.com/kmeps4/900manual | 2 | 0| 
| 20221219T11:54:47Z | A repository for folow-along projects, excerpted from the book `Hacking: The Art of Exploitation` | https://github.com/1emvr/The-Art-of-Exploitation | 0 | 0| 
| 20221219T11:16:18Z | This project aims to further your knowledge in the world of elf-like binary exploitation in in i386 system | https://github.com/alas42/rainfall | 0 | 0| 
| 20221219T10:51:32Z | ertertert | https://github.com/Kirromn3/Exploit-2 | 0 | 0| 
| 20221219T09:54:07Z | 聚合Github上已有的Poc或者Exp，CVE信息来自CVE官网。Auto Collect Poc Or Exp from Github by CVE ID. | https://github.com/ycdxsb/PocOrExp_in_Github | 562 | 147| 
| 20221219T09:25:31Z | Project for secure software _Exploit stack overflow  | https://github.com/xdxxxdx/OVS_Secure-software_2016 | 0 | 0| 
| 20221219T03:15:33Z | This repository is primarily maintained by Omar Santos (@santosomar) and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 12462 | 2139| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221219T13:41:16Z | Tutorial Deface, Download shell backdoor, exploit lainnya | https://github.com/bellpwn/netxploit | 1 | 0| 
| 20221219T13:40:03Z | Venom is a library that meant to perform evasive communication using stolen browser socket | https://github.com/Idov31/Venom | 188 | 21| 
| 20221219T12:30:16Z | hiphp - free & open source project for create a BackDoor to control PHP-based sites. 🚪🔑🙂 | https://github.com/yasserbdj96/hiphp | 25 | 9| 
| 20221219T06:20:39Z | Null | https://github.com/0xn4utilus/backdoor22 | 0 | 0| 
| 20221219T04:45:23Z | Esta script es para enviarle a la victima el archivo php.sh que se encuentra en este repositorio , ya que la script es un backdoor php que esta configurado para el archivo index.php , por eso tienen que crear el archivo index desde el repositorio PHPloit ya que el index.php tambien se le enviara a la victima.. | https://github.com/MRX90902WX/Hack | 0 | 0| 
| 20221219T03:27:03Z | Null | https://github.com/Anonimo055x/Backdoor-Clion-Ransonware-8 | 0 | 0| 
| 20221218T20:34:07Z | Null | https://github.com/guowei-cn/video_classification_backdoor_attack | 0 | 0| 
| 20221218T17:04:40Z | Null | https://github.com/ShibuShivansh40/Python-Backdoor | 0 | 0| 
| 20221218T11:21:03Z | Villain is a Windows & Linux backdoor generator and multi-session handler that allows users to connect with sibling servers (other machines running Villain) and share their backdoor sessions, handy for working as a team. | https://github.com/t3l3machus/Villain | 1929 | 329| 
| 20221218T09:40:09Z | Null | https://github.com/AliSeg25/Backdoor | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221219T12:18:44Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2126 | 603| 
| 20221219T08:34:35Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3247 | 457| 
| 20221219T03:53:30Z | Optik is a set of symbolic execution tools that assist smart-contract fuzzers | https://github.com/crytic/optik | 49 | 7| 
| 20221218T17:17:28Z | Open-source symbolic execution framework: https://maat.re | https://github.com/trailofbits/maat | 522 | 30| 
| 20221218T02:04:26Z | Symbolic Execution Over Processor Traces | https://github.com/carter-yagemann/ARCUS | 82 | 17| 
| 20221217T01:12:34Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 602 | 111| 
| 20221215T14:00:21Z | Symbolic execution engine written for the OOX language | https://github.com/tjausm/Jip | 0 | 0| 
| 20221214T23:23:44Z | Use angr in Ghidra | https://github.com/Nalen98/AngryGhidra | 410 | 37| 
| 20221214T23:18:16Z | Compiled Sail ISA snapshots for the Isla symbolic execution tool | https://github.com/rems-project/isla-snapshots | 1 | 1| 
| 20221214T23:10:42Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 25 | 5| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221219T01:54:46Z | A curated list of Meachine learning Security & Privacy papers published in security top-4 conferences (IEEE S&P, ACM CCS, USENIX Security and NDSS). | https://github.com/gnipping/Awesome-ML-SP-Papers | 23 | 2| 
| 20221215T16:22:48Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 65 | 15| 
| 20221212T19:19:12Z | Dynamic Proof of Retrievability using Verifiable Computation and Error Correction Code (NDSS%23) | https://github.com/vt-asaplab/porla | 2 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221219T11:59:31Z | Ethereum smart contract fuzzer | https://github.com/crytic/echidna | 1823 | 239| 
| 20221219T11:57:31Z | Null | https://github.com/PrabhjotSembhi/fuzzy-memory | 0 | 0| 
| 20221219T10:35:17Z | Null | https://github.com/SteeKsi/i-only-need-to-know-a-few-things-about-fuzzy-logic-to-proves-things-with-it | 0 | 0| 
| 20221219T10:34:50Z | Null | https://github.com/SteeKsi/it-may-only-be-a-coincidence-that-the-numbers-of-fuzzy-logic-are-also-the-same-thing-as-normalized- | 0 | 0| 
| 20221219T10:34:08Z | Null | https://github.com/SteeKsi/if-fuzzy-logic-is-real-numbers-it-is-a-way-to-use-logic-with-normalized-floating-point-to-me | 0 | 0| 
| 20221219T09:47:01Z | Null | https://github.com/mostafanassr2000/FuzzyLogic | 0 | 0| 
| 20221219T09:12:52Z | Binary, coverage-guided fuzzer for Windows and macOS | https://github.com/googleprojectzero/Jackalope | 792 | 95| 
| 20221219T02:48:02Z | Import a repository  | https://github.com/cloudflare-wangler/fuzzy-doodle | 0 | 0| 
| 20221219T01:44:54Z | What is this | https://github.com/Mehrdadmehrdadian/fuzzy-octo-waffle | 0 | 0| 
| 20221218T23:45:46Z | Custom Scripts write on Python for scaning, fuzzing, enumeration, etc... | https://github.com/RobertMuriel/Python_Scripts_Pentesting | 0 | 0| 



# 日更新程序
