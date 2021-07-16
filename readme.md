# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210715 | 卡巴斯基对 LuminousMoth APT 组织攻击活动的分析 | https://securelist.com/apt-luminousmoth/103332/| 
| 20210715 | Issue 2182: XNU network stack kernel heap overflow due to out-of-bounds memmove in 6lowpan | https://bugs.chromium.org/p/project-zero/issues/detail?id=2182| 
| 20210715 | Chrome 94 版本将支持 HTTPS-First 模式，进一步推动长尾网站对 HTTPS 的支持 | https://blog.chromium.org/2021/07/increasing-https-adoption.html| 
| 20210715 | 利用 r2 和 Frida 挖掘成人玩具 Satisfyer 的认证绕过漏洞 | https://bananamafia.dev/post/satisfyer/| 
| 20210715 | 利用一个存在 15 年的 Linux Netfilter 的漏洞绕过系统所有的缓解措施实现内核代码执行（CVE-2021-22555） | https://google.github.io/security-research/pocs/linux/cve-2021-22555/writeup.html| 
| 20210715 | 搭建环境，Fuzz grub bootloader | https://sthbrx.github.io/blog/2021/06/14/fuzzing-grub-part-2-going-faster/| 
| 20210715 | CVE-2021-1879: Use-After-Free in QuickTimePluginReplacement | https://googleprojectzero.github.io/0days-in-the-wild/0day-RCAs/2021/CVE-2021-1879.html| 
| 20210715 | Lenovo ThinkPad 笔记本固件 SMM 代码执行漏洞分析（CVE-2021-3452） | https://github.com/binarly-io/Vulnerability-REsearch/blob/main/Lenovo/BRLY-2021-001.md| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210715 | Elkeid-RASP：基于主机的入侵检测解决方案 | https://mp.weixin.qq.com/s/o0rSOLQ34-Ph0aY-_5tfSA| 
| 20210715 | 人工智能赋能网络攻击的安全威胁及应对策略 | http://www.engineering.org.cn/ch/10.15302/J-SSCAE-2021.03.002| 
| 20210715 | On the (Un)Reliability of Privacy Policies in Android Apps | https://mp.weixin.qq.com/s/c3BRmlYnbCQjPS48LIUEzg| 
| 20210715 | 手把手教你搭建一个无框架埋点体系 | https://mp.weixin.qq.com/s/QanYnjRN5TM_NlJtQzCALg| 
| 20210715 | D3FEND学习笔记 | https://mp.weixin.qq.com/s/WsCgI6ilaGL8XJPUJUTCdQ| 
| 20210715 | Active Directory 证书服务快速防御指南 | https://mp.weixin.qq.com/s/XTl9WkdZwCKke_0tLOUr2w| 
| 20210715 | office病毒分析资料整理 | https://mp.weixin.qq.com/s/4YQ-wbzM0mCLOiUad5wpNg| 
| 20210715 | 自由与使命汇报ppt | https://mp.weixin.qq.com/s/I_HmTHao2uaoB35C1aJmGQ| 
| 20210715 | 30万篇外媒疫情新闻数据集介绍 | https://mp.weixin.qq.com/s/VQdHQnHnWhHrE-Ze_W9meA| 
| 20210715 | 更适应DevOps的被动式漏洞检测产品技术研究及架构设计 | https://www.freebuf.com/articles/es/280227.html| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210715T21:05:12Z | CVE-2021-1675 | C# and Impacket implementation of PrintNightmare CVE-2021-1675/CVE-2021-34527 | https://github.com/cube0x0/CVE-2021-1675 | Windows Print Spooler Elevation of Privilege Vulnerability| 
| 20210715T19:00:32Z | CVE-2020-14343 | Experimenting with the CVE-2020-14343 PyYAML vulnerability | https://github.com/raul23/pyyaml-CVE-2020-14343 | A vulnerability was discovered in the PyYAML library in versions before 5.4, where it is susceptible to arbitrary code execution when it processes untrusted YAML files through the full_load method or with the FullLoader loader. Applications that use the library to process untrusted input may be vulnerable to this flaw. This flaw allows an attacker to execute arbitrary code on the system by abusing the python/object/new constructor. This flaw is due to an incomplete fix for CVE-2020-1747.| 
| 20210715T14:13:12Z | CVE-2020-1938 | Scanner for CVE-2020-1938 | https://github.com/yukiNeko114514/CVE-2020-1938 | When using the Apache JServ Protocol (AJP), care must be taken when trusting incoming connections to Apache Tomcat. Tomcat treats AJP connections as having higher trust than, for example, a similar HTTP connection. If such connections are available to an attacker, they can be exploited in ways that may be surprising. In Apache Tomcat 9.0.0.M1 to 9.0.0.30, 8.5.0 to 8.5.50 and 7.0.0 to 7.0.99, Tomcat shipped with an AJP Connector enabled by default that listened on all configured IP addresses. It was expected (and recommended in the security guide) that this Connector would be disabled if not required. This vulnerability report identified a mechanism that allowed: - returning arbitrary files from anywhere in the web application - processing any file in the web application as a JSP Further, if the web application allowed file upload and stored those files within the web application (or the attacker was able to control the content of the web application by some other means) then this, along with the ability to process a file as a JSP, made remote code execution possible. It is important to note that mitigation is only required if an AJP port is accessible to untrusted users. Users wishing to take a defence-in-depth approach and block the vector that permits returning arbitrary files and execution as JSP may upgrade to Apache Tomcat 9.0.31, 8.5.51 or 7.0.100 or later. A number of changes were made to the default AJP Connector configuration in 9.0.31 to harden the default configuration. It is likely that users upgrading to 9.0.31, 8.5.51 or 7.0.100 or later will need to make small changes to their configurations.| 
| 20210715T13:43:37Z | CVE-2021-22893 | Proof-of-Concept (PoC) script to exploit Pulse Secure CVE-2021-22893.  | https://github.com/ZephrFish/CVE-2021-22893 | Pulse Connect Secure 9.0R3/9.1R1 and higher is vulnerable to an authentication bypass vulnerability exposed by the Windows File Share Browser and Pulse Secure Collaboration features of Pulse Connect Secure that can allow an unauthenticated user to perform remote arbitrary code execution on the Pulse Connect Secure gateway. This vulnerability has been exploited in the wild.| 
| 20210715T12:54:05Z | cve-2021-22555 | Null | https://github.com/JoneyJunior/cve-2021-22555 | A heap out-of-bounds write affecting Linux since v2.6.19-rc1 was discovered in net/netfilter/x_tables.c. This allows an attacker to gain privileges or cause a DoS (via heap memory corruption) through user name space| 
| 20210715T04:38:43Z | CVE-2021-26690 | Null | https://github.com/fkm75P8YjLkb/CVE-2021-26690 | Apache HTTP Server versions 2.4.0 to 2.4.46 A specially crafted Cookie header handled by mod_session can cause a NULL pointer dereference and crash, leading to a possible Denial Of Service| 
| 20210715T04:37:58Z | CVE-2021-26691 | Null | https://github.com/fkm75P8YjLkb/CVE-2021-26691 | In Apache HTTP Server versions 2.4.0 to 2.4.46 a specially crafted SessionHeader sent by an origin server could cause a heap overflow| 
| 20210715T04:31:58Z | CVE-2021-30641 | Null | https://github.com/fkm75P8YjLkb/CVE-2021-30641 | Apache HTTP Server versions 2.4.39 to 2.4.46 Unexpected matching behavior with %MergeSlashes OFF%| 
| 20210715T04:29:56Z | CVE-2021-3516 | Null | https://github.com/fkm75P8YjLkb/CVE-2021-3516 | There%s a flaw in libxml2%s xmllint in versions before 2.9.11. An attacker who is able to submit a crafted file to be processed by xmllint could trigger a use-after-free. The greatest impact of this flaw is to confidentiality, integrity, and availability.| 
| 20210715T04:23:58Z | CVE-2021-34496 | Null | https://github.com/fkm75P8YjLkb/CVE-2021-34496 | Windows GDI Information Disclosure Vulnerability| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210715T20:10:31Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 162 | 15| 
| 20210715T08:44:22Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1730 | 498| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210715T23:49:35Z | Null | https://github.com/Whomever0/exploit-scripts | 0 | 0| 
| 20210715T23:47:26Z | Roblox exploit DLL using the LBI execution method | https://github.com/deaddlocust/LBI-Base | 11 | 0| 
| 20210715T23:21:15Z | Null | https://github.com/TheCrazzXz/Exploits-Lab | 0 | 0| 
| 20210715T23:15:00Z | Synapse CLI is an open source project that uses the Synapse X console functions aiming to provide a command-line-like interface for Roblox exploiting. | https://github.com/Remfly/synapse-cli | 1 | 0| 
| 20210715T23:14:41Z | Null | https://github.com/deaddlocust/chsarp-print-exploit | 0 | 0| 
| 20210715T23:11:34Z | Null | https://github.com/3hydraking/Windows-Exploit-Suggester-Python3 | 0 | 0| 
| 20210715T22:12:53Z | Null | https://github.com/HubExploit/HubExploit | 0 | 0| 
| 20210715T21:35:14Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9712 | 1599| 
| 20210715T21:22:58Z | A private Da Hood exploit script | https://github.com/iamtryingtofindname/Artemis | 0 | 0| 
| 20210715T21:11:11Z | Purple Fox Plus Stealer, Purple Fox Plus Stealer, all chromium and gecko based browser and many more features. serverless stealer. | https://github.com/exploitblizzard/PurpleFoxPlus-Stealer | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210715T23:56:24Z | A collection of python written hacking tools consisting of network scanner, arp spoofer and detector, dns spoofer, code injector, packet sniffer, network jammer, email sender, downloader, wireless password harvester credential harvester, keylogger, download&execute, and reverse_backdoor. | https://github.com/dmdhrumilmistry/pyhtools | 1 | 1| 
| 20210715T23:43:30Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 212 | 40| 
| 20210715T22:24:49Z | Windows C2 and Backdoor Training | https://github.com/1nt3rc3pt0r/WinBack | 0 | 0| 
| 20210715T19:01:13Z | A Python module for building botnet ,backdoor or trojan with Telegram control panel | https://github.com/onionj/pybotnet | 7 | 4| 
| 20210715T17:30:18Z | This is a backdoor with shell and persistence to run on the victim computer. It is obviously detected by anti-virus as its not obfuscated or packed. Feel free to play with the code and create what you want. | https://github.com/Calastrophe/C-Backdoor | 0 | 0| 
| 20210715T16:28:38Z | The best backdoor scanner there is. | https://github.com/iK4oS/backdoor.exe | 1 | 1| 
| 20210715T16:26:30Z | Null | https://github.com/iK4oS/PremiumBackdoor.exe | 0 | 1| 
| 20210715T11:51:50Z | A batch script for taking information. A bit overdeveloped, and kind of useless. | https://github.com/Takaovi/BatchStealer | 8 | 2| 
| 20210715T09:00:49Z | Null | https://github.com/FierzaEriez/Mini-Shell-Backdoor | 1 | 0| 
| 20210715T01:13:37Z | A python backdoor | https://github.com/FelipeDosAnjos/HarpiaBackdoor | 1 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210715T20:28:45Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 149 | 33| 
| 20210715T19:29:21Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 442 | 67| 
| 20210715T10:36:51Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 14 | 3| 
| 20210715T10:16:18Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2386 | 351| 
| 20210715T08:44:22Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1730 | 498| 
| 20210715T02:20:12Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1839 | 386| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210715T23:47:22Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 288 | 39| 
| 20210715T23:28:22Z | Implementação do projeto de mestrado feito na universidade de campo limpo paulista. | https://github.com/aikid/fuzzyscript | 0 | 0| 
| 20210715T21:32:48Z | Null | https://github.com/AdaLogics/go-fuzz-headers | 2 | 1| 
| 20210715T21:21:44Z | 99minutos coverage maps | https://github.com/99minutos/fuzzy-journey | 0 | 0| 
| 20210715T20:59:46Z | Null | https://github.com/opimentel-github/fuzzy-tools | 0 | 0| 
| 20210715T20:38:57Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6485 | 1316| 
| 20210715T20:38:10Z | Fuzzy Extractors in Java | https://github.com/ThexXTURBOXx/FuzzyExtractors | 1 | 0| 
| 20210715T20:10:51Z | A fuzzy ecosystem for evaluating the stability of your computational tools. | https://github.com/verificarlo/fuzzy | 10 | 11| 
| 20210715T19:05:49Z | Null | https://github.com/NickBBn/fuzzer | 0 | 0| 
| 20210715T18:36:14Z | The practical work from Samara State Transport University | https://github.com/hasan2001jk/fuzzy-eureka | 0 | 0| 



# 日更新程序
