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


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230120T13:31:06Z | CVE-2021-37500 | Directory traversal vulnerability in Reprise License Manager (RLM) web interface before 14.2BL4 in the diagnostics function that allows RLM users with sufficient privileges to overwrite any file the on the server. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-37500 | | 
| 20230120T13:31:02Z | CVE-2021-37499 | CRLF vulnerability in Reprise License Manager (RLM) web interface through 14.2BL4 in the password parameter in View License Result function, that allows remote attackers to inject arbitrary HTTP headers. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-37499 | | 
| 20230120T13:30:58Z | CVE-2021-37498 | An SSRF issue was discovered in Reprise License Manager (RLM) web interface through 14.2BL4 that allows remote attackers to trigger outbound requests to intranet servers, conduct port scans via the actserver parameter in License Activation function. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-37498 | | 
| 20230120T11:32:19Z | CVE-2023-23163 | Null | https://github.com/rahulpatwari/CVE-2023-23163 | | 
| 20230120T11:31:37Z | CVE-2023-23162 | Null | https://github.com/rahulpatwari/CVE-2023-23162 | | 
| 20230120T11:28:30Z | CVE-2023-23161 | Null | https://github.com/rahulpatwari/CVE-2023-23161 | | 
| 20230120T11:18:46Z | CVE-2022-4616 | The webserver in Delta DX-3021 versions prior to 1.24 is vulnerable to command injection through the network diagnosis page. This vulnerability could allow a remote unauthenticated user to add files, delete files, and change file permissions. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4616 | | 
| 20230120T11:18:42Z | CVE-2022-39186 | EXFO - BV-10 Performance Endpoint Unit misconfiguration. System configuration file has misconfigured permissions CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-39186 | | 
| 20230120T11:18:31Z | CVE-2023-0227 | Insufficient Session Expiration in GitHub repository pyload/pyload prior to 0.5.0b3.dev36. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0227 | | 
| 20230120T11:18:27Z | CVE-2022-3437 | A heap-based buffer overflow vulnerability was found in Samba within the GSSAPI unwrap_des() and unwrap_des3() routines of Heimdal. The DES and Triple-DES decryption routines in the Heimdal GSSAPI library allow a length-limited write buffer overflow on malloc() allocated memory when presented with a maliciously small p CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-3437 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T12:19:04Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 198 | 1| 
| 20230120T12:07:28Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10120 | 341| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T07:17:14Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 290 | 67| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T13:29:06Z | Kumpulan Alat untuk Exploitasi. | https://github.com/Xcod3bughunt3r/ExploitsTools | 0 | 0| 
| 20230120T11:35:46Z | This repository is primarily maintained by Omar Santos (@santosomar) and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 12619 | 2163| 
| 20230120T11:30:05Z | walkthrough with working Exploits. I am also uploading the ELF to practise | https://github.com/whoami546/binary-exploitation-walkthroughs | 0 | 0| 
| 20230120T11:18:23Z | Dell EMC PV ME5, versions ME5.1.0.0.0 and ME5.1.0.1.0, contains a Client-side desync Vulnerability. An unauthenticated attacker could potentially exploit this vulnerability to force a victim%s browser to desynchronize its connection with the website, typically leading to XSS and DoS. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-23691 | 0 | 0| 
| 20230120T11:17:15Z | This tool is used for backdoor and shellcode generation for various architecture devices | https://github.com/doudoudedi/hackEmbedded | 30 | 3| 
| 20230120T10:59:53Z | CTF Writeups from exploit-education | https://github.com/programmer838/Exploit-Education-Writeups | 0 | 0| 
| 20230120T10:41:22Z | venos is a tool for looking inside code exploiting it executing commands and more | https://github.com/abrahamlinconinhindi/venos | 0 | 0| 
| 20230120T10:29:05Z | Everything you need to build and run Linux and Android kernels for exploit development | https://github.com/gsingh93/linux-exploit-dev-env | 6 | 0| 
| 20230120T06:45:54Z | Improvement for Thaumaturge Exploit Vulnerability | https://github.com/mysurvive/pf2e-thaum-vuln | 1 | 0| 
| 20230120T02:55:28Z | MyBB 1.8.32 - Chained LFI Remote Code Execution (RCE) (Authenticated) python exploit script... | https://github.com/FDlucifer/mybb_1832_LFI_RCE | 1 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T12:09:08Z | Villain is a Windows & Linux backdoor generator and multi-session handler that allows users to connect with sibling servers (other machines running Villain) and share their backdoor sessions, handy for working as a team. | https://github.com/t3l3machus/Villain | 2281 | 385| 
| 20230120T11:37:42Z | Anywhere is a powerful botnet that allows for the remote control of compromised devices | https://github.com/thisisnzed/Anywhere | 4 | 0| 
| 20230120T11:17:15Z | This tool is used for backdoor and shellcode generation for various architecture devices | https://github.com/doudoudedi/hackEmbedded | 30 | 3| 
| 20230120T08:21:56Z | Null | https://github.com/TheOrangeDev/IcedOutBackdoor | 0 | 0| 
| 20230120T07:00:32Z | Null | https://github.com/SohamRoy05/Python-Backdoor | 0 | 0| 
| 20230120T05:07:34Z | Null | https://github.com/redflyingfish/passport_and_backdoor_DNN_watermark | 0 | 0| 
| 20230120T00:06:26Z | Un simple backdoor en bash , ejecutar en un entorno controlado o fuera de mi responsabilidad . | https://github.com/Yimb3r/Red-Socks | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T12:04:11Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3277 | 466| 
| 20230120T09:37:14Z | radius2 is a fast binary emulation and symbolic execution framework using radare2 | https://github.com/aemmitt-ns/radius | 311 | 24| 
| 20230120T07:17:14Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 290 | 67| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T13:55:46Z | Null | https://github.com/TINGWEIJING/Diabetes-Prediction-Using-Fuzzy-Logic | 0 | 0| 
| 20230120T13:22:57Z | Null | https://github.com/pizzaaa-steeeve/fuzzy-palm | 0 | 0| 
| 20230120T13:05:52Z | Opslagbestand | https://github.com/puppyguusje/fuzzy-disco | 0 | 0| 
| 20230120T12:46:41Z | Null | https://github.com/JaxToon/Fuzzy-Logic-Mamdani | 0 | 0| 
| 20230120T12:43:07Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 3347 | 671| 
| 20230120T12:14:49Z | Null | https://github.com/0nespo/Fuzzy-Mandani-Classification | 0 | 0| 
| 20230120T12:00:58Z | Null | https://github.com/ShapFuzz/ShapFuzz | 0 | 0| 
| 20230120T11:06:37Z | Null | https://github.com/akashrane/Fuzzy_Logic_Room_Temperature_Prediction | 0 | 0| 
| 20230120T11:06:24Z | Null | https://github.com/Prajwal-Jadhav/fuzzy-octo-bassoon | 0 | 0| 
| 20230120T10:45:51Z | Null | https://github.com/fuzzy-rotary-phone/fuzzy-rotary-phone.github.io | 0 | 0| 



# 日更新程序
