# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
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
| 20230119 | 如何利用本地提权漏洞（CVE-2021-3490）实现在5.15 之前的 Linux 内核版本进行容器逃逸。 | https://www.crowdstrike.com/blog/exploiting-cve-2021-3490-for-container-escapes/| 
| 20230119 | pksecurity发布其在pwn2own 2022使用的microsoft teams rce | http://blog.pksecurity.io/2023/01/16/2022-microsoft-teams-rce.html| 


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
| 20230121T02:14:19Z | CVE-2022-36804 | Bitbucket CVE-2022-36804 unauthenticated remote command execution | https://github.com/kljunowsky/CVE-2022-36804-POC | | 
| 20230121T02:08:30Z | CVE-2022-40684 | Exploit for CVE-2022-40684 affecting Fortinet FortiOS, FortiProxy, and FortiSwitchManager | https://github.com/kljunowsky/CVE-2022-40684-POC | | 
| 20230121T01:58:03Z | CVE-2022-41040 | CVE-2022-41040 - Server Side Request Forgery (SSRF) in Microsoft Exchange Server | https://github.com/kljunowsky/CVE-2022-41040-POC | | 
| 20230121T01:52:55Z | CVE-2022-42889 | Apache commons text - CVE-2022-42889 Text4Shell proof of concept exploit. | https://github.com/kljunowsky/CVE-2022-42889-text4shell | | 
| 20230121T01:09:16Z | CVE-2023-0179 | Null | https://github.com/TurtleARM/CVE-2023-0179-PoC | | 
| 20230120T23:23:42Z | CVE-2020-16145 | Roundcube Webmail before 1.3.15 and 1.4.8 allows stored XSS in HTML messages during message display via a crafted SVG document. This issue has been fixed in 1.4.8 and 1.3.15. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-16145 | | 
| 20230120T23:23:38Z | CVE-2020-15953 | LibEtPan through 1.9.4, as used in MailCore 2 through 0.6.3 and other products, has a STARTTLS buffering issue that affects IMAP, SMTP, and POP3. When a server sends a "begin TLS" response, the client reads additional data (e.g., from a meddler-in-the-middle attacker) and evaluates it in a TLS context, aka "response in CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-15953 | | 
| 20230120T23:23:34Z | CVE-2023-24025 | CRYSTALS-DILITHIUM (in Post-Quantum Cryptography Selected Algorithms 2022) in PQClean d03da30 may allow universal forgeries of digital signatures via a template side-channel attack because of intermediate data leakage of one vector. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-24025 | | 
| 20230120T23:23:30Z | CVE-2023-23607 | erohtar/Dasherr is a dashboard for self-hosted services. In affected versions unrestricted file upload allows any unauthenticated user to execute arbitrary code on the server. The file /www/include/filesave.php allows for any file to uploaded to anywhere. If an attacker uploads a php file they can execute code on the s CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-23607 | | 
| 20230120T23:23:27Z | CVE-2021-33642 | When a file is processed, an infinite loop occurs in next_inline() of the more_curly() function. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-33642 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T18:52:06Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10123 | 341| 
| 20230120T12:19:04Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 198 | 1| 
| 20230119T16:37:09Z | Site single page responsivo desenvolvido apenas para prática. | https://github.com/Everton-Luciano/kleep-project | 0 | 0| 
| 20230119T14:50:36Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 269 | 50| 
| 20230119T12:18:24Z | Preprocessor for symbolic execution, extracted from KLEE | https://github.com/Generative-Program-Analysis/fs-linker | 2 | 0| 
| 20230119T10:15:34Z | A Max implementation of a shift register sequencer like the MTM Turing Machine or the Klee Sequencer | https://github.com/jakebeamish/max-shift-register-sequencer | 0 | 0| 
| 20230118T23:02:27Z | Collection of Kicad 6.0 symbols, footprints and 3D models useful in keyboard creation | https://github.com/crides/kleeb | 69 | 6| 
| 20230118T16:26:28Z | 基於 Klee One 改造的字型，以傳承字形風格為主。 | https://github.com/Ayaginu-Sue/Astalia | 1 | 0| 
| 20230118T06:47:11Z | Null | https://github.com/fafrincs/KLEE-FLOAT | 0 | 0| 
| 20230116T05:26:06Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2140 | 604| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T07:17:14Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 290 | 67| 
| 20230113T18:45:53Z | Null | https://github.com/turbocanary/turbotest_r6aikmfr_s2e79up1 | 0 | 0| 
| 20230107T16:37:04Z | The exploit generator CRAX++ is CRAX with x86_64 ROP techniques, s2e 2.0 upgrade, code selection, I/O states, dynamic ROP, and more! | https://github.com/SQLab/CRAXplusplus | 75 | 12| 
| 20230105T06:57:30Z | Null | https://github.com/dona7025/S2ExamDs-ml | 0 | 0| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230121T02:53:17Z | Paper: Exploiting Superpixel-based Contextual Information on Active Learning for High Spatial Resolution Remote Sensing Image Classification | https://github.com/Jaychan-Tang/SNSSL | 0 | 0| 
| 20230121T02:14:19Z | Bitbucket CVE-2022-36804 unauthenticated remote command execution | https://github.com/kljunowsky/CVE-2022-36804-POC | 6 | 3| 
| 20230121T02:08:30Z | Exploit for CVE-2022-40684 affecting Fortinet FortiOS, FortiProxy, and FortiSwitchManager | https://github.com/kljunowsky/CVE-2022-40684-POC | 12 | 1| 
| 20230121T01:58:03Z | CVE-2022-41040 - Server Side Request Forgery (SSRF) in Microsoft Exchange Server | https://github.com/kljunowsky/CVE-2022-41040-POC | 73 | 11| 
| 20230121T01:52:55Z | Apache commons text - CVE-2022-42889 Text4Shell proof of concept exploit. | https://github.com/kljunowsky/CVE-2022-42889-text4shell | 42 | 8| 
| 20230121T01:21:57Z | Null | https://github.com/AnthonyRP05/Exploit_binaire | 0 | 0| 
| 20230121T00:12:02Z | NWEA Testing Exploits. | https://github.com/busks/NweaTestingTool | 1 | 0| 
| 20230120T23:20:11Z | A high-performance serving framework for ML models, offers dynamic batching and multi-stage pipeline to fully exploit your compute machine | https://github.com/mosecorg/mosec | 166 | 20| 
| 20230120T23:15:11Z | Null | https://github.com/GitHubUser12346457/Exploit | 0 | 0| 
| 20230120T23:03:39Z | While trying to hack into the HP DeskJet 2700 I found a way to cause a Denial of Service on the admin login page by changing the login cookie and the authorization token in each request | https://github.com/temoc1n/HP-DeskJet-2700-DoS-Exploit- | 1 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230121T02:19:30Z | Villain is a Windows & Linux backdoor generator and multi-session handler that allows users to connect with sibling servers (other machines running Villain) and share their backdoor sessions, handy for working as a team. | https://github.com/t3l3machus/Villain | 2301 | 388| 
| 20230120T23:02:38Z | This tool is used for backdoor and shellcode generation for various architecture devices | https://github.com/doudoudedi/hackEmbedded | 31 | 3| 
| 20230120T17:38:05Z | Null | https://github.com/kaster-san/backdoors | 0 | 0| 
| 20230120T16:56:02Z | Null | https://github.com/redflyingfish/passport_and_backdoor_DNN_watermark | 0 | 0| 
| 20230120T14:00:02Z | The BackDoor of HIPHP gives you the power to control websites based on PHP using HTTP/HTTPS protocol. By sending files, tokens and commands through port 80%s POST/GET method, users can access a range of activities such as downloading and editing files. It also allows for connecting to Tor networks with password protection for extra security. | https://github.com/yasserbdj96/hiphp | 37 | 10| 
| 20230120T11:37:42Z | Anywhere is a powerful botnet that allows for the remote control of compromised devices | https://github.com/thisisnzed/Anywhere | 4 | 0| 
| 20230120T08:21:56Z | Null | https://github.com/TheOrangeDev/IcedOutBackdoor | 0 | 0| 
| 20230120T07:00:32Z | Null | https://github.com/SohamRoy05/Python-Backdoor | 0 | 0| 
| 20230120T00:06:26Z | Un simple backdoor en bash , ejecutar en un entorno controlado o fuera de mi responsabilidad . | https://github.com/Yimb3r/Red-Socks | 0 | 0| 
| 20230119T21:18:12Z | Null | https://github.com/wcenatus/backdoor-nextjs | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T19:03:42Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3278 | 466| 
| 20230120T09:37:14Z | radius2 is a fast binary emulation and symbolic execution framework using radare2 | https://github.com/aemmitt-ns/radius | 311 | 24| 
| 20230120T07:17:14Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 290 | 67| 
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
| 20230119T20:04:55Z | find relevant security papers published in the top-4 conferences (S&P, USENIX, CCS, NDSS) | https://github.com/Kyle-Kyle/top4grep | 28 | 2| 
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
| 20230121T01:29:29Z | Null | https://github.com/joyceohiri1/fuzzy-octo-rotary-phone | 0 | 0| 
| 20230120T23:08:46Z | Fast approximate string matching. | https://github.com/tomukmatthews/fuzzy-lightning | 3 | 0| 
| 20230120T22:47:02Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2639 | 180| 
| 20230120T21:49:15Z | Null | https://github.com/gabycaballeroduran/fuzzy-invention | 0 | 0| 
| 20230120T21:11:15Z | Revizor - a fuzzer that searches for microarchitectural leaks in CPUs | https://github.com/microsoft/sca-fuzzer | 40 | 18| 
| 20230120T21:00:18Z | Fuzz your Rust code with Google-developed Honggfuzz ! | https://github.com/rust-fuzz/honggfuzz-rs | 374 | 38| 
| 20230120T20:56:02Z | Uni project for Machine Learning | https://github.com/adam-struharnansky/project_ml_fuzzy | 0 | 0| 
| 20230120T17:14:18Z | Fuzz Distortion | https://github.com/revertcreations/fuzzywuzzy | 0 | 0| 
| 20230120T14:25:40Z | Official repository  vuls Scan: 15000+PoCs; 23 kinds of application password crack; 7000+Web fingerprints; 146 protocols and 90000+ rules Port scanning; Fuzz, HW, awesome BugBounty( ͡° ͜ʖ ͡°)... | https://github.com/hktalent/scan4all | 3372 | 400| 
| 20230120T13:55:46Z | Null | https://github.com/TINGWEIJING/Diabetes-Prediction-Using-Fuzzy-Logic | 0 | 0| 



# 日更新程序
