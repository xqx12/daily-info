# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210630 | 玄武实验室去年报告微软的 Windows Printer Spooler 远程代码执行漏洞 (CVE-2021-1675)已于 6 月初被修复，昨天 GitHub 上出现了该漏洞的 PoC 代码（ https://github.com/blackorbird/PrintNightmare ），建议用户尽快更新系统修复该漏洞。 | https://xlab.tencent.com/cn/2021/06/21/xlab-21-001/| 
| 20210630 | Chrome 浏览器 NAT Slipstreaming 漏洞分析（CVE-2021–21210） | https://vovohelo.medium.com/how-i-found-my-first-chrome-bug-cve-2021-21210-248a21272248| 
| 20210630 | 7 亿条 LinkedIn 疑似泄露数据正在 RaidForums 论坛被出售 | https://www.privacysharks.com/exclusive-700-million-linkedin-records-for-sale-on-hacker-forum-june-22nd-2021/| 
| 20210630 | Binary code-coverage fuzzer for macOS, based on libFuzzer and LLVM | https://github.com/ant4g0nist/ManuFuzzer| 
| 20210630 | Metadata service MITM allows root privilege escalation (EKS / GKE) | https://blog.champtar.fr/Metadata_MITM_root_EKS_GKE/| 
| 20210630 | Pre-auth RCE in ForgeRock OpenAM (CVE-2021-35464) | https://portswigger.net/research/pre-auth-rce-in-forgerock-openam-cve-2021-35464| 
| 20210630 | Project Zero 研究员利用 KVM AMD 相关组件代码漏洞实现虚拟机逃逸（CVE-2021-29657） | https://googleprojectzero.blogspot.com/2021/06/an-epyc-escape-case-study-of-kvm.html| 
| 20210630 | 卡巴斯基团队对多款线上约会 App 的隐私安全性分析 | https://securelist.com/dating-apps-report-2021/103000/| 
| 20210630 | 利用 dlopen 外的另一个 API 可以在 App 内成功绕过 GateKeeper 加载被 Quarantined 的 dylib | https://theevilbit.github.io/posts/gatekeeper_not_a_bypass/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210630T12:31:30Z | CVE-2020-15368 | How to exploit a vulnerable windows driver. Exploit for AsrDrv104.sys | https://github.com/stong/CVE-2020-15368 | AsrDrv103.sys in the ASRock RGB Driver does not properly restrict access from user space, as demonstrated by triggering a triple fault via a request to zero CR3.| 
| 20210630T12:31:21Z | CVE-2021-1675 | Impacket implementation of CVE-2021-1675 | https://github.com/cube0x0/CVE-2021-1675 | Windows Print Spooler Elevation of Privilege Vulnerability| 
| 20210630T10:27:56Z | CVE-2021-1675 | CVE-2021-1675 exploit | https://github.com/yu2u/CVE-2021-1675 | Windows Print Spooler Elevation of Privilege Vulnerability| 
| 20210630T09:38:35Z | CVE-2021-27850 | A Proof of concept for CVE-2021-27850 affecting Apache Tapestry and leading to unauthencticated remote code execution. | https://github.com/kahla-sec/CVE-2021-27850_POC | A critical unauthenticated remote code execution vulnerability was found all recent versions of Apache Tapestry. The affected versions include 5.4.5, 5.5.0, 5.6.2 and 5.7.0. The vulnerability I have found is a bypass of the fix for CVE-2019-0195. Recap: Before the fix of CVE-2019-0195 it was possible to download arbitrary class files from the classpath by providing a crafted asset file URL. An attacker was able to download the file `AppModule.class` by requesting the URL `http://localhost:8080/assets/something/services/AppModule.class` which contains a HMAC secret key. The fix for that bug was a blacklist filter that checks if the URL ends with `.class`, `.properties` or `.xml`. Bypass: Unfortunately, the blacklist solution can simply be bypassed by appending a `/` at the end of the URL: `http://localhost:8080/assets/something/services/AppModule.class/` The slash is stripped after the blacklist check and the file `AppModule.class` is loaded into the response. This class usually contains the HMAC secret key which is used to sign serialized Java objects. With the knowledge of that key an attacker can sign a Java gadget chain that leads to RCE (e.g. CommonsBeanUtils1 from ysoserial). Solution for this vulnerability: * For Apache Tapestry 5.4.0 to 5.6.1, upgrade to 5.6.2 or later. * For Apache Tapestry 5.7.0, upgrade to 5.7.1 or later.| 
| 20210630T08:19:25Z | CVE-2021-31955 | Null | https://github.com/mavillon1/CVE-2021-31955-POC | Windows Kernel Information Disclosure Vulnerability| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210630T08:42:31Z | Null | https://github.com/fontworks-fonts/Klee | 463 | 13| 
| 20210630T00:31:56Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 686 | 16| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210630T12:14:26Z | Knowledge base of exploit mitigations available across numerous  operating systems, architectures and applications and versions. | https://github.com/nccgroup/exploit_mitigations | 5 | 1| 
| 20210630T12:14:07Z | Null | https://github.com/AnaCosteira/PostExploitTools | 0 | 0| 
| 20210630T12:03:51Z | Null | https://github.com/evilbuffer/malware-and-exploitdev-resources | 9 | 1| 
| 20210630T12:03:11Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 25 | 12| 
| 20210630T11:36:10Z | learning various heap exploitation techniques | https://github.com/izabela-am/Heap-Exploitation | 0 | 0| 
| 20210630T11:09:40Z | KoGaMa Cheats / exploits | https://github.com/Hxrpiee/KoGaMa | 1 | 0| 
| 20210630T11:02:13Z | BioCCP.jl exploits the Coupon Collector Problem for sample size determination in combinatorial biotechnology. | https://github.com/kirstvh/BioCCP | 2 | 0| 
| 20210630T10:53:05Z | This repository contains hints to exploit and capture flag of  CTF machines from various platforms. this isn%t a detailed walk-through. from some boxes which I hunt. | https://github.com/nibrasmuhamed/CTF-Walkthrough | 0 | 0| 
| 20210630T10:43:21Z | A convenient script that provides the bare essentials for exploiting such as ESP, freecam and aimbot. | https://github.com/TheDookySoo/Essentials | 1 | 0| 
| 20210630T10:37:53Z | Null | https://github.com/ColdFusionX/ColdFusionX.github.io | 2 | 3| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210630T12:18:58Z | EcchiExploit Shell v1.0 | https://github.com/dmzhari/ecchi-shell | 0 | 0| 
| 20210630T06:52:25Z | Code and data of the ACL-IJCNLP 2021 paper %Hidden Killer: Invisible Textual Backdoor Attacks with Syntactic Trigger% | https://github.com/thunlp/HiddenKiller | 1 | 2| 
| 20210630T03:03:36Z | Hanoman is an GUI antivirus engine singature based detection 🐒 | https://github.com/hrtywhy/Hanoman | 5 | 5| 
| 20210630T00:09:23Z | Null | https://github.com/FierzaEriez/Mini-Shell-Backdoor | 1 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210630T05:15:07Z | Use angr in Ghidra | https://github.com/Nalen98/AngryGhidra | 307 | 21| 
| 20210630T02:13:22Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 14 | 3| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210630T12:30:25Z | A library of fuzzy rough machine learning algorithms | https://github.com/oulenz/fuzzy-rough-learn | 6 | 2| 
| 20210630T12:25:37Z | Ethereum smart contract fuzzer | https://github.com/crytic/echidna | 667 | 103| 
| 20210630T12:20:35Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6437 | 1309| 
| 20210630T12:16:40Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 466 | 42| 
| 20210630T12:03:41Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3578 | 832| 
| 20210630T11:57:15Z | This is a tool for fuzzing XSS vulnerabilities based on genetic algorithm. | https://github.com/Timofey21/darlene | 3 | 0| 
| 20210630T11:52:10Z | RESTler is the first stateful REST API fuzzing tool for automatically testing cloud services through their REST APIs and finding security and reliability bugs in these services. | https://github.com/microsoft/restler-fuzzer | 926 | 95| 
| 20210630T11:45:03Z | Null | https://github.com/bhattacharjee/fuzzy-funicular | 0 | 0| 
| 20210630T11:37:26Z | Null | https://github.com/s9varesc/url-fuzzing-docker | 0 | 0| 
| 20210630T11:24:21Z | Null | https://github.com/Kineubdgahe/fuzzy-spork | 0 | 0| 



# 日更新程序
