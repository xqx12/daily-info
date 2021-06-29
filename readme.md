# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210629 | 利用 macOS CVE-2020-9971 XPC Services 提权漏洞逃逸 Microsoft Office App Sandbox | https://perception-point.io/using-cve-2020-9971-to-escape-microsoft-offices-app-sandbox/| 
| 20210629 | AEM CRX Bypass: The 0-day that took control over some enterprise AEM CRX Package Manager | https://labs.detectify.com/2021/06/28/aem-crx-bypass-0day-control-over-some-enterprise-aem-crx-package-manager/| 
| 20210629 | 惠普安全团队对 Snake Keylogger 的分析 | https://threatresearch.ext.hp.com/the-many-skins-of-snake-keylogger/| 
| 20210629 | Google ISC DHCP 软件随机数存在问题，导致攻击者可以通过网络攻击 Google Cloud Platform 虚拟机 | https://github.com/irsl/gcp-dhcp-takeover-code-exec| 
| 20210629 | ATM 机 NFC 模块固件存在漏洞，可通过手机 App 攻击 | https://arstechnica.com/information-technology/2021/06/nfc-flaws-let-researchers-hack-an-atm-by-waving-a-phone/| 
| 20210629 | 如何用 WinAFL 发现 Windows 图形设备接口 GDI+ 的 RCE 漏洞（CVE-2021-1665） | https://www.mcafee.com/blogs/other-blogs/mcafee-labs/analyzing-cve-2021-1665-remote-code-execution-vulnerability-in-windows-gdi/| 
| 20210629 | G DATA 研究团队发现微软为一个 Rootkit 驱动（Netfilter）签发了合法签名 | https://threatpost.com/microsoft-malicious-rootkit-gaming/167323/| 
| 20210629 | Adobe Acrobat Reader DC CVE-2020-9715 UAF 漏洞的分析和利用，来自 Exodus Intelligence | https://blog.exodusintel.com/2021/04/20/analysis-of-a-use-after-free-vulnerability-in-adobe-acrobat-reader-dc/?utm_source=rss&utm_medium=rss&utm_campaign=analysis-of-a-use-after-free-vulnerability-in-adobe-acrobat-reader-dc| 
| 20210629 | Certified Pre-Owned - Abusing Active Directory Certificate Services | https://www.specterops.io/assets/resources/Certified_Pre-Owned.pdf| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210629 | “重门深锁”FormBook Crypter 执行隐匿技术精析 | https://mp.weixin.qq.com/s/bfILTCvuaBASdmWTd4BnoQ| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210629T12:54:01Z | CVE-2021-31955 | Null | https://github.com/mavillon1/CVE-2021-31955-POC | Windows Kernel Information Disclosure Vulnerability| 
| 20210629T12:20:58Z | CVE-2021-22911 | Pre-Auth Blind NoSQL Injection leading to Remote Code Execution in Rocket Chat 3.12.1 | https://github.com/CsEnox/CVE-2021-22911 | | 
| 20210629T12:01:41Z | CVE-2020-15368 | How to exploit a vulnerable windows driver. Exploit for AsrDrv104.sys | https://github.com/stong/CVE-2020-15368 | | 
| 20210629T11:28:41Z | CVE-2020-3580 | Null | https://github.com/Hudi233/CVE-2020-3580 | Multiple vulnerabilities in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct cross-site scripting (XSS) attacks against a user of the web services interface of an affected device. The vulnerabilities are due to insufficient validation of user-supplied input by the web services interface of an affected device. An attacker could exploit these vulnerabilities by persuading a user of the interface to click a crafted link. A successful exploit could allow the attacker to execute arbitrary script code in the context of the interface or allow the attacker to access sensitive, browser-based information. Note: These vulnerabilities affect only specific AnyConnect and WebVPN configurations. For more information, see the Vulnerable Products section.| 
| 20210629T09:12:29Z | CVE-2021-32537 | PoC for CVE-2021-32537: an out-of-bounds memory access that leads to pool corruption in the Windows kernel. | https://github.com/0vercl0k/CVE-2021-32537 | 未查询到CVE信息| 
| 20210629T06:15:33Z | CVE-2021-27850 | A Proof of concept for CVE-2021-27850 affecting Apache Tapestry and leading to unauthencticated remote code execution. | https://github.com/kahla-sec/CVE-2021-27850_POC | A critical unauthenticated remote code execution vulnerability was found all recent versions of Apache Tapestry. The affected versions include 5.4.5, 5.5.0, 5.6.2 and 5.7.0. The vulnerability I have found is a bypass of the fix for CVE-2019-0195. Recap: Before the fix of CVE-2019-0195 it was possible to download arbitrary class files from the classpath by providing a crafted asset file URL. An attacker was able to download the file `AppModule.class` by requesting the URL `http://localhost:8080/assets/something/services/AppModule.class` which contains a HMAC secret key. The fix for that bug was a blacklist filter that checks if the URL ends with `.class`, `.properties` or `.xml`. Bypass: Unfortunately, the blacklist solution can simply be bypassed by appending a `/` at the end of the URL: `http://localhost:8080/assets/something/services/AppModule.class/` The slash is stripped after the blacklist check and the file `AppModule.class` is loaded into the response. This class usually contains the HMAC secret key which is used to sign serialized Java objects. With the knowledge of that key an attacker can sign a Java gadget chain that leads to RCE (e.g. CommonsBeanUtils1 from ysoserial). Solution for this vulnerability: * For Apache Tapestry 5.4.0 to 5.6.1, upgrade to 5.6.2 or later. * For Apache Tapestry 5.7.0, upgrade to 5.7.1 or later.| 
| 20210629T05:39:49Z | CVE-2021-35475 | Writeup for CVE-2021-35475; Stored Cross-Site Scripting(XSS) on SAS® Environment Manager 2.5 | https://github.com/saitamang/CVE-2021-35475 | SAS Environment Manager 2.5 allows XSS through the Name field when creating/editing a server. The XSS will prompt when editing the Configuration Properties.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T10:42:50Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 685 | 15| 
| 20210629T00:31:42Z | Null | https://github.com/kleelab/kleelab.github.io | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T12:17:11Z | cicd logic and gitlab&github runner&jenkins agent container, centos base ,whith jdk/python/go, maven/npm,/kubectl/helm | https://github.com/chimeh/cicd-s2e-runner | 2 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T12:51:43Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 17 | 11| 
| 20210629T12:50:03Z | RCE exploit for a .NET JSON deserialization vulnerability in Telerik UI for ASP.NET AJAX. | https://github.com/noperator/CVE-2019-18935 | 195 | 56| 
| 20210629T12:42:41Z | 蓝凌OA漏洞利用工具 | https://github.com/yuanhaiGreg/LandrayExploit | 4 | 1| 
| 20210629T12:41:34Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9610 | 1574| 
| 20210629T12:33:22Z | Null | https://github.com/TheCrazzXz/Exploits-Lab | 0 | 0| 
| 20210629T12:26:43Z | Command line exploit. Use OS vulnerabilities to spy client connect to a server by opening a file. | https://github.com/MoryokaV/Activity-Exploit | 0 | 0| 
| 20210629T12:10:20Z | A convenient script that provides the bare essentials for exploiting such as ESP, freecam and aimbot. | https://github.com/TheDookySoo/Essentials | 1 | 0| 
| 20210629T12:02:59Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 25 | 12| 
| 20210629T11:23:22Z | Development of code to exploit LSST and VISTA imaging | https://github.com/lsst-uk/lsst-ir-fusion | 0 | 0| 
| 20210629T11:08:57Z | BioCCP.jl exploits the Coupon Collector Problem for sample size determination in combinatorial biotechnology. | https://github.com/kirstvh/BioCCP | 2 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T12:26:43Z | A static analysis tool to reveal backdoor threats in Ethereum smart contracts | https://github.com/SmartContractBackdoor/DPiper-tool | 2 | 0| 
| 20210629T09:13:27Z | A Python module for building botnet ,backdoor or trojan with Telegram control panel | https://github.com/onionj/pybotnet | 2 | 2| 
| 20210629T07:42:52Z | Code and data of the ACL 2021 paper %Turn the Combination Lock: Learnable Textual Backdoor Attacks via Word Substitution% | https://github.com/thunlp/BkdAtk-LWS | 2 | 0| 
| 20210629T07:15:00Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 209 | 40| 
| 20210629T07:01:52Z | Encipher - Generate XOR encoded backdoors using Python | https://github.com/Revise7/Encipher | 0 | 0| 
| 20210629T06:59:17Z |  SniperSight - Listener, Backdoor & Keylogger Generator Developed & Maintained By revise7 | https://github.com/Revise7/SniperSight | 0 | 0| 
| 20210629T06:53:03Z | shell backdoor | https://github.com/rabeltester44/reapers | 0 | 0| 
| 20210629T03:18:26Z | %Socialx% is a Social Engineering And Remote Access Trojan Tool. You can generate fud backdoor and you can embed any file you want inside of the exe file. | https://github.com/AzizKpln/Social_X | 119 | 34| 
| 20210629T02:40:51Z | Null | https://github.com/ShannonAI/backdoor_nlg | 2 | 2| 
| 20210629T01:43:01Z | Null | https://github.com/0zzam0/backdoor_attack | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T11:08:06Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1724 | 495| 
| 20210629T08:49:39Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 144 | 33| 
| 20210629T02:57:53Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 14 | 3| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T09:53:05Z | Code to run the evaluation of our %Obfuscated Access and Search Patterns in Searchable Encryption%, NDSS%21 | https://github.com/simon-oya/NDSS21-osse-evaluation | 2 | 1| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210629T12:43:53Z | Tool for synchronizing saves for games via synchronization services like Dropbox or OwnCloud | https://github.com/manuelVo/fuzzy-robot | 1 | 0| 
| 20210629T12:40:03Z | Null | https://github.com/DanielEbert/EmulatedFirmwareFuzzing | 0 | 0| 
| 20210629T12:29:40Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6429 | 1308| 
| 20210629T12:15:12Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 13 | 6| 
| 20210629T12:00:52Z | a fuzzier graph plotting method | https://github.com/autumnull/fuzzyplot | 0 | 0| 
| 20210629T11:58:44Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210629T11:50:41Z | Null | https://github.com/danilomachadopires/FuzzyASOC | 0 | 0| 
| 20210629T10:25:41Z | My personal portfolio website | https://github.com/FuzzyGrim/fuzzygrim.github.io | 0 | 0| 
| 20210629T09:47:47Z | Fuzzing en español | https://github.com/0xVIC/Diccionarios | 1 | 0| 
| 20210629T09:35:37Z | Null | https://github.com/lizaorsini346/fuzzy-parakeet | 0 | 0| 



# 日更新程序
