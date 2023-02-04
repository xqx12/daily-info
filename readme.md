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


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230203T22:05:47Z | CVE-2020-10963 | FrozenNode Laravel-Administrator through 5.0.12 allows unrestricted file upload (and consequently Remote Code Execution) via admin/tips_image/image/file_upload image upload with PHP content within a GIF image that has the .php extension. NOTE: this product is discontinued. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-10963 | | 
| 20230203T21:58:58Z | cve-2022-44268 | Payload generator and extractor for CVE-2022-44268 written in Python. | https://github.com/agathanon/cve-2022-44268 | | 
| 20230203T19:54:03Z | CVE-2020-26664 | A vulnerability in EbmlTypeDispatcher::send in VideoLAN VLC media player 3.0.11 allows attackers to trigger a heap-based buffer overflow via a crafted .mkv file. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-26664 | | 
| 20230203T19:53:56Z | CVE-2020-36403 | HTSlib through 1.10.2 allows out-of-bounds write access in vcf_parse_format (called from vcf_parse and vcf_read). CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-36403 | | 
| 20230203T19:53:46Z | CVE-2020-13300 | GitLab CE/EE version 13.3 prior to 13.3.4 was vulnerable to an OAuth authorization scope change without user consent in the middle of the authorization flow. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-13300 | | 
| 20230203T19:53:43Z | CVE-2020-26732 | SKYWORTH GN542VF Boa version 0.94.13 does not set the Secure flag for the session cookie in an HTTPS session, which makes it easier for remote attackers to capture this cookie by intercepting its transmission within an HTTP session. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-26732 | | 
| 20230203T19:53:39Z | CVE-2021-28116 | Squid through 4.14 and 5.x through 5.0.5, in some configurations, allows information disclosure because of an out-of-bounds read in WCCP protocol data. This can be leveraged as part of a chain for remote code execution as nobody. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-28116 | | 
| 20230203T17:48:29Z | CVE-2023-24138 | TOTOLINK CA300-PoE V6.2c.884 was discovered to contain a command injection vulnerability via the host_time parameter in the NTPSyncWithHost function. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-24138 | | 
| 20230203T17:42:56Z | CVE-2022-34138 | Insecure direct object references (IDOR) in the web server of Biltema IP and Baby Camera Software v124 allows attackers to access sensitive information. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-34138 | | 
| 20230203T17:42:53Z | CVE-2020-0305 | In cdev_get of char_dev.c, there is a possible use-after-free due to a race condition. This could lead to local escalation of privilege with System execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-10Android ID: A-153467744 CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-0305 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T17:05:07Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2148 | 604| 
| 20230203T14:15:33Z | Collection of Kicad 6.0 symbols, footprints and 3D models useful in keyboard creation | https://github.com/crides/kleeb | 74 | 6| 
| 20230203T01:31:43Z | Null | https://github.com/LuiKlee/LuiKlee.github.io | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T23:40:41Z | Roblox Exploit | https://github.com/ConsumingChef/ConsumerHub | 0 | 0| 
| 20230203T23:20:00Z | my pwnable.kr exploits | https://github.com/DanielSegal1/pwnable | 0 | 0| 
| 20230203T22:57:31Z | by CipherSniff | https://github.com/CipherSniff/NBT_Exploits | 1 | 0| 
| 20230203T22:52:47Z | WIP | https://github.com/wang-fr/i-Ready-Exploit-Collection | 0 | 0| 
| 20230203T22:05:59Z | IBM Cognos Controller 10.2.0, 10.2.1, 10.3.0, 10.3.1, and 10.4.0 could allow a remote attacker to obtain sensitive information, caused by a flaw in the HTTP OPTIONS method, aka Optionsbleed. By sending an OPTIONS HTTP request, a remote attacker could exploit this vulnerability to read secret data from process memory an CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2019-4173 | 0 | 0| 
| 20230203T22:05:51Z | IBM StoredIQ 7.6 could allow a remote attacker to conduct phishing attacks, using an open redirect attack. By persuading a victim to visit a specially-crafted Web site, a remote attacker could exploit this vulnerability to spoof the URL displayed to redirect a user to a malicious Web site that would appear to be truste CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2019-4166 | 0 | 0| 
| 20230203T12:22:54Z | Этот скрипт является тренировочным. Он предназначен для извлечения данных с сайта rapid7.com. В данном проекте используются две основные библиотеки bs4 и selenium. Скрипт запускался на операционной системе Windows. | https://github.com/mishaniahomi/scraping_vulnerability_and_exploit | 0 | 0| 
| 20230203T12:07:52Z | OpenSSH server (sshd) 9.1 introduced a double-free vulnerability during options.kex_algorithms handling. This is fixed in OpenSSH 9.2. The double free can be triggered by an unauthenticated attacker in the default configuration; however, the vulnerability discoverer reports that %exploiting this vulnerability will not  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-25136 | 0 | 0| 
| 20230203T11:56:47Z | Null | https://github.com/HmiBlackHat/DominExploit | 0 | 0| 
| 20230203T11:46:41Z | An information disclosure vulnerability that could be exploited to read arbitrary files from a server when parsing an image in Image Magic. | https://github.com/Ashifcoder/CVE-2022-44268-automated-poc | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T23:05:01Z | A shell script that mimics sudo and sends you back the password | https://github.com/nisay759/sudo-backdoor | 19 | 7| 
| 20230203T20:27:04Z | Jason-Backdoor | https://github.com/J4s0n1/Jadoor0 | 0 | 0| 
| 20230203T20:25:14Z | Ferramenta que Mescla Backdoor Metasploit em Apps Android | https://github.com/Cyber-Root0/JoinePayload | 3 | 2| 
| 20230203T19:03:57Z | Null | https://github.com/sanlimustafa/BackDoor_V.2.0 | 0 | 0| 
| 20230203T04:28:58Z | [ICLR2023] Distilling Cognitive Backdoor Patterns within an Image | https://github.com/HanxunH/CognitiveDistillation | 6 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T17:05:07Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2148 | 604| 
| 20230203T13:05:16Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 619 | 111| 
| 20230203T04:02:58Z | Quiver-Based Symbolic Execution | https://github.com/LostBitset/quiver_se | 1 | 0| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T10:28:34Z | A curated list of Meachine learning Security & Privacy papers published in security top-4 conferences (IEEE S&P, ACM CCS, USENIX Security and NDSS). | https://github.com/gnipping/Awesome-ML-SP-Papers | 27 | 2| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T22:41:07Z | Null | https://github.com/GaetanThomas42/fuzzy-potato | 0 | 0| 
| 20230203T21:54:09Z | Website for the Furry social platform | https://github.com/coding-bunny/fuzznet | 0 | 0| 
| 20230203T21:44:27Z | Fuzzy C-Means & SLIC algorithms are used in this exercise | https://github.com/HokageHimanshu/Computer-Vision-Fuzzy-C-Means-SLIC | 0 | 0| 
| 20230203T13:40:48Z | Samochód sterowany logiką rozmytą  | https://github.com/MarcinZabielski/fuzzyCar | 0 | 0| 
| 20230203T12:54:08Z | Null | https://github.com/rithwiksivadasan/Fuzzymatching-strings | 0 | 0| 
| 20230203T12:45:07Z | uriel_fernade | https://github.com/Ulegom17/fuzzy-adventure | 0 | 0| 
| 20230203T11:20:18Z | cli tool for searching cloudtrail events using fuzzy search | https://github.com/paololazzari/cloudtrail-event-fuzzy-viewer | 0 | 0| 
| 20230203T10:41:25Z | Null | https://github.com/yayomu/fuzzy-octo-dollop | 0 | 0| 
| 20230203T02:36:05Z | REcollapse is a helper tool for black-box regex fuzzing to bypass validations and discover normalizations in web applications | https://github.com/0xacb/recollapse | 385 | 32| 
| 20230203T02:23:54Z | Fuzz Introspector -- introspect, extend and optimise fuzzers | https://github.com/ossf/fuzz-introspector | 237 | 34| 



# 日更新程序
