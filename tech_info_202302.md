# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230203 | ESET发布2022年最后一个季度APT活动总结报告 | https://github.com/blackorbird/APT_REPORT/blob/master/summary/2023/eset_apt_activity_report_t32022.pdf| 
| 20230203 | WithSecure发布的关于lazarus APT活动各个阶段的分析与总结 | http://labs.withsecure.com/content/dam/labs/docs/WithSecure-Lazarus-No-Pineapple-Threat-Intelligence-Report-2023.pdf| 
| 20230203 | chrome v8的WebAssembly中的UAF漏洞，可在32位的Pixel中实现RCE | https://bugs.chromium.org/p/chromium/issues/detail?id=1377816| 
| 20230203 | 使用机器学习方法（随机森林）帮助完善IDA分析结果，例如用来识别函数段、识别switch跳转表、区分 Arm 和 Thumb 代码段，识别代码中的函数指针等 | http://research.checkpoint.com/2019/thumbs-up-using-machine-learning-to-improve-idas-analysis/| 
| 20230203 | Linux Netfilter 本地提权漏洞 PoC 公开，CVE-2023-0179 | http://securityonline.info/researcher-publishes-poc-exploit-for-privilege-escalation-flaw-cve-2023-0179-in-linux-kernel/| 
| 20230203 | OpenSSH server 9.1中存在一个无需身份认证的double free漏洞，但考虑到权限限制和沙箱保护等因素其可利用性较差。 | http://www.openwall.com/lists/oss-security/2023/02/02/2| 
| 20230203 | 介绍包括CVE-2022-25365在内的多个Docker漏洞，通过攻击命名管道实现权限提升，以及一个辅助分析工具PipeViewer | https://www.cyberark.com/resources/threat-research-blog/breaking-docker-named-pipes-systematically-docker-desktop-privilege-escalation-part-1| 
| 20230203 | Google Chrome 在验证命令解码器时产生的缓冲区溢出漏洞 | https://googleprojectzero.github.io/0days-in-the-wild//0day-RCAs/2022/CVE-2022-4135.html| 
| 20230203 | 介绍了一些简单的2FA的bypass方法。不过这类方法估计很难在实际中奏效。 | https://thegrayarea.tech/bug-hunting-101-multi-factor-authentication-otp-bypass-79f03b554df6?gi=3e094ba14e0a| 
| 20230203 | CVE-2022-44268:ImageMagick任意文件读取PoC | https://sec.today/pulses/1dfde550-81c4-4a03-9228-7ad6037f7143/| 
| 20230203 | CVE-2022-44268:ImageMagick任意文件读取PoC | https://github.com/duc-nt/CVE-2022-44268-ImageMagick-Arbitrary-File-Read-PoC| 
| 20230202 | MYSQL JDBC反序列化攻击介绍 | https://tttang.com/archive/1877/| 
| 20230202 | Dompdf的URI验证可通过字母大写进行绕过，导致漏洞产生 | http://securityonline.info/cve-2023-23924-critical-severity-rce-flaw-found-in-popular-dompdf-library/| 
| 20230202 | Cisco系列产品中出现高危漏洞。CVE-2023-20076：远程命令注入，需要身份认证；CSCwc67015：任意文件写，可导致代码执行。 | https://www.darkreading.com/ics-ot/command-injection-bug-cisco-industrial-gear-devices-complete-takeover| 
| 20230202 | Mimikatz Bypass Credential Guard的记录 | https://xz.aliyun.com/t/12097| 
| 20230202 | 红队入门级介绍，利用 Crackmapexec 和 mimikatz 绕过 LSA 进行Windows 域渗透，建议和文中提到的“上一篇博客”一起阅读 | https://infosecwriteups.com/unlocking-the-secrets-of-lsa-5bd29d5c6927?gi=069b8f50c100&source=rss----7b722bfd1b8d---4| 
| 20230202 | Adobe Acrobat Reader UAF漏洞（CVE-2023-21608）利用代码 | https://github.com/hacksysteam/CVE-2023-21608| 
| 20230201 | 使用ipatables命令对Android应用抓包分析。 | https://mp.weixin.qq.com/s/P0ESUUXBmq2aQnrqDHsDaw| 
| 20230201 | Dell dbutil_2_3.sys 驱动提权漏洞的exp | https://github.com/nanabingies/CVE-2021-21551| 
| 20230201 | WordPress漏洞整理 | http://sucur.it/3JxrIl4| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230201 | 九阶段太空攻击研究与战术分析框架和七层美国防太空架构 | https://mp.weixin.qq.com/s/TvEZKKzyRyb1_jVU1YeEMg| 
| 20230201 | 2022年度APT高级威胁报告 | https://book.yunzhan365.com/tkgd/ftku/mobile/index.html| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230204T01:29:16Z | CVE-2020-10883 | This vulnerability allows local attackers to escalate privileges on affected installations of TP-Link Archer A7 Firmware Ver: 190726 AC1750 routers. An attacker must first obtain the ability to execute low-privileged code on the target system in order to exploit this vulnerability. The specific flaw exists within the f CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-10883 | | 
| 20230204T01:29:12Z | CVE-2020-10882 | This vulnerability allows network-adjacent attackers to execute arbitrary code on affected installations of TP-Link Archer A7 Firmware Ver: 190726 AC1750 routers. Authentication is not required to exploit this vulnerability. The specific flaw exists within the tdpServer service, which listens on UDP port 20002 by defau CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-10882 | | 
| 20230204T01:29:08Z | CVE-2020-6806 | By carefully crafting promise resolutions, it was possible to cause an out-of-bounds read off the end of an array resized during script execution. This could have led to memory corruption and a potentially exploitable crash. This vulnerability affects Thunderbird < 68.6, Firefox < 74, Firefox < ESR68.6, and Firefox ESR CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-6806 | | 
| 20230204T01:28:48Z | CVE-2021-45868 | In the Linux kernel before 5.15.3, fs/quota/quota_tree.c does not validate the block number in the quota tree (on disk). This can, for example, lead to a kernel/locking/rwsem.c use-after-free if there is a corrupted quota file. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-45868 | | 
| 20230204T01:28:37Z | CVE-2021-24374 | The Jetpack Carousel module of the JetPack WordPress plugin before 9.8 allows users to create a "carousel" type image gallery and allows users to comment on the images. A security vulnerability was found within the Jetpack Carousel module by nguyenhg_vcs that allowed the comments of non-published page/posts to be leake CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-24374 | | 
| 20230204T01:28:23Z | CVE-2023-24806 | ** REJECT ** DO NOT USE THIS CANDIDATE NUMBER. Reason: This CVE has been rejected as it was incorrectly assigned. All references and descriptions in this candidate have been removed to prevent accidental usage. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-24806 | | 
| 20230204T01:28:12Z | CVE-2022-28711 | A memory corruption vulnerability exists in the cgi.c unescape functionality of ArduPilot APWeb master branch 50b6b7ac - master branch 46177cb9. A specially-crafted HTTP request can lead to memory corruption. An attacker can send a network request to trigger this vulnerability. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-28711 | | 
| 20230204T00:20:33Z | CVE-2023-23615 | Discourse is an open source discussion platform. The embeddable comments can be exploited to create new topics as any user but without any clear title or content. This issue is patched in the latest stable, beta and tests-passed versions of Discourse. As a workaround, disable embeddable comments by deleting all embedda CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-23615 | | 
| 20230204T00:20:30Z | CVE-2023-23082 | A heap buffer overflow vulnerability in Kodi Home Theater Software up to 19.5 allows attackers to cause a denial of service due to an improper length of the value passed to the offset argument. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-23082 | | 
| 20230204T00:20:23Z | CVE-2022-24895 | Symfony is a PHP framework for web and console applications and a set of reusable PHP components. When authenticating users Symfony by default regenerates the session ID upon login, but preserves the rest of session attributes. Because this does not clear CSRF tokens upon login, this might enables same-site attackers t CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-24895 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T17:05:07Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2148 | 604| 
| 20230203T14:15:33Z | Collection of Kicad 6.0 symbols, footprints and 3D models useful in keyboard creation | https://github.com/crides/kleeb | 74 | 6| 
| 20230203T01:31:43Z | Null | https://github.com/LuiKlee/LuiKlee.github.io | 0 | 0| 
| 20230202T19:25:20Z | ⬇️ File Upload/sharing application, used by thousands of webmasters since 2007.  | https://github.com/kleeja-official/kleeja | 169 | 50| 
| 20230202T10:48:24Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 16 | 51| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230202T13:38:52Z | Spacecraft Simulation Environment Core codes | https://github.com/ut-issl/s2e-core | 26 | 8| 
| 20230201T13:08:21Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 293 | 73| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230204T01:29:16Z | This vulnerability allows local attackers to escalate privileges on affected installations of TP-Link Archer A7 Firmware Ver: 190726 AC1750 routers. An attacker must first obtain the ability to execute low-privileged code on the target system in order to exploit this vulnerability. The specific flaw exists within the f CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-10883 | 0 | 0| 
| 20230204T01:29:12Z | This vulnerability allows network-adjacent attackers to execute arbitrary code on affected installations of TP-Link Archer A7 Firmware Ver: 190726 AC1750 routers. Authentication is not required to exploit this vulnerability. The specific flaw exists within the tdpServer service, which listens on UDP port 20002 by defau CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-10882 | 0 | 0| 
| 20230204T01:29:08Z | By carefully crafting promise resolutions, it was possible to cause an out-of-bounds read off the end of an array resized during script execution. This could have led to memory corruption and a potentially exploitable crash. This vulnerability affects Thunderbird < 68.6, Firefox < 74, Firefox < ESR68.6, and Firefox ESR CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-6806 | 0 | 0| 
| 20230204T00:21:05Z | Vulnerability in the MySQL Server product of Oracle MySQL (component: Server: Security: Encryption). Supported versions that are affected are 5.6.45 and prior and 5.7.27 and prior. Easily exploitable vulnerability allows unauthenticated attacker with network access via multiple protocols to compromise MySQL Server. Suc CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2019-2924 | 0 | 0| 
| 20230204T00:21:01Z | Vulnerability in the MySQL Connectors product of Oracle MySQL (component: Connector/ODBC). Supported versions that are affected are 5.3.13 and prior and 8.0.17 and prior. Easily exploitable vulnerability allows unauthenticated attacker with network access via multiple protocols to compromise MySQL Connectors. Successfu CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2019-2920 | 0 | 0| 
| 20230204T00:20:57Z | Vulnerability in the MySQL Server product of Oracle MySQL (component: Server: Security: Encryption). Supported versions that are affected are 5.6.45 and prior and 5.7.27 and prior. Easily exploitable vulnerability allows unauthenticated attacker with network access via multiple protocols to compromise MySQL Server. Suc CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2019-2922 | 0 | 0| 
| 20230204T00:20:54Z | Vulnerability in the MySQL Server product of Oracle MySQL (component: Server: Security: Encryption). Supported versions that are affected are 5.6.45 and prior and 5.7.27 and prior. Easily exploitable vulnerability allows unauthenticated attacker with network access via multiple protocols to compromise MySQL Server. Suc CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2019-2923 | 0 | 0| 
| 20230204T00:20:33Z | Discourse is an open source discussion platform. The embeddable comments can be exploited to create new topics as any user but without any clear title or content. This issue is patched in the latest stable, beta and tests-passed versions of Discourse. As a workaround, disable embeddable comments by deleting all embedda CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-23615 | 0 | 0| 
| 20230204T00:13:47Z | 4XX Bypass and exploit tool | https://github.com/shadowdevnotreal/4xxbypass | 0 | 0| 
| 20230204T00:04:46Z | Null | https://github.com/joeengo/exploiting | 8 | 12| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T23:05:01Z | A shell script that mimics sudo and sends you back the password | https://github.com/nisay759/sudo-backdoor | 19 | 7| 
| 20230203T20:27:04Z | Jason-Backdoor | https://github.com/J4s0n1/Jadoor0 | 0 | 0| 
| 20230203T20:25:14Z | Ferramenta que Mescla Backdoor Metasploit em Apps Android | https://github.com/Cyber-Root0/JoinePayload | 3 | 2| 
| 20230203T19:03:57Z | Null | https://github.com/sanlimustafa/BackDoor_V.2.0 | 0 | 0| 
| 20230203T04:28:58Z | [ICLR2023] Distilling Cognitive Backdoor Patterns within an Image | https://github.com/HanxunH/CognitiveDistillation | 6 | 0| 
| 20230202T23:04:26Z | Null | https://github.com/rama1277/shell-backdoor-rama | 0 | 0| 
| 20230202T18:05:33Z | FLIP: A Provable Defense Framework for Backdoor Mitigation in Federated Learning (ICLR 2023) | https://github.com/KaiyuanZh/FLIP | 2 | 0| 
| 20230202T17:54:14Z | client-server-nat | https://github.com/LIBERTY-D/backdoor | 0 | 0| 
| 20230202T13:36:49Z | A Python based Backdoor for Windows | https://github.com/BeastCodZ/Backdoor | 0 | 0| 
| 20230202T09:11:06Z | /root/.ssh/authorized_keys evil file watchdog with ebpf tracepoint hook. | https://github.com/Esonhugh/sshd_backdoor | 233 | 24| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T17:05:07Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2148 | 604| 
| 20230203T13:05:16Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 619 | 111| 
| 20230203T04:02:58Z | Quiver-Based Symbolic Execution | https://github.com/LostBitset/quiver_se | 1 | 0| 
| 20230202T19:56:19Z | Null | https://github.com/data-storage-lab/Symbolic-Execution | 1 | 0| 
| 20230202T06:37:05Z | A C# analyzer which performs symbolic execution on users% code | https://github.com/twoltjer/SymbolicExecutionAnalyzer | 1 | 0| 
| 20230201T13:08:21Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 293 | 73| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T10:28:34Z | A curated list of Meachine learning Security & Privacy papers published in security top-4 conferences (IEEE S&P, ACM CCS, USENIX Security and NDSS). | https://github.com/gnipping/Awesome-ML-SP-Papers | 27 | 2| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230204T01:16:53Z | Fast web fuzzer written in Go | https://github.com/ffuf/ffuf | 8565 | 964| 
| 20230204T00:59:30Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8325 | 1813| 
| 20230204T00:22:43Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 1257 | 168| 
| 20230204T00:11:53Z | Ethereum smart contract fuzzer | https://github.com/crytic/echidna | 1912 | 245| 
| 20230203T22:41:07Z | Null | https://github.com/GaetanThomas42/fuzzy-potato | 0 | 0| 
| 20230203T21:54:09Z | Website for the Furry social platform | https://github.com/coding-bunny/fuzznet | 0 | 0| 
| 20230203T21:44:27Z | Fuzzy C-Means & SLIC algorithms are used in this exercise | https://github.com/HokageHimanshu/Computer-Vision-Fuzzy-C-Means-SLIC | 0 | 0| 
| 20230203T13:40:48Z | Samochód sterowany logiką rozmytą  | https://github.com/MarcinZabielski/fuzzyCar | 0 | 0| 
| 20230203T12:54:08Z | Null | https://github.com/rithwiksivadasan/Fuzzymatching-strings | 0 | 0| 
| 20230203T12:45:07Z | uriel_fernade | https://github.com/Ulegom17/fuzzy-adventure | 0 | 0| 



# 日更新程序
