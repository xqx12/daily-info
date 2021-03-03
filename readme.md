# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210303 | 2018 年爆出的“幽灵”漏洞，近期该漏洞完整攻击代码出现在 VirusTotal 平台 | https://therecord.media/first-fully-weaponized-spectre-exploit-discovered-online/| 
| 20210303 | How I Might Have Hacked Any Microsoft Account | https://thezerohack.com/how-i-might-have-hacked-any-microsoft-account| 
| 20210303 | Anatomy of an Exploit: RCE with CVE-2020-1350 SIGRed | https://www.graplsecurity.com/post/anatomy-of-an-exploit-rce-with-cve-2020-1350-sigred| 
| 20210303 | UnC0ver 团队宣布其越狱工具已经支持 iOS 14.3 版本 | https://threatpost.com/jailbreak-tool-works-on-iphones-up-to-ios-14-3/164420/| 
| 20210303 | Chromium RenderFrameHostImpl UAF 漏洞的利用 | https://microsoftedge.github.io/edgevr/posts/yet-another-uaf/| 
| 20210303 | VMware ESXi SLP 服务 Pre-Auth RCE 漏洞分析（CVE-2020-3992、CVE-2021-21974） | https://www.thezdi.com/blog/2021/3/1/cve-2020-3992-amp-cve-2021-21974-pre-auth-remote-code-execution-in-vmware-esxi| 
| 20210303 | 近期有攻击者利用恶意 Office 文档传播 ObliqueRAT 远控样本 | https://blog.talosintelligence.com/2021/02/obliquerat-new-campaign.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+feedburner%2FTalos+%28Talos%E2%84%A2+Blog%29| 
| 20210303 | bluetooth_stack 开源蓝牙协议栈源码分析与漏洞挖掘 | https://www.cnblogs.com/hac425/p/14470699.html| 
| 20210303 | 红蓝对抗中的云原生漏洞挖掘及利用实录 | https://security.tencent.com/index.php/blog/msg/183| 
| 20210303 | Node.JS 第三方库 systeminformation 被发现命令注入漏洞 | https://sec.today/pulses/bc156e11-0a44-49a5-af0e-124516b58119/| 
| 20210303 | Node.JS 第三方库 systeminformation 被发现命令注入漏洞 | https://github.com/ForbiddenProgrammer/CVE-2021-21315-PoC| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210303 | sqlinjection-detect: C语言编写的基于语义分析的SQL注入检测... | https://github.com/peter-cui1221/sqlinjection-detect| 
| 20210303 | Node.js原型链污染的利用 | https://www.freebuf.com/articles/web/264966.html| 
| 20210303 | PHP反序列化 — 字符逃逸 | https://xz.aliyun.com/t/9213| 
| 20210303 | SonicWall SSL-VPN 远程命令执行 | https://www.sec-in.com/article/899| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210303T12:41:24Z | CVE-2021-21315 | CVE 2021-21315 PoC | https://github.com/ForbiddenProgrammer/CVE-2021-21315-PoC | The System Information Library for Node.JS (npm package %systeminformation%) is an open source collection of functions to retrieve detailed hardware, system and OS information. In systeminformation before version 5.3.1 there is a command injection vulnerability. Problem was fixed in version 5.3.1. As a workaround instead of upgrading, be sure to check or sanitize service parameters that are passed to si.inetLatency(), si.inetChecksite(), si.services(), si.processLoad() ... do only allow strings, reject any arrays. String sanitation works as expected.| 
| 20210303T10:55:25Z | CVE-2021-23132 | com_media allowed paths that are not intended for image uploads to RCE | https://github.com/HoangKien1020/CVE-2021-23132 | 未查询到CVE信息| 
| 20210303T10:53:02Z | CVE-2021-27246 | Null | https://github.com/synacktiv/CVE-2021-27246_Pwn2Own2020 | 未查询到CVE信息| 
| 20210303T10:40:21Z | CVE-2021-21972 | Nmap script to check vulnerability CVE-2021-21972 | https://github.com/GuayoyoLabs/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210303T10:30:34Z | CVE-2020-9484 | Null | https://github.com/DXY0411/CVE-2020-9484 | When using Apache Tomcat versions 10.0.0-M1 to 10.0.0-M4, 9.0.0.M1 to 9.0.34, 8.5.0 to 8.5.54 and 7.0.0 to 7.0.103 if a) an attacker is able to control the contents and name of a file on the server; and b) the server is configured to use the PersistenceManager with a FileStore; and c) the PersistenceManager is configured with sessionAttributeValueClassNameFilter=%null% (the default unless a SecurityManager is used) or a sufficiently lax filter to allow the attacker provided object to be deserialized; and d) the attacker knows the relative file path from the storage location used by FileStore to the file the attacker has control over; then, using a specifically crafted request, the attacker will be able to trigger remote code execution via deserialization of the file under their control. Note that all of conditions a) to d) must be true for the attack to succeed.| 
| 20210303T08:01:24Z | CVE-2020-28243 | CVE-2020-28243 Local Privledge Escalation Exploit in SaltStack Minion | https://github.com/stealthcopter/CVE-2020-28243 | An issue was discovered in SaltStack Salt before 3002.5. The minion%s restartcheck is vulnerable to command injection via a crafted process name. This allows for a local privilege escalation by any user able to create a files on the minion in a non-blacklisted directory.| 
| 20210303T03:58:10Z | CVE-2021-21972 | CVE-2021-21972 | https://github.com/milo2012/CVE-2021-21972 | | 
| 20210303T03:46:48Z | CVE-2020-24597 | Directory traversal in com_media to RCE | https://github.com/HoangKien1020/CVE-2020-24597 | 未查询到CVE信息| 
| 20210303T03:30:46Z | cve-2021-21972 | Null | https://github.com/d3sh1n/cve-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210303T03:10:23Z | CVE-2021-21972 | Null | https://github.com/QmF0c3UK/CVE-2021-21972-vCenter-6.5-7.0-RCE-POC | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210303T13:21:15Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 170 | 5| 
| 20210303T13:15:04Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1638 | 483| 
| 20210303T05:15:19Z | Null | https://github.com/fontworks-fonts/Klee | 372 | 10| 
| 20210303T02:24:23Z | KleeneExpressions | https://github.com/ostomachion/Kleene | 1 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210303T13:12:27Z | Exploit ILP to learn symmetry breaking constraints of ASP programs. | https://github.com/prosysscience/Symmetry_Breaking_with_ILP | 0 | 0| 
| 20210303T13:10:12Z | Null | https://github.com/Deepanjalkumar/Exploit-Development | 0 | 0| 
| 20210303T13:02:27Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 9 | 4| 
| 20210303T12:59:07Z | A number of exploits and tools I%ve written for CVEs accredited to Marshall Whittaker/oxagast | https://github.com/oxagast/oxasploits | 4 | 1| 
| 20210303T12:50:17Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 8 | 5| 
| 20210303T12:31:44Z | Null | https://github.com/YanChab/Exploit-SB147 | 0 | 0| 
| 20210303T12:27:28Z | Kernel exploits and writeups | https://github.com/meowmeowxw/kernel-exploits | 0 | 0| 
| 20210303T11:47:40Z | Null | https://github.com/Lanph3re/hevd-stackoverflow-exploit | 0 | 0| 
| 20210303T11:35:12Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9075 | 1460| 
| 20210303T11:28:23Z | Windows全版本提权脚本 | https://github.com/safesword/WindowsExp | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210303T11:31:51Z | %Socialx% is a Social Engineering And Remote Access Trojan Tool. You can generate fud backdoor and you can embed any file you want inside of the exe file. | https://github.com/AzizKpln/Social_X | 68 | 17| 
| 20210303T11:03:06Z | backdoor uiuiuiui | https://github.com/zeru2/backdoor | 0 | 0| 
| 20210303T10:55:08Z | Thefatrat a massive exploiting tool : Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack and etc . This tool compiles a malware with popular payload and then the compiled malware can be execute on windows, android, mac . The malware that created with this tool also have an ability to bypass most AV software protection . | https://github.com/Screetsec/TheFatRat | 4995 | 1645| 
| 20210303T10:50:00Z | Backdoor Open Source | https://github.com/kadzicuh/Backdoor | 0 | 0| 
| 20210303T07:13:10Z | Linux Kernel module-less implant (backdoor) | https://github.com/milabs/kopycat | 0 | 0| 
| 20210303T02:17:39Z | A port of BHIS%s Backdoors & Breaches for playingcards.io | https://github.com/FirmGuardian/backdoors-and-breaches-pcio | 1 | 1| 
| 20210303T01:55:08Z | Null | https://github.com/djaldave/laevad-backdoor | 0 | 0| 
| 20210303T01:01:24Z | A Simple android remote administration tool using sockets. It uses java on the client side and python on the server side | https://github.com/karma9874/AndroRAT | 172 | 76| 
| 20210303T00:25:50Z | Simple Backdoor plugin for 1.12.2. | https://github.com/MajesticWaffle/Minecraft-Backdoor | 1 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210303T02:49:16Z | Null | https://github.com/guardstrikelab/fuzzx_cpp_demo | 0 | 0| 
| 20210303T02:37:27Z | Null | https://github.com/mrfuzz12/FuzzCheat | 0 | 0| 
| 20210303T02:32:37Z | Coding practice for HTML/CSS/anything else web based | https://github.com/FuzzyPumpkin/FuzzyPumpkin.github.io | 5 | 1| 
| 20210303T02:12:36Z | A fork and successor of the Sulley Fuzzing Framework | https://github.com/jtpereyda/boofuzz | 1158 | 235| 
| 20210303T01:53:52Z | FuzzBench - Fuzzer benchmarking as a service. | https://github.com/google/fuzzbench | 604 | 102| 
| 20210303T01:45:19Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 5987 | 1201| 
| 20210303T01:33:47Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 1339 | 295| 
| 20210303T00:28:21Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 8 | 1| 
| 20210303T00:06:05Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2275 | 115| 



# 日更新程序
