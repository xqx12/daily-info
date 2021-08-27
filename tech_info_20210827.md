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


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210827T08:27:41Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T06:49:41Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2664 | 68| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T12:13:43Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 147 | 37| 
| 20210827T11:04:27Z | Null | https://github.com/Chanel-B/S2E-STUDENT-COURSE | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T12:52:27Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 21 | 13| 
| 20210827T12:50:48Z | Some files for information security exploits | https://github.com/renatus-cartesius/infosec | 0 | 0| 
| 20210827T12:49:35Z | HEVD | https://github.com/ReJimp/Kernel_Exploit | 2 | 0| 
| 20210827T12:47:38Z | Auto IP range scanner & exploit tool for BlueKeep metasploit module | https://github.com/ind3p3nd3nt/BlueRDPSploit | 13 | 8| 
| 20210827T12:44:00Z | GigSploit  is a NO KEY Exploit Support owl hub and more! | https://github.com/REDSCRIPT3R/GigSploit- | 0 | 0| 
| 20210827T12:35:13Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9928 | 1659| 
| 20210827T12:34:41Z | A thread-safe Hash Table using Nvidia’s API for CUDA-enabled GPUs. 200 times faster than the C++ only code through sheer exploitation of a GPU’s fine-grained parallelism. | https://github.com/Miruna-Chi/CUDA-Hash-Table | 0 | 0| 
| 20210827T12:28:44Z | Detect common exploits | https://github.com/StarTux/Exploits | 1 | 0| 
| 20210827T12:15:29Z | The Browser Exploitation Framework Project | https://github.com/beefproject/beef | 5900 | 1397| 
| 20210827T12:14:12Z | 42 , Security project, 15 levels to discover securities exploits | https://github.com/thallard/snow-crash | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T11:41:08Z | pybotnet -   A Python Library for building Botnet , Trojan or BackDoor for windows and linux with Telegram control panel  | https://github.com/onionj/pybotnet | 13 | 8| 
| 20210827T09:49:08Z | Null | https://github.com/FreeLesio/WordPress-Backdoor | 0 | 0| 
| 20210827T05:52:41Z | A collection of python written hacking tools consisting of network scanner, arp spoofer and detector, dns spoofer, code injector, packet sniffer, network jammer, email sender, downloader, wireless password harvester credential harvester, keylogger, download&execute, and reverse_backdoor. | https://github.com/dmdhrumilmistry/pyhtools | 20 | 8| 
| 20210827T04:16:48Z | Backdoor Bellingham HTML/CSS project that highlights the beauty of the city of subdued excitement! | https://github.com/dwstrong5/Backdoor-Bellingham | 0 | 0| 
| 20210827T01:24:13Z | A LKM rootkit targeting 4.x and 5.x kernel versions which opens a backdoor that can be used to spawn a reverse shell to a remote host and more. | https://github.com/h3xduck/Umbra | 22 | 5| 
| 20210827T00:29:41Z | A simple backdoor and a listener | https://github.com/guilhermeortolano/Backdor | 0 | 0| 
| 20210827T00:19:58Z | Null | https://github.com/guilhermeortolano/backdoor | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T12:55:22Z | Symbolica%s open-source symbolic execution engine. | https://github.com/SymbolicaDev/Symbolica | 4 | 0| 
| 20210827T08:18:35Z | It is a repository for conducting symbolic execution on nodejs automatically | https://github.com/zheli-1/nodejs-sym-harness | 0 | 0| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T02:04:23Z | NDSS 2020 - HYPER-CUBE: High-Dimensional Hypervisor Fuzzing | https://github.com/RUB-SysSec/Hypercube | 8 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T13:18:00Z | Null | https://github.com/Hwangwoosam/fuzzing | 5 | 0| 
| 20210827T13:00:15Z | MS-fuzz data | https://github.com/Clingto/MS-Fuzz | 0 | 0| 
| 20210827T12:51:48Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210827T12:33:45Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2382 | 137| 
| 20210827T12:28:20Z | Hi thre, I%m TRÄW🤟🏻, i%m a beginner in ethical hacking and Content Creator on Level iv Security & NOOBSEC. I Spend most of time coding outstanding ethical hacking projects or recording useful short tutorials . I love programming ethical hacking tools, fuzzing and hacking all the things | https://github.com/0xTRAW/0xTRAW | 1 | 1| 
| 20210827T12:24:34Z | Gentoo overlay | https://github.com/lferra/fuzzy-potato | 0 | 0| 
| 20210827T12:15:12Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 22 | 9| 
| 20210827T12:03:14Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210827T11:45:18Z | Null | https://github.com/Kanzuxbdue/fuzzy-system | 0 | 0| 
| 20210827T11:41:36Z | Official Keras implementation of IEEE JBHI 2021 paper: %Choquet Integral and Coalition Game-based Ensemble of Deep Learning Models for COVID-19 Screening from Chest X-ray Images% | https://github.com/subhankar01/Covid-Chestxray-lambda-fuzzy | 1 | 3| 



# 日更新程序
