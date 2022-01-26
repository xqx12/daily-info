# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210807 | fuzzing check分支概述 | https://mp.weixin.qq.com/s/7JdHPEo6DyxOjFuw1VMlqg| 
| 20210807 | weblogic Coherence 组件漏洞总结分析 | https://nosec.org/home/detail/4806.html| 
| 20210807 | 使用 GDB 获取软路由的文件系统 | https://mp.weixin.qq.com/s/FWprX-R1EfWrPMNa0WPedA| 
| 20210807 | 《党委（党组）网络安全工作责任制实施办法》解读 | https://mp.weixin.qq.com/s/ZzFx2Leu7DYhm39Kacofcg| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210807T20:08:18Z | CVE-2021-31799 | PoC for exploiting CVE-2021-31799 : In RDoc 3.11 through 6.x before 6.3.1, as distributed with Ruby through 3.0.1, it is possible to execute arbitrary code via , and tags in a filename. | https://github.com/AlAIAL90/CVE-2021-31799 | In RDoc 3.11 through 6.x before 6.3.1, as distributed with Ruby through 3.0.1, it is possible to execute arbitrary code via , and tags in a filename.| 
| 20210807T20:08:14Z | CVE-2021-20786 | PoC for exploiting CVE-2021-20786 : Cross-site request forgery (CSRF) vulnerability in GroupSession (GroupSession Free edition from ver2.2.0 to the version prior to ver5.1.0, GroupSession byCloud from ver3.0.3 to the version prior to ver5.1.0, and GroupSession ZION from ver3.0.3 to the version prior to ver5.1.0) allows a remote attacker to hijack the authentication of administrators via a specially crafted URL. | https://github.com/AlAIAL90/CVE-2021-20786 | Cross-site request forgery (CSRF) vulnerability in GroupSession (GroupSession Free edition from ver2.2.0 to the version prior to ver5.1.0, GroupSession byCloud from ver3.0.3 to the version prior to ver5.1.0, and GroupSession ZION from ver3.0.3 to the version prior to ver5.1.0) allows a remote attacker to hijack the authentication of administrators via a specially crafted URL.| 
| 20210807T20:08:10Z | CVE-2021-32558 | PoC for exploiting CVE-2021-32558 : An issue was discovered in Sangoma Asterisk 13.x before 13.38.3, 16.x before 16.19.1, 17.x before 17.9.4, and 18.x before 18.5.1, and Certified Asterisk before 16.8-cert10. If the IAX2 channel driver receives a packet that contains an unsupported media format, a crash can occur. | https://github.com/AlAIAL90/CVE-2021-32558 | An issue was discovered in Sangoma Asterisk 13.x before 13.38.3, 16.x before 16.19.1, 17.x before 17.9.4, and 18.x before 18.5.1, and Certified Asterisk before 16.8-cert10. If the IAX2 channel driver receives a packet that contains an unsupported media format, a crash can occur.| 
| 20210807T20:08:07Z | CVE-2021-35478 | PoC for exploiting CVE-2021-35478 : Nagios Log Server before 2.1.9 contains Reflected XSS in the dropdown box for the alert history and audit log function. All parameters used for filtering are affected. This affects users who open a crafted link or third-party web page. | https://github.com/AlAIAL90/CVE-2021-35478 | Nagios Log Server before 2.1.9 contains Reflected XSS in the dropdown box for the alert history and audit log function. All parameters used for filtering are affected. This affects users who open a crafted link or third-party web page.| 
| 20210807T20:08:00Z | CVE-2021-28165 | PoC for exploiting CVE-2021-28165 : In Eclipse Jetty 7.2.2 to 9.4.38, 10.0.0.alpha0 to 10.0.1, and 11.0.0.alpha0 to 11.0.1, CPU usage can reach 100% upon receiving a large invalid TLS frame. | https://github.com/AlAIAL90/CVE-2021-28165 | In Eclipse Jetty 7.2.2 to 9.4.38, 10.0.0.alpha0 to 10.0.1, and 11.0.0.alpha0 to 11.0.1, CPU usage can reach 100% upon receiving a large invalid TLS frame.| 
| 20210807T20:07:57Z | CVE-2021-29425 | PoC for exploiting CVE-2021-29425 : In Apache Commons IO before 2.7, When invoking the method FileNameUtils.normalize with an improper input string, like "//../foo", or "\\..\foo", the result would be the same value, thus possibly providing access to files in the parent directory, but not further above (thus "limited" path traversal), if the calling code would use the result to construct a path value. | https://github.com/AlAIAL90/CVE-2021-29425 | In Apache Commons IO before 2.7, When invoking the method FileNameUtils.normalize with an improper input string, like %//../foo%, or %\\..\foo%, the result would be the same value, thus possibly providing access to files in the parent directory, but not further above (thus %limited% path traversal), if the calling code would use the result to construct a path value.| 
| 20210807T20:07:53Z | CVE-2021-28169 | PoC for exploiting CVE-2021-28169 : For Eclipse Jetty versions <= 9.4.40, <= 10.0.2, <= 11.0.2, it is possible for requests to the ConcatServlet with a doubly encoded path to access protected resources within the WEB-INF directory. For example a request to `/concat?/%2557EB-INF/web.xml` can retrieve the web.xml file. This can reveal sensitive information regarding the implementation of a web application. | https://github.com/AlAIAL90/CVE-2021-28169 | For Eclipse Jetty versions <= 9.4.40, <= 10.0.2, <= 11.0.2, it is possible for requests to the ConcatServlet with a doubly encoded path to access protected resources within the WEB-INF directory. For example a request to `/concat?/%2557EB-INF/web.xml` can retrieve the web.xml file. This can reveal sensitive information regarding the implementation of a web application.| 
| 20210807T20:07:49Z | CVE-2021-35479 | PoC for exploiting CVE-2021-35479 : Nagios Log Server before 2.1.9 contains Stored XSS in the custom column view for the alert history and audit log function through the affected pp parameter. This affects users who open a crafted link or third-party web page. | https://github.com/AlAIAL90/CVE-2021-35479 | Nagios Log Server before 2.1.9 contains Stored XSS in the custom column view for the alert history and audit log function through the affected pp parameter. This affects users who open a crafted link or third-party web page.| 
| 20210807T20:07:46Z | CVE-2021-32610 | PoC for exploiting CVE-2021-32610 : In Archive_Tar before 1.4.14, symlinks can refer to targets outside of the extracted archive, a different vulnerability than CVE-2020-36193. | https://github.com/AlAIAL90/CVE-2021-32610 | In Archive_Tar before 1.4.14, symlinks can refer to targets outside of the extracted archive, a different vulnerability than CVE-2020-36193.| 
| 20210807T20:07:42Z | CVE-2021-36004 | PoC for exploiting CVE-2021-36004 : Adobe InDesign version 16.0 (and earlier) is affected by an Out-of-bounds Write vulnerability in the CoolType library. An unauthenticated attacker could leverage this vulnerability to achieve remote code execution in the context of the current user. Exploitation of this issue requires user interaction in that a victim must open a malicious file. | https://github.com/AlAIAL90/CVE-2021-36004 | Adobe InDesign version 16.0 (and earlier) is affected by an Out-of-bounds Write vulnerability in the CoolType library. An unauthenticated attacker could leverage this vulnerability to achieve remote code execution in the context of the current user. Exploitation of this issue requires user interaction in that a victim must open a malicious file.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210807T15:06:10Z | Whole Program LLVM: wllvm ported to go | https://github.com/SRI-CSL/gllvm | 147 | 22| 
| 20210807T14:32:44Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2524 | 60| 
| 20210807T03:23:16Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 219 | 35| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210807T22:50:38Z | Null | https://github.com/Buster-2002/Discord-Exploit | 0 | 1| 
| 20210807T22:38:50Z | Exploit para vulnerabilidade de sqli no Drupal 7.0 < 7.31 | https://github.com/Black-Catx/Drupal-Exploit | 0 | 0| 
| 20210807T22:24:33Z | bad robox ui lib | https://github.com/ceat-ceat/ScriptPanelv2 | 0 | 1| 
| 20210807T22:21:54Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9829 | 1625| 
| 20210807T22:19:19Z | Exploit Development CheatSheet. | https://github.com/V0lk3n/OSED-CheatSheet | 0 | 0| 
| 20210807T21:18:38Z | Null | https://github.com/TheCrazzXz/Exploits-Lab | 0 | 1| 
| 20210807T21:01:14Z | Writeups on my TryHackMe adventures! | https://github.com/Sma-Das/TryHackMe | 6 | 0| 
| 20210807T20:08:18Z | PoC for exploiting CVE-2021-31799 : In RDoc 3.11 through 6.x before 6.3.1, as distributed with Ruby through 3.0.1, it is possible to execute arbitrary code via , and tags in a filename. | https://github.com/AlAIAL90/CVE-2021-31799 | 0 | 0| 
| 20210807T20:08:14Z | PoC for exploiting CVE-2021-20786 : Cross-site request forgery (CSRF) vulnerability in GroupSession (GroupSession Free edition from ver2.2.0 to the version prior to ver5.1.0, GroupSession byCloud from ver3.0.3 to the version prior to ver5.1.0, and GroupSession ZION from ver3.0.3 to the version prior to ver5.1.0) allows a remote attacker to hijack the authentication of administrators via a specially crafted URL. | https://github.com/AlAIAL90/CVE-2021-20786 | 0 | 0| 
| 20210807T20:08:10Z | PoC for exploiting CVE-2021-32558 : An issue was discovered in Sangoma Asterisk 13.x before 13.38.3, 16.x before 16.19.1, 17.x before 17.9.4, and 18.x before 18.5.1, and Certified Asterisk before 16.8-cert10. If the IAX2 channel driver receives a packet that contains an unsupported media format, a crash can occur. | https://github.com/AlAIAL90/CVE-2021-32558 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210807T21:06:33Z | This tool gives developers, researchers and companies the ability to analyze software packages of different programming languages that are being or will be used in their codes, providing information that allows them to know in advance if this library complies with processes. secure development, if currently supported, possible backdoors (malicious embedded code), typosquatting analysis, the history of versions and reported vulnerabilities (CVEs) of the package. | https://github.com/Telefonica/packagedna | 5 | 0| 
| 20210807T20:54:07Z | Uses Apple%s MDM protocol to backdoor a device with a malicious profile. | https://github.com/MythicAgents/orthrus | 14 | 4| 
| 20210807T19:15:36Z | This backdoor can download and upload files execute programs in the victim machine and has full persistance. | https://github.com/K5e6Dtt/Backdoor | 0 | 0| 
| 20210807T15:35:08Z | Smooth penetration, more control, better speed and performance. ^_^ blackdoor | https://github.com/s3q/blackdoor | 2 | 0| 
| 20210807T14:25:46Z | 🤖An Evil and Smart Bot for Enslaving Windows Written in Rust and Python | https://github.com/wildonion/katyusha | 3 | 1| 
| 20210807T11:07:17Z | Null | https://github.com/EjHvorSerDuVildUdJim/backdoor | 0 | 0| 
| 20210807T09:02:59Z | POC for RCE backdoor in PHP 8.1.0 | https://github.com/vida00/Backdoor-PHP8.1.0 | 0 | 0| 
| 20210807T07:15:17Z | Null | https://github.com/FierzaEriez/Mini-Shell-Backdoor | 1 | 1| 
| 20210807T00:51:02Z | Welcome to RoSEC Security, a highly advanced security suite to protect your Roblox games from the newest threats, backdoors, and server-sided exploits. | https://github.com/Revoxelizer/RoSEC-Security | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210807T22:58:54Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 450 | 68| 
| 20210807T20:35:57Z | A symbolic execution engine for LLVM IR | https://github.com/insufficiently-caffeinated/caffeine | 7 | 4| 
| 20210807T15:48:09Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1743 | 500| 
| 20210807T04:08:43Z | A tool for generating nonlinear numerical invariants for C and Java programs.  DIG uses dynamic analysis to infer invariants over program execution traces and applies symbolic execution to inferred invariants. | https://github.com/unsat/dig | 4 | 4| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210807T22:59:13Z | Fast web fuzzer written in Go | https://github.com/ffuf/ffuf | 4930 | 574| 
| 20210807T22:50:40Z | Null | https://github.com/GeorgeOgeorge/fuzzy_eaj | 0 | 0| 
| 20210807T21:53:33Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210807T20:46:12Z | Null | https://github.com/iolson/fuzzyhat-nfts | 0 | 0| 
| 20210807T20:43:05Z | A Codice Fiscale Generator | https://github.com/tonyarris/codice-fuzzcale | 1 | 0| 
| 20210807T20:00:41Z | MATLAB code for the paper titled %A Self-Adaptive Fuzzy Learning System for Streaming Data Prediction%. | https://github.com/Gu-X/Self-Adaptive-Fuzzy-Learning-System | 0 | 0| 
| 20210807T19:29:41Z | Null | https://github.com/mogg411/fuzzy-octo-guacamole | 0 | 0| 
| 20210807T18:55:42Z | Fuzzy: contains code for a Fuzzy Engine and a Dynamical Systems Simulator (DySySim). | https://github.com/josokw/Fuzzy | 2 | 0| 
| 20210807T18:23:54Z | Null | https://github.com/lzhfromustc/goFuzz | 0 | 0| 
| 20210807T18:03:44Z | A fuzzer which allows to find bugs in Goost | https://github.com/goostengine/goost-fuzzer | 0 | 0| 



# 日更新程序
