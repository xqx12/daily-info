# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210407 | AOSP 现在支持 Rust 开发，以解决 C 和 C++ 开发带来的内存安全错误。 | https://security.googleblog.com/2021/04/rust-in-android-platform.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+GoogleOnlineSecurityBlog+%28Google+Online+Security+Blog%29| 
| 20210407 | 如何绕过 Cloudflare, Incapsula, SUCURI 和其它的 WAF。 | https://miloserdov.org/?p=2960| 
| 20210407 | OAuth2 和 OpenID 的安全问题研究。 | https://www.notion.so/1-Hidden-OAuth-attack-vectors-d5a01415c8594118bc019c53a71f9082| 
| 20210407 | Terminal 中间人的实现。 | https://posts.specterops.io/man-in-the-terminal-65476e6165b9?gi=dc8b85487037| 
| 20210407 | Justin Warner：Using Kaitai to Parse Cobalt Strike Beacon Configs | https://sixdub.medium.com/using-kaitai-to-parse-cobalt-strike-beacon-configs-f5f0552d5a6e| 
| 20210407 | BleedingTooth：Linux 系统中蓝牙模块的零交互漏洞。允许未经身份验证的远程攻击者在具有漏洞的设备上执行具有 kernel privileges 权限的任意代码。 | https://google.github.io/security-research/pocs/linux/bleedingtooth/writeup| 
| 20210407 | 如何使用 Radare2 静态分析恶意软件。 | https://www.blueteamsacademy.com/radare2/| 
| 20210407 | Firefox 使用 ThreadSanitizer 来缓解 Data Races。 | https://hacks.mozilla.org/2021/04/eliminating-data-races-in-firefox-a-technical-report/| 
| 20210407 | Pwn2Own 2021 的日程表。 | https://www.zerodayinitiative.com/blog/2021/4/2/pwn2own-2021-schedule-and-live-results| 
| 20210407 | Priv2Admin：在 Windows 中利用漏洞提权。 | https://sec.today/pulses/6dfd8925-9bf7-4c7c-8ba2-583f3171ffd0/| 
| 20210407 | 【图片】有关 Windows privileges 的备忘录。 | https://sec.today/pulses/b6d22f58-5a27-40d6-80e4-b9407864b12f/| 
| 20210407 | Priv2Admin：在 Windows 中利用漏洞提权。 | https://github.com/gtworek/Priv2Admin| 
| 20210407 | 【图片】有关 Windows privileges 的备忘录。 | https://speakerdeck.com/fr0gger/windows-privileges| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210407 | HIDS-Agent开发之检测反弹shell | https://www.anquanke.com/post/id/235717| 
| 20210407 | IDA 辅助工具Karta——二进制文件中搜索开源代码 | https://www.anquanke.com/post/id/235632| 
| 20210407 | ELK在渗透测试中的利用与安全配置解析 | https://xz.aliyun.com/t/9370| 
| 20210407 | 内网渗透--对不出网目标的打法 | https://xz.aliyun.com/t/9372| 
| 20210407 | 某VPN客户端远程下载文件执行挖掘 | https://mp.weixin.qq.com/s/XbsxziIFKx8VhGd-pv0Ghg| 
| 20210407 | Shiro-550反序列化漏洞分析 | https://www.sec-in.com/article/999| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210407T12:51:00Z | CVE-2021-24086 | Proof of concept for CVE-2021-24086, a NULL dereference in tcpip.sys. | https://github.com/0vercl0k/CVE-2021-24086 | Windows TCP/IP Denial of Service Vulnerability| 
| 20210407T11:25:28Z | CVE-2020-14882 | Null | https://github.com/nice0e3/CVE-2020-14882_Exploit_Gui | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210407T10:37:30Z | CVE-2021-22192 | CVE-2021-22192 靶场： 未授权用户 RCE 漏洞 | https://github.com/lyy289065406/CVE-2021-22192 | An issue has been discovered in GitLab CE/EE affecting all versions starting from 13.2 allowing unauthorized authenticated users to execute arbitrary code on the server.| 
| 20210407T09:46:02Z | CVE-2021-21300 | Null | https://github.com/danshuizhangyu/CVE-2021-21300 | Git is an open-source distributed revision control system. In affected versions of Git a specially crafted repository that contains symbolic links as well as files using a clean/smudge filter such as Git LFS, may cause just-checked out script to be executed while cloning onto a case-insensitive file system such as NTFS, HFS+ or APFS (i.e. the default file systems on Windows and macOS). Note that clean/smudge filters have to be configured for that. Git for Windows configures Git LFS by default, and is therefore vulnerable. The problem has been patched in the versions published on Tuesday, March 9th, 2021. As a workaound, if symbolic link support is disabled in Git (e.g. via `git config --global core.symlinks false`), the described attack won%t work. Likewise, if no clean/smudge filters such as Git LFS are configured globally (i.e. _before_ cloning), the attack is foiled. As always, it is best to avoid cloning repositories from untrusted sources. The earliest impacted version is 2.14.2. The fix versions are: 2.30.1, 2.29.3, 2.28.1, 2.27.1, 2.26.3, 2.25.5, 2.24.4, 2.23.4, 2.22.5, 2.21.4, 2.20.5, 2.19.6, 2.18.5, 2.17.62.17.6.| 
| 20210407T03:02:12Z | 未知编号 | Null | https://github.com/jessica0f0116/cve_2021_1732 | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210407T12:50:40Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 12 | 8| 
| 20210407T12:43:49Z | IC1 project part %Low% (Exploitation) | https://github.com/buykjk/ic1-project-low | 0 | 0| 
| 20210407T12:43:46Z | Computer Network Exploitation (CNE) Field Manual | https://github.com/mzet-/z-field-manual | 2 | 2| 
| 20210407T12:39:00Z | 在科研（摸鱼）过程中，收集到的或者自己写的一些有用的（经过实战检验的）exp/poc，欢迎提交issue和PR | https://github.com/ycdxsb/Exploits | 2 | 0| 
| 20210407T12:35:12Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9231 | 1492| 
| 20210407T12:19:22Z | courses, exploits and lots of code, as i am currently preparing for this exam, i will keep updating everthing i learned or coded here | https://github.com/kainesmicheal/OSWE | 1 | 1| 
| 20210407T12:06:58Z | weblogic full vulnerability exploit tool, support T3/XMLDecoder vulnerability scanning . | https://github.com/DesaiParekh/weblogic_cmd_plus | 5 | 2| 
| 20210407T12:02:59Z | [+] Web crawler that look for possible exploits in URL%s | https://github.com/vLeeH/httpmapper | 2 | 0| 
| 20210407T12:02:52Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 21 | 8| 
| 20210407T12:02:23Z | anon-exploiter.github.io | https://github.com/Anon-Exploiter/anon-exploiter.github.io | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210407T11:58:12Z | Arduino scrpts and meterpreter reverse_tcp backdoor with hid | https://github.com/Taewinzer/Arduino-backdoor-with-meterpreter | 0 | 0| 
| 20210407T11:03:20Z | Minecraft 1.12.2 client  | https://github.com/NKz32/MajorasBackdoor-Clean | 0 | 0| 
| 20210407T06:01:40Z | Backdoor | https://github.com/walpurgisnatch/netrat | 0 | 0| 
| 20210407T05:23:55Z | AUTO-db is a Python script which automates many tools - nmap , file transfer using apache2 and python , remote connections using ssh and msfvenom backdoor,  enum4linux , nikto , dirbuster , gobuster , oscanner , wpscan , nmapAutomator and autorecon | https://github.com/Devansh-git-stor/AUTO-db | 1 | 0| 
| 20210407T04:35:02Z | Null | https://github.com/xpf/Backdoor-Learning-arXiv | 1 | 0| 
| 20210407T03:06:02Z | Null | https://github.com/password520/SmsBackdoor | 0 | 0| 
| 20210407T02:11:08Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 204 | 34| 
| 20210407T01:52:18Z | Windows RAT written in Java for learning purposes | https://github.com/hacefresko/JRAT | 7 | 4| 
| 20210407T00:19:39Z | Reverse TCP trojan backdoor written in python | https://github.com/userlandkernel/Pyrovalerone | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210407T12:49:58Z | I.C. project. A method to choose the best way to implant sensors in management zones | https://github.com/lucasdasilvalima/agrilab-fuzzy-cmeans | 0 | 0| 
| 20210407T12:46:27Z | A mutation-based fuzzing engine for MQTT brokers. | https://github.com/PBearson/MosquittoByte | 0 | 0| 
| 20210407T12:29:54Z | Null | https://github.com/Nafis/unbaised-feature-selection-fuzzy-forest | 0 | 0| 
| 20210407T12:27:55Z | White-box fuzzer for Java bytecode | https://github.com/vorpal-research/kex | 6 | 5| 
| 20210407T12:16:17Z | Null | https://github.com/FDU-Program-Analysis/chunk-fuzzer-pass | 0 | 0| 
| 20210407T12:15:15Z | Functions to extract drug records from the FAERS (FDA Adverse Event Reporting System) database | https://github.com/tystan/fuzzyfaers | 0 | 0| 
| 20210407T12:15:12Z | This is a Fuzzer library built in JS and nodeJS | https://github.com/fuzzing-unb/FuzzerJS | 0 | 0| 
| 20210407T12:06:25Z | A kotlin implementation of sublime text editor%s fuzzy search | https://github.com/android-password-store/sublime-fuzzy | 3 | 0| 
| 20210407T12:03:16Z | Null | https://github.com/prateekgrover-in/NeuralNetworksFuzzyLogic | 0 | 0| 
| 20210407T11:54:32Z | Studies on Fuzzy Inference developed under my masters degree. | https://github.com/renatolm/fuzzy-inference | 0 | 0| 



# 日更新程序
