# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210416 | Chromium V8 增加了额外的检查以解决近期关于 Chromium 浏览器系列上的远程 RCE 漏洞。 | https://chromium.googlesource.com/v8/v8/+/d4aafa4022b718596b3deadcc3cdcb9209896154| 
| 20210416 | Chromium V8 JavaScript引擎远程代码执行漏洞分析讨论。 | http://noahblog.360.cn/chromium_v8_remote_code_execution_vulnerability_analysis/| 
| 20210416 | 通过网页中的 6 个特征字段检测钓鱼站点。 | https://bradleyjkemp.dev/post/6-ways-to-detect-phishing-sites-using-high-entropy-strings/| 
| 20210416 | Exploiting System Mechanic Driver | https://voidsec.com/exploiting-system-mechanic-driver/| 
| 20210416 | JavaScript prototype 污染攻击的寻找和利用。 | https://infosecwriteups.com/javascript-prototype-pollution-practice-of-finding-and-exploitation-f97284333b2?gi=9db44f26abcf| 
| 20210416 | 利用 url 默认处理规则实现 RCE。 | https://positive.security/blog/url-open-rce| 
| 20210416 | 利用 C# 和 DInvoke 执行 UUID shellcode。 | https://blog.sunggwanchoi.com/eng-uuid-shellcode-execution/| 
| 20210416 | 通过 Fuzz 发现 Telegrams animated stickers 的远程攻击漏洞。 | https://www.shielder.it/blog/2021/02/hunting-for-bugs-in-telegrams-animated-stickers-remote-attack-surface/| 
| 20210416 | JTAGulator：辅助从目标设备上识别 OCD（On-chip debug） 接口的开源工具。OCD 接口可以提供对目标设备 chip-level 权限控制，便于提取程序或数据，修改寄存器内容。 | https://github.com/grandideastudio/jtagulator/blob/1.11/CHANGES.markdown| 
| 20210416 | Attack Detection Fundamentals 2021 macOS - Lab #1：通过 Office 获取访问权限（包括沙箱穿透） | https://sec.today/pulses/60949952-6461-42d9-a963-57b905f28c4c/| 
| 20210416 | Attack Detection Fundamentals 2021 macOS - Lab #1：通过 Office 获取访问权限（包括沙箱穿透） | https://labs.f-secure.com/blog/attack-detection-fundamentals-2021-macos-lab-1/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210416 | 哥斯拉插件开发指南——初入茅庐 | https://mp.weixin.qq.com/s/Q2eFRQQCEVf4bf_jNsWX2g| 
| 20210416 | Spring Boot中关于%2e的Trick | http://rui0.cn/archives/1643| 
| 20210416 | Driftingblues5靶机实战 | https://www.sec-in.com/article/1021| 
| 20210416 | 可扩展跨平台网络安全工具套件 CaptfEncoder v2.0.0 发布 | https://mp.weixin.qq.com/s?__biz=MzI0ODU5Mzg0NA==&mid=2247483998&idx=1&sn=baaa69c5576a1e52b7d8aeb9482e1cf3&chksm=e99f2e85dee8a79304a5535dbf6c77e9f9def6b2a7438c73e28792ac5ea3c628a02204d116e6&token=2122222341&lang=zh_CN#rd| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210416T21:40:35Z | CVE-2021-24086 | Proof of concept for CVE-2021-24086, a NULL dereference in tcpip.sys triggered remotely. | https://github.com/0vercl0k/CVE-2021-24086 | Windows TCP/IP Denial of Service Vulnerability| 
| 20210416T20:49:41Z | CVE-2021-29447 | Null | https://github.com/motikan2010/CVE-2021-29447 | Wordpress is an open source CMS. A user with the ability to upload files (like an Author) can exploit an XML parsing issue in the Media Library leading to XXE attacks. This requires WordPress installation to be using PHP 8. Access to internal files is possible in a successful XXE attack. This has been patched in WordPress version 5.7.1, along with the older affected versions via a minor release. We strongly recommend you keep auto-updates enabled.| 
| 20210416T19:33:02Z | CVE-2021-22986 | Null | https://github.com/nice0e3/CVE-2021-22986_F5_BIG_IP_GUI_Exploit | On BIG-IP versions 16.0.x before 16.0.1.1, 15.1.x before 15.1.2.1, 14.1.x before 14.1.4, 13.1.x before 13.1.3.6, and 12.1.x before 12.1.5.3 amd BIG-IQ 7.1.0.x before 7.1.0.3 and 7.0.0.x before 7.0.0.2, the iControl REST interface has an unauthenticated remote command execution vulnerability. Note: Software versions which have reached End of Software Development (EoSD) are not evaluated.| 
| 20210416T19:31:53Z | CVE-2020-14882 | Null | https://github.com/nice0e3/CVE-2020-14882_Exploit_Gui | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210416T15:07:57Z | CVE-2020-9472 | CVE-2020-9472 构造文件 | https://github.com/john-dooe/CVE-2020-9472-poisoned-plugin | Umbraco CMS 8.5.3 allows an authenticated file upload (and consequently Remote Code Execution) via the Install Package functionality.| 
| 20210416T13:56:27Z | CVE-2021-3156 | CVE-2021-3156: Sudo heap overflow exploit for Debain 10 | https://github.com/0xdevil/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210416T07:55:48Z | CVE-2020-7461 | PoC for DHCP vulnerability (NAME:WRECK) in FreeBSD | https://github.com/knqyf263/CVE-2020-7461 | | 
| 20210416T06:04:51Z | CVE-2021-21402 | CVE-2021-21402 Jellyfin任意文件读取 Wker脚本，可批量。 | https://github.com/givemefivw/CVE-2021-21402 | Jellyfin is a Free Software Media System. In Jellyfin before version 10.7.1, with certain endpoints, well crafted requests will allow arbitrary file read from a Jellyfin server%s file system. This issue is more prevalent when Windows is used as the host OS. Servers that are exposed to the public Internet are potentially at risk. This is fixed in version 10.7.1. As a workaround, users may be able to restrict some access by enforcing strict security permissions on their filesystem, however, it is recommended to update as soon as possible.| 
| 20210416T05:40:58Z | CVE-2020-25078 | D-Link DCS系列摄像头账号密码信息泄露批量脚本 | https://github.com/S0por/CVE-2020-25078 | An issue was discovered on D-Link DCS-2530L before 1.06.01 Hotfix and DCS-2670L through 2.02 devices. The unauthenticated /config/getuser endpoint allows for remote administrator password disclosure.| 
| 20210416T05:40:05Z | CVE-2021-26295 | Apache OFBiz rmi反序列化EXP(CVE-2021-26295) | https://github.com/S0por/CVE-2021-26295-Apache-OFBiz-EXP | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210416T10:15:55Z | test | https://github.com/xenoney/kleee | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210416T10:04:27Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 115 | 26| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210416T23:47:22Z | passive keyless entry exploit research | https://github.com/zeetulsa/pke | 1 | 0| 
| 20210416T23:44:35Z | Null | https://github.com/tedtag/exploits | 0 | 0| 
| 20210416T23:40:59Z | Null | https://github.com/hicwwq/OutageExploit-v1 | 0 | 0| 
| 20210416T23:34:51Z | Identifying and exploiting vulnerabilities on a target server while also investigating the attack%s characteristics using Kibana SIEM | https://github.com/gabalayan/Penetration-Testing-and-Incident-Response-Project | 0 | 0| 
| 20210416T23:10:06Z | A collection of challenge writeups, CVE POC%s, and explanations | https://github.com/0xmanjoos/Exploit-Development | 1 | 1| 
| 20210416T23:09:35Z | Security and Hacking Tools, Exploits, Proof of Concepts, Shellcodes, Scripts. | https://github.com/nullsecuritynet/tools | 1371 | 453| 
| 20210416T23:01:09Z | PS4 Gentoo Exploit Host for 5.05 FW with GoldHEN v1.1 Coded by SiSTRo / Port by Joonie86 | https://github.com/xforce505/xforce505.github.io | 0 | 0| 
| 20210416T22:40:39Z | dockerized version of https://github.com/Al-Azif/ps4-exploit-host/releases | https://github.com/phixion/psx-docker | 0 | 0| 
| 20210416T22:20:45Z | This study has exploited correlation analysis and machine learning-based algorithms to identify relevant attributes in the used cars dataset which has a significant impact on predicting a used car%s price. | https://github.com/xizhao1019/UsedCars-Analysis | 0 | 0| 
| 20210416T21:38:01Z | My custom buffer overflow fuzzer and exploit script | https://github.com/A1-exe/bufferoverflow | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210416T21:10:48Z | LeuxBackdoor 100% clean y Deobf UwU, Cualquier duda Mandarme MD Luscius#0001 | https://github.com/Luscius-Dev/LeuxBackdoor-0.6-DEOBF | 1 | 1| 
| 20210416T20:02:48Z | Null | https://github.com/ChGunay/Backdoor-ArkaKapi | 0 | 0| 
| 20210416T19:36:04Z | PCI Express DIY hacking toolkit for Xilinx SP605 | https://github.com/Cr4sh/s6_pcie_microblaze | 318 | 79| 
| 20210416T19:29:31Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 62 | 11| 
| 20210416T19:17:18Z | This is a fully functional Backdoor program, which is made in python 2. It includes many useful and important functions which are related to CyberSecurity and Hacking. | https://github.com/Muhammad-Haris-Arain/Advance-Backdoor-Program | 0 | 0| 
| 20210416T16:15:29Z | Null | https://github.com/subhomoy-roy-choudhury/BackDoor_Script | 0 | 0| 
| 20210416T13:16:48Z | Null | https://github.com/mikkelskov1/backdoor2 | 0 | 0| 
| 20210416T12:14:57Z | Null | https://github.com/sanjayVontela/Backdoor | 0 | 0| 
| 20210416T08:01:57Z | Null | https://github.com/Wrench56/Backdoor | 0 | 0| 
| 20210416T07:41:28Z | A pure-Rust library for VMware host-guest protocol (%VMXh backdoor%) | https://github.com/lucab/vmw_backdoor-rs | 3 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210416T23:01:23Z | RESTler is the first stateful REST API fuzzing tool for automatically testing cloud services through their REST APIs and finding security and reliability bugs in these services. | https://github.com/microsoft/restler-fuzzer | 750 | 76| 
| 20210416T21:58:22Z | Usermode code for the ARM OS fuzzer project | https://github.com/jprx/arm-os-fuzzer-usercode | 0 | 0| 
| 20210416T21:43:35Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2315 | 124| 
| 20210416T21:38:06Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6203 | 1250| 
| 20210416T21:38:01Z | My custom buffer overflow fuzzer and exploit script | https://github.com/A1-exe/bufferoverflow | 0 | 0| 
| 20210416T21:12:25Z | Security oriented software fuzzer. Supports evolutionary, feedback-driven fuzzing based on code coverage (SW and HW based) | https://github.com/google/honggfuzz | 2191 | 439| 
| 20210416T20:44:27Z | Null | https://github.com/rochdiD/fuzzy-search | 0 | 0| 
| 20210416T20:39:19Z | a simplified means to CRUD ephemeral user-scoped EC2 instances | https://github.com/rstudio/fuzzbucket | 3 | 1| 
| 20210416T20:14:11Z | Python scripts to fuzz test a MUD through telnet. | https://github.com/virthe/mudfuzz | 1 | 0| 
| 20210416T20:06:13Z | Null | https://github.com/Tarik02/io-ts-fuzzy | 0 | 0| 



# 日更新程序
