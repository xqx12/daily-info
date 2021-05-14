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
| 20210514T11:57:17Z | CVE-2021-21551 | Exploit to SYSTEM for CVE-2021-21551 | https://github.com/waldo-irc/CVE-2021-21551 | Dell dbutil_2_3.sys driver contains an insufficient access control vulnerability which may lead to escalation of privileges, denial of service, or information disclosure. Local authenticated user access is required.| 
| 20210514T09:57:36Z | CVE-2021-21300 | CVE-2021-21300 | https://github.com/tao-sun2/CVE-2021-21300 | Git is an open-source distributed revision control system. In affected versions of Git a specially crafted repository that contains symbolic links as well as files using a clean/smudge filter such as Git LFS, may cause just-checked out script to be executed while cloning onto a case-insensitive file system such as NTFS, HFS+ or APFS (i.e. the default file systems on Windows and macOS). Note that clean/smudge filters have to be configured for that. Git for Windows configures Git LFS by default, and is therefore vulnerable. The problem has been patched in the versions published on Tuesday, March 9th, 2021. As a workaound, if symbolic link support is disabled in Git (e.g. via `git config --global core.symlinks false`), the described attack won%t work. Likewise, if no clean/smudge filters such as Git LFS are configured globally (i.e. _before_ cloning), the attack is foiled. As always, it is best to avoid cloning repositories from untrusted sources. The earliest impacted version is 2.14.2. The fix versions are: 2.30.1, 2.29.3, 2.28.1, 2.27.1, 2.26.3, 2.25.5, 2.24.4, 2.23.4, 2.22.5, 2.21.4, 2.20.5, 2.19.6, 2.18.5, 2.17.62.17.6.| 
| 20210514T08:03:43Z | CVE-2021-2021 | This is a good projects. | https://github.com/TheCryingGame/CVE-2021-2021good | Vulnerability in the MySQL Server product of Oracle MySQL (component: Server: Optimizer). Supported versions that are affected are 8.0.22 and prior. Easily exploitable vulnerability allows high privileged attacker with network access via multiple protocols to compromise MySQL Server. Successful attacks of this vulnerability can result in unauthorized ability to cause a hang or frequently repeatable crash (complete DOS) of MySQL Server. CVSS 3.1 Base Score 4.9 (Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:U/C:N/I:N/A:H).| 
| 20210514T05:44:37Z | CVE-2021-2109 | weblogic CVE-2021-2109批量验证poc | https://github.com/yuaneuro/CVE-2021-2109_poc | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows high privileged attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 7.2 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H).| 
| 20210514T00:51:39Z | CVE-2020-8813 | Null | https://github.com/m4udSec/Cacti-CVE-2020-8813 | graph_realtime.php in Cacti 1.2.8 allows remote attackers to execute arbitrary OS commands via shell metacharacters in a cookie, if a guest user has the graph real-time privilege.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210514T10:17:40Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 589 | 14| 
| 20210514T07:39:11Z | Null | https://github.com/KLeelaSantosh/kleeelasantosh | 0 | 0| 
| 20210514T07:36:46Z | Null | https://github.com/KLeelaSantosh/kleela | 0 | 0| 
| 20210514T07:34:25Z | Null | https://github.com/KLeelaSantosh/Kleelasan | 0 | 0| 
| 20210514T06:43:01Z | An opiniated Next TypeScript powered starter which include Klee, emotion / styled-system, framer motion, jest and Cypress | https://github.com/Liinkiing/next-ts-klee-starter | 0 | 0| 
| 20210514T05:13:19Z | Config files for my GitHub profile. | https://github.com/KLeelaSantosh/KLeelaSantosh | 0 | 0| 
| 20210514T02:46:06Z | Null | https://github.com/fontworks-fonts/Klee | 444 | 13| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210514T02:29:03Z | cicd logic and gitlab&github runner&jenkins agent container, centos base ,whith jdk/python/go, maven/npm,/kubectl/helm | https://github.com/chimeh/cicd-s2e-runner | 1 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210514T11:58:16Z | Scheme flooding vulnerability: how it works and why it is a threat to anonymous browsing | https://github.com/fingerprintjs/external-protocol-flooding | 86 | 3| 
| 20210514T11:02:47Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 22 | 10| 
| 20210514T10:56:08Z | A Python program implementing and exploiting the Minsky Turing machine considered in the paper %Intrinsic Propensity for Vulnerability in Computers? Arbitrary Code Execution in the Universal Turing Machine% as per CVE-2021-32471 (https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32471) | https://github.com/intrinsic-propensity/turing-machine | 31 | 1| 
| 20210514T10:46:51Z | Null | https://github.com/setzer17/exploit | 0 | 0| 
| 20210514T10:39:08Z | The Lost Nintendo DS Television Output, brought back to life | https://github.com/LostNintendoHistory/Lost-NDS-TV | 237 | 12| 
| 20210514T10:08:19Z | CDK is an open-sourced container penetration toolkit, offering stable exploitation in different slimmed containers without any OS dependency. It comes with penetration tools and many powerful PoCs/EXPs helps you to escape container and takeover K8s cluster easily. | https://github.com/cdk-team/CDK | 1394 | 205| 
| 20210514T10:05:42Z | linux post-exploitation framework made by linux user | https://github.com/jm33-m0/emp3r0r | 462 | 86| 
| 20210514T09:37:59Z | 📈 A visualization of MetricQ data exploiting the advantages of the HTA db backend  | https://github.com/metricq/metricq-webview | 0 | 1| 
| 20210514T09:28:52Z | [CVPR 2021] Exploiting Edge-Oriented Reasoning for 3D Point-based Scene Graph Analysis | https://github.com/chaoyivision/SGGpoint | 0 | 0| 
| 20210514T09:09:30Z | Null | https://github.com/SP0x0K/Binary-Exploitation-Templates | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210514T01:16:20Z | This is a test project to know how it works a backdoor and how can we protect our PC , please take care and do not use for bad intentions. | https://github.com/Mariana-Saory-GA/backdoorattempt | 0 | 0| 
| 20210514T00:56:28Z | Null | https://github.com/Simon-Lozada/Backdoor_Python | 0 | 0| 
| 20210514T00:06:29Z | Gmod Backdoor Scanner Written in C++ | https://github.com/ProtoGrace/Gmod-Backdoor-Scanner | 9 | 3| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210514T02:02:11Z | Custom link shortner | https://github.com/appukuttan66/fuzzy-invention | 0 | 0| 
| 20210514T01:39:55Z | Fast web fuzzer written in Go | https://github.com/ffuf/ffuf | 4482 | 523| 
| 20210514T01:16:44Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 1| 
| 20210514T01:10:34Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 281 | 38| 
| 20210514T00:40:44Z | Null | https://github.com/qviet1602/fuzzy_matching | 0 | 0| 
| 20210514T00:11:27Z | Null | https://github.com/aplawson7707/fuzzy_matching | 0 | 0| 
| 20210514T00:06:41Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 6 | 5| 



# 日更新程序
