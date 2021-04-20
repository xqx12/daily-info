# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210420 | Codecov Bash Uploader 工具被黑客修改，可能将用户的 CI（持续集成）的密钥、代码等机密信息发送到了第三方服务器上。 | https://about.codecov.io/security-update/| 
| 20210420 | Pass-the-Hash (PTH): a PoC code to use Pass-the-Hash for authentication on a local Named Pipe user Impersonation. | https://s3cur3th1ssh1t.github.io/Named-Pipe-PTH/| 
| 20210420 | 在 Chrome 沙箱中利用 1Day 和 渲染器重定向实现信息泄漏。 | https://ptr-yudai.hatenablog.com/entry/2021/04/19/140802| 
| 20210420 | CVE-2021-3493：Ubuntu 下利用 overlayfs 提权。 | https://ssd-disclosure.com/ssd-advisory-overlayfs-pe/| 
| 20210420 | 介绍一些例如 GA 等自定义 fuzzer 的功能和设计。 | https://github.com/hardenedlinux/harbian-qa/blob/master/survey.md| 
| 20210420 | 通过 WebDriver REST API 的 RCE。 | https://lorexxar.cn/2021/04/16/chrome-webdriver-attack/| 
| 20210420 | Tenda D151 和 D301 无需身份认证下载配置信息及登录的 POC。 | https://github.com/BenChaliah/Tenda_D151_D301_POC| 
| 20210420 | Lazarus APT 组织将恶意代码写入 BMP 图像的攻击方法。 | https://blog.malwarebytes.com/malwarebytes-news/2021/04/lazarus-apt-conceals-malicious-code-within-bmp-file-to-drop-its-rat/| 
| 20210420 | 逆向分析 Guloader 的工作流程和其反逆向的机制。 | https://elis531989.medium.com/dancing-with-shellcodes-cracking-the-latest-version-of-guloader-75083fb15cb4| 
| 20210420 | PlaidCTF 2021 The-False-Promise Chrome 的 Writeup。 | https://sec.today/pulses/f1054dfc-bff6-48ee-bc7e-f7fabb48afcc/| 
| 20210420 | PlaidCTF 2021 The-False-Promise Chrome 的 Writeup。 | https://hackmd.io/@aventador/BJkOOyi8u| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210420 | MyBatis和MyBatis可能导致的sql注入 | https://www.sec-in.com/article/1022| 
| 20210420 | 可扩展跨平台网络安全工具套件 CaptfEncoder v2.0.0 | https://mp.weixin.qq.com/s?__biz=MzI0ODU5Mzg0NA==&mid=2247483998&idx=1&sn=baaa69c5576a1e52b7d8aeb9482e1cf3&chksm=e99f2e85dee8a79304a5535dbf6c77e9f9def6b2a7438c73e28792ac5ea3c628a02204d116e6&token=1448493475&lang=zh_CN#rd| 
| 20210420 | Java反序列化 — URLDNS利用链分析 | https://xz.aliyun.com/t/9417| 
| 20210420 | Yii2反序列化RCE 新POP链 | https://xz.aliyun.com/t/9420| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210420T12:03:30Z | CVE-2021-3493 | Ubuntu OverlayFS Local Privesc | https://github.com/briskets/CVE-2021-3493 | The overlayfs implementation in the linux kernel did not properly validate with respect to user namespaces the setting of file capabilities on files in an underlying file system. Due to the combination of unprivileged user namespaces along with a patch carried in the Ubuntu kernel to allow unprivileged overlay mounts, an attacker could use this to gain elevated privileges.| 
| 20210420T11:13:21Z | CVE-2020-1350 | HoneyPoC: Proof-of-Concept (PoC) script to exploit SIGRed (CVE-2020-1350). Achieves Domain Admin on Domain Controllers running Windows Server 2000 up to Windows Server 2019. | https://github.com/ZephrFish/CVE-2020-1350 | A remote code execution vulnerability exists in Windows Domain Name System servers when they fail to properly handle requests, aka %Windows DNS Server Remote Code Execution Vulnerability%.| 
| 20210420T04:03:57Z | CVE-2020-14882 | Null | https://github.com/nice0e3/CVE-2020-14882_Exploit_Gui | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Console). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).| 
| 20210420T03:04:13Z | CVE-2020-14364 | Null | https://github.com/gejian-iscas/CVE-2020-14364 | An out-of-bounds read/write access flaw was found in the USB emulator of the QEMU in versions before 5.2.0. This issue occurs while processing USB packets from a guest when USBDevice %setup_len% exceeds its %data_buf[4096]% in the do_token_in, do_token_out routines. This flaw allows a guest user to crash the QEMU process, resulting in a denial of service, or the potential execution of arbitrary code with the privileges of the QEMU process on the host.| 
| 20210420T02:41:51Z | CVE-2021-26295 | Apache OFBiz rmi反序列化EXP(CVE-2021-26295) | https://github.com/S0por/CVE-2021-26295-Apache-OFBiz-EXP | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210420T10:42:27Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1675 | 489| 
| 20210420T08:37:55Z | Null | https://github.com/Jython1415/penguin-Klee | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210420T06:08:42Z | GUI Configuration tool for WIZnet serial to ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool-GUI | 12 | 7| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210420T12:02:46Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 22 | 9| 
| 20210420T11:50:55Z | PS4 Exploit list | https://github.com/Hakkuraifu/PS4xploit | 34 | 11| 
| 20210420T11:18:27Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 10 | 2| 
| 20210420T11:13:21Z | HoneyPoC: Proof-of-Concept (PoC) script to exploit SIGRed (CVE-2020-1350). Achieves Domain Admin on Domain Controllers running Windows Server 2000 up to Windows Server 2019. | https://github.com/ZephrFish/CVE-2020-1350 | 247 | 75| 
| 20210420T10:55:19Z | Config files for my GitHub profile. | https://github.com/Code-Jester/Roblox-Exploit | 1 | 0| 
| 20210420T10:49:35Z | Development of code to exploit LSST and VISTA imaging | https://github.com/lsst-uk/lsst-ir-fusion | 0 | 0| 
| 20210420T10:20:42Z | Exploits for Sync-Breeze  | https://github.com/laordenhacker/Sync-Breeze | 0 | 0| 
| 20210420T09:58:44Z | Website application for searching devices on the internet with vulnerability summarization and exploits demonstration. | https://github.com/larescze/bpc-akr-seclab | 0 | 0| 
| 20210420T09:52:18Z | Null | https://github.com/Raycodex/Exploiting | 0 | 1| 
| 20210420T09:50:03Z | Null | https://github.com/codeVerson1/Roblox-Exploits | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210420T12:02:21Z | Ghost Framework is an Android post-exploitation framework that exploits the Android Debug Bridge to remotely access an Android device. | https://github.com/EntySec/ghost | 1043 | 504| 
| 20210420T10:39:26Z | Null | https://github.com/Delle9999/backdoor | 0 | 0| 
| 20210420T08:30:04Z | Null | https://github.com/igpig/igpigs-Backdoor | 0 | 0| 
| 20210420T03:05:41Z | Hidden backdoor attack on NLP systems | https://github.com/lishaofeng/NLP_Backdoor | 1 | 0| 
| 20210420T01:20:02Z | free and open source nonobf server backdoor plugin | https://github.com/AcaiBerii/Bakdooro | 0 | 0| 
| 20210420T01:14:45Z | Null | https://github.com/mustblade/phpstudy_backdoor_exp | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210420T12:02:00Z | Null | https://github.com/DanielEbert/EmulatedFirmwareFuzzing | 0 | 0| 
| 20210420T11:57:55Z | Playground with fuzzy logic | https://github.com/perinm/proj-fuzzy | 0 | 0| 
| 20210420T11:56:44Z | Null | https://github.com/erdifajarf/PMDK_FuzzyAHP | 0 | 0| 
| 20210420T11:15:03Z | Python library to compute a fuzzy time difference. | https://github.com/hXtreme/fuzzy_delta_time | 0 | 0| 
| 20210420T11:08:06Z | Null | https://github.com/milhamm/restaurant-fuzzy-logic | 0 | 0| 
| 20210420T10:32:14Z | Fuzzy Front End 2021 - Pimp my makerspace | https://github.com/olenesheim/fuzzy_front_end | 0 | 0| 
| 20210420T10:30:12Z | Binary, coverage-guided fuzzer for Windows and macOS | https://github.com/googleprojectzero/Jackalope | 498 | 56| 
| 20210420T10:08:37Z | Null | https://github.com/KonradMierzwa/OfficeSamurai.FuzzyWuzzy | 0 | 0| 
| 20210420T10:07:33Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 1| 
| 20210420T09:56:01Z | Null | https://github.com/Nafis/unbaised-feature-selection-fuzzy-forest | 0 | 0| 



# 日更新程序
