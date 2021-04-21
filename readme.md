# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210421 | CVE-2020-28973：ABUS Secvest 无线报警系统的未鉴权漏洞。 | https://eye.security/en/blog/breaking-abus-secvest-internet-connected-alarm-systems-cve-2020-28973| 
| 20210421 | HabitsRAT：Go 语言开发的 Windows Server 和 Linux 的后门软件。 | https://www.intezer.com/blog/malware-analysis/habitsrat-used-to-target-linux-and-windows-servers/| 
| 20210421 | CVE-2021-30481：利用 Steamworks API 和 Source Engine，通过 Steam 邀请实现 RCE。 | https://secret.club/2021/04/20/source-engine-rce-invite.html| 
| 20210421 | CocoaPods Trunk 存在远程命令执行漏洞。 | https://justi.cz/security/2021/04/20/cocoapods-rce.html| 
| 20210421 | Bypassing memory safety mechanisms through speculative control flow hijacks | https://arxiv.org/pdf/2003.05503.pdf| 
| 20210421 | 分析 Chromium issue 1196683 和 1195777，两个有关 v8 引擎的漏洞修复的 issue。 | https://iamelli0t.github.io/2021/04/20/Chromium-Issue-1196683-1195777.html| 
| 20210421 | 通过未公开的 API 挂起和恢复进程和线程绕过 EDR Hook 。 | https://windows-internals.com/thread-and-process-state-change/| 
| 20210421 | ELF 二进制文件的学习参考指南。 | https://tmpout.sh/1/| 
| 20210421 | 探讨 CVE-2020-9900（本地提权） 和 CVE-2021-1786（任意文件删除）符号链接攻击的漏洞。 | https://theevilbit.github.io/posts/macos_crashreporter/| 
| 20210421 | Tenet：IDA Pro 的插件，用于清晰的展示和探索被分析的程序执行状态。 | https://sec.today/pulses/92a5c3de-6fd4-40b8-986c-854a2cf2e2e7/| 
| 20210421 | CVE-2021-26413：Windows Installer 签名欺骗漏洞 | https://sec.today/pulses/63e8a3c7-ab25-463b-a757-8c76f20b299d/| 
| 20210421 | 研究发现 APT 攻击者通过 0day 绕过 Pulse Secure VPN 身份验证。 | https://sec.today/pulses/b6165b1d-3413-401f-9845-86d7dfb28828/| 
| 20210421 | Perfusion：Windows 7, Windows Server 2008R2, Windows 8, and Windows Server 2012 上的本地提权工具。 | https://sec.today/pulses/25405811-53fe-4074-a6b1-9c8d1d84e098/| 
| 20210421 | Tenet：IDA Pro 的插件，用于清晰的展示和探索被分析的程序执行状态。 | https://blog.ret2.io/2021/04/20/tenet-trace-explorer/| 
| 20210421 | CVE-2021-26413：Windows Installer 签名欺骗漏洞 | https://sec.okta.com/articles/2021/04/uncovering-and-disclosing-signature-spoofing-vulnerability-windows/| 
| 20210421 | 研究发现 APT 攻击者通过 0day 绕过 Pulse Secure VPN 身份验证。 | https://www.fireeye.com/blog/threat-research/2021/04/suspected-apt-actors-leverage-bypass-techniques-pulse-secure-zero-day.html| 
| 20210421 | Perfusion：Windows 7, Windows Server 2008R2, Windows 8, and Windows Server 2012 上的本地提权工具。 | https://github.com/itm4n/Perfusion/blob/master/RegistryPatch.ps1| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210421 | 如何制作一个微型内核 | https://www.sec-in.com/article/1028| 
| 20210421 | Analysis of a use-after-free Vulnerability in Adobe Acroba... | https://blog.exodusintel.com/2021/04/20/analysis-of-a-use-after-free-vulnerability-in-adobe-acrobat-reader-dc/| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210421T11:49:38Z | CVE-2021-3493 | Ubuntu OverlayFS Local Privesc | https://github.com/briskets/CVE-2021-3493 | The overlayfs implementation in the linux kernel did not properly validate with respect to user namespaces the setting of file capabilities on files in an underlying file system. Due to the combination of unprivileged user namespaces along with a patch carried in the Ubuntu kernel to allow unprivileged overlay mounts, an attacker could use this to gain elevated privileges.| 
| 20210421T11:48:59Z | CVE-2021-28480 | PoC for exploiting RCE in Exchange CVEs: CVE-2021-28480, CVE-2021-28481, CVE-2021-28482 and CVE-2021-28483.  Achieves Domain Admin on Exchange Servers running Windows Server 2003 up to Windows Server 2019. | https://github.com/ZephrFish/ExchangeRCE-CVE-2021-28480 | Microsoft Exchange Server Remote Code Execution Vulnerability This CVE ID is unique from CVE-2021-28481, CVE-2021-28482, CVE-2021-28483.| 
| 20210421T11:18:33Z | CVE-2021-22893 | Proof-of-Concept (PoC) script to exploit Pulse Secure CVE-2021-22893.  | https://github.com/ZephrFish/CVE-2021-22893 | 未查询到CVE信息| 
| 20210421T10:59:57Z | CVE-2021-22192 | CVE-2021-22192 靶场： 未授权用户 RCE 漏洞 | https://github.com/lyy289065406/CVE-2021-22192 | An issue has been discovered in GitLab CE/EE affecting all versions starting from 13.2 allowing unauthorized authenticated users to execute arbitrary code on the server.| 
| 20210421T10:58:48Z | CVE-2021-30481 | https://nvd.nist.gov/vuln/detail/CVE-2021-30481 | https://github.com/floesen/CVE-2021-30481 | Valve Steam through 2021-04-10, when a Source engine game is installed, allows remote authenticated users to execute arbitrary code because of a buffer overflow that occurs for a Steam invite after one click.| 
| 20210421T10:58:41Z | CVE-2021-22893 | Pulse Connect Secure RCE Vulnerability (CVE-2021-22893) | https://github.com/Mad-robot/CVE-2021-22893 | 未查询到CVE信息| 
| 20210421T09:31:14Z | CVE-2020-14364 | Null | https://github.com/gejian-iscas/CVE-2020-14364 | An out-of-bounds read/write access flaw was found in the USB emulator of the QEMU in versions before 5.2.0. This issue occurs while processing USB packets from a guest when USBDevice %setup_len% exceeds its %data_buf[4096]% in the do_token_in, do_token_out routines. This flaw allows a guest user to crash the QEMU process, resulting in a denial of service, or the potential execution of arbitrary code with the privileges of the QEMU process on the host.| 
| 20210421T08:32:02Z | CVE-2021-3156 | CVE-2021-3156: Sudo heap overflow exploit for Debain 10 | https://github.com/0xdevil/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210421T07:18:09Z | CVE-2021-26295 | Apache OFBiz rmi反序列化EXP(CVE-2021-26295) | https://github.com/S0por/CVE-2021-26295-Apache-OFBiz-EXP | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210421T08:37:43Z | Null | https://github.com/Jython1415/penguin-Klee | 1 | 0| 
| 20210421T06:11:47Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 7 | 1| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210421T07:37:39Z | Null | https://github.com/yuvalkirstain/s2e-coref | 3 | 2| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210421T12:02:30Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 22 | 9| 
| 20210421T12:01:02Z | Null | https://github.com/Nyhrox1337/Exploit-Remote-File-Executor-Discord | 0 | 0| 
| 20210421T11:55:01Z | a tool for creating exploited media files for discord | https://github.com/Schmenn/discord-exploits | 99 | 13| 
| 20210421T11:48:59Z | PoC for exploiting RCE in Exchange CVEs: CVE-2021-28480, CVE-2021-28481, CVE-2021-28482 and CVE-2021-28483.  Achieves Domain Admin on Exchange Servers running Windows Server 2003 up to Windows Server 2019. | https://github.com/ZephrFish/ExchangeRCE-CVE-2021-28480 | 2 | 0| 
| 20210421T11:29:46Z | Linux/Windows Exploits | https://github.com/tedelm/Exploits | 0 | 0| 
| 20210421T11:27:46Z | SECMON is a web-based tool for the automation of infosec watching and vulnerability management with a web interface. | https://github.com/Guezone/SECMON | 0 | 0| 
| 20210421T11:23:47Z | A python script file to statically and dynamically investigate and analyse binary files for buffer overflow exploits. | https://github.com/BroadbentT/BINARY-MASTER | 5 | 1| 
| 20210421T11:18:33Z | Proof-of-Concept (PoC) script to exploit Pulse Secure CVE-2021-22893.  | https://github.com/ZephrFish/CVE-2021-22893 | 0 | 0| 
| 20210421T11:15:01Z | Example C Program for Binary Exploitation Workshops | https://github.com/kevinalmansa/vulnerable-c-program | 1 | 0| 
| 20210421T11:00:35Z | jvav shiro exploit | https://github.com/M4da0/ShiroExploit | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210421T11:28:20Z | Tiny backdoor, built for survival | https://github.com/Raffy27/Hydra | 0 | 0| 
| 20210421T11:27:02Z | A Backdoor made from my malware development notes. | https://github.com/0x1CA3/Cbackdoor | 0 | 0| 
| 20210421T11:18:11Z | LKM rootkit for Linux Kernels 2.6.x/3.x/4.x/5.x (x86/x86_64 and ARM64) | https://github.com/m0nad/Diamorphine | 756 | 280| 
| 20210421T09:48:11Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/ghost | 1044 | 505| 
| 20210421T07:37:32Z | Null | https://github.com/subhomoy-roy-choudhury/BackDoor_Script | 0 | 0| 
| 20210421T03:34:13Z | Simple Python Backdoor | https://github.com/zNairy/Sonaris | 5 | 0| 
| 20210421T03:07:47Z | Null | https://github.com/piyushsharma220699/Backdoor-in-Cyber-Security | 0 | 0| 
| 20210421T02:30:14Z | Python 3 IRC Bot / Botnet | https://github.com/trackmastersteve/HackServ | 18 | 16| 
| 20210421T01:10:13Z | A demo and explanation of how backdoor poisoning in the form of a Trojan work in neural networks | https://github.com/adit-bala/Introduction-to-Trojans-in-AI | 0 | 0| 
| 20210421T00:09:49Z | free and open source nonobf server backdoor plugin | https://github.com/AcaiBerii/Bakdooro | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210421T01:29:01Z | Group 4C Fuzzy Logic Medieval Chess AI Senior Project | https://github.com/arizonagranger/SeniorProjectFuzzyLogicChess | 1 | 1| 
| 20210421T01:14:36Z | A regression greybox fuzzer aflchurn | https://github.com/aflchurn/aflchurn | 21 | 1| 
| 20210421T01:04:01Z | Null | https://github.com/igorsodre/fuzzy-trader | 0 | 0| 
| 20210421T00:51:18Z | Take the current implementation and turning a microservice architecture | https://github.com/ccesarrod/FuzzyMicrosrvices | 0 | 0| 
| 20210421T00:39:12Z | A test framework for running integration and regression testing on Fuzzy Merging in CluedIn | https://github.com/CluedIn-io/Fuzzy-Merging-TestBed | 0 | 0| 
| 20210421T00:28:00Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6210 | 1253| 
| 20210421T00:21:46Z | This repository is for testing a number of open source applications for vulnerabilities using multiple fuzzers. | https://github.com/bartholomewHarris/fuzzingNode.jsApplications | 1 | 1| 
| 20210421T00:05:32Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 3 | 3| 
| 20210421T00:02:49Z | Null | https://github.com/josh-mountain/fuzzy-potato | 0 | 0| 



# 日更新程序
