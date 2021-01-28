# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210127 | Google 修复 Golang Windows RCE 漏洞（CVE-2021-3115） | https://www.bleepingcomputer.com/news/security/google-fixes-severe-golang-windows-rce-vulnerability/| 
| 20210127 | Apple 紧急发布 iOS 14.4/iPadOS 14.4，修复 3 个可能已被野外利用的 0Day | https://support.apple.com/en-us/HT212146| 
| 20210127 | sudo 堆溢出漏洞 CVE-2021-3156 分析 | https://blog.qualys.com/vulnerabilities-research/2021/01/26/cve-2021-3156-heap-based-buffer-overflow-in-sudo-baron-samedit| 
| 20210127 | The all-in-one Red Team browser extension for Web Pentesters | https://github.com/LasCC/Hack-Tools| 
| 20210127 | Fill your Boots: Enhanced Embedded BootloaderExploits via Fault Injection and Binary Analysis(Paper) | http://tches.iacr.org/index.php/TCHES/article/view/8727/8327| 
| 20210127 | 动静态分析的方法检测软件供应链中的 0Day 攻击 | https://ajinabraham.com/blog/detecting-zero-days-in-software-supply-chain-with-static-and-dynamic-analysis| 
| 20210127 | ZDI 将于 4 月份在温哥华举办 Pwn2Own 2021，比赛的目标及细则公布了 | https://www.thezdi.com/blog/2021/1/25/announcing-pwn2own-vancouver-2021| 
| 20210127 | Checkpoint 对近期发现的 TikTok 通讯录同步相关的隐私问题的分析 | https://research.checkpoint.com/2021/tiktok-fixes-privacy-issue-discovered-by-check-point-research/| 
| 20210127 | SSRF 漏洞以及在不同语言中的利用 | https://security.tencent.com/index.php/blog/msg/179| 
| 20210127 | 为Hyper-V“网桥”进行模糊测试-第1部分：Windows Driver Foundation（WDF）编写硬件驱动程序介绍。 | https://www.alex-ionescu.com/?p=377| 
| 20210127 | 当黑客不讲武德之国内安全专家也容易被社工分析研究。 | https://paper.seebug.org/1471/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210127 | 从弱口令到拿下站群服务器 | https://www.hetianlab.com/specialized/20210119110943| 
| 20210127 | 浅谈Springboot中的文件上传 | https://www.sec-in.com/article/836| 
| 20210127 | 自动化的攻击溯源之痛 ：数据获取与关联的困惑 | https://mp.weixin.qq.com/s/dJDHLvJOGVPQB1cfTayX9w| 
| 20210127 | 如何开源手动挖掘LinkedIn领英 | https://mp.weixin.qq.com/s/mtQ40m7qLayUDxgmWgsWPw| 
| 20210127 | 互联网产品数据与隐私合规审查要点 | https://mp.weixin.qq.com/s/m_8Y3x-DzoWNwU8tBT-ENw| 
| 20210127 | 一次挖矿入侵处理记录 | https://github.com/bg6cq/ITTS/blob/master/security/mine/README.md| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210127T23:20:37Z | CVE-2021-3156 | CVE-2021-3156 | https://github.com/reverse-ex/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character:| 
| 20210127T22:16:53Z | CVE-2021-3156 | This simple bash script will patch the recently discovered sudo heap overflow vulnerability. | https://github.com/elbee-cyber/CVE-2021-3156-PATCHER | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character:| 
| 20210127T21:16:52Z | CVE-2021-3156 | CVE-2021-3156 | https://github.com/ymrsmns/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character:| 
| 20210127T18:21:50Z | cve-2021-3156 | Null | https://github.com/nexcess/sudo_cve-2021-3156 | 未查询到CVE信息| 
| 20210127T10:23:27Z | CVE-2021-3129 | Exploit for CVE-2021-3129 | https://github.com/nth347/CVE-2021-3129-exploit | Ignition before 2.5.2, as used in Laravel and other products, allows unauthenticated remote attackers to execute arbitrary code because of insecure usage of file_get_contents() and file_put_contents(). This is exploitable on sites using debug mode with Laravel before 8.4.2.| 
| 20210127T08:29:37Z | CVE-2021-3129 | Laravel debug rce | https://github.com/SNCKER/CVE-2021-3129 | Ignition before 2.5.2, as used in Laravel and other products, allows unauthenticated remote attackers to execute arbitrary code because of insecure usage of file_get_contents() and file_put_contents(). This is exploitable on sites using debug mode with Laravel before 8.4.2.| 
| 20210127T06:32:10Z | CVE-2020-14882 | CVE-2020-14882部署冰蝎内存马 | https://github.com/ShmilySec/CVE-2020-14882 | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210127T06:26:17Z | CVE-2021-3129 | Null | https://github.com/crisprss/Laravel_CVE-2021-3129_EXP | Ignition before 2.5.2, as used in Laravel and other products, allows unauthenticated remote attackers to execute arbitrary code because of insecure usage of file_get_contents() and file_put_contents(). This is exploitable on sites using debug mode with Laravel before 8.4.2.| 
| 20210127T01:22:30Z | CVE-2020-9484 | Null | https://github.com/AssassinUKG/CVE-2020-9484 | When using Apache Tomcat versions 10.0.0-M1 to 10.0.0-M4, 9.0.0.M1 to 9.0.34, 8.5.0 to 8.5.54 and 7.0.0 to 7.0.103 if a) an attacker is able to control the contents and name of a file on the server; and b) the server is configured to use the PersistenceManager with a FileStore; and c) the PersistenceManager is configured with sessionAttributeValueClassNameFilter=%null% (the default unless a SecurityManager is used) or a sufficiently lax filter to allow the attacker provided object to be deserialized; and d) the attacker knows the relative file path from the storage location used by FileStore to the file the attacker has control over; then, using a specifically crafted request, the attacker will be able to trigger remote code execution via deserialization of the file under their control. Note that all of conditions a) to d) must be true for the attack to succeed.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210127T22:52:40Z | Null | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210127T15:26:16Z | Null | https://github.com/jiseongg/klee_experiment | 0 | 0| 
| 20210127T15:25:22Z | Null | https://github.com/fontworks-fonts/Klee | 335 | 10| 
| 20210127T13:43:29Z | Null | https://github.com/kleelab/kleelab.github.io | 0 | 0| 
| 20210127T10:21:46Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1618 | 479| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210127T23:49:00Z | This project exploited data generated using the Spotify API, in order to classify songs by their musical genre and to predict the popularity of a song by analysing its features | https://github.com/Louis-Bahrman/Spotify-Data-Analysis | 0 | 0| 
| 20210127T22:53:11Z | binary-exploitation-dev | https://github.com/EvaLovlac3/binary-exploitation-dev | 0 | 0| 
| 20210127T22:24:02Z | Null | https://github.com/MTK-bypass/exploits_collection | 29 | 17| 
| 20210127T22:18:15Z | Thi powershell script has got to run in remote windows host, even for pivoting | https://github.com/FabioDefilippo/winallenum | 0 | 1| 
| 20210127T22:03:50Z | Old and new CTFs about Linux kernel exploitation. | https://github.com/MaherAzzouzi/LinuxKernelExploitation | 1 | 0| 
| 20210127T21:28:55Z | Penetration testing / Exploitation framework | https://github.com/Ret2LC/BetterSploit | 3 | 1| 
| 20210127T21:23:36Z | Null | https://github.com/th3ken-dev/TH3KEN-EDITON | 2 | 0| 
| 20210127T20:12:44Z | A roblox exploit. | https://github.com/Eren-Bey/KingSploit-X | 0 | 0| 
| 20210127T20:08:02Z | Development of code to exploit LSST and VISTA imaging | https://github.com/lsst-uk/lsst-ir-fusion | 0 | 0| 
| 20210127T20:06:45Z | Exploitation techniques summarization | https://github.com/andrewbae/exploitation-techniques | 2 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210127T22:17:45Z | Analysis of SunBurst (SolarWinds) embedded backdoor | https://github.com/conikeec/sunburst-analysis | 1 | 1| 
| 20210127T21:33:03Z | Null | https://github.com/mikkelskov1/backdoor2 | 0 | 0| 
| 20210127T14:32:57Z | This is just for me ok! | https://github.com/GetRektBoy724/sementara | 1 | 0| 
| 20210127T09:40:57Z | Undetectable & Xor encrypting with custom KEY (FUD Metasploit Rat) bypass Top Antivirus like BitDefender,Malwarebytes,Avast,ESET-NOD32,AVG,... & Automatically Add ICON and MANIFEST to excitable | https://github.com/persianhydra/Xeexe-TopAntivirusEvasion | 271 | 76| 
| 20210127T08:52:23Z | Worlds simplest PHP backdoor | https://github.com/F-Masood/php-backdoors | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210127T23:51:42Z | Null | https://github.com/magic8347/fuzzy-octo-enigma | 0 | 0| 
| 20210127T23:18:36Z | A differential fuzzer for x86 decoders | https://github.com/trailofbits/mishegos | 124 | 17| 
| 20210127T22:02:24Z | Seminarski rad iz predmeta Računarska Inteligencija na Matematičkom fakultetu. | https://github.com/djanluka/FuzzyClassification | 0 | 0| 
| 20210127T21:58:56Z | Generate code for json encoders/decoders, codecs, fuzzers, generators, and more | https://github.com/MartinSStewart/elm-review-todo-it-for-me | 0 | 0| 
| 20210127T21:58:32Z | FuzzBench - Fuzzer benchmarking as a service. | https://github.com/google/fuzzbench | 589 | 97| 
| 20210127T21:49:06Z | Scalable fuzzing infrastructure. | https://github.com/google/clusterfuzz | 4424 | 410| 
| 20210127T21:38:50Z | To make fuzzing Rust easy | https://github.com/smoelius/test-fuzz | 0 | 0| 
| 20210127T21:17:49Z | Null | https://github.com/tonight84575/fuzzy-waddle | 0 | 0| 
| 20210127T21:14:15Z | Null | https://github.com/mujianahkintor/fuzzy-telegram | 0 | 0| 
| 20210127T21:11:37Z | Null | https://github.com/Sentinel-One/efi_fuzz | 60 | 7| 



# 日更新程序
