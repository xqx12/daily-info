# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210907 | Reversing and Exploiting Samsungs Neural Processing Unit | https://github.com/Impalabs/conferences/blob/master/2021-barbhack21/21-Barbhack21-Reversing_and_Exploiting_Samsungs_Neural_Processing_Unit.pdf| 
| 20210907 | 用深度学习的方案检测命令混淆的问题 | https://medium.com/adobetech/using-deep-learning-to-better-detect-command-obfuscation-965b448973e0?source=social.tw&_branch_match_id=963757906340777726| 
| 20210907 | How to Exploit SQL Server Using OLE Automation | https://www.imperva.com/blog/how-to-exploit-sql-server-using-ole-automation/?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+Imperviews+%28Imperva+Cyber+Security+Blog%29| 
| 20210907 | 西部数据 PR4100 NAS 远程 Root 漏洞分析 | http://www.synacktiv.com/en/publications/your-vulnerability-is-in-another-oem.html| 
| 20210907 | 加密邮件提供商 ProtonMail 被发现将特殊用户的 IP 地址等信息提供给监管机构 | https://thehackernews.com/2021/09/protonmail-shares-activists-ip-address.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+TheHackersNews+%28The+Hackers+News+-+Cyber+Security+Blog%29| 
| 20210907 | 利用蓝牙耳机不变的 MAC 地址追踪用户 | http://nrkbeta.no/2021/09/02/someone-could-be-tracking-you-through-your-headphones/| 
| 20210907 | AMD CPU 被发现类似 Meltdown 的漏洞 | https://www.tomshardware.com/news/zen2-processor-vulnerability-mitigation| 
| 20210907 | Hacking Xiaomis Android Apps | http://blog.takemyhand.xyz/2021/07/hacking-on-xiaomis-android-apps.html| 
| 20210907 | 云原生——容器和应用安全运营实践思考 | https://security.tencent.com/index.php/blog/msg/200| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210907 | URL FIlter 绕过 - Python 之 Flask | https://github.com/CHYbeta/URLFilterBypassDemo/blob/master/python/flask_demo/README.md| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210907T23:02:56Z | CVE-2021-1590 | PoC for exploiting CVE-2021-1590 : A vulnerability in the implementation of the system login block-for command for Cisco NX-OS Software could allow an unauthenticated, remote attacker to cause a login process to unexpectedly restart, causing a denial of service (DoS) condition. This vulnerability is due to a logic error in the implementation of the system login block-for command when an attack is detected and acted upon. An attacker could exploit this vulnerability by performing a brute-force login attack on an affected device. A successful exploit could allow the attacker to cause a login process to reload, which could result in a delay during authentication to the affected device. | https://github.com/AlAIAL90/CVE-2021-1590 | A vulnerability in the implementation of the system login block-for command for Cisco NX-OS Software could allow an unauthenticated, remote attacker to cause a login process to unexpectedly restart, causing a denial of service (DoS) condition. This vulnerability is due to a logic error in the implementation of the system login block-for command when an attack is detected and acted upon. An attacker could exploit this vulnerability by performing a brute-force login attack on an affected device. A successful exploit could allow the attacker to cause a login process to reload, which could result in a delay during authentication to the affected device.| 
| 20210907T23:02:54Z | CVE-2021-1591 | PoC for exploiting CVE-2021-1591 : A vulnerability in the EtherChannel port subscription logic of Cisco Nexus 9500 Series Switches could allow an unauthenticated, remote attacker to bypass access control list (ACL) rules that are configured on an affected device. This vulnerability is due to oversubscription of resources that occurs when applying ACLs to port channel interfaces. An attacker could exploit this vulnerability by attempting to access network resources that are protected by the ACL. A successful exploit could allow the attacker to access network resources that would be protected by the ACL that was applied on the port channel interface. | https://github.com/AlAIAL90/CVE-2021-1591 | A vulnerability in the EtherChannel port subscription logic of Cisco Nexus 9500 Series Switches could allow an unauthenticated, remote attacker to bypass access control list (ACL) rules that are configured on an affected device. This vulnerability is due to oversubscription of resources that occurs when applying ACLs to port channel interfaces. An attacker could exploit this vulnerability by attempting to access network resources that are protected by the ACL. A successful exploit could allow the attacker to access network resources that would be protected by the ACL that was applied on the port channel interface.| 
| 20210907T23:02:51Z | CVE-2021-1592 | PoC for exploiting CVE-2021-1592 : A vulnerability in the way Cisco UCS Manager software handles SSH sessions could allow an authenticated, remote attacker to cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper resource management for established SSH sessions. An attacker could exploit this vulnerability by opening a significant number of SSH sessions on an affected device. A successful exploit could allow the attacker to cause a crash and restart of internal Cisco UCS Manager software processes and a temporary loss of access to the Cisco UCS Manager CLI and web UI. Note: The attacker must have valid user credentials to authenticate to the affected device. | https://github.com/AlAIAL90/CVE-2021-1592 | A vulnerability in the way Cisco UCS Manager software handles SSH sessions could allow an authenticated, remote attacker to cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper resource management for established SSH sessions. An attacker could exploit this vulnerability by opening a significant number of SSH sessions on an affected device. A successful exploit could allow the attacker to cause a crash and restart of internal Cisco UCS Manager software processes and a temporary loss of access to the Cisco UCS Manager CLI and web UI. Note: The attacker must have valid user credentials to authenticate to the affected device.| 
| 20210907T23:02:48Z | CVE-2021-32955 | PoC for exploiting CVE-2021-32955 : Delta Electronics DIAEnergie Version 1.7.5 and prior allows unrestricted file uploads, which may allow an attacker to remotely execute code. | https://github.com/AlAIAL90/CVE-2021-32955 | Delta Electronics DIAEnergie Version 1.7.5 and prior allows unrestricted file uploads, which may allow an attacker to remotely execute code.| 
| 20210907T23:02:45Z | CVE-2021-32967 | PoC for exploiting CVE-2021-32967 : Delta Electronics DIAEnergie Version 1.7.5 and prior may allow an attacker to add a new administrative user without being authenticated or authorized, which may allow the attacker to log in and use the device with administrative privileges. | https://github.com/AlAIAL90/CVE-2021-32967 | Delta Electronics DIAEnergie Version 1.7.5 and prior may allow an attacker to add a new administrative user without being authenticated or authorized, which may allow the attacker to log in and use the device with administrative privileges.| 
| 20210907T23:02:42Z | CVE-2021-32991 | PoC for exploiting CVE-2021-32991 : Delta Electronics DIAEnergie Version 1.7.5 and prior is vulnerable to cross-site request forgery, which may allow an attacker to cause a user to carry out an action unintentionally. | https://github.com/AlAIAL90/CVE-2021-32991 | Delta Electronics DIAEnergie Version 1.7.5 and prior is vulnerable to cross-site request forgery, which may allow an attacker to cause a user to carry out an action unintentionally.| 
| 20210907T23:02:40Z | CVE-2021-33003 | PoC for exploiting CVE-2021-33003 : Delta Electronics DIAEnergie Version 1.7.5 and prior may allow an attacker to retrieve passwords in cleartext due to a weak hashing algorithm. | https://github.com/AlAIAL90/CVE-2021-33003 | Delta Electronics DIAEnergie Version 1.7.5 and prior may allow an attacker to retrieve passwords in cleartext due to a weak hashing algorithm.| 
| 20210907T23:02:37Z | CVE-2021-32983 | PoC for exploiting CVE-2021-32983 : A Blind SQL injection vulnerability exists in the /DataHandler/Handler_CFG.ashx endpoint of Delta Electronics DIAEnergie Version 1.7.5 and prior. The application does not properly validate the user-controlled value supplied through the parameter keyword before using it as part of an SQL query. A remote, unauthenticated attacker can exploit this issue to execute arbitrary code in the context of NT SERVICE\MSSQLSERVER. | https://github.com/AlAIAL90/CVE-2021-32983 | A Blind SQL injection vulnerability exists in the /DataHandler/Handler_CFG.ashx endpoint of Delta Electronics DIAEnergie Version 1.7.5 and prior. The application does not properly validate the user-controlled value supplied through the parameter keyword before using it as part of an SQL query. A remote, unauthenticated attacker can exploit this issue to execute arbitrary code in the context of NT SERVICE\MSSQLSERVER.| 
| 20210907T23:02:34Z | CVE-2021-33007 | PoC for exploiting CVE-2021-33007 : A heap-based buffer overflow in Delta Electronics TPEditor: v1.98.06 and prior may be exploited by processing a specially crafted project file. Successful exploitation of this vulnerability may allow an attacker to execute arbitrary code. | https://github.com/AlAIAL90/CVE-2021-33007 | A heap-based buffer overflow in Delta Electronics TPEditor: v1.98.06 and prior may be exploited by processing a specially crafted project file. Successful exploitation of this vulnerability may allow an attacker to execute arbitrary code.| 
| 20210907T23:02:32Z | CVE-2021-33019 | PoC for exploiting CVE-2021-33019 : A stack-based buffer overflow vulnerability in Delta Electronics DOPSoft Version 4.00.11 and prior may be exploited by processing a specially crafted project file, which may allow an attacker to execute arbitrary code. | https://github.com/AlAIAL90/CVE-2021-33019 | A stack-based buffer overflow vulnerability in Delta Electronics DOPSoft Version 4.00.11 and prior may be exploited by processing a specially crafted project file, which may allow an attacker to execute arbitrary code.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210907T14:59:27Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2737 | 73| 
| 20210907T14:41:50Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 14 | 45| 
| 20210907T14:03:25Z | Config files for my GitHub profile. | https://github.com/Kleemann77/Kleemann77 | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210907T23:43:36Z | Artics Roblox Exploit for @articsdev | https://github.com/P-DennyGamingYT/Artics | 0 | 0| 
| 20210907T23:33:54Z | FLOOD is a tool which exploits some of the most popular DDoS attacks | https://github.com/4anonz/FLOOD | 0 | 0| 
| 20210907T23:26:34Z | Coe rpzd cola lá no meu canal fiz um exploit group sem precisar de ADM sem ko | https://github.com/davizinZZZ/davizinZZZ | 1 | 0| 
| 20210907T23:23:06Z | Post exploitation helper | https://github.com/melnicek/peh | 32 | 5| 
| 20210907T23:02:56Z | PoC for exploiting CVE-2021-1590 : A vulnerability in the implementation of the system login block-for command for Cisco NX-OS Software could allow an unauthenticated, remote attacker to cause a login process to unexpectedly restart, causing a denial of service (DoS) condition. This vulnerability is due to a logic error in the implementation of the system login block-for command when an attack is detected and acted upon. An attacker could exploit this vulnerability by performing a brute-force login attack on an affected device. A successful exploit could allow the attacker to cause a login process to reload, which could result in a delay during authentication to the affected device. | https://github.com/AlAIAL90/CVE-2021-1590 | 0 | 0| 
| 20210907T23:02:54Z | PoC for exploiting CVE-2021-1591 : A vulnerability in the EtherChannel port subscription logic of Cisco Nexus 9500 Series Switches could allow an unauthenticated, remote attacker to bypass access control list (ACL) rules that are configured on an affected device. This vulnerability is due to oversubscription of resources that occurs when applying ACLs to port channel interfaces. An attacker could exploit this vulnerability by attempting to access network resources that are protected by the ACL. A successful exploit could allow the attacker to access network resources that would be protected by the ACL that was applied on the port channel interface. | https://github.com/AlAIAL90/CVE-2021-1591 | 0 | 0| 
| 20210907T23:02:51Z | PoC for exploiting CVE-2021-1592 : A vulnerability in the way Cisco UCS Manager software handles SSH sessions could allow an authenticated, remote attacker to cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper resource management for established SSH sessions. An attacker could exploit this vulnerability by opening a significant number of SSH sessions on an affected device. A successful exploit could allow the attacker to cause a crash and restart of internal Cisco UCS Manager software processes and a temporary loss of access to the Cisco UCS Manager CLI and web UI. Note: The attacker must have valid user credentials to authenticate to the affected device. | https://github.com/AlAIAL90/CVE-2021-1592 | 0 | 0| 
| 20210907T23:02:48Z | PoC for exploiting CVE-2021-32955 : Delta Electronics DIAEnergie Version 1.7.5 and prior allows unrestricted file uploads, which may allow an attacker to remotely execute code. | https://github.com/AlAIAL90/CVE-2021-32955 | 0 | 0| 
| 20210907T23:02:45Z | PoC for exploiting CVE-2021-32967 : Delta Electronics DIAEnergie Version 1.7.5 and prior may allow an attacker to add a new administrative user without being authenticated or authorized, which may allow the attacker to log in and use the device with administrative privileges. | https://github.com/AlAIAL90/CVE-2021-32967 | 0 | 0| 
| 20210907T23:02:42Z | PoC for exploiting CVE-2021-32991 : Delta Electronics DIAEnergie Version 1.7.5 and prior is vulnerable to cross-site request forgery, which may allow an attacker to cause a user to carry out an action unintentionally. | https://github.com/AlAIAL90/CVE-2021-32991 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210907T23:31:36Z | Null | https://github.com/ammarin25455/Remote-Desktop-Backdoor | 0 | 0| 
| 20210907T23:24:40Z | Backdoored Plugin for anarchy servers  | https://github.com/ssllllll/Backdoored-Plugin | 2 | 1| 
| 20210907T23:15:48Z | Null | https://github.com/Huiying-Li/Latent-Backdoor | 0 | 0| 
| 20210907T13:36:28Z | Nuker bot and backdoor for admin perms and such | https://github.com/ESYT2021/discord-bot-backdoor | 0 | 0| 
| 20210907T13:20:51Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 307 | 57| 
| 20210907T12:50:06Z | Code and data of the EMNLP 2021 paper %Mind the Style of Text! Adversarial and Backdoor Attacks Based on Text Style Transfer% | https://github.com/thunlp/StyleAttack | 0 | 0| 
| 20210907T12:44:18Z | Unofficial pytorch implementation of RobNet(Defense-Resistant Backdoor Attacks on DNN) | https://github.com/dhkim2810/RobNet | 0 | 0| 
| 20210907T06:49:58Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) remote administration and post-exploitation tool mainly written in python | https://github.com/n1nj4sec/pupy | 6546 | 1655| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210907T17:46:36Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2446 | 363| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210907T23:37:26Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 299 | 39| 
| 20210907T23:09:32Z | 1xpaNck4vI0r43R4jwOc2LEzljF_7qQ5QNMZxmVvE7spp4dKg | https://github.com/machinei/fuzzy-spork | 0 | 0| 
| 20210907T22:52:58Z | Rockyou for web fuzzing | https://github.com/six2dez/OneListForAll | 314 | 77| 
| 20210907T22:07:37Z | Repo for the New HI-SPACE project. Named because fuzzy-octo-robot is much more fun than %new-hi-space%, and since this is a personal project I choose fun :)  | https://github.com/ahope/fuzzy-octo-robot | 0 | 0| 
| 20210907T21:44:58Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6635 | 1358| 
| 20210907T21:20:20Z | Null | https://github.com/tlperini/fuzzyclock | 0 | 0| 
| 20210907T21:01:35Z | Null | https://github.com/FuzzFinance/fuzz-swap-core | 0 | 0| 
| 20210907T20:41:38Z | Web fuzzing tool | https://github.com/fagci/fuzzy | 0 | 0| 
| 20210907T20:32:58Z | Hacking tools written by me. IP fortune, webmap -- web vulns scanner, rtsp brute+fuzz, and more. | https://github.com/fagci/h4ck | 11 | 4| 
| 20210907T20:21:01Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3673 | 872| 



# 日更新程序
