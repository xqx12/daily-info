# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210113 | Bypassing Windows protection mechanisms & Playing with OffensiveNim | https://s3cur3th1ssh1t.github.io/Playing-with-OffensiveNim/| 
| 20210113 | PHP 框架 Laravel v8.4.2 版本调试模式 RCE 漏洞分析 | https://www.ambionics.io/blog/laravel-debug-rce| 
| 20210113 | Practical Web Cache Poisoning | https://portswigger.net/research/practical-web-cache-poisoning| 
| 20210113 | Firefox、Chrome 浏览器跨域窃取图片信息漏洞(CVE-2020-16012)分析 | https://blog.mozilla.org/attack-and-defense/2021/01/11/leaking-silhouettes-of-cross-origin-images/| 
| 20210113 | Breaking The Browser – A tale of IPC, credentials and backdoors | https://www.mdsec.co.uk/2021/01/breaking-the-browser-a-tale-of-ipc-credentials-and-backdoors/| 
| 20210113 | 微软发布 1 月份漏洞补丁公告，本次修复 10 个高危漏洞 | http://threatpost.com/critical-microsoft-defender-bug-exploited/162992/| 
| 20210113 | Making Clouds Rain :: Remote Code Execution in Microsoft Office 365 | https://srcincite.io/blog/2021/01/12/making-clouds-rain-rce-in-office-365.html| 
| 20210113 | Project Zero 新 Blog，介绍他们 2020 年春发现的野外攻击代码，经分析从中发现多个 0Day，覆盖 Windows、Android、Chrome 浏览器 | https://googleprojectzero.blogspot.com/2021/01/introducing-in-wild-series.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210113 | 重组 SUNBURST DNS 请求还原受害者域 | https://mp.weixin.qq.com/s/fZYmiTSuSErO1zCw2Czrww| 
| 20210113 | 子域名枚举的艺术——主动子域枚举 | https://www.sec-in.com/article/793| 
| 20210113 | 又一个流量代理扫描平台 | https://misakikata.github.io/2021/01/%E5%8F%88%E5%8F%92%E4%B8%80%E4%B8%AA%E4%BB%A3%E7%90%86%E6%89%AB%E6%8F%8F%E5%B9%B3%E5%8F%B0/| 
| 20210113 | Vulnstack 3 域环境靶机实战 | https://www.hetianlab.com/specialized/20210108150244| 
| 20210113 | 利用官网getshell | https://mp.weixin.qq.com/s?__biz=MjM5MTYxNjQxOA==&mid=2652867929&idx=1&sn=592912e06f9af6840c728990f1f88950&chksm=bd59f1948a2e78825e6524d4a599d6e0c3516cf77d7d526c2d036e576f5bebbc2bdee6ebb7c9&scene=178&cur_album_id=1351008152896192512#rd| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210113T13:51:12Z | cve-2020-16012 | PoC for CVE-2020-16012, a timing side channel in drawImage in Firefox & Chrome | https://github.com/aleksejspopovs/cve-2020-16012 | | 
| 20210113T09:29:09Z | CVE-2020-36184 | CVE-2020-36184 && Jackson-databind  RCE | https://github.com/Al1ex/CVE-2020-36184 | FasterXML jackson-databind 2.x before 2.9.10.8 mishandles the interaction between serialization gadgets and typing, related to org.apache.tomcat.dbcp.dbcp2.datasources.PerUserPoolDataSource.| 
| 20210113T09:19:44Z | CVE-2020-7048 | Null | https://github.com/ElmouradiAmine/CVE-2020-7048 | The WordPress plugin, WP Database Reset through 3.1, contains a flaw that allowed any unauthenticated user to reset any table in the database to the initial WordPress set-up state (deleting all site content stored in that table), as demonstrated by a wp-admin/admin-post.php?db-reset-tables[]=comments URI.| 
| 20210113T07:54:41Z | CVE-2021-3131 | CVE-2021-3131 | https://github.com/jet-pentest/CVE-2021-3131 | 未查询到CVE信息| 
| 20210113T07:53:08Z | CVE-2020-36179 | CVE-2020-36179~82  Jackson-databind SSRF&RCE | https://github.com/Al1ex/CVE-2020-36179 | FasterXML jackson-databind 2.x before 2.9.10.8 mishandles the interaction between serialization gadgets and typing, related to oadd.org.apache.commons.dbcp.cpdsadapter.DriverAdapterCPDS.| 
| 20210113T07:29:03Z | CVE-2021-3019 | CVE-2021-3019 lanproxy目录遍历任意文件读取漏洞探测POC | https://github.com/FanqXu/CVE-2021-3019 | ffay lanproxy 0.1 allows Directory Traversal to read /../conf/config.properties to obtain credentials for a connection to the intranet.| 
| 20210113T06:42:44Z | CVE-2020-3452 | CISCO CVE-2020-3452 Scanner & Exploiter | https://github.com/darklotuskdb/CISCO-CVE-2020-3452-Scanner-Exploiter | A vulnerability in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct directory traversal attacks and read sensitive files on a targeted system. The vulnerability is due to a lack of proper input validation of URLs in HTTP requests processed by an affected device. An attacker could exploit this vulnerability by sending a crafted HTTP request containing directory traversal character sequences to an affected device. A successful exploit could allow the attacker to view arbitrary files within the web services file system on the targeted device. The web services file system is enabled when the affected device is configured with either WebVPN or AnyConnect features. This vulnerability cannot be used to obtain access to ASA or FTD system files or underlying operating system (OS) files.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210113T10:47:29Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1600 | 479| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210113T05:42:08Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 90 | 22| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210113T13:55:51Z | Development of code to exploit LSST and VISTA imaging | https://github.com/lsst-uk/lsst-ir-fusion | 0 | 0| 
| 20210113T13:51:20Z | The ZetaSploit Framework is a modular penetration testing platform that enables you to write, test, and execute exploit code. The ZetaSploit Framework contains a suite of tools that you can use to test security vulnerabilities, enumerate networks and execute attacks. | https://github.com/EntySec/ZetaSploit | 11 | 4| 
| 20210113T13:43:07Z | The Hybrid Fake Face (HFF) dataset is built by exploiting the PGGAN, StyleGAN, Glow, and StarGAN.  | https://github.com/EricGzq/Hybrid-Fake-Face-Dataset | 6 | 0| 
| 20210113T13:31:58Z | Commodity Injection Signatures, Malicious Inputs, XSS, HTTP Header Injection, XXE, RCE, Javascript, XSLT | https://github.com/xsscx/Commodity-Injection-Signatures | 249 | 101| 
| 20210113T13:25:12Z | Exploit for CVE-2021-3129 | https://github.com/ambionics/laravel-exploits | 0 | 0| 
| 20210113T13:22:34Z | Sifter is a OSINT, recon & vulnerability scanner. It incorporates a plethara of tools within different module sets that tries to cover every attack vector. Allowing you to quickly perform recon tasks and organize the results in one place. From OSINT to Recon, Exploitation, Post-Exploitation, OpSec, Threat Analysis, XSS, SQLinjection, Network Scanning, WebApp Analysis or DNS enumeration.. Sifter should be able to cover it all. | https://github.com/s1l3nt78/sifter | 361 | 104| 
| 20210113T13:16:34Z | A simple dns server to exploit server side request forgery using DNS rebinding technique | https://github.com/abhilash-pangutty/dns-rebinder | 0 | 0| 
| 20210113T13:16:19Z | A collection of more than 140+ tools, scripts, cheatsheets and other loots that I have developed over years for Red Teaming/Pentesting/IT Security audits purposes. Most of them came handy on at least one of my real-world engagements. | https://github.com/mgeeky/Penetration-Testing-Tools | 551 | 146| 
| 20210113T13:07:18Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 8887 | 1410| 
| 20210113T12:58:52Z | CAUTION: Malicious files used to infect web sites. | https://github.com/Am0rphous/Malware-Collection | 17 | 6| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210113T12:39:14Z | Null | https://github.com/anish833/Backdoor | 0 | 0| 
| 20210113T12:01:40Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 162 | 30| 
| 20210113T09:19:20Z | Null | https://github.com/rabbitx1337/backdoor | 0 | 0| 
| 20210113T05:38:31Z | TheGremlinLinuxBackdoor Project, still in making do not use for now ! | https://github.com/k0rup710n/GremlinLinux-Backdoor | 0 | 0| 
| 20210113T03:46:45Z | Backdoor de shell reversa simples em C  | https://github.com/medn1c/reverse-shell | 0 | 0| 
| 20210113T02:34:23Z | Tool to find potential backdoor/security holes in your endpoint | https://github.com/subasgit/backdoorfinder | 1 | 0| 
| 20210113T02:17:32Z | A sethc backdoor based by golang | https://github.com/TenguG/ShiftGoor | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210113T13:32:45Z | Collection of quality safety articles. Awesome articles.   | https://github.com/tom0li/collection-document | 1331 | 427| 
| 20210113T13:25:31Z | Dictionary collection project such as Pentesing, Fuzzing, Bruteforce and BugBounty. 渗透测试、SRC漏洞挖掘、爆破、Fuzzing等字典收集项目。 | https://github.com/insightglacier/Dictionary-Of-Pentesting | 413 | 100| 
| 20210113T13:23:17Z | This program is for fuzzy set operation  written in c language  | https://github.com/kingSSG/Fuzzy-set-operations- | 1 | 0| 
| 20210113T13:07:14Z | Null | https://github.com/maria-romitsyna/fuzzy-maytanic | 0 | 0| 
| 20210113T12:51:38Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 230 | 31| 
| 20210113T12:04:56Z | An HL7 message fuzzer ( client and server ) | https://github.com/IOActive/HL7-Fuzzer | 1 | 0| 
| 20210113T11:55:51Z | AFLNet: A Greybox Fuzzer for Network Protocols (https://thuanpv.github.io/publications/AFLNet_ICST20.pdf) | https://github.com/aflnet/aflnet | 350 | 56| 
| 20210113T11:42:06Z | Script made for analyzing network parameters to give optimal result | https://github.com/Sancene/FuzzyProject | 0 | 1| 
| 20210113T11:35:50Z | fzf-like fuzzy-finder as a Go library | https://github.com/ktr0731/go-fuzzyfinder | 204 | 19| 
| 20210113T11:06:06Z | Academic papers and articles that I read related to web hacking, fuzzing, etc. / 阅读过的Web安全方向、模糊测试方向的一些论文与阅读笔记 | https://github.com/LyleMi/papers | 172 | 7| 



# 日更新程序
