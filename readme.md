# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210627 | 利用 Hook 技术打造通用的 Webshell | https://jayl1n.github.io/2021/06/25/use-inlinehook-technology-to-make-a-more-general-webshell/| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210627T11:34:35Z | CVE-2021-31955 | Null | https://github.com/mavillon1/CVE-2021-31955-POC | Windows Kernel Information Disclosure Vulnerability| 
| 20210627T08:25:45Z | CVE-2021-27850 | A Proof of concept for CVE-2021-27850 affecting Apache Tapestry and leading to unauthencticated remote code execution. | https://github.com/kahla-sec/CVE-2021-27850_POC | A critical unauthenticated remote code execution vulnerability was found all recent versions of Apache Tapestry. The affected versions include 5.4.5, 5.5.0, 5.6.2 and 5.7.0. The vulnerability I have found is a bypass of the fix for CVE-2019-0195. Recap: Before the fix of CVE-2019-0195 it was possible to download arbitrary class files from the classpath by providing a crafted asset file URL. An attacker was able to download the file `AppModule.class` by requesting the URL `http://localhost:8080/assets/something/services/AppModule.class` which contains a HMAC secret key. The fix for that bug was a blacklist filter that checks if the URL ends with `.class`, `.properties` or `.xml`. Bypass: Unfortunately, the blacklist solution can simply be bypassed by appending a `/` at the end of the URL: `http://localhost:8080/assets/something/services/AppModule.class/` The slash is stripped after the blacklist check and the file `AppModule.class` is loaded into the response. This class usually contains the HMAC secret key which is used to sign serialized Java objects. With the knowledge of that key an attacker can sign a Java gadget chain that leads to RCE (e.g. CommonsBeanUtils1 from ysoserial). Solution for this vulnerability: * For Apache Tapestry 5.4.0 to 5.6.1, upgrade to 5.6.2 or later. * For Apache Tapestry 5.7.0, upgrade to 5.7.1 or later.| 
| 20210627T04:48:33Z | CVE-2020-10558 | TESLA MODEL 3 HACK | https://github.com/AmazingOut/Tesla-CVE-2020-10558 | The driving interface of Tesla Model 3 vehicles in any release before 2020.4.10 allows Denial of Service to occur due to improper process separation, which allows attackers to disable the speedometer, web browser, climate controls, turn signal visual and sounds, navigation, autopilot notifications, along with other miscellaneous functions from the main screen.| 
| 20210627T04:38:20Z | CVE-2021-32537 | PoC for CVE-2021-32537: an out-of-bounds memory access that leads to pool corruption in the Windows kernel. | https://github.com/0vercl0k/CVE-2021-32537 | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210627T09:35:23Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 685 | 15| 
| 20210627T04:51:57Z | Null | https://github.com/Chiyukichan/klee_file | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210627T12:09:21Z | An open source Roblox Exploit / Script Executor, Join our Discord: https://kokscheats.com/discord | https://github.com/SimcraftLOL/Koks-Roblox-Executor | 1 | 0| 
| 20210627T12:02:51Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 25 | 12| 
| 20210627T12:00:45Z | Modular penetration testing platform that enables you to write, test, and execute exploit code. | https://github.com/EntySec/HatSploit | 66 | 22| 
| 20210627T11:47:51Z | This repository contains hints to exploit and capture flag of  CTF machines from various platforms. this isn%t a detailed walk-through. from some boxes which I hunt. | https://github.com/nibrasmuhamed/CTF-Walkthrough | 0 | 0| 
| 20210627T11:13:59Z | My Collection of exploits, reverse shells, scripts and more | https://github.com/nop-tech/Pentesting | 2 | 2| 
| 20210627T11:04:07Z | Null | https://github.com/hxr404/Discord-Console-hacks | 13 | 7| 
| 20210627T10:25:39Z | A little mod I made for my friends in my survival server and keep them from exploiting spectator mode. | https://github.com/North-West-Wind/FabricSurvivalSpectator | 0 | 0| 
| 20210627T10:17:35Z | Null | https://github.com/rjsu26/Exploit_dev_notes | 0 | 0| 
| 20210627T09:36:45Z | A roblox server sided anti exploit capable of handling common exploits smoothly. Performance friendly, and reserves resources. The point of this anti exploit is to stop common exploits reliably with minimum performance impact, and rarely cause any false positive related problems. | https://github.com/SilentsReplacement/BoboFighter | 5 | 2| 
| 20210627T09:25:21Z | Resources for the Kr00k vulnerability (CVE-2019-15126) | https://github.com/raul23/Kr00k | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210627T11:45:18Z | Une simple Backdoor, donnant accés à l%ensemble des fichiers d%un ordinateur. | https://github.com/billythegoat356/F0rs4k3n | 0 | 0| 
| 20210627T11:18:42Z | Ethical hacking backdoor malware source, do not use this program with unauthorized parties | https://github.com/icrescenti/YWV4 | 0 | 0| 
| 20210627T11:17:35Z | PHP WEBSHELL BYPASS PHP SHELL BACKDOOR UNDETECTED! | https://github.com/webshell-archive/PHP | 1 | 0| 
| 20210627T05:39:38Z | Windows Reverse Shell | https://github.com/knight8645726/Backdoor | 0 | 0| 
| 20210627T02:40:04Z | Null | https://github.com/Coops0/Anti-Backdoor | 0 | 0| 
| 20210627T01:04:51Z | Pytorch implementation of backdoor unlearning. | https://github.com/fmy266/Pytorch-Backdoor-Unlearning | 0 | 0| 
| 20210627T00:24:59Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/Ghost | 1172 | 556| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210627T10:38:41Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 422 | 62| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210627T12:02:23Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210627T11:55:49Z | Null | https://github.com/bhattacharjee/fuzzy-funicular | 0 | 0| 
| 20210627T11:55:16Z | This is a tool for fuzzing XSS vulnerabilities based on genetic algorithm. | https://github.com/Timofey21/darlene | 2 | 0| 
| 20210627T09:44:41Z | Terminal-based, hyper-fast, CRDT-backed, collaborative note-taking tool | https://github.com/Sambigeara/fuzzynote | 264 | 3| 
| 20210627T09:05:07Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210627T08:27:57Z | DOM fuzzer | https://github.com/mevid93/domzzer | 0 | 0| 
| 20210627T08:00:48Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 288 | 39| 
| 20210627T07:41:20Z | precision-error guided fuzz testing for deep learning operators | https://github.com/predoodl/predoo | 10 | 0| 
| 20210627T07:35:44Z | Fuzzy Watering Control System | https://github.com/fikri221/fuzzy-wcs | 0 | 0| 
| 20210627T05:22:24Z | Null | https://github.com/lizaorsini346/fuzzy-parakeet | 0 | 0| 



# 日更新程序
