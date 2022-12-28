# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221228 | 影响任天堂多款在线游戏的网络库缓冲区溢出漏洞的细节和poc公开，涉及ns，3ds，wiiu平台的多款游戏 | http://securityonline.info/cve-2022-47949-critical-rce-flaw-affects-multiple-nintendo-games/| 
| 20221228 | 2022年APT攻击洞察报告 | https://github.com/blackorbird/APT_REPORT/blob/master/summary/2023/2022_APT_TRENDS_INSIGHT_REPORT.pdf| 
| 20221228 | 供应链相关的攻击和缓解措施研究 | https://engineering.mercari.com/en/blog/entry/20221215-supplychain-security-reevaluation/| 
| 20221228 | 一个Linux的防火墙，以内核模块的形式实现，其主要亮点是可以像rootkit一样隐藏自己。 | https://antonio-cooler.gitbook.io/coolervoid-tavern/hidden-firewall-in-kernel| 
| 20221228 | ARM平台上的漏洞利用入门教程书 | https://ad2001.gitbook.io/a-noobs-guide-to-arm-exploitation/| 
| 20221228 | 使用CLR hooking的方法绕过杀软检测，以实现在powershell中随意执行恶意命令 | http://practicalsecurityanalytics.com/new-amsi-bypass-using-clr-hooking/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221228 | 2022攻防演练木马专项分析报告 | http://report.threatbook.cn/2022.pdf| 
| 20221228 | 从开源项目和库的Issue和Bug报告中挖掘情报 | https://mp.weixin.qq.com/s/WaPpf20x7flfePP5-T7XIg| 
| 20221228 | 欧盟网络安全局 2022 年度威胁报告 | https://mp.weixin.qq.com/s/UDbOlnLfsD4pk_3PQCuGBw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20221228T13:34:17Z | CVE-2021-27645 | The nameserver caching daemon (nscd) in the GNU C Library (aka glibc or libc6) 2.29 through 2.33, when processing a request for netgroup lookup, may crash due to a double-free, potentially resulting in degraded service or Denial of Service on the local system. This is related to netgroupcache.c. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-27645 | | 
| 20221228T13:34:13Z | CVE-2021-3326 | The iconv function in the GNU C Library (aka glibc or libc6) 2.32 and earlier, when processing invalid input sequences in the ISO-2022-JP-3 encoding, fails an assertion in the code path and aborts the program, potentially resulting in a denial of service. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-3326 | | 
| 20221228T13:34:10Z | CVE-2022-3575 | Frauscher Sensortechnik GmbH FDS102 for FAdC R2 and FAdCi R2 v2.8.0 to v2.9.1 are vulnerable to malicious code upload without authentication by using the configuration upload function. This could lead to a complete compromise of the FDS102 device. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-3575 | | 
| 20221228T13:34:00Z | CVE-2022-42745 | CandidATS version 3.0.0 allows an external attacker to read arbitrary files from the server. This is possible because the application is vulnerable to XXE. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-42745 | | 
| 20221228T13:33:56Z | CVE-2022-42744 | CandidATS version 3.0.0 allows an external attacker to perform CRUD operations on the application databases. This is possible because the application does not correctly validate the entriesPerPage parameter against SQLi attacks. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-42744 | | 
| 20221228T13:33:53Z | CVE-2022-27894 | The Foundry Blobster service was found to have a cross-site scripting (XSS) vulnerability that could have allowed an attacker with access to Foundry to launch attacks against other users. This vulnerability is resolved in Blobster 3.228.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-27894 | | 
| 20221228T13:33:29Z | CVE-2022-40276 | Zettlr version 2.3.0 allows an external attacker to remotely obtain arbitrary local files on any client that attempts to view a malicious markdown file through Zettlr. This is possible because the application does not have a CSP policy (or at least not strict enough) and/or does not properly validate the contents of ma CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-40276 | | 
| 20221228T13:03:21Z | CVE-2022-31621 | MariaDB Server before 10.7 is vulnerable to Denial of Service. In extra/mariabackup/ds_xbstream.cc, when an error occurs (stream_ctxt->dest_file == NULL) while executing the method xbstream_open, the held lock is not released correctly, which allows local users to trigger a denial of service due to the deadlock. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-31621 | | 
| 20221228T13:03:17Z | CVE-2022-31624 | MariaDB Server before 10.7 is vulnerable to Denial of Service. While executing the plugin/server_audit/server_audit.c method log_statement_ex, the held lock lock_bigbuffer is not released correctly, which allows local users to trigger a denial of service due to the deadlock. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-31624 | | 
| 20221228T13:03:14Z | CVE-2022-31622 | MariaDB Server before 10.7 is vulnerable to Denial of Service. In extra/mariabackup/ds_compress.cc, when an error occurs (pthread_create returns a nonzero value) while executing the method create_worker_threads, the held lock is not released correctly, which allows local users to trigger a denial of service due to the  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-31622 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221228T04:43:34Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 282 | 66| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221228T13:32:22Z | BOTNET PAYLOAD | https://github.com/Hex1629/EXPLOIT_BINS | 0 | 0| 
| 20221228T13:02:20Z | In Jenkins 2.320 through 2.355 (both inclusive) and LTS 2.332.1 through LTS 2.332.3 (both inclusive) the help icon does not escape the feature name that is part of its tooltip, effectively undoing the fix for SECURITY-1955, resulting in a cross-site scripting (XSS) vulnerability exploitable by attackers with Job/Config CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-34170 | 0 | 0| 
| 20221228T13:02:09Z | In Jenkins 2.340 through 2.355 (both inclusive) the tooltip of the build button in list views supports HTML without escaping the job display name, resulting in a cross-site scripting (XSS) vulnerability exploitable by attackers with Job/Configure permission. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-34173 | 0 | 0| 
| 20221228T13:01:32Z | A vulnerability classified as problematic was found in Python 2.7.13. This vulnerability affects unknown code of the component pgAdmin4. The manipulation leads to uncontrolled search path. The attack can be initiated remotely. The exploit has been disclosed to the public and may be used. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2017-20052 | 0 | 0| 
| 20221228T12:57:46Z | HCL XPages applications are susceptible to a Cross Site Request Forgery (CSRF) vulnerability. An unauthenticated attacker could exploit this vulnerability to perform actions in the application on behalf of the logged in user. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-38660 | 0 | 0| 
| 20221228T12:57:15Z | BD Totalys MultiProcessor, versions 1.70 and earlier, contain hardcoded credentials. If exploited, threat actors may be able to access, modify or delete sensitive information, including electronic protected health information (ePHI), protected health information (PHI) and personally identifiable information (PII). Cust CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-40263 | 0 | 0| 
| 20221228T12:57:08Z | A vulnerability in a feature that monitors RADIUS requests on Cisco Identity Services Engine (ISE) Software could allow an unauthenticated, remote attacker to negatively affect the performance of an affected device. This vulnerability is due to insufficient management of system resources. An attacker could exploit this CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20937 | 0 | 0| 
| 20221228T12:55:26Z | Dell EMC Avamar versions 18.2,19.1,19.2,19.3,19.4 contain a plain-text password storage vulnerability. A high privileged user could potentially exploit this vulnerability, leading to a complete outage. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-36318 | 0 | 0| 
| 20221228T12:55:23Z | Dell EMC Avamar Server version 19.4 contains a plain-text password storage vulnerability in AvInstaller. A local attacker could potentially exploit this vulnerability, leading to the disclosure of certain user credentials. The attacker may be able to use the exposed credentials to access the vulnerable application with CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-36317 | 0 | 0| 
| 20221228T12:55:19Z | Openwsman, versions up to and including 2.6.9, are vulnerable to arbitrary file disclosure because the working directory of openwsmand daemon was set to root directory. A remote, unauthenticated attacker can exploit this vulnerability by sending a specially crafted HTTP request to openwsman server. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2019-3816 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221228T13:28:00Z | Null | https://github.com/liuyugeng/backdoor-attacks-against-dataset-distillation | 0 | 0| 
| 20221228T12:14:58Z | The d8s-dates for python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. A potential code execution backdoor inserted by third parties is the democritus-timezones package. The affected version of d8s-htm is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-44052 | 0 | 0| 
| 20221228T12:14:44Z | The d8s-xml for python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. A potential code execution backdoor inserted by third parties is the democritus-utility package. The affected version of d8s-htm is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-44054 | 0 | 0| 
| 20221228T12:14:40Z | The d8s-stats for python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. A potential code execution backdoor inserted by third parties is the democritus-math package. The affected version of d8s-htm is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-44051 | 0 | 0| 
| 20221228T12:14:36Z | The d8s-networking for python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. A potential code execution backdoor inserted by third parties is the democritus-user-agents package. The affected version of d8s-htm is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-44053 | 0 | 0| 
| 20221228T12:14:16Z | The d8s-networking for python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. A potential code execution backdoor inserted by third parties is the democritus-json package. The affected version of d8s-htm is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-44050 | 0 | 0| 
| 20221228T12:14:12Z | The d8s-strings for python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. A potential code execution backdoor inserted by third parties is the democritus-uuids package. The affected version of d8s-htm is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-43303 | 0 | 0| 
| 20221228T12:14:08Z | The d8s-timer for python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. A potential code execution backdoor inserted by third parties is the democritus-uuids package. The affected version of d8s-htm is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-43304 | 0 | 0| 
| 20221228T12:14:00Z | The d8s-python for python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. A potential code execution backdoor inserted by third parties is the democritus-algorithms package. The affected version of d8s-htm is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-43305 | 0 | 0| 
| 20221228T12:13:55Z | The d8s-timer for python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. A potential code execution backdoor inserted by third parties is the democritus-dates package. The affected version of d8s-htm is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-43306 | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221228T04:43:34Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 282 | 66| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221228T11:37:02Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8205 | 1789| 
| 20221228T10:50:29Z | ** DISPUTED ** This record was originally reported by the oss-fuzz project who failed to consider the security context in which JXPath is intended to be used and failed to contact the JXPath maintainers prior to requesting the CVE allocation. The CVE was then allocated by Google in breach of the CNA rules. After review CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-40159 | 0 | 0| 
| 20221228T09:29:44Z | ** DISPUTED ** This record was originally reported by the oss-fuzz project who failed to consider the security context in which JXPath is intended to be used and failed to contact the JXPath maintainers prior to requesting the CVE allocation. The CVE was then allocated by Google in breach of the CNA rules. After review CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-40160 | 0 | 0| 
| 20221228T09:08:17Z | Null | https://github.com/mrbooshehri/cmd-fuzzy-ssh | 0 | 0| 
| 20221228T07:42:38Z | Null | https://github.com/tommy0812/fuzzy-systems | 0 | 0| 
| 20221228T07:12:25Z | Null | https://github.com/putrisetya/Algoritma-Fuzzy-C-means- | 0 | 0| 
| 20221228T06:17:59Z | Null | https://github.com/NizamZidan10/Fuzzy-C-Means | 0 | 0| 
| 20221228T06:17:57Z | Null | https://github.com/annisashrmn22/Algoritma-Fuzzy-C-Means | 0 | 0| 
| 20221228T06:17:55Z | Null | https://github.com/Salmaashafira/algoritma-Fuzzy-C-Means | 0 | 0| 
| 20221228T01:23:52Z | Null | https://github.com/pit845/fuzzy-octo-waffle | 0 | 0| 



# 日更新程序
