# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210603 | BFSLabs 对 Windows Hyper-V vmswitch.sys CVE-2021-28476 漏洞的简要分析 | https://labs.bluefrostsecurity.de/advisories/bfs-sa-2021-001/| 
| 20210603 | An Introduction to Manual Active Directory Querying with Dsquery and Ldapsearch | https://posts.specterops.io/an-introduction-to-manual-active-directory-querying-with-dsquery-and-ldapsearch-84943c13d7eb?gi=6f0b84b5f8eb| 
| 20210603 | 有研究员公开了他收集的各个版本的苹果 SEP 处理器 BootROM | http://securerom.fun| 
| 20210603 | 恶意软件分析与溯源过程中如何收集家族样本的技术分析，来自 SSTIC 会议 | https://www.sstic.org/2021/presentation/Taking_Advantage_of_PE_Metadata_or_How_To_Complete_your_Favorite_Threat_Actor_Sample_Collection/| 
| 20210603 | SSTIC 会议上 Google 研究员关于近期他们开源的 Hyper-V Fuzzer - Hyntrospect 的演讲 | https://www.sstic.org/2021/presentation/hyntrospect_a_fuzzer_for_hyper-v_devices/| 
| 20210603 | James Forshaw 对 SeRelabelPrivilege 的介绍 | https://www.tiraniddo.dev/2021/06/the-much-misunderstood.html| 
| 20210603 | Microsoft SharePoint Server CVE-2021-31181 RCE 漏洞的分析 | https://www.thezdi.com/blog/2021/6/1/cve-2021-31181-microsoft-sharepoint-webpart-interpretation-conflict-remote-code-execution-vulnerability| 
| 20210603 | Apple Safari JSC 脚本引擎 WebAssembly CVE-2021-30734 RCE 漏洞的分析 | https://blog.ret2.io/2021/06/02/pwn2own-2021-jsc-exploit/| 
| 20210603 | 微软关于 Edge 浏览器 UI 安全的设计与安全对抗实践 | https://microsoftedge.github.io/edgevr/posts/ui-security-thinking-outside-the-viewport/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210603T11:37:30Z | CVE-2020-7471 | PoC for the SQL injection vulnerability in PostgreSQL with Django, found in Django 1.11 before 1.11.28, 2.2 before 2.2.10, and 3.0 before 3.0.3 | https://github.com/huzaifakhan771/CVE-2020-7471-Django | Django 1.11 before 1.11.28, 2.2 before 2.2.10, and 3.0 before 3.0.3 allows SQL Injection if untrusted data is used as a StringAgg delimiter (e.g., in Django applications that offer downloads of data as a series of rows with a user-specified column delimiter). By passing a suitably crafted delimiter to a contrib.postgres.aggregates.StringAgg instance, it was possible to break escaping and inject malicious SQL.| 
| 20210603T11:07:56Z | CVE-2021-21985 | CVE-2021-21985 vmware vcenter 远程代码执行 EXP | https://github.com/r0ckysec/CVE-2021-21985 | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210603T10:19:10Z | CVE-2021-21985 | Null | https://github.com/alt3kx/CVE-2021-21985_PoC | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210603T09:50:31Z | CVE-2020-24949 | PHPFusion 9.03.50 - Remote Code Execution | https://github.com/r90tpass/CVE-2020-24949 | Privilege escalation in PHP-Fusion 9.03.50 downloads/downloads.php allows an authenticated user (not admin) to send a crafted request to the server and perform remote command execution (RCE).| 
| 20210603T01:16:00Z | CVE-2020-36326 | PoC for exploiting CVE-2020-36326 | https://github.com/JamesGeee/CVE-2020-36326 | PHPMailer 6.1.8 through 6.4.0 allows object injection through Phar Deserialization via addAttachment with a UNC pathname. NOTE: this is similar to CVE-2018-19296, but arose because 6.1.8 fixed a functionality problem in which UNC pathnames were always considered unreadable by PHPMailer, even in safe contexts. As an unintended side effect, this fix eliminated the code that blocked addAttachment exploitation.| 
| 20210603T00:08:19Z | CVE-2021-29208 | PoC for exploiting CVE-2021-29208 | https://github.com/JamesGeee/CVE-2021-29208 | A remote dom xss, crlf injection vulnerability was discovered in HPE Integrated Lights-Out 4 (iLO 4); HPE SimpliVity 380 Gen9; HPE Integrated Lights-Out 5 (iLO 5) for HPE Gen10 Servers; HPE SimpliVity 380 Gen10; HPE SimpliVity 2600; HPE SimpliVity 380 Gen10 G; HPE SimpliVity 325; HPE SimpliVity 380 Gen10 H version(s): Prior to version 2.78.| 
| 20210603T00:08:14Z | CVE-2020-22023 | PoC for exploiting CVE-2020-22023 | https://github.com/JamesGeee/CVE-2020-22023 | | 
| 20210603T00:08:11Z | CVE-2020-22022 | PoC for exploiting CVE-2020-22022 | https://github.com/JamesGeee/CVE-2020-22022 | A heap-based Buffer Overflow vulnerability exists in FFmpeg 4.2 in filter_frame at libavfilter/vf_fieldorder.c, which might lead to memory corruption and other potential consequences.| 
| 20210603T00:08:07Z | CVE-2021-32625 | PoC for exploiting CVE-2021-32625 | https://github.com/JamesGeee/CVE-2021-32625 | Redis is an open source (BSD licensed), in-memory data structure store, used as a database, cache, and message broker. An integer overflow bug in Redis version 6.0 or newer (on 32-bit systems ONLY) can be exploited using the `STRALGO LCS` command to corrupt the heap and potentially result with remote code execution. This is a result of an incomplete fix for CVE-2021-29477 which only addresses the problem on 64-bit systems but fails to do that for 32-bit. 64-bit systems are not affected. The problem is fixed in version 6.2.4 and 6.0.14. An additional workaround to mitigate the problem without patching the `redis-server` executable is to use ACL configuration to prevent clients from using the `STRALGO LCS` command.| 
| 20210603T00:08:04Z | CVE-2021-29206 | PoC for exploiting CVE-2021-29206 | https://github.com/JamesGeee/CVE-2021-29206 | A remote xss vulnerability was discovered in HPE Integrated Lights-Out 4 (iLO 4); HPE SimpliVity 380 Gen9; HPE Integrated Lights-Out 5 (iLO 5) for HPE Gen10 Servers; HPE SimpliVity 380 Gen10; HPE SimpliVity 2600; HPE SimpliVity 380 Gen10 G; HPE SimpliVity 325; HPE SimpliVity 380 Gen10 H version(s): Prior to version 2.78.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210603T08:24:15Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1709 | 494| 
| 20210603T01:39:42Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 644 | 15| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210603T12:02:50Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 24 | 11| 
| 20210603T11:49:14Z | A post exploitation tool based on a web application, focusing on bypassing endpoint protection and application whitelisting | https://github.com/AdrianVollmer/PowerHub | 433 | 76| 
| 20210603T11:39:22Z | A Framework meant for the exploitation of iOS devices. | https://github.com/0x1CA3/iPwn | 11 | 1| 
| 20210603T10:56:14Z | Scripts (ServerSide and FE) | https://github.com/0WNEDU/Roblox-Misc-Scripts-Exploits | 0 | 0| 
| 20210603T10:03:01Z | Burp extension to help identify and exploit JavaScript `eval()` | https://github.com/b4dpxl/Evaluator | 0 | 0| 
| 20210603T09:30:56Z | RCE Exploit for Gitlab < 13.9.4 | https://github.com/CsEnox/GitLab-Wiki-RCE | 3 | 1| 
| 20210603T09:14:16Z | Contribute to the Development of Exploit Prevention by thinking of some great messages | https://github.com/ryanalexander/exploit-prevention-lang | 0 | 0| 
| 20210603T08:55:39Z | Simple Exploit | https://github.com/PlinBlin/Simple-Exploit | 1 | 0| 
| 20210603T08:53:59Z | A Go library for manipulating Windows processes. | https://github.com/jamesmoriarty/gomem | 9 | 1| 
| 20210603T08:35:17Z | RCE Exploit found by Darvin in GAMESENSE aka SKEET | https://github.com/DarvinYouTube/GameSense-RCE | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210603T07:53:27Z | This will remove the hostflow java assist backdoor | https://github.com/abhiram555/JavaAssistBackdoorRemover | 0 | 1| 
| 20210603T07:19:46Z | Null | https://github.com/huynhquynh-dev/backdoor_py | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210603T01:09:38Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6346 | 1288| 
| 20210603T01:07:44Z | Null | https://github.com/Immoraly/Fuzzy-Hash | 0 | 0| 
| 20210603T00:25:50Z | Null | https://github.com/taiwoseun4563/fuzzy-garbanzo | 0 | 0| 
| 20210603T00:09:15Z | SecLists is the security tester%s companion. It%s a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. | https://github.com/danielmiessler/SecLists | 31803 | 16382| 



# 日更新程序
