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


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230120T23:23:42Z | CVE-2020-16145 | Roundcube Webmail before 1.3.15 and 1.4.8 allows stored XSS in HTML messages during message display via a crafted SVG document. This issue has been fixed in 1.4.8 and 1.3.15. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-16145 | | 
| 20230120T23:23:38Z | CVE-2020-15953 | LibEtPan through 1.9.4, as used in MailCore 2 through 0.6.3 and other products, has a STARTTLS buffering issue that affects IMAP, SMTP, and POP3. When a server sends a "begin TLS" response, the client reads additional data (e.g., from a meddler-in-the-middle attacker) and evaluates it in a TLS context, aka "response in CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-15953 | | 
| 20230120T23:23:34Z | CVE-2023-24025 | CRYSTALS-DILITHIUM (in Post-Quantum Cryptography Selected Algorithms 2022) in PQClean d03da30 may allow universal forgeries of digital signatures via a template side-channel attack because of intermediate data leakage of one vector. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-24025 | | 
| 20230120T23:23:30Z | CVE-2023-23607 | erohtar/Dasherr is a dashboard for self-hosted services. In affected versions unrestricted file upload allows any unauthenticated user to execute arbitrary code on the server. The file /www/include/filesave.php allows for any file to uploaded to anywhere. If an attacker uploads a php file they can execute code on the s CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-23607 | | 
| 20230120T23:23:27Z | CVE-2021-33642 | When a file is processed, an infinite loop occurs in next_inline() of the more_curly() function. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-33642 | | 
| 20230120T23:23:23Z | CVE-2021-33641 | When processing files, malloc stores the data of the current line. When processing comments, malloc incorrectly accesses the released memory (use after free). CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-33641 | | 
| 20230120T23:23:19Z | CVE-2020-25502 | Cybereason EDR version 19.1.282 and above, 19.2.182 and above, 20.1.343 and above, and 20.2.X and above has a DLL hijacking vulnerability, which could allow a local attacker to execute code with elevated privileges. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-25502 | | 
| 20230120T23:23:09Z | CVE-2022-46732 | Even if the authentication fails for local service authentication, the requested command could still execute regardless of authentication status. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46732 | | 
| 20230120T23:23:05Z | CVE-2023-24028 | In MISP 2.4.167, app/Controller/Component/ACLComponent.php has incorrect access control for the decaying import function. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-24028 | | 
| 20230120T23:23:01Z | CVE-2023-24027 | In MISP 2.4.167, app/webroot/js/action_table.js allows XSS via a network history name. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-24027 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T18:52:06Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 10123 | 341| 
| 20230120T12:19:04Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 198 | 1| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T07:17:14Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 290 | 67| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T23:15:11Z | Null | https://github.com/GitHubUser12346457/Exploit | 0 | 0| 
| 20230120T23:03:39Z | While trying to hack into the HP DeskJet 2700 I found a way to cause a Denial of Service on the admin login page by changing the login cookie and the authorization token in each request | https://github.com/temoc1n/HP-DeskJet-2700-DoS-Exploit- | 1 | 0| 
| 20230120T22:36:16Z | Bukkit plugin that aims on fixing Exploits in your Minecraft network. [Requires HamsterAPI to work] | https://github.com/2lstudios-mc/ExploitFixer | 180 | 51| 
| 20230120T22:35:09Z | Our main goal is to share tips from some well-known bughunters. Using recon methodology, we are able to find subdomains, apis, and tokens that are already exploitable, so we can report them. We wish to influence Onelinetips and explain the commands, for the better understanding of new hunters.. | https://github.com/KingOfBugbounty/KingOfBugBountyTips | 3325 | 640| 
| 20230120T22:18:22Z | IBM Cognos Analytics 11.0 and 11.1 allows overly permissive cross-origin resource sharing which could allow an attacker to transfer private information. An attacker could exploit this vulnerability to access content that should be restricted. IBM X-Force ID: 161422. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2019-4343 | 0 | 0| 
| 20230120T22:18:11Z | A vulnerability, which was classified as problematic, was found in earclink ESPCMS P8.21120101. Affected is an unknown function of the component Content Handler. The manipulation leads to cross site scripting. It is possible to launch the attack remotely. The exploit has been disclosed to the public and may be used. VD CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0246 | 0 | 0| 
| 20230120T22:17:59Z | A vulnerability classified as critical was found in TuziCMS 2.0.6. This vulnerability affects the function delall of the file \App\Manage\Controller\KefuController.class.php. The manipulation of the argument id leads to sql injection. The attack can be initiated remotely. The exploit has been disclosed to the public an CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0244 | 0 | 0| 
| 20230120T13:29:06Z | Kumpulan Alat untuk Exploitasi. | https://github.com/Xcod3bughunt3r/ExploitsTools | 0 | 0| 
| 20230120T11:35:46Z | This repository is primarily maintained by Omar Santos (@santosomar) and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 12619 | 2163| 
| 20230120T11:30:05Z | walkthrough with working Exploits. I am also uploading the ELF to practise | https://github.com/whoami546/binary-exploitation-walkthroughs | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T23:02:38Z | This tool is used for backdoor and shellcode generation for various architecture devices | https://github.com/doudoudedi/hackEmbedded | 31 | 3| 
| 20230120T17:38:05Z | Null | https://github.com/kaster-san/backdoors | 0 | 0| 
| 20230120T16:56:02Z | Null | https://github.com/redflyingfish/passport_and_backdoor_DNN_watermark | 0 | 0| 
| 20230120T14:00:02Z | The BackDoor of HIPHP gives you the power to control websites based on PHP using HTTP/HTTPS protocol. By sending files, tokens and commands through port 80%s POST/GET method, users can access a range of activities such as downloading and editing files. It also allows for connecting to Tor networks with password protection for extra security. | https://github.com/yasserbdj96/hiphp | 37 | 10| 
| 20230120T11:37:42Z | Anywhere is a powerful botnet that allows for the remote control of compromised devices | https://github.com/thisisnzed/Anywhere | 4 | 0| 
| 20230120T08:21:56Z | Null | https://github.com/TheOrangeDev/IcedOutBackdoor | 0 | 0| 
| 20230120T07:00:32Z | Null | https://github.com/SohamRoy05/Python-Backdoor | 0 | 0| 
| 20230120T00:06:26Z | Un simple backdoor en bash , ejecutar en un entorno controlado o fuera de mi responsabilidad . | https://github.com/Yimb3r/Red-Socks | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T19:03:42Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3278 | 466| 
| 20230120T09:37:14Z | radius2 is a fast binary emulation and symbolic execution framework using radare2 | https://github.com/aemmitt-ns/radius | 311 | 24| 
| 20230120T07:17:14Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 290 | 67| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230120T23:08:46Z | Fast approximate string matching. | https://github.com/tomukmatthews/fuzzy-lightning | 3 | 0| 
| 20230120T22:47:02Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2639 | 180| 
| 20230120T21:49:15Z | Null | https://github.com/gabycaballeroduran/fuzzy-invention | 0 | 0| 
| 20230120T21:11:15Z | Revizor - a fuzzer that searches for microarchitectural leaks in CPUs | https://github.com/microsoft/sca-fuzzer | 40 | 18| 
| 20230120T21:00:18Z | Fuzz your Rust code with Google-developed Honggfuzz ! | https://github.com/rust-fuzz/honggfuzz-rs | 374 | 38| 
| 20230120T20:56:02Z | Uni project for Machine Learning | https://github.com/adam-struharnansky/project_ml_fuzzy | 0 | 0| 
| 20230120T17:14:18Z | Fuzz Distortion | https://github.com/revertcreations/fuzzywuzzy | 0 | 0| 
| 20230120T14:25:40Z | Official repository  vuls Scan: 15000+PoCs; 23 kinds of application password crack; 7000+Web fingerprints; 146 protocols and 90000+ rules Port scanning; Fuzz, HW, awesome BugBounty( ͡° ͜ʖ ͡°)... | https://github.com/hktalent/scan4all | 3372 | 400| 
| 20230120T13:55:46Z | Null | https://github.com/TINGWEIJING/Diabetes-Prediction-Using-Fuzzy-Logic | 0 | 0| 
| 20230120T13:22:57Z | Null | https://github.com/pizzaaa-steeeve/fuzzy-palm | 0 | 0| 



# 日更新程序
