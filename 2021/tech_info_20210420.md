# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210420 | Codecov Bash Uploader 工具被黑客修改，可能将用户的 CI（持续集成）的密钥、代码等机密信息发送到了第三方服务器上。 | https://about.codecov.io/security-update/| 
| 20210420 | Pass-the-Hash (PTH): a PoC code to use Pass-the-Hash for authentication on a local Named Pipe user Impersonation. | https://s3cur3th1ssh1t.github.io/Named-Pipe-PTH/| 
| 20210420 | 在 Chrome 沙箱中利用 1Day 和 渲染器重定向实现信息泄漏。 | https://ptr-yudai.hatenablog.com/entry/2021/04/19/140802| 
| 20210420 | CVE-2021-3493：Ubuntu 下利用 overlayfs 提权。 | https://ssd-disclosure.com/ssd-advisory-overlayfs-pe/| 
| 20210420 | 介绍一些例如 GA 等自定义 fuzzer 的功能和设计。 | https://github.com/hardenedlinux/harbian-qa/blob/master/survey.md| 
| 20210420 | 通过 WebDriver REST API 的 RCE。 | https://lorexxar.cn/2021/04/16/chrome-webdriver-attack/| 
| 20210420 | Tenda D151 和 D301 无需身份认证下载配置信息及登录的 POC。 | https://github.com/BenChaliah/Tenda_D151_D301_POC| 
| 20210420 | Lazarus APT 组织将恶意代码写入 BMP 图像的攻击方法。 | https://blog.malwarebytes.com/malwarebytes-news/2021/04/lazarus-apt-conceals-malicious-code-within-bmp-file-to-drop-its-rat/| 
| 20210420 | 逆向分析 Guloader 的工作流程和其反逆向的机制。 | https://elis531989.medium.com/dancing-with-shellcodes-cracking-the-latest-version-of-guloader-75083fb15cb4| 
| 20210420 | PlaidCTF 2021 The-False-Promise Chrome 的 Writeup。 | https://sec.today/pulses/f1054dfc-bff6-48ee-bc7e-f7fabb48afcc/| 
| 20210420 | PlaidCTF 2021 The-False-Promise Chrome 的 Writeup。 | https://hackmd.io/@aventador/BJkOOyi8u| 
| 20210420 | NAT 原理以及 UDP 穿透实现。 | https://paper.seebug.org/1561/| 
| 20210420 | 解密钴矿攻击流量分析。 | https://isc.sans.edu/diary/rss/27322| 
| 20210420 | Metasploit Windows最全的漏洞利用列表。 | https://www.infosecmatter.com/list-of-metasploit-windows-exploits-detailed-spreadsheet/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210420 | MyBatis和MyBatis可能导致的sql注入 | https://www.sec-in.com/article/1022| 
| 20210420 | 可扩展跨平台网络安全工具套件 CaptfEncoder v2.0.0 | https://mp.weixin.qq.com/s?__biz=MzI0ODU5Mzg0NA==&mid=2247483998&idx=1&sn=baaa69c5576a1e52b7d8aeb9482e1cf3&chksm=e99f2e85dee8a79304a5535dbf6c77e9f9def6b2a7438c73e28792ac5ea3c628a02204d116e6&token=1448493475&lang=zh_CN#rd| 
| 20210420 | Java反序列化 — URLDNS利用链分析 | https://xz.aliyun.com/t/9417| 
| 20210420 | Yii2反序列化RCE 新POP链 | https://xz.aliyun.com/t/9420| 
| 20210420 | 人工智能在网络安全领域的应用现状 | https://dl.ccf.org.cn/institude/institudeDetail?_ack=1&id=5398508341266432| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210420T23:07:23Z | CVE-2020-1350 | HoneyPoC: Proof-of-Concept (PoC) script to exploit SIGRed (CVE-2020-1350). Achieves Domain Admin on Domain Controllers running Windows Server 2000 up to Windows Server 2019. | https://github.com/ZephrFish/CVE-2020-1350 | A remote code execution vulnerability exists in Windows Domain Name System servers when they fail to properly handle requests, aka %Windows DNS Server Remote Code Execution Vulnerability%.| 
| 20210420T19:00:47Z | CVE-2021-22192 | CVE-2021-22192 靶场： 未授权用户 RCE 漏洞 | https://github.com/lyy289065406/CVE-2021-22192 | An issue has been discovered in GitLab CE/EE affecting all versions starting from 13.2 allowing unauthorized authenticated users to execute arbitrary code on the server.| 
| 20210420T04:03:57Z | CVE-2020-14882 | Null | https://github.com/nice0e3/CVE-2020-14882_Exploit_Gui | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210420T03:04:13Z | CVE-2020-14364 | Null | https://github.com/gejian-iscas/CVE-2020-14364 | An out-of-bounds read/write access flaw was found in the USB emulator of the QEMU in versions before 5.2.0. This issue occurs while processing USB packets from a guest when USBDevice %setup_len% exceeds its %data_buf[4096]% in the do_token_in, do_token_out routines. This flaw allows a guest user to crash the QEMU process, resulting in a denial of service, or the potential execution of arbitrary code with the privileges of the QEMU process on the host.| 
| 20210420T02:41:51Z | CVE-2021-26295 | Apache OFBiz rmi反序列化EXP(CVE-2021-26295) | https://github.com/S0por/CVE-2021-26295-Apache-OFBiz-EXP | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210420T22:58:07Z | Spring 2021 Geography 817 work folder  | https://github.com/klee12/klee12.github.io | 0 | 0| 
| 20210420T22:41:29Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1674 | 489| 
| 20210420T08:37:55Z | Null | https://github.com/Jython1415/penguin-Klee | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210420T06:08:42Z | GUI Configuration tool for WIZnet serial to ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool-GUI | 12 | 7| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210420T23:43:13Z | Null | https://github.com/Kro0oz/Wp-exploit-upload-shell | 0 | 0| 
| 20210420T23:22:15Z | Exploit Manager for A/D Challenges | https://github.com/Omnicrist/exploit_manager | 2 | 0| 
| 20210420T23:13:47Z | Null | https://github.com/brerodrigues/exploit_drafts | 0 | 0| 
| 20210420T22:19:49Z | No Sandbox - Applications That Run Chromium and Chrome Without The Sandbox. TL;DR exploits in these browser based applications are already sandboxed escaped: https://no-sandbox.io/ | https://github.com/sickcodes/no-sandbox | 135 | 12| 
| 20210420T21:51:11Z | Exploit Jenkins using Shodan API | https://github.com/streghstreek/shodan-shell | 0 | 0| 
| 20210420T21:43:23Z | Crea tu Exploit apk de forma rapida para hackeos   | https://github.com/FastmoreCrak/ZicelTT | 0 | 0| 
| 20210420T21:35:56Z | A python script file to statically and dynamically investigate and analyse binary files for buffer overflow exploits. | https://github.com/BroadbentT/BINARY-MASTER | 5 | 1| 
| 20210420T21:35:14Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9307 | 1503| 
| 20210420T21:25:24Z | OWASP Benchmark is a test suite designed to verify the speed and accuracy of software vulnerability detection tools. A fully runnable web app written in Java, it supports analysis by Static (SAST), Dynamic (DAST), and Runtime (IAST) tools that support Java. The idea is that since it is fully runnable and all the vulnerabilities are actually exploitable, it’s a fair test for any kind of vulnerability detection tool.  For more details on this project, please see the OWASP Benchmark Project home page. | https://github.com/OWASP/Benchmark | 357 | 292| 
| 20210420T21:14:24Z | PS4 Exploits 5.05-7.55 | https://github.com/Buzbee/Buzbee.github.io | 1 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210420T23:39:50Z | LKM rootkit for Linux Kernels 2.6.x/3.x/4.x/5.x (x86/x86_64 and ARM64) | https://github.com/m0nad/Diamorphine | 755 | 280| 
| 20210420T20:57:21Z | Simple Python Backdoor | https://github.com/zNairy/Sonaris | 5 | 0| 
| 20210420T19:38:42Z | Null | https://github.com/Wrench56/Backdoor | 1 | 0| 
| 20210420T19:03:29Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 65 | 11| 
| 20210420T16:35:46Z | I created this script to help make it easier for you to directly attack index.php on the website | https://github.com/penucuriCode/shell-backdoor | 2 | 1| 
| 20210420T13:21:03Z | OWASP ZAP add-on containing the web-backdoors and attack files from FuzzDB | https://github.com/zaproxy/fuzzdb-offensive | 6 | 6| 
| 20210420T13:12:20Z | Three sub-projects of different backdoor attack configurations scaling in complexity, with server and client implementations. | https://github.com/BrunoScaglione/Backdoor-Attack-Simulation | 0 | 0| 
| 20210420T12:02:21Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/ghost | 1043 | 504| 
| 20210420T10:39:26Z | Null | https://github.com/Delle9999/backdoor | 0 | 0| 
| 20210420T08:30:04Z | Null | https://github.com/igpig/igpigs-Backdoor | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210420T23:59:28Z | SQL project to analyse a growing business and colect relevant information to help steer the company%s future. | https://github.com/alanaselli/MavenFuzzyFactory_Project | 0 | 0| 
| 20210420T23:29:04Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2318 | 125| 
| 20210420T22:51:22Z | Fuzzy Logic for Python 3 | https://github.com/amogorkon/fuzzylogic | 22 | 9| 
| 20210420T22:48:18Z | Null | https://github.com/barddes/fuzzer-opencv | 0 | 0| 
| 20210420T22:33:19Z | A symbolic fuzzer that can generate input values symbolically for a python function. We assume that the function is not recursive and at most calls two self-contained methods. We can assume that all variables are annotated with the type information, and only container used in the programs are lists with the maximum size 10. | https://github.com/mathews1193/Symbolic_Fuzzer | 0 | 0| 
| 20210420T22:03:48Z | Security oriented software fuzzer. Supports evolutionary, feedback-driven fuzzing based on code coverage (SW and HW based) | https://github.com/google/honggfuzz | 2193 | 442| 
| 20210420T21:32:30Z | criando arquivo .fis no Matlab usando linhas de comando | https://github.com/jacimarajp/Controle-fuzzy | 0 | 0| 
| 20210420T21:04:41Z | Fuzzy matching for Neovim | https://github.com/amirrezaask/fuzzy.nvim | 35 | 1| 
| 20210420T20:55:02Z | Remote areas monitoring IoT node: ULP (Energy-harvesting powered) fire detection & alarming system using Fuzzy logic with an edge computing approach for daily temperature logging. | https://github.com/Rad-hi/Fuzzy_Fire_Detection | 0 | 0| 
| 20210420T20:43:27Z | fuzzyset.js - A fuzzy string set for javascript | https://github.com/Glench/fuzzyset.js | 1235 | 102| 



# 日更新程序
