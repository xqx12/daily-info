# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210204 | GitHub Security Lab 已披露的漏洞公告列表 | https://securitylab.github.com/advisories/| 
| 20210204 | Realtek RTL8195A Wi-Fi 模块被发现多个高危漏洞 | https://www.vdoo.com/blog/realtek-rtl8195a-vulnerabilities-discovered/| 
| 20210204 | Facebook Messenger Desktop App Arbitrary File Read | https://medium.com/@renwa/facebook-messenger-desktop-app-arbitrary-file-read-db2374550f6d| 
| 20210204 | Endpoint Detection and Response: How Hackers Have Evolved | https://www.optiv.com/explore-optiv-insights/source-zero/endpoint-detection-and-response-how-hackers-have-evolved| 
| 20210204 | How I was able to Turn a XSS into a Account Takeover | https://pullerjsecu.medium.com/how-i-was-able-to-turn-a-xss-into-a-account-takeover-ae0c478640e7| 
| 20210204 | ScareCrow - 自动化生成 EDR 软件 Bypass Payload 的工具 | https://github.com/optiv/ScareCrow| 
| 20210204 | VDSO As A Potential KASLR Oracle | https://www.longterm.io/vdso_sidechannel.html| 
| 20210204 | 通过复制智能卡欺骗 Nespresso 咖啡机 | http://pollevanhoof.be/nuggets/smart_cards/nespresso| 
| 20210204 | Security Scorecards - 开源组件安全健康度衡量工具 | https://github.com/ossf/scorecard| 
| 20210204 | Google 计划从构建精确漏洞库、开源组件依赖分析、高危漏洞通知预警等角度推动建立开源组件的安全生态 | https://sec.today/pulses/ffc52689-445f-4585-a35c-59bd55067be3/| 
| 20210204 | Google 计划从构建精确漏洞库、开源组件依赖分析、高危漏洞通知预警等角度推动建立开源组件的安全生态 | https://security.googleblog.com/2021/02/know-prevent-fix-framework-for-shifting.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+GoogleOnlineSecurityBlog+%28Google+Online+Security+Blog%29| 
| 20210204 | 漏洞焦点：SoftMaker Office PlanMaker存在的多个安全漏洞。 | https://blog.talosintelligence.com/2021/02/vuln-spotlight-softmaker-office-planmaker.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+feedburner%2FTalos+%28Talos%E2%84%A2+Blog%29| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210204 | 2021HWS冬令营线上赛固件安全-WriteUp | https://mp.weixin.qq.com/s/fwbFMHuVdX-FNa7dB5mw0Q| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210204T23:38:03Z | CVE-2021-3156 | Null | https://github.com/blasty/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210204T17:38:43Z | CVE-2020-5902 | simple bash script of F5 BIG-IP CVE-2020-5902 checker | https://github.com/faisalfs10x/F5-BIG-IP-CVE-2020-5902-checker | In BIG-IP versions 15.0.0-15.1.0.3, 14.1.0-14.1.2.5, 13.1.0-13.1.3.3, 12.1.0-12.1.5.1, and 11.6.1-11.6.5.1, the Traffic Management User Interface (TMUI), also referred to as the Configuration utility, has a Remote Code Execution (RCE) vulnerability in undisclosed pages.| 
| 20210204T17:38:27Z | CVE-2020-3452 | simple bash script of Cisco CVE-2020-3452 checker  | https://github.com/faisalfs10x/Cisco-CVE-2020-3452-checker | A vulnerability in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct directory traversal attacks and read sensitive files on a targeted system. The vulnerability is due to a lack of proper input validation of URLs in HTTP requests processed by an affected device. An attacker could exploit this vulnerability by sending a crafted HTTP request containing directory traversal character sequences to an affected device. A successful exploit could allow the attacker to view arbitrary files within the web services file system on the targeted device. The web services file system is enabled when the affected device is configured with either WebVPN or AnyConnect features. This vulnerability cannot be used to obtain access to ASA or FTD system files or underlying operating system (OS) files.| 
| 20210204T13:35:06Z | CVE-2021-3156 | Root shell PoC for CVE-2021-3156 | https://github.com/CptGibbon/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210204T13:05:02Z | CVE-2021-25646 | CSharp CVE-2021-25646-GUI | https://github.com/AirEvan/CVE-2021-25646-GUI | Apache Druid includes the ability to execute user-provided JavaScript code embedded in various types of requests. This functionality is intended for use in high-trust environments, and is disabled by default. However, in Druid 0.20.0 and earlier, it is possible for an authenticated user to send a specially-crafted request that forces Druid to run user-provided JavaScript code for that request, regardless of server configuration. This can be leveraged to execute code on the target machine with the privileges of the Druid server process.| 
| 20210204T07:51:56Z | CVE-2021-3156 | CVE-2021-3156 Vagrant Lab | https://github.com/dinhbaouit/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210204T07:47:48Z | cve-2021-25646 | Apache Druid 远程代码执行;检测脚本 | https://github.com/yaunsky/cve-2021-25646 | 未查询到CVE信息| 
| 20210204T06:16:27Z | CVE-2021-3156 | Null | https://github.com/leterts/CVE-2021-3156-sudo-raising | | 
| 20210204T02:20:26Z | cve-2020-17523 | shiro-cve-2020-17523 漏洞分析 | https://github.com/jweny/shiro-cve-2020-17523 | 未查询到CVE信息| 
| 20210204T01:40:33Z | CVE-2021-25646 | Null | https://github.com/lp008/CVE-2021-25646 | Apache Druid includes the ability to execute user-provided JavaScript code embedded in various types of requests. This functionality is intended for use in high-trust environments, and is disabled by default. However, in Druid 0.20.0 and earlier, it is possible for an authenticated user to send a specially-crafted request that forces Druid to run user-provided JavaScript code for that request, regardless of server configuration. This can be leveraged to execute code on the target machine with the privileges of the Druid server process.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210204T23:50:58Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 5 | 1| 
| 20210204T22:44:58Z | hw3-klee8880 created by GitHub Classroom | https://github.com/depaulcdm/hw3-klee8880 | 0 | 0| 
| 20210204T18:45:55Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 107 | 6| 
| 20210204T17:38:30Z | Proyecto universitario donde se presenta una solucion C++(Visual Studio) a una variante del clasico problema de la galeria de arte propuesto incialmente por Victor Klee en 1973 | https://github.com/arielbertino/Galeria-de-Arte | 0 | 0| 
| 20210204T15:58:20Z | ⬇️ File Upload/sharing application, used by thousands of webmasters since 2007.  | https://github.com/kleeja-official/kleeja | 111 | 33| 
| 20210204T14:08:04Z | Null | https://github.com/fontworks-fonts/Klee | 352 | 9| 
| 20210204T13:10:41Z | Klee Work Adventure | https://github.com/r-bdns/kwa | 0 | 0| 
| 20210204T12:01:52Z | The compiler inputs a PDDL benchmark of the Carpark planning problem and converts it to an equivalent C code which is used for solving the planning problem by program verification tools such as KLEE/TracerX. | https://github.com/daneshvar-amrollahi/Carpark-PDDL2C | 0 | 0| 
| 20210204T07:05:33Z | Null | https://github.com/jiseongg/klee_experiment | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210204T23:55:03Z | Null | https://github.com/mikeydamootz/Exploits | 0 | 0| 
| 20210204T23:54:49Z | Script that lets you enter in an IP address and it will search through the the services to find the CPE%s within the system and scan them to see if the system contains any Common Vulnerabilities and Exploits (CVE%s) according to the Vulner%s API database. | https://github.com/Milo924/Vulners-Report | 0 | 0| 
| 20210204T23:51:09Z | Thi powershell script has got to run in remote windows host, even for pivoting | https://github.com/FabioDefilippo/winallenum | 0 | 1| 
| 20210204T23:31:55Z | free aram boost | https://github.com/devshadows/aram-exploit | 0 | 0| 
| 20210204T23:31:41Z | This is my version of %Settlers of Catan%. The game is ostensibly complete with the exception of slow repainting when the robber is moved. Other than that, the game is functionally finished. The game plays best on a screen 1920x1080 as that enables status screens to be visible if 3-4 players are playing. A shortcut key has been implemented for cancellation of actions. Hold ALT_C when the Catan Board has focus, and this will enable an OptionPane to appear that allows for cancellation. And as for game additions I wanted to talk about, I have implemented a class system to the game that makes it more difficult (it is optional; choose the settler class if you want the standard game) as well as optional cataclysm events that can affect player resources at a 5% chance. As well, ports are optional as I%ve heard some people say they are too exploitable. Again, these three things are optional. And finally, all the image files used in this game are not my own. They are all sourced from Google Images (non-copyrighted, as far as I can tell). I will continue to work on the slow repaint issue in the future, but I will put this project down for a little while. (For whatever reason, I can%t put new lines in the description because of arbitrary code rules, so this jumbled mess of words is what I must put). | https://github.com/GitCaseyHub/SettlersOfCatan | 0 | 0| 
| 20210204T23:09:18Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 4 | 1| 
| 20210204T22:53:02Z | Null | https://github.com/Rolexboy88cool/EoSHubExploit | 0 | 0| 
| 20210204T21:49:08Z | Vulnerabilities% Risk of Exploitation | https://github.com/thiagofigcosta/V-REx | 0 | 0| 
| 20210204T21:40:10Z | DDoS Scripts, L4+L7, Exploits itd.. | https://github.com/notrengele/DDoS_Scripts | 0 | 0| 
| 20210204T21:21:33Z | Null | https://github.com/NoTySrry/NoTysExploit | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210204T23:47:05Z | Three sub-projects of different backdoor attack configurations scaling in complexity, with server and client implementations. | https://github.com/BrunoScaglione/Backdoor-Attack-Simulation | 0 | 0| 
| 20210204T22:34:58Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 38 | 8| 
| 20210204T21:07:29Z | Null | https://github.com/mikkelskov1/backdoor2 | 0 | 0| 
| 20210204T20:04:22Z | Open-Source PowerShell module to allow online play of Backdoors & Breaches card game devised by Black Hills Information Security | https://github.com/TheShiShiLion/BackdoorsAndBreaches | 6 | 0| 
| 20210204T18:53:27Z | Null | https://github.com/odilov/simple-backdoor | 0 | 0| 
| 20210204T17:22:09Z | AdvDoor: Adversarial Backdoor Attack of Deep Learning System | https://github.com/Anonymous-AdvDoor/AdvDoor | 0 | 0| 
| 20210204T14:20:24Z | Bilingual PhishingKit. TigerShark intergrates a vast array of various phishing tools and frameworks, from C2 servers, backdoors and delivery methods in multiple scripting languages in order to suit whatever your deployment needs may be. | https://github.com/s1l3nt78/TigerShark | 188 | 29| 
| 20210204T14:09:18Z | FUD cross-platform python2 backdoor with C2 | https://github.com/7h3w4lk3r/pyback | 15 | 5| 
| 20210204T10:51:10Z | Null | https://github.com/rabbitx1337/backdoor | 0 | 0| 
| 20210204T10:47:01Z | STILL WORK IN PROGRESS | https://github.com/MatthewHardcastle/-WIP-Backdoor | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210204T13:55:22Z | saphIR is an Intermediate Representation with amd64 and arm64 backends. Also included: a compiler, an arm64 lifter, an arm64 to amd64 dynamic binary translator, and a fuzzer. | https://github.com/balayette/saphIR-project | 22 | 0| 
| 20210204T13:44:26Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 5839 | 1178| 
| 20210204T13:35:54Z | SecLists is the security tester%s companion. It%s a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. | https://github.com/danielmiessler/SecLists | 29703 | 15019| 
| 20210204T12:34:34Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2261 | 117| 
| 20210204T12:28:47Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3332 | 770| 
| 20210204T11:51:40Z | Scripts written by me, which might be useful later -> Devops work | https://github.com/Cy83rr/fuzzy-memory | 0 | 0| 
| 20210204T11:36:19Z | Null | https://github.com/ivicanikolicsg/SivoFuzzer | 0 | 0| 
| 20210204T11:20:02Z | Null | https://github.com/ArijZouaoui/Credit-Scoring-using-Fuzzy-Logic | 0 | 0| 
| 20210204T11:10:34Z | Null | https://github.com/stuartelimu/fuzzy-octo-carnival | 0 | 0| 
| 20210204T11:06:37Z | A fork of AFL for fuzzing Windows binaries | https://github.com/googleprojectzero/winafl | 1601 | 416| 



# 日更新程序
