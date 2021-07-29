# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210729 | 针对 PyPI 市场 Python 软件包的静态安全分析（Paper） | https://arxiv.org/abs/2107.12699| 
| 20210729 | 利用 Falco 云安全工具缓解 Linux 文件系统 CVE-2021-33909 漏洞影响 | https://sysdig.com/blog/cve-2021-33909-sequoia-falco-linux-filesystem/| 
| 20210729 | Hyper-V vmswitch.sys CVE-2021-28476 RCE 漏洞分析 | https://www.guardicore.com/labs/critical-vulnerability-in-hyper-v-allowed-attackers-to-exploit-azure/| 
| 20210729 | 2021 Pwnie Award 奖的提名列表公布了 | https://pwnies.com/category/nominations/?y=2021| 
| 20210729 | SharpSphere - 通过 VMware Tools 与 vCenter 管理的虚拟机进行交互的渗透辅助工具 | https://jamescoote.co.uk/introducing-sharpsphere/| 
| 20210729 | NTLM relaying to AD CS - On certificates, printers and a little hippo | https://dirkjanm.io/ntlm-relaying-to-ad-certificate-services/| 
| 20210729 | JavaScriptCore 标准库的实现以及性能优化 | https://webkit.org/blog/11934/optimizing-javascript-standard-library-functions-in-jsc/| 
| 20210729 | ZDI 对 Windows GDI 子系统 CVE-2021-27077 漏洞的分析 | https://www.thezdi.com/blog/2021/7/26/cve-2021-27077-selecting-bitmaps-into-mismatched-device-contexts| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210729 | NPM软件包供应链攻击赏析 | https://mp.weixin.qq.com/s/PCPX4G9MucAMHH8pWpg6pQ| 
| 20210729 | 一个人怎么建立独立的思维框架和逻辑体系？ | https://www.zhihu.com/question/442047678/answer/1846239907| 
| 20210729 | 水泽-信息收集自动化工具 | https://github.com/0x727/ShuiZe_0x727| 
| 20210729 | 一场关于网络安全伦理审查的对话 | https://mp.weixin.qq.com/s/8NlY3I49UxDirA7Pe8h7Cw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210729T12:18:22Z | cve-2021-1480 | Null | https://github.com/xmco/sdwan-cve-2021-1480 | Multiple vulnerabilities in Cisco SD-WAN vManage Software could allow an unauthenticated, remote attacker to execute arbitrary code or allow an authenticated, local attacker to gain escalated privileges on an affected system. For more information about these vulnerabilities, see the Details section of this advisory.| 
| 20210729T10:02:13Z | CVE-2021-27965 | Proof of concept for CVE-2021-27965 (Stack-based Buffer Overflow) | https://github.com/Crystalware/CVE-2021-27965 | The MsIo64.sys driver before 1.1.19.1016 in MSI Dragon Center before 2.0.98.0 has a buffer overflow that allows privilege escalation via a crafted 0x80102040, 0x80102044, 0x80102050, or 0x80102054 IOCTL request.| 
| 20210729T09:28:22Z | CVE-2020-3452 | CISCO CVE-2020-3452 Scanner & Exploiter | https://github.com/darklotuskdb/CISCO-CVE-2020-3452-Scanner-Exploiter | A vulnerability in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct directory traversal attacks and read sensitive files on a targeted system. The vulnerability is due to a lack of proper input validation of URLs in HTTP requests processed by an affected device. An attacker could exploit this vulnerability by sending a crafted HTTP request containing directory traversal character sequences to an affected device. A successful exploit could allow the attacker to view arbitrary files within the web services file system on the targeted device. The web services file system is enabled when the affected device is configured with either WebVPN or AnyConnect features. This vulnerability cannot be used to obtain access to ASA or FTD system files or underlying operating system (OS) files.| 
| 20210729T08:25:46Z | CVE-2021- | Null | https://github.com/hanchen666/CVE-2021-XXXX | 未查询到CVE信息| 
| 20210729T08:24:46Z | CVE-2021-3560 | NYCY_homework_&_meeting | https://github.com/BizarreLove/CVE-2021-3560 | 未查询到CVE信息| 
| 20210729T06:47:23Z | CVE-2021-36934 | CVE-2021-36934 PowerShell Fix | https://github.com/tda90/CVE-2021-36934 | | 
| 20210729T04:51:30Z | CVE-2020-9014 | Proof of concept code for CVE-2020-9014 | https://github.com/Crystalware/CVE-2020-9014 | In Epson iProjection v2.30, the driver file (EMP_NSAU.sys) allows local users to cause a denial of service (BSOD) via crafted input to the virtual audio device driver with IOCTL 0x9C402402, 0x9C402406, or 0x9C40240A. \Device\EMPNSAUIO and \DosDevices\EMPNSAU are similarly affected.| 
| 20210729T04:13:11Z | CVE-2020-5248 | CVE-2020-5248 | https://github.com/Mkway/CVE-2020-5248 | GLPI before before version 9.4.6 has a vulnerability involving a default encryption key. GLPIKEY is public and is used on every instance. This means anyone can decrypt sensitive data stored using this key. It is possible to change the key before installing GLPI. But on existing instances, data must be reencrypted with the new key. Problem is we can not know which columns or rows in the database are using that; espcially from plugins. Changing the key without updating data would lend in bad password sent from glpi; but storing them again from the UI will work.| 
| 20210729T03:57:57Z | CVE-2021-3438 | Proof of concept code for CVE-2021-3438 | https://github.com/Crystalware/CVE-2021-3438 | A potential buffer overflow in the software drivers for certain HP LaserJet products and Samsung product printers could lead to an escalation of privilege.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210729T12:16:02Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2414 | 57| 
| 20210729T09:58:55Z | A RISC-V RV32 virtual prototype based on riscv-vp with symbolic execution support | https://github.com/agra-uni-bremen/symex-vp | 2 | 0| 
| 20210729T05:02:29Z | ⬇️ File Upload/sharing application, used by thousands of webmasters since 2007.  | https://github.com/kleeja-official/kleeja | 125 | 36| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210729T07:15:00Z | Null | https://github.com/Chanel-B/S2E_Projects | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210729T12:20:36Z | Null | https://github.com/Dolf7/Binary_Exploitation_1 | 0 | 0| 
| 20210729T12:09:09Z | Moving Object Segmentation in 3D LiDAR Data: A Learning-based Approach Exploiting Sequential Data (RAL/IROS 2021) | https://github.com/PRBonn/LiDAR-MOS | 115 | 17| 
| 20210729T12:06:56Z | Some simple python scripts that can be used to discover and exploit vulnerabilities  | https://github.com/shin0x/Python-Security-Scripts | 0 | 0| 
| 20210729T12:03:12Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 29 | 14| 
| 20210729T12:00:51Z | Blueborne CVE-2017-0781 Android heap overflow vulnerability | https://github.com/ojasookert/CVE-2017-0781 | 78 | 40| 
| 20210729T11:58:09Z | Model of resource exploitation of Iron Age communities in southwest Anatolia. To be presented at ReSoc conference | https://github.com/driesdaems10/Resoc | 1 | 1| 
| 20210729T11:44:26Z | E3C is a freely available multilingual corpus (Italian, English, French, Spanish, and Basque) of semantically annotated clinical narratives to allow for the linguistic analysis, benchmarking, and training of information extraction systems. It consists of two types of annotations: (i) clinical entities: pathologies, symptoms, procedures, body parts, etc., according to standard clinical taxonomies (i.e. SNOMED-CT, ICD-10); and (ii) temporal information and factuality: events, time expressions, and temporal relations according to the THYME standard. The corpus is organised into three layers, with different purposes. Layer 1: about 25K tokens per language with full manual annotation of clinical entities, temporal information and factuality, for benchmarkingand linguistic analysis. Layer 2: 50-100K tokens per language with semi-automatic annotations of clinical entities, to be used to train baseline systems. Layer 3: about 1M tokens per language of non-annotated medical documents to be exploited by semi-supervised approaches. Researchers can use the benchmark training and test splits of our corpus to develop and test their own models. We trained several deep learning based models and provide baselines using the benchmark. Both the corpus and the built models will be available through the ELG platform.  | https://github.com/hltfbk/E3C-Corpus | 0 | 1| 
| 20210729T11:12:54Z | PacketLimiter is a open-source packet limiter to fix minecraft exploits with version support for 1.7 to 1.17. | https://github.com/HakanGulgen/packetlimiter | 0 | 0| 
| 20210729T11:06:16Z | Exploiting a buffer overflow vulnerability with ROP chains. | https://github.com/kavishkagihan/ROP-Buffer-overflow | 0 | 0| 
| 20210729T11:04:00Z | Null | https://github.com/seapaddy/php-exploit | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210729T12:23:04Z | CredPhish is a PowerShell script designed to invoke legitimate credential prompts and exfiltrate passwords over DNS. | https://github.com/tokyoneon/CredPhish | 67 | 8| 
| 20210729T10:02:04Z | Here is the reverse_backdoor using reverse TCP model.It%s only for educational purpose not harm any device. | https://github.com/sainathreddy0207/reverse_backdoor | 0 | 0| 
| 20210729T09:15:54Z | Invisible, customizable backdoor for Minecraft Spigot Plugins. | https://github.com/ThiccIndustries/Minecraft-Backdoor | 20 | 6| 
| 20210729T08:27:04Z | Python AV Evasion Tools | https://github.com/G1ft3dC0d3/MsfMania | 189 | 45| 
| 20210729T07:49:48Z | The code of AAAI-21 paper Defending against Backdoors in Federated Learning with Robust Learning Rate. | https://github.com/TinfoilHat0/Defending-Against-Backdoors-with-Robust-Learning-Rate | 0 | 0| 
| 20210729T02:47:49Z | Simple multi client Backdoor, with Python. | https://github.com/zNairy/Sonaris | 6 | 0| 
| 20210729T02:40:38Z | Null | https://github.com/jjy1994/BackdoorSSL | 3 | 0| 
| 20210729T01:09:26Z | A batch script for taking information. A bit overdeveloped, and kind of useless. | https://github.com/Takaovi/BatchStealer | 11 | 2| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210729T10:41:45Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 153 | 33| 
| 20210729T10:12:17Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 17 | 3| 
| 20210729T10:11:24Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1852 | 388| 
| 20210729T09:58:55Z | A RISC-V RV32 virtual prototype based on riscv-vp with symbolic execution support | https://github.com/agra-uni-bremen/symex-vp | 2 | 0| 
| 20210729T09:13:56Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2402 | 354| 
| 20210729T08:49:54Z | Monster is a symbolic execution engine for 64-bit RISC-U code | https://github.com/cksystemsgroup/monster | 6 | 3| 
| 20210729T05:35:35Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1734 | 499| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210729T12:15:19Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 20 | 8| 
| 20210729T12:12:22Z | Null | https://github.com/epsonik/FuzzyDescV2 | 0 | 0| 
| 20210729T11:43:58Z | Lists to FUZZ the hack out of a target in a noisy way... | https://github.com/haxcited/xorcist | 0 | 0| 
| 20210729T11:16:26Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 3 | 1| 
| 20210729T10:56:39Z | Fuzzy Text watchface for Garmin devices | https://github.com/nels0nwu/fuzzy-text | 0 | 0| 
| 20210729T10:40:54Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210729T10:37:29Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210729T10:24:07Z | 针对小型应用服务搜索场景的工具包（也可部署为独立服务） | https://github.com/kc910521/MiniSearch | 5 | 0| 
| 20210729T10:21:02Z | Null | https://github.com/syi07030/incognito-project_web-fuzzing | 0 | 0| 
| 20210729T09:39:10Z | Null | https://github.com/anhduy0911/FuzzyPropose | 0 | 0| 



# 日更新程序
