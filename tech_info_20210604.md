# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210604 | Open Source Insights - Google 开源了可以展示多个开源组件依赖关系的工具，目前已支持 go/cargo/npm 等市场的开源组件 | https://deps.dev/| 
| 20210604 | Easy Hypervisor Heap Visualization with PyPANDA and HeapInspect | https://www.lukecraig.com/pypanda_heap_inspect/| 
| 20210604 | DetectionLab - 一套自动化构建 Windows 域环境并安装安全检测相关组件的工具 | https://github.com/clong/DetectionLab| 
| 20210604 | 有研究员公开了一个解析并提取 Dell PFS BIOS 固件的工具 | https://github.com/platomav/BIOSUtilities#vaio-packaging-manager-extractor| 
| 20210604 | XSS in the AWS Console | https://frichetten.com/blog/xss_in_aws_console/| 
| 20210604 | Gitlab 任意文件读漏洞分析（CVE-2021–22201） | https://tradahacking.vn/cve-2021-22201-arbitrary-file-read-on-gitlab-d84d77cd83e3| 
| 20210604 | CVE-2021-30724: CVMServer Vulnerability in macOS and iOS | https://www.trendmicro.com/en_us/research/21/f/CVE-2021-30724_CVMServer_Vulnerability_in_macOS_and_iOS.html| 
| 20210604 | Chrome 浏览器将通过机器学习模型的方式检测扩展的安全性 | https://security.googleblog.com/2021/06/new-protections-for-enhanced-safe.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+GoogleOnlineSecurityBlog+%28Google+Online+Security+Blog%29| 
| 20210604 | SharpPanda: Chinese APT Group Targets Southeast Asian Government With Previously Unknown Backdoor。来自 Checkpoint 的 Blog | https://research.checkpoint.com/2021/chinese-apt-group-targets-southeast-asian-government-with-previously-unknown-backdoor/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210604 | 技术分享 , Fastjson-RCE漏洞复现 | https://mp.weixin.qq.com/s/H0vKBKmsATuB3yKGXeAQvw| 
| 20210604 | Jar 组件自动化风险监测和升级实践 | https://mp.weixin.qq.com/s/3tmwACw-weWCBzipHK79AQ| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210604T23:23:37Z | CVE-2021-21985 | Null | https://github.com/alt3kx/CVE-2021-21985_PoC | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210604T17:32:33Z | CVE-2021-21985 | CVE-2021-21985 VMware vCenter Server远程代码执行漏洞 EXP | https://github.com/r0ckysec/CVE-2021-21985 | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210604T16:59:25Z | CVE-2021-29155 | Proof of Concept CVE-2021-29155  | https://github.com/Kakashiiiiy/CVE-2021-29155 | An issue was discovered in the Linux kernel through 5.11.x. kernel/bpf/verifier.c performs undesirable out-of-bounds speculation on pointer arithmetic, leading to side-channel attacks that defeat Spectre mitigations and obtain sensitive information from kernel memory. Specifically, for sequences of pointer arithmetic operations, the pointer modification performed by the first operation is not correctly accounted for when restricting subsequent operations.| 
| 20210604T15:46:07Z | CVE-2021-28476 | PoC for CVE-2021-28476 a guest-to-host "Hyper-V Remote Code Execution Vulnerability" in vmswitch.sys. | https://github.com/0vercl0k/CVE-2021-28476 | Hyper-V Remote Code Execution Vulnerability| 
| 20210604T14:44:35Z | CVE-2021-27965 | stack based buffer overflow in MsIo64.sys, Proof of Concept Local Privilege Escalation to nt authority/system | https://github.com/mathisvickie/CVE-2021-27965 | The MsIo64.sys driver before 1.1.19.1016 in MSI Dragon Center before 2.0.98.0 has a buffer overflow that allows privilege escalation via a crafted 0x80102040, 0x80102044, 0x80102050, or 0x80102054 IOCTL request.| 
| 20210604T11:26:42Z | CVE-2021-29447 | Wordpress XXE injection 구축 자동화 및 PoC  | https://github.com/dnr6419/CVE-2021-29447 | Wordpress is an open source CMS. A user with the ability to upload files (like an Author) can exploit an XML parsing issue in the Media Library leading to XXE attacks. This requires WordPress installation to be using PHP 8. Access to internal files is possible in a successful XXE attack. This has been patched in WordPress version 5.7.1, along with the older affected versions via a minor release. We strongly recommend you keep auto-updates enabled.| 
| 20210604T05:57:15Z | CVE-2021-2173 | CVE-2021-2173 | https://github.com/emad-almousa/CVE-2021-2173 | Vulnerability in the Recovery component of Oracle Database Server. Supported versions that are affected are 12.1.0.2, 12.2.0.1, 18c and 19c. Easily exploitable vulnerability allows high privileged attacker having DBA Level Account privilege with network access via Oracle Net to compromise Recovery. While the vulnerability is in Recovery, attacks may significantly impact additional products. Successful attacks of this vulnerability can result in unauthorized read access to a subset of Recovery accessible data. CVSS 3.1 Base Score 4.1 (Confidentiality impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:C/C:L/I:N/A:N).| 
| 20210604T01:53:35Z | CVE-2021-21985 | CVE-2021-21985 vmware 6.7-9.8 RCE | https://github.com/daedalus/CVE-2021-21985 | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210604T23:18:02Z | Dodoco doko? | https://github.com/RiceFT/klee | 0 | 0| 
| 20210604T17:23:04Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 141 | 14| 
| 20210604T16:39:31Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 12 | 0| 
| 20210604T12:51:45Z | Null | https://github.com/LunaNyan/klee.n-e.kr | 0 | 0| 
| 20210604T11:05:29Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 646 | 15| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210604T10:59:30Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 128 | 31| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210604T23:56:04Z | Organizes rp++ output to make finding good gadgets faster | https://github.com/bmdyy/ropz | 0 | 0| 
| 20210604T23:54:48Z | Portable, NULL-free, Position-Independent (PIC) and highly optimized shellcodes for exploit development. | https://github.com/cwaazywabbit/shellcodes | 0 | 0| 
| 20210604T22:43:47Z | NTFS exploit delivery with randomized activation and time bomb. | https://github.com/hafiz-kamilin/exercise_ntfsExploiter | 0 | 0| 
| 20210604T22:40:35Z | Null | https://github.com/zYan666/Demon-Exploit | 0 | 0| 
| 20210604T22:36:27Z | Null | https://github.com/HarrysExploit/Harrys-exploit-setup | 0 | 0| 
| 20210604T22:34:04Z | Null | https://github.com/HarrysExploit/Harrys-exploit | 0 | 0| 
| 20210604T22:30:02Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 11 | 3| 
| 20210604T22:27:16Z | We exploit to the full the capabilities of distributed processing using a Distributed Linear Support Vector Machine to retrieve, train the model and predict a medical dataset. | https://github.com/Arnaldgg7/SparkML_Distributed_Machine_Learning_Model | 0 | 0| 
| 20210604T22:21:45Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9529 | 1541| 
| 20210604T21:55:59Z | BananaCannon is a series of exploit proof of concepts for MonkeyType.com, a popular typing test web application with a growing community. This repository contains XSS exploits and a python PoC to spoof leaderboard scores | https://github.com/tcbutler320/BananaCannon | 2 | 1| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210604T22:50:56Z | A workflow to create/manage a backdoor admin account and rotate the password. E.g. Another LAPS workflow. | https://github.com/Rocketman-Tech/BreakGlassUser | 0 | 0| 
| 20210604T22:35:11Z | Windows 10 PRO Activator - No more backdoors via loaders from China and neither you will need any crack anymore that is valid for a week or two. This is script is written for powershell/cmd. This script will also removing all bloatware from Windows 10. Edit the script after your needs. | https://github.com/wuseman/wLoader | 63 | 16| 
| 20210604T22:30:19Z | Null | https://github.com/victormuller2007/backdoord | 0 | 0| 
| 20210604T20:45:49Z | App that gives trends and growth of several career fields, how likely they%ll be taken over by automation & robots and gives a backdoor to enter the BIG digital revolution | https://github.com/AyoubHan/Backdoor-Project | 0 | 0| 
| 20210604T19:41:19Z | A basic trojan backdoor that connects the infected system with the trojan%s command server, which includes a custom shell. Educational purposes only. | https://github.com/c0y0te-git/Antioch_Trojan | 0 | 0| 
| 20210604T19:28:48Z | Python 3 IRC Bot / Botnet | https://github.com/trackmastersteve/HackServ | 21 | 17| 
| 20210604T14:27:43Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/ghost | 1129 | 543| 
| 20210604T14:27:23Z | A sample app to demonstrate how to create Xamarin UITests using the Page Object architecture, Backdoor Methods and App Links (aka Deep Linking) | https://github.com/brminnick/UITestSampleApp | 35 | 27| 
| 20210604T13:37:58Z | a simple BackDoor Written With C/C++ | https://github.com/SudoerUser/SuDoor | 0 | 0| 
| 20210604T10:16:38Z | Null | https://github.com/k2oneiy/backdoor-step-by-step-process | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210604T13:00:14Z | Thin interface for libFuzzer, an in-process, coverage-guided, evolutionary fuzzing engine. | https://github.com/planetis-m/libfuzzer | 1 | 0| 
| 20210604T12:53:02Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6354 | 1288| 
| 20210604T12:39:45Z | Fuzzing dictionaries for afl-fuzz/LibFuzzer 可能是目前最全面的开源模糊测试字典集合了~ | https://github.com/salmonx/dictionaries | 13 | 0| 
| 20210604T12:31:55Z | VMI Kernel Fuzzer for Xen Project - VM forking, VMI & AFL integration demo | https://github.com/intel/kernel-fuzzer-for-xen-project | 318 | 45| 
| 20210604T12:07:05Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 441 | 38| 
| 20210604T11:50:38Z | Null | https://github.com/dechjo/fuzzing-experiments | 0 | 0| 
| 20210604T11:30:34Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210604T10:20:31Z | This is a simple implementation of Fuzzy c-mean and Hard c-mean clustring.  | https://github.com/GhazalTajik1998/Hard-and-Fuzzy-C-mean-clustring | 0 | 0| 
| 20210604T09:27:30Z | Null | https://github.com/ahi-hfg/fuzzy-dollop | 0 | 0| 
| 20210604T09:13:53Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3532 | 822| 



# 日更新程序
