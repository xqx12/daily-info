# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210626T23:20:02Z | CVE-2021-31955 | Null | https://github.com/mavillon1/CVE-2021-31955-POC | Windows Kernel Information Disclosure Vulnerability| 
| 20210626T18:30:40Z | CVE-2021-32537 | PoC for CVE-2021-32537: an out-of-bounds memory access that leads to pool corruption in the Windows kernel. | https://github.com/0vercl0k/CVE-2021-32537 | 未查询到CVE信息| 
| 20210626T11:27:28Z | CVE-2021-35475 | Writeup for CVE-2021-35475; Stored Cross-Site Scripting(XSS) on SAS® Environment Manager 2.5 | https://github.com/saitamang/CVE-2021-35475 | SAS Environment Manager 2.5 allows XSS through the Name field when creating/editing a server. The XSS will prompt when editing the Configuration Properties.| 
| 20210626T09:24:14Z | CVE-2021-27850 | A Proof of concept for CVE-2021-27850 affecting Apache Tapestry and leading to unauthencticated remote code execution. | https://github.com/kahla-sec/CVE-2021-27850_POC | A critical unauthenticated remote code execution vulnerability was found all recent versions of Apache Tapestry. The affected versions include 5.4.5, 5.5.0, 5.6.2 and 5.7.0. The vulnerability I have found is a bypass of the fix for CVE-2019-0195. Recap: Before the fix of CVE-2019-0195 it was possible to download arbitrary class files from the classpath by providing a crafted asset file URL. An attacker was able to download the file `AppModule.class` by requesting the URL `http://localhost:8080/assets/something/services/AppModule.class` which contains a HMAC secret key. The fix for that bug was a blacklist filter that checks if the URL ends with `.class`, `.properties` or `.xml`. Bypass: Unfortunately, the blacklist solution can simply be bypassed by appending a `/` at the end of the URL: `http://localhost:8080/assets/something/services/AppModule.class/` The slash is stripped after the blacklist check and the file `AppModule.class` is loaded into the response. This class usually contains the HMAC secret key which is used to sign serialized Java objects. With the knowledge of that key an attacker can sign a Java gadget chain that leads to RCE (e.g. CommonsBeanUtils1 from ysoserial). Solution for this vulnerability: * For Apache Tapestry 5.4.0 to 5.6.1, upgrade to 5.6.2 or later. * For Apache Tapestry 5.7.0, upgrade to 5.7.1 or later.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T18:53:27Z | Config files for my GitHub profile. | https://github.com/c-kleerun/c-kleerun | 0 | 0| 
| 20210626T13:46:38Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 683 | 15| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T23:57:11Z | Resources for the Kr00k vulnerability (CVE-2019-15126) | https://github.com/raul23/Kr00k | 0 | 0| 
| 20210626T23:04:46Z | A series of CTF/hacking challenge solutions for binary exploitation(or pwn)/reverse engineering/vulnerability research/memory corruption(or whatever term you use) | https://github.com/docfate111/binary-exploitation-solution-scripts | 0 | 0| 
| 20210626T23:02:52Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 25 | 12| 
| 20210626T22:25:11Z | KDMapper is a simple tool that exploits iqvw64e.sys Intel driver to manually map non-signed drivers in memory | https://github.com/TheCruZ/kdmapper | 296 | 114| 
| 20210626T22:07:59Z | Writeup for exploit.education/nebula | https://github.com/vi11ain/nebula-writeup | 1 | 0| 
| 20210626T21:56:54Z | MCAtlas changes relating to Towny, including Towny exploit fix, general messages, etc. | https://github.com/Ruinscraft/mcatlas-towny-helpers | 0 | 0| 
| 20210626T21:35:13Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9598 | 1569| 
| 20210626T20:55:19Z | Windows 7 Professional 7601 Service Pack 1 is vulnerable to eternalblue exploit and while exploiting this myself i ran into a number of issues . So , now i will show you how to exploit it without using metasploit . | https://github.com/AnikateSawhney/Pwning_Blue_From_HTB_Without_Metasploit | 0 | 0| 
| 20210626T19:44:57Z | Makes it so that you can craft ores, non OP (cannot be exploited with Fortune). (Datapack) | https://github.com/zaydam1000000/craftable_ores | 0 | 0| 
| 20210626T19:31:10Z | Null | https://github.com/zYan666/Demon-Exploit | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T20:55:14Z | Ethical hacking backdoor malware source, do not use this program with unauthorized parties | https://github.com/icrescenti/YWV4 | 0 | 0| 
| 20210626T19:33:27Z | Null | https://github.com/FierzaEriez/Mini-Shell-Backdoor | 0 | 0| 
| 20210626T19:03:53Z | Invisible, customizable backdoor for Minecraft Spigot Plugins. | https://github.com/ThiccIndustries/Minecraft-Backdoor | 10 | 4| 
| 20210626T18:45:26Z | Null | https://github.com/Wrench56/Backdoor | 0 | 0| 
| 20210626T17:20:46Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/Ghost | 1171 | 556| 
| 20210626T17:15:59Z | a little Windows 10 Backdoor source | https://github.com/catch1337/Backdoor | 0 | 0| 
| 20210626T11:36:01Z | ASP WEBSHELL BYPASS PHP SHELL BACKDOOR UNDETECTED! | https://github.com/webshell-archive/ASP | 1 | 0| 
| 20210626T11:35:46Z | PHP WEBSHELL BYPASS PHP SHELL BACKDOOR UNDETECTED! | https://github.com/webshell-archive/PHP | 1 | 0| 
| 20210626T10:02:30Z | Python backdoor | https://github.com/DianaNeumann/Porte_arriere | 0 | 0| 
| 20210626T09:59:16Z | Null | https://github.com/fmy266/Pytorch-Backdoor-Unlearning | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T08:22:56Z | Symbolic-execution-based verifier for the Viper intermediate verification language. | https://github.com/viperproject/silicon | 19 | 11| 
| 20210626T03:49:26Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2366 | 348| 
| 20210626T02:56:41Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 144 | 33| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T06:09:11Z | Original implementation of FlowPrint as in the NDSS %20 paper | https://github.com/Thijsvanede/FlowPrint | 49 | 18| 
| 20210626T02:22:29Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 15 | 2| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T12:43:04Z | My personal portfolio website | https://github.com/FuzzyGrim/fuzzygrim.github.io | 0 | 0| 
| 20210626T12:35:41Z | This is a tool for fuzzing XSS vulnerabilities based on genetic algorithm. | https://github.com/Timofey21/darlene | 0 | 0| 
| 20210626T12:35:08Z | DOM fuzzer | https://github.com/mevid93/domzzer | 0 | 0| 
| 20210626T12:32:00Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210626T12:31:22Z | Null | https://github.com/DanielEbert/EmulatedFirmwareFuzzing | 0 | 0| 
| 20210626T12:26:56Z | This is a tool for fuzzing XSS vulnerabilities based on genetic algorithm. | https://github.com/Timofey21/GoXSSfuzz | 0 | 0| 
| 20210626T11:31:11Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210626T11:28:55Z | Null | https://github.com/AdaLogics/go-fuzz-headers | 2 | 1| 
| 20210626T09:28:43Z | Null | https://github.com/bolpuine/fuzzy-octo-palm-tree | 0 | 0| 
| 20210626T08:42:56Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6417 | 1303| 



# 日更新程序
