# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210606 | Linux提权：Python脚本利用劫持演示。 | https://www.hackingarticles.in/linux-privilege-escalation-python-library-hijacking/| 
| 20210606 | VCSA 6.5-7.0 远程代码执行漏洞（CVE-2021-21985） | https://buaq.net/go-75544.html| 
| 20210606 | 针对进程注入技术深入研究。 | https://medium.com/csg-govtech/process-injection-techniques-used-by-malware-1a34c078612c| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210606 | Code Signing - iOS 代码段的校验机制分析 | https://mp.weixin.qq.com/s/msUwo3YUcfHXkuAp5wRfyQ| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210606T19:41:34Z | CVE-2021-22911 | Pre-Auth Blind NoSQL Injection leading to Remote Code Execution in Rocket Chat 3.12.1 | https://github.com/CsEnox/CVE-2021-22911 | A improper input sanitization vulnerability exists in Rocket.Chat server 3.11, 3.12 & 3.13 that could lead to unauthenticated NoSQL injection, resulting potentially in RCE.| 
| 20210606T18:30:46Z | cve-2021-33879 | GameLoop update MITM | https://github.com/mmiszczyk/cve-2021-33879 | Tencent GameLoop before 4.1.21.90 downloaded updates over an insecure HTTP connection. A malicious attacker in an MITM position could spoof the contents of an XML document describing an update package, replacing a download URL with one pointing to an arbitrary Windows executable. Because the only integrity check would be a comparison of the downloaded file%s MD5 checksum to the one contained within the XML document, the downloaded executable would then be executed on the victim%s machine.| 
| 20210606T18:10:41Z | CVE-2021-29440 | Unsafe Twig processing of static pages leading to RCE in Grav CMS 1.7.10 | https://github.com/CsEnox/CVE-2021-29440 | Grav is a file based Web-platform. Twig processing of static pages can be enabled in the front matter by any administrative user allowed to create or edit pages. As the Twig processor runs unsandboxed, this behavior can be used to gain arbitrary code execution and elevate privileges on the instance. The issue was addressed in version 1.7.11.| 
| 20210606T16:03:55Z | CVE-2020-0688 | Remote Code Execution on Microsoft Exchange Server through fixed cryptographic keys | https://github.com/MrTiz/CVE-2020-0688 | A remote code execution vulnerability exists in Microsoft Exchange software when the software fails to properly handle objects in memory, aka %Microsoft Exchange Memory Corruption Vulnerability%.| 
| 20210606T13:53:59Z | CVE-2020-9496 | XML-RPC request are vulnerable to unsafe deserialization and Cross-Site Scripting issues in Apache OFBiz 17.12.03 | https://github.com/ambalabanov/CVE-2020-9496 | XML-RPC request are vulnerable to unsafe deserialization and Cross-Site Scripting issues in Apache OFBiz 17.12.03| 
| 20210606T11:24:03Z | CVE-2021-27965 | stack based buffer overflow in MsIo64.sys, Proof of Concept Local Privilege Escalation to nt authority/system | https://github.com/mathisvickie/CVE-2021-27965 | | 
| 20210606T08:51:32Z | CVE-2020-13957 | Apache Solr RCE CVE-2020-13957 | https://github.com/s-index/CVE-2020-13957 | | 
| 20210606T08:41:21Z | CVE-2021-25641 | Apache/Alibaba Dubbo <= 2.7.3 PoC Code for CVE-2021-25641 RCE via Deserialization of Untrusted Data; Affects Versions <= 2.7.6 With Different Gadgets | https://github.com/Dor-Tumarkin/CVE-2021-25641-Proof-of-Concept | Each Apache Dubbo server will set a serialization id to tell the clients which serialization protocol it is working on. But for Dubbo versions before 2.7.8 or 2.6.9, an attacker can choose which serialization id the Provider will use by tampering with the byte preamble flags, aka, not following the server%s instruction. This means that if a weak deserializer such as the Kryo and FST are somehow in code scope (e.g. if Kryo is somehow a part of a dependency), a remote unauthenticated attacker can tell the Provider to use the weak deserializer, and then proceed to exploit it.| 
| 20210606T08:09:03Z | CVE-2021-21551 | arbitrary kernel read/write in dbutil_2_3.sys, Proof of Concept Local Privilege Escalation to nt authority/system | https://github.com/mathisvickie/CVE-2021-21551 | Dell dbutil_2_3.sys driver contains an insufficient access control vulnerability which may lead to escalation of privileges, denial of service, or information disclosure. Local authenticated user access is required.| 
| 20210606T05:59:51Z | CVE-2021-22205 | Null | https://github.com/mr-r3bot/Gitlab-CVE-2021-22205 | An issue has been discovered in GitLab CE/EE affecting all versions starting from 11.9. GitLab was not properly validating image files that were passed to a file parser which resulted in a remote command execution.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210606T21:35:51Z | Null | https://github.com/JaimePSantos/ResearchKlee | 0 | 0| 
| 20210606T16:54:02Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 14 | 45| 
| 20210606T15:28:53Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 651 | 15| 
| 20210606T10:55:07Z | Null | https://github.com/ReneSchwarzer/Kleene | 0 | 0| 
| 20210606T02:57:41Z | ⬇️ File Upload/sharing application, used by thousands of webmasters since 2007.  | https://github.com/kleeja-official/kleeja | 121 | 35| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210606T14:20:15Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 129 | 31| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210606T23:18:24Z | xnu_gym is a pongoOS module that patches XNU to reintroduce previously known and patched vulnerabilities. This is an easy way to practice kernel exploitation and jailbreak development! | https://github.com/tjkr0wn/xnu_gym | 45 | 1| 
| 20210606T22:45:08Z | Some scripts to exploit my vulnerable web app | https://github.com/kitty14956590/vuln-webapp-scripts | 0 | 0| 
| 20210606T22:39:19Z | Gote Hub - Comunity Roblox Exploiting And Scripting @Copyright 2021 | https://github.com/Vilictus/Gote-Hub | 0 | 0| 
| 20210606T22:10:44Z | Educational web application demonstrating techniques of binary exploitation (Front-end) | https://github.com/Pen-Test3rs/binary_exploits_frontend | 0 | 0| 
| 20210606T21:35:56Z | SECMON is a web-based tool for the automation of infosec watching and vulnerability management with a web interface. | https://github.com/Guezone/SECMON | 33 | 6| 
| 20210606T21:28:29Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 208 | 39| 
| 20210606T21:20:14Z | Website for Easy Cross-Site Exploitation | https://github.com/MooseTheGoose/xsserver | 0 | 0| 
| 20210606T20:33:51Z | Open source cheat for the MMO game ROBLOX | https://github.com/ringarang/QLX | 0 | 0| 
| 20210606T20:29:21Z | GEF - GDB Enhanced Features for exploit devs & reversers | https://github.com/hugsy/gef | 3661 | 510| 
| 20210606T20:09:03Z | Scripts (ServerSide and FE) | https://github.com/0WNEDU/Roblox-Misc-Scripts-Exploits | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210606T21:28:29Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 208 | 39| 
| 20210606T17:15:52Z | Undetectable & Xor encrypting with custom KEY (FUD Metasploit Rat) bypass Top Antivirus like BitDefender,Malwarebytes,Avast,ESET-NOD32,AVG,... & Automatically Add ICON and MANIFEST to excitable | https://github.com/persianhydra/Xeexe-TopAntivirusEvasion | 465 | 106| 
| 20210606T15:11:29Z | Code and data of the ACL-IJCNLP 2021 paper %Hidden Killer: Invisible Textual Backdoor Attacks with Syntactic Trigger% | https://github.com/thunlp/HiddenKiller | 0 | 1| 
| 20210606T13:30:23Z | Very Easy Relative Backdoor Application | https://github.com/Not-C-Developer/VERBA | 0 | 0| 
| 20210606T12:52:35Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 247 | 43| 
| 20210606T11:58:07Z | PHP 8.1.0-dev Backdoor System Shell Script | https://github.com/flast101/php-8.1.0-dev-backdoor-rce | 7 | 2| 
| 20210606T00:00:16Z | Demo page for the backdoorthen package | https://github.com/johanfive/backdoordemo | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210606T23:20:28Z | Cross platform coverage-guided fuzzer with dynamic instrumentation | https://github.com/alal4465/Archer | 4 | 0| 
| 20210606T22:54:45Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 283 | 38| 
| 20210606T21:51:19Z | Este repositorio contiene el código de una propuesta para llevar a cabo el ataque por correlación y emparejamiento cruzado a el esquema de bóveda difusa.  | https://github.com/Mariuki/CorrelationAttack2FuzzyVault | 0 | 0| 
| 20210606T20:32:58Z | Atividade feita para a aula de Inteligência Computacional | https://github.com/BrunoPivoto/AtividadeFuzzy | 0 | 0| 
| 20210606T20:24:47Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6365 | 1290| 
| 20210606T20:22:32Z | Null | https://github.com/JoDeMiro/FuzzyBevezetes | 0 | 0| 
| 20210606T19:53:19Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210606T18:55:38Z | Null | https://github.com/julesbeley/Fuzzy-string-matching-pandas | 0 | 0| 
| 20210606T18:35:42Z | A passive diode fuzz Eurorack module with switches for changing which diodes are included | https://github.com/rahji/fivefingerfuzz | 0 | 0| 
| 20210606T18:27:28Z | Null | https://github.com/Sghosh1999/fuzzy_search | 1 | 0| 



# 日更新程序
