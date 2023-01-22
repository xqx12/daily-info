# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230121 | CVE-2022-42864:IOHIDFamily中的一个TOCTOU的writeup和poc | https://muirey03.blogspot.com/2023/01/cve-2022-42864-diabolical-cookies.html| 
| 20230121 | 介绍了作者以一种意外的方式发现并找到 WinIO 内核驱动栈溢出漏洞。并展示了利用此漏洞为根基，攻击某外围设备厂商的驱动，并最终执行任意内核代码的全过程。 | https://www.cyberark.com/resources/threat-research-blog/inglourious-drivers-a-journey-of-finding-vulnerabilities-in-drivers| 
| 20230120 | idek CTF 2022* 取证系统题目 - HiddenGem Mixtape详细writeup | https://hackmd.io/@crazyman/ryDLmrzoi| 
| 20230120 | JSNativeContextSpecialization::BuildElementAccess中的Copy-on-write检查绕过,可能导致rce不过可能难以利用 | https://bugs.chromium.org/p/project-zero/issues/detail?id=2381| 
| 20230120 | CVE-2022-47966:viettel安全的名为khoadha的安全研究员发布使用DocumentHandler来攻击xslt transformer的研究 | https://blog.viettelcybersecurity.com/saml-show-stopper/| 
| 20230120 | ManageEngine CVE-2022-47966 技术的深入分析 | http://www.horizon3.ai/manageengine-cve-2022-47966-technical-deep-dive/| 
| 20230120 | CVE-2023-0297:pyLoad中由于js2py的eval_js安全配置不当导致未授权RCE | https://github.com/bAuh0lz/CVE-2023-0297_Pre-auth_RCE_in_pyLoad| 
| 20230120 | r3kapig战队发布关于idek 2022* CTF的Pwn和Reverse大部分题目的writeup | https://mp.weixin.qq.com/s/nBJU1jWaD2TFsij6OtM-_A| 
| 20230120 | r3kapig战队发布关于idek 2022* CTF的Misc,OSINT,BlockChain类别所有题目的详细writeup | https://mp.weixin.qq.com/s/1xUncQ7CBht3q55T3rKl1w| 
| 20230120 | Gamaredon使用Telegram为网络中转媒介(目标是躲避流量监控)以攻击乌克兰目标 | https://blogs.blackberry.com/en/2023/01/gamaredon-abuses-telegram-to-target-ukrainian-organizations| 
| 20230120 | CVE-2022-27226:iRZ Mobile Routers中CSRF到RCE | http://johnjhacking.com/blog/cve-2022-27226/| 
| 20230120 | CVE-2023-22809:sudoedit中存在一个有意思的逻辑漏洞,sudoedit通过sudo_edith函数中--来判断文件列表进而影响执行的command_details,同时find_editorh函数会从EDITOR,SUDO_EDITOR,EDITOR环境变量中提取信息,并且调用resolve_editor函数进行解析,resolve_editor函数既解析了编辑器的路径,还解析了以--为分割的参数.而如果在环境变量中加入--,则在最后的执行命令中造成了命令行的混淆,让sudo认为--”参数之后的所有内容都视为要编辑的文件.从而可以利用这个漏洞去编辑任意敏感文件以达到提权的目的 | https://sec.today/pulses/b8209ba6-528b-449c-881e-b19f3e3443de/| 
| 20230120 | 在新版Linux内核中利用空指针引用 | https://sec.today/pulses/6d1baec9-2c36-4834-b58f-83dbc273d6d8/| 
| 20230120 | CVE-2023-22809:sudoedit中存在一个有意思的逻辑漏洞,sudoedit通过sudo_edith函数中--来判断文件列表进而影响执行的command_details,同时find_editorh函数会从EDITOR,SUDO_EDITOR,EDITOR环境变量中提取信息,并且调用resolve_editor函数进行解析,resolve_editor函数既解析了编辑器的路径,还解析了以--为分割的参数.而如果在环境变量中加入--,则在最后的执行命令中造成了命令行的混淆,让sudo认为--”参数之后的所有内容都视为要编辑的文件.从而可以利用这个漏洞去编辑任意敏感文件以达到提权的目的 | https://www.synacktiv.com/sites/default/files/2023-01/sudo-CVE-2023-22809.pdf| 
| 20230120 | 在新版Linux内核中利用空指针引用 | https://googleprojectzero.blogspot.com/2023/01/exploiting-null-dereferences-in-linux.html| 
| 20230120 | EmojiDeploy:影响Azure web服务的RCE,其主要通过SCM服务 Kudu上的CSRF漏洞将带有恶意载荷的zip部署到Azure,再调用相关的功能从zip部署代码实现rce | http://ermetic.com/blog/azure/emojideploy-smile-your-azure-web-service-just-got-rced| 
| 20230120 | 解析BackgroundItems-v4.btm中的启动项信息,可用于MacOS的取证 | https://github.com/objective-see/DumpBTM/| 
| 20230120 | 疑似中国黑客针对 Fortinet 零日漏洞（CVE-2022-42475）制作恶意软件后门：BoldMove | https://www.darkreading.com/threat-intelligence/china-based-attacker-crafted-custom-malware-for-fortinet-zero-day| 
| 20230119 | viettel安全的名为vudq4的安全研究员发布关于CVE-2022-21587 (Oracle E-Business Suite 未授权RCE)的细节.其主要通过oracle.apps.bne.framework.BneMultipartRequest中的doUploadFile函数,其处理文件名带有uue的文件时候会调用doUnZip,而该函数容易遭到ZipSlip的攻击造成文件上传.同时也介绍了如何编写可以在其工作的webshell,但是由于oracle.apps.fnd.security.WLFilter的限制.所以只能去考虑如何覆盖pl来进行执行,由于所有经过pl的都会经过weblogic.servlet.CGIServlet在调试的可以发现一个不重要的文件txkFNDWRR.pl(作用只有生成log),通过覆盖来实现webshell,完成RCE | https://blog.viettelcybersecurity.com/cve-2022-21587-oracle-e-business-suite-unauth-rce/| 
| 20230119 | Firefox 在野0day漏洞分析,CVE-2022-26485(RCE)+CVE-2022-26486(SBX) | https://weiyiling.cn/one/firefox_0day_case_analysis| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230119 | 顶会论文写作建议（上）：宏观布局，避免“hard to follow” | https://mp.weixin.qq.com/s/kberQa8ss7l2gh9PAx_cSQ| 
| 20230119 | 从CISA KEV看海量漏洞管理方法 | https://mp.weixin.qq.com/s/X5J4gYanCGrGMJ9Yp6J8tQ| 
| 20230119 | 基于代码属性图的自动化漏洞挖掘实践 | https://blog.0kami.cn/blog/2023/%E5%9F%BA%E4%BA%8E%E4%BB%A3%E7%A0%81%E5%B1%9E%E6%80%A7%E5%9B%BE%E7%9A%84%E8%87%AA%E5%8A%A8%E5%8C%96%E6%BC%8F%E6%B4%9E%E6%8C%96%E6%8E%98%E5%AE%9E%E8%B7%B5/| 
| 20230119 | mqtt攻击面和挖掘思路浅析 | https://vul.360.net/archives/649| 
| 20230119 | 一种 Foxit Reader 漏洞利用思路探索 | https://vul.360.net/archives/648| 
| 20230118 | 开源软件安全性分析 | https://mp.weixin.qq.com/s/dDHmQkWhSchnD7kTBtKymw| 
| 20230118 | 利用空间测绘进行威胁分析 | https://mp.weixin.qq.com/s/b-rynWs2xX3ft48QFx8NBg| 
| 20230118 | 2022年全球高级持续性威胁（APT）研究报告 | https://cdn.isc.360.com/iscvideo-bucket/360_APT_Annual_Research_Report_2022.pdf| 
| 20230117 | 玩转CodeQLpy之用友GRP-U8漏洞挖掘 | https://mp.weixin.qq.com/s/hYPdNN6skbikC3FFYRlbrQ| 
| 20230117 | 关于大模型时代软件智能化开发的一点展望 | https://mp.weixin.qq.com/s/UTcnFq53JjIMsShmKtQvDw| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230122T02:13:37Z | CVE-2023-22809 | A script to automate privilege escalation with CVE-2023-22809 vulnerability | https://github.com/n3m1dotsys/CVE-2023-22809-sudoedit-privesc | | 
| 20230122T01:50:10Z | CVE-2022-1388 | CVE-2022-1388 Scanner | https://github.com/EvilLizard666/CVE-2022-1388 | | 
| 20230122T01:50:00Z | CVE-2022-44900 | Demo webapp vulnerable to CVE-2022-44900 | https://github.com/0xless/CVE-2022-44900-demo-lab | | 
| 20230121T22:40:58Z | CVE-2021-20294 | Simple CVE-2021-20294 poc | https://github.com/tin-z/CVE-2021-20294-POC | | 
| 20230121T22:06:39Z | CVE-2023-0179 | Null | https://github.com/TurtleARM/CVE-2023-0179-PoC | | 
| 20230121T21:26:32Z | CVE-2023-22617 | A remote attacker might be able to cause infinite recursion in PowerDNS Recursor 4.8.0 via a DNS query that retrieves DS records for a misconfigured domain, because QName minimization is used in QM fallback mode. This is fixed in 4.8.1. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-22617 | | 
| 20230121T19:03:58Z | CVE-2022-36804 | Bitbucket CVE-2022-36804 unauthenticated remote command execution | https://github.com/kljunowsky/CVE-2022-36804-POC | | 
| 20230121T18:10:26Z | CVE-2023-0433 | Heap-based Buffer Overflow in GitHub repository vim/vim prior to 9.0.1225. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0433 | | 
| 20230121T10:33:47Z | CVE-2022-45770 | LPE exploit via windows driver | https://github.com/Marsel-marsel/CVE-2022-45770 | | 
| 20230121T07:10:05Z | CVE-2023-24038 | The HTML-StripScripts module through 1.06 for Perl allows _hss_attval_style ReDoS because of catastrophic backtracking for HTML content with certain style attributes. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-24038 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230122T01:27:56Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10128 | 341| 
| 20230121T07:11:00Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 200 | 1| 
| 20230121T06:51:03Z | Null | https://github.com/rajashekharpendli/kleeteam | 0 | 0| 
| 20230121T06:19:52Z | Null | https://github.com/rajashekharpendli/klee | 0 | 0| 
| 20230119T16:37:09Z | Site single page responsivo desenvolvido apenas para prática. | https://github.com/Everton-Luciano/kleep-project | 0 | 0| 
| 20230119T14:50:36Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 269 | 50| 
| 20230119T12:18:24Z | Preprocessor for symbolic execution, extracted from KLEE | https://github.com/Generative-Program-Analysis/fs-linker | 2 | 0| 
| 20230119T10:15:34Z | A Max implementation of a shift register sequencer like the MTM Turing Machine or the Klee Sequencer | https://github.com/jakebeamish/max-shift-register-sequencer | 0 | 0| 
| 20230118T23:02:27Z | Collection of Kicad 6.0 symbols, footprints and 3D models useful in keyboard creation | https://github.com/crides/kleeb | 69 | 6| 
| 20230118T16:26:28Z | 基於 Klee One 改造的字型，以傳承字形風格為主。 | https://github.com/Ayaginu-Sue/Astalia | 1 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230122T00:41:22Z | Created with StackBlitz ⚡️ | https://github.com/natanbr/Alice-in-borderland---acid-game-s2e6- | 0 | 0| 
| 20230121T12:01:48Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 291 | 67| 
| 20230113T18:45:53Z | Null | https://github.com/turbocanary/turbotest_r6aikmfr_s2e79up1 | 0 | 0| 
| 20230107T16:37:04Z | The exploit generator CRAX++ is CRAX with x86_64 ROP techniques, s2e 2.0 upgrade, code selection, I/O states, dynamic ROP, and more! | https://github.com/SQLab/CRAXplusplus | 75 | 12| 
| 20230105T06:57:30Z | Null | https://github.com/dona7025/S2ExamDs-ml | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230122T01:11:34Z | :triangular_flag_on_post: A CLI tool & library to enhance and speed up script/exploit writing with string conversion/manipulation. | https://github.com/noraj/ctf-party | 56 | 4| 
| 20230121T23:48:01Z | Null | https://github.com/codingcore12/SILENT-EXCEL-XLS-EXPLOIT-CLEAN-hy | 1 | 0| 
| 20230121T23:46:41Z | Null | https://github.com/codingcore12/SILENT-PDF-EXPLOIT-CLEAN-hy | 1 | 0| 
| 20230121T23:45:42Z | Null | https://github.com/codingcore12/SILENT-DOC-EXPLOIT-CLEAN-hy | 1 | 0| 
| 20230121T23:37:19Z | Patches for Waterfall to improve overall performance, fix memory issues and protect against attacks. | https://github.com/2lstudios-mc/FlameCord | 201 | 145| 
| 20230121T22:35:28Z | Null | https://github.com/srcdslab/sm-plugin-FixSprayExploit | 1 | 1| 
| 20230121T21:41:51Z | exploit | https://github.com/vbrexploits/eakfucker | 0 | 0| 
| 20230121T21:09:12Z | A few JavaScript exploits that can be embedded in websites.  | https://github.com/THECRAZEDPOTATTO/HTML-JavaScript-exploits | 1 | 0| 
| 20230121T15:30:10Z | Cobalt Strike is a post-exploitation framework designed to be extended and customized by the user community. Several excellent tools and scripts have been written and published, but they can be challenging to locate. Community Kit is a central repository of extensions written by the user community to extend the capabilities of Cobalt Strike. The Cobalt Strike team acts as the curator and provides this kit to showcase this fantastic work. | https://github.com/Cobalt-Strike/community_kit | 160 | 2| 
| 20230121T13:43:59Z | Null | https://github.com/404PageN0tFound/RobloxExploits | 1 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230122T00:47:42Z | keylogger搭載してるというか、それに特化したハッキングツール。 | https://github.com/ware255/yuki | 1 | 0| 
| 20230121T23:58:46Z | Kernel  rk | https://github.com/carloslack/KoviD | 107 | 26| 
| 20230121T22:58:48Z | Villain is a Windows & Linux backdoor generator and multi-session handler that allows users to connect with sibling servers (other machines running Villain) and share their backdoor sessions, handy for working as a team. | https://github.com/t3l3machus/Villain | 2312 | 389| 
| 20230121T21:05:58Z | Null | https://github.com/Backdoorislife/https-github.com-checkpoint-soyhenry-org-2023-01-21-Backdoorislife | 0 | 0| 
| 20230121T16:17:25Z | The BackDoor of HIPHP gives you the power to control websites based on PHP using HTTP/HTTPS protocol. By sending files, tokens and commands through port 80%s POST/GET method, users can access a range of activities such as downloading and editing files. It also allows for connecting to Tor networks with password protection for extra security. | https://github.com/yasserbdj96/hiphp | 37 | 10| 
| 20230121T13:58:16Z | Null | https://github.com/sadarxd/Backdoor-version-1 | 0 | 0| 
| 20230121T13:57:45Z | Null | https://github.com/sadarxd/Backdoor-version-2 | 0 | 0| 
| 20230121T13:51:56Z | code is written in oop java. | https://github.com/sadarxd/Backdoor | 0 | 0| 
| 20230121T09:04:08Z | Evil-Droid is a framework that creates & generates & embed apk payload to penetrate Android platforms. | https://github.com/HackWithSumit/AndroidBackdoor-EvilDroid | 0 | 0| 
| 20230121T02:55:16Z | Null | https://github.com/Gabriel160204/Backdoor-Reverse-Shell | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230121T12:01:48Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 291 | 67| 
| 20230121T10:34:37Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3282 | 468| 
| 20230120T09:37:14Z | radius2 is a fast binary emulation and symbolic execution framework using radare2 | https://github.com/aemmitt-ns/radius | 311 | 24| 
| 20230119T13:02:43Z | Bachelor thesis, attempting decompilation using symbolic execution | https://github.com/lokegustafsson/thesis-decompilation | 2 | 0| 
| 20230119T12:18:24Z | Preprocessor for symbolic execution, extracted from KLEE | https://github.com/Generative-Program-Analysis/fs-linker | 2 | 0| 
| 20230119T12:16:58Z | Open-source symbolic execution framework: https://maat.re | https://github.com/trailofbits/maat | 540 | 31| 
| 20230118T20:49:45Z | A survey of literature and applications for symbolic execution tools | https://github.com/LinqLover/symbolic-execution-survey | 0 | 0| 
| 20230118T13:13:41Z | Symbolic Execution engine for finding bugs in EO programs | https://github.com/polystat/symex | 0 | 0| 
| 20230117T20:33:19Z | The symbolic execution engine powering the K Framework | https://github.com/runtimeverification/haskell-backend | 185 | 42| 
| 20230117T11:46:00Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 614 | 111| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230121T15:18:39Z | find relevant security papers published in the top-4 conferences (S&P, USENIX, CCS, NDSS) | https://github.com/Kyle-Kyle/top4grep | 29 | 2| 
| 20230119T16:29:30Z | Null | https://github.com/tokunagak/NDSS | 0 | 0| 
| 20230119T14:19:34Z | Code for the NDSS%23 paper %DARWIN: Survival of the Fittest Fuzzing Mutators% | https://github.com/TUDA-SSL/DARWIN | 1 | 0| 
| 20230118T07:06:06Z | Anomaly Detection in the Open World: Normality Shift Detection, Explanation, and Adaptation (NDSS%23). | https://github.com/dongtsi/OWAD | 5 | 1| 
| 20230116T10:17:44Z | ConfFuzz NDSS Data Set | https://github.com/conffuzz/conffuzz-ndss-data | 1 | 1| 
| 20230115T02:56:21Z | A Summary of Vulnerabilities Found in the BlockScope NDSS%23 Paper | https://github.com/VPRLab/BlkVulnReport | 2 | 0| 
| 20230113T21:10:57Z | DroneSecurity (NDSS 2023) | https://github.com/RUB-SysSec/DroneSecurity | 1 | 0| 
| 20230111T23:04:46Z | A Summary of Vulnerabilities Found in the BlockScope NDSS%23 Paper | https://github.com/VPRLab/BS_VulnReport | 2 | 0| 
| 20230110T22:12:59Z | Experiments from the Witcher NDSS submission  | https://github.com/sefcom/Witcher-experiment | 0 | 0| 
| 20230107T14:25:39Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 67 | 15| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230122T00:30:48Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 1229 | 164| 
| 20230121T22:46:34Z | Just Crazy... | https://github.com/Algebra0001/fuzzy-waddle | 0 | 0| 
| 20230121T22:27:46Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8289 | 1807| 
| 20230121T22:08:42Z | Floating ball controller is about floating a ball in the middle of a plastic tube using a computer cooling fan. The controller measures speed and distance using ultrasonic range sensor. This controller uses fuzzy logic rules to control the fan. This project helps could be applied to industrial applications like car speed cruiser. | https://github.com/ShahdayBhai/Floating-Ball-Using-Fuzzy-Logic-Controller | 0 | 0| 
| 20230121T21:48:25Z | Fuzzed for the door puzzle in Blackwater / Pathfinder wrath of the righteous | https://github.com/kristianwiklund/pf_fuzzer | 0 | 0| 
| 20230121T21:00:32Z | Web Fuzzing para descobrir arquivos escondidos dentro do WebSite - File Exposure e Hidden Files | https://github.com/GuilhermeAMonte/WebFuzzing | 0 | 0| 
| 20230121T20:50:41Z | Null | https://github.com/l1gh7w34ver/basic_fuzz_test | 0 | 0| 
| 20230121T20:32:41Z | Null | https://github.com/belgranomanuela/fuzzyChallenge | 1 | 0| 
| 20230121T13:40:47Z | Solutions and explanations for the book %Fuzzy Sets & Fuzzy Logic: Theory and Applications by George J. Klir and Bo Yuan% | https://github.com/x-projekt/_fuzzy-sets-logic | 0 | 0| 
| 20230121T13:39:39Z | Fuzzy Match lib in Cython. | https://github.com/SClovesgtx/CyFuzz | 0 | 0| 



# 日更新程序
