# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210301 | 去年 Black Hat USA 2020 会议的议题视频全部公开了 | https://www.youtube.com/playlist?list=PLH15HpR5qRsXE_4kOSy_SXwFkFQre4AV_| 
| 20210301 | BlackHat USA 2020 会议 “iOS Kernel PAC, One Year Later” 议题的视频 | https://www.youtube.com/watch?v=7zCBOFxATFs&feature=youtu.be| 
| 20210301 | 研究员 Hardik Shah 在 Grayhat 2020 会议的 Fuzzing Workshop 资料 | https://github.com/hardik05/Conferences/tree/main/Grayhat2020| 
| 20210301 | HMDM - 基于 physmeme 项目，将未签名代码直接映射到内核的工具，可以用于漏洞研究学习 | https://githacks.org/_xeroxz/hmdm| 
| 20210301 | Linux 内核 CVE-2020-14381 漏洞的分析 | https://blog.frizn.fr/linux-kernel/cve-2020-14381| 
| 20210301 | Cosmopolitan Libc - 将 C 代码真正编译成跨平台执行的库，一次编译，支持在 Linux + Mac + Windows + FreeBSD + OpenBSD + NetBSD + BIOS 直接 Native 执行。 | https://ahgamut.github.io/c/2021/02/27/ape-cosmo/| 
| 20210301 | Apple 漏洞致谢数全球第一背后的新攻击面 & 一洞攻破 Safari | https://paper.seebug.org/1490/| 
| 20210301 | SaltStack 远程执行代码存在多个高危漏洞分析（CVE-2021-25281 ，CVE-2021-25282， CVE-2021-25283） | https://sec.today/pulses/1bd5fa4b-65f8-4f7a-8ad3-3f339022a1a1/| 
| 20210301 | SaltStack 远程执行代码存在多个高危漏洞分析（CVE-2021-25281 ，CVE-2021-25282， CVE-2021-25283） | https://paper.seebug.org/1491/| 
| 20210301 | 进行对Kernsomware勒索软件分析溯源。 | https://cert-agid.gov.it/news/kernsomware/| 
| 20210301 | 使用WinAFL进行模糊处理和查找漏洞视频。 | https://www.youtube.com/watch?v=m7tJkeW6H58&t=394s| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210301 | SecWiki周刊（第365期) | https://www.sec-wiki.com/weekly/365| 
| 20210301 | 恶意软件分析工具集成环境 | https://mp.weixin.qq.com/s/WMWQUWu8dt45iQsrcLfSxg| 
| 20210301 | 大白话解释拟态安全 | https://mp.weixin.qq.com/s/UR0XbF02JJmo7RbNF1CYVw| 
| 20210301 | 浅谈如何有效落地DevSecOps | https://mp.weixin.qq.com/s/5eX3-SCfvFfRitb9_onjvw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210302T00:33:48Z | CVE-2021-21315 | CVE 2021-21315 PoC | https://github.com/ForbiddenProgrammer/CVE-2021-21315-PoC | The System Information Library for Node.JS (npm package %systeminformation%) is an open source collection of functions to retrieve detailed hardware, system and OS information. In systeminformation before version 5.3.1 there is a command injection vulnerability. Problem was fixed in version 5.3.1. As a workaround instead of upgrading, be sure to check or sanitize service parameters that are passed to si.inetLatency(), si.inetChecksite(), si.services(), si.processLoad() ... do only allow strings, reject any arrays. String sanitation works as expected.| 
| 20210302T00:28:35Z | CVE-2021-21972 | CVE-2021-21972 Exploit | https://github.com/NS-Sp4ce/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210301T23:20:52Z | CVE-2021-21972 | VMware vCenter CVE-2021-21972 Tools | https://github.com/robwillisinfo/VMware_vCenter_CVE-2021-21972 | | 
| 20210301T23:20:29Z | CVE-2021-21972 | CVE-2021-21972 | https://github.com/milo2012/CVE-2021-21972 | | 
| 20210301T23:04:06Z | CVE-2021-21972 | Nmap script to check vulnerability CVE-2021-21972 | https://github.com/GuayoyoLabs/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210301T22:58:24Z | CVE-2021-25281 | Chaining CVE-2021-25281 and CVE-2021-25282 to exploit a SaltStack | https://github.com/Immersive-Labs-Sec/CVE-2021-25281 | An issue was discovered in through SaltStack Salt before 3002.5. salt-api does not honor eauth credentials for the wheel_async client. Thus, an attacker can remotely run any wheel modules on the master.| 
| 20210301T22:51:09Z | CVE-2021-21972 | Proof of Concept Exploit for vCenter CVE-2021-21972 | https://github.com/horizon3ai/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210301T22:28:38Z | CVE-2021-27246 | Null | https://github.com/synacktiv/CVE-2021-27246_Pwn2Own2020 | 未查询到CVE信息| 
| 20210301T16:34:12Z | CVE-2020-14882 | CVE-2020-14882 | https://github.com/milo2012/CVE-2020-14882 | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210301T13:01:34Z | CVE-2020-9484 | Null | https://github.com/DXY0411/CVE-2020-9484 | When using Apache Tomcat versions 10.0.0-M1 to 10.0.0-M4, 9.0.0.M1 to 9.0.34, 8.5.0 to 8.5.54 and 7.0.0 to 7.0.103 if a) an attacker is able to control the contents and name of a file on the server; and b) the server is configured to use the PersistenceManager with a FileStore; and c) the PersistenceManager is configured with sessionAttributeValueClassNameFilter=%null% (the default unless a SecurityManager is used) or a sufficiently lax filter to allow the attacker provided object to be deserialized; and d) the attacker knows the relative file path from the storage location used by FileStore to the file the attacker has control over; then, using a specifically crafted request, the attacker will be able to trigger remote code execution via deserialization of the file under their control. Note that all of conditions a) to d) must be true for the attack to succeed.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210301T15:33:25Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210301T11:45:19Z | Null | https://github.com/fontworks-fonts/Klee | 370 | 10| 
| 20210301T10:06:41Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1637 | 483| 
| 20210301T08:13:39Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 107 | 4| 
| 20210301T04:28:58Z | Null | https://github.com/abbykleespie/A2AbbyKleespie.appstudio | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210302T01:02:33Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 9 | 4| 
| 20210302T01:01:44Z | works for any exploit | https://github.com/loglizzy/Knight-Heroes-Gui | 0 | 0| 
| 20210302T00:50:18Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 7 | 5| 
| 20210302T00:47:50Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 8 | 1| 
| 20210302T00:46:06Z | A CTF web app designed to teach software developers application security by showcasing what vulnerable code looks like, how to write code to exploit the vulnerability, and how to write code to patch the vulnerability. | https://github.com/neumaneuma/appseccheat.codes | 0 | 0| 
| 20210302T00:42:12Z | Thi powershell script has got to run in remote windows host, even for pivoting | https://github.com/FabioDefilippo/winallenum | 2 | 1| 
| 20210302T00:40:55Z | Exploit Microsoft Windows - Escalate UAC Protection Bypass (Via dot net profiler) (Metasploit) | https://github.com/jalladsathwara/Js-Exploit | 1 | 1| 
| 20210301T23:55:39Z | I honestly only made this repo due people still dming about the exploits i released 4/6 months ago, so enjoy. | https://github.com/exze-salamoonder/fivem-exploits | 1 | 0| 
| 20210301T23:51:37Z | Extensible framework for analyzing publicly available information about vulnerabilities | https://github.com/leonov-av/vulristics | 23 | 1| 
| 20210301T23:11:53Z | Set of CLI tools for automatically generating (as well as testing) PHP exploits. | https://github.com/madberries/sourceforage | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210302T01:04:23Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 180 | 26| 
| 20210301T21:26:11Z | Null | https://github.com/EjHvorSerDuVildUdJim/backdoor | 0 | 0| 
| 20210301T19:14:26Z | Null | https://github.com/Wiilldd/backdoor | 0 | 0| 
| 20210301T18:22:09Z | Null | https://github.com/ph-luffy/Backdoor | 1 | 1| 
| 20210301T17:12:01Z | backdoor uiuiuiui | https://github.com/zeru2/backdoor | 0 | 0| 
| 20210301T16:50:18Z | Fud Persistent Windows Backdoor developed purely in python | https://github.com/swagkarna/Chuvi-Botnet | 13 | 5| 
| 20210301T16:41:40Z | Thefatrat a massive exploiting tool : Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack and etc . This tool compiles a malware with popular payload and then the compiled malware can be execute on windows, android, mac . The malware that created with this tool also have an ability to bypass most AV software protection . | https://github.com/Screetsec/TheFatRat | 4987 | 1644| 
| 20210301T16:31:58Z | Null | https://github.com/angelo1104/backdoor-node | 0 | 0| 
| 20210301T16:17:29Z | OWASP ZAP add-on containing the web-backdoors and attack files from FuzzDB | https://github.com/zaproxy/fuzzdb-offensive | 6 | 6| 
| 20210301T15:02:04Z | Neural networks for the Fooling a Complete Neural Network Verifier paper (ICLR 2021) | https://github.com/szegedai/nn_backdoor | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210301T14:20:40Z | 🛩️Generate a David for the Goliath URLs🚀 | https://github.com/sd2001/FuzzyUrls | 3 | 0| 
| 20210301T14:10:51Z | VMI Kernel Fuzzer for Xen Project - VM forking, VMI & AFL integration demo | https://github.com/intel/kernel-fuzzer-for-xen-project | 238 | 38| 
| 20210301T13:53:13Z | Coverage-guided, in-process fuzzing for the JVM | https://github.com/CodeIntelligenceTesting/jazzer | 189 | 7| 
| 20210301T13:51:30Z | ProFuzzBench - A Benchmark for Stateful Protocol Fuzzing | https://github.com/profuzzbench/profuzzbench | 58 | 12| 
| 20210301T13:36:50Z | Null | https://github.com/Sunwader/fuzzy-fiesta | 0 | 0| 
| 20210301T13:27:21Z | Null | https://github.com/Fa2Fin/fuzzy-adventure | 0 | 0| 
| 20210301T13:08:38Z | Hi thre, I%m TRÄW🤟🏻, i%m a beginner in ethical hacking and Content Creator on Level iv Security & NOOBSEC. I Spend most of time coding outstanding ethical hacking projects or recording useful short tutorials . I love programming ethical hacking tools, fuzzing and hacking all the things | https://github.com/spectertraww/spectertraww | 1 | 0| 
| 20210301T12:54:03Z | SecLists is the security tester%s companion. It%s a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. | https://github.com/danielmiessler/SecLists | 30160 | 15311| 
| 20210301T12:53:33Z | Bootstrap Intro | https://github.com/orlawalsh/fuzzy-bassoon | 0 | 0| 
| 20210301T12:46:55Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 6 | 1| 



# 日更新程序
