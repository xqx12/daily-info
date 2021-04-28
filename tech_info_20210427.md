# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210427 | Alive2: Bounded Translation Validation for LLVM | http://www.cs.utah.edu/~regehr/alive2-pldi21.pdf| 
| 20210427 | Singular Security Lab 公开的 PPT。 | https://github.com/singularseclab/Slides| 
| 20210427 | 深入了解 QEMU 的工作原理，例如添加设备、中断、计时器等。 | https://airbus-seclab.github.io/qemu_blog/| 
| 20210427 | CVE-2021–28482（Microsoft Exchange Server 远程代码执行漏洞）的分析。 | https://testbnull.medium.com/microsoft-exchange-from-deserialization-to-post-auth-rce-cve-2021-28482-e713001d915f| 
| 20210427 | 利用 Windows 内置的工具进行横向渗透扫描。 | https://posts.slayerlabs.com/living-off-the-land/| 
| 20210427 | Wireshark 解密 RDP 流量的教程。 | https://unit42.paloaltonetworks.com/wireshark-tutorial-decrypting-rdp-traffic/| 
| 20210427 | CVE-2021-30657：由于 macOS 安全验证存在逻辑缺陷，未经签名和公证（Notarizing）的脚本或程序可以避开安全机制的检查。 | https://objective-see.com/blog/blog_0x64.html| 
| 20210427 | 苹果发布 iOS 14.5 和 macOS Big Sur 11.3 版本，修复多个高危漏洞，包括玄武实验室 Zhipeng Huo 和 Yuebin Sun 发现的3个漏洞。 | https://support.apple.com/zh-cn/HT212317| 
| 20210427 | 渗透测试Oauth应用程序视频。 | https://www.youtube.com/watch?v=gVqrf2uUdQ0| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210427 | 关基运营者应采取反间谍技术安全防范措施 | https://mp.weixin.qq.com/s/wcAg8yVVjSpE98H4L942nw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210427T21:13:20Z | CVE-2021-1732 | Read my  blog for more info -  | https://github.com/exploitblizzard/Windows-Privilege-Escalation-CVE-2021-1732 | Windows Win32k Elevation of Privilege Vulnerability This CVE ID is unique from CVE-2021-1698.| 
| 20210427T19:20:50Z | CVE-2021-26868 | Null | https://github.com/mavillon/CVE-2021-26868 | Windows Graphics Component Elevation of Privilege Vulnerability| 
| 20210427T18:36:14Z | CVE-2020-8958 | CVE-2020-8958: Authenticated RCE exploit for NetLink HG323 | https://github.com/Asjidkalam/CVE-2020-8958 | | 
| 20210427T15:01:11Z | CVE-2020-1938 | Null | https://github.com/streghstreek/CVE-2020-1938 | When using the Apache JServ Protocol (AJP), care must be taken when trusting incoming connections to Apache Tomcat. Tomcat treats AJP connections as having higher trust than, for example, a similar HTTP connection. If such connections are available to an attacker, they can be exploited in ways that may be surprising. In Apache Tomcat 9.0.0.M1 to 9.0.0.30, 8.5.0 to 8.5.50 and 7.0.0 to 7.0.99, Tomcat shipped with an AJP Connector enabled by default that listened on all configured IP addresses. It was expected (and recommended in the security guide) that this Connector would be disabled if not required. This vulnerability report identified a mechanism that allowed: - returning arbitrary files from anywhere in the web application - processing any file in the web application as a JSP Further, if the web application allowed file upload and stored those files within the web application (or the attacker was able to control the content of the web application by some other means) then this, along with the ability to process a file as a JSP, made remote code execution possible. It is important to note that mitigation is only required if an AJP port is accessible to untrusted users. Users wishing to take a defence-in-depth approach and block the vector that permits returning arbitrary files and execution as JSP may upgrade to Apache Tomcat 9.0.31, 8.5.51 or 7.0.100 or later. A number of changes were made to the default AJP Connector configuration in 9.0.31 to harden the default configuration. It is likely that users upgrading to 9.0.31, 8.5.51 or 7.0.100 or later will need to make small changes to their configurations.| 
| 20210427T14:46:59Z | CVE-2021-22192 | CVE-2021-22192 靶场： 未授权用户 RCE 漏洞 | https://github.com/lyy289065406/CVE-2021-22192 | An issue has been discovered in GitLab CE/EE affecting all versions starting from 13.2 allowing unauthorized authenticated users to execute arbitrary code on the server.| 
| 20210427T12:21:49Z | CVE-2021-31221 | Indicator of Compromise Scanner for CVE-2021-31221  | https://github.com/fireaye/ioc-scanner-CVE-2021-31221 | 未查询到CVE信息| 
| 20210427T10:33:39Z | CVE-2021-3291 | rebuild cve | https://github.com/ImHades101/CVE-2021-3291 | Zen Cart 1.5.7b allows admins to execute arbitrary OS commands by inspecting an HTML radio input element (within the modules edit page) and inserting a command.| 
| 20210427T10:14:18Z | 未知编号 | CVE-2021-22192 | https://github.com/PetrusViet/Gitlab-RCE | 未查询到CVE信息| 
| 20210427T08:27:04Z | 未知编号 | CVE-2021-1732 poc & exp; tested on 20H2 | https://github.com/Pai-Po/CVE-2021-1732 | 未查询到CVE信息| 
| 20210427T08:07:39Z | CVE-2020-14883 | Alibaba-Nacos-Unauthorized/ApacheDruid-RCE_CVE-2021-25646/MS-Exchange-SSRF-CVE-2021-26885/Oracle-WebLogic-CVE-2021-2109_RCE/RG-CNVD-2021-14536/RJ-SSL-VPN-UltraVires/Redis-Unauthorized-RCE/TDOA-V11.7-GetOnlineCookie/VMware-vCenter-GetAnyFile/yongyou-GRP-U8-XXE/Oracle-WebLogic-CVE-2020-14883/Oracle-WebLogic-CVE-2020-14882/Apache-Solr-GetAnyFile/F5-BIG-IP-CVE-2021-22986/Sonicwall-SSL-VPN-RCE/GitLab-Graphql-CNVD-2021-14193/D-Link-DCS-CVE-2020-25078/WLAN-AP-WEA453e-RCE/360TianQing-Unauthorized/360TianQing-SQLinjection/FanWeiOA-V8-SQLinjection/QiZhiBaoLeiJi-AnyUserLogin/QiAnXin-WangKangFirewall-RCE/金山-V8-终端安全系统/NCCloud-SQLinjection/ShowDoc-RCE | https://github.com/Yang0615777/PocList | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210427T19:06:41Z | Spring 2021 Geography 817 work folder  | https://github.com/klee12/klee12.github.io | 1 | 0| 
| 20210427T15:11:46Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 216 | 35| 
| 20210427T14:58:10Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1679 | 491| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210427T00:15:26Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 117 | 27| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210427T23:51:52Z | Create a scan bot that keeps users hidden, scans photos on each page visited compares individuals pictured against missing and exploited people database as well as databases for lost, stolen or missing artwork. Upon any match sends info on site, time and date as well as subject to appropriate parties.  | https://github.com/CryptoEnvy/recoveryscan | 0 | 0| 
| 20210427T23:19:43Z | CTFs and solutions for Linux binary exploitation. | https://github.com/MaherAzzouzi/LinuxExploitation | 10 | 6| 
| 20210427T22:56:31Z | Null | https://github.com/adam-pawelek/Software-Exploitation | 0 | 0| 
| 20210427T22:12:22Z | Null | https://github.com/Pasxeegamer/Coinmaster-Exploitzz-v2 | 0 | 0| 
| 20210427T22:04:10Z | this is a simple python exploition tool with loads more! | https://github.com/buffkermitisagod/router-sploit | 1 | 0| 
| 20210427T21:54:02Z | Fix exploits on anarchy minecraft servers | https://github.com/moom0o/AnarchyExploitFixes | 30 | 6| 
| 20210427T21:49:37Z | Null | https://github.com/WhoTippedMyCows/SoftwareExploitation | 0 | 0| 
| 20210427T21:47:14Z | Extraction et exploitation des données de conversations Messenger | https://github.com/adrien-chinour/statistiques-messenger | 0 | 0| 
| 20210427T21:05:30Z | An experimental debt system for me and my friends, exploiting git requests for financial safety and gits history for trust | https://github.com/psorus/git-pay | 0 | 2| 
| 20210427T20:24:11Z | forked version of funtuna, a homebrew ps2 app launcher designed to ease the pain of getting a stable exploit for those that have a console uncompatible with FreeMcBoot | https://github.com/israpps/Funtuna-Fork | 3 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210427T19:23:38Z | A python backdoor | https://github.com/FelipeDosAnjos/HarpiaBackdoor | 0 | 0| 
| 20210427T18:44:14Z | Python 3 IRC Bot / Botnet | https://github.com/trackmastersteve/HackServ | 19 | 16| 
| 20210427T18:33:03Z | A token logger for discord + steals Brave/Chrome passwords and usernames | https://github.com/CUPZYY/Backdoor-Machine | 1 | 0| 
| 20210427T18:07:28Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 67 | 11| 
| 20210427T13:55:48Z | Web Shell Backdoors Collection | https://github.com/PhenaxGod/Web-Shell-Backdoors | 0 | 0| 
| 20210427T13:27:11Z | A self-spreading parasitic, polymorphic internet-worm for the netBIOS backdoor | https://github.com/timo-cmd2/Win32.ThermalStorm | 1 | 0| 
| 20210427T09:33:28Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 227 | 38| 
| 20210427T09:09:40Z | Null | https://github.com/haehae00/backdoor | 0 | 0| 
| 20210427T03:59:34Z | generator of php_backdoor | https://github.com/Ki11i0n4ir3/backdoor-gen | 0 | 0| 
| 20210427T03:18:29Z | Backdoor Untuk Rce | https://github.com/ChokkaXploiter/azure | 1 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210427T22:41:37Z | Scalable fuzzing infrastructure. | https://github.com/google/clusterfuzz | 4490 | 434| 
| 20210427T22:17:32Z | Fuzzy charrs are fuzzy. | https://github.com/marenubium87/FuzzyCharr | 0 | 0| 
| 20210427T22:07:43Z | Null | https://github.com/Juanosorio94/fuzzing-rdma | 0 | 0| 
| 20210427T22:00:34Z | A unit test-like interface for fuzzing and symbolic execution | https://github.com/trailofbits/deepstate | 611 | 64| 
| 20210427T21:55:33Z | Null | https://github.com/RunzhouHan/fuzzing_fs_aware_applications | 0 | 0| 
| 20210427T21:50:19Z | This is the main website and system for Ball Fuzz Tennis Center. | https://github.com/Ball-Fuzz-Tennis-Center/tennis-system | 0 | 0| 
| 20210427T21:46:12Z | Null | https://github.com/JonathanScialpi/CorDapp_Fuzzer | 0 | 0| 
| 20210427T21:43:59Z | Null | https://github.com/JoDeMiro/Fuzzy | 0 | 0| 
| 20210427T21:13:38Z | Usermode code for the ARM OS fuzzer project | https://github.com/jprx/arm-os-fuzzer-usercode | 0 | 0| 
| 20210427T21:08:38Z | Null | https://github.com/MazenH24/fuzzy_system_carbon_dioxide_percentage | 0 | 0| 



# 日更新程序
