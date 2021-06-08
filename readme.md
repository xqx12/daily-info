# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210608 | 高通 TEE 可信执行环境（QSEE）漏洞的利用分析 | https://raelize.com/blog/qualcomm-ipq40xx-breaking-into-qsee-using-fault-injection/| 
| 20210608 | YouTube 上有人分享如何为 SerenityOS 打造一款 JS 字节码虚拟机的教程 | https://www.youtube.com/playlist?list=PLMOpZvQB55beChggmvk-sUm8X_vSezpqL| 
| 20210608 | AppLocker-Bypass: Bypassing AppLocker (executing Powershell scripts/commands) with C# | https://github.com/o1mate/AppLocker-Bypass| 
| 20210608 | Project Zero 开源的 Jackalope Fuzzer 支持在 Linux 开启 Sanitizer Coverage 了 | https://github.com/googleprojectzero/Jackalope/blob/main/README_sancov.md| 
| 20210608 | Siloscape - Palo Alto 发现了第一个通过 Windows 容器环境攻击 Kubernetes clusters 的恶意软件 | https://unit42.paloaltonetworks.com/siloscape/| 
| 20210608 | NetGear Nighthawk WiFi 路由器使用的第三方网络套件 QUAGGA 的漏洞分析 | https://versprite.com/blog/security-research/netgear-nighthawk-router-security-bug/?utm_content=169073507&utm_medium=social&utm_source=twitter&hss_channel=tw-146588685| 
| 20210608 | KRF - Kernelspace Randomized Faulter，基于 Fault injection 技术实现的针对 Linux/FreeBSD 平台的 Fuzzer | https://github.com/trailofbits/krf| 
| 20210608 | 研究员 riusksk 对 HITB AMS 2021 会议部分议题的分析 | https://mp.weixin.qq.com/s/5eC3oKLYthmVwzV3gR9ryQ| 
| 20210608 | VCSA 6.5-7.0 远程代码执行 CVE-2021-21985 漏洞分析 | http://noahblog.360.cn/vcenter-cve-2021-2021-21985/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210608 | InForSec学术交流会 参会小计DAY2 | https://mp.weixin.qq.com/s/LPRoggcsRIl1xT0xMXpLeQ| 
| 20210608 | InForSec学术交流会 参会小计DAY2 | /news/29266| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210608T11:36:47Z | cve-2021-21985 | cve-2021-21985 exploit | https://github.com/xnianq/cve-2021-21985_exp | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210608T11:36:38Z | CVE-2021-21985 | CVE-2021-21985 VMware vCenter Server远程代码执行漏洞 EXP (更新可回显EXP) | https://github.com/r0ckysec/CVE-2021-21985 | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210608T05:57:32Z | CVE-2021-29505 | 对CVE-2021-29505进行复现，并分析学了下Xstream反序列化过程 | https://github.com/MyBlackManba/CVE-2021-29505 | XStream is software for serializing Java objects to XML and back again. A vulnerability in XStream versions prior to 1.4.17 may allow a remote attacker has sufficient rights to execute commands of the host only by manipulating the processed input stream. No user who followed the recommendation to setup XStream%s security framework with a whitelist limited to the minimal required types is affected. The vulnerability is patched in version 1.4.17.| 
| 20210608T04:06:19Z | CVE-2021-22911 | Pre-Auth Blind NoSQL Injection leading to Remote Code Execution in Rocket Chat 3.12.1 | https://github.com/CsEnox/CVE-2021-22911 | A improper input sanitization vulnerability exists in Rocket.Chat server 3.11, 3.12 & 3.13 that could lead to unauthenticated NoSQL injection, resulting potentially in RCE.| 
| 20210608T02:35:21Z | CVE-2021-21985 | Null | https://github.com/testanull/Project_CVE-2021-21985_PoC | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210608T01:26:15Z | CVE-2020-17514 | PoC for exploiting CVE-2020-17514 | https://github.com/JamesGeeee/CVE-2020-17514 | Apache Fineract prior to 1.5.0 disables HTTPS hostname verification in ProcessorHelper in the configureClient method. Under typical deployments, a man in the middle attack could be successful.| 
| 20210608T01:26:05Z | CVE-2021-33839 | PoC for exploiting CVE-2021-33839 | https://github.com/JamesGeeee/CVE-2021-33839 | Luca through 1.7.4 on Android allows remote attackers to obtain sensitive information about COVID-19 tracking because the QR code of a Public Location can be intentionally confused with the QR code of a Private Meeting.| 
| 20210608T01:26:00Z | CVE-2021-22911 | PoC for exploiting CVE-2021-22911 | https://github.com/JamesGeeee/CVE-2021-22911 | A improper input sanitization vulnerability exists in Rocket.Chat server 3.11, 3.12 & 3.13 that could lead to unauthenticated NoSQL injection, resulting potentially in RCE.| 
| 20210608T01:24:53Z | CVE-2021-33840 | PoC for exploiting CVE-2021-33840 | https://github.com/JamesGeeee/CVE-2021-33840 | The server in Luca through 1.1.14 allows remote attackers to cause a denial of service (insertion of many fake records related to COVID-19) because Phone Number data lacks a digital signature.| 
| 20210608T01:24:01Z | CVE-2021-33838 | PoC for exploiting CVE-2021-33838 | https://github.com/JamesGeeee/CVE-2021-33838 | Luca through 1.7.4 on Android allows remote attackers to obtain sensitive information about COVID-19 tracking because requests related to Check-In State occur shortly after requests for Phone Number Registration.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210608T11:39:23Z | Null | https://github.com/JaimePSantos/ResearchKlee | 0 | 0| 
| 20210608T10:40:58Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 18 | 0| 
| 20210608T06:49:03Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 654 | 15| 
| 20210608T06:41:04Z | Dodoco doko? | https://github.com/RiceFT/klee | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210608T08:53:41Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 130 | 31| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210608T12:29:06Z | The MATLAB P-code for estimating quality of JPEG compressed images. The code can be exploited to estimate quality of JPEG compressed images irrespective of block size and position of blocking artifact. | https://github.com/MdAmirBaig/IQA-of-JPEG-compressed-image | 0 | 0| 
| 20210608T12:27:25Z | Access Manager sera comme un gestionnaire d’accès ou plutôt de gestion de machine Windows agissant tel un contrôle parental. Ayant la possibilité de bloquer des sites internet spécifiques comme le fait DansGuardian. Néanmoins le point ces derniers sont appelés filtres DNS/Web et sont exploitables (bypassable) par la simple utilisation d’un VPN car ceux-ci agissent à l’aide de l’adresse IP du routeur. Notre point fort sera à ce niveau de bloquer les sites internets même si un VPN y est utilisé. Son point faible sera qu’il n’est qu’exécutable sous Windows. Le projet pourra filter les téléchargements / fichiers [ouverts/ecris] etc comme sous forme d’un Évent Log mais plus sophistiqué. Mais également d’éteindre la machine ou le wifi ou d’autoriser que certaines applications à s’exécuter à une plage horaire précise (il sera bien évidement impossible de modifier l’heure sous le système) il sera possible d’enregistrer des images / ou keylogg la machine afin d’avoir un suivi régulier et avance il sera aussi prévu (pas de date) de retrouver chaque machine possédant une license Access Manager via une interface web de récupérer certaines de ces informations. | https://github.com/Sehyn/Access-Manager | 0 | 0| 
| 20210608T12:25:40Z | The MATLAB P-code for estimating quality of JPEG compressed images. The code can be exploited to estimate quality of JPEG compressed images irrespective of block size and position of blocking artifact. | https://github.com/MdAmirBaig/Quality-Assessment-of-JPEG-compressed-image-with-known-and-unknown-positions-of-blocking-artifact | 0 | 0| 
| 20210608T12:20:21Z | CDK is an open-sourced container penetration toolkit, offering stable exploitation in different slimmed containers without any OS dependency. It comes with penetration tools and many powerful PoCs/EXPs helps you to escape container and takeover K8s cluster easily. | https://github.com/cdk-team/CDK | 1443 | 218| 
| 20210608T12:15:17Z | Repo for testing some exploits | https://github.com/RobertFent/exploits | 0 | 0| 
| 20210608T12:06:52Z | PKU-Exploit | https://github.com/xxycfhb/xxycfhb.github.io | 0 | 0| 
| 20210608T12:02:52Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 24 | 11| 
| 20210608T11:49:37Z | An open-source post-exploitation framework for students, researchers and developers. | https://github.com/malwaredllc/byob | 6348 | 1453| 
| 20210608T11:49:12Z | Collection of docker images to be used for exploit development and testing | https://github.com/mishrasunny174/pwn-docker | 6 | 1| 
| 20210608T11:42:06Z | Evil plugin for exploiting compromised EconicXP CMS instances | https://github.com/richardcurteis/EconicXP_CMS_Exploit | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210608T09:22:54Z | Very Easy Relative Backdoor Application | https://github.com/Not-C-Developer/VERBA | 0 | 0| 
| 20210608T03:39:45Z | Undetectable & Xor encrypting with custom KEY (FUD Metasploit Rat) bypass Top Antivirus like BitDefender,Malwarebytes,Avast,ESET-NOD32,AVG,... & Automatically Add ICON and MANIFEST to excitable | https://github.com/persianhydra/Xeexe-TopAntivirusEvasion | 465 | 107| 
| 20210608T03:36:36Z | php script to gain access to a site once injected | https://github.com/Sliden101/backdoor | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210608T12:09:17Z | Stores work from deploying web app to Heroku | https://github.com/dmottice20/fuzzy-memory | 0 | 0| 
| 20210608T12:03:11Z | Null | https://github.com/FuzzySid/FuzzySid | 0 | 0| 
| 20210608T12:00:54Z | Project page for %The Fuzzing Book% | https://github.com/uds-se/fuzzingbook | 572 | 115| 
| 20210608T11:56:32Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6368 | 1292| 
| 20210608T11:56:31Z | Thin interface for libFuzzer, an in-process, coverage-guided, evolutionary fuzzing engine. | https://github.com/planetis-m/libfuzzer | 28 | 0| 
| 20210608T11:50:26Z | Null | https://github.com/fuzzyjoin/fuzzyjoin.github.io | 0 | 0| 
| 20210608T11:26:16Z | Null | https://github.com/a6colute/fuzzy-search | 0 | 0| 
| 20210608T11:17:41Z | Null | https://github.com/s9varesc/url-fuzzing-docker | 0 | 0| 
| 20210608T11:09:42Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210608T11:07:42Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 



# 日更新程序
