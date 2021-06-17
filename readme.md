# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210616 | 关于 Guacamole RCE 的那些事儿. | https://paper.seebug.org/1605/| 
| 20210616 | Windows Kernel Hijacking Is Not an Option: MemoryRanger Comes to the Rescue Again. | https://arxiv.org/abs/2106.06065| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210616 | HT2114 Telnet 服务暴力破解 new | https://tools.xazlsec.com/index.php/HT2110/242.html| 
| 20210616 | HT2111 SSH 服务暴力枚举 | https://tools.xazlsec.com/index.php/HT2110/231.html| 
| 20210616 | HT1223 Go 版指纹识别工具 Webanalyze | https://tools.xazlsec.com/index.php/HT1220/215.html| 
| 20210616 | HT1221 Web 应用信息收集工具 WIG | https://tools.xazlsec.com/index.php/HT1220/207.html| 
| 20210616 | HT1218 网络测绘系统利用 | https://tools.xazlsec.com/index.php/HT1210/203.html| 
| 20210616 | HT1216 Nmap 端口扫描工具 | https://tools.xazlsec.com/index.php/HT1210/192.html| 
| 20210616 | HT1213 脚本语言版端口扫描 | https://tools.xazlsec.com/index.php/HT1210/173.html| 
| 20210616 | HT1211 常见端口及服务信息 | https://tools.xazlsec.com/index.php/HT1210/168.html| 
| 20210616 | HT1161 Github 信息泄漏 | https://tools.xazlsec.com/index.php/HT1160/163.html| 
| 20210616 | HT1152 Shodan 自动化利用 | https://tools.xazlsec.com/index.php/HT1150/158.html| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210616T23:29:52Z | CVE-2020-17522 | PoC for exploiting CVE-2020-17522 : When ORT (now via atstccfg) generates ip_allow.config files in Apache Traffic Control 3.0.0 to 3.1.0 and 4.0.0 to 4.1.0, those files include permissions that allow bad actors to push arbitrary content into and remove arbitrary content from CDN cache servers. Additionally, these permissions are potentially extended to IP addresses outside the desired range, resulting in them being granted to clients possibly outside the CDN arcitechture. | https://github.com/PwnCast/CVE-2020-17522 | When ORT (now via atstccfg) generates ip_allow.config files in Apache Traffic Control 3.0.0 to 3.1.0 and 4.0.0 to 4.1.0, those files include permissions that allow bad actors to push arbitrary content into and remove arbitrary content from CDN cache servers. Additionally, these permissions are potentially extended to IP addresses outside the desired range, resulting in them being granted to clients possibly outside the CDN arcitechture.| 
| 20210616T17:03:54Z | CVE-2021-31166 | Proof of concept for CVE-2021-31166, a remote HTTP.sys use-after-free triggered remotely. | https://github.com/0vercl0k/CVE-2021-31166 | HTTP Protocol Stack Remote Code Execution Vulnerability| 
| 20210616T14:36:12Z | CVE-2021-3560 | Null | https://github.com/secnigma/CVE-2021-3560-Polkit-Privilege-Esclation | 未查询到CVE信息| 
| 20210616T12:01:04Z | CVE-2021-21975 | VMWare-CVE-2021-21975 SSRF vulnerability | https://github.com/Vulnmachines/VMWare-CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 
| 20210616T01:46:39Z | CVE-2021-3156 | Null | https://github.com/dock0d1/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210616T16:32:03Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 149 | 14| 
| 20210616T09:37:17Z | TracerX Symbolic Virtual Machine | https://github.com/tracer-x/TracerX | 15 | 9| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210616T23:54:34Z | php8.1.0 remote code execution | https://github.com/xansx/php8.1.0-exploit | 0 | 0| 
| 20210616T23:49:23Z | GEF - GDB Enhanced Features for exploit devs & reversers | https://github.com/hugsy/gef | 3676 | 511| 
| 20210616T23:29:59Z | PoC for exploiting CVE-2017-7670 : The Traffic Router component of the incubating Apache Traffic Control project is vulnerable to a Slowloris style Denial of Service attack. TCP connections made on the configured DNS port will remain in the ESTABLISHED state until the client explicitly closes the connection or Traffic Router is restarted. If connections remain in the ESTABLISHED state indefinitely and accumulate in number to match the size of the thread pool dedicated to processing DNS requests, the thread pool becomes exhausted. Once the thread pool is exhausted, Traffic Router is unable to service any DNS request, regardless of transport protocol. | https://github.com/PwnCast/CVE-2017-7670 | 0 | 0| 
| 20210616T23:29:52Z | PoC for exploiting CVE-2020-17522 : When ORT (now via atstccfg) generates ip_allow.config files in Apache Traffic Control 3.0.0 to 3.1.0 and 4.0.0 to 4.1.0, those files include permissions that allow bad actors to push arbitrary content into and remove arbitrary content from CDN cache servers. Additionally, these permissions are potentially extended to IP addresses outside the desired range, resulting in them being granted to clients possibly outside the CDN arcitechture. | https://github.com/PwnCast/CVE-2020-17522 | 0 | 0| 
| 20210616T23:18:28Z | DarkWare is a roblox exploit hub. | https://github.com/Yarik312/DarkWare | 1 | 0| 
| 20210616T23:04:44Z | Null | https://github.com/Zen-Hub-Exploits/Universal-Exploit-Hub | 0 | 0| 
| 20210616T22:42:47Z | Null | https://github.com/Exploit/Exploit | 0 | 3| 
| 20210616T22:41:55Z | RomBuster is a RomPager exploitation tool that allows to disclosure network device admin password. | https://github.com/EntySec/RomBuster | 10 | 1| 
| 20210616T22:41:27Z |  CamOver is a camera exploitation tool that allows to disclosure network camera admin password. | https://github.com/EntySec/CamOver | 3 | 2| 
| 20210616T22:41:08Z | CamRaptor is a tool that exploits several vulnerabilities in popular DVR cameras to obtain device credentials. | https://github.com/EntySec/CamRaptor | 3 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210616T23:11:51Z | Null | https://github.com/ouldevloper/python-backdoor | 0 | 0| 
| 20210616T22:57:12Z | Null | https://github.com/dhikmed/Undetectabe_Malware_Backdoor_C | 0 | 0| 
| 20210616T20:19:10Z | PHP Backdoor is a web-based application that allows to execute terminal commands on a server directly from a browser. | https://github.com/psyll/PHP-Backdoor | 1 | 0| 
| 20210616T18:56:02Z | simple reverse shell in python | https://github.com/Exo0001/simple-backdoor | 0 | 0| 
| 20210616T18:21:23Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/ghost | 1152 | 551| 
| 20210616T11:07:52Z | Null | https://github.com/ggpabuk/ExiledBackdoor | 0 | 0| 
| 20210616T01:13:52Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 249 | 43| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210616T23:50:35Z | LN-fuzz: State Sequence Network Protocol Fuzzer | https://github.com/setsal/LN-fuzz | 4 | 0| 
| 20210616T23:45:19Z | CBOR codec (in Go) with CBOR tags, Go struct tags (toarray/keyasint/omitempty), float64/32/16, big.Int, and fuzz tested billions of execs for reliable RFC 7049 & RFC 8949.  | https://github.com/fxamacker/cbor | 280 | 21| 
| 20210616T23:34:17Z | FuzzBench - Fuzzer benchmarking as a service. | https://github.com/google/fuzzbench | 650 | 120| 
| 20210616T23:21:19Z | RESTler is the first stateful REST API fuzzing tool for automatically testing cloud services through their REST APIs and finding security and reliability bugs in these services. | https://github.com/microsoft/restler-fuzzer | 891 | 92| 
| 20210616T23:06:54Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210616T22:42:49Z | Fuzzy Inference Systems package | https://github.com/jdvelasq/fuzzy_toolbox | 0 | 0| 
| 20210616T22:35:43Z | Fuzzer for the .NET toolchains, developed as a project for the 2018 Language-Based Security course at Aarhus University. | https://github.com/jakobbotsch/Fuzzlyn | 212 | 18| 
| 20210616T22:03:43Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 4 | 1| 
| 20210616T22:01:29Z | Bazel Starlark extensions for defining fuzz tests in Bazel projects | https://github.com/bazelbuild/rules_fuzzing | 36 | 8| 
| 20210616T21:55:34Z | Null | https://github.com/opimentel-github/fuzzy-tools | 0 | 0| 



# 日更新程序
