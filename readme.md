# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210402 | James Forshaw：关于 Windows Server Containers 的安全研究背景、过程和一些见解。 | https://googleprojectzero.blogspot.com/2021/04/who-contains-containers.html| 
| 20210402 | 通过函数指针回调，很多 Win 32 的 API 可以被用于执行 shellcode。 | https://osandamalith.com/2021/04/01/executing-shellcode-via-callbacks/| 
| 20210402 | CVE-2021-24098 的 POC。关于 Windows 控制台驱动的拒绝服务漏洞。 | https://github.com/waleedassar/CVE-2021-24098| 
| 20210402 | Mikko Kenttälä：macOS Mail 的一个无交互的漏洞。由于符号连接未正确删除，通过自动解压附件，可以实现在 Mail.app 的沙箱环境中添加或修改任意文件。 | https://mikko-kenttala.medium.com/zero-click-vulnerability-in-apples-macos-mail-59e0c14b106c| 
| 20210402 | 当 ajaxpipe 或 quickling 的参数添加到 Fackbook 的任意站点请求时，错误的响应可能会造成 Facebook 的 access_token 被恶意接管。 | https://ysamm.com/?p=654| 
| 20210402 | Facebook 在 OAuth 认证中的 fallback_redirect_uri 路径检查不完整，使得 Facebook 和 Instagram 账户可以被恶意接管。 | https://ysamm.com/?p=646| 
| 20210402 | ProChecker：用于自动化分析 4G LTE 协议的安全性和隐私框架。 | https://syed-rafiul-hussain.github.io/wp-content/uploads/2021/03/ProChecker.pdf| 
| 20210402 | Michael Stepankin：nOtWASP 前十个让人哭笑不得的漏洞。 | https://portswigger.net/research/notwasp-bottom-10-vulnerabilities-that-make-you-cry| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210402 | 国内伪基站垃圾短信生态系统研究 | https://mp.weixin.qq.com/s/te4igYM_PHbf2xedXdmQxw| 
| 20210402 | 驱动病毒那些事(三)----APC注入 | https://www.sec-in.com/article/994| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210402T11:30:27Z | CVE-2021-24098 | POC for CVE-2021-24098 | https://github.com/waleedassar/CVE-2021-24098 | Windows Console Driver Denial of Service Vulnerability| 
| 20210402T10:51:05Z | CVE-2021-21975 | Nmap script to check vulnerability CVE-2021-21975 | https://github.com/GuayoyoCyber/CVE-2021-21975 | | 
| 20210402T09:31:09Z | CVE-2021-3156 | Sudo Baron Samedit Exploit | https://github.com/worawit/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210402T07:40:04Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210402T03:45:52Z | CVE-2021-1699 | POC for CVE-2021-1699 | https://github.com/waleedassar/CVE-2021-1699 | Windows (modem.sys) Information Disclosure Vulnerability| 
| 20210402T03:06:32Z | CVE-2021-1732 | Null | https://github.com/ltfafei/CVE-2021-1732_exp | Windows Win32k Elevation of Privilege Vulnerability This CVE ID is unique from CVE-2021-1698.| 
| 20210402T03:06:31Z | CVE-2021-26295 | CVE-2021-26295 Apache OFBiz POC | https://github.com/ltfafei/CVE-2021-26295_Apache_OFBiz_POC | Apache OFBiz has unsafe deserialization prior to 17.12.06. An unauthenticated attacker can use this vulnerability to successfully take over Apache OFBiz.| 
| 20210402T03:06:29Z | CVE-2021-21975 | Null | https://github.com/ltfafei/CVE-2021-21975_VMware_SSRF | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210402T10:57:10Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 114 | 9| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210402T06:55:39Z | Null | https://github.com/yuvalkirstain/s2e-coref | 2 | 2| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210402T12:25:44Z | just testing some stuff | https://github.com/klausklemens/exploits | 0 | 0| 
| 20210402T12:21:54Z | PS4 Exploit Host | https://github.com/Night-King-Host/Night-King-Host.github.io | 6 | 3| 
| 20210402T12:02:24Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 13 | 6| 
| 20210402T11:35:11Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9221 | 1490| 
| 20210402T11:26:18Z | Model of resource exploitation of Iron Age communities in southwest Anatolia. To be presented at ReSoc conference | https://github.com/driesdaems10/Resoc | 1 | 1| 
| 20210402T11:18:29Z | Fixes some Minecraft Server exploits and lag exploits | https://github.com/NickyAdmin/NickysFixer | 1 | 0| 
| 20210402T11:03:26Z | Automated All-in-One OS Command Injection Exploitation Tool | https://github.com/commixproject/commix | 2578 | 597| 
| 20210402T09:49:48Z | exploit host 7.02 by darkfire | https://github.com/darkfirevc/https-darkfirevc.github.io-index.html.html | 0 | 0| 
| 20210402T09:28:04Z | This tool lets you search your gadgets on your binaries to facilitate your ROP exploitation. ROPgadget supports ELF, PE and Mach-O format on x86, x64, ARM, ARM64, PowerPC, SPARC and MIPS architectures.  | https://github.com/JonathanSalwan/ROPgadget | 2630 | 500| 
| 20210402T09:26:30Z | linux post-exploitation framework made by linux user | https://github.com/jm33-m0/emp3r0r | 429 | 81| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210402T10:14:55Z | Null | https://github.com/Kenya123/backdoor | 0 | 0| 
| 20210402T08:11:20Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 201 | 34| 
| 20210402T08:06:46Z | [Disclaimer FireROOT] This repository is for research purposes only, the use of this code is your responsibility. CONTACT ME: Attack@fireRootHacker.Ga | https://github.com/facenano/fireroothacker | 1 | 1| 
| 20210402T04:02:40Z | PCI Express DIY hacking toolkit for Xilinx SP605 | https://github.com/Cr4sh/s6_pcie_microblaze | 309 | 79| 
| 20210402T03:18:54Z | generator of php_backdoor | https://github.com/M4chin3M4N/backdoor-gen | 0 | 0| 
| 20210402T02:25:05Z | A backdoor trojan written in python | https://github.com/noxis0/Doku | 0 | 0| 
| 20210402T01:38:32Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 56 | 10| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210402T12:17:25Z | collection of helper tools for fuzzing | https://github.com/fuzzah/fuzzaide | 2 | 0| 
| 20210402T12:15:09Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 1 | 0| 
| 20210402T11:54:07Z | Null | https://github.com/s9varesc/url-fuzzing-docker | 0 | 0| 
| 20210402T11:27:57Z | Null | https://github.com/s9varesc/url-fuzzing | 1 | 1| 
| 20210402T11:12:10Z | Kernel Fuzzing driven by System call(Syscall) Dependency graph | https://github.com/LittleSec/SDKernelFuzzing | 0 | 0| 
| 20210402T11:03:20Z | Peach Pit For Peach fuzzer and aflsmart fuzzer | https://github.com/0x34d/Peach_pit | 0 | 0| 
| 20210402T11:02:09Z | Using different tools to fuzz audit deamon | https://github.com/punnal/Audit-Fuzzing | 1 | 1| 
| 20210402T10:15:14Z | A bare-metal x86 instruction set fuzzer a la Sandsifter | https://github.com/blitz/baresifter | 35 | 3| 
| 20210402T10:08:27Z | Null | https://github.com/VeriBlock/fuzz-corpus | 0 | 1| 
| 20210402T09:54:37Z | Null | https://github.com/Sambigeara/fuzzynote | 2 | 1| 



# 日更新程序
