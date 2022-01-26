# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210827 | 在 Reader 角色中滥用 Azure Logic Apps 访问敏感信息 | https://www.netspi.com/blog/technical/cloud-penetration-testing/illogical-apps-exploring-exploiting-azure-logic-apps/?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+NetspiBlog+%28NetSPI+Blog%29| 
| 20210827 | 利用 ROP 链绕过 Linux 内核的 Linux Kernel Runtime Guard（LKRG）保护特性 | https://a13xp0p0v.github.io/2021/08/25/lkrg-bypass.html| 
| 20210827 | GDB 调试器的高级用法 | https://interrupt.memfault.com/blog/advanced-gdb| 
| 20210827 | Nyx: Greybox Hypervisor Fuzzing using Fast Snapshots and Affine Types（Paper） | https://github.com/RUB-SysSec/Nyx| 
| 20210827 | 利用 Trust Policy 访问模型的古老特性实现 AWS 的特权 | https://rzepsky.medium.com/aws-privilege-escalation-exploring-odd-features-of-the-trust-policy-7a970a32861| 
| 20210827 | RC4 与 Salsa20 加密算法的逆向 | https://www.goggleheadedhacker.com/blog/post/reversing-crypto-functions| 
| 20210827 | HITB 会议关于 Android 内核 UAF 漏洞利用的议题：The Art of Exploiting UAF by Ret2bpf in Android Kernel | https://conference.hitb.org/hitbsecconf2021sin/materials/D1T1%20-%20%20The%20Art%20of%20Exploiting%20UAF%20by%20Ret2bpf%20in%20Android%20Kernel%20-%20Xingyu%20Jin%20&%20Richard%20Neal.pdf| 
| 20210827 | 来自 HITB 会议的议题：Make JDBC Attack Brilliant Again | https://conference.hitb.org/hitbsecconf2021sin/materials/D1T2%20-%20Make%20JDBC%20Attacks%20Brilliant%20Again%20-%20Xu%20Yuanzhen%20&%20Chen%20Hongkun.pdf| 
| 20210827 | BlackHat USA 2021 洞察（三）：议题技术解读 | https://mp.weixin.qq.com/s/BCdN9KOFpCYUKQ_SNSgPPQ| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210827 | 全球高级持续性威胁（APT）2021年中报告 | https://ti.qianxin.com/uploads/2021/08/26/67c584e9e1e86a8dc3f40801f05eb981.pdf| 
| 20210827 | 车机硬件分析与固件提取 | https://mp.weixin.qq.com/s/IIqg3ePO6MNY-pxcpGYv1w| 
| 20210827 | 通过漏洞预测改进漏洞修复决策 | https://mp.weixin.qq.com/s/LOBnwPsYMNfLg9nkeeMi-w| 
| 20210827 | BloodHound：Six Degrees of Domain Admin | https://github.com/BloodHoundAD/BloodHound| 
| 20210827 | The Hacker Recipes 黑客实操笔记 | https://www.thehacker.recipes/| 
| 20210827 | 红队资料集锦 | https://blog.qwqdanchun.com/archives/414| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210827T21:28:19Z | cve-2021-21972 | Null | https://github.com/stevenp322/cve-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210827T19:25:06Z | CVE-2021-29447 | Null | https://github.com/AssassinUKG/CVE-2021-29447 | Wordpress is an open source CMS. A user with the ability to upload files (like an Author) can exploit an XML parsing issue in the Media Library leading to XXE attacks. This requires WordPress installation to be using PHP 8. Access to internal files is possible in a successful XXE attack. This has been patched in WordPress version 5.7.1, along with the older affected versions via a minor release. We strongly recommend you keep auto-updates enabled.| 
| 20210827T13:39:36Z | CVE-2020-15368 | How to exploit a vulnerable windows driver. Exploit for AsrDrv104.sys | https://github.com/stong/CVE-2020-15368 | | 
| 20210827T08:27:41Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T23:37:41Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2666 | 68| 
| 20210827T18:26:20Z | Null | https://github.com/Aredu89/Test-kleeen-demo | 0 | 0| 
| 20210827T13:59:49Z | a mirai bot | https://github.com/youfantan/KleeBot | 0 | 0| 
| 20210827T13:31:03Z | A RISC-V RV32 virtual prototype based on riscv-vp with symbolic execution support | https://github.com/agra-uni-bremen/symex-vp | 3 | 1| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T14:19:07Z | Null | https://github.com/Chanel-B/S2E-STUDENT-COURSE | 0 | 0| 
| 20210827T12:13:43Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 147 | 37| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T23:57:02Z | Null | https://github.com/TheCrazzXz/Exploits-Lab | 0 | 1| 
| 20210827T23:23:48Z | pwninit - automate starting binary exploit challenges | https://github.com/io12/pwninit | 213 | 12| 
| 20210827T23:17:44Z | Made small changes to the exploit such as removing the update patch screen and fixing some bugs. Using this exploit can get you banned on Roblox, I highly recommend using a paid executor like Synapse X. | https://github.com/EthanMcDonagh/VapeV4ForRoblox | 1 | 0| 
| 20210827T23:02:20Z | Discord UI for Roblox. Mainly used as an Exploit Library. | https://github.com/EthanMcDonagh/Discord-Library-Roblox | 1 | 0| 
| 20210827T22:56:54Z | Exploit for Bubble Gum Simulator that has many features such as Auto Hatch, Teleport to Islands, Auto Collect & More! | https://github.com/EthanMcDonagh/BubbleGumFuckerV1 | 1 | 0| 
| 20210827T22:30:12Z | Writeups on my TryHackMe adventures! | https://github.com/Sma-Das/TryHackMe | 7 | 0| 
| 20210827T21:58:50Z | The Ultimate Roblox Exploit by ferderplays | https://github.com/FERDdeveloper/SaugaHack | 1 | 0| 
| 20210827T21:57:49Z | Here I will post my solutions/exploits for some of the challenges on 0x0539.net | https://github.com/0x1CA3/0x0539 | 0 | 0| 
| 20210827T21:47:18Z | A Remote Code Execution Post Exploitation Framework via Exif Data in images | https://github.com/CalfCrusher/Exif-Maniac | 0 | 0| 
| 20210827T21:42:23Z | Python Pickle RCE Exploit + vulnerable Flask App | https://github.com/CalfCrusher/Python-Pickle-RCE-Exploit | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T21:56:17Z | A simple backdoor and a listener | https://github.com/guilhermeortolano/Backdor | 0 | 0| 
| 20210827T18:03:12Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 94 | 16| 
| 20210827T17:50:10Z | This is an advanced backdoor, created with Python | https://github.com/NoamHarush/Backdoor | 0 | 0| 
| 20210827T16:40:27Z | Kumpulan shell backdoor untuk sebuah website. | https://github.com/FahruGates/Shell-backdoor- | 0 | 0| 
| 20210827T14:11:37Z | Golang package for pentest | https://github.com/iIIusi0n/backkit | 3 | 0| 
| 20210827T13:52:22Z | Null | https://github.com/yungestdev/BackDoor | 0 | 0| 
| 20210827T11:41:08Z | pybotnet -   A Python Library for building Botnet , Trojan or BackDoor for windows and linux with Telegram control panel  | https://github.com/onionj/pybotnet | 13 | 8| 
| 20210827T09:49:08Z | Null | https://github.com/FreeLesio/WordPress-Backdoor | 0 | 0| 
| 20210827T05:52:41Z | A collection of python written hacking tools consisting of network scanner, arp spoofer and detector, dns spoofer, code injector, packet sniffer, network jammer, email sender, downloader, wireless password harvester credential harvester, keylogger, download&execute, and reverse_backdoor. | https://github.com/dmdhrumilmistry/pyhtools | 20 | 8| 
| 20210827T04:16:48Z | Backdoor Bellingham HTML/CSS project that highlights the beauty of the city of subdued excitement! | https://github.com/dwstrong5/Backdoor-Bellingham | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T20:18:33Z | Symbolic execution of LLVM IR with an engine written in Rust | https://github.com/PLSysSec/haybale | 325 | 16| 
| 20210827T17:56:00Z | Verifying constant-time code with symbolic execution | https://github.com/PLSysSec/haybale-pitchfork | 31 | 0| 
| 20210827T13:31:03Z | A RISC-V RV32 virtual prototype based on riscv-vp with symbolic execution support | https://github.com/agra-uni-bremen/symex-vp | 3 | 1| 
| 20210827T12:55:22Z | Symbolica%s open-source symbolic execution engine. | https://github.com/SymbolicaDev/Symbolica | 4 | 0| 
| 20210827T08:18:35Z | It is a repository for conducting symbolic execution on nodejs automatically | https://github.com/zheli-1/nodejs-sym-harness | 0 | 0| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T13:32:29Z | NDSS 2020 - HYPER-CUBE: High-Dimensional Hypervisor Fuzzing | https://github.com/RUB-SysSec/Hypercube | 7 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T23:58:32Z | SecLists is the security tester%s companion. It%s a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. | https://github.com/danielmiessler/SecLists | 33151 | 17230| 
| 20210827T23:01:12Z | This is a test task app. It compares hashes of opcode sequnce from dex files of chosen APKs using SSDeep algorithm | https://github.com/Dvasilets/TestTaskFuzzyHashSSDeep | 0 | 0| 
| 20210827T22:50:48Z | Null | https://github.com/oscarpimentel/fuzzy-torch | 1 | 0| 
| 20210827T22:48:47Z | Null | https://github.com/oscarpimentel/fuzzy-tools | 0 | 0| 
| 20210827T22:27:14Z | Code for fuzzy monkeys. | https://github.com/fuzzyatelin/fuzzyatelin.github.io | 3 | 9| 
| 20210827T21:31:51Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210827T20:58:19Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210827T20:09:56Z | Tools for fuzzing RDP | https://github.com/cyberark/rdpfuzz | 0 | 0| 
| 20210827T20:04:23Z | Null | https://github.com/Katheeravan305/Machine-Learning-and-Fuzzy-Logic-Module | 0 | 0| 
| 20210827T20:02:30Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 



# 日更新程序
