# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210401 | iOS 开源工具 objection ios info binary 输出信息的分析 | https://sensepost.com/blog/2021/on-ios-binary-protections/| 
| 20210401 | How To intercept mutually-authenticated TLS communications of a Java thick client | https://offsec.almond.consulting/java-tls-intercept.html| 
| 20210401 | Starkiller：1.7.0 版本发布。基于 Electron 实现的 Powershell Empire 可视化工具。 | https://github.com/BC-SECURITY/Starkiller/releases| 
| 20210401 | SharpProxyLogon：C# 实现的 ProxyLogon RCE，用于 Microsoft Exchange Server 的 CVE-2021-26855 的利用。 | https://github.com/Flangvik/SharpProxyLogon| 
| 20210401 | 在 Cobalt Strike 工具中，使用 GUID 完成对 shellcode 混淆。 | https://www.guidepointsecurity.com/yet-another-cobalt-strike-loader-guid-edition/| 
| 20210401 | ldsview：用于离线检索 LDIF 的工具。 | http://github.com/kgoins/ldsview| 
| 20210401 | FIREEYE 发布一个用于解析 Windows 后台智能传输服务（BITS）的 Python 工具。 | https://github.com/fireeye/BitsParser| 
| 20210401 | 如何搭建一个 Linux 内核调试环境。 | https://pwning.systems/posts/setting-up-a-kernel-debugging-environment/| 
| 20210401 | Google 发表关于针对安全研究人员攻击的最新活动进展。 | https://blog.google/threat-analysis-group/update-campaign-targeting-security-researchers/| 
| 20210401 | MacOS内核安全性探讨。 | https://www.viva64.com/en/b/0818/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210401 | 驱动病毒那些事(二)----回调 | https://www.sec-in.com/article/992| 
| 20210401 | 邬晓磊：基于关键词的大型红蓝对抗经验分享 | https://mp.weixin.qq.com/s/8boR_ZucLk5nMJwfi2UdGA| 
| 20210401 | 洞态IAST Agent正式开源 | https://mp.weixin.qq.com/s/iSHmK4Fbl0whDvIH-u8tag| 
| 20210401 | 鸠占鹊巢: Furucombo 攻击事件分析 | https://mp.weixin.qq.com/s/jDQhFNEeIMT_cdjHkggYjw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210401T17:11:06Z | CVE-2021-26295 | Null | https://github.com/yumusb/CVE-2021-26295 | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 
| 20210401T17:02:00Z | CVE-2021-24098 | POC for CVE-2021-24098 | https://github.com/waleedassar/CVE-2021-24098 | Windows Console Driver Denial of Service Vulnerability| 
| 20210401T16:38:22Z | CVE-2021-1699 | POC for CVE-2021-1699 | https://github.com/waleedassar/CVE-2021-1699 | Windows (modem.sys) Information Disclosure Vulnerability| 
| 20210401T12:52:34Z | 未知编号 | Null | https://github.com/feihong-cs/Attacking_Shiro_with_CVE_2020_2555 | 未查询到CVE信息| 
| 20210401T12:48:44Z | CVE-2021-21975 | CVE-2021-21975 vRealize Operations Manager SSRF | https://github.com/Al1ex/CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 
| 20210401T12:42:37Z | CVE-2021-3156 | Sudo Baron Samedit Exploit | https://github.com/worawit/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210401T12:20:11Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210401T12:15:16Z | CVE-2021-26295 | CVE-2021-26295 Apache OFBiz POC | https://github.com/ltfafei/CVE-2021-26295_Apache_OFBiz_POC | | 
| 20210401T10:38:21Z | CVE-2021-26295 | Null | https://github.com/yumusb/CVE-2021-26295-POC | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 
| 20210401T09:59:53Z | CVE-2020-9496 | Null | https://github.com/Vulnmachines/apache-ofbiz-CVE-2020-9496 | XML-RPC request are vulnerable to unsafe deserialization and Cross-Site Scripting issues in Apache OFBiz 17.12.03| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210401T19:59:46Z | Spring 2021 Geography 817 work folder  | https://github.com/klee12/klee12.github.io | 0 | 0| 
| 20210401T14:21:03Z | Readable String Sanitizer | https://github.com/schemenauero/kleen-js | 0 | 0| 
| 20210401T10:59:44Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 114 | 9| 
| 20210401T10:43:57Z | KLEE in the browser | https://github.com/klee/klee-web | 45 | 12| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210401T23:43:40Z | A CTF web app designed to teach software developers application security by showcasing what vulnerable code looks like, how to write code to exploit the vulnerability, and how to write code to patch the vulnerability. | https://github.com/neumaneuma/appseccheat.codes | 3 | 1| 
| 20210401T23:34:44Z | --------------------------------------------------------------------------------------------------------------------------------------- - script  :  https://pst.klgrth.io/paste/7zb9xspodnoh47wnu4f6cqcc -----------------------------------------------------------------------------------------------------------------------------------------   Its called:Instant Refund Method G2A to make some easy money with BITCOIN.    Read this eBook first as it%s a core of the method:  -------------------------------------------------------------------------------------------------------------------------- https://anonfiles.com/v4s1q683qd/g2a-BTC-method_v4.0_-updated_pdf  ---------------------------------------------------------------------------------------------------------------------------    G2A Instant Refund Exploit allows you to get any product from https://www.g2a.com/ completely for free.you will need some Bitcoin (because you will have to send a payment for these products, which will be returned to your wallet instantly after making a purchase - this is how this exploit works, but I won’t describe too much here,as everything is described in that eBook.) Many people are using this method just to get free games from G2A, when the best thing to do is to purchase Steam Giftcards instead.    Steam Giftcards can be easily sold for Bitcoin on: https://paxful.com/ for example.    You can’t use VPN - because otherwise g2a won’t allow you to create an order.Some people are using this method to purchase Amazon giftcards. Dont do that they can remove your balance from your Amazon account and cancel your pending orders.If you purchase steam giftcards and sell them for Bitcoin on paxful.com, there is nothing g2a or paxful can do.    Okey if you understand everything lets go for the fun part:   // So if you can’t change your IP every order, you can use it like 7-8 times per day.    When you will have gift cards. Now what you need to do, is go to    https://paxful.com    And sell your giftcards for real money. As you can see, for $100 Steam Giftcard, you will get $80.5 BTC for example.   Here’s a link to  Giftcard:  https://www.g2a.com/en/category/gift-cards-c6  [How this works] the browser is shifted in another timezone and g2a takes that you sent the payment but does not verify it. Bitbay gives an error AFTER you got your key so your money is refunded instantly. | https://github.com/ozacksoz78/BTC-EXPLOIT-METHODS | 0 | 0| 
| 20210401T22:54:39Z | GEF - GDB Enhanced Features for exploit devs & reversers | https://github.com/hugsy/gef | 3559 | 498| 
| 20210401T22:43:18Z | HTB Exploits | https://github.com/ramilmustafayev/htb | 0 | 0| 
| 20210401T22:39:07Z | PS4 Exploit Host | https://github.com/Night-King-Host/Night-King-Host.github.io | 6 | 3| 
| 20210401T22:38:34Z | PS4 Gentoo Exploit Host for 5.05 FW with GoldHEN v1.00 Coded by SiSTRo / Port by Joonie86 | https://github.com/xforce505/xforce505.github.io | 0 | 0| 
| 20210401T22:23:22Z | Shitty paste of a roblox exploit | https://github.com/0Leak/EternalV1 | 0 | 0| 
| 20210401T22:21:33Z | Null | https://github.com/thecasual/exploits | 0 | 0| 
| 20210401T22:00:12Z | Roblox Exploit GUI lol | https://github.com/TheMinecrafter05/FaceLesS | 0 | 0| 
| 20210401T21:58:57Z | Exploit Development and Reverse Engineering with GDB Made Easy | https://github.com/pwndbg/pwndbg | 3548 | 518| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210401T18:21:11Z | PCI Express DIY hacking toolkit for Xilinx SP605 | https://github.com/Cr4sh/s6_pcie_microblaze | 308 | 78| 
| 20210401T18:04:50Z | Backdoor in PYTHON ( Test version ) | https://github.com/s4rr4/python-backdor | 1 | 0| 
| 20210401T16:12:41Z | Fully Undetectable Malware Backdoor | https://github.com/raunvk/stealthware-backdoor | 3 | 2| 
| 20210401T15:45:56Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 188 | 34| 
| 20210401T12:30:52Z | Minecraft Server Backdoor Plugin | https://github.com/NeunXKILLER20/PluginPwn | 1 | 0| 
| 20210401T12:26:19Z | Null | https://github.com/AliAbdallah454/backdoor | 0 | 0| 
| 20210401T08:09:52Z | generator of php_backdoor | https://github.com/M4chin3M4N/backdoor-gen | 0 | 0| 
| 20210401T07:17:02Z | [Disclaimer FireROOT] This repository is for research purposes only, the use of this code is your responsibility. CONTACT ME: Attack@fireRootHacker.Ga | https://github.com/facenano/fireroothacker | 1 | 1| 
| 20210401T06:41:21Z | Null | https://github.com/cranelab/backdoor-museum | 0 | 0| 
| 20210401T03:34:43Z | I created this script to help make it easier for you to directly attack index.php on the website | https://github.com/penucuriCode/shell-backdoor | 1 | 1| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210401T23:38:45Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 266 | 37| 
| 20210401T23:24:47Z | A mutation-based fuzzing engine for MQTT brokers. | https://github.com/PBearson/MosquittoByte | 0 | 0| 
| 20210401T23:16:12Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 1| 
| 20210401T23:09:35Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6170 | 1247| 
| 20210401T22:16:56Z | REST API Fuzz Testing (RAFT): Source code for self-hosted service developed for Azure, including the API, orchestration engine, and default set of security tools (including MSR%s RESTler), that enables developers to embed security tooling into their CI/CD workflows | https://github.com/microsoft/rest-api-fuzz-testing | 127 | 21| 
| 20210401T22:15:47Z | This code is based on a watering system case study from CII-2M3 Pengantar Kecerdasan Buatan Pokok Bahasan 07.ppt Telkom University | https://github.com/rarrazaan/fuzzyLogicPython | 0 | 0| 
| 20210401T22:14:28Z | Hacking tools written by me. IP fortune, webmap -- web vulns scanner, rtsp brute+fuzz, and more. | https://github.com/fagcinsk/h4ck | 1 | 0| 
| 20210401T22:03:39Z | A case study of a fuzzer in the Rascal Language | https://github.com/fuzzing-unb/rascalFuzz | 0 | 0| 
| 20210401T21:48:44Z | Autofuze has been developped to provide a full toolkit to fuzz and pentest several protocols used in automotive industry such as USB, XCP, UDS, CAN. Everything is done in Python to provide a convenient way to develop automated test. | https://github.com/DanAurea/AutoFuze | 0 | 0| 
| 20210401T20:33:46Z | This is a Fuzzer library built in JS and nodeJS | https://github.com/fuzzing-unb/FuzzerJS | 0 | 0| 



# 日更新程序
