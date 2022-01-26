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
| 20210603T17:32:25Z | CVE-2021-27965 | stack based buffer overflow in MsIo64.sys, Proof of Concept Local Privilege Escalation to nt authority/system | https://github.com/mathisvickie/CVE-2021-27965 | The MsIo64.sys driver before 1.1.19.1016 in MSI Dragon Center before 2.0.98.0 has a buffer overflow that allows privilege escalation via a crafted 0x80102040, 0x80102044, 0x80102050, or 0x80102054 IOCTL request.| 
| 20210603T17:32:02Z | CVE-2021-21551 | arbitrary kernel read/write in dbutil_2_3.sys, Proof of Concept Local Privilege Escalation to nt authority/system | https://github.com/mathisvickie/CVE-2021-21551 | Dell dbutil_2_3.sys driver contains an insufficient access control vulnerability which may lead to escalation of privileges, denial of service, or information disclosure. Local authenticated user access is required.| 
| 20210603T14:20:48Z | CVE-2020-36326 | PoC for exploiting CVE-2020-36326 | https://github.com/JamesGeee/CVE-2020-36326 | PHPMailer 6.1.8 through 6.4.0 allows object injection through Phar Deserialization via addAttachment with a UNC pathname. NOTE: this is similar to CVE-2018-19296, but arose because 6.1.8 fixed a functionality problem in which UNC pathnames were always considered unreadable by PHPMailer, even in safe contexts. As an unintended side effect, this fix eliminated the code that blocked addAttachment exploitation.| 
| 20210603T11:37:30Z | CVE-2020-7471 | PoC for the SQL injection vulnerability in PostgreSQL with Django, found in Django 1.11 before 1.11.28, 2.2 before 2.2.10, and 3.0 before 3.0.3 | https://github.com/huzaifakhan771/CVE-2020-7471-Django | Django 1.11 before 1.11.28, 2.2 before 2.2.10, and 3.0 before 3.0.3 allows SQL Injection if untrusted data is used as a StringAgg delimiter (e.g., in Django applications that offer downloads of data as a series of rows with a user-specified column delimiter). By passing a suitably crafted delimiter to a contrib.postgres.aggregates.StringAgg instance, it was possible to break escaping and inject malicious SQL.| 
| 20210603T09:50:31Z | CVE-2020-24949 | PHPFusion 9.03.50 - Remote Code Execution | https://github.com/r90tpass/CVE-2020-24949 | Privilege escalation in PHP-Fusion 9.03.50 downloads/downloads.php allows an authenticated user (not admin) to send a crafted request to the server and perform remote command execution (RCE).| 
| 20210603T00:08:19Z | CVE-2021-29208 | PoC for exploiting CVE-2021-29208 | https://github.com/JamesGeee/CVE-2021-29208 | A remote dom xss, crlf injection vulnerability was discovered in HPE Integrated Lights-Out 4 (iLO 4); HPE SimpliVity 380 Gen9; HPE Integrated Lights-Out 5 (iLO 5) for HPE Gen10 Servers; HPE SimpliVity 380 Gen10; HPE SimpliVity 2600; HPE SimpliVity 380 Gen10 G; HPE SimpliVity 325; HPE SimpliVity 380 Gen10 H version(s): Prior to version 2.78.| 
| 20210603T00:08:14Z | CVE-2020-22023 | PoC for exploiting CVE-2020-22023 | https://github.com/JamesGeee/CVE-2020-22023 | A heap-based Buffer Overflow vulnerabililty exists in FFmpeg 4.2 in filter_frame at libavfilter/vf_bitplanenoise.c, which might lead to memory corruption and other potential consequences.| 
| 20210603T00:08:11Z | CVE-2020-22022 | PoC for exploiting CVE-2020-22022 | https://github.com/JamesGeee/CVE-2020-22022 | A heap-based Buffer Overflow vulnerability exists in FFmpeg 4.2 in filter_frame at libavfilter/vf_fieldorder.c, which might lead to memory corruption and other potential consequences.| 
| 20210603T00:08:07Z | CVE-2021-32625 | PoC for exploiting CVE-2021-32625 | https://github.com/JamesGeee/CVE-2021-32625 | Redis is an open source (BSD licensed), in-memory data structure store, used as a database, cache, and message broker. An integer overflow bug in Redis version 6.0 or newer (on 32-bit systems ONLY) can be exploited using the `STRALGO LCS` command to corrupt the heap and potentially result with remote code execution. This is a result of an incomplete fix for CVE-2021-29477 which only addresses the problem on 64-bit systems but fails to do that for 32-bit. 64-bit systems are not affected. The problem is fixed in version 6.2.4 and 6.0.14. An additional workaround to mitigate the problem without patching the `redis-server` executable is to use ACL configuration to prevent clients from using the `STRALGO LCS` command.| 
| 20210603T00:08:04Z | CVE-2021-29206 | PoC for exploiting CVE-2021-29206 | https://github.com/JamesGeee/CVE-2021-29206 | A remote xss vulnerability was discovered in HPE Integrated Lights-Out 4 (iLO 4); HPE SimpliVity 380 Gen9; HPE Integrated Lights-Out 5 (iLO 5) for HPE Gen10 Servers; HPE SimpliVity 380 Gen10; HPE SimpliVity 2600; HPE SimpliVity 380 Gen10 G; HPE SimpliVity 325; HPE SimpliVity 380 Gen10 H version(s): Prior to version 2.78.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210603T23:57:26Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 645 | 15| 
| 20210603T23:47:18Z | Null | https://github.com/JaimePSantos/ResearchKlee | 0 | 0| 
| 20210603T08:24:15Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1709 | 494| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210603T23:31:01Z | Command line configuration & Test Tool for WIZnet Serial to Ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool | 7 | 3| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210603T23:58:50Z | windows and linux streams for post exploitation | https://github.com/kymb0/post_exploitation | 1 | 0| 
| 20210603T23:50:45Z | Some scripts to exploit my vulnerable web app | https://github.com/kitty14956590/vuln-webapp-scripts | 0 | 0| 
| 20210603T23:39:07Z | The AWS exploitation framework, designed for testing the security of Amazon Web Services environments. | https://github.com/RhinoSecurityLabs/pacu | 2090 | 375| 
| 20210603T23:38:15Z | Personal dump of exploits and POCs | https://github.com/guerzon/exploits | 0 | 0| 
| 20210603T23:13:43Z | Null | https://github.com/HarrysExploit/Harrys-exploit-script-hub | 0 | 0| 
| 20210603T23:09:51Z | Local file inclusion discovery and exploitation tool | https://github.com/hansmach1ne/lfimap | 2 | 0| 
| 20210603T22:56:03Z | Null | https://github.com/zYan666/Demon-Exploit | 0 | 0| 
| 20210603T22:16:04Z | Exploiting Buffer Overflows and other SEED Lab Projects | https://github.com/Ab-spyder/Buffer_Overflows | 0 | 0| 
| 20210603T22:12:39Z | The whole collection of Exploits developed by me (Hacker5preme) | https://github.com/Hacker5preme/Exploits | 1 | 0| 
| 20210603T22:09:58Z | OWASP Benchmark is a test suite designed to verify the speed and accuracy of software vulnerability detection tools. A fully runnable web app written in Java, it supports analysis by Static (SAST), Dynamic (DAST), and Runtime (IAST) tools that support Java. The idea is that since it is fully runnable and all the vulnerabilities are actually exploitable, it’s a fair test for any kind of vulnerability detection tool.  For more details on this project, please see the OWASP Benchmark Project home page. | https://github.com/OWASP/Benchmark | 373 | 336| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210603T20:49:03Z | The code for: Detecting Backdoors in Black-box Neural Networks via Adversarial Extreme Value Analysis | https://github.com/aeva-backdoor-deteciton/Aeva-Blackbox-Backdoor-Detection | 0 | 0| 
| 20210603T17:08:19Z | A token logger for discord + steals Brave/Chrome passwords and usernames | https://github.com/CUPZYY/Backdoor-Machine | 11 | 1| 
| 20210603T14:56:23Z | PoC minecraft 1.12.2 backdoor plugin | https://github.com/mathisvickie/mc-backdoor | 1 | 0| 
| 20210603T13:55:36Z | Null | https://github.com/vaaadym/backdoor | 0 | 0| 
| 20210603T12:24:29Z | Null | https://github.com/ShannonAI/backdoor_nlg | 0 | 1| 
| 20210603T07:53:27Z | This will remove the hostflow java assist backdoor | https://github.com/abhiram555/JavaAssistBackdoorRemover | 0 | 1| 
| 20210603T07:19:46Z | Null | https://github.com/huynhquynh-dev/backdoor_py | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210603T23:57:43Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 75 | 18| 
| 20210603T23:42:18Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6351 | 1288| 
| 20210603T23:33:54Z | Null | https://github.com/my000own000files1/Fuzzy | 0 | 0| 
| 20210603T22:45:13Z | FuzzBench - Fuzzer benchmarking as a service. | https://github.com/google/fuzzbench | 645 | 119| 
| 20210603T22:04:08Z | Null | https://github.com/RANDY-Todd/fuzzy-garbanzo | 0 | 0| 
| 20210603T21:59:29Z | Null | https://github.com/JAC61090/fuzzy-dollop-day-planner | 0 | 0| 
| 20210603T21:13:27Z | WindowsHTML Engine | https://github.com/zeondev/fuzzy-engine | 0 | 0| 
| 20210603T20:28:53Z | Fuzzy Inference Systems package | https://github.com/jdvelasq/fuzzyis | 0 | 0| 
| 20210603T20:28:22Z | Null | https://github.com/niluferdone/FuzzyLogicProject | 0 | 0| 
| 20210603T20:28:14Z | Null | https://github.com/caaciquee/fuzzy-potato | 0 | 0| 



# 日更新程序
