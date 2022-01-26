# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210413 | CVE-2021-29627：由于 FreeBSD 的 accept_filter 处理程序错误而留下一个空指针，可能被利用于内核提权。 | https://github.com/raymontag/cve-2021-29627| 
| 20210413 | Process Herpaderping：通过在映像映射后修改磁盘上的内容来掩盖进程意图的方法。 | https://movaxbx.ru/2021/04/11/process-herpaderping/| 
| 20210413 | Chrome 和Firefox 等浏览器的 WebDriver REST APIs RCE 分析。 | https://starlabs.sg/blog/2021/04/you-talking-to-me/| 
| 20210413 | SSRF 漏洞可能的攻击方式列表。 | https://github.com/assetnote/blind-ssrf-chains| 
| 20210413 | 介绍为什么 macOS EDR（Endpoint Detection and Response）不应该运行在 Rosetta 2 下。 | https://www.sentinelone.com/blog/why-your-macos-edr-solution-shouldnt-be-running-under-rosetta-2/| 
| 20210413 | PD Actions：使用 GitHub Actions 实现自动化的安全工作流程。 | https://blog.projectdiscovery.io/github-actions-for-application-security/| 
| 20210413 | 在 Tesla Model 3 上利用 CVE-2020-6418。 | https://leethax0.rs/2021/04/ElectricChrome/| 
| 20210413 | 关于内核漏洞的原理分析。 | http://www.yuque.com/posec/public/sp9bs1| 
| 20210413 | 针对CycloneTCP上的远程拒绝服务漏洞（CVE-2021-26788） | https://blog.quarkslab.com/remote-denial-of-service-on-cyclonetcp-cve-2021-26788.html| 
| 20210413 | AT＆T 3B2与3B5计算机驱动程序设计指南手册。 | https://archive.org/details/Att3b2And3b5ComputerDriverDesignGuide| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210413 | 微信小程序反编译 | https://www.sec-in.com/article/1012| 
| 20210413 | 从BCTF人机对抗视角浅谈自动化攻防技术发展 | https://mp.weixin.qq.com/s/5wR37FLoTPn3fftxZw_Brw| 
| 20210413 | MindAPI: Bringing order to API hacking chaos | https://github.com/dsopas/MindAPI| 
| 20210413 | 主流WebShell工具流量层分析 | https://xz.aliyun.com/t/9404| 
| 20210413 | Spring Boot Fat Jar 写文件漏洞到稳定 RCE 的探索 | https://landgrey.me/blog/22/| 
| 20210413 | SmartyPHP沙箱逃逸分析 | https://www.anquanke.com/post/id/235505| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210413T21:13:25Z | CVE-2020-5902 | Auto exploit RCE CVE-2020-5902  | https://github.com/haisenberg/CVE-2020-5902 | In BIG-IP versions 15.0.0-15.1.0.3, 14.1.0-14.1.2.5, 13.1.0-13.1.3.3, 12.1.0-12.1.5.1, and 11.6.1-11.6.5.1, the Traffic Management User Interface (TMUI), also referred to as the Configuration utility, has a Remote Code Execution (RCE) vulnerability in undisclosed pages.| 
| 20210413T19:15:08Z | CVE-2020-14368 | Interactive RCE exploit demo for Eclipse CHE | https://github.com/codingchili/CVE-2020-14368 | A flaw was found in Eclipse Che in versions prior to 7.14.0 that impacts CodeReady Workspaces. When configured with cookies authentication, Theia IDE doesn%t properly set the SameSite value, allowing a Cross-Site Request Forgery (CSRF) and consequently allowing a cross-site WebSocket hijack on Theia IDE. This flaw allows an attacker to gain full access to the victim%s workspace through the /services endpoint. To perform a successful attack, the attacker conducts a Man-in-the-middle attack (MITM) and tricks the victim into executing a request via an untrusted link, which performs the CSRF and the Socket hijack. The highest threat from this vulnerability is to confidentiality, integrity, as well as system availability.| 
| 20210413T16:11:40Z | cve-2021-29627 | Trigger-only for CVE-2021-29627 | https://github.com/raymontag/cve-2021-29627 | In FreeBSD 13.0-STABLE before n245050, 12.2-STABLE before r369525, 13.0-RC4 before p0, and 12.2-RELEASE before p6, listening socket accept filters implementing the accf_create callback incorrectly freed a process supplied argument string. Additional operations on the socket can lead to a double free or use after free.| 
| 20210413T15:33:32Z | CVE-2020-14882 | Null | https://github.com/nice0e3/CVE-2020-14882_Exploit_Gui | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210413T14:26:49Z | CVE-2021-3138 | Disource POC | https://github.com/Mesh3l911/CVE-2021-3138 | In Discourse 2.7.0 through beta1, a rate-limit bypass leads to a bypass of the 2FA requirement for certain forms.| 
| 20210413T11:44:17Z | CVE-2020-17519 | CVE-2020-17519 Cheetah | https://github.com/givemefivw/CVE-2020-17519 | A change introduced in Apache Flink 1.11.0 (and released in 1.11.1 and 1.11.2 as well) allows attackers to read any file on the local filesystem of the JobManager through the REST interface of the JobManager process. Access is restricted to files accessible by the JobManager process. All users should upgrade to Flink 1.11.3 or 1.12.0 if their Flink instance(s) are exposed. The issue was fixed in commit b561010b0ee741543c3953306037f00d7a9f0801 from apache/flink:master.| 
| 20210413T09:07:38Z | CVE-2021-6666 | Null | https://github.com/givemefivw/CVE-2021-6666 | 未查询到CVE信息| 
| 20210413T04:26:27Z | CVE-2021-26832 | Cross Site Scripting (XSS) at the "Reset Password" page form of Priority Enterprise Management System v8.00 allows attackers to execute javascript on behalf of the victim by sending a malicious URL or directing the victim to a malicious site. | https://github.com/NagliNagli/CVE-2021-26832 | 未查询到CVE信息| 
| 20210413T01:07:21Z | cve-2020-2021 | Null | https://github.com/givemefivw/cve-2020-2021 | When Security Assertion Markup Language (SAML) authentication is enabled and the %Validate Identity Provider Certificate% option is disabled (unchecked), improper verification of signatures in PAN-OS SAML authentication enables an unauthenticated network-based attacker to access protected resources. The attacker must have network access to the vulnerable server to exploit this vulnerability. This issue affects PAN-OS 9.1 versions earlier than PAN-OS 9.1.3; PAN-OS 9.0 versions earlier than PAN-OS 9.0.9; PAN-OS 8.1 versions earlier than PAN-OS 8.1.15, and all versions of PAN-OS 8.0 (EOL). This issue does not affect PAN-OS 7.1. This issue cannot be exploited if SAML is not used for authentication. This issue cannot be exploited if the %Validate Identity Provider Certificate% option is enabled (checked) in the SAML Identity Provider Server Profile. Resources that can be protected by SAML-based single sign-on (SSO) authentication are: GlobalProtect Gateway, GlobalProtect Portal, GlobalProtect Clientless VPN, Authentication and Captive Portal, PAN-OS next-generation firewalls (PA-Series, VM-Series) and Panorama web interfaces, Prisma Access In the case of GlobalProtect Gateways, GlobalProtect Portal, Clientless VPN, Captive Portal, and Prisma Access, an unauthenticated attacker with network access to the affected servers can gain access to protected resources if allowed by configured authentication and Security policies. There is no impact on the integrity and availability of the gateway, portal or VPN server. An attacker cannot inspect or tamper with sessions of regular users. In the worst case, this is a critical severity vulnerability with a CVSS Base Score of 10.0 (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:N). In the case of PAN-OS and Panorama web interfaces, this issue allows an unauthenticated attacker with network access to the PAN-OS or Panorama web interfaces to log in as an administrator and perform administrative actions. In the worst-case scenario, this is a critical severity vulnerability with a CVSS Base Score of 10.0 (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H). If the web interfaces are only accessible to a restricted management network, then the issue is lowered to a CVSS Base Score of 9.6 (CVSS:3.1/AV:A/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H). Palo Alto Networks is not aware of any malicious attempts to exploit this vulnerability.| 
| 20210413T01:05:46Z | cve-2020- | Null | https://github.com/givemefivw/cve-2020-tttt | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210413T22:15:22Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210413T20:06:48Z | Spring 2021 Geography 817 work folder  | https://github.com/klee12/klee12.github.io | 0 | 0| 
| 20210413T16:49:14Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1670 | 489| 
| 20210413T14:28:13Z | A very fun and useful bot containing many features.  | https://github.com/quantix-dev/Kleebot | 1 | 0| 
| 20210413T08:46:44Z | Safe KLEE API for Rust | https://github.com/markhakansson/klee-rs | 0 | 0| 
| 20210413T08:27:10Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 214 | 35| 
| 20210413T07:57:03Z | Raw bindings for KLEE | https://github.com/markhakansson/klee-bindings | 0 | 0| 
| 20210413T05:41:32Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 122 | 11| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210413T23:57:43Z | The PS4 5.05 Exploit Host Menu created by xforce505 | https://github.com/xforce505/PS4-Exploit-Host-Menu | 0 | 0| 
| 20210413T23:52:04Z | Null | https://github.com/akkaiba/pythonDeface-Exploit | 0 | 0| 
| 20210413T23:39:39Z | Ded Security - Toolkit | https://github.com/dedsecubr/dedsecurity-framework | 6 | 2| 
| 20210413T23:32:49Z | PS4 Exploit Host | https://github.com/Night-King-Host/Night-King-Host.github.io | 8 | 4| 
| 20210413T23:30:46Z | Automatic Linux privesc via exploitation of low-hanging fruit e.g. gtfobins :arrow_up: :skull_and_crossbones: | https://github.com/liamg/traitor | 3054 | 152| 
| 20210413T23:28:11Z | I made this for fun so don%t exploit with it. | https://github.com/RJScriptingDevelopment/LUA-EXPLOIT-FOR-ROBLOX | 0 | 0| 
| 20210413T23:24:05Z | Download My Roblox Exploit:  | https://github.com/AngeltvFAN/Key | 0 | 0| 
| 20210413T23:20:10Z | This library is designed to exclusively aid in process exploitation, function analysis, and operations similar to IDA Pro/Cheat Engine | https://github.com/thedoomed/EyeStep-CPP-Extended | 4 | 5| 
| 20210413T22:20:27Z | Microbiome Analysis Powered By Recursive Quasi-species Networks: Uncovering rules of organization, competition, succession and exploitation | https://github.com/zeroknowledgediscovery/qbiome | 0 | 0| 
| 20210413T21:48:27Z | 存储各类渗透测试 工具/exp等 | https://github.com/ClassBluer/Exploit_Tools | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210413T19:57:22Z | Backdoor is going to be an interactive web console for Elixir & Phoenix projects | https://github.com/amberbit/backdoor | 2 | 1| 
| 20210413T16:36:49Z | A webshell that can bypass some system security | https://github.com/22XploiterCrew-Team/Gel4y-Mini-Shell-Backdoor | 22 | 5| 
| 20210413T14:50:05Z | Null | https://github.com/ph-luffy/Backdoor | 1 | 1| 
| 20210413T11:36:52Z | Null | https://github.com/BSalwiczek/backdoor-trojan | 0 | 0| 
| 20210413T10:25:32Z | Null | https://github.com/Bifrostbiolabs/Yggdrasil_Backdoor | 0 | 0| 
| 20210413T09:06:58Z | QA tasks for %Hidden Backdoors in Human-Centric Language Models% | https://github.com/HLori/Question-Answering | 0 | 0| 
| 20210413T04:18:07Z | 🤖An Evil and Smart Bot for Enslaving Windows. | https://github.com/wildonion/katyusha | 1 | 1| 
| 20210413T01:57:07Z | A Simple android remote administration tool using sockets. It uses java on the client side and python on the server side | https://github.com/karma9874/AndroRAT | 202 | 92| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210413T23:53:39Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2316 | 124| 
| 20210413T23:08:22Z | CS 4152 Project | https://github.com/nicbarone/Fuzzy-Kiwi | 0 | 0| 
| 20210413T22:43:44Z | Robust and versatile headless monkey (fuzz) testing for the web with reproducible steps, error alerts, strategy sharing and many other good things. | https://github.com/bell-lab-apps/fuzz-monkey | 0 | 0| 
| 20210413T21:59:20Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 4 | 1| 
| 20210413T21:35:52Z | Calculating CardiovascularDiseaseRisk using Fuzzy logic | https://github.com/StefanutVlad/fuzzyCardiovascularDiseaseRisk | 0 | 0| 
| 20210413T21:25:27Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 272 | 37| 
| 20210413T21:12:37Z | This calendar gives you 1-2 sentences about a thing that a marginalised person in computing did connected to the date. | https://github.com/fuzzy-binaires/fuzzy-binaires.github.io | 0 | 0| 
| 20210413T21:12:16Z | Fuzzster - fuzzy matching web application | https://github.com/datahappy1/go_fuzzymatch_webapp | 0 | 0| 
| 20210413T21:08:24Z | Fuzzy Logic Implementation | https://github.com/Nico-Duduf/DuFuzzyLogic | 2 | 1| 
| 20210413T20:51:44Z | fuzzing applications | https://github.com/MucahitSaratar/myfuzzer | 0 | 0| 



# 日更新程序
