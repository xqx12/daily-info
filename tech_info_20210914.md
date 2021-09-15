# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210914 | BinDiff 二进制比较简介 | https://mp.weixin.qq.com/s/fPjqO_L5aHxzVUu8GtIgeA| 
| 20210914 | Apple 发布 iOS 14.8 版本更新 | https://support.apple.com/en-us/HT212807| 
| 20210914 | 利用 Root-Cause Clustering 的方案实现 Fuzz 过程中 Crash 样本的去重 | https://nebelwelt.net/files/21CCS.pdf| 
| 20210914 | VaultFuzzer: A state-based approach for Linux kernel | https://www.reddit.com/r/netsec/comments/pnedi0/vaultfuzzer_a_statebased_approach_for_linux_kernel/| 
| 20210914 | Go 语言实现的跨平台 CobaltStrike Beacon | https://github.com/darkr4y/geacon| 
| 20210914 | Oracle BI XML XXE 漏洞分析 | https://testbnull.medium.com/linh-tinh-v%E1%BB%81-oracle-business-intelligence-part-1-5a050b48a193| 
| 20210914 | 通过分析 NSO Group Pegasus 间谍软件，CitizenLab 发现了一个针对 iMessage 的 Zero-Click 0Day Exploit - FORCEDENTRY，Apple 今天发布补丁更新修复该漏洞 | https://citizenlab.ca/2021/09/forcedentry-nso-group-imessage-zero-click-exploit-captured-in-the-wild/| 
| 20210914 | Hacking CloudKit - 因 CloudKit 使用不当，导致可以删除 Apple Shortcuts | https://labs.detectify.com/2021/09/13/hacking-cloudkit-how-i-accidentally-deleted-your-apple-shortcuts/| 
| 20210914 | [复现] 8月30日 Cream 被攻击事件 | https://paper.seebug.org/1709/| 
| 20210914 | 浅析 Hacking Team 新活动 | https://paper.seebug.org/1711/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210914 | 谈谈网络空间“行为测绘” | https://mp.weixin.qq.com/s/THEdOpSu_bSPWo66sRDyPA| 
| 20210914 | VaultFuzzer: 针对Linux内核的状态导向模糊测试方案 | https://mp.weixin.qq.com/s/ZevJBJjANmBLPCG0RyC3eg| 
| 20210914 | fapro: 协议模拟服务器 | https://github.com/fofapro/fapro| 
| 20210914 | 攻击推理-安全知识图谱应用的困境思考 | https://mp.weixin.qq.com/s/DOfrD7SGpoXP--zZPzf5bg| 
| 20210914 | goblin: 一款适用于红蓝对抗中的仿真钓鱼系统 | https://github.com/xiecat/goblin| 
| 20210914 | 网络空间资产安全管理实践与创新 | https://mp.weixin.qq.com/s/3NWI-_qJZfTuqvFl3d2SAQ| 
| 20210914 | Xcheck之PHP代码安全检查 | https://mp.weixin.qq.com/s?__biz=Mzg2ODQ3ODE1NA==&mid=2247483818&idx=1&sn=f55330a128035ba29cc8f1eca2c56230&chksm=ceaafc0ff9dd7519397f4dc0f710c3901ad7b76436dbc7accbfc1a543c702f49dabefa0d7ea5&token=654851123&lang=zh_CN#rd| 
| 20210914 | URL FIlter 绕过 - Python 之 Django | https://github.com/CHYbeta/URLFilterBypassDemo/tree/master/python/django_demo| 
| 20210914 | 检测浏览器是否存在代理 | https://github.com/ttttmr/checkproxy| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210914T20:02:42Z | 未知编号 | Scans Microsoft office documents for malicious xml entries | https://github.com/InfoSecPolkCounty/CVE2021-40444-document-Scanner | 未查询到CVE信息| 
| 20210914T19:23:22Z | CVE-2021-3156 | CVE-2021-3156: Sudo heap overflow exploit for Debian 10 | https://github.com/0xdevil/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210914T16:18:44Z | CVE-2021-24741 | Multiple SQL Inejection Vulnerability in Support Board Version 3.3.3 that allow remote unauthenticated attacker to execute arbitrary SQL commands via status_code, department, user_id, conversation_id, conversation_status_code, and recipient_id parameters to ajax.php which is connected to functions.php which the vulnerability is present. | https://github.com/itsjeffersonli/CVE-2021-24741 | 未查询到CVE信息| 
| 20210914T13:56:49Z | CVE-2021-40444 | partly working PoC, check lockedbytes PoC for full experience! | https://github.com/js-on/CVE-2021-40444 | 未查询到CVE信息| 
| 20210914T11:39:01Z | CVE-2021-24499 | Mass exploitation of CVE-2021-24499 unauthenticated upload leading to remote code execution in Workreap theme. | https://github.com/RyouYoo/CVE-2021-24499 | The Workreap WordPress theme before 2.2.2 AJAX actions workreap_award_temp_file_uploader and workreap_temp_file_uploader did not perform nonce checks, or validate that the request is from a valid user in any other way. The endpoints allowed for uploading arbitrary files to the uploads/workreap-temp directory. Uploaded files were neither sanitized nor validated, allowing an unauthenticated visitor to upload executable code such as php scripts.| 
| 20210914T08:18:40Z | cve-2021-40444 | Null | https://github.com/Immersive-Labs-Sec/cve-2021-40444-analysis | | 
| 20210914T06:44:49Z | CVE-2021-40845 | AlphaWeb XE, the embedded web server running on AlphaCom XE, has a vulnerability which allows to upload PHP files leading to RCE once the authentication is successful. | https://github.com/ricardojoserf/CVE-2021-40845 | 未查询到CVE信息| 
| 20210914T03:21:25Z | CVE-2021-32202 | CVE-2021-32202 | https://github.com/l00neyhacker/CVE-2021-32202 | In CS-Cart version 4.11.1, it is possible to induce copy-paste XSS by manipulating the %post description% filed in the blog post creation page.| 
| 20210914T03:17:26Z | CVE-2021-36582 | CVE-2021-36582 | https://github.com/l00neyhacker/CVE-2021-36582 | In Kooboo CMS 2.1.1.0, it is possible to upload a remote shell (e.g., aspx) to the server and then call upon it to receive a reverse shell from the victim server. The files are uploaded to /Content/Template/root/reverse-shell.aspx and can be simply triggered by browsing that URL.| 
| 20210914T03:12:30Z | CVE-2021-36581 | CVE-2021-36581 | https://github.com/l00neyhacker/CVE-2021-36581 | Kooboo CMS 2.1.1.0 is vulnerable to Insecure file upload. It is possible to upload any file extension to the server. The server does not verify the extension of the file and the tester was able to upload an aspx to the server.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210914T18:52:11Z | Null | https://github.com/klee669/klee.github.io | 0 | 0| 
| 20210914T14:48:27Z | Null | https://github.com/kleemeo/kleemeo.github.io | 0 | 0| 
| 20210914T14:35:19Z | KLEE with floating point support (unmaintained) | https://github.com/srg-imperial/klee-float | 12 | 14| 
| 20210914T08:49:57Z | Config files for my GitHub profile. | https://github.com/kleefr1/kleefr1 | 0 | 0| 
| 20210914T07:06:29Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1776 | 505| 
| 20210914T04:33:53Z | Assets to be used for linking, wget-uploads and Gists. | https://github.com/lahiri-phdworks/Assets | 0 | 0| 
| 20210914T01:33:58Z | Null | https://github.com/ioliu/klee | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210914T09:35:45Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 148 | 37| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210914T23:58:31Z | Rewritten exploits and automated scripts | https://github.com/jclel/tools | 0 | 0| 
| 20210914T23:49:49Z | CVE-2018-15473 Exploit | https://github.com/MrDottt/CVE-2018-15473 | 0 | 0| 
| 20210914T23:35:30Z | Proof of concept code for the BranchSpec exploit. | https://github.com/fanyao/branchspec | 2 | 4| 
| 20210914T23:30:47Z | lxd privilege escalation exploit with an alpine image encoded inside lxd-privesc-exploit. (Privilege escalation resultant in root access)  | https://github.com/0bfxgh0st/lxd-privesc-exploit | 0 | 0| 
| 20210914T22:48:39Z | Exploit Development and Reverse Engineering with GDB Made Easy | https://github.com/pwndbg/pwndbg | 3953 | 566| 
| 20210914T22:23:57Z | Desenvolvendo exploits x86 para linux | https://github.com/git-cardoso/Desenvolvimento_exploits_x86 | 0 | 0| 
| 20210914T22:18:32Z | A malicious JavaScript script that exploit XSS vulnerabilities in a modern way using steganography technique and Telegram. | https://github.com/nwqda/snitchyScript | 0 | 0| 
| 20210914T22:05:58Z | Pseudo shells for different Lambda Runtime Environments & Lambda persistency exploits | https://github.com/Djkusik/Lambda-sHell | 0 | 0| 
| 20210914T21:40:41Z | I found a way to exploit the rotation minecraft applies to certain Blocks to reconstruct coordinates from them | https://github.com/DerBejijing/BlockRotationExploit | 6 | 0| 
| 20210914T21:28:33Z | writeups of challenges in Exploit Education  | https://github.com/talsim/Exploit-Education | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210914T23:54:55Z | Python Backdoor Detection Model Based on Combined Features | https://github.com/das-lab/PBDT | 0 | 0| 
| 20210914T23:38:10Z | THCA WebShell Backdoor | https://github.com/anonsecteaminc/THCA | 0 | 0| 
| 20210914T21:35:09Z | LeuxBackdoor 0.9 xd | https://github.com/Lali346/LeuxBackdoor-0.9 | 0 | 0| 
| 20210914T18:37:51Z | kumpulan shell backdoor | https://github.com/anggixxx1/backdoor | 0 | 1| 
| 20210914T17:57:38Z | A collection of python written hacking tools consisting of network scanner, arp spoofer and detector, dns spoofer, code injector, packet sniffer, network jammer, email sender, downloader, wireless password harvester credential harvester, keylogger, download&execute, ransomware and reverse_backdoor. | https://github.com/dmdhrumilmistry/pyhtools | 21 | 8| 
| 20210914T17:16:48Z | This is a Backdoor, Created with Python. | https://github.com/JohnTR13/Backdoor | 0 | 0| 
| 20210914T15:11:10Z | Unofficial pytorch implementation of RobNet(Defense-Resistant Backdoor Attacks on DNN) | https://github.com/dhkim2810/RobNet | 0 | 0| 
| 20210914T13:56:19Z | e | https://github.com/Torono909/lunacore.backdoor | 0 | 0| 
| 20210914T13:39:22Z | Null | https://github.com/ccxmIcal/Discord-Bot-Controlled-Backdoor | 0 | 0| 
| 20210914T12:36:17Z | This is an advanced backdoor, created with Python | https://github.com/Senc3951/Backdoor | 2 | 1| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210914T12:10:28Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 157 | 34| 
| 20210914T11:58:36Z | RAUK: Automatic Schedulability Analysis of RTIC Applications Using Symbolic Execution | https://github.com/markhakansson/master-thesis | 5 | 0| 
| 20210914T09:35:45Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 148 | 37| 
| 20210914T07:06:29Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1776 | 505| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210914T02:29:51Z | NDSS 2020 - HYPER-CUBE: High-Dimensional Hypervisor Fuzzing | https://github.com/RUB-SysSec/Hypercube | 12 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210914T23:03:41Z | Null | https://github.com/AmeliaYeah/dns-host-directory-fuzz | 0 | 0| 
| 20210914T21:56:46Z | An investigation of American Fuzzy Lop++ as a fuzzer | https://github.com/hark130/hardy-remix | 0 | 0| 
| 20210914T21:51:44Z | Null | https://github.com/tmwatchanan/FuzzySets.jl | 0 | 0| 
| 20210914T21:39:53Z | Examples to stand up demo infrastructure | https://github.com/mikelaramie/fuzzy-bassoon | 0 | 0| 
| 20210914T21:38:25Z | Repo para TP #4 de PIAPC | https://github.com/hernanbrue/HB_fuzzy | 0 | 0| 
| 20210914T20:10:01Z | Calculating regression of large datasets using FCM clustering algorithm to aproximate and reduce data set size. | https://github.com/margawron/FuzzyRegression | 0 | 0| 
| 20210914T20:02:36Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210914T19:37:01Z | Gentoo overlay | https://github.com/lferra/fuzzy-potato | 0 | 0| 
| 20210914T18:54:04Z | Repo for a personal website using blogdown | https://github.com/mntzj/fuzzy-potato | 0 | 0| 
| 20210914T18:35:23Z | Null | https://github.com/becsun/fuzzy-barnacle | 0 | 0| 



# 日更新程序
