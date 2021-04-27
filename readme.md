# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210427 | Alive2: Bounded Translation Validation for LLVM | http://www.cs.utah.edu/~regehr/alive2-pldi21.pdf| 
| 20210427 | Singular Security Lab 公开的 PPT。 | https://github.com/singularseclab/Slides| 
| 20210427 | 深入了解 QEMU 的工作原理，例如添加设备、中断、计时器等。 | https://airbus-seclab.github.io/qemu_blog/| 
| 20210427 | CVE-2021–28482（Microsoft Exchange Server 远程代码执行漏洞）的分析。 | https://testbnull.medium.com/microsoft-exchange-from-deserialization-to-post-auth-rce-cve-2021-28482-e713001d915f| 
| 20210427 | 利用 Windows 内置的工具进行横向渗透扫描。 | https://posts.slayerlabs.com/living-off-the-land/| 
| 20210427 | Wireshark 解密 RDP 流量的教程。 | https://unit42.paloaltonetworks.com/wireshark-tutorial-decrypting-rdp-traffic/| 
| 20210427 | CVE-2021-30657：由于 macOS 安全验证存在逻辑缺陷，未经签名和公证（Notarizing）的脚本或程序可以避开安全机制的检查。 | https://objective-see.com/blog/blog_0x64.html| 
| 20210427 | 苹果发布 iOS 14.5 和 macOS Big Sur 11.3 版本，修复多个高危漏洞，包括玄武实验室 Zhipeng Huo 和 Yuebin Sun 发现的3个漏洞。 | https://support.apple.com/zh-cn/HT212317| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210427T12:43:28Z | CVE-2021-26868 | Null | https://github.com/mavillon/CVE-2021-26868 | Windows Graphics Component Elevation of Privilege Vulnerability| 
| 20210427T12:21:49Z | CVE-2021-31221 | Indicator of Compromise Scanner for CVE-2021-31221  | https://github.com/fireaye/ioc-scanner-CVE-2021-31221 | 未查询到CVE信息| 
| 20210427T10:33:39Z | CVE-2021-3291 | rebuild cve | https://github.com/ImHades101/CVE-2021-3291 | Zen Cart 1.5.7b allows admins to execute arbitrary OS commands by inspecting an HTML radio input element (within the modules edit page) and inserting a command.| 
| 20210427T10:14:18Z | 未知编号 | CVE-2021-22192 | https://github.com/PetrusViet/Gitlab-RCE | 未查询到CVE信息| 
| 20210427T09:10:33Z | CVE-2021-22192 | CVE-2021-22192 靶场： 未授权用户 RCE 漏洞 | https://github.com/lyy289065406/CVE-2021-22192 | An issue has been discovered in GitLab CE/EE affecting all versions starting from 13.2 allowing unauthorized authenticated users to execute arbitrary code on the server.| 
| 20210427T08:27:04Z | 未知编号 | CVE-2021-1732 poc & exp; tested on 20H2 | https://github.com/Pai-Po/CVE-2021-1732 | 未查询到CVE信息| 
| 20210427T08:09:49Z | CVE-2021-1732 | Read my  blog for more info -  | https://github.com/exploitblizzard/Windows-Privilege-Escalation-CVE-2021-1732 | Windows Win32k Elevation of Privilege Vulnerability This CVE ID is unique from CVE-2021-1698.| 
| 20210427T08:07:39Z | CVE-2020-14883 | Alibaba-Nacos-Unauthorized/ApacheDruid-RCE_CVE-2021-25646/MS-Exchange-SSRF-CVE-2021-26885/Oracle-WebLogic-CVE-2021-2109_RCE/RG-CNVD-2021-14536/RJ-SSL-VPN-UltraVires/Redis-Unauthorized-RCE/TDOA-V11.7-GetOnlineCookie/VMware-vCenter-GetAnyFile/yongyou-GRP-U8-XXE/Oracle-WebLogic-CVE-2020-14883/Oracle-WebLogic-CVE-2020-14882/Apache-Solr-GetAnyFile/F5-BIG-IP-CVE-2021-22986/Sonicwall-SSL-VPN-RCE/GitLab-Graphql-CNVD-2021-14193/D-Link-DCS-CVE-2020-25078/WLAN-AP-WEA453e-RCE/360TianQing-Unauthorized/360TianQing-SQLinjection/FanWeiOA-V8-SQLinjection/QiZhiBaoLeiJi-AnyUserLogin/QiAnXin-WangKangFirewall-RCE/金山-V8-终端安全系统/NCCloud-SQLinjection/ShowDoc-RCE | https://github.com/Yang0615777/PocList | | 
| 20210427T03:31:23Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210427T03:23:26Z | cve-2021-11123 | 测试用的 | https://github.com/chenanu123/cve-2021-11123 | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210427T11:17:31Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 417 | 10| 
| 20210427T05:58:08Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 215 | 35| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210427T00:15:26Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 117 | 27| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210427T12:44:10Z | Learning shell scripting with a small exploiting tool created for a specific scenario. | https://github.com/iAgonyii/TheUltimateEdulabExploiter | 0 | 0| 
| 20210427T12:36:48Z | iblessing is an iOS security exploiting toolkit, it mainly includes application information collection, static analysis and dynamic analysis. It can be used for reverse engineering, binary analysis and vulnerability mining. | https://github.com/Soulghost/iblessing | 344 | 51| 
| 20210427T12:35:14Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9333 | 1509| 
| 20210427T12:29:57Z | Forestry Thematic Exploitation Platform | https://github.com/cgi-eoss/ftep | 5 | 0| 
| 20210427T12:17:45Z | 在科研（摸鱼）过程中，收集到的或者自己写的一些有用的（经过实战检验的）exp/poc，欢迎提交issue和PR | https://github.com/ycdxsb/Exploits | 2 | 0| 
| 20210427T12:09:22Z | Null | https://github.com/MTK-bypass/exploits_collection | 84 | 40| 
| 20210427T12:05:17Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 11 | 3| 
| 20210427T12:03:32Z | xcube is a Python package for generating and exploiting data cubes powered by xarray, dask, and zarr. | https://github.com/dcs4cop/xcube | 73 | 13| 
| 20210427T12:02:41Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 22 | 9| 
| 20210427T11:58:22Z | Null | https://github.com/Username132131231/exploit | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210427T12:34:52Z | Web Shell Backdoors Collection | https://github.com/PhenaxGod/Web-Shell-Backdoors | 0 | 0| 
| 20210427T10:50:50Z | A token logger for discord + steals Brave/Chrome passwords and usernames , I only made this for fun, so please don%t use it maliciously🙏 | https://github.com/CUPZYY/Backdoor-Machine | 1 | 0| 
| 20210427T09:33:28Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 227 | 38| 
| 20210427T09:09:40Z | Null | https://github.com/haehae00/backdoor | 0 | 0| 
| 20210427T04:30:26Z | Null | https://github.com/FelipeDosAnjos/HarpiaBackdoor | 0 | 0| 
| 20210427T03:59:34Z | generator of php_backdoor | https://github.com/Ki11i0n4ir3/backdoor-gen | 0 | 0| 
| 20210427T03:18:29Z | Backdoor Untuk Rce | https://github.com/ChokkaXploiter/azure | 1 | 0| 
| 20210427T02:26:22Z | Sample Blockchain Smart Contract Backdoor | https://github.com/MAYASEVEN/Sample-Blockchain-Smart-Contract-Backdoor | 1 | 0| 
| 20210427T01:35:13Z | Shell Backdoor. Credits to ph.luffy | https://github.com/PhenaxGod/Shell-Backdoor | 0 | 0| 
| 20210427T00:54:10Z | Arsnick is a Python IRC Bot/Backdoor written in Python | https://github.com/netzwerk/Arsnick | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210427T12:47:37Z | very advanced (web) fuzzer | https://github.com/d4rckh/vaf | 0 | 0| 
| 20210427T12:43:16Z | node.js implementation of a web fuzzer | https://github.com/aJesus37/njFuzz | 0 | 0| 
| 20210427T12:21:54Z | Fuzzy matching for Neovim | https://github.com/amirrezaask/fuzzy.nvim | 37 | 1| 
| 20210427T12:13:47Z | This is a Fuzzer library built in JS and nodeJS | https://github.com/fuzzing-unb/FuzzerJS | 0 | 0| 
| 20210427T12:09:32Z | Null | https://github.com/SuryaSD/Finding-Similar-Types-of-Names-Fuzzy-Search | 0 | 0| 
| 20210427T12:00:58Z | Ev description  | https://github.com/muz4151/fuzzy-succotash | 0 | 0| 
| 20210427T11:55:52Z | 渗透测试路径字典，爆破字典。内容来自互联网和实战积累。 | https://github.com/cpkkcb/fuzzDicts | 65 | 38| 
| 20210427T11:54:46Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 272 | 37| 
| 20210427T11:47:10Z | Null | https://github.com/HighlApp/spark-fuzzy | 0 | 0| 
| 20210427T11:40:05Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6233 | 1259| 



# 日更新程序
