# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210503 | pystinger：通过webshell实现SOCK4代理与端口映射工具。 | https://securityonline.info/pystinger-bypass-firewall-for-traffic-forwarding-using-webshell/| 
| 20210503 | 恶意软件分析：针对Ragnarok勒索软件。 | https://www.reddit.com/r/ReverseEngineering/comments/n1771o/malware_analysis_ragnarok_ransomware/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210504 | FTPServer的Fuzzing | https://mp.weixin.qq.com/s/ezo0W22-igu8uhnbO8sR-Q| 
| 20210504 | 解析以色列网络空间作战力量 | https://mp.weixin.qq.com/s/4QvU3yHKVbLzTupW4aF37Q| 
| 20210503 | SecWiki周刊（第374期) | https://www.sec-wiki.com/weekly/374| 
| 20210502 | 工作中常用的相似度算法以及特征提取算法 | https://mp.weixin.qq.com/s/vUS553WX8pFIiWoqhkFNlg| 
| 20210502 | 云安全架构连载之三-超大型企业混合云安全架构最佳实践 | https://mp.weixin.qq.com/s/xkeNxE99ORtVs9EOv0ellQ| 
| 20210502 | 前端安全—你必须要注意的依赖安全漏洞 | https://mp.weixin.qq.com/s/kCqD0ikh9h5xc42sKkESVA| 
| 20210502 | 前端安全编码规范 | https://mp.weixin.qq.com/s/C-nXBRNvLA2-gcJV3W8Opg| 
| 20210502 | 浅谈前端代码加密 | https://mp.weixin.qq.com/s/UqGA97TLEn5BkzjVDX_EhA| 
| 20210502 | 网络安全创业的这点破事 | https://mp.weixin.qq.com/s/fHuci5HptS8Vchm9FVKxig| 
| 20210502 | 做为攻击者那些年的一些想法 | https://mp.weixin.qq.com/s/TtV01MA2C6ZJQG5wtFOSBg| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210505T00:27:59Z | CVE-2021-0261 | Null | https://github.com/GoogleProjectZer0/CVE-2021-0261 | A vulnerability in the HTTP/HTTPS service used by J-Web, Web Authentication, Dynamic-VPN (DVPN), Firewall Authentication Pass-Through with Web-Redirect, and Captive Portal allows an unauthenticated attacker to cause an extended Denial of Service (DoS) for these services by sending a high number of specific requests. This issue affects: Juniper Networks Junos OS 12.3 versions prior to 12.3R12-S17 on EX Series; 12.3X48 versions prior to 12.3X48-D105 on SRX Series; 15.1 versions prior to 15.1R7-S8; 15.1X49 versions prior to 15.1X49-D230 on SRX Series; 16.1 versions prior to 16.1R7-S8; 17.4 versions prior to 17.4R2-S12, 17.4R3-S3; 18.1 versions prior to 18.1R3-S11; 18.2 versions prior to 18.2R3-S6; 18.3 versions prior to 18.3R2-S4, 18.3R3-S3; 18.4 versions prior to 18.4R2-S5, 18.4R3-S4; 19.1 versions prior to 19.1R2-S2, 19.1R3-S2; 19.2 versions prior to 19.2R1-S5, 19.2R3; 19.3 versions prior to 19.3R2-S4, 19.3R3; 19.4 versions prior to 19.4R1-S3, 19.4R2-S2, 19.4R3; 20.1 versions prior to 20.1R1-S3, 20.1R2; 20.2 versions prior to 20.2R1-S1, 20.2R2.| 
| 20210505T00:27:54Z | CVE-2021-0259 | Null | https://github.com/GoogleProjectZer0/CVE-2021-0259 | Due to a vulnerability in DDoS protection in Juniper Networks Junos OS and Junos OS Evolved on QFX5K Series switches in a VXLAN configuration, instability might be experienced in the underlay network as a consequence of exceeding the default ddos-protection aggregate threshold. If an attacker on a client device on the overlay network sends a high volume of specific, legitimate traffic in the overlay network, due to an improperly detected DDoS violation, the leaf might not process certain L2 traffic, sent by spines in the underlay network. Continued receipt and processing of the high volume traffic will sustain the Denial of Service (DoS) condition. This issue affects: Juniper Networks Junos OS on QFX5K Series: 17.3 versions prior to 17.3R3-S11; 17.4 versions prior to 17.4R3-S5; 18.1 versions prior to 18.1R3-S13; 18.2 versions prior to 18.2R2-S8, 18.2R3-S8; 18.3 versions prior to 18.3R3-S5; 18.4 versions prior to 18.4R1-S8, 18.4R2-S6, 18.4R3-S6; 19.1 versions prior to 19.1R3-S4; 19.2 versions prior to 19.2R1-S6, 19.2R3-S2; 19.3 versions prior to 19.3R3-S2; 19.4 versions prior to 19.4R2-S4, 19.4R3-S1; 20.1 versions prior to 20.1R2; 20.2 versions prior to 20.2R2; 20.3 versions prior to 20.3R1-S2, 20.3R2. Juniper Networks Junos OS Evolved on QFX5220: All versions prior to 20.3R2-EVO.| 
| 20210505T00:15:59Z | CVE-2021-25327 | Null | https://github.com/GoogleProjectZer0/CVE-2021-25327 | Skyworth Digital Technology RN510 V.3.1.0.4 contains a cross-site request forgery (CSRF) vulnerability in /cgi-bin/net-routeadd.asp and /cgi-bin/sec-urlfilter.asp. Missing CSRF protection in devices can lead to XSRF, as the above pages are vulnerable to cross-site scripting (XSS).| 
| 20210505T00:15:55Z | CVE-2021-25328 | Null | https://github.com/GoogleProjectZer0/CVE-2021-25328 | Skyworth Digital Technology RN510 V.3.1.0.4 RN510 V.3.1.0.4 contains a buffer overflow vulnerability in /cgi-bin/app-staticIP.asp. An authenticated attacker can send a specially crafted request to endpoint which can lead to a denial of service (DoS) or possible code execution on the device.| 
| 20210505T00:15:51Z | CVE-2021-0262 | Null | https://github.com/GoogleProjectZer0/CVE-2021-0262 | Through routine static code analysis of the Juniper Networks Junos OS software codebase, the Secure Development Life Cycle team identified a Use After Free vulnerability in PFE packet processing on the QFX10002-60C switching platform. Exploitation of this vulnerability may allow a logically adjacent attacker to trigger a Denial of Service (DoS). Continued exploitation of this vulnerability will sustain the Denial of Service (DoS) condition. This issue only affects QFX10002-60C devices. No other product or platform is vulnerable to this issue. This issue affects Juniper Networks Junos OS on QFX10002-60C: 19.1 version 19.1R3-S1 and later versions; 19.1 versions prior to 19.1R3-S3; 19.2 version 19.2R2 and later versions; 19.2 versions prior to 19.2R3-S1; 20.2 versions prior to 20.2R1-S2. This issue does not affect Juniper Networks Junos OS: versions prior to 19.1R3; 19.2 versions prior to 19.2R2; any version of 19.3; version 20.2R2 and later releases.| 
| 20210504T22:25:53Z | cve-2020-10977 | GitLab Arbitrary File Read Exploit | https://github.com/nickvdyck/gitlab-cve-2020-10977 | GitLab EE/CE 8.5 to 12.9 is vulnerable to a an path traversal when moving an issue between projects.| 
| 20210504T19:08:13Z | CVE-2021-3138 | Discource POC | https://github.com/Mesh3l911/CVE-2021-3138 | In Discourse 2.7.0 through beta1, a rate-limit bypass leads to a bypass of the 2FA requirement for certain forms.| 
| 20210504T16:48:39Z | CVE-2021-28480 | PoC for exploiting RCE in Exchange CVEs: CVE-2021-28480, CVE-2021-28481, CVE-2021-28482 and CVE-2021-28483.  Achieves Domain Admin on Exchange Servers running Windows Server 2003 up to Windows Server 2019. | https://github.com/ZephrFish/ExchangeRCE-CVE-2021-28480 | | 
| 20210504T16:47:40Z | CVE-2020-1350 | HoneyPoC: Proof-of-Concept (PoC) script to exploit SIGRed (CVE-2020-1350). Achieves Domain Admin on Domain Controllers running Windows Server 2000 up to Windows Server 2019. | https://github.com/ZephrFish/CVE-2020-1350 | A remote code execution vulnerability exists in Windows Domain Name System servers when they fail to properly handle requests, aka %Windows DNS Server Remote Code Execution Vulnerability%.| 
| 20210504T16:27:02Z | CVE-2021-30128 | CVE-2021-30128 Apache OFBiz 反序列化漏洞远程代码执行 | https://github.com/r0ckysec/CVE-2021-30128 | Apache OFBiz has unsafe deserialization prior to 17.12.07 version| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210504T16:30:10Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 437 | 11| 
| 20210504T13:58:24Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1680 | 491| 
| 20210504T13:50:49Z | OVO | https://github.com/iKleeOVO/iKleeOVO.github.io | 0 | 1| 
| 20210504T12:00:35Z | ovo | https://github.com/Mtoly/klee.github.io | 0 | 0| 
| 20210504T10:13:09Z | 99484C Worlds Code | https://github.com/Jython1415/penguin-Klee | 1 | 0| 
| 20210504T05:41:39Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 9 | 1| 
| 20210504T05:36:28Z | An opiniated Next TypeScript powered starter which include Klee, emotion / styled-system, framer motion, jest and Cypress | https://github.com/Liinkiing/next-ts-klee-starter | 0 | 0| 
| 20210503T22:04:49Z | Null | https://github.com/realAyinde/kleenfoods | 0 | 0| 
| 20210503T08:15:27Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 216 | 35| 
| 20210503T01:46:20Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 11 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210505T00:51:02Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 16 | 11| 
| 20210505T00:29:28Z | Kubernetes security and vulnerability tools and utilities. | https://github.com/kris-nova/hack | 9 | 1| 
| 20210505T00:23:48Z | lab_tool is a system that allows you to do ethical hacking tests. | https://github.com/dylan14567/lab_tool | 1 | 3| 
| 20210505T00:06:55Z | Hello, I had said in my ret2sys/ret2libc exploit attack write-up i%d be making another write-up for binaries with exploit mitigations such as NX and ASLR on, and today is that day I will start to work on my writeup! | https://github.com/Ret2plt/Ret2plt-Exploit-write-up | 0 | 0| 
| 20210505T00:02:54Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 22 | 9| 
| 20210504T23:57:41Z | FULL-W2V: Fully Exploiting Data Reuse for W2V on GPU-Accelerated Systems | https://github.com/tlranda/FULL-W2V | 0 | 0| 
| 20210504T23:43:41Z |  Just another project for monitoring public exploits for CVEs | https://github.com/ARPSyndicate/cvemon | 0 | 0| 
| 20210504T23:02:43Z | Raspberry Pi 0 automate Exploitation OSINT  | https://github.com/F0rbidden-Equation/Pi_OSINT | 0 | 0| 
| 20210504T22:40:34Z | Small crash client base for retarded(german) people who steal other people%s code. | https://github.com/narumii/Niko | 9 | 0| 
| 20210504T22:25:53Z | GitLab Arbitrary File Read Exploit | https://github.com/nickvdyck/gitlab-cve-2020-10977 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210505T00:34:57Z | Small and convenient C2 tool for Windows targets | https://github.com/Cr4sh/MicroBackdoor | 143 | 25| 
| 20210505T00:30:29Z | Simple Python Backdoor | https://github.com/zNairy/Sonaris | 6 | 0| 
| 20210504T20:58:22Z | LKM rootkit for Linux Kernels 2.6.x/3.x/4.x/5.x (x86/x86_64 and ARM64) | https://github.com/m0nad/Diamorphine | 764 | 283| 
| 20210504T17:49:50Z | A Simple android remote administration tool using sockets. It uses java on the client side and python on the server side | https://github.com/karma9874/AndroRAT | 213 | 100| 
| 20210504T16:40:19Z | Python 3 IRC Bot / Botnet | https://github.com/trackmastersteve/HackServ | 19 | 16| 
| 20210504T15:27:43Z | the dashboard for managing the backdoor data for the luxr system | https://github.com/EDMONDGIHOZO/luxr_dashboard | 0 | 0| 
| 20210504T13:39:33Z | Gel4y mini shell backdoor | https://github.com/Kedjaw3n/Backdoor | 0 | 0| 
| 20210504T11:08:54Z | Null | https://github.com/Hem1700/backdoor | 0 | 0| 
| 20210504T11:08:45Z | PCI Express DIY hacking toolkit for Xilinx SP605 | https://github.com/Cr4sh/s6_pcie_microblaze | 342 | 87| 
| 20210504T10:41:20Z | Hanoman is an GUI antivirus engine singature based detection 🐒 | https://github.com/hrtywhy/Hanoman | 1 | 1| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210505T00:55:30Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 67 | 15| 
| 20210505T00:53:16Z | CS 4152 Project | https://github.com/nicbarone/Fuzzy-Kiwi | 0 | 0| 
| 20210505T00:51:08Z | Null | https://github.com/paul-gomes/Neuro-Fuzzy-System | 0 | 0| 
| 20210505T00:46:04Z | Cyber ​​Lab - Protection | https://github.com/Nadavkeysar/Fuzzing | 0 | 0| 
| 20210505T00:30:30Z | Coding practice for HTML/CSS/anything else web based | https://github.com/FuzzyPumpkin/FuzzyPumpkin.github.io | 5 | 1| 
| 20210505T00:19:22Z | Null | https://github.com/rittermi/Feeling-Fuzzy | 0 | 0| 
| 20210505T00:03:41Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 278 | 37| 
| 20210504T23:56:18Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 302 | 23| 
| 20210504T23:03:38Z | Fuzz testing for go. | https://github.com/google/gofuzz | 1038 | 97| 
| 20210504T22:15:47Z | FormatFuzzer is a framework for high-efficiency, high-quality generation and parsing of binary inputs. | https://github.com/uds-se/FormatFuzzer | 122 | 13| 



# 日更新程序
