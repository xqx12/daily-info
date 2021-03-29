# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210329 | BugBug Bounty Roadmaps | https://github.com/1ndianl33t/Bug-Bounty-Roadmaps| 
| 20210329 | Lua 字节码的反编译 | https://ferib.dev/blog.php?l=post/Lua_Devirtualization_Part_2_Decompiling_Lua| 
| 20210329 | OAuth Apps 正在成为厂商以及用户的新安全攻击面 | http://www.proofpoint.com/us/blog/cloud-security/oauth-abuse-think-solarwindssolorigate-campaign-focus-cloud-applications| 
| 20210329 | MSSQL数据库攻击实战指北 - 防守方攻略 | https://mp.weixin.qq.com/s/uENvpPan7aVd7MbSoAT9Dg| 
| 20210329 | CVE-2021-24093 Windows 图形组件远程执行代码漏洞分析 | http://blog.topsec.com.cn/cve-2021-24093-windows%E5%9B%BE%E5%BD%A2%E7%BB%84%E4%BB%B6%E8%BF%9C%E7%A8%8B%E6%89%A7%E8%A1%8C%E4%BB%A3%E7%A0%81%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/| 
| 20210329 | From HTTP 500 to Account Takeover | https://sensepost.com/blog/2021/from-500-to-account-takeover/| 
| 20210329 | Dumping LSASS in memory undetected using MirrorDump | https://www.pentestpartners.com/security-blog/dumping-lsass-in-memory-undetected-using-mirrordump/| 
| 20210329 | 浅析软件供应链攻击之包抢注低成本钓鱼 | https://security.tencent.com/index.php/blog/msg/185| 
| 20210329 | 有 Android 恶意软件伪造成系统更新 App 攻击用户 | https://blog.zimperium.com/new-advanced-android-malware-posing-as-system-update/| 
| 20210329 | 基于 CodeQL 的 C/C++ 源码静态分析实践 | https://sec.today/pulses/da6d77b2-a763-4d17-ac77-db0ff6d9482e/| 
| 20210329 | 基于 CodeQL 的 C/C++ 源码静态分析实践 | https://xz.aliyun.com/t/9275| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210329 | 病毒分析之伪装eset升级程序 | https://www.sec-in.com/article/960| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210329T12:09:43Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210329T11:55:46Z | CVE-2021-29267 | SherlockIM ChatBot XSS | https://github.com/Security-AVS/CVE-2021-29267 | 未查询到CVE信息| 
| 20210329T11:32:42Z | CVE-2021-22986 | CVE-2021-22986 & F5 BIG-IP RCE | https://github.com/Al1ex/CVE-2021-22986 | 未查询到CVE信息| 
| 20210329T09:22:29Z | CVE-2021-3156 | Sudo Baron Samedit Exploit | https://github.com/worawit/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210329T05:58:53Z | CVE-2021-22986 | Code By:Tas9er / F5 BIG-IP 远程命令执行漏洞 | https://github.com/Tas9er/CVE-2021-22986 | 未查询到CVE信息| 
| 20210329T03:13:04Z | CVE-2020-1938 | Null | https://github.com/Hancheng-Lei/Hacking-Vulnerability-CVE-2020-1938-Ghostcat | When using the Apache JServ Protocol (AJP), care must be taken when trusting incoming connections to Apache Tomcat. Tomcat treats AJP connections as having higher trust than, for example, a similar HTTP connection. If such connections are available to an attacker, they can be exploited in ways that may be surprising. In Apache Tomcat 9.0.0.M1 to 9.0.0.30, 8.5.0 to 8.5.50 and 7.0.0 to 7.0.99, Tomcat shipped with an AJP Connector enabled by default that listened on all configured IP addresses. It was expected (and recommended in the security guide) that this Connector would be disabled if not required. This vulnerability report identified a mechanism that allowed: - returning arbitrary files from anywhere in the web application - processing any file in the web application as a JSP Further, if the web application allowed file upload and stored those files within the web application (or the attacker was able to control the content of the web application by some other means) then this, along with the ability to process a file as a JSP, made remote code execution possible. It is important to note that mitigation is only required if an AJP port is accessible to untrusted users. Users wishing to take a defence-in-depth approach and block the vector that permits returning arbitrary files and execution as JSP may upgrade to Apache Tomcat 9.0.31, 8.5.51 or 7.0.100 or later. A number of changes were made to the default AJP Connector configuration in 9.0.31 to harden the default configuration. It is likely that users upgrading to 9.0.31, 8.5.51 or 7.0.100 or later will need to make small changes to their configurations.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210329T11:52:11Z | learn klee | https://github.com/dajun183/kleeverify | 0 | 0| 
| 20210329T04:17:14Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 6 | 0| 
| 20210329T02:56:38Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 372 | 10| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210329T12:08:50Z | To understand the non-uniform distribution of English letters and how that may be exploited in cryptanalysis | https://github.com/ItCallum/Cryptography-project-1 | 0 | 0| 
| 20210329T12:04:25Z | A collection of more than 140+ tools, scripts, cheatsheets and other loots that I have developed over years for Red Teaming/Pentesting/IT Security audits purposes. Most of them came handy on at least one of my real-world engagements. | https://github.com/mgeeky/Penetration-Testing-Tools | 627 | 153| 
| 20210329T12:02:40Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 13 | 6| 
| 20210329T11:50:00Z | Null | https://github.com/kiarashjam/Exploiting-Video-Games-to-Test-AV | 0 | 1| 
| 20210329T11:43:31Z | Model of resource exploitation of Iron Age communities in southwest Anatolia. To be presented at ReSoc conference | https://github.com/driesdaems10/Resoc | 1 | 1| 
| 20210329T11:41:14Z | Windows Exploit Development Tutorial Series | https://github.com/whichbuffer/WindowsExploitDev | 0 | 1| 
| 20210329T11:40:14Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9200 | 1482| 
| 20210329T11:29:34Z | Random stuff related to exploitation, reversing, etc | https://github.com/mike-hilton/binary-fun | 0 | 0| 
| 20210329T11:26:07Z | Eternalblue written in CSharp. Contains version detection, vulnerability scanner and exploit of MS17-010 | https://github.com/povlteksttv/Eternalblue | 37 | 6| 
| 20210329T11:01:11Z | %Ike: A binary exploitation and reversing handbook.  | https://github.com/mahaloz/ike | 2 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210329T12:07:39Z | A self-spreading parasitic, polymorphic internet-worm for the netBIOS backdoor | https://github.com/timo-cmd2/Win32.ThemalSh4ke | 1 | 0| 
| 20210329T11:02:10Z | WaNet - Imperceptible Warping-based Backdoor Attack (ICLR 2021) | https://github.com/VinAIResearch/Warping-based_Backdoor_Attack-release | 5 | 2| 
| 20210329T09:28:30Z | Null | https://github.com/viamAhmadi/ninja-backdoor-server | 0 | 0| 
| 20210329T09:26:49Z | Null | https://github.com/viamAhmadi/ninja-backdoor | 0 | 0| 
| 20210329T08:45:04Z | 🤖An Evil and Smart Bot for Enslaving Windows. | https://github.com/wildonion/katyusha | 1 | 1| 
| 20210329T08:10:01Z | Null | https://github.com/xpf/Backdoor-Learning-arXiv | 0 | 0| 
| 20210329T04:40:14Z | Input-aware Dynamic Backdoor Attack (NeurIPS 2020) | https://github.com/VinAIResearch/input-aware-backdoor-attack-release | 27 | 3| 
| 20210329T04:29:06Z | Fully Undetectable Malware Backdoor | https://github.com/raunvk/stealthware-backdoor | 3 | 2| 
| 20210329T04:24:22Z | Worst Panel/Script | https://github.com/sumsspiffy/worst-wtf | 1 | 0| 
| 20210329T03:15:47Z | Null | https://github.com/Madff386/backdoor | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210329T12:07:28Z | Python-based code for estiamtion of highway bottleneck probability using speed transition matrices.  | https://github.com/tisljaricleo/fuzzy-highway-bottleneck-python | 0 | 0| 
| 20210329T12:00:18Z | White-box fuzzer for Java bytecode | https://github.com/vorpal-research/kex | 6 | 5| 
| 20210329T11:38:39Z | Null | https://github.com/s9varesc/url-fuzzing-docker | 0 | 0| 
| 20210329T11:38:07Z | Null | https://github.com/iii-i/zlib-fuzz | 2 | 0| 
| 20210329T11:37:30Z | Sensor gula yang dibangun dengan konsep pembiasan cahaya dalam suatu larutan menggunakan atmega32 di bascom avr | https://github.com/Dzikrul-Hamdi-Nasution/Sensor-Gula-dengan-Fuzzy-Logic | 0 | 0| 
| 20210329T11:30:43Z | Null | https://github.com/FDU-Program-Analysis/chunk-fuzzer-pass | 0 | 0| 
| 20210329T11:08:59Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 1| 
| 20210329T10:53:24Z | A fork of AFL for fuzzing Windows binaries | https://github.com/googleprojectzero/winafl | 1634 | 419| 
| 20210329T10:50:58Z | fuzzy matching for very large datasets in .NET | https://github.com/mohamedshabanofficial/FuzzyMatching | 0 | 0| 
| 20210329T10:46:23Z | Fuzzy TS optimisation based on genetic algorithm | https://github.com/jairpaulino/fuzzy-ts-opt | 0 | 0| 



# 日更新程序
