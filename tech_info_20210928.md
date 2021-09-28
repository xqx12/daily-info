# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210928 | VSCode 远程开发扩展在处理 vscode-remote ssh 参数时存在命令执行漏洞 | https://www.shielder.it/advisories/remote-command-execution-in-visual-studio-code-remote-development-extension/| 
| 20210928 | ASUS ROG Armoury Crate Lite Service v4.2.8 (CVE-2021-40981) 提权漏洞的分析 | https://aptw.tf/2021/09/24/armoury-crate-privesc.html| 
| 20210928 | SADDNS: Side Channel Based DNS Cache Poisoning Attack | https://github.com/seclab-ucr/SADDNS| 
| 20210928 | Victure IPC360 摄像头多个高危漏洞的分析 | https://www.bitdefender.com/files/News/CaseStudies/study/402/Bitdefender-PR-Whitepaper-VictureIPC-creat5590-en-EN.pdf| 
| 20210928 | 整数处理相关的溢出、截断等漏洞的挖掘 | https://maxwelldulin.com/BlogPost?post=9715056640| 
| 20210928 | v8 脚本引擎 CVE-2021-30632 类型混淆漏洞的分析 | https://securitylab.github.com/research/in_the_wild_chrome_cve_2021_30632/| 
| 20210928 | 卡巴斯基对俄罗斯黑市论坛上一款 BloodyStealer 恶意软件的分析 | https://securelist.com/bloodystealer-and-gaming-assets-for-sale/104319/| 
| 20210928 | 实例分析 DiscuzX 3.4 SSRF漏洞 | http://blog.topsec.com.cn/discuzx-3-4-ssrf/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210928T11:44:00Z | CVE-2021-36563 | Null | https://github.com/Edgarloyola/CVE-2021-36563 | The CheckMK management web console (versions 1.5.0 to 2.0.0) does not sanitise user input in various parameters of the WATO module. This allows an attacker to open a backdoor on the device with HTML content and interpreted by the browser (such as JavaScript or other client-side scripts), the XSS payload will be triggered when the user accesses some specific sections of the application. In the same sense a very dangerous potential way would be when an attacker who has the monitor role (not administrator) manages to get a stored XSS to steal the secretAutomation (for the use of the API in administrator mode) and thus be able to create another administrator user who has high privileges on the CheckMK monitoring web console. Another way is that persistent XSS allows an attacker to modify the displayed content or change the victim%s information. Successful exploitation requires access to the web management interface, either with valid credentials or with a hijacked session.| 
| 20210928T11:39:44Z | CVE-2021-30632 | Null | https://github.com/Lagal1990/CVE-2021-30632 | | 
| 20210928T08:53:13Z | CVE-2021-40346 | CVE-2021-40346 integer overflow enables http smuggling | https://github.com/donky16/CVE-2021-40346-POC | An integer overflow exists in HAProxy 2.0 through 2.5 in htx_add_header that can be exploited to perform an HTTP request smuggling attack, allowing an attacker to bypass all configured http-request HAProxy ACLs and possibly other ACLs.| 
| 20210928T08:48:35Z | CVE-2021-22005 | CVE-2021-22005 - VMWare vCenter Server File Upload to RCE | https://github.com/r0ckysec/CVE-2021-22005 | The vCenter Server contains an arbitrary file upload vulnerability in the Analytics service. A malicious actor with network access to port 443 on vCenter Server may exploit this issue to execute code on vCenter Server by uploading a specially crafted file.| 
| 20210928T07:23:57Z | CVE-2021-35042 | Null | https://github.com/r4vi/CVE-2021-35042 | Django 3.1.x before 3.1.13 and 3.2.x before 3.2.5 allows QuerySet.order_by SQL injection if order_by is untrusted input from a client of a web application.| 
| 20210928T07:15:57Z | CVE-2021-40444 | CVE 2021 40444 Windows Exploit services.dll | https://github.com/kal1gh0st/CVE-2021-40444_CAB_archives | Microsoft MSHTML Remote Code Execution Vulnerability| 
| 20210928T06:34:47Z | CVE-2021-22005 | CVE-2021-22005_PoC | https://github.com/RedTeamExp/CVE-2021-22005_PoC | The vCenter Server contains an arbitrary file upload vulnerability in the Analytics service. A malicious actor with network access to port 443 on vCenter Server may exploit this issue to execute code on vCenter Server by uploading a specially crafted file.| 
| 20210928T05:25:07Z | CVE-2021-22005 | CVE-2021-22005批量验证python脚本 | https://github.com/5gstudent/CVE-2021-22005- | The vCenter Server contains an arbitrary file upload vulnerability in the Analytics service. A malicious actor with network access to port 443 on vCenter Server may exploit this issue to execute code on vCenter Server by uploading a specially crafted file.| 
| 20210928T04:08:46Z | CVE-2021-3493 | Ubuntu OverlayFS Local Privesc | https://github.com/briskets/CVE-2021-3493 | The overlayfs implementation in the linux kernel did not properly validate with respect to user namespaces the setting of file capabilities on files in an underlying file system. Due to the combination of unprivileged user namespaces along with a patch carried in the Ubuntu kernel to allow unprivileged overlay mounts, an attacker could use this to gain elevated privileges.| 
| 20210928T03:40:15Z | CVE-2021-40444 | CVE-2021-40444 - Fully Weaponized Microsoft Office Word RCE Exploit | https://github.com/klezVirus/CVE-2021-40444 | Microsoft MSHTML Remote Code Execution Vulnerability| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210928T11:05:12Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1789 | 507| 
| 20210928T10:32:39Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2799 | 76| 
| 20210928T08:31:49Z | Website for the KLEE project: https://klee.github.io/ | https://github.com/klee/klee.github.io | 14 | 45| 
| 20210928T07:27:14Z | Null | https://github.com/CinquinAndy/klee-green-it-app | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210928T09:16:38Z | Null | https://github.com/yuvalkirstain/s2e-coref | 15 | 6| 
| 20210928T04:36:25Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 158 | 37| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210928T12:37:11Z | Roblox exploit under development | https://github.com/Unknown3958/UnknownExploit | 0 | 0| 
| 20210928T12:33:51Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 10140 | 1708| 
| 20210928T12:02:59Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 32 | 19| 
| 20210928T11:40:50Z | BioCCP.jl exploits the Coupon Collector Problem for sample size determination in combinatorial biotechnology. | https://github.com/kirstvh/BioCCP.jl | 3 | 0| 
| 20210928T11:34:16Z | In case you are an entrepreneur and you need to stay aware of the recently digitized, innovation driven world then you can%t overlook digital marketing. There are a developing and extremely worthwhile online commercial center and digital marketing can assist you with catching that. Digital marketing is the way towards pulling in designated crowds online that will be the differentiation between a successfully prospering business – and a bombed one. Whether or not you get enormous measures of traffic to your site, it would not amount to anything aside from on the off chance that they don%t change over to leads or deal. In the digital field where business and trade are making a shortcut to, Digital Marketing tools and strategies outfit business people with the best opportunities for contest, endurance and even business improvement. Assuming you are as yet not influenced, here are eight additional reasons that express the significance of digital marketing for your business.  1. Levels the Online Playing Field:  Old thoughts and ideas of huge worldwide companies and associations having the assets to support a web based showcasing effort are repetitive at this point. Digital marketing truly levels the chances, offering small and medium organizations the chance to battle with the enormous partnership%s n and attract a great deal of designated traffic. With digital marketing, small associations presently have the resources for perform deals and showcasing measures that were at that point open just too huge enterprises. Without a call place, small organizations can associate satisfactorily with different customers, even with customers from any part of the world whether or not they have actual stores or branches in those spaces. This is the premier motivation behind why digital marketing is significant for your business.  2. You Will Get to Know Your Audience and Market Share Better:  Customer awareness for online facilities may be thought little of if you haven%t investigated your online crowd and market share. Perhaps, more fundamentally, you will not appreciate your online commercial center: the components will be particular to traditional channels with different kinds of customer profile and conduct, competitors, recommendations, and alternatives for promoting interchanges. There are remarkable gadgets available from the standard advanced stages where you can decide the level of customer request which is the reason digital marketing is so significant for your private company. It is good that you do a pursuit whole investigation utilizing Google%s Keyword organizer to see how you are exploiting the aim of searchers to attract them to your site or see what number of people charmed by things or administrations or divisions you could reach through Facebook IQ.  3. Advanced Marketing More Cost-Effective than Traditional Marketing:  More modest organizations have close to no resources and even capitalization. This is the motive digital marketing gives them an unrivaled and significantly savvier publicizing channel that passes on outcomes. A new overview included that up to 40% of respondents pronounced to get great reserve funds by using digital marketing procedures for advancements of their items and services. The outline moreover communicates that 28% of business owners surveyed will move marketing use assignments from standard media diverts and put them in digital online media techniques and methods. According to HubSpot, digital advertisers give indications of worked on Cost-Per-Lead (CPL) stood out from other advancing channels. This is when the greater part of them understands the force and significance of digital marketing for private ventures.  4. Computerized Marketing Will Help You Generate Better Revenues:  Expanded transformation rates created by amazing digital marketing techniques will pass on stacks of valuable benefits for yourself as well as your business as far as better and higher incomes which is the reason digital marketing is significant for organizations in this digital age. A review directed on the point guarantees that there is 2.8 occasions better pay development anticipation for associations using digital marketing philosophies to the people who don%t. With better pay development expectation, little and medium endeavors using digital marketing strategies will have 3.3 occasions better chances of expanding their workforce and business – offering them chances to better, greater and farther arriving at business areas both locally and globally.  5. Advanced Marketing Will Increase Your Conversion Rates:  Associations publicizing things and administrations online measure achievement by the rate pace of approaching traffic which get changed into leads, endorsers or arrangements, dependent upon the planned inspirations driving your website. Without transformation, all your traffic would turn out to mean nothing and all your advancing undertakings will simply go to squander that is the explanation business visionaries are smoothing out their digital marketing endeavors towards change advancement, zeroing in on it above all the other things. There are a couple of tools and strategies that you can use for your digital marketing efforts, for instance, Search Engine Optimization, social media-based advertising and email commercials. These three produce fast and incredible correspondence and joint effort with designated crowds and will pass on better than normal results as far as higher affirmation rates. This is the significant explanation each business in the present time knows about the significance of digital marketing and are vigorously putting resources into it.  6. Computerized Marketing Will Build the Reputation of Your Brand:  The power of computerized showcasing lies in its ability for pulling in designated crowds. These sorts of groups for your substance are without question adequately ready to look into your image, items or benefits and may be sufficiently fascinated to purchase what you offer. Following through on what you ensured will help you with developing a prevalent relationship with your main interest group, help them with the progress into paying customers that will return and connect with your site all the more routinely and reliably. This will be worthwhile for your image, as satisfied customers will most likely edify others concerning their inclusion in your image, thing or administration. Your image will become popular on the web, further opening new entrances of opportunities for showing up at more prominent business sectors and accomplish business advancement.   7. Advanced Marketing Helps Facilitate Communication with Targeted Audiences:  One motivation behind why digital marketing is significant for organizations in 2021 and is taking over ordinary promoting channels is the limit of Internet advertising instruments to associate with interest groups progressively. Commitment in any design is what your customers desire to get while teaming up with your image or business. How your business handles such commitment and associations will spell the differentiation between a fruitful business and disillusionment. Working together and outfitting your customers with real commitment can give you an information into what your objective groups need. This fundamental information will direct you towards making the right arrangement of next moves, give your customers an obviously better encounter, develop incredible relationship with them – eventually acquiring their resolute trust that you will require when your business begins to create.  8. Advanced Marketing Will Entice Your Consumers to Take Favorable Actions:  While tributes assist with obtaining trust from centered groups, Digital Marketing uses convincing systems like SEO technique, web-based media promoting procedure, media methodology and so forth that will draw people to make a favorable activity your picture or business needs them to take. Change to leads or arrangements is as yet begun and under full control by the guest of the site. They are not compelled to do as such, be that as it may, computerized advertisers can use brilliant and innovative ways to deal with appeal change using Calls-To-Action. Suggestions to take action figures out what your web visitors should do straight away – either to join, download something, call or buy – unequivocal advances that will bait them to play out an extraordinary action. Imaginative designs, structures and messages are smoothed out by copy, shading plans, and delineations and even, arranged on the page to deliver the best results similar to making ideal activity.  This carries us to the furthest limit of the rundown of top 8 reasons that demonstrate the significance of computerized advertising for independent ventures in 2021. Advanced advertising has become fundamental for the endurance of organizations. Numerous physical stores are leaving business since you can purchase nearly everything on the web. Yet, even with an online store, it isn%t sufficient just to have many guests to your site. You need your guests to change over into clients for your store to endure. Advanced advertising will assist you with utilizing brilliant, imaginative and viable procedures that will build your transformation rates and thus sway your incomes. Advanced advertising is tied in with focusing on the perfect individuals and eventually guaranteeing the endurance of your business. We are a ROI-driven computerized promoting organization in Mumbai that can assist your business with becoming on the web by offering types of assistance like, online media advertising, SEO showcasing. Web advancement and so on and making successful computerized promoting systems for your business and keeping at standard with all the most recent computerized showcasing patterns. | https://github.com/Payal1995dot/The-Importance-of-Digital-Marketing-for-private-venture-in-2021- | 0 | 0| 
| 20210928T11:08:40Z | This is a repository of exploits that helps in pentest. | https://github.com/TarunYenni/exploits | 0 | 0| 
| 20210928T11:05:54Z | This is an optimized and efficient scene segmentation model which exploits multi-scale feature fusion technique for capturing contextual information from the scene. This model produces less parameters and FLOPS compare to many existing real-time scene segmentation model. | https://github.com/tanmaysingha/FANet | 3 | 2| 
| 20210928T11:03:30Z | Ways to bypass school restrictions and collect data | https://github.com/itsjaylen/SchoolExploits | 0 | 0| 
| 20210928T10:22:31Z | Exploitdb Twitter bot | https://github.com/dedsxc/bot_exploitdb | 0 | 0| 
| 20210928T10:09:17Z | Evolving computational sustainability in rapidly changing exploited ecosystems | https://github.com/melian009/Deepbios | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210928T11:25:11Z | Unofficial pytorch implementation of RobNet(Defense-Resistant Backdoor Attacks on DNN) | https://github.com/dhkim2810/RobNet | 0 | 0| 
| 20210928T09:10:36Z | Apache Tomcat auto WAR deployment & pwning penetration testing tool. | https://github.com/mgeeky/tomcatWarDeployer | 314 | 118| 
| 20210928T08:48:42Z | Remote control software | https://github.com/h1zzz/purewater | 0 | 0| 
| 20210928T07:32:48Z | Not mine | https://github.com/luke-beep/backdoor | 0 | 0| 
| 20210928T06:53:08Z | backdoored ECDSA signatures yum! | https://github.com/oreparaz/backdoor-ecdsa | 0 | 0| 
| 20210928T03:15:37Z | Code for EMNLP 2021 paper: Backdoor Attacks on Pre-trained Models by Layerwise Weight Poisoning | https://github.com/LinyangLee/Layer-Weight-Poison | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210928T12:43:41Z | radius is a fast binary emulation and symbolic execution framework using radare2 | https://github.com/aemmitt-ns/radius | 15 | 1| 
| 20210928T11:05:12Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1789 | 507| 
| 20210928T07:19:03Z | Symbolica%s open-source symbolic execution engine. | https://github.com/Symbolica/Symbolica | 29 | 2| 
| 20210928T04:36:25Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 158 | 37| 
| 20210928T04:24:53Z | A Ghidra extension that allows you to run Angr symbolic execution using the Pcode from Ghidra. | https://github.com/jdkleuver/PcodeSym | 1 | 0| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210928T06:25:55Z | SafeInit protects software from uninitialized read vulnerabilities - code released for NDSS 2017 | https://github.com/vusec/safeinit | 21 | 4| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210928T12:43:39Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3698 | 877| 
| 20210928T12:38:50Z | 🔥 Studying The Fuzzing Book : https://www.fuzzingbook.org | https://github.com/KimSeoYe/TheFuzzingBook | 5 | 0| 
| 20210928T12:33:54Z | Filtered Fuzzy Time Series | https://github.com/Marcos001/Filtered-Fuzzy-Time-Series | 0 | 0| 
| 20210928T12:15:16Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 28 | 10| 
| 20210928T12:09:38Z | Kernel fuzzer inspired by Syzkaller | https://github.com/SunHao-0/healer | 116 | 14| 
| 20210928T12:03:10Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 303 | 39| 
| 20210928T11:58:53Z | What is WinAppDbg? The WinAppDbg python module allows developers to quickly code instrumentation scripts in Python under a Windows environment.  It uses ctypes to wrap many Win32 API calls related to debugging, and provides an object-oriented abstraction layer to manipulate threads, libraries and processes, attach your script as a debugger, trace execution, hook API calls, handle events in your debugee and set breakpoints of different kinds (code, hardware and memory). Additionally it has no native code at all, making it easier to maintain or modify than other debuggers on Windows.  The intended audience are QA engineers and software security auditors wishing to test / fuzz Windows applications with quickly coded Python scripts, as well as malware analysts and researchers wishing to instrument and test Windows binaries. Several ready to use utilities are shipped and can be used for this purposes.  Current features also include disassembling x86/x64 native code, debugging multiple processes simultaneously and produce a detailed log of application crashes, useful for fuzzing and automated testing. | https://github.com/sahdow3256/-WinDbg | 1 | 0| 
| 20210928T11:54:12Z | Null | https://github.com/Kirby01/Upcoming-Fuzz-Soon... | 0 | 0| 
| 20210928T11:41:59Z | domato but as a website | https://github.com/GawdOfROFL/rofl-fuzzer | 15 | 1| 
| 20210928T11:22:28Z | Null | https://github.com/TinkerBoard2-Android/test-vts-testcase-fuzz | 0 | 0| 



# 日更新程序
