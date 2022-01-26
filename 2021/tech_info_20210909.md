# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210909 | Facebook 邮件泄露及账号接管漏洞分析 | https://rikeshbaniyaaa.medium.com/facebook-email-disclosure-and-account-takeover-ecdb44ee12e9| 
| 20210909 | New CPU side-channel attack takes aim at Chrome’s Site Isolation feature | https://therecord.media/new-cpu-side-channel-attack-takes-aim-at-chromes-site-isolation-feature/| 
| 20210909 | GitHub 提供的拼写检查 workflow 被发现存在漏洞，可以泄露 GITHUB_TOKEN API Key | https://github.com/justinsteven/advisories/blob/master/2021_github_actions_checkspelling_token_leak_via_advice_symlink.md| 
| 20210909 | Alles CTF 比赛中一个 macOS XPC 相关的 UAF 漏洞的分析及利用 | http://www.synacktiv.com/publications/macos-xpc-exploitation-sandbox-share-case-study.html| 
| 20210909 | Exploiting checkm8 with unknown SecureROM for the T2 chip | https://zeronights.ru/wp-content/uploads/2021/09/04_kovrizhnyh.pdf| 
| 20210909 | 利用 Opera 浏览器的 Stored XSS 漏洞实现本地文件读 | https://blogs.opera.com/security/2021/09/bug-bounty-guest-post-local-file-read-via-stored-xss-in-the-opera-browser/| 
| 20210909 | Yagi - 将 Ghidra decompiler 集成到 IDA 的工具 | https://github.com/airbus-cert/Yagi| 
| 20210909 | lsassy - 远程从 lsass dump 提取敏感凭据信息的工具 | https://github.com/Hackndo/lsassy| 
| 20210909 | Panda Dome Antivirus - Heap-Based Buffer Overflow Vulnerability | http://zeifan.my/security/heap/overflow/2021/09/08/panda-av-heap-overflow.html| 
| 20210909 | Khepri - Golang/C++ 语言写的一个跨平台的后渗透测试阶段的工具 | https://sec.today/pulses/0a75736d-c503-4d38-a972-073088bb59a2/| 
| 20210909 | Khepri - Golang/C++ 语言写的一个跨平台的后渗透测试阶段的工具 | https://github.com/geemion/Khepri| 
| 20210909 | Introduction to OWASP Top 10 2021 | https://owasp.org/Top10/| 
| 20210909 | macOS XPC 漏洞利用 - 沙盒分享案例研究。 | https://www.synacktiv.com/en/publications/macos-xpc-exploitation-sandbox-share-case-study.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210909 | IoT 恶意软件进化谱系研究 | https://mp.weixin.qq.com/s/xXYFcVOXA6lZfhign0BJlg| 
| 20210909 | Miara的延续--gafgyt病毒分析 | https://mp.weixin.qq.com/s/JYBdhxbt0mqU3wIqFFWdhQ| 
| 20210909 | HAProxy 场景绕过之一: CVE-2021-40346 | https://github.com/CHYbeta/OddProxyDemo/tree/master/haproxy/demo1| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210909T17:10:13Z | CVE-2021-40444 | Null | https://github.com/rfcxv/CVE-2021-40444-POC | 未查询到CVE信息| 
| 20210909T16:28:23Z | CVE-2020-9054 | CVE-2020-9054 PoC for Zyxel | https://github.com/darrenmartyn/CVE-2020-9054 | Multiple ZyXEL network-attached storage (NAS) devices running firmware version 5.21 contain a pre-authentication command injection vulnerability, which may allow a remote, unauthenticated attacker to execute arbitrary code on a vulnerable device. ZyXEL NAS devices achieve authentication by using the weblogin.cgi CGI executable. This program fails to properly sanitize the username parameter that is passed to it. If the username parameter contains certain characters, it can allow command injection with the privileges of the web server that runs on the ZyXEL device. Although the web server does not run as the root user, ZyXEL devices include a setuid utility that can be leveraged to run any command with root privileges. As such, it should be assumed that exploitation of this vulnerability can lead to remote code execution with root privileges. By sending a specially-crafted HTTP POST or GET request to a vulnerable ZyXEL device, a remote, unauthenticated attacker may be able to execute arbitrary code on the device. This may happen by directly connecting to a device if it is directly exposed to an attacker. However, there are ways to trigger such crafted requests even if an attacker does not have direct connectivity to a vulnerable devices. For example, simply visiting a website can result in the compromise of any ZyXEL device that is reachable from the client system. Affected products include: NAS326 before firmware V5.21(AAZF.7)C0 NAS520 before firmware V5.21(AASZ.3)C0 NAS540 before firmware V5.21(AATB.4)C0 NAS542 before firmware V5.21(ABAG.4)C0 ZyXEL has made firmware updates available for NAS326, NAS520, NAS540, and NAS542 devices. Affected models that are end-of-support: NSA210, NSA220, NSA220+, NSA221, NSA310, NSA310S, NSA320, NSA320S, NSA325 and NSA325v2| 
| 20210909T15:59:34Z | CVE-2020-25233 | Null | https://github.com/twentybel0w/CVE-2020-25233 | A vulnerability has been identified in LOGO! 8 BM (incl. SIPLUS variants) (All versions < V8.3). The firmware update of affected devices contains the private RSA key that is used as a basis for encryption of communication with the device.| 
| 20210909T15:12:30Z | CVE-2021- | Null | https://github.com/evildrummer/CVE-2021-XYZ2 | | 
| 20210909T14:51:42Z | CVE-2021- | Null | https://github.com/evildrummer/CVE-2021-XYZ | 未查询到CVE信息| 
| 20210909T12:56:56Z | CVE-2021-37678 | TP Seguridad Informática | https://github.com/fran-CICS/ExploitTensorflowCVE-2021-37678 | TensorFlow is an end-to-end open source platform for machine learning. In affected versions TensorFlow and Keras can be tricked to perform arbitrary code execution when deserializing a Keras model from YAML format. The [implementation](https://github.com/tensorflow/tensorflow/blob/460e000de3a83278fb00b61a16d161b1964f15f4/tensorflow/python/keras/saving/model_config.py#L66-L104) uses `yaml.unsafe_load` which can perform arbitrary code execution on the input. Given that YAML format support requires a significant amount of work, we have removed it for now. We have patched the issue in GitHub commit 23d6383eb6c14084a8fc3bdf164043b974818012. The fix will be included in TensorFlow 2.6.0. We will also cherrypick this commit on TensorFlow 2.5.1, TensorFlow 2.4.3, and TensorFlow 2.3.4, as these are also affected and still in supported range.| 
| 20210909T04:01:49Z | 未知编号 | Null | https://github.com/itom-qe/itom-qe-2021-09-08-T-21-09-456-cveaj | 未查询到CVE信息| 
| 20210909T02:37:51Z | CVE-2021-1590 | PoC for exploiting CVE-2021-1590 : A vulnerability in the implementation of the system login block-for command for Cisco NX-OS Software could allow an unauthenticated, remote attacker to cause a login process to unexpectedly restart, causing a denial of service (DoS) condition. This vulnerability is due to a logic error in the implementation of the system login block-for command when an attack is detected and acted upon. An attacker could exploit this vulnerability by performing a brute-force login attack on an affected device. A successful exploit could allow the attacker to cause a login process to reload, which could result in a delay during authentication to the affected device. | https://github.com/AlAIAL90/CVE-2021-1590 | | 
| 20210909T02:37:48Z | CVE-2021-1591 | PoC for exploiting CVE-2021-1591 : A vulnerability in the EtherChannel port subscription logic of Cisco Nexus 9500 Series Switches could allow an unauthenticated, remote attacker to bypass access control list (ACL) rules that are configured on an affected device. This vulnerability is due to oversubscription of resources that occurs when applying ACLs to port channel interfaces. An attacker could exploit this vulnerability by attempting to access network resources that are protected by the ACL. A successful exploit could allow the attacker to access network resources that would be protected by the ACL that was applied on the port channel interface. | https://github.com/AlAIAL90/CVE-2021-1591 | A vulnerability in the EtherChannel port subscription logic of Cisco Nexus 9500 Series Switches could allow an unauthenticated, remote attacker to bypass access control list (ACL) rules that are configured on an affected device. This vulnerability is due to oversubscription of resources that occurs when applying ACLs to port channel interfaces. An attacker could exploit this vulnerability by attempting to access network resources that are protected by the ACL. A successful exploit could allow the attacker to access network resources that would be protected by the ACL that was applied on the port channel interface.| 
| 20210909T02:37:45Z | CVE-2021-1592 | PoC for exploiting CVE-2021-1592 : A vulnerability in the way Cisco UCS Manager software handles SSH sessions could allow an authenticated, remote attacker to cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper resource management for established SSH sessions. An attacker could exploit this vulnerability by opening a significant number of SSH sessions on an affected device. A successful exploit could allow the attacker to cause a crash and restart of internal Cisco UCS Manager software processes and a temporary loss of access to the Cisco UCS Manager CLI and web UI. Note: The attacker must have valid user credentials to authenticate to the affected device. | https://github.com/AlAIAL90/CVE-2021-1592 | A vulnerability in the way Cisco UCS Manager software handles SSH sessions could allow an authenticated, remote attacker to cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper resource management for established SSH sessions. An attacker could exploit this vulnerability by opening a significant number of SSH sessions on an affected device. A successful exploit could allow the attacker to cause a crash and restart of internal Cisco UCS Manager software processes and a temporary loss of access to the Cisco UCS Manager CLI and web UI. Note: The attacker must have valid user credentials to authenticate to the affected device.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T18:24:52Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 14 | 45| 
| 20210909T11:06:54Z | Backend application for running static analysis of rust-based programs | https://github.com/LedgerProject/safepkt_backend | 0 | 1| 
| 20210909T11:06:44Z | Web application for running static analysis of rust-based programs | https://github.com/LedgerProject/safepkt | 0 | 1| 
| 20210909T09:03:31Z | Null | https://github.com/kleeenz/kleeenzapp | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T06:42:02Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 149 | 37| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T23:59:20Z | Book of Exploits I make  | https://github.com/joshmerr/exploitbook | 0 | 0| 
| 20210909T23:40:22Z | Repo to maintain Microsoft Cloud exploitation stuff. | https://github.com/ar0dd/LaListaDeMCA | 1 | 0| 
| 20210909T23:07:32Z | Repository for my talk %Crafting exploits, tools and havoc with Ruby% featured at Ruby Kaigi 2021. | https://github.com/MauroEldritch/rubycraft | 0 | 0| 
| 20210909T22:21:11Z | CTF framework and exploit development library | https://github.com/Gallopsled/pwntools | 8243 | 1438| 
| 20210909T22:03:44Z |  A collection of proof-of-concept exploits for publicly disclosed vulnerabilities discovered by the STM Cyber team. | https://github.com/STMCyber/CVEs | 0 | 0| 
| 20210909T21:49:30Z | PacketLimiter is a open-source packet limiter to fix minecraft exploits with version support for 1.7 to 1.17. | https://github.com/HakanGulgen/packetlimiter | 0 | 0| 
| 20210909T21:16:08Z | An R package of data from the Kootenay Lake Exploitation Study | https://github.com/poissonconsulting/klexdatr | 0 | 1| 
| 20210909T20:19:52Z | Null | https://github.com/zYan666/Demon-Exploit | 0 | 0| 
| 20210909T20:10:22Z | A list of fun things to do with DarkRP addons | https://github.com/OverlordAkise/darkrp-exploits | 0 | 0| 
| 20210909T19:01:27Z | Gonna share my writeups and resources here | https://github.com/jopraveen/exploit-development | 8 | 4| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T20:59:50Z | Esse script automatiza a criação de backdoors | https://github.com/H7XX/backdoor-creator | 0 | 0| 
| 20210909T20:36:50Z | Undetectable & Xor encrypting with custom KEY (FUD Metasploit Rat) bypass Top Antivirus like BitDefender,Malwarebytes,Avast,ESET-NOD32,AVG,... & Automatically Add ICON and MANIFEST to excitable | https://github.com/persianhydra/Xeexe-TopAntivirusEvasion | 549 | 126| 
| 20210909T20:16:15Z | Python botnet and backdoor | https://github.com/sweetsoftware/Ares | 1129 | 445| 
| 20210909T17:46:45Z | backdoor | https://github.com/Emilia-ZX/backdoor | 0 | 0| 
| 20210909T16:27:24Z | Something I wrote for CVE-2019-15107, a Webmin backdoor | https://github.com/darrenmartyn/CVE-2019-15107 | 0 | 0| 
| 20210909T07:13:07Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) remote administration and post-exploitation tool mainly written in python | https://github.com/n1nj4sec/pupy | 6549 | 1657| 
| 20210909T04:40:47Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 95 | 17| 
| 20210909T04:08:17Z | Backdoor Attacks on Lottery Ticket Hypothesis | https://github.com/zeyuanyin/LTH-Backdoor | 0 | 0| 
| 20210909T02:30:57Z | Remote control software | https://github.com/h1zzz/purewater | 0 | 0| 
| 20210909T02:21:54Z | https://51pwn.com,Awesome Penetration Testing，hacker tools collection, metasploit exploit, meterpreter....struts2、weblogic, 0day,poc,apt,backdoor,VulApps,vuln,pentest-script | https://github.com/hktalent/myhktools | 11 | 9| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T20:26:42Z | Symbolica%s open-source symbolic execution engine. | https://github.com/SymbolicaDev/Symbolica | 25 | 1| 
| 20210909T19:28:58Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1883 | 391| 
| 20210909T14:40:11Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 157 | 34| 
| 20210909T11:23:55Z | Symbolic-execution-based verifier for the Viper intermediate verification language. | https://github.com/viperproject/silicon | 20 | 12| 
| 20210909T08:43:09Z | A unit test-like interface for fuzzing and symbolic execution | https://github.com/trailofbits/deepstate | 654 | 65| 
| 20210909T08:17:50Z | RAUK: Automatic Schedulability Analysis of RTIC Applications Using Symbolic Execution | https://github.com/markhakansson/master-thesis | 5 | 0| 
| 20210909T06:42:02Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 149 | 37| 
| 20210909T04:20:56Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2448 | 362| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T13:41:06Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 22 | 4| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T22:54:39Z | Null | https://github.com/Altair-Bueno/fuzzy-disco | 0 | 1| 
| 20210909T22:42:09Z | A REST API written using Python 3 and Flask, making use of Elasticsearch. | https://github.com/lethalazo/fuzzy-search-API | 1 | 0| 
| 20210909T22:20:23Z | Mayhem fuzzme templates for programming languages and fuzzers that you love! | https://github.com/ForAllSecure/fuzzme | 0 | 0| 
| 20210909T22:19:52Z | An investigation of American Fuzzy Lop++ as a fuzzer | https://github.com/hark130/hardy-remix | 0 | 0| 
| 20210909T21:36:57Z | Null | https://github.com/MrZMN/FuzzyKey | 1 | 0| 
| 20210909T21:34:39Z | Null | https://github.com/chu-data-lab/AutomaticFuzzyJoin | 7 | 1| 
| 20210909T21:29:19Z | Small script written in python3 to perform LFI Fuzzer attack. Please do not use it for unethical or illegal activities I do not responsible any of those things. This is educational purposes only. BTW... it can be used in CTFs of course | https://github.com/LaptopKing/lfifuzzer | 0 | 0| 
| 20210909T21:23:09Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210909T20:55:23Z | Sound and Cost-effective Fuzzing of Stripped Binaries by Incremental and Stochastic Rewriting | https://github.com/ZhangZhuoSJTU/StochFuzz | 88 | 3| 
| 20210909T20:54:46Z | Fuzzy String Matching in Python | https://github.com/seatgeek/fuzzywuzzy | 8487 | 873| 



# 日更新程序
