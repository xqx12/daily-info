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
| 20210401T11:58:10Z | CVE-2021-26295 | CVE-2021-26295 Apache OFBiz POC | https://github.com/ltfafei/CVE-2021-26295_Apache_OFBiz_POC | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 
| 20210401T11:21:49Z | CVE-2021-21975 | CVE-2021-21975 vRealize Operations Manager SSRF | https://github.com/Al1ex/CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 
| 20210401T11:12:55Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210401T11:02:53Z | CVE-2021-3156 | Sudo Baron Samedit Exploit | https://github.com/worawit/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210401T10:38:21Z | CVE-2021-26295 | Null | https://github.com/yumusb/CVE-2021-26295-POC | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 
| 20210401T09:59:53Z | CVE-2020-9496 | Null | https://github.com/Vulnmachines/apache-ofbiz-CVE-2020-9496 | XML-RPC request are vulnerable to unsafe deserialization and Cross-Site Scripting issues in Apache OFBiz 17.12.03| 
| 20210401T07:34:25Z | CVE-2021-24098 | POC for CVE-2021-24098 | https://github.com/waleedassar/CVE-2021-24098 | Windows Console Driver Denial of Service Vulnerability| 
| 20210401T07:00:47Z | CVE-2021-1699 | POC for CVE-2021-1699 | https://github.com/waleedassar/CVE-2021-1699 | | 
| 20210401T02:55:30Z | CVE-2021-26828 | Null | https://github.com/hevox/CVE-2021-26828_ScadaBR_RCE | 未查询到CVE信息| 
| 20210401T02:10:14Z | 未知编号 | Null | https://github.com/feihong-cs/Attacking_Shiro_with_CVE_2020_2555 | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210401T10:59:44Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 114 | 9| 
| 20210401T10:43:57Z | KLEE in the browser | https://github.com/klee/klee-web | 45 | 12| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210401T12:02:44Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 13 | 6| 
| 20210401T12:00:52Z | -------> RAFEL<------  Android Rat  Written in Java With WebPanel For Controlling Victims | https://github.com/swagkarna/Rafel-Rat | 62 | 33| 
| 20210401T11:54:36Z | An open-source post-exploitation framework for students, researchers and developers. | https://github.com/malwaredllc/byob | 6115 | 1384| 
| 20210401T11:42:55Z | We propose an approach in which the developer interacts with the SBFL algorithm by giving feedback on the elements of the prioritized list. We exploit contextual knowledge of the user about the next item in the ranked list, with which larger code entities can be repositioned in their suspiciousness. | https://github.com/InteractiveFaultLocalization/InteractiveFaultLocalization.github.io | 0 | 0| 
| 20210401T11:35:13Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9216 | 1488| 
| 20210401T11:31:11Z | Implementation of %Collective Robustness Certificates: Exploiting Interdependence in Graph Neural Networks% | https://github.com/jan-schuchardt/collective_robustness | 0 | 0| 
| 20210401T11:10:07Z | Binary Exploitation and Reverse-Engineering (from assembly into C) | https://github.com/anyaschukin/RainFall | 9 | 4| 
| 20210401T11:08:32Z | Binary Exploitation and Reverse-Engineering (from assembly into C) | https://github.com/anyaschukin/OverRide | 0 | 1| 
| 20210401T11:02:55Z | simple exploits | https://github.com/Stexlthy/Public-Exploito-Discordo | 0 | 0| 
| 20210401T10:57:41Z | Essential python script to exploit buffer overflow | https://github.com/jayngng/buffer_overflow_exploit | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210401T08:54:02Z | PCI Express DIY hacking toolkit for Xilinx SP605 | https://github.com/Cr4sh/s6_pcie_microblaze | 305 | 76| 
| 20210401T08:09:52Z | generator of php_backdoor | https://github.com/M4chin3M4N/backdoor-gen | 0 | 0| 
| 20210401T07:38:18Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 56 | 9| 
| 20210401T07:17:02Z | [Disclaimer FireROOT] This repository is for research purposes only, the use of this code is your responsibility. CONTACT ME: Attack@fireRootHacker.Ga | https://github.com/facenano/fireroothacker | 1 | 1| 
| 20210401T06:41:21Z | Null | https://github.com/cranelab/backdoor-museum | 0 | 0| 
| 20210401T03:34:43Z | I created this script to help make it easier for you to directly attack index.php on the website | https://github.com/penucuriCode/shell-backdoor | 1 | 1| 
| 20210401T02:07:57Z | Null | https://github.com/xpf/Backdoor-Learning-arXiv | 1 | 0| 
| 20210401T01:09:28Z | Null | https://github.com/xpf/Backdoor-Learning | 0 | 0| 
| 20210401T00:41:26Z | Simple bind backdoor destined for linux servers | https://github.com/mednic/b4ckd0or | 2 | 0| 
| 20210401T00:38:56Z | Invisible, customizable backdoor for Minecraft Spigot Plugins. | https://github.com/ThiccIndustries/Minecraft-Backdoor | 2 | 1| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210401T12:09:02Z | Null | https://github.com/s9varesc/url-fuzzing | 1 | 1| 
| 20210401T12:04:47Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 1| 
| 20210401T12:02:42Z | The SMB Fuzzer fuzzes the Server  Message Block Protocol that enables file sharing, printing and IPC between Unix and Windows systems. | https://github.com/mellowCS/SMB_Fuzzer | 0 | 0| 
| 20210401T12:00:45Z | Simple fuzzer for OpenAPI 3 specification based APIs | https://github.com/vwt-digital/openapi3-fuzzer | 5 | 2| 
| 20210401T11:56:45Z | A fuzzing system based on a seq2seq model to generate valuable seed corpus. | https://github.com/kppw99/ddrfuzz | 1 | 1| 
| 20210401T11:46:56Z | A simple approximate string matching algorithm | https://github.com/vladlazar94/fuzzy-search | 0 | 0| 
| 20210401T11:46:52Z | Null | https://github.com/pankaj846/Fuzzy_Logic_Image_Enhancement | 0 | 0| 
| 20210401T11:11:36Z | a RESTful chat API in Spring Boot Gradle project !! | https://github.com/dbijaya/fuzzy-train | 1 | 0| 
| 20210401T11:04:09Z | Null | https://github.com/erdifajarf/PMDK_FuzzyAHP | 0 | 0| 
| 20210401T10:59:34Z | Fuzzy logic and neural networking assignments | https://github.com/diegoportela99/FuzzyNeural | 0 | 0| 



# 日更新程序
