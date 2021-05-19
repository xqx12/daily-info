# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210518 | Roku 机顶盒 RokuOS v9.4.0 build 4200 版本越狱 Exploit | https://github.com/llamasoft/RootMyRoku| 
| 20210518 | 恶意软件开发者滥用 PE 文件格式特性实现 GetProcAddress 欺骗 | https://dennisbabkin.com/blog/?t=malware-researchers-beware-of-getprocaddress-spoofing| 
| 20210518 | iOS 14.5 如何用 PAC 保护 Objective-C 对象 | https://mp.weixin.qq.com/s/VsqnWo6HGQT5LXdulpcaGg| 
| 20210518 | 如何从 Windows 截屏保存的图片中检测泄露的密码，CTF Writeup | https://lkmidas.github.io/posts/20210517-omhctf2021-writeups/| 
| 20210518 | DNS 安全进化 - DNS 协议中的信任问题 | https://ripe82.ripe.net/wp-content/uploads/presentations/18-huston-dns-evolution.pdf| 
| 20210518 | ESET 团队对 Android 平台的监视 App 进行研究，在 58 款监视 App 中总计发现了 150 多个漏洞，这些漏洞进一步会对用户造成危害。 | https://www.welivesecurity.com/2021/05/17/android-stalkerware-threatens-victims-further-exposes-snoopers-themselves/| 
| 20210518 | 研究员 Dmytro Oleksiuk 开源了一个工具库，帮助在开启 Hyper-V HVCI 硬件保护特性的机器上辅助编写 Payload 的工具 | https://github.com/Cr4sh/KernelForge/| 
| 20210518 | 利用 cgroups 的机制实现 Docker 容器逃逸 | https://0xdf.gitlab.io/2021/05/17/digging-into-cgroups.html| 
| 20210518 | RedWarden - Flexible CobaltStrike Malleable Redirector | https://github.com/mgeeky/RedWarden| 
| 20210518 | Finding writable folders and hijackable DLLs. | https://medium.com/@markmotig/finding-writable-folders-and-hijackable-dlls-3594a9a0b1c8| 
| 20210518 | 针对PHP Web Shell Hexedglobals.3793系列恶意软件分析溯源。 | https://labs.detectify.com/2019/05/24/investigation-of-php-web-shell-hexedglobals-3793-variants/| 
| 20210518 | FragAttacks：USENIX 2021 安全会议演讲议题视频。 | https://www.youtube.com/watch?v=OJ9nFeuitIU| 
| 20210518 | GW Tester：专门测试S/P-GW工具演示。 | https://wmnsk.com/posts/20200116_gw-tester/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210518 | Domain Borrowing: 一种基于CDN的新型隐蔽通信方法 | https://xlab.tencent.com/cn/2021/05/14/domain-borrowing/| 
| 20210518 | 另类的dex代码保护方法 | https://mp.weixin.qq.com/s/Efa0Dw8yCH_nojSwof0XYQ| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210518T21:50:32Z | CVE-2021-31703 | CVE-2021-31703 | https://github.com/l00neyhacker/CVE-2021-31703 | 未查询到CVE信息| 
| 20210518T21:45:27Z | CVE-2021-31702 | CVE-2021-31702 | https://github.com/l00neyhacker/CVE-2021-31702 | 未查询到CVE信息| 
| 20210518T20:24:30Z | CVE-2020-28018 | Exploit for Exim4 4.93 CVE-2020-28018 | https://github.com/lmol/CVE-2020-28018 | Exim 4 before 4.94.2 allows Use After Free in smtp_reset in certain situations that may be common for builds with OpenSSL.| 
| 20210518T16:21:31Z | CVE-2020-23852 | PoC for exploiting CVE-2020-23852 | https://github.com/JamesGeee/CVE-2020-23852 | A heap based buffer overflow vulnerability exists in ffjpeg through 2020-07-02 in the jfif_decode(void *ctxt, BMP *pb) function at ffjpeg/src/jfif.c (line 544 & line 545), which could cause a denial of service by submitting a malicious jpeg image.| 
| 20210518T16:21:28Z | CVE-2020-23851 | PoC for exploiting CVE-2020-23851 | https://github.com/JamesGeee/CVE-2020-23851 | A stack-based buffer overflow vulnerability exists in ffjpeg through 2020-07-02 in the jfif_decode(void *ctxt, BMP *pb) function at ffjpeg/src/jfif.c:513:28, which could cause a denial of service by submitting a malicious jpeg image.| 
| 20210518T16:21:26Z | CVE-2021-29603 | PoC for exploiting CVE-2021-29603 | https://github.com/JamesGeee/CVE-2021-29603 | TensorFlow is an end-to-end open source platform for machine learning. A specially crafted TFLite model could trigger an OOB write on heap in the TFLite implementation of `ArgMin`/`ArgMax`(https://github.com/tensorflow/tensorflow/blob/102b211d892f3abc14f845a72047809b39cc65ab/tensorflow/lite/kernels/arg_min_max.cc#L52-L59). If `axis_value` is not a value between 0 and `NumDimensions(input)`, then the condition in the `if` is never true, so code writes past the last valid element of `output_dims->data`. The fix will be included in TensorFlow 2.5.0. We will also cherrypick this commit on TensorFlow 2.4.2, TensorFlow 2.3.3, TensorFlow 2.2.3 and TensorFlow 2.1.4, as these are also affected and still in supported range.| 
| 20210518T16:21:23Z | CVE-2021-29602 | PoC for exploiting CVE-2021-29602 | https://github.com/JamesGeee/CVE-2021-29602 | TensorFlow is an end-to-end open source platform for machine learning. The implementation of the `DepthwiseConv` TFLite operator is vulnerable to a division by zero error(https://github.com/tensorflow/tensorflow/blob/1a8e885b864c818198a5b2c0cbbeca5a1e833bc8/tensorflow/lite/kernels/depthwise_conv.cc#L287-L288). An attacker can craft a model such that `input`%s fourth dimension would be 0. The fix will be included in TensorFlow 2.5.0. We will also cherrypick this commit on TensorFlow 2.4.2, TensorFlow 2.3.3, TensorFlow 2.2.3 and TensorFlow 2.1.4, as these are also affected and still in supported range.| 
| 20210518T16:20:58Z | CVE-2021-28465 | PoC for exploiting CVE-2021-28465 | https://github.com/JamesGeee/CVE-2021-28465 | Web Media Extensions Remote Code Execution Vulnerability| 
| 20210518T16:09:16Z | CVE-2020-24421 | PoC for exploiting CVE-2020-24421 | https://github.com/JamesGeee/CVE-2020-24421 | Adobe InDesign version 15.1.2 (and earlier) is affected by a NULL pointer dereference bug that occurs when handling a malformed .indd file. The impact is limited to causing a denial-of-service of the client application. User interaction is required to exploit this issue.| 
| 20210518T16:09:15Z | CVE-2020-9389 | PoC for exploiting CVE-2020-9389 | https://github.com/JamesGeee/CVE-2020-9389 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210518T23:06:00Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210518T19:37:42Z | TracerX Symbolic Virtual Machine | https://github.com/tracer-x/TracerX | 14 | 9| 
| 20210518T18:11:52Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 14 | 43| 
| 20210518T16:11:01Z | Null | https://github.com/rounakmodgil/kleenacademy | 0 | 0| 
| 20210518T15:21:21Z | Klee Kai creative assets | https://github.com/KleeKai-DEV/Klee-Kai-Creative | 0 | 0| 
| 20210518T11:20:11Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 136 | 13| 
| 20210518T11:20:07Z | Null | https://github.com/BajacDev/rust-klee-docker | 1 | 0| 
| 20210518T10:28:39Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 612 | 14| 
| 20210518T08:37:08Z | 99484 A & C team Worlds Code for 2021 Live-Remote Skills | https://github.com/Jython1415/penguin-Klee | 1 | 0| 
| 20210518T06:28:50Z | Null | https://github.com/fontworks-fonts/Klee | 448 | 13| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210518T05:02:41Z | Null | https://github.com/Hamzaawan1/s2exam | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210518T23:44:24Z | Pwn the devs in muse dash, exploit their code to your own advantage with this script | https://github.com/Easey8/Pwn-Dash | 0 | 0| 
| 20210518T23:40:51Z | Loads a driver from disk without signing required by using an exploited driver | https://github.com/AliHampton/DriverLoader | 0 | 0| 
| 20210518T23:36:34Z | Null | https://github.com/Lxnden1/LunarExploits | 0 | 0| 
| 20210518T23:35:55Z | An easy challenge for a stack-based buffer overflow! Preset shellcode will execute calc.exe upon exploitation. | https://github.com/Crystalware/BufferOverflow_EasyChallenge | 0 | 0| 
| 20210518T23:11:48Z |  Learning vulnerability analysis, exploit development, software debugging, binary analysis, and general cyber security issues | https://github.com/rudenal/ctfs | 0 | 0| 
| 20210518T22:17:52Z | Mega repo for exploit development. Contains individual exploits and libraries to assist during exploitation | https://github.com/jeffssh/exploits | 2 | 0| 
| 20210518T22:15:59Z | Microbiome Analysis Powered By Recursive Quasi-species Networks: Uncovering rules of organization, competition, succession and exploitation | https://github.com/zeroknowledgediscovery/qbiome | 0 | 0| 
| 20210518T22:03:27Z | Unpack the full potential of your PlayStation 4. | https://github.com/ps4h3x/ps4h3x.xyz | 2 | 0| 
| 20210518T21:44:14Z | The official Exploit Database repository | https://github.com/offensive-security/exploitdb | 6111 | 1734| 
| 20210518T21:36:02Z | Pown.js is a security testing an exploitation toolkit built on top of Node.js and NPM. | https://github.com/pownjs/pown | 205 | 27| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210518T23:24:46Z | Backend for our cyber security forum - %Backdoor% | https://github.com/backdoor-epics/backdoor-backend | 0 | 1| 
| 20210518T22:11:21Z | A simple remote tool written in C#.    一个简单的c#远控 | https://github.com/qwqdanchun/DcRat | 98 | 41| 
| 20210518T21:28:59Z | Simple Backdoor Coded in Python | https://github.com/Drew-Alleman/backdoor | 0 | 0| 
| 20210518T20:34:40Z | You have a Front Door, a Backdoor, why not a SideD00r... | https://github.com/Aaron-Akhtar/SideD00r | 0 | 0| 
| 20210518T20:31:20Z | React frontend for the cybersecurity forum website - %Backdoor% | https://github.com/backdoor-epics/backdoor-frontend | 0 | 1| 
| 20210518T19:07:45Z | sexc modd | https://github.com/RandomClientCollector/ZispanosBackdoor | 0 | 0| 
| 20210518T17:14:34Z | Null | https://github.com/connorbuck/backdoor-dispensary-website | 0 | 0| 
| 20210518T14:55:43Z | Null | https://github.com/Fsoky/BackDoor-Python | 3 | 1| 
| 20210518T14:44:35Z | A backdoor plugin for Spigot, Paper, and Bukkit! | https://github.com/PythonJoshua/backdoorplugin | 2 | 1| 
| 20210518T12:32:06Z | php script to gain access to a site once injected | https://github.com/Urtext69/backdoor | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210518T23:57:24Z | Fuzzer for LP models in MPS | https://github.com/elefthei/lp-fuzzer | 0 | 0| 
| 20210518T23:15:06Z | Highly experimental parser that calculates the way a pattern best matches a text, and how closely it matches the text, rather than calculates a binary match or parse error. | https://github.com/SamRoberts/fuzzy | 0 | 0| 
| 20210518T22:37:54Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2328 | 126| 
| 20210518T20:44:58Z | Null | https://github.com/eavarlamova/fuzzy-transport-problem | 0 | 0| 
| 20210518T20:41:26Z | Null | https://github.com/opimentel-github/fuzzy-torch | 1 | 0| 
| 20210518T19:56:52Z | Downloader for Firefox/jsshell builds for fuzzing. | https://github.com/MozillaSecurity/fuzzfetch | 23 | 10| 
| 20210518T19:54:11Z | Null | https://github.com/gdepuydt/fuzzoz | 0 | 0| 
| 20210518T19:49:05Z | Fuzzy finder for every AWS component | https://github.com/AndreZiviani/aws-fuzzy | 9 | 2| 
| 20210518T19:22:40Z | Null | https://github.com/XOMAv2/NeuroFuzzySystemsLabs | 0 | 0| 
| 20210518T19:05:49Z | WOW Classic Addons | https://github.com/LuckDuck-GitHub/fuzzy-invention | 0 | 0| 



# 日更新程序
