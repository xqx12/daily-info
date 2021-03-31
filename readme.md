# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210331 | Tavis 开源了一个测试 setuid 程序在资源受限环境运行行为的小工具 | https://github.com/taviso/scanlimits| 
| 20210331 | 微软发布的《Security baseline for Office 365 ProPlus》 | https://techcommunity.microsoft.com/t5/microsoft-security-baselines/security-baseline-for-office-365-proplus-v2103-march-2021-draft/ba-p/2228388| 
| 20210331 | Windows TPM 驱动（tpm.sys）信息泄露漏洞 PoC（CVE-2021-1656） | https://github.com/waleedassar/CVE-2021-1656| 
| 20210331 | Fuzzing 方向的 Paper 收集，按照细分的领域整理 | https://wcventure.github.io/FuzzingPaper/| 
| 20210331 | kCTF - Google 开源了一套基于 Kubernetes 的 CTF 基础设施搭建框架 | https://google.github.io/kctf/| 
| 20210331 | Fuzzing sockets: Apache HTTP, Part 2: Custom Interceptors | https://securitylab.github.com/research/fuzzing-apache-2/| 
| 20210331 | 利用 Wind Vision App 认证过程以及 IPC 通信过程的漏洞实现免费看数字电视 | https://labs.f-secure.com/blog/wind-vision-writeup/| 
| 20210331 | 卡巴斯基发了一篇针对 APT 10 组织近期 A41APT 攻击行动的分析报告 | https://securelist.com/apt10-sophisticated-multi-layered-loader-ecipekac-discovered-in-a41apt-campaign/101519/| 
| 20210331 | FluBot：一场席卷欧洲的移动银行木马攻击活动 | https://blogs.360.cn/post/analysis-of-FluBot.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210331 | 驱动病毒那些事(一)----基础 | https://www.sec-in.com/article/989| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210331T12:00:12Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210331T11:56:37Z | CVE-2021-1699 | POC for CVE-2021-1699 | https://github.com/waleedassar/CVE-2021-1699 | Windows (modem.sys) Information Disclosure Vulnerability| 
| 20210331T06:44:09Z | CVE-2021-3156 | Sudo Baron Samedit Exploit | https://github.com/worawit/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210331T06:01:30Z | CVE-2021-1656 | Null | https://github.com/waleedassar/CVE-2021-1656 | TPM Device Driver Information Disclosure Vulnerability| 
| 20210331T03:49:34Z | CVE-2021-26828 | Null | https://github.com/hevox/CVE-2021-26828_ScadaBR_RCE | 未查询到CVE信息| 
| 20210331T01:53:28Z | 未知编号 | Null | https://github.com/feihong-cs/Attacking_Shiro_with_CVE_2020_2555 | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210331T09:04:48Z | KLEE in the browser | https://github.com/klee/klee-web | 44 | 12| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210331T10:48:32Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 114 | 25| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210331T12:28:19Z | Automated All-in-One OS command injection and exploitation tool  can be used from web developers, penetration testers or even security   researchers in order to test web-based applications   with the view to find bugs, errors or vulnerabilities   related to command injection attacks.   Installation :  $ apt update && apt upgrade  $ apt install git   $ apt install python2  $ git clone https://github.com/commixproject/commix  $ cd commix  $ chmod +x *  usage :  $ python2 commix.py  Now it shows how you can use this too..  $ python2 commix.py -h   it shows all options...  $ python2 commix.py -u site.com  it shows all information.... | https://github.com/Zack-sys/Commix-Automated-All-in-One-OS-command-injection-ang-exploitation-tool | 6 | 0| 
| 20210331T12:21:01Z | A-Rat = Remote access tool  we can generate python based rat  installation :  $ apt update   $ apt upgrade  $ apt install git  $ apt install python2  $ apt install python  $ git clone https://github.com/Xi4u7/A-Rat  $ cd A-Rat  $ chmod +x *  usage :  $ python2 A-Rat.py  $ help  $ set host 127.0.0.1 [your ip]  $ set port 1337  $ set output /$HOME/rat.py  $ generate  It generates rat.py in termux home directory  Open termux new session   type $ ls  here you get that rat.py   go to again A-Rat means privious session of termux  Type run to start exploit.  $ run  and then open new session and run rat like this  $ python rat.py  and come back to A-Rat session   Now its connected to that rat. means Hacked.  press control + c to stop. | https://github.com/Zack-sys/A-Rat-Exploit | 16 | 1| 
| 20210331T12:18:30Z | PhoneSploit is tool for remote ADB Exploitation. With the help of this tool you can control android device by just IP address.  pkg up -y pkg install git -y pkg install python -y pkg install openssl-tool pkg install wget -y pip install colorama git clone https://github.com/MasterDevX/Termux-ADB cd Termux-ADB chmod 777 InstallTools.sh bash InstallTools.sh cd $HOME git clone https://github.com/aerosol-can/PhoneSploit cd PhoneSploit python phonesploit.py | https://github.com/Zack-sys/Phonesploit---hacking-android-using-IP-address | 5 | 0| 
| 20210331T12:10:55Z | Scripts for private exploit | https://github.com/ubimumu/scripts | 0 | 0| 
| 20210331T12:09:55Z | CMS Detection and Exploitation suite - Scan WordPress, Joomla, Drupal and 100 other CMSs  Functions Of CMSeek :  Basic CMS Detection of over 80 CMS Drupal version detection Advanced Wordpress Scans Detects Version User Enumeration Plugins Enumeration Theme Enumeration Detects Users (3 Detection Methods) Looks for Version Vulnerabilities and much more! Advanced Joomla Scans Version detection Backup files finder Admin page finder Core vulnerability detection Directory listing check Config leak detection Various other checks Modular bruteforce system Use pre made bruteforce modules or create your own and integrate with it  Installation :  $ apt update && apt upgrade  $ apt install git   $ apt install python2  $ apt install python  $ git clone https://github.com/Tuhinshubhra/CMSeeK  $ cd CMSeeK  $ chmod +x *  Run :   $ python cmseek.py   here select your oprion and use.. | https://github.com/Zack-sys/CMSEEK-SUIT---CMS-Detection-and-Exploitation-suite---Scan-WordPress-Joomla-Drupal-and-100-other-CM | 4 | 0| 
| 20210331T12:02:47Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 13 | 6| 
| 20210331T12:00:12Z | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | 149 | 24| 
| 20210331T11:50:20Z | 在科研（摸鱼）过程中，收集到的或者自己写的一些有用的（经过实战检验的）exp/poc，欢迎提交issue和PR | https://github.com/ycdxsb/Exploits | 2 | 0| 
| 20210331T11:45:33Z | Post-exploitation tool for Active Directory recon | https://github.com/tmenochet/ADMap | 0 | 0| 
| 20210331T11:44:28Z | Android RAT  | https://github.com/Th30neAnd0nly/Ohm | 2 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210331T12:19:44Z | https://github.blog/2021-03-16-using-github-code-scanning-and-codeql-to-detect-traces-of-solorigate-and-other-backdoors/ | https://github.com/434791829/License-number-12 | 1 | 0| 
| 20210331T11:26:46Z | Null | https://github.com/Delle9999/backdoor | 0 | 0| 
| 20210331T09:24:21Z | Null | https://github.com/xpf/Backdoor-Learning-arXiv | 0 | 0| 
| 20210331T08:19:55Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 186 | 34| 
| 20210331T03:26:55Z | Python 3 Reverse Shell | https://github.com/trackmastersteve/shell | 12 | 4| 
| 20210331T03:07:51Z | Invisible, customizable backdoor for Minecraft Spigot Plugins. | https://github.com/ThiccIndustries/Minecraft-Backdoor | 2 | 1| 
| 20210331T01:28:34Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 200 | 34| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210331T12:32:04Z | Null | https://github.com/fuzzsa/fuzzsa-bugs | 0 | 1| 
| 20210331T12:30:33Z | AFLNet: A Greybox Fuzzer for Network Protocols (https://thuanpv.github.io/publications/AFLNet_ICST20.pdf) | https://github.com/aflnet/aflnet | 386 | 63| 
| 20210331T12:13:31Z | Null | https://github.com/primait/ex_fuzzywuzzy | 0 | 0| 
| 20210331T12:09:04Z | 📨 Responsive email template generator. | https://github.com/luangjokaj/fuzzymail | 114 | 4| 
| 20210331T12:03:01Z | Null | https://github.com/kinzhong/fuzzing-automation-tools | 0 | 0| 
| 20210331T11:43:22Z | Null | https://github.com/FDU-Program-Analysis/chunk-fuzzer-pass | 0 | 0| 
| 20210331T11:09:42Z | Null | https://github.com/Yin-Lynn-Htun/Fuzzy-shop | 0 | 0| 
| 20210331T11:07:24Z | Null | https://github.com/s9varesc/url-fuzzing | 1 | 1| 
| 20210331T10:51:22Z | Null | https://github.com/s9varesc/url-fuzzing-docker | 0 | 0| 
| 20210331T10:35:48Z | Hacking tools written by me. IP fortune, webmap -- web vulns scanner, rtsp brute+fuzz, and more. | https://github.com/fagcinsk/h4ck | 1 | 0| 



# 日更新程序
