# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221207 | 尽管进行了多因素身份认证，但若能获取到受害者用户登录后的 Cookie，就可以通过直接传递 Cookie 的方式接管受害者用户的账户 | https://blog.netwrix.com/2022/11/29/bypassing-mfa-with-pass-the-cookie-attack/| 
| 20221207 | 微软披露DEV-0139(疑似Lazarus)针对加密货币行业发起定向攻击,其主要通过社工获取信任后使用Telegram为载体投递武器化的macro宏文档,宏执行后释放另一个xls并且其内嵌的宏下载一个png文件(由白文件,黑dll,带有Guid xor加密后的backdoor程序组成),然后将这三个部分分割后提取出来再写入本地.然后其通过白加黑的手法运行载荷。除了xls载荷还有利用msi安装包进行植入的活动,其也是利用白加黑以进行木马的植入 | https://www.microsoft.com/en-us/security/blog/2022/12/06/dev-0139-launches-targeted-attacks-against-the-cryptocurrency-industry/| 
| 20221207 | 暗网中的 InTheBox 市场为移动恶意软件制造者提供了多种类别的 Webinjects 模板 | http://cybersecuritynews.com/largest-mobile-malware-darkweb-marketplace/| 
| 20221207 | X server所使用的底层像素管理库pixman存在整数溢出漏洞可导致堆越界写 | https://bugs.chromium.org/p/project-zero/issues/detail?id=2345| 
| 20221207 | 使用 Akamai WAF Bypass 在 Spring Boot 错误页面上通过 SSTI 而进行 RCE | https://h1pmnh.github.io/post/writeup_spring_el_waf_bypass/| 
| 20221207 | 介绍Netgear RAX30 1.0.7.78版本的DHCP命令注入和WAN利用链 | https://www.reddit.com/r/netsec/comments/ze8pr7/the_last_breath_of_our_netgear_rax30_bugs_a/| 
| 20221207 | 使用 OpenAI 的 davinci-003 模型为 IDA Pro 反编译的函数提供注释和变量重命名信息的插件 | https://github.com/JusticeRage/Gepetto| 
| 20221207 | DanaBot恶意软件的混淆技术分析，涉及多种对抗逆向工程的实用方法 | https://www.zscaler.com/blogs/security-research/technical-analysis-danabot-obfuscation-techniques| 
| 20221207 | CI/CD 的供应链安全案例，如果一个项目使用了有漏洞的Github action，攻击者可以通过发起MR实现提权 | https://www.legitsecurity.com/blog/github-actions-that-open-the-door-to-cicd-pipeline-attacks| 
| 20221207 | GOAD lab part11 ACL writeup | https://mayfly277.github.io/posts/GOADv2-pwning-part11/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221207 | DISTDET：具有成本效益的分布式网络威胁检测系统 | https://mp.weixin.qq.com/s/AdyyZQit40tulOaIyNAbEA| 
| 20221207 | SEVulDet：一种语义增强的可学习漏洞检测器 | https://mp.weixin.qq.com/s/agQNMQo9atwZOFjPBleLcg| 
| 20221207 | ConDySTA: 上下文感知的动态辅助静态污点分析 | https://mp.weixin.qq.com/s/syrJfq9HsB_Ob4yvN4_KtA| 
| 20221207 | 开源软件供应链安全系列：OSS风险点与预防 | https://mp.weixin.qq.com/s/Sn9-qk_cfgTHBJh9ourD4A| 
| 20221207 | 安全概念分析框架 | https://mp.weixin.qq.com/s/JysvRftmGl2zg41ko8n1yA| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20221207T13:36:43Z | CVE-2022-25765 | pdfkit <0.8.6 command injection shell. The package pdfkit from 0.0.0 are vulnerable to Command Injection where the URL is not properly sanitized. (Tested on ver 0.8.6) - CVE-2022-25765 | https://github.com/CyberArchitect1/CVE-2022-25765-pdfkit-Exploit-Reverse-Shell | | 
| 20221207T11:04:01Z | CVE-2022-1388 | Null | https://github.com/amitlttwo/CVE-2022-1388 | | 
| 20221207T10:56:15Z | CVE-2021-41805 | HashiCorp Consul exploit with python. (CVE-2021-41805) | https://github.com/I-Am-Nelson/CVE-2021-41805 | | 
| 20221207T06:45:41Z | CVE-2022-20441 | Null | https://github.com/nidhi7598/frameworks_base_AOSP_10_r33_CVE-2022-20441 | | 
| 20221207T02:25:11Z | CVE-2022-2414 | A flaw was found in pki-core. Access to external entities when parsing XML documents can lead to XML external entity (XXE) attacks. This flaw allows a remote attacker to potentially retrieve the content of arbitrary files by sending specially crafted HTTP requests. | https://github.com/amitlttwo/CVE-2022-2414-Proof-Of-Concept | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221207T13:10:12Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2116 | 600| 
| 20221207T12:26:59Z | my hexo blog | https://github.com/kleeper914/kleeper914.github.io | 1 | 0| 
| 20221207T12:21:11Z | Null | https://github.com/abdulraheemiq/bootstrap-purple-kleeja | 0 | 0| 
| 20221207T11:01:25Z | An open-source Chinese font derived from Fontworks% Klee One. 一款开源中文字体，基于 FONTWORKS 出品字体 Klee One 衍生。   | https://github.com/lxgw/LxgwWenKai | 9539 | 327| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221207T13:18:41Z | Décrire, nettoyer, exploiter les données pour la mise en place et la présententation d%une application diététique | https://github.com/110111-1/DS-OPENFOODFACT-SANTE | 0 | 0| 
| 20221207T12:44:08Z | Post-exploitation tool to cover your tracks on various operating systems | https://github.com/sundowndev/covermyass | 206 | 37| 
| 20221207T12:05:08Z | Null | https://github.com/dugisan3rd/exploit | 0 | 0| 
| 20221207T11:50:51Z | Public Archive of Reverse-Engineering & Binary-Exploitation Challenges for APU BOH 2022 | https://github.com/WesleyWong420/Battle-of-Hackers-2022 | 0 | 0| 
| 20221207T11:49:49Z | A post-exploitation toolkit to simulate the weaponization and detection of native Windows binaries based on LOLBas framework.  | https://github.com/WesleyWong420/Build-Your-Own-LOLBins | 0 | 0| 
| 20221207T11:29:24Z | PHPunit Checker CVE-2017-9841 By MrMad | https://github.com/MadExploits/PHPunit-Exploit | 0 | 0| 
| 20221207T10:56:15Z | HashiCorp Consul exploit with python. (CVE-2021-41805) | https://github.com/I-Am-Nelson/CVE-2021-41805 | 0 | 0| 
| 20221207T10:54:21Z | The AluTrace Project was a project funded by the german Ministry of Economics, Labor and Tourism Baden-Württemberg (34-4224.044/21, 01/2020-12/2021) to digitally link the data and knowledge islands that are created through product development and manufacturing cycles in order to exploit them for lightweight design. | https://github.com/Mat-O-Lab/AluTrace-Data-and-Documentation | 0 | 0| 
| 20221207T10:31:25Z | Did you need a tool to operate DVR devices and CCTV cameras??  congratulations. You have it right now! | https://github.com/C4ssif3r/Ariana-DVR-exploiter-Framework | 0 | 0| 
| 20221207T06:58:57Z | This repository is primarily maintained by Omar Santos (@santosomar) and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 12424 | 2132| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221207T13:30:48Z | Villain is a Windows & Linux backdoor generator and multi-session handler that allows users to connect with sibling servers (other machines running Villain) and share their backdoor sessions, handy for working as a team. | https://github.com/t3l3machus/Villain | 1539 | 273| 
| 20221207T09:55:30Z | Mimicry is a security tool developed by Chaitin Technology for active deception in exploitation and post-exploitation. | https://github.com/chaitin/mimicry | 1 | 1| 
| 20221207T08:25:08Z | A list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 615 | 122| 
| 20221207T05:52:57Z | A Script For Block Fivem Backdoors | https://github.com/mo13ammad/FivemBackDoors | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221207T13:10:12Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2116 | 600| 
| 20221207T11:20:11Z | Symbolic execution engine for .NET Core | https://github.com/VSharp-team/VSharp | 35 | 21| 
| 20221207T07:58:11Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3228 | 455| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221207T12:55:59Z | cifuzz makes fuzz tests as easy as unit tests | https://github.com/CodeIntelligenceTesting/cifuzz | 125 | 9| 
| 20221207T12:47:46Z | An example Java App to show examples of unit, fuzz and component testing | https://github.com/CodeIntelligenceTesting/Road-Smart | 2 | 0| 
| 20221207T11:50:20Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8119 | 1770| 
| 20221207T11:38:51Z | Null | https://github.com/Bensoto22/fuzzy-engine | 0 | 0| 
| 20221207T11:28:08Z | Store rating system using fuzzy logic (lab project) | https://github.com/glebbash/fuzzy-store-rating | 0 | 0| 
| 20221207T09:26:34Z | Null | https://github.com/slowkeep/FuzzCatcher | 0 | 0| 
| 20221207T09:26:21Z | Dictionary collection project such as Pentesing, Fuzzing, Bruteforce and BugBounty. 渗透测试、SRC漏洞挖掘、爆破、Fuzzing等字典收集项目。 | https://github.com/insightglacier/Dictionary-Of-Pentesting | 1425 | 317| 
| 20221207T00:03:35Z | Null | https://github.com/kra0s22/fuzzy-logic-water-quality | 0 | 0| 



# 日更新程序
