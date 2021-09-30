# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210929 | VMware vCenter CVE-2021-22005 漏洞的 Exploit 代码被公开了 | https://securityaffairs.co/wordpress/122686/hacking/cve-2021-22005-exploit-vmware-vcenter.html?utm_source=feedly&utm_medium=rss&utm_campaign=cve-2021-22005-exploit-vmware-vcenter| 
| 20210929 | 5 RCEs in npm for $15,000 | https://robertchen.cc/blog/2021/09/20/npm-rce| 
| 20210929 | 原型链污染（Prototype Pollution）漏洞的扫描及利用 | https://blog.s1r1us.ninja/research/PP| 
| 20210929 | radius - 基于 radare2 写的符号执行引擎 | https://github.com/aemmitt-ns/radius| 
| 20210929 | XSS to RCE: Covert Target Websites into Payload Landing Pages | https://whynotsecurity.com/blog/xss-to-rce/| 
| 20210929 | Call Stack Spoofing PoC，用于替换调用栈躲避杀软检测 | https://github.com/mgeeky/ThreadStackSpoofer| 
| 20210929 | Elkeid - 一个云原生的基于主机的安全(入侵检测与风险识别)解决方案 | https://paper.seebug.org/1566/| 
| 20210929 | 卡巴斯基对间谍组件 FinSpy 的最新分析 | https://securelist.com/finspy-unseen-findings/104322/| 
| 20210929 | Google 发起新的奖励计划，推动研究员为 Tsunami 漏洞扫描器编写插件和指纹识别组件 | https://security.googleblog.com/2021/09/announcing-new-patch-reward-program-for.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+GoogleOnlineSecurityBlog+%28Google+Online+Security+Blog%29| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210929 | 漏洞报告中的信息一致性研究 | https://mp.weixin.qq.com/s/iDZaElzNU5iz88KR3I8Dug| 
| 20210929 | 基于频域特征的恶意流量实时检测 | https://mp.weixin.qq.com/s/FX4WfTHR61fYS5r5cP-EIQ| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210929T23:09:37Z | CVE-2021-22005 | CVE-2021-22005 - VMWare vCenter Server File Upload to RCE | https://github.com/r0ckysec/CVE-2021-22005 | The vCenter Server contains an arbitrary file upload vulnerability in the Analytics service. A malicious actor with network access to port 443 on vCenter Server may exploit this issue to execute code on vCenter Server by uploading a specially crafted file.| 
| 20210929T23:07:37Z | CVE-2021-30632 | Null | https://github.com/Lagal1990/CVE-2021-30632 | 未查询到CVE信息| 
| 20210929T20:09:47Z | CVE-2021-40444 | CVE-2021-40444 - Fully Weaponized Microsoft Office Word RCE Exploit | https://github.com/klezVirus/CVE-2021-40444 | Microsoft MSHTML Remote Code Execution Vulnerability| 
| 20210929T17:41:14Z | CVE-2021-25162 | CVE-2021-25162 | https://github.com/twentybel0w/CVE-2021-25162 | A remote execution of arbitrary commands vulnerability was discovered in some Aruba Instant Access Point (IAP) products in version(s): Aruba Instant 6.4.x: 6.4.4.8-4.2.4.17 and below; Aruba Instant 6.5.x: 6.5.4.18 and below; Aruba Instant 8.3.x: 8.3.0.14 and below; Aruba Instant 8.5.x: 8.5.0.11 and below; Aruba Instant 8.6.x: 8.6.0.7 and below; Aruba Instant 8.7.x: 8.7.1.1 and below. Aruba has released patches for Aruba Instant that address this security vulnerability.| 
| 20210929T17:40:54Z | CVE-2021-38647 | CVE-2021-38647 - POC to exploit unauthenticated RCE #OMIGOD | https://github.com/AlteredSecurity/CVE-2021-38647 | Open Management Infrastructure Remote Code Execution Vulnerability| 
| 20210929T15:45:11Z | CVE-2021-22005 | Null | https://github.com/rwincey/CVE-2021-22005 | The vCenter Server contains an arbitrary file upload vulnerability in the Analytics service. A malicious actor with network access to port 443 on vCenter Server may exploit this issue to execute code on vCenter Server by uploading a specially crafted file.| 
| 20210929T15:28:04Z | CVE-2020-2950 | Null | https://github.com/tuo4n8/CVE-2020-2950 | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Fusion Middleware (component: Analytics Web General). Supported versions that are affected are 5.5.0.0.0, 11.1.1.9.0, 12.2.1.3.0 and 12.2.1.4.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle Business Intelligence Enterprise Edition. Successful attacks of this vulnerability can result in takeover of Oracle Business Intelligence Enterprise Edition. CVSS 3.0 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210929T11:39:29Z | CVE-2021-40444 | Microsoft MSHTML Remote Code Execution Vulnerability CVE-2021-40444 | https://github.com/ozergoker/CVE-2021-40444 | Microsoft MSHTML Remote Code Execution Vulnerability| 
| 20210929T07:12:57Z | CVE-2021-3493 | Ubuntu OverlayFS Local Privesc | https://github.com/briskets/CVE-2021-3493 | The overlayfs implementation in the linux kernel did not properly validate with respect to user namespaces the setting of file capabilities on files in an underlying file system. Due to the combination of unprivileged user namespaces along with a patch carried in the Ubuntu kernel to allow unprivileged overlay mounts, an attacker could use this to gain elevated privileges.| 
| 20210929T01:29:00Z | CVE-2021-40346 | CVE-2021-40346 integer overflow enables http smuggling | https://github.com/donky16/CVE-2021-40346-POC | An integer overflow exists in HAProxy 2.0 through 2.5 in htx_add_header that can be exploited to perform an HTTP request smuggling attack, allowing an attacker to bypass all configured http-request HAProxy ACLs and possibly other ACLs.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210929T15:33:23Z | application de mesure énergétique des application métier d%une entreprise - kleegroup - api | https://github.com/CinquinAndy/klee-green-it-app-api | 0 | 0| 
| 20210929T14:28:16Z | Null | https://github.com/kleelab/kleelab.github.io | 0 | 0| 
| 20210929T12:17:10Z | for atcoder | https://github.com/kashee337/klee_atcoder | 0 | 0| 
| 20210929T09:55:24Z | projet to format csv files to pg | https://github.com/CinquinAndy/klee_csv_formater_to_pg | 0 | 0| 
| 20210929T09:32:43Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2802 | 75| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210929T11:10:27Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 161 | 37| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210929T12:52:54Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 22 | 14| 
| 20210929T12:52:07Z | A collection of more than 140+ tools, scripts, cheatsheets and other loots that I have developed over years for Red Teaming/Pentesting/IT Security audits purposes. Most of them came handy on at least one of my real-world engagements. | https://github.com/mgeeky/Penetration-Testing-Tools | 800 | 182| 
| 20210929T12:49:15Z | Understanding and Exploiting Deep Learning-based Sentiment Analysis from News Headlines for Predicting Price Movements of WTI Crude Oil | https://github.com/Captain-1337/Master-Thesis | 0 | 0| 
| 20210929T12:46:52Z | In this project, I deployed and assessed a simple web application environment’s security posture. Then, I intentionally test the security of the environment by simulating an attack scenario and exploiting cloud configuration vulnerabilities. I%ll also set up monitoring to identify suspicious behavior and vulnerable configurations and  remediate the identified misconfigurations. Finally, I tied it all together by proposing a DevOps build pipeline that includes security best practices. | https://github.com/YoussefBayouli/AWS-Cloud-Security---Protecting-Resources-and-Data-in-the-Cloud | 0 | 0| 
| 20210929T12:46:10Z | Null | https://github.com/krastanoel/exploits | 0 | 0| 
| 20210929T12:32:46Z | Exploit Development - Weaponized Exploit and Proof of Concepts (PoC)  | https://github.com/VoidSec/Exploit-Development | 50 | 17| 
| 20210929T12:13:28Z | Collection of Discord hacking tools/fun stuff/exploits that is completely developed using NodeJS. | https://github.com/I2rys/ODiscord | 6 | 4| 
| 20210929T12:11:13Z | not public yet | https://github.com/LazarusReborn/PDF-Silent-Exploit | 0 | 0| 
| 20210929T12:10:50Z | Experimental Linux kernel module that attempts to offer an in-kernel defence against the %rowhammer% exploit | https://github.com/nyarosu/rowhammer | 0 | 0| 
| 20210929T12:03:21Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 32 | 19| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210929T12:06:23Z | The best backdoor scanner there is. | https://github.com/iK4oS/backdoor.exe | 2 | 2| 
| 20210929T10:17:15Z | pybotnet -   A Python Library for building Botnet , Trojan or BackDoor for windows and linux with Telegram control panel  | https://github.com/onionj/pybotnet | 21 | 12| 
| 20210929T10:11:37Z | Remote control software | https://github.com/h1zzz/purewater | 0 | 0| 
| 20210929T08:18:34Z | Unofficial pytorch implementation of RobNet(Defense-Resistant Backdoor Attacks on DNN) | https://github.com/dhkim2810/RobNet | 0 | 0| 
| 20210929T07:07:03Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 100 | 18| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210929T12:56:31Z | radius is a fast binary emulation and symbolic execution framework using radare2 | https://github.com/aemmitt-ns/radius | 73 | 4| 
| 20210929T12:10:29Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 158 | 35| 
| 20210929T11:10:27Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 161 | 37| 
| 20210929T07:05:10Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1894 | 393| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210929T20:17:48Z | Heterogeneous Private Information Retrieval (NDSS20) | https://github.com/hamidmozaffari/HPIR-NDSS20 | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210929T23:55:28Z | Null | https://github.com/afleissner2019/fuzzy-match | 0 | 0| 
| 20210929T22:58:37Z | Implemented federated learning for binary classification (tabular data) with PyTorch. The data fuzzification technique and local differential privacy mechanism are applied to protect data privacy.  | https://github.com/taokz/FuzzyFL | 0 | 0| 
| 20210929T22:35:36Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210929T22:19:40Z | Repo para TP #4 de PIAPC | https://github.com/hernanbrue/HB_fuzzy | 0 | 0| 
| 20210929T22:10:16Z | An investigation of American Fuzzy Lop++ as a fuzzer | https://github.com/hark130/hardy-remix | 0 | 0| 
| 20210929T21:26:32Z | loving the name github gave me, this is a test for me to work on. | https://github.com/th3boe/fuzzy-lamp | 0 | 0| 
| 20210929T21:26:26Z | Null | https://github.com/yuchunju/art-works-fuzz | 0 | 0| 
| 20210929T21:03:13Z | Code for fuzzy monkeys. | https://github.com/fuzzyatelin/fuzzyatelin.github.io | 3 | 11| 
| 20210929T20:56:33Z | Null | https://github.com/xfuzzycomp/FuzzyAsteroids | 1 | 0| 
| 20210929T20:43:34Z | This repository contains the source code related to the conference paper Bias Quantification for Protected Features in Pattern Classification Problems published at the 25th Iberoamerican Congress on Pattern Recognition in March 2021. | https://github.com/LisaKouts/Fuzzy-rough-Uncertainty-Bias | 0 | 0| 



# 日更新程序
