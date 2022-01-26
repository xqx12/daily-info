# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210514 | Linux 内核 CAN 网络子系统 ISOTP CAN 协议本地提权漏洞分析 | https://github.com/nrb547/kernel-exploitation/blob/main/cve-2021-32606/cve-2021-32606.md| 
| 20210514 | 利用 Custom Protocol Handlers 实现跨浏览器的用户指纹跟踪 | https://fingerprintjs.com/blog/external-protocol-flooding/| 
| 20210514 | How we bypassed bytenode and decompiled Node.js bytecode in Ghidra | http://swarm.ptsecurity.com/how-we-bypassed-bytenode-and-decompiled-node-js-bytecode-in-ghidra/| 
| 20210514 | MOBISEC 2020 会议的议题 PPT 和视频公开了 | https://mobisec.reyammer.io/slides| 
| 20210514 | A tale of solving all the recent XSS challenges using chrome 1-day. | https://blog.s1r1us.ninja/CTF/site-isolation| 
| 20210514 | NVIDIA GeForce Experience 任意文件写漏洞的细节 | https://voidsec.com/nvidia-geforce-experience-command-execution/| 
| 20210514 | Pwn2Own VMware ESXi vmxnet3 漏洞背后的发现过程 | https://zerodayengineering.com/research/vmware-esxi-vmxnet3-from-patch-to-poc.html| 
| 20210514 | Metasploit 框架新加入了 DELL 固件更新驱动 dbutil_2_3.sys 提权漏洞的 Exploit | https://github.com/rapid7/metasploit-framework/pull/15190| 
| 20210514 | 兼容的代价：通过文件扩展属性攻陷macOS内核 | https://mp.weixin.qq.com/s/bfdwAhRRso34OOZrG2r65Q| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210514 | vulnhub: Momentum:1 | https://www.sec-in.com/article/1059| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210514T23:10:35Z | 未知编号 | A Python program implementing and exploiting the Minsky Turing machine considered in the paper "Intrinsic Propensity for Vulnerability in Computers? Arbitrary Code Execution in the Universal Turing Machine" as per CVE-2021-32471 (https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32471) | https://github.com/intrinsic-propensity/turing-machine | 未查询到CVE信息| 
| 20210514T17:15:24Z | CVE-2020-8813 | Null | https://github.com/m4udSec/Cacti-CVE-2020-8813 | 未查询到CVE信息| 
| 20210514T16:00:43Z | CVE-2020-28502 | CVE-2020-28502 node-XMLHttpRequest RCE | https://github.com/s-index/CVE-2020-28502 | | 
| 20210514T13:32:39Z | CVE-2021-21300 | CVE-2021-21300 | https://github.com/tao-sun2/CVE-2021-21300 | Git is an open-source distributed revision control system. In affected versions of Git a specially crafted repository that contains symbolic links as well as files using a clean/smudge filter such as Git LFS, may cause just-checked out script to be executed while cloning onto a case-insensitive file system such as NTFS, HFS+ or APFS (i.e. the default file systems on Windows and macOS). Note that clean/smudge filters have to be configured for that. Git for Windows configures Git LFS by default, and is therefore vulnerable. The problem has been patched in the versions published on Tuesday, March 9th, 2021. As a workaound, if symbolic link support is disabled in Git (e.g. via `git config --global core.symlinks false`), the described attack won%t work. Likewise, if no clean/smudge filters such as Git LFS are configured globally (i.e. _before_ cloning), the attack is foiled. As always, it is best to avoid cloning repositories from untrusted sources. The earliest impacted version is 2.14.2. The fix versions are: 2.30.1, 2.29.3, 2.28.1, 2.27.1, 2.26.3, 2.25.5, 2.24.4, 2.23.4, 2.22.5, 2.21.4, 2.20.5, 2.19.6, 2.18.5, 2.17.62.17.6.| 
| 20210514T08:03:43Z | CVE-2021-2021 | This is a good projects. | https://github.com/TheCryingGame/CVE-2021-2021good | Vulnerability in the MySQL Server product of Oracle MySQL (component: Server: Optimizer). Supported versions that are affected are 8.0.22 and prior. Easily exploitable vulnerability allows high privileged attacker with network access via multiple protocols to compromise MySQL Server. Successful attacks of this vulnerability can result in unauthorized ability to cause a hang or frequently repeatable crash (complete DOS) of MySQL Server. CVSS 3.1 Base Score 4.9 (Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:U/C:N/I:N/A:H).| 
| 20210514T05:44:37Z | CVE-2021-2109 | weblogic CVE-2021-2109批量验证poc | https://github.com/yuaneuro/CVE-2021-2109_poc | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows high privileged attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 7.2 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H).| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210514T23:02:07Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1690 | 492| 
| 20210514T20:24:17Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 14 | 43| 
| 20210514T19:01:54Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 590 | 14| 
| 20210514T17:34:32Z | Null | https://github.com/fontworks-fonts/Klee | 445 | 13| 
| 20210514T14:57:49Z | Null | https://github.com/KLeelaSantosh/kleelas | 0 | 0| 
| 20210514T07:39:11Z | Null | https://github.com/KLeelaSantosh/kleeelasantosh | 0 | 0| 
| 20210514T07:36:46Z | Null | https://github.com/KLeelaSantosh/kleela | 0 | 0| 
| 20210514T07:34:25Z | Null | https://github.com/KLeelaSantosh/Kleelasan | 0 | 0| 
| 20210514T06:43:01Z | An opiniated Next TypeScript powered starter which include Klee, emotion / styled-system, framer motion, jest and Cypress | https://github.com/Liinkiing/next-ts-klee-starter | 0 | 0| 
| 20210514T05:13:19Z | Config files for my GitHub profile. | https://github.com/KLeelaSantosh/KLeelaSantosh | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210514T02:29:03Z | cicd logic and gitlab&github runner&jenkins agent container, centos base ,whith jdk/python/go, maven/npm,/kubectl/helm | https://github.com/chimeh/cicd-s2e-runner | 1 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210514T23:48:19Z | My first Roblox GUI. | https://github.com/Remfly/remXskull-exploit | 1 | 0| 
| 20210514T23:46:29Z | Null | https://github.com/nenun/Web-Exploit-Scanner | 0 | 1| 
| 20210514T23:44:01Z | Exploits project Hacking Command Center | https://github.com/chacka0101/exploits | 5 | 6| 
| 20210514T23:23:21Z | labsecurity is a framework and its use is for ethical hacking and computer security | https://github.com/dylan14567/labsecurity | 1 | 3| 
| 20210514T23:21:30Z | Extensible framework for analyzing publicly available information about vulnerabilities | https://github.com/leonov-av/vulristics | 27 | 1| 
| 20210514T23:11:01Z | a deeper dive into exploiting the SHA-1 hashing algorithm | https://github.com/aabdelw1/length-extension-attack | 0 | 0| 
| 20210514T22:59:55Z | %The software will be building a network server from scratch that at startup will have the ability to selectively enable insecure portions of code that can be exploited. The software could be developed as a honeypot for detection of exploitation attempts within a network and/or as a practice server for pentesters.  The project may also need to develop companion software that can test the code, or collect logs from the server.% | https://github.com/TimHanneman/Multi_Purpose_Exploitable_Server | 0 | 0| 
| 20210514T22:46:41Z | source for the CSRF exploit possible on neverlose.cc | https://github.com/Sizzukie/csrf-neverlose.cc | 0 | 0| 
| 20210514T22:46:29Z | Blog consacré au Raspberry Pi. Au programme : des actualités, des tutoriels en français, des conseils, des projets, et bien plus pour exploiter le maximum de votre framboise ! | https://github.com/Skyost/FramboisePi | 0 | 0| 
| 20210514T22:38:02Z | Alpine Builder for pentest. Exploit lxd and docker group permission. | https://github.com/Seven-7Up/alpine-builderForPentest | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210514T21:22:53Z | Gmod Backdoor Scanner Written in C++ | https://github.com/ProtoGrace/Gmod-Backdoor-Scanner | 10 | 3| 
| 20210514T20:01:49Z | Null | https://github.com/Albeeeeeeeert/DevoFiler-uden-backdoors-og-fejl | 0 | 0| 
| 20210514T19:36:43Z | A demo and explanation of how a trojan backdoor attack can be performed on the classic MNIST experiment | https://github.com/adit-bala/Introduction-to-Trojans-in-AI | 0 | 0| 
| 20210514T19:05:04Z | Python 3 IRC Bot / Botnet | https://github.com/trackmastersteve/HackServ | 19 | 16| 
| 20210514T19:00:48Z | Null | https://github.com/narenmanoj/backdoor-adv-training | 0 | 0| 
| 20210514T16:39:55Z | Simple backdoor using lib python%s socket and subprocess for Windows | https://github.com/NoNameoN-A/Backdoor-Client-Server-Socket-Python | 3 | 1| 
| 20210514T16:23:41Z | Null | https://github.com/JiannanXiao6/backdoor | 0 | 0| 
| 20210514T15:31:00Z | This program is an non-object oriented opensource, hidden and undetectable backdoor/reverse shell/RAT for Windows made in Python 3 which contains many features such as multi-client support and cross-platform server. | https://github.com/xp4xbox/Python-Backdoor | 389 | 142| 
| 20210514T15:03:46Z | This is a simple backdoor for education purposes | https://github.com/Yegorius171/simple_backdoor | 0 | 0| 
| 20210514T12:56:43Z | Null | https://github.com/Simon-Lozada/Backdoor_Python | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210514T22:15:30Z | Rust based CAN bus fuzzer  | https://github.com/Rusty-CAN-Factory/rusty-can-fuzzer | 2 | 0| 
| 20210514T22:12:32Z | Fuzzer for Dolt repositories | https://github.com/dolthub/fuzzer | 1 | 0| 
| 20210514T21:53:55Z | Implementacija algoritama fuzzy klasterovanja, njihova primena na odredjenim skupovima podataka i uporedjivanje sa drugim algoritmima klasterovanja. | https://github.com/markobabic8/Fuzzy-clustering | 0 | 1| 
| 20210514T21:52:21Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 1735 | 341| 
| 20210514T21:33:11Z | Null | https://github.com/s9varesc/url-fuzzing | 1 | 1| 
| 20210514T21:19:46Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 281 | 38| 
| 20210514T20:26:43Z | A fuzzing platform for Zigbee protocol implementation | https://github.com/zigbeeprotocol/Z-Fuzzer | 2 | 0| 
| 20210514T20:19:55Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2328 | 125| 
| 20210514T20:11:59Z | Нейро-нечеткие системы | https://github.com/Blackbackofficial/neuro-fuzzy_systems | 0 | 0| 
| 20210514T19:31:31Z | fuzz Tor, OpenSSL and probably more using AFL++ | https://github.com/toralf/fuzz-utils | 0 | 0| 



# 日更新程序
