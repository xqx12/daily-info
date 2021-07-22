# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210721 | 利用 PowerShell 混淆技术绕过 ASMI 检测的工具 | https://www.reddit.com/r/netsec/comments/olzpsr/a_new_powershell_obfuscation_tool_for_amsi_bypass/| 
| 20210721 | Windows 11 安装环境探测工具 WhyNotWin11 发布公告，修复 DLL 劫持漏洞 | https://www.reddit.com/r/netsec/comments/ogpzl1/previous_whynotwin11_releases_vulnerable_to_dll/| 
| 20210721 | 攻防启示：Chromium组件风险剖析与收敛 | https://mp.weixin.qq.com/s/f0aFLEKyABpYDobPN2b6tQ| 
| 20210721 | Harpoon - 利用多个第三方 API 收集情报数据的命令行工具 | https://github.com/Te-k/harpoon| 
| 20210721 | 一个古老的打印机驱动漏洞，成功利用可以实现 Windows 本地提权。影响 HP、Samsung 以及 Xerox 打印机 | https://labs.sentinelone.com/cve-2021-3438-16-years-in-hiding-millions-of-printers-worldwide-vulnerable/| 
| 20210721 | Fortinet 安全设备 FortiManager daemon 存在 RCE 漏洞 | https://www.theregister.com/2021/07/20/fortinet_rce/| 
| 20210721 | Apple 内核 mount 系统调用 Double-Fetch 漏洞分析 | https://pwning.systems/posts/apple-kernel-vulnerability/| 
| 20210721 | size_t 到 int 类型转换导致的 Linux 内核文件系统层漏洞，成功利用可以实现本地提权(CVE-2021-33909) | https://blog.qualys.com/vulnerabilities-threat-research/2021/07/20/sequoia-a-local-privilege-escalation-vulnerability-in-linuxs-filesystem-layer-cve-2021-33909| 
| 20210721 | Chrome 浏览器 92 版本将进一步强化 Site Isolation 保护机制 | https://security.googleblog.com/2021/07/protecting-more-with-site-isolation.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+GoogleOnlineSecurityBlog+%28Google+Online+Security+Blog%29| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210721 | 基于用户态虚拟化的物联网设备仿真方法 | https://blog.lyle.ac.cn/2021/07/09/uemu/| 
| 20210721 | 浅谈云安全之K8S | https://www.anquanke.com/post/id/245526| 
| 20210721 | 应急响应的神兵利器 | https://www.anquanke.com/post/id/246290| 
| 20210721 | NGLite-基于区块链网络的匿名跨平台远控程序 | https://www.anquanke.com/post/id/247454| 
| 20210721 | 利用pocsuite3框架编写poc实战案例 | https://mp.weixin.qq.com/s/LN5gJnKpunfWGJ6yQQtHuw| 
| 20210721 | 某工控设备固件提取及分析 | http://blog.nsfocus.net/vxwork-qnx/| 
| 20210721 | 攻防启示：Chromium组件风险剖析与收敛 | https://mp.weixin.qq.com/s/f0aFLEKyABpYDobPN2b6tQ| 
| 20210721 | [翻译] 通过不安全的动态加载获得获得反射 XSS | https://mp.weixin.qq.com/s/MyC527oZVqT1ZDjlUZ_gYw| 
| 20210721 | VPN客户端访问日志_内部访问出错_2021年4月15日样本分析 | https://mp.weixin.qq.com/s/ymvqym3vEwKjGnR2F3skWw| 
| 20210721 | 探索建⽴API接⼝安全⻛险评分算法(参考 cvss3.1) | https://mp.weixin.qq.com/s/Ws4oGuPQJN4rHviazVqfAw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210721T23:14:02Z | CVE-2021-36934 | Fix for the CVE-2021-36934 | https://github.com/JoranSlingerland/CVE-2021-36934 | | 
| 20210721T21:29:58Z | CVE-2021-1675 | C# and Impacket implementation of PrintNightmare CVE-2021-1675/CVE-2021-34527 | https://github.com/cube0x0/CVE-2021-1675 | Windows Print Spooler Elevation of Privilege Vulnerability| 
| 20210721T18:34:36Z | CVE-2020-23934 | Python Implementation of CVE-2020-23934 | https://github.com/zyeinn/CVE-2020-23934 | An issue was discovered in RiteCMS 2.2.1. An authenticated user can directly execute system commands by uploading a php web shell in the %Filemanager% section.| 
| 20210721T18:26:38Z | cve-2021-33909 | This module fixes an issue in the kernels filesystem layer (CVE-2021-33909) by kprobe-replacing vulnerable functions during runtime | https://github.com/baerwolf/cve-2021-33909 | fs/seq_file.c in the Linux kernel 3.16 through 5.13.x before 5.13.4 does not properly restrict seq buffer allocations, leading to an integer overflow, an Out-of-bounds Write, and escalation to root by an unprivileged user, aka CID-8cae8cd89f05.| 
| 20210721T12:56:25Z | CVE-2021-33909 | Sequoia exploit (7/20/21) | https://github.com/AmIAHuman/CVE-2021-33909 | fs/seq_file.c in the Linux kernel 3.16 through 5.13.x before 5.13.4 does not properly restrict seq buffer allocations, leading to an integer overflow, an Out-of-bounds Write, and escalation to root by an unprivileged user, aka CID-8cae8cd89f05.| 
| 20210721T03:02:49Z | CVE-2020-15778 | Exploit for CVE-2020-15778(OpenSSH vul) | https://github.com/Neko2sh1ro/CVE-2020-15778-Exploit |  scp in OpenSSH through 8.3p1 allows command injection in the scp.c toremote function, as demonstrated by backtick characters in the destination argument. NOTE: the vendor reportedly has stated that they intentionally omit validation of %anomalous argument transfers% because that could %stand a great chance of breaking existing workflows.%| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210721T15:54:50Z | Personal portfolio website built with React | https://github.com/collinkleest/kleest.io | 0 | 0| 
| 20210721T10:43:16Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210721T10:25:30Z | Report PPT template for CS students  | https://github.com/Fishermanykx/paper_reading_report_template | 1 | 0| 
| 20210721T10:12:29Z | Null | https://github.com/xenoney/kleee | 0 | 0| 
| 20210721T05:57:20Z | ⚡ Kleeja Open Source Desktop Application (Windows / Linux / Mac) | https://github.com/anasybal/Kleeja-da | 1 | 1| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210721T14:56:09Z | Automatic Exploit Generation (AEG) tool based on S2E 2.X | https://github.com/aesophor/baphomet | 3 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210721T23:52:12Z | Hardware setup tips for exploiting MouseJack on Catalina and OS X | https://github.com/notwlsn/catalina-mousejack | 0 | 0| 
| 20210721T23:26:30Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9758 | 1609| 
| 20210721T23:25:16Z | Null | https://github.com/0xturazzi/Um-Livrinho-Sobre-Exploit-Dev | 0 | 0| 
| 20210721T23:20:13Z | A collection of custom built scripts to exploit known vulnerability chains | https://github.com/R-s0n/Custom_Exploits | 0 | 0| 
| 20210721T22:58:35Z | labsecurity is a framework and its use is for ethical hacking and computer security | https://github.com/dylan14567/labsecurity | 5 | 4| 
| 20210721T22:41:46Z | 🦓 RCE in Zimbra Collaboration 8.7.X < 8.7.11p10 | https://github.com/oppsec/Zebra | 1 | 0| 
| 20210721T22:32:53Z | Analysis of kernel mode device drivers, in an attempt to find bugs or vulnerabilities. All exploits that have been patched by the vendor that are related to the device driver will be disclosed in this GitHub repository as well. | https://github.com/Crystalware/Driver-Analysis | 0 | 1| 
| 20210721T22:20:59Z | Repository for my talk %Crafting exploits, tools and havoc with Ruby% featured at Ruby Kaigi 2021. | https://github.com/MauroEldritch/rubycraft | 0 | 0| 
| 20210721T22:13:52Z | Multi-library tool, innitially developed for binary exploitation. | https://github.com/migoliatte/Elf-shellCodeExploit | 0 | 0| 
| 20210721T22:12:30Z | Modular penetration testing platform that enables you to write, test, and execute exploit code. | https://github.com/EntySec/HatSploit | 73 | 28| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210721T21:55:58Z | Null | https://github.com/Enormity-Organization/Backdoor-Generator | 1 | 0| 
| 20210721T21:35:23Z | Dashboard for conducting Backdoors and Breaches sessions over Zoom. | https://github.com/p3hndrx/B-B-Shuffle | 2 | 0| 
| 20210721T18:48:03Z | Null | https://github.com/Enormity-Hack/Backdoor-Generator | 0 | 0| 
| 20210721T18:07:41Z | Backdoor has been discovered in Linsys WAG200G that listening on port 32764 in 2015. I decided to create this repository with some codes to access backdoor because this security hole exists today. | https://github.com/enty8080/32764-multi-backdoor | 2 | 2| 
| 20210721T12:35:26Z | Leux-Backdoor 0.3 0.9 version  | https://github.com/3arthx/Leux-Backdoor | 2 | 1| 
| 20210721T09:57:08Z | RATata is a simple python RAT to setup and use ! | https://github.com/loTus04/RATata | 8 | 6| 
| 20210721T07:30:02Z | Null | https://github.com/gsingla21/Backdoor | 0 | 0| 
| 20210721T06:47:44Z | Null | https://github.com/sudharshan-krishna/backdoor | 0 | 0| 
| 20210721T06:19:13Z | Malware and malicious applications database | https://github.com/Black-Hell-Team/sppen | 15 | 2| 
| 20210721T04:50:40Z | Config files for my GitHub profile. | https://github.com/backdooroe/backdooroe | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210721T09:06:15Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1847 | 388| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210721T23:55:59Z | Null | https://github.com/amorblue/Fuzzing | 0 | 0| 
| 20210721T23:38:11Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210721T23:31:40Z | SecLists is the security tester%s companion. It%s a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. | https://github.com/danielmiessler/SecLists | 32574 | 16853| 
| 20210721T23:04:51Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 490 | 48| 
| 20210721T22:45:56Z | A fuzzy c-means implementation to classify wines. | https://github.com/JMateusSousa/Fuzzy-C-Means | 0 | 1| 
| 20210721T22:25:47Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2358 | 132| 
| 20210721T21:35:36Z | Fuzzy Logic & Knowledge Based System for difficulty of the AI in First person shooters | https://github.com/tinitis0/Fuzzy-Logic-KBS | 0 | 0| 
| 20210721T21:35:26Z | A fuzzer for full VM kernel/driver targets | https://github.com/IntelLabs/kAFL | 244 | 42| 
| 20210721T20:54:12Z | Hi thre, I%m TRÄW🤟🏻, i%m a beginner in ethical hacking and Content Creator on Level iv Security & NOOBSEC. I Spend most of time coding outstanding ethical hacking projects or recording useful short tutorials . I love programming ethical hacking tools, fuzzing and hacking all the things | https://github.com/0xTRAW/0xTRAW | 1 | 1| 
| 20210721T20:53:08Z | Practice repository for binary exploitation and fuzzing | https://github.com/RickdeJager/binexp-practice | 0 | 0| 



# 日更新程序
