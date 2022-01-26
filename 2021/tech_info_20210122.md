# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210122 | SSRF exploitation in Spreedsheet to PDF converter | https://medium.com/@r4id3n/ssrf-exploitation-in-spreedsheet-to-pdf-converter-2c7eacdac781| 
| 20210122 | Windows 准备为 Win32 API 开发多个语言 Bindings，新开源 Rust Binding | https://blogs.windows.com/windowsdeveloper/2021/01/21/making-win32-apis-more-accessible-to-more-languages/| 
| 20210122 | CSRF Protection Bypass in Atlassian Confluence Server | https://yeuchimse.com/csrf-protection-bypass-in-atlassian-confluence-server/| 
| 20210122 | Docker on macOS 本地提权漏洞分析 | https://wojciechregula.blog/post/when-vulnerable-library-is-actually-your-physical-book/| 
| 20210122 | Analyzing Bugzilla Testcases with Bugmon | https://hacks.mozilla.org/2021/01/analyzing-bugzilla-testcases-with-bugmon/| 
| 20210122 | 利用 Job 对象限制进程内存使用的方式实现 Anti Debug | https://secret.club/2021/01/20/diet-process.html| 
| 20210122 | James Forshaw 对 Windows 内核 Double Fetch 条件竞争漏洞利用新思路的分享 | https://googleprojectzero.blogspot.com/2021/01/windows-exploitation-tricks-trapping.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210122 | Five86-2靶机渗透实战 | https://www.hetianlab.com/specialized/20210115135759| 
| 20210122 | Windows后渗透之权限维持 | https://www.sec-in.com/article/794| 
| 20210122 | 用PyOD工具库进行「异常检测」 | https://zhuanlan.zhihu.com/p/58313521| 
| 20210122 | 基于机器学习的敏感信息泄露治理探索 | https://mp.weixin.qq.com/s/9ZOSyPJdyxgrbsY4FIvgXw| 
| 20210122 | CVE-2020-16040: Chromium V8引擎整数溢出漏洞分析 | https://mp.weixin.qq.com/s/j-WbrCQVb4E2JfY-bDqzJw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210122T16:29:39Z | CVE-2020-8554 | Null | https://github.com/Dviejopomata/CVE-2020-8554 | Kubernetes API server in all versions allow an attacker who is able to create a ClusterIP service and set the spec.externalIPs field, to intercept traffic to that IP address. Additionally, an attacker who is able to patch the status (which is considered a privileged operation and should not typically be granted to users) of a LoadBalancer service can set the status.loadBalancer.ingress.ip to similar effect.| 
| 20210122T10:56:30Z | CVE-2021-2109 | Null | https://github.com/rabbitsafe/CVE-2021-2109 | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows high privileged attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 7.2 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H).| 
| 20210122T09:56:32Z | CVE-2020-26217 | CVE-2020-26217 && XStream RCE | https://github.com/Al1ex/CVE-2020-26217 | XStream before version 1.4.14 is vulnerable to Remote Code Execution.The vulnerability may allow a remote attacker to run arbitrary shell commands only by manipulating the processed input stream. Only users who rely on blocklists are affected. Anyone using XStream%s Security Framework allowlist is not affected. The linked advisory provides code workarounds for users who cannot upgrade. The issue is fixed in version 1.4.14.| 
| 20210122T09:23:56Z | CVE-2020-26259 | CVE-2020-26259 &&XStream Arbitrary File Delete | https://github.com/Al1ex/CVE-2020-26259 | XStream is a Java library to serialize objects to XML and back again. In XStream before version 1.4.15, is vulnerable to an Arbitrary File Deletion on the local host when unmarshalling. The vulnerability may allow a remote attacker to delete arbitrary know files on the host as log as the executing process has sufficient rights only by manipulating the processed input stream. If you rely on XStream%s default blacklist of the Security Framework, you will have to use at least version 1.4.15. The reported vulnerability does not exist running Java 15 or higher. No user is affected, who followed the recommendation to setup XStream%s Security Framework with a whitelist! Anyone relying on XStream%s default blacklist can immediately switch to a whilelist for the allowed types to avoid the vulnerability. Users of XStream 1.4.14 or below who still want to use XStream default blacklist can use a workaround described in more detailed in the referenced advisories.| 
| 20210122T08:51:39Z | 未知编号 | 2020l4web-campaign-DanCvejn created by GitHub Classroom | https://github.com/pslib-cz/2020l4web-campaign-DanCvejn | 未查询到CVE信息| 
| 20210122T08:45:00Z | CVE-2020-26258 | CVE-2020-26258 && XStream SSRF | https://github.com/Al1ex/CVE-2020-26258 | XStream is a Java library to serialize objects to XML and back again. In XStream before version 1.4.15, a Server-Side Forgery Request vulnerability can be activated when unmarshalling. The vulnerability may allow a remote attacker to request data from internal resources that are not publicly available only by manipulating the processed input stream. If you rely on XStream%s default blacklist of the Security Framework, you will have to use at least version 1.4.15. The reported vulnerability does not exist if running Java 15 or higher. No user is affected who followed the recommendation to setup XStream%s Security Framework with a whitelist! Anyone relying on XStream%s default blacklist can immediately switch to a whilelist for the allowed types to avoid the vulnerability. Users of XStream 1.4.14 or below who still want to use XStream default blacklist can use a workaround described in more detailed in the referenced advisories.| 
| 20210122T08:18:45Z | CVE-2020-13937 | Apache Kylin API Unauthorized Access | https://github.com/Al1ex/CVE-2020-13937 | | 
| 20210122T06:33:51Z | 未知编号 | Null | https://github.com/zeromirror/cve_2020-11060 | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210122T20:24:35Z | Null | https://github.com/davidtr1037/klee-aaqc | 1 | 0| 
| 20210122T04:55:37Z | Kwik n Kleen  | https://github.com/SailekshmiP/Kwik-n-Kleen- | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210122T22:55:08Z | The AWS exploitation framework, designed for testing the security of Amazon Web Services environments. | https://github.com/RhinoSecurityLabs/pacu | 1829 | 334| 
| 20210122T22:35:53Z | Search for Unix binaries that can be exploited to bypass system security restrictions. | https://github.com/t0thkr1s/gtfo | 69 | 13| 
| 20210122T22:16:14Z | Text multi-class classification project exploiting different techniques for vector representation of text. | https://github.com/paoloitaliani/Text-Classification | 0 | 0| 
| 20210122T22:07:24Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 4 | 1| 
| 20210122T21:41:54Z | Null | https://github.com/Rilshrink/mCoreExploit | 0 | 0| 
| 20210122T21:24:42Z | The Eclipse Foundation has been a partner in many publicly funded research projects since 2013. We help organizations to successfully create, publish, and sustain an open source software platform, making the results of the research projects available for commercial or public exploitation. | https://github.com/EclipseFdn/eclipse.org-research | 0 | 9| 
| 20210122T20:21:47Z | Null | https://github.com/ferdinandmudjialim/exploitdb-cve-search-jupyter | 0 | 0| 
| 20210122T20:21:37Z | :fire: Powerful port scanner with python with built in tool kit to exploit known socket vulnerabilities (syn flood and others) | https://github.com/symonk/zonic | 0 | 0| 
| 20210122T20:18:49Z | Null | https://github.com/EyeFlND/ExploitLogs | 0 | 0| 
| 20210122T19:58:21Z | All Files, Scripts, and exploits can be found here | https://github.com/LMS57/TempleOfPwn | 1 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210122T23:44:40Z | Apache Tomcat auto WAR deployment & pwning penetration testing tool. | https://github.com/mgeeky/tomcatWarDeployer | 279 | 106| 
| 20210122T22:19:20Z | Backdoor de shell reversa simples em C  | https://github.com/medn1c/reverse-shell | 2 | 0| 
| 20210122T21:51:08Z | Null | https://github.com/mikkelskov1/backdoor2 | 0 | 0| 
| 20210122T21:38:00Z | unlock the advanced menu of Lenovo Yoga Slim 7 BIOS | https://github.com/esno/yoga-bios-unlock | 9 | 0| 
| 20210122T20:38:52Z | shell backdoor | https://github.com/hilmanXcode/shell | 0 | 0| 
| 20210122T20:10:51Z | Null | https://github.com/EjHvorSerDuVildUdJim/backdoor | 0 | 0| 
| 20210122T18:04:33Z | Worlds simplest PHP backdoor | https://github.com/F-Masood/php-backdoors | 0 | 0| 
| 20210122T16:03:09Z | access to target folders/files/and ... with python program | https://github.com/m0h0n/backdoor | 1 | 0| 
| 20210122T15:52:15Z | Backdoor for scripts | https://github.com/fnalte/Backdoor | 0 | 0| 
| 20210122T11:39:32Z | Null | https://github.com/rabbitx1337/backdoor | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210122T13:22:07Z | Using Atheris to fuzz test | https://github.com/ramonmedeiros/fuzz_testing | 0 | 0| 
| 20210122T13:00:19Z | Example for CW1 of Software Reliability in Haskell | https://github.com/mpardalos/FuzzerExampleHs | 0 | 0| 
| 20210122T12:52:27Z | SecLists is the security tester%s companion. It%s a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. | https://github.com/danielmiessler/SecLists | 29482 | 14854| 
| 20210122T12:46:42Z | A groovy/java tabular Data (from CSV,SQL,JSON) processing library that supports fuzzy column matching,tranformations/merging/querying | https://github.com/kayr/fuzzy-csv | 7 | 6| 
| 20210122T12:25:29Z | some code and notes for a soft version of K-means clustering | https://github.com/Jalagarto/Fuzzy_C_means | 1 | 0| 
| 20210122T12:25:00Z | Fuzzer and metamorphic tester for C++ libraries | https://github.com/PollyLabs/library-metamorphic-testing | 1 | 1| 
| 20210122T12:10:11Z | A Fuzzy Matching Approach for Clustering Strings | https://github.com/ebanalyse/fuzzup | 1 | 0| 
| 20210122T12:02:42Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 5807 | 1163| 
| 20210122T11:57:07Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 4 | 1| 
| 20210122T11:41:23Z | The first repository for me, just a try, without any target. | https://github.com/NightSunLight112358/fuzzy-octo-fortnight | 0 | 0| 



# 日更新程序
