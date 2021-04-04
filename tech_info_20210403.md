# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210403 | 网络空间资产测绘(CAM)能力指南 | https://mp.weixin.qq.com/s/p3LwmZq7nrGOy5qy7p9SDQ| 
| 20210403 | 安全是一门语言的艺术：威胁调查分析语言概述 | https://mp.weixin.qq.com/s/U8E4JxMDeL5IeVGAh9fuiQ| 
| 20210403 | 对美军新近发展作战理念的梳理与思考 | https://mp.weixin.qq.com/s/D8T6ImssRi8sjDqD4_bGpg| 
| 20210403 | DGA域名检测的工程实践 | https://mp.weixin.qq.com/s/GlWqTWQzBfoXt8J8uJAPRQ| 
| 20210403 | CVE-2016-0165 Win32k漏洞分析笔记 | https://xz.aliyun.com/t/9348| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210403T23:47:22Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210403T21:17:20Z | CVE-2021-24098 | POC for CVE-2021-24098 | https://github.com/waleedassar/CVE-2021-24098 | Windows Console Driver Denial of Service Vulnerability| 
| 20210403T16:23:43Z | 未知编号 | Null | https://github.com/CyberCommands/CVE2021-21975 | 未查询到CVE信息| 
| 20210403T13:53:06Z | CVE-2020-25213 | Null | https://github.com/piruprohacking/CVE-2020-25213 | The File Manager (wp-file-manager) plugin before 6.9 for WordPress allows remote attackers to upload and execute arbitrary PHP code because it renames an unsafe example elFinder connector file to have the .php extension. This, for example, allows attackers to run the elFinder upload (or mkfile and put) command to write PHP code into the wp-content/plugins/wp-file-manager/lib/files/ directory. This was exploited in the wild in August and September 2020.| 
| 20210403T13:50:42Z | CVE-2020-17453 | PoC (Proof of Concept) - CVE-2020-17453 | https://github.com/JHHAX/CVE-2020-17453-PoC | 未查询到CVE信息| 
| 20210403T12:56:38Z | CVE-2021-22986 | CVE-2021-22986 & F5 BIG-IP RCE | https://github.com/Al1ex/CVE-2021-22986 | On BIG-IP versions 16.0.x before 16.0.1.1, 15.1.x before 15.1.2.1, 14.1.x before 14.1.4, 13.1.x before 13.1.3.6, and 12.1.x before 12.1.5.3 amd BIG-IQ 7.1.0.x before 7.1.0.3 and 7.0.0.x before 7.0.0.2, the iControl REST interface has an unauthenticated remote command execution vulnerability. Note: Software versions which have reached End of Software Development (EoSD) are not evaluated.| 
| 20210403T12:10:03Z | CVE-2021-21972 | Null | https://github.com/password520/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210403T08:56:32Z | CVE-2021-21975 | [CVE-2021-21975] VMware vRealize Operations Manager API Server Side Request Forgery (SSRF) | https://github.com/murataydemir/CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 
| 20210403T02:35:05Z | CVE-2021-3156 | Sudo Baron Samedit Exploit | https://github.com/worawit/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210403T02:01:20Z | 未知编号 | Null | https://github.com/feihong-cs/Attacking_Shiro_with_CVE_2020_2555 | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210403T13:51:43Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 377 | 9| 
| 20210403T13:37:18Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 116 | 10| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210403T23:30:19Z | Null | https://github.com/capnhowdie11/OnlyFans-exploit | 0 | 0| 
| 20210403T22:53:06Z | Le but de ce projet est de réaliser un mécanisme d’allocation / désallocation de mémoire inspiré du fameux couple malloc() / free() de la librairie standard. La gestion de l’espace libre (par exemple suite à la suppression de structures allouées) est un aspect important du projet. Le système devra s’appuyer sur une zone mémoire allouée en début de programme. Il y a donc 4 fonctions à écrire pour pouvoir l’utiliser : /* initialisation de la zone de travail */ int initMemory(int nBytes); /* allocation dynamique d’espace dans la zone */ void* myalloc(int nBytes); /* désallocation d’une zone adressée par un pointeur */ int myfree(void* p); /* recuperation de la zone initialement reservee */ int freeMemory(); | https://github.com/tbdev99/Projet-Systeme-d-exploitation-Allocation-Dynamique | 0 | 0| 
| 20210403T22:45:36Z | PS4 Exploit Host | https://github.com/Night-King-Host/Night-King-Host.github.io | 6 | 3| 
| 20210403T22:41:10Z | PS1 savegame exploit | https://github.com/socram8888/tonyhax | 230 | 6| 
| 20210403T22:38:45Z | exploit/unix/selea/authenticated_command_execution | https://github.com/enty8080/selea_authenticated_rce | 1 | 0| 
| 20210403T22:35:28Z | Swiss Boot Memory Cards and Game Save Hacks a la GCMM | https://github.com/GameCubeHomebrew/GameSave-Exploits | 0 | 0| 
| 20210403T21:47:17Z | Windows Exploit Suggester - Next Generation | https://github.com/bitsadmin/wesng | 2258 | 355| 
| 20210403T21:03:34Z | Modular penetration testing platform that enables you to write, test, and execute exploit code. | https://github.com/EntySec/HatSploit | 24 | 8| 
| 20210403T20:53:49Z | Exploit Education challenges. | https://github.com/theirisbugs/exploit-education-phoenix | 0 | 0| 
| 20210403T20:35:09Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9223 | 1492| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210403T22:14:59Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 56 | 10| 
| 20210403T21:11:39Z | Fully Undetectable Malware Backdoor | https://github.com/raunvk/stealthware-backdoor | 10 | 5| 
| 20210403T20:31:05Z | Null | https://github.com/Wiilldd/backdoor | 0 | 0| 
| 20210403T08:13:39Z | A pseudo C2 Server and backdoor to *simulate* the way usual C2 server works | https://github.com/alainpetit21/POLY_CY101_client_Server | 0 | 0| 
| 20210403T06:30:22Z | Null | https://github.com/rlarjsdn2313/backdoor | 0 | 0| 
| 20210403T06:00:26Z | I created this script to help make it easier for you to directly attack index.php on the website | https://github.com/penucuriCode/shell-backdoor | 1 | 1| 
| 20210403T01:11:51Z | Null | https://github.com/cranelab/backdoor-museum | 0 | 0| 
| 20210403T00:58:33Z | [Disclaimer FireROOT] This repository is for research purposes only, the use of this code is your responsibility. CONTACT ME: Attack@fireRootHacker.Ga | https://github.com/facenano/fireroothacker | 1 | 1| 
| 20210403T00:42:39Z | Null | https://github.com/ouldevloper/python-backdoor | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210403T23:28:23Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 42 | 4| 
| 20210403T22:52:33Z | Fuzzy matching for Neovim | https://github.com/amirrezaask/fuzzy.nvim | 23 | 1| 
| 20210403T22:38:53Z | Null | https://github.com/Juanosorio94/fuzzing-rdma | 0 | 0| 
| 20210403T22:35:48Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 269 | 37| 
| 20210403T22:05:40Z | https://github.com/wcventure/FuzzingPaper | https://github.com/mishmashclone/wcventure-FuzzingPaper | 5 | 1| 
| 20210403T22:00:53Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 4 | 1| 
| 20210403T21:33:29Z | Null | https://github.com/Sambigeara/fuzzynote | 2 | 1| 
| 20210403T20:42:04Z | Null | https://github.com/DanielEbert/EmulatedFirmwareFuzzing | 0 | 0| 
| 20210403T20:17:06Z | Null | https://github.com/swaroop-acharjee/type_2_fuzzy_segmentation | 0 | 0| 
| 20210403T20:12:53Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2301 | 123| 



# 日更新程序
