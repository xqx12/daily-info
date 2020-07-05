# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20200704 | 全球网络设备提供商F5 Networks发布了安全漏洞报告，该“远程代码执行“”漏洞影响全球的政府，银行，互联网服务提供商，云计算数据中心以及整个企业网络中安全威胁。 | https://www.zdnet.com/article/f5-patches-vulnerability-that-received-a-cvss-10-severity-score/| 
| 20200704 | 使用Radare2-16逆向工程x64二进制文件（unix套接字基础知识） | https://artik.blue/reversing-radare-15| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20200704 | 不一样的 反弹Shell 系统剖析 | https://mp.weixin.qq.com/s/VAHriOf4HVUna3FxhKg_OA| 
| 20200704 | 初探网络安全智能决策 | https://mp.weixin.qq.com/s/EStPo05HwUTQHOTRx7qltg| 
| 20200704 | 小议智能设备安全研究 | https://mp.weixin.qq.com/s/Wc6rE_2rVKHOPoCQzmGvKg| 
| 20200704 | Oracle 注入学习（终结版） | https://mp.weixin.qq.com/s/BvZ0niXtofDMjzUpHxjKig| 
| 20200704 | CTF实战特训营实训真题 | https://zhuanlan.zhihu.com/p/148384035| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20200704T19:27:59Z | CVE-2020-14947 | The official exploit for OCS Inventory NG v2.7 Remote Command Execution CVE-2020-14947 | https://github.com/mhaskar/CVE-2020-14947 | OCS Inventory NG 2.7允许通过Shell元字符进行远程命令执行需要require / commandLine / CommandLine.php，因为plugins / main_sections / ms_config / ms_snmp_config.php中的mib_file在get_mib_oid中处理不当。| 
| 20200704T19:10:37Z | CVE-2020-5902 | CVE-2020-5902 | https://github.com/dwisiswant0/CVE-2020-5902 | 在BIG-IP版本15.0.0-15.1.0.3、14.1.0-14.1.2.5、13.1.0-13.1.3.3、12.1.0-12.1.5.1和11.6.1-11.6.5.1中，流量管理用户接口（TMUI），也称为“配置”实用程序，在未公开的页面中具有远程执行代码（RCE）漏洞。| 
| 20200704T16:40:22Z | CVE-2020-8835 | Null | https://github.com/snappyJack/Rick_write_exp_CVE-2020-8835 | 在Linux内核5.5.0及更高版本中，bpf验证程序（kernel / bpf / verifier.c）不能正确限制32位操作的寄存器范围，从而导致内核内存中的读取和写入越界。该漏洞还影响从v5.4.7开始的Linux 5.4稳定系列，因为引入的提交已反向移植到该分支。此漏洞已在5.6.1、5.5.14和5.4.29中修复。 （问题是ZDI-CAN-10780）| 
| 20200704T15:22:41Z | CVE-2020-12828 | CVE-2020-12828 PoC and Analysis.  | https://github.com/0xsha/ZombieVPN | 在1.3.3.218之前的AnchorFree VPN SDK中发现了一个问题。 VPN SDK服务通过绑定到本地主机的套接字获取某些可执行位置。绑定到套接字并提供恶意可执行文件所在的路径会导致以SYSTEM特权执行恶意可执行文件。| 
| 20200704T14:44:45Z | CVE-2020-15392 | User Enumeration on Supravizio BPM 10.1.2 | https://github.com/inflixim4be/CVE-2020-15392 | 未查询到CVE信息| 
| 20200704T14:44:07Z | CVE-2020-15367 | Brute Force on Supravizio BPM 10.1.2 | https://github.com/inflixim4be/CVE-2020-15367 | 未查询到CVE信息| 
| 20200704T14:31:27Z | CVE-2020-11444 | Exphub[漏洞利用脚本库] 包括Webloigc、Struts2、Tomcat、Nexus、Solr、Jboss、Drupal的漏洞利用脚本，优先更新高危且易利用的漏洞利用脚本，最新添加CVE-2020-11444、CVE-2020-10204、CVE-2020-10199、CVE-2020-1938、CVE-2020-2551、CVE-2020-2555、CVE-2020-2883、CVE-2019-17558、CVE-2019-6340 | https://github.com/zhzyker/exphub | | 
| 20200704T10:20:13Z | 未知编号 | CVE Data Analysis, CVE Monitor, CVE EXP Prediction Based on Deep Learning. 1999-2020年存量CVE数据分析、监控CVE增量更新、基于深度学习的CVE EXP预测和自动化推送 | https://github.com/404notf0und/CVE-Flow | 未查询到CVE信息| 
| 20200704T09:16:16Z | CVE-2020-2021 | CVE-2020-2021 | https://github.com/mr-r3b00t/CVE-2020-2021 | QUERY LENGTH LIMIT EXCEDEED. MAX ALLOWED QUERY : 500 CHARS QUERY LENGTH LIMIT EXCEDEED. MAX ALLOWED QUERY : 500 CHARS 在这种情况下，这是一个严重严重漏洞，其CVSS基本分数为10.0（CVSS：3.1 / AV：N / AC：L / PR：N / UI：N / S：C / C：H / I：H / A： H）。如果仅可通过受限管理网络访问Web界面，则问题将降低为CVSS基本分数9.6（CVSS：3.1 / AV：A / AC：L / PR：N / UI：N / S：C / C：H / I：H / A：H）。 Palo Alto Networks不知道有任何恶意尝试利用此漏洞。| 
| 20200704T07:35:34Z | CVE-2020-1948 | Null | https://github.com/ctlyz123/CVE-2020-1948 | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20200704T15:32:01Z | Python module execution timer for application | https://github.com/Edenskull/KleenTimer | 0 | 0| 
| 20200704T15:28:36Z | ⬇️ File Upload/sharing application, used by thousands of webmasters since 2007.  | https://github.com/kleeja-official/kleeja | 100 | 33| 
| 20200704T04:41:58Z | A 4chan image browser written in SwiftUI | https://github.com/jackpal/KleeneStar | 8 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20200704T15:20:17Z | cicd logic and gitlab&github runner, centos base ,whith jdk/python/go, maven/npm,/kubectl/helm | https://github.com/chimeh/cicd-s2e-runner | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20200704T23:40:37Z | *Frequently Updated. Sifter is a osint, recon & vulnerability scanner. It combines a plethara of tools within different module sets in order to quickly perform recon tasks, check network firewalling, enumerate remote and local hosts, and scan for the %blue% vulnerabilities within microsft and if unpatched, exploit them.  It uses tools like blackwidow and konan for webdir enumeration and attack surface mapping rapidly using ASM.  | https://github.com/s1l3nt78/sifter | 175 | 57| 
| 20200704T23:37:51Z | a iOS repo for exploit patches and fixes. not exactly meant for the public, but it%s open to be added. | https://github.com/syns/iospatches | 1 | 0| 
| 20200704T23:18:54Z | this  bash script lets you choose a linux enumeration script, exploitation and utilities. read README.md file to learn about this script.. | https://github.com/FabioDefilippo/linuxallenum | 0 | 0| 
| 20200704T23:01:19Z | Ruby script to automate metasploit scanning, exploitation, and post-exploitation | https://github.com/paulosgf/autoMetasploit | 4 | 1| 
| 20200704T22:56:26Z | A python script file to remotely analyse and exploit Microsoft Windows system via impacket. | https://github.com/BroadbentT/WIN-MASTER | 13 | 10| 
| 20200704T22:54:42Z | This code is an IRC BOT that can connect to an IRC server with SSL The main purpose of this bot is to scan for Open/Unsecured VNC servers. The bot can also search for credit card informations in the computer that the bot is running (removed in last version to optimize compilation process time). Added SSH takeover module/command.. There is also a DDoS module made in Python, for taking out the target from the network. | https://github.com/independentcod/PerlIRCSSL_VNCbypass | 14 | 7| 
| 20200704T22:49:41Z | An exploit that attaches to Noita, a rougelite game. | https://github.com/pepsipu/rouge | 0 | 0| 
| 20200704T22:21:11Z | this bash script let you download scripts and clone repos for remote exploits | https://github.com/FabioDefilippo/linuxallremote | 0 | 0| 
| 20200704T22:19:44Z | Script solo para Termux que automatiza la instalación de The Browser Exploitation Framework. | https://github.com/tony23x/BeEF-INSTALL | 0 | 0| 
| 20200704T22:05:10Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 6664 | 1043| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20200704T22:52:42Z | A native backdoor module for Microsoft IIS (Internet Information Services) | https://github.com/0x09AL/IIS-Raid | 309 | 75| 
| 20200704T19:58:17Z | Undetectable & Xor encrypting with custom KEY (FUD Metasploit Rat) bypass Top Antivirus like BitDefender,Malwarebytes,Avast,ESET-NOD32,AVG,... & Automatically Add ICON and MANIFEST to excitable | https://github.com/persianhydra/Xeexe-TopAntivirusEvasion | 69 | 25| 
| 20200704T12:17:20Z | A backdoor application that gains control of another system | https://github.com/pan0sSt/reverse_backdoor | 1 | 1| 
| 20200704T08:19:34Z | Thoron Framework is a Linux post-exploitation framework that exploits Linux TCP vulnerability to provide a shell-like connection. Thoron Framework has the ability to create simple payloads to provide Linux TCP attack. | https://github.com/entynetproject/thoron | 68 | 26| 
| 20200704T08:17:51Z | Mouse Framework is an iOS and macOS post-exploitation framework that gives you a command line session with extra functionality between you and a target machine using only a simple Mouse payload. Mouse gives you the power and convenience of uploading and downloading files, tab completion, taking pictures, location tracking, shell command execution, escalating privileges, password retrieval, and much more. | https://github.com/entynetproject/mouse | 167 | 63| 
| 20200704T07:59:10Z | kumpulan mini shell | https://github.com/Array-Gans/mini-shell-backdoor | 0 | 0| 
| 20200704T07:08:25Z | Easy to understand back door written in python  | https://github.com/alik604/myPyBackDoor | 9 | 6| 
| 20200704T04:49:42Z | A malware with lots of features!! and with backdoor. DO NOT MISUSE!! USE FOR EDUCATIONAL PURPOSE ONLY!! | https://github.com/Gauthamprasath/EtherealX | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20200704T23:34:14Z | Fuzzy charrs are fuzzy. | https://github.com/marenubium87/FuzzyCharr | 0 | 0| 
| 20200704T23:08:03Z | american fuzzy lop - a security-oriented fuzzer | https://github.com/google/AFL | 1223 | 196| 
| 20200704T22:43:02Z | Null | https://github.com/renanreboredo/fuzzy-trader | 0 | 0| 
| 20200704T22:32:19Z | Fuzzy TS optimisation based on genetic algorithm | https://github.com/jairpaulino/fuzzy-ts-opt | 0 | 0| 
| 20200704T22:10:25Z | Null | https://github.com/lazygrey/fuzzing_with_cmaes | 0 | 0| 
| 20200704T21:07:28Z | CLI to create file/folder with fuzzy-file matching autocomplete | https://github.com/JoeNg93/fuzzy-new-file | 0 | 0| 
| 20200704T21:06:33Z | Simple tool to rename source files by matching a list of choices. | https://github.com/pcjco/PyFuzzy-renamer | 0 | 0| 
| 20200704T20:14:56Z | The Python3 Fuzzing Module | https://github.com/jangelesg/py3webfuzz | 0 | 0| 
| 20200704T20:07:33Z | Grammar-based Fuzzer that uses WebIDL as a grammar. | https://github.com/PrVrSs/idl2js | 0 | 0| 
| 20200704T19:43:03Z | Null | https://github.com/nikhils4/fuzzy-eureka | 0 | 1| 



# 日更新程序
