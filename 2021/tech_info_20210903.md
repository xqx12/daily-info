# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210903 | BRAKTOOTH - 有研究团队在蓝牙协议中发现多个崩溃和死锁问题，影响超过 1400 款产品。 | https://asset-group.github.io/disclosures/braktooth/| 
| 20210903 | Metasploit 生成的 Shellcode 的导入函数解析以及执行流程分析 | https://blog.nviso.eu/2021/09/02/anatomy-and-disruption-of-metasploit-shellcode/| 
| 20210903 | 微软对 SolarWinds APT 组织使用的 Serv-U FTP 软件 CVE-2021-35211 漏洞的分析 | https://www.microsoft.com/security/blog/2021/09/02/a-deep-dive-into-the-solarwinds-serv-u-ssh-vulnerability/| 
| 20210903 | DHCP Games with Smart Router Devices | https://www.anvilsecure.com/blog/dhcp-games-with-smart-router-devices.html| 
| 20210903 | VoIP 及 SIP 客戶端 Linphone 存在协议中的拒绝服务漏洞，攻击者可以远程 Crash 目标 Client | https://claroty.com/2021/08/31/blog-research-crashing-sip-clients-with-a-single-slash/| 
| 20210903 | Multiple vulnerabilities in EMC VNX NAS 8.1.9-232 | https://www.errno.fr/VNX_advisory| 
| 20210903 | 有研究团队测试发现，GitHub Copilot 基于 AI 生成的代码也常常存在漏洞 | https://arxiv.org/abs/2108.09293| 
| 20210903 | MySQL InnoDB memcached plugin 堆缓冲区溢出漏洞分析（CVE-2021-2429） | https://www.thezdi.com/blog/2021/9/2/cve-2021-2429-a-heap-based-buffer-overflow-bug-in-the-mysql-innodb-memcached-plugin| 
| 20210903 | Play the music and bypass TCC aka CVE-2020-29621 | https://wojciechregula.blog/post/play-the-music-and-bypass-tcc-aka-cve-2020-29621/| 
| 20210903 | WhatsApp GIF 图片处理过程中的越界读写漏洞分析（CVE-2020-1910） | https://sec.today/pulses/3887a67d-f06b-451a-a019-73e9b3ba7ad0/| 
| 20210903 | WhatsApp GIF 图片处理过程中的越界读写漏洞分析（CVE-2020-1910） | https://research.checkpoint.com/2021/now-patched-vulnerability-in-whatsapp-could-have-led-to-data-exposure-of-users/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210903 | HITB 2021 新加坡安全会议公开视频 | https://www.youtube.com/playlist?list=PLmv8T5-GONwQhUlGN2UhOAi8YxPaiYCDQ| 
| 20210903 | Fileless Malware | https://dmcxblue.net/2021/08/30/fileless-malware/| 
| 20210903 | DARPA近年网络空间安全领域主要项目梳理 | https://mp.weixin.qq.com/s/CwXqkHDSFK6XMFtvOpnsjw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210903T22:57:11Z | CVE-2021-1588 | PoC for exploiting CVE-2021-1588 : A vulnerability in the MPLS Operation, Administration, and Maintenance (OAM) feature of Cisco NX-OS Software could allow an unauthenticated, remote attacker to cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper input validation when an affected device is processing an MPLS echo-request or echo-reply packet. An attacker could exploit this vulnerability by sending malicious MPLS echo-request or echo-reply packets to an interface that is enabled for MPLS forwarding on the affected device. A successful exploit could allow the attacker to cause the MPLS OAM process to crash and restart multiple times, causing the affected device to reload and resulting in a DoS condition. | https://github.com/AlAIAL90/CVE-2021-1588 | A vulnerability in the MPLS Operation, Administration, and Maintenance (OAM) feature of Cisco NX-OS Software could allow an unauthenticated, remote attacker to cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper input validation when an affected device is processing an MPLS echo-request or echo-reply packet. An attacker could exploit this vulnerability by sending malicious MPLS echo-request or echo-reply packets to an interface that is enabled for MPLS forwarding on the affected device. A successful exploit could allow the attacker to cause the MPLS OAM process to crash and restart multiple times, causing the affected device to reload and resulting in a DoS condition.| 
| 20210903T22:57:07Z | CVE-2021-1590 | PoC for exploiting CVE-2021-1590 : A vulnerability in the implementation of the system login block-for command for Cisco NX-OS Software could allow an unauthenticated, remote attacker to cause a login process to unexpectedly restart, causing a denial of service (DoS) condition. This vulnerability is due to a logic error in the implementation of the system login block-for command when an attack is detected and acted upon. An attacker could exploit this vulnerability by performing a brute-force login attack on an affected device. A successful exploit could allow the attacker to cause a login process to reload, which could result in a delay during authentication to the affected device. | https://github.com/AlAIAL90/CVE-2021-1590 | A vulnerability in the implementation of the system login block-for command for Cisco NX-OS Software could allow an unauthenticated, remote attacker to cause a login process to unexpectedly restart, causing a denial of service (DoS) condition. This vulnerability is due to a logic error in the implementation of the system login block-for command when an attack is detected and acted upon. An attacker could exploit this vulnerability by performing a brute-force login attack on an affected device. A successful exploit could allow the attacker to cause a login process to reload, which could result in a delay during authentication to the affected device.| 
| 20210903T22:57:03Z | CVE-2021-1591 | PoC for exploiting CVE-2021-1591 : A vulnerability in the EtherChannel port subscription logic of Cisco Nexus 9500 Series Switches could allow an unauthenticated, remote attacker to bypass access control list (ACL) rules that are configured on an affected device. This vulnerability is due to oversubscription of resources that occurs when applying ACLs to port channel interfaces. An attacker could exploit this vulnerability by attempting to access network resources that are protected by the ACL. A successful exploit could allow the attacker to access network resources that would be protected by the ACL that was applied on the port channel interface. | https://github.com/AlAIAL90/CVE-2021-1591 | A vulnerability in the EtherChannel port subscription logic of Cisco Nexus 9500 Series Switches could allow an unauthenticated, remote attacker to bypass access control list (ACL) rules that are configured on an affected device. This vulnerability is due to oversubscription of resources that occurs when applying ACLs to port channel interfaces. An attacker could exploit this vulnerability by attempting to access network resources that are protected by the ACL. A successful exploit could allow the attacker to access network resources that would be protected by the ACL that was applied on the port channel interface.| 
| 20210903T22:56:59Z | CVE-2021-1592 | PoC for exploiting CVE-2021-1592 : A vulnerability in the way Cisco UCS Manager software handles SSH sessions could allow an authenticated, remote attacker to cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper resource management for established SSH sessions. An attacker could exploit this vulnerability by opening a significant number of SSH sessions on an affected device. A successful exploit could allow the attacker to cause a crash and restart of internal Cisco UCS Manager software processes and a temporary loss of access to the Cisco UCS Manager CLI and web UI. Note: The attacker must have valid user credentials to authenticate to the affected device. | https://github.com/AlAIAL90/CVE-2021-1592 | A vulnerability in the way Cisco UCS Manager software handles SSH sessions could allow an authenticated, remote attacker to cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper resource management for established SSH sessions. An attacker could exploit this vulnerability by opening a significant number of SSH sessions on an affected device. A successful exploit could allow the attacker to cause a crash and restart of internal Cisco UCS Manager software processes and a temporary loss of access to the Cisco UCS Manager CLI and web UI. Note: The attacker must have valid user credentials to authenticate to the affected device.| 
| 20210903T22:56:53Z | CVE-2021-32967 | PoC for exploiting CVE-2021-32967 : Delta Electronics DIAEnergie Version 1.7.5 and prior may allow an attacker to add a new administrative user without being authenticated or authorized, which may allow the attacker to log in and use the device with administrative privileges. | https://github.com/AlAIAL90/CVE-2021-32967 | Delta Electronics DIAEnergie Version 1.7.5 and prior may allow an attacker to add a new administrative user without being authenticated or authorized, which may allow the attacker to log in and use the device with administrative privileges.| 
| 20210903T22:56:51Z | CVE-2021-32955 | PoC for exploiting CVE-2021-32955 : Delta Electronics DIAEnergie Version 1.7.5 and prior allows unrestricted file uploads, which may allow an attacker to remotely execute code. | https://github.com/AlAIAL90/CVE-2021-32955 | Delta Electronics DIAEnergie Version 1.7.5 and prior allows unrestricted file uploads, which may allow an attacker to remotely execute code.| 
| 20210903T22:56:49Z | CVE-2021-32991 | PoC for exploiting CVE-2021-32991 : Delta Electronics DIAEnergie Version 1.7.5 and prior is vulnerable to cross-site request forgery, which may allow an attacker to cause a user to carry out an action unintentionally. | https://github.com/AlAIAL90/CVE-2021-32991 | Delta Electronics DIAEnergie Version 1.7.5 and prior is vulnerable to cross-site request forgery, which may allow an attacker to cause a user to carry out an action unintentionally.| 
| 20210903T22:56:45Z | CVE-2021-33003 | PoC for exploiting CVE-2021-33003 : Delta Electronics DIAEnergie Version 1.7.5 and prior may allow an attacker to retrieve passwords in cleartext due to a weak hashing algorithm. | https://github.com/AlAIAL90/CVE-2021-33003 | Delta Electronics DIAEnergie Version 1.7.5 and prior may allow an attacker to retrieve passwords in cleartext due to a weak hashing algorithm.| 
| 20210903T22:56:41Z | CVE-2021-32983 | PoC for exploiting CVE-2021-32983 : A Blind SQL injection vulnerability exists in the /DataHandler/Handler_CFG.ashx endpoint of Delta Electronics DIAEnergie Version 1.7.5 and prior. The application does not properly validate the user-controlled value supplied through the parameter keyword before using it as part of an SQL query. A remote, unauthenticated attacker can exploit this issue to execute arbitrary code in the context of NT SERVICE\MSSQLSERVER. | https://github.com/AlAIAL90/CVE-2021-32983 | A Blind SQL injection vulnerability exists in the /DataHandler/Handler_CFG.ashx endpoint of Delta Electronics DIAEnergie Version 1.7.5 and prior. The application does not properly validate the user-controlled value supplied through the parameter keyword before using it as part of an SQL query. A remote, unauthenticated attacker can exploit this issue to execute arbitrary code in the context of NT SERVICE\MSSQLSERVER.| 
| 20210903T22:56:37Z | CVE-2021-33007 | PoC for exploiting CVE-2021-33007 : A heap-based buffer overflow in Delta Electronics TPEditor: v1.98.06 and prior may be exploited by processing a specially crafted project file. Successful exploitation of this vulnerability may allow an attacker to execute arbitrary code. | https://github.com/AlAIAL90/CVE-2021-33007 | A heap-based buffer overflow in Delta Electronics TPEditor: v1.98.06 and prior may be exploited by processing a specially crafted project file. Successful exploitation of this vulnerability may allow an attacker to execute arbitrary code.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210903T18:24:08Z | ⚡ Kleeja Open Source Desktop Application (Windows / Linux / Mac) | https://github.com/Lil-Nickel/Kleeja-da | 1 | 1| 
| 20210903T14:37:56Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2712 | 69| 
| 20210903T13:04:35Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 175 | 19| 
| 20210903T12:21:17Z | Null | https://github.com/pansilup/cgc-prgs-for-klee-seed-mode | 0 | 0| 
| 20210903T05:57:00Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 13 | 1| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210903T22:57:11Z | PoC for exploiting CVE-2021-1588 : A vulnerability in the MPLS Operation, Administration, and Maintenance (OAM) feature of Cisco NX-OS Software could allow an unauthenticated, remote attacker to cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper input validation when an affected device is processing an MPLS echo-request or echo-reply packet. An attacker could exploit this vulnerability by sending malicious MPLS echo-request or echo-reply packets to an interface that is enabled for MPLS forwarding on the affected device. A successful exploit could allow the attacker to cause the MPLS OAM process to crash and restart multiple times, causing the affected device to reload and resulting in a DoS condition. | https://github.com/AlAIAL90/CVE-2021-1588 | 0 | 0| 
| 20210903T22:57:07Z | PoC for exploiting CVE-2021-1590 : A vulnerability in the implementation of the system login block-for command for Cisco NX-OS Software could allow an unauthenticated, remote attacker to cause a login process to unexpectedly restart, causing a denial of service (DoS) condition. This vulnerability is due to a logic error in the implementation of the system login block-for command when an attack is detected and acted upon. An attacker could exploit this vulnerability by performing a brute-force login attack on an affected device. A successful exploit could allow the attacker to cause a login process to reload, which could result in a delay during authentication to the affected device. | https://github.com/AlAIAL90/CVE-2021-1590 | 0 | 0| 
| 20210903T22:57:03Z | PoC for exploiting CVE-2021-1591 : A vulnerability in the EtherChannel port subscription logic of Cisco Nexus 9500 Series Switches could allow an unauthenticated, remote attacker to bypass access control list (ACL) rules that are configured on an affected device. This vulnerability is due to oversubscription of resources that occurs when applying ACLs to port channel interfaces. An attacker could exploit this vulnerability by attempting to access network resources that are protected by the ACL. A successful exploit could allow the attacker to access network resources that would be protected by the ACL that was applied on the port channel interface. | https://github.com/AlAIAL90/CVE-2021-1591 | 0 | 0| 
| 20210903T22:56:59Z | PoC for exploiting CVE-2021-1592 : A vulnerability in the way Cisco UCS Manager software handles SSH sessions could allow an authenticated, remote attacker to cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper resource management for established SSH sessions. An attacker could exploit this vulnerability by opening a significant number of SSH sessions on an affected device. A successful exploit could allow the attacker to cause a crash and restart of internal Cisco UCS Manager software processes and a temporary loss of access to the Cisco UCS Manager CLI and web UI. Note: The attacker must have valid user credentials to authenticate to the affected device. | https://github.com/AlAIAL90/CVE-2021-1592 | 0 | 0| 
| 20210903T22:56:53Z | PoC for exploiting CVE-2021-32967 : Delta Electronics DIAEnergie Version 1.7.5 and prior may allow an attacker to add a new administrative user without being authenticated or authorized, which may allow the attacker to log in and use the device with administrative privileges. | https://github.com/AlAIAL90/CVE-2021-32967 | 0 | 0| 
| 20210903T22:56:51Z | PoC for exploiting CVE-2021-32955 : Delta Electronics DIAEnergie Version 1.7.5 and prior allows unrestricted file uploads, which may allow an attacker to remotely execute code. | https://github.com/AlAIAL90/CVE-2021-32955 | 0 | 0| 
| 20210903T22:56:49Z | PoC for exploiting CVE-2021-32991 : Delta Electronics DIAEnergie Version 1.7.5 and prior is vulnerable to cross-site request forgery, which may allow an attacker to cause a user to carry out an action unintentionally. | https://github.com/AlAIAL90/CVE-2021-32991 | 0 | 0| 
| 20210903T22:56:45Z | PoC for exploiting CVE-2021-33003 : Delta Electronics DIAEnergie Version 1.7.5 and prior may allow an attacker to retrieve passwords in cleartext due to a weak hashing algorithm. | https://github.com/AlAIAL90/CVE-2021-33003 | 0 | 0| 
| 20210903T22:56:41Z | PoC for exploiting CVE-2021-32983 : A Blind SQL injection vulnerability exists in the /DataHandler/Handler_CFG.ashx endpoint of Delta Electronics DIAEnergie Version 1.7.5 and prior. The application does not properly validate the user-controlled value supplied through the parameter keyword before using it as part of an SQL query. A remote, unauthenticated attacker can exploit this issue to execute arbitrary code in the context of NT SERVICE\MSSQLSERVER. | https://github.com/AlAIAL90/CVE-2021-32983 | 0 | 0| 
| 20210903T22:56:37Z | PoC for exploiting CVE-2021-33007 : A heap-based buffer overflow in Delta Electronics TPEditor: v1.98.06 and prior may be exploited by processing a specially crafted project file. Successful exploitation of this vulnerability may allow an attacker to execute arbitrary code. | https://github.com/AlAIAL90/CVE-2021-33007 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210903T22:21:14Z | Backdoor in c++ | https://github.com/Terraminator/Backdoor | 0 | 0| 
| 20210903T22:18:24Z | Python network worm that spreads on the local network and gives the attacker control of these machines. | https://github.com/pylyf/NetWorm | 187 | 91| 
| 20210903T18:52:19Z | A basic PoC leak for CVE-2021-28663 (Internal of the Android kernel backdoor vulnerability) | https://github.com/lntrx/CVE-2021-28663 | 19 | 5| 
| 20210903T16:35:37Z | A practical experiment on supply-chain security using reproducible builds | https://github.com/kpcyrd/i-probably-didnt-backdoor-this | 74 | 2| 
| 20210903T16:24:12Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 95 | 16| 
| 20210903T15:15:45Z | This is a ready to go compiled version of BKDR (Backdoor in-browser code editor). To access the development version of Backdoor, and would like to contribute to the development, please visit https://github.com/RecaMedia/Backdoor. | https://github.com/RecaMedia/Backdoor-Release | 14 | 7| 
| 20210903T15:15:09Z | Backdoor is a standalone browser based code editor that operates on a LASP (Linux, Apache, SQLite, PHP) server, providing all basic development tools and more. | https://github.com/RecaMedia/Backdoor | 8 | 3| 
| 20210903T15:13:08Z | Null | https://github.com/kaidi-jin/backdoor_samples_detection | 5 | 0| 
| 20210903T12:03:17Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) remote administration and post-exploitation tool mainly written in python | https://github.com/n1nj4sec/pupy | 6535 | 1654| 
| 20210903T11:26:30Z | Null | https://github.com/fatih98/backdoor | 1 | 1| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210903T20:06:59Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2444 | 362| 
| 20210903T17:21:54Z | A tool for generating nonlinear numerical invariants for C and Java programs.  DIG uses dynamic analysis to infer invariants over program execution traces and applies symbolic execution to inferred invariants. | https://github.com/unsat/dig | 8 | 4| 
| 20210903T14:45:40Z | Symbolica%s open-source symbolic execution engine. | https://github.com/SymbolicaDev/Symbolica | 4 | 1| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210903T23:05:53Z | Rockyou for web fuzzing | https://github.com/six2dez/OneListForAll | 313 | 75| 
| 20210903T22:40:42Z | Emulation based snapshot fuzzer | https://github.com/jaoeul/gingersnap | 0 | 0| 
| 20210903T22:39:10Z | Repository holding database dumps from getfursu.it | https://github.com/veelkoov/fuzzrake-data | 0 | 0| 
| 20210903T22:07:05Z | The code behind getfursu.it | https://github.com/veelkoov/fuzzrake | 6 | 0| 
| 20210903T21:53:50Z | Null | https://github.com/N-Musa/fuzzy-todoApp | 0 | 0| 
| 20210903T21:38:15Z | Code for fuzzy monkeys. | https://github.com/fuzzyatelin/fuzzyatelin.github.io | 3 | 9| 
| 20210903T21:09:45Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2386 | 137| 
| 20210903T20:32:41Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210903T19:55:58Z | RESTler is the first stateful REST API fuzzing tool for automatically testing cloud services through their REST APIs and finding security and reliability bugs in these services. | https://github.com/microsoft/restler-fuzzer | 1042 | 114| 
| 20210903T19:23:51Z | Here you%ll find some of my Fuzzy Logic exercises  | https://github.com/Marceeaax/FuzzyLogic | 0 | 0| 



# 日更新程序
