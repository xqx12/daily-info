# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210419 | xscreensaver：raw socket leak | https://bugs.chromium.org/p/project-zero/issues/detail?id=2174| 
| 20210419 | CVE-2021-20291：CRI-O 和 Podman 的DOS 漏洞成因和缓解方法。 | https://sysdig.com/blog/cve-2021-20291-cri-o-podman/| 
| 20210419 | CVE-2021-28316：Microsoft Windows WLAN AutoConfig Service 安全功能绕过漏洞。由于入域的工作站在锁屏页面中可以修改连接 Wi-Fi，攻击者可以滥用此功能将工作站接入非法的 Wi-Fi 中进行身份验证，以捕捉 MSCHAPv2。 | https://shenaniganslabs.io/2021/04/13/Airstrike.html| 
| 20210419 | CVE-2021-23133：Linux內核中 sctp 套接字的竞争条件。 | https://www.openwall.com/lists/oss-security/2021/04/18/2| 
| 20210419 | 没有运行在沙箱中的 Chromium 和 Chrome 面临的安全风险。 | https://github.com/sickcodes/no-sandbox| 
| 20210419 | CVE-2021-0256：Juniper Junos OS 本地提权漏洞。Junos OS 专用的硬件设备上的网络操作系统。 | https://starlabs.sg/advisories/21-0256/| 
| 20210419 | 任意删除 Facebook 上直播视频的漏洞。 | https://infosecwriteups.com/poc-remove-any-facebooks-live-video-14-000-bounty-70c8135b7b4c?gi=5367bc83f14e| 
| 20210419 | Elie Bursztein：分析账户如何被盗用，深入概述 Google 是如何保护用户免受此类攻击。 | https://elie.net/talk/account-protections-a-google-perspective/| 
| 20210419 | Todd Austin 解释了他们团队的设计的处理器是如何挑战 DARPAs hardware hacking。 | https://spectrum.ieee.org/tech-talk/semiconductors/processors/morpheus-turns-a-cpu-into-a-rubiks-cube-to-defeat-hackers| 
| 20210419 | 通过逆向 tcpic.sys 分析 CVE-2021-24086 。 | https://sec.today/pulses/e609fefa-1407-4672-ab1a-f182a931592d/| 
| 20210419 | 通过逆向 tcpic.sys 分析 CVE-2021-24086 。 | https://doar-e.github.io/blog/2021/04/15/reverse-engineering-tcpipsys-mechanics-of-a-packet-of-the-death-cve-2021-24086/| 
| 20210419 | 多平台的敏感信息监测工具-GShark | https://paper.seebug.org/1560/| 
| 20210419 | Linux内核新CVE报告。 | https://linuxkernelcves.com/| 
| 20210418 | Go 语言的雪花算法实现 | https://godruoyi.com/posts/golang-snowflake| 
| 20210418 | Cobalt Strike 利用 Chrome 0day 上线 | https://mp.weixin.qq.com/s/LOpAu8vs8ob85W3sCmXMew| 
| 20210416 | Chromium V8 增加了额外的检查以解决近期关于 Chromium 浏览器系列上的远程 RCE 漏洞。 | https://chromium.googlesource.com/v8/v8/+/d4aafa4022b718596b3deadcc3cdcb9209896154| 
| 20210416 | Chromium V8 JavaScript引擎远程代码执行漏洞分析讨论。 | http://noahblog.360.cn/chromium_v8_remote_code_execution_vulnerability_analysis/| 
| 20210416 | 通过网页中的 6 个特征字段检测钓鱼站点。 | https://bradleyjkemp.dev/post/6-ways-to-detect-phishing-sites-using-high-entropy-strings/| 
| 20210416 | Exploiting System Mechanic Driver | https://voidsec.com/exploiting-system-mechanic-driver/| 
| 20210416 | JavaScript prototype 污染攻击的寻找和利用。 | https://infosecwriteups.com/javascript-prototype-pollution-practice-of-finding-and-exploitation-f97284333b2?gi=9db44f26abcf| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210419 | 蚁剑流量改造学习 | https://www.sec-in.com/article/1025| 
| 20210419 | 恶意软件在沙盒中应该执行多长时间？ | https://mp.weixin.qq.com/s/z1MS0Df89NhSeAU9IxF5nw| 
| 20210418 | 安全招聘汇总 , 第十三期 | https://mp.weixin.qq.com/s/I6F0GP_lPcdc2Zh8hc_T4w| 
| 20210418 | 三款开源HIDS功能对比评估 | https://mp.weixin.qq.com/s/6zLrq-jfkaQWBdeNO2RaYQ| 
| 20210418 | 什么是安全架构《二》 | https://iami.xyz/Security-Architecture-Review-II/| 
| 20210418 | 什么是安全架构 | https://iami.xyz/Security-Architecture-Review/| 
| 20210418 | 什么是安全架构《三》 | https://iami.xyz/Security-Architecture-Review-III/| 
| 20210418 | 反制Webdriver - 从Bot到RCE进发 | https://lorexxar.cn/2021/04/16/chrome-webdriver-attack/| 
| 20210416 | 哥斯拉插件开发指南——初入茅庐 | https://mp.weixin.qq.com/s/Q2eFRQQCEVf4bf_jNsWX2g| 
| 20210416 | Spring Boot中关于%2e的Trick | http://rui0.cn/archives/1643| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210420T00:55:50Z | CVE-2021-3493 | Ubuntu OverlayFS Local Privesc | https://github.com/briskets/CVE-2021-3493 | The overlayfs implementation in the linux kernel did not properly validate with respect to user namespaces the setting of file capabilities on files in an underlying file system. Due to the combination of unprivileged user namespaces along with a patch carried in the Ubuntu kernel to allow unprivileged overlay mounts, an attacker could use this to gain elevated privileges.| 
| 20210419T21:09:30Z | CVE-2020-1350 | HoneyPoC: Proof-of-Concept (PoC) script to exploit SIGRed (CVE-2020-1350). Achieves Domain Admin on Domain Controllers running Windows Server 2000 up to Windows Server 2019. | https://github.com/ZephrFish/CVE-2020-1350 | A remote code execution vulnerability exists in Windows Domain Name System servers when they fail to properly handle requests, aka %Windows DNS Server Remote Code Execution Vulnerability%.| 
| 20210419T18:08:13Z | CVE-2021-30481 | https://nvd.nist.gov/vuln/detail/CVE-2021-30481 | https://github.com/floesen/CVE-2021-30481 | Valve Steam through 2021-04-10, when a Source engine game is installed, allows remote authenticated users to execute arbitrary code because of a buffer overflow that occurs for a Steam invite after one click.| 
| 20210419T12:48:13Z | cve-2021-6666 | 就是玩，哎，让你监测TM的。 | https://github.com/r90tpass/cve-2021-6666 | 未查询到CVE信息| 
| 20210419T11:56:34Z | 未知编号 | Null | https://github.com/r90tpass/CVE_2021-6123111 | 未查询到CVE信息| 
| 20210419T10:14:21Z | CVE-2021-1 | 1 | https://github.com/hackzuoji/CVE-2021-1 | 未查询到CVE信息| 
| 20210419T06:22:40Z | CVE-2021-24086 | Proof of concept for CVE-2021-24086, a NULL dereference in tcpip.sys triggered remotely. | https://github.com/0vercl0k/CVE-2021-24086 | Windows TCP/IP Denial of Service Vulnerability| 
| 20210418T14:52:17Z | CVE-2020-24033 | Null | https://github.com/M0NsTeRRR/CVE-2020-24033 | An issue was discovered in fs.com S3900 24T4S 1.7.0 and earlier. The form does not have an authentication or token authentication mechanism that allows remote attackers to forge requests on behalf of a site administrator to change all settings including deleting users, creating new users with escalated privileges.| 
| 20210418T12:36:36Z | CVE-2020- | Cibersecurity paython3 tool that search CVE by different patterns | https://github.com/f0ns1/CVE-2020-python_tool | 未查询到CVE信息| 
| 20210418T11:22:10Z | CVE-2020-1472 | CVE-2020-1472复现流程 | https://github.com/NAXG/CVE-2020-1472 | An elevation of privilege vulnerability exists when an attacker establishes a vulnerable Netlogon secure channel connection to a domain controller, using the Netlogon Remote Protocol (MS-NRPC), aka %Netlogon Elevation of Privilege Vulnerability%.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210419T05:50:54Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1674 | 489| 
| 20210418T21:37:03Z | Spring 2021 Geography 817 work folder  | https://github.com/klee12/klee12.github.io | 0 | 0| 
| 20210418T18:49:32Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 6 | 1| 
| 20210418T18:28:01Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 14 | 43| 
| 20210418T06:36:11Z | KLEE demonstration on the program second_largest | https://github.com/basu-abhinav/second_largest | 0 | 0| 
| 20210418T03:24:29Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210417T18:14:06Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 125 | 12| 
| 20210416T10:15:55Z | test | https://github.com/xenoney/kleee | 0 | 0| 
| 20210414T16:58:57Z | Null | https://github.com/dorawei/klee-tc | 0 | 0| 
| 20210413T14:28:13Z | A very fun and useful bot containing many features.  | https://github.com/quantix-dev/Kleebot | 1 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210416T10:04:27Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 115 | 26| 
| 20210411T10:32:25Z | Null | https://github.com/Lyes7/TDM_S2E1 | 0 | 0| 
| 20210408T14:29:39Z | Null | https://github.com/yuvalkirstain/s2e-coref | 3 | 2| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210420T00:50:50Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 15 | 9| 
| 20210420T00:49:14Z | Null | https://github.com/MaherAzzouzi/BrowserExploitation | 0 | 0| 
| 20210420T00:44:44Z | The AWS exploitation framework, designed for testing the security of Amazon Web Services environments. | https://github.com/RhinoSecurityLabs/pacu | 2001 | 360| 
| 20210420T00:43:52Z | Bukkit/BungeeCord plugin that aims on fixing Exploits in your Minecraft network. [Requires HamsterAPI to work] | https://github.com/2lstudios-mc/ExploitFixer | 82 | 23| 
| 20210420T00:21:39Z | Various ASM, C and C++ tools, shellcodes and exploit experiments. | https://github.com/forrest-orr/ExploitDev | 6 | 0| 
| 20210420T00:02:28Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 21 | 8| 
| 20210419T23:47:08Z | PS-Phwoar! Alpha Version Exploit Host Menu for 5.05 FW with GoldHEN v1.1 Coded by SiSTRo / Port by Joonie86 | https://github.com/xforce505/xforce505.github.io | 0 | 0| 
| 20210419T23:20:34Z | Exploit allowing to load arbitrary code on the PSX using only a memory card (no game needed) | https://github.com/brad-lin/FreePSXBoot | 164 | 12| 
| 20210419T23:11:32Z | Crea tu Exploit apk de forma rapida para hackeos   | https://github.com/FastmoreCrak/ZicelTT | 0 | 0| 
| 20210419T22:43:43Z | Merlin is a cross-platform post-exploitation HTTP/2 Command & Control  server and agent written in golang. | https://github.com/Ne0nd0g/merlin | 3151 | 495| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210419T23:32:27Z | PCI Express DIY hacking toolkit for Xilinx SP605 | https://github.com/Cr4sh/s6_pcie_microblaze | 319 | 79| 
| 20210419T23:02:17Z | free and open source nonobf server backdoor plugin | https://github.com/AcaiBerii/Bakdooro | 0 | 0| 
| 20210419T22:08:11Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 64 | 11| 
| 20210419T21:23:29Z | Null | https://github.com/piyushsharma220699/Backdoor-in-Cyber-Security | 0 | 0| 
| 20210419T19:11:52Z | Python 3 IRC Bot / Botnet | https://github.com/trackmastersteve/HackServ | 18 | 16| 
| 20210419T18:09:38Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/ghost | 1042 | 504| 
| 20210419T17:09:04Z | Null | https://github.com/Wrench56/Backdoor | 1 | 0| 
| 20210419T13:48:04Z | A sample app to demonstrate how to create Xamarin UITests using the Page Object architecture, Backdoor Methods and App Links (aka Deep Linking) | https://github.com/brminnick/UITestSampleApp | 35 | 26| 
| 20210419T13:36:11Z | Rxploit | https://github.com/NANI1734/Rxploit | 2 | 0| 
| 20210419T13:01:55Z | Null | https://github.com/ChGunay/Backdoor-ArkaKapi | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210420T00:06:58Z | Fuzzy matching for Neovim | https://github.com/amirrezaask/fuzzy.nvim | 35 | 1| 
| 20210419T22:58:31Z | A unit test-like interface for fuzzing and symbolic execution | https://github.com/trailofbits/deepstate | 608 | 62| 
| 20210419T22:53:08Z | Fuzzer to generate decimal tests | https://github.com/paupino/decfuzzgen | 0 | 0| 
| 20210419T22:51:10Z | Null | https://github.com/DanoKalhor/fuzzy | 0 | 0| 
| 20210419T22:25:10Z | Scalable fuzzing infrastructure. | https://github.com/google/clusterfuzz | 4488 | 432| 
| 20210419T22:08:10Z | interactive `git` with the help of `fzf` | https://github.com/bigH/git-fuzzy | 1749 | 34| 
| 20210419T21:34:44Z | Null | https://github.com/joseffaghihi/Causal-probabilistic-fuzzy-logic | 0 | 0| 
| 20210419T21:28:12Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6208 | 1251| 
| 20210419T21:22:44Z | A site that allows you to reverse image search millions of furry images in under a second | https://github.com/Syfaro/fuzzysearch | 7 | 1| 
| 20210419T21:22:01Z | Manage & generate prefs.js files | https://github.com/MozillaSecurity/prefpicker | 5 | 2| 



# 日更新程序
