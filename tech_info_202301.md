# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230104 | MuddyWater APT组织总结 | https://socradar.io/dark-web-profile-muddywater-apt-group/| 
| 20230104 | Powershell后漏洞利用脚本 | http://securityonline.info/powermeup-powershell-scripts-for-post-exploitation/| 
| 20230104 | 关于hackvent2022 15-21 day的writeup,主要是一些信号分析,取证,密码,pwn的题目 | https://0xdf.gitlab.io/hackvent2022/hard| 
| 20230104 | PyTorch 遭到依赖混淆供应链攻击，请删除2022/12/25~12/30这一时间段的安装包并重新下载最新版本 | https://thehackernews.com/2023/01/pytorch-machine-learning-framework.html| 
| 20230104 | N-Day RCE Exploit for ZDI-17-836 (CVE-2017-12561),CVE-2017-12561的分析和利用 比较详细 适合学习 | http://primalcerebral.com/blog/egregious-mage-nday-rce-exploit-zdi-17-836.php| 
| 20230104 | Bhyve是FreeBSD的hypervisor,本篇文章将描述如何将适配器模拟器中有限的OOB写入漏洞转化为代码执行,从而允许逃逸 | https://www.synacktiv.com/publications/escaping-from-bhyve.html| 
| 20230103 | Faraday CTF 2022 Write-up，以一道ctf题为例介绍mips架构下的iot漏洞利用技巧，适合初学者学习 | https://www.reddit.com/r/ReverseEngineering/comments/101iozj/reverse_engineering_and_exploiting_an_iot_bug/| 
| 20230103 | Hexacon 2022会议中《More Tales from the iOS/macOS Kernel Trenches》议题slide，其中提及了CVE-2022-22640、CVE-2022-32821漏洞的原理等详细信息及利用技术。 | https://github.com/potmdehex/slides/blob/main/Hexacon_2022_More_Tales_from_the_iOS_macOS_Kernel_Trenches.pdf| 
| 20230103 | Esi注入相关的几个真实漏洞case study | https://infosecwriteups.com/exploring-the-world-of-esi-injection-b86234e66f91?gi=d40322198891&source=rss----7b722bfd1b8d---4| 
| 20230103 | vbSparkle:反混淆VBS和VBA macro的工具 | https://github.com/airbus-cert/vbSparkle| 
| 20230103 | 使用BinDiff分析复现群晖NAS一个严重栈溢出漏洞，并使用栈迁移+ROP完成利用实现RCE | http://paper.seebug.org/2038/| 
| 20230102 | 基于Ghidra和GPT-3的辅助逆向工具 | https://github.com/moyix/gpt-wpre| 
| 20230102 | modreveal 找出当前Linux机器的隐藏Linux内核模块的工具 | https://github.com/jafarlihi/modreveal| 
| 20230102 | 介绍 8086 处理器指令预取技术的电路实现 | http://www.righto.com/2023/01/inside-8086-processors-instruction.html| 
| 20230101 | LuaJIT Sandbox Escape: The Saga Ends | https://0xbigshaq.github.io/2022/12/30/luajit-sandbox-escape/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230104 | 卡巴斯基深度报告：从俄乌战争重新评估网络战 | https://mp.weixin.qq.com/s/-qGn-mQBaptREToko3iC0Q| 
| 20230103 | SecWiki周刊（第461期) | https://www.sec-wiki.com/weekly/461| 
| 20230102 | 2022太空安全报告 | https://mp.weixin.qq.com/s/N8kTUz11C2aAsZyYk85r4g| 
| 20230102 | 实时缺陷定位 | https://mp.weixin.qq.com/s/YngEu1mHECLvqlEiyQywZA| 
| 20230101 | 云原生安全系列（二）, 利用K8s污点容忍度横向移动主节点 | https://mp.weixin.qq.com/s/OC88N93BopEdiJqe_ttcqQ| 
| 20230101 | SLEUTH：基于COTS审计数据的实时攻击场景重构 | https://mp.weixin.qq.com/s/0zgoFUn1R3mS5m3UCOaYSg| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230105T01:33:13Z | CVE-2022-4876 | A vulnerability was found in Kaltura mwEmbed up to 2.96.rc1 and classified as problematic. This issue affects some unknown processing of the file includes/DefaultSettings.php. The manipulation of the argument HTTP_X_FORWARDED_HOST leads to cross site scripting. The attack may be initiated remotely. Upgrading to version CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4876 | | 
| 20230104T23:22:08Z | CVE-2021-4302 | A vulnerability was found in slackero phpwcms up to 1.9.26. It has been classified as problematic. This affects an unknown part of the component SVG File Handler. The manipulation leads to cross site scripting. It is possible to initiate the attack remotely. Upgrading to version 1.9.27 is able to address this issue. Th CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-4302 | | 
| 20230104T23:21:59Z | CVE-2023-22466 | Tokio is a runtime for writing applications with Rust. Starting with version 1.7.0 and prior to versions 1.18.4, 1.20.3, and 1.23.1, when configuring a Windows named pipe server, setting `pipe_mode` will reset `reject_remote_clients` to `false`. If the application has previously configured `reject_remote_clients` to `t CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-22466 | | 
| 20230104T23:21:51Z | CVE-2022-4875 | A vulnerability has been found in fossology and classified as problematic. This vulnerability affects unknown code. The manipulation of the argument sql/VarValue leads to cross site scripting. The attack can be initiated remotely. The name of the patch is 8e0eba001662c7eb35f045b70dd458a4643b4553. It is recommended to a CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4875 | | 
| 20230104T23:21:46Z | CVE-2021-4300 | A vulnerability has been found in ghostlander Halcyon and classified as critical. Affected by this vulnerability is the function CBlock::AddToBlockIndex of the file src/main.cpp of the component Block Verification. The manipulation leads to improper access controls. The attack can be launched remotely. Upgrading to ver CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-4300 | | 
| 20230104T21:11:43Z | CVE-2023-0054 | Out-of-bounds Write in GitHub repository vim/vim prior to 9.0.1145. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0054 | | 
| 20230104T21:11:34Z | CVE-2022-45052 | A Local File Inclusion vulnerability has been found in Axiell Iguana CMS. Due to insufficient neutralisation of user input on the url parameter on the imageProxy.type.php endpoint, external users are capable of accessing files on the server. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-45052 | | 
| 20230104T20:08:44Z | CVE-2022-46456 | NASM v2.16 was discovered to contain a global buffer overflow in the component dbgdbg_typevalue at /output/outdbg.c. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46456 | | 
| 20230104T20:08:40Z | CVE-2022-43920 | IBM Sterling B2B Integrator Standard Edition 6.0.0.0 through 6.1.2.1 could allow an authenticated user to gain privileges in a different group due to an access control vulnerability in the Sftp server adapter. IBM X-Force ID: 241362. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-43920 | | 
| 20230104T20:08:34Z | CVE-2022-25926 | Versions of the package window-control before 1.4.5 are vulnerable to Command Injection via the sendKeys function, due to improper input sanitization. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-25926 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230105T00:20:45Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 9772 | 335| 
| 20230104T08:05:39Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2134 | 603| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230102T14:07:04Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 285 | 66| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230104T23:13:19Z | Check bad character for binary exploitation. | https://github.com/Hein679/CheckBadCharacters | 0 | 0| 
| 20230104T22:53:11Z | Exploit Development and Reverse Engineering with GDB Made Easy | https://github.com/pwndbg/pwndbg | 5166 | 726| 
| 20230104T22:44:16Z | adds robux to roblox with easy extension | https://github.com/Jack55216/roblox-zero-day-exploit | 2 | 0| 
| 20230104T22:10:12Z | I%m trying to build a CVE and secret scanner better than Trivy and Aqua using Golang, Echo, MemDB (exploiting radix trees). | https://github.com/rajat965ng/findit | 0 | 0| 
| 20230104T17:31:22Z | This is a roblox exploit I made in 13 minutes and 25 seconds. | https://github.com/G0blinu/ytbexploit | 1 | 0| 
| 20230104T13:56:02Z | Gather and update all available and newest CVEs with their PoC. | https://github.com/trickest/cve | 3920 | 491| 
| 20230104T13:41:08Z | This repository is primarily maintained by Omar Santos (@santosomar) and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 12521 | 2151| 
| 20230104T13:38:33Z | Original PyTorch implementation of %BrainPrint: Identifying Individuals Exploiting a Semi-Self-Supervised Contrastive Framework Trained for Structural MRIs% | https://github.com/BrainPrint-project/BrainPrint | 0 | 0| 
| 20230104T13:13:40Z | The Browser Exploitation Framework Project | https://github.com/beefproject/beef | 8017 | 1852| 
| 20230104T13:10:53Z | A hacking tool to remotely exploit Android devices using ADB and get a Meterpreter session. | https://github.com/AzeemIdrisi/PhoneSploit-Pro | 1 | 1| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230104T23:31:05Z | A curated list of trustworthy deep learning papers. Daily updating... | https://github.com/MinghuiChen43/awesome-trustworthy-deep-learning | 102 | 13| 
| 20230104T16:19:40Z | Null | https://github.com/svenvandoornn/Backdoor-Detector | 0 | 0| 
| 20230104T15:56:31Z | The BackDoor of HIPHP gives you the power to control websites based on PHP using HTTP/HTTPS protocol. By sending files, tokens and commands through port 80%s POST/GET method, users can access a range of activities such as downloading and editing files. It also allows for connecting to Tor networks with password protection for extra security. | https://github.com/yasserbdj96/hiphp | 32 | 10| 
| 20230104T13:30:35Z | Full-featured C2 framework which silently persists on webserver with a single-line PHP backdoor | https://github.com/nil0x42/phpsploit | 1844 | 418| 
| 20230104T11:06:57Z | Fork of https://github.com/ThiccIndustries/Minecraft-Backdoor | https://github.com/Limitlesschicken/NCP-2 | 0 | 0| 
| 20230104T09:33:01Z | An enhanced version of icmpdoor | https://github.com/my-0day/icmp_backdoor_enhanced | 0 | 1| 
| 20230104T04:37:01Z | Un backdoor en python para termux , su uso no es mi responsabilidad ejecutar python2 server.py desde la maquina atacante configurar ip y puerto de la red local o para fuera de la red con ngrok tcp ,enviar herramienta a la victima usar ig social para que ejecute iniciar.sh. | https://github.com/MRX90902WX/Backdoor-Python | 0 | 0| 
| 20230104T03:10:02Z | Scanly is a docker image analysis CLI that aims to eliminate security backdoor/vulnerablities in Docker image hubs and stop host break outs inside workernodes and api servers by scanning for known CVEs and other security issues in the image layers. | https://github.com/DanielPickens/Scanly | 0 | 0| 
| 20230104T02:24:39Z | Reverse de la backdoor de AG derrière le packet Hello Telemetry. | https://github.com/adann0/ankabackdoor | 0 | 0| 
| 20230104T01:48:32Z | Null | https://github.com/knightcao/AI-BackDoor-Detection | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230104T21:26:02Z | Open-source symbolic execution framework: https://maat.re | https://github.com/trailofbits/maat | 528 | 30| 
| 20230104T11:10:30Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3262 | 460| 
| 20230104T04:10:26Z | A program that performs symbolic execution about all the possible paths a program written in a c-like language (SimpleC) can take. The output are formulas in CNF that represent the possible paths the program could generate, these formulas can be analyzed via a SAT solver.. | https://github.com/rndae/symbolic-execution-clikelang | 0 | 0| 
| 20230102T16:48:31Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 606 | 111| 
| 20230102T14:07:04Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 285 | 66| 
| 20230101T20:30:19Z | Template for a simple exercise involving Angr for symbolic execution. | https://github.com/nsumner/se-symex-template | 0 | 0| 
| 20230101T12:19:40Z | Files for http://blog.deniable.org/posts/symbolic-execution/ | https://github.com/houseofxyz/symbolic-execution | 0 | 0| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230103T18:15:20Z | The pre-processed Juliet, NDSS18 datasets for Assembly code summarization | https://github.com/L1NNA/Juliet-NDSS18-BinaryCodeSum | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230105T01:25:41Z | Null | https://github.com/soojeongi/fuzzy-engine | 0 | 0| 
| 20230104T23:06:04Z | Repositório de dados do projeto FuzzyNetClass | https://github.com/emmonks/FuzzyNetClass | 0 | 0| 
| 20230104T22:52:16Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 87 | 23| 
| 20230104T22:51:57Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8227 | 1792| 
| 20230104T22:29:24Z | Null | https://github.com/Mrfamou/fuzzy-funicular | 0 | 0| 
| 20230104T21:42:04Z | Null | https://github.com/Jbenitez0/fuzzy-disco | 0 | 0| 
| 20230104T15:34:40Z | A curated list of awesome Fuzzing(or Fuzz Testing) for software security | https://github.com/cpuu/awesome-fuzzing | 615 | 67| 
| 20230104T13:39:58Z | Coverage-guided, in-process fuzzing for the Node.js | https://github.com/CodeIntelligenceTesting/jazzer.js | 114 | 2| 
| 20230104T13:22:11Z | In this project we want to examine a hypothetical system for automatic car braking to describe the mechanism of fuzzy inference systems | https://github.com/arash-mehrzadi/fuzzy-car-accident-risk-predictor | 0 | 0| 
| 20230104T12:40:48Z | Null | https://github.com/TimothyElems/peach-fuzz | 0 | 0| 



# 日更新程序
