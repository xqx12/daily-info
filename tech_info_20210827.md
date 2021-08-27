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
| 20210827T12:28:44Z | Detect common exploits | https://github.com/StarTux/Exploits | 1 | 0| 
| 20210827T12:27:45Z | Auto IP range scanner & exploit tool for BlueKeep metasploit module | https://github.com/ind3p3nd3nt/BlueRDPSploit | 13 | 8| 
| 20210827T12:16:28Z | HEVD | https://github.com/ReJimp/Kernel_Exploit | 2 | 0| 
| 20210827T12:15:29Z | The Browser Exploitation Framework Project | https://github.com/beefproject/beef | 5900 | 1397| 
| 20210827T12:14:12Z | 42 , Security project, 15 levels to discover securities exploits | https://github.com/thallard/snow-crash | 0 | 0| 
| 20210827T12:07:44Z | A thread-safe Hash Table using Nvidia’s API for CUDA-enabled GPUs. 200 times faster than the C++ only code through sheer exploitation of a GPU’s fine-grained parallelism. | https://github.com/Miruna-Chi/CUDA-Hash-Table | 0 | 0| 
| 20210827T12:03:01Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 29 | 15| 
| 20210827T11:58:50Z | 🎣    Fish for line detections by exploiting the known velocity structure of the disk. | https://github.com/richteague/gofish | 8 | 6| 
| 20210827T11:51:06Z | some hacking tools that I wrote | https://github.com/Alekseyyy/InfoSec | 0 | 2| 
| 20210827T11:45:41Z | Color philosophy has a long past of screening that certain colors are related to certain dispositions which will also touch how patients feel. The investigation shows these possessions are professed by those who have to be in the space and the lengthier they’re in the space the more the color touches them. Since dispositions have been related to vicissitudes in levels of strain and strain levels have been related to the probability of better handling hostile circumstances like shock or illness. High strain levels have also been related to the expansion of new complaints, so dropping strain while in retrieval spaces will be helpful. Before you resolve on the colors and designs for your ICU Curtains, you need to reflect two issues: color / design strength and the senses of the color / design selections. What Do the Colors & Designs Mean? There are well-established senses for insignia, and there are no correct or wrong selections when it comes to colors / designs, even mixed or assorted colors can evoke the same reaction of both of their parent colors. For instance, a mixed blue / green pattern on a curtain made by ICU Curtains Manufacturers in India will bring out moods related with blue and those related with green. Use these senses to help you pick the perfect color or design curtain made by ICU Curtains Manufacturers for your space: Oranges speak to contentment Greens characteristically make people think of cash and flora, this generates vigor in space and comfort Blues remind us of amity and serenity, which is good for soothing patients Yellows are a joyful color which provokes vitality and vigor Reds are an exploit color which can make patients feel brave and conclusive It’s informal to see how you can create dissimilar dispositions for your patients selecting exact colors and designs for your curtains that are available with ICU Curtains Suppliers. Opposing Curtain Injury  While it may seem common intelligence to stock your ICU Curtains in parts that won’t cause harm, it isn’t continually so clear. Many hidden opponents of ICU Curtains prowl in storing parts and storerooms. Let’s look at a few shared areas where injury can happen.  High Dampness Parts This is an informal one to evade. You don’t want to stock your curtains bought from ICU Curtains Suppliers in India in storerooms or lodgings where the heat varies to excesses and produces at times high humidity. This surge in dampness can damage the curtains and in some cases totally extinguish them.  Wire Shelving It is common to find medicinal grade stainless steel cable shelving or stands in storing areas, but on some of these sills you’ll find bulging metal that has the latent to catch and slash your ICU Curtains when positioned or detached on those sills.   Obstacles Another part where problems and tears can happen is in tight accommodations or in storing areas that have other apparatus such as IV barrows with shafts that can easily clasp the draperies when being detached and harm or totally wreck them. By safeguarding that your ICU Curtains stay in perfect state you’ll be able to keep prices down on the price of possessions as well as the labor in assembling, getting and reinstating.  If you are looking for an ICU Curtains product directory, please log onto Ozahub. | https://github.com/OzahubNew/How-ICU-Curtains-Colors-Influence-Patients- | 0 | 0| 


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
| 20210827T10:44:04Z | Symbolica%s open-source symbolic execution engine. | https://github.com/SymbolicaDev/Symbolica | 4 | 0| 
| 20210827T08:18:35Z | It is a repository for conducting symbolic execution on nodejs automatically | https://github.com/zheli-1/nodejs-sym-harness | 0 | 0| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T02:04:23Z | NDSS 2020 - HYPER-CUBE: High-Dimensional Hypervisor Fuzzing | https://github.com/RUB-SysSec/Hypercube | 8 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210827T12:22:24Z | Hi thre, I%m TRÄW🤟🏻, i%m a beginner in ethical hacking and Content Creator on Level iv Security & NOOBSEC. I Spend most of time coding outstanding ethical hacking projects or recording useful short tutorials . I love programming ethical hacking tools, fuzzing and hacking all the things | https://github.com/0xTRAW/0xTRAW | 1 | 1| 
| 20210827T12:15:12Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 22 | 9| 
| 20210827T12:03:14Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210827T11:45:18Z | Null | https://github.com/Kanzuxbdue/fuzzy-system | 0 | 0| 
| 20210827T11:41:36Z | Official Keras implementation of IEEE JBHI 2021 paper: %Choquet Integral and Coalition Game-based Ensemble of Deep Learning Models for COVID-19 Screening from Chest X-ray Images% | https://github.com/subhankar01/Covid-Chestxray-lambda-fuzzy | 1 | 3| 
| 20210827T11:29:23Z | MATLAB code for the paper titled %A Self-Adaptive Fuzzy Learning System for Streaming Data Prediction%. | https://github.com/Gu-X/Self-Adaptive-Fuzzy-Learning-System | 0 | 0| 
| 20210827T11:17:58Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6580 | 1349| 
| 20210827T11:05:14Z | Property-based grey-box fuzzing for Multicore OCaml | https://github.com/ocaml-multicore/parafuzz | 3 | 0| 
| 20210827T10:17:22Z | Fuzzing tool for the 14th institute | https://github.com/Radon10043/fuzzing-tool-14 | 0 | 2| 
| 20210827T10:15:55Z | Rapid fuzzy string matching in Python using various string metrics | https://github.com/maxbachmann/RapidFuzz | 1030 | 46| 



# 日更新程序
