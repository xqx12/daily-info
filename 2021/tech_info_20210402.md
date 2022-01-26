# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210402 | James Forshaw：关于 Windows Server Containers 的安全研究背景、过程和一些见解。 | https://googleprojectzero.blogspot.com/2021/04/who-contains-containers.html| 
| 20210402 | 通过函数指针回调，很多 Win 32 的 API 可以被用于执行 shellcode。 | https://osandamalith.com/2021/04/01/executing-shellcode-via-callbacks/| 
| 20210402 | CVE-2021-24098 的 POC。关于 Windows 控制台驱动的拒绝服务漏洞。 | https://github.com/waleedassar/CVE-2021-24098| 
| 20210402 | Mikko Kenttälä：macOS Mail 的一个无交互的漏洞。由于符号连接未正确删除，通过自动解压附件，可以实现在 Mail.app 的沙箱环境中添加或修改任意文件。 | https://mikko-kenttala.medium.com/zero-click-vulnerability-in-apples-macos-mail-59e0c14b106c| 
| 20210402 | 当 ajaxpipe 或 quickling 的参数添加到 Fackbook 的任意站点请求时，错误的响应可能会造成 Facebook 的 access_token 被恶意接管。 | https://ysamm.com/?p=654| 
| 20210402 | Facebook 在 OAuth 认证中的 fallback_redirect_uri 路径检查不完整，使得 Facebook 和 Instagram 账户可以被恶意接管。 | https://ysamm.com/?p=646| 
| 20210402 | ProChecker：用于自动化分析 4G LTE 协议的安全性和隐私框架。 | https://syed-rafiul-hussain.github.io/wp-content/uploads/2021/03/ProChecker.pdf| 
| 20210402 | Michael Stepankin：nOtWASP 前十个让人哭笑不得的漏洞。 | https://portswigger.net/research/notwasp-bottom-10-vulnerabilities-that-make-you-cry| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210402 | 国内伪基站垃圾短信生态系统研究 | https://mp.weixin.qq.com/s/te4igYM_PHbf2xedXdmQxw| 
| 20210402 | 驱动病毒那些事(三)----APC注入 | https://www.sec-in.com/article/994| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210402T23:06:50Z | CVE-2021-21975 | [CVE-2021-21975] VMware vRealize Operations Manager API Server Side Request Forgery (SSRF) | https://github.com/murataydemir/CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 
| 20210402T22:50:55Z | CVE-2021-21975 | Nmap script to check vulnerability CVE-2021-21975 | https://github.com/GuayoyoCyber/CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 
| 20210402T22:16:34Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210402T19:12:54Z | CVE-2020-9922 | Null | https://github.com/Wowfunhappy/Fix-Apple-Mail-CVE-2020-9922 | A logic issue was addressed with improved state management. This issue is fixed in macOS Catalina 10.15.6, Security Update 2020-004 Mojave, Security Update 2020-004 High Sierra. Processing a maliciously crafted email may lead to writing arbitrary files.| 
| 20210402T17:35:03Z | 未知编号 | Null | https://github.com/feihong-cs/Attacking_Shiro_with_CVE_2020_2555 | 未查询到CVE信息| 
| 20210402T11:30:27Z | CVE-2021-24098 | POC for CVE-2021-24098 | https://github.com/waleedassar/CVE-2021-24098 | Windows Console Driver Denial of Service Vulnerability| 
| 20210402T09:31:09Z | CVE-2021-3156 | Sudo Baron Samedit Exploit | https://github.com/worawit/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210402T03:45:52Z | CVE-2021-1699 | POC for CVE-2021-1699 | https://github.com/waleedassar/CVE-2021-1699 | Windows (modem.sys) Information Disclosure Vulnerability| 
| 20210402T03:06:32Z | CVE-2021-1732 | Null | https://github.com/ltfafei/CVE-2021-1732_exp | Windows Win32k Elevation of Privilege Vulnerability This CVE ID is unique from CVE-2021-1698.| 
| 20210402T03:06:31Z | CVE-2021-26295 | CVE-2021-26295 Apache OFBiz POC | https://github.com/ltfafei/CVE-2021-26295_Apache_OFBiz_POC | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210402T23:50:49Z | Null | https://github.com/abbykleespie/LAWk8AbbyKleespie.appstudio | 0 | 0| 
| 20210402T19:52:36Z | Spring 2021 Geography 817 work folder  | https://github.com/klee12/klee12.github.io | 0 | 0| 
| 20210402T17:04:07Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 375 | 10| 
| 20210402T17:02:49Z | Personal Blog | https://github.com/klee1611/klee1611.github.io | 0 | 0| 
| 20210402T12:45:42Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 6 | 1| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210402T06:55:39Z | Null | https://github.com/yuvalkirstain/s2e-coref | 2 | 2| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210402T23:15:09Z | A module for Garry%s Mod that mitigates exploits on the Source engine. | https://github.com/danielga/gmsv_serversecure | 61 | 17| 
| 20210402T23:07:24Z | Thi powershell script has got to run in remote windows host, even for pivoting | https://github.com/FabioDefilippo/winallenum | 2 | 1| 
| 20210402T22:56:52Z | lab_tool is a system that allows you to do ethical hacking tests. | https://github.com/dylan14567/lab_tool | 1 | 2| 
| 20210402T22:46:11Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 10 | 1| 
| 20210402T22:43:43Z | GEF - GDB Enhanced Features for exploit devs & reversers | https://github.com/hugsy/gef | 3560 | 498| 
| 20210402T22:22:14Z | Le but de ce projet est de réaliser un mécanisme d’allocation / désallocation de mémoire inspiré du fameux couple malloc() / free() de la librairie standard. La gestion de l’espace libre (par exemple suite à la suppression de structures allouées) est un aspect important du projet. Le système devra s’appuyer sur une zone mémoire allouée en début de programme. Il y a donc 4 fonctions à écrire pour pouvoir l’utiliser : /* initialisation de la zone de travail */ int initMemory(int nBytes); /* allocation dynamique d’espace dans la zone */ void* myalloc(int nBytes); /* désallocation d’une zone adressée par un pointeur */ int myfree(void* p); /* recuperation de la zone initialement reservee */ int freeMemory(); | https://github.com/tbdev99/Projet-Systeme-d-exploitation-Allocation-Dynamique | 0 | 0| 
| 20210402T22:19:57Z | Modular penetration testing platform that enables you to write, test, and execute exploit code. | https://github.com/EntySec/HatSploit | 24 | 8| 
| 20210402T22:15:17Z | A simple pickle assembler to make handcrafting pickle bytecode easier. | https://github.com/gousaiyang/pickleassem | 0 | 0| 
| 20210402T21:28:33Z | Various ASM, C and C++ tools, shellcodes and exploit experiments. | https://github.com/forrest-orr/ExploitDev | 57 | 6| 
| 20210402T21:22:10Z | scan/ exploit lfi vulnerabilities | https://github.com/DSimsek000/finc | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210402T23:38:25Z | PCI Express DIY hacking toolkit for Xilinx SP605 | https://github.com/Cr4sh/s6_pcie_microblaze | 312 | 79| 
| 20210402T23:28:43Z | Simple lua backdoor, Dong, watheck, jayboy  | https://github.com/IncognitoBasePlate/Backdoor-test-for-roblox | 0 | 0| 
| 20210402T22:06:11Z | Null | https://github.com/Wiilldd/backdoor | 0 | 0| 
| 20210402T21:02:31Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 56 | 10| 
| 20210402T17:49:08Z | The Stick Hacker is an advanced type backdoor made by myself (Ihatestick) this version is 0.1 beta | https://github.com/Ihatestick/The-Stick-Hacker | 1 | 0| 
| 20210402T15:13:24Z | Shell Backdoor | https://github.com/FadliYunianto/Fadli | 0 | 0| 
| 20210402T12:36:30Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 188 | 34| 
| 20210402T10:14:55Z | Null | https://github.com/Kenya123/backdoor | 0 | 0| 
| 20210402T08:11:20Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 201 | 34| 
| 20210402T03:18:54Z | generator of php_backdoor | https://github.com/M4chin3M4N/backdoor-gen | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210402T23:50:32Z | This is a Fuzzer library built in JS and nodeJS | https://github.com/fuzzing-unb/FuzzerJS | 0 | 0| 
| 20210402T23:14:34Z | Docker image for fuzzing the Dungeon (zork) text based adventure game | https://github.com/realmadsci/zorkfuzzing | 0 | 0| 
| 20210402T22:58:45Z | Epub source for the Standard Ebooks edition of Little Fuzzy, by H. Beam Piper | https://github.com/standardebooks/h-beam-piper_little-fuzzy | 1 | 2| 
| 20210402T22:40:43Z | Null | https://github.com/mnathvt/nlp_fuzzy_match_algorithms | 0 | 0| 
| 20210402T22:40:18Z | Null | https://github.com/DanielEbert/EmulatedFirmwareFuzzing | 0 | 0| 
| 20210402T22:20:23Z | SecLists is the security tester%s companion. It%s a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. | https://github.com/danielmiessler/SecLists | 30745 | 15672| 
| 20210402T21:54:11Z | Fuzzy matching for Neovim | https://github.com/amirrezaask/fuzzy.nvim | 23 | 1| 
| 20210402T21:53:32Z | Black-box fuzzer that fuzzes APIs based on OpenAPI specification | https://github.com/matusf/openapi-fuzzer | 1 | 0| 
| 20210402T21:49:22Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2298 | 122| 
| 20210402T21:32:21Z | 📨 Responsive email template generator. | https://github.com/luangjokaj/fuzzymail | 114 | 4| 



# 日更新程序
