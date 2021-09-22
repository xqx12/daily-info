# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210921 | SecWiki周刊（第394期) | https://www.sec-wiki.com/weekly/394| 
| 20210921 | CCS 2021 论文录用列表 | https://mp.weixin.qq.com/s/ENzG3CKSDMR-0EpCTuVq0w| 
| 20210921 | 浅谈固件Fuzz | https://mp.weixin.qq.com/s/IL-wIM8wePZL07l9YJnX_Q| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210921T11:43:41Z | CVE-2021-24499 | Mass exploitation of CVE-2021-24499 unauthenticated upload leading to remote code execution in Workreap theme. | https://github.com/RyouYoo/CVE-2021-24499 | The Workreap WordPress theme before 2.2.2 AJAX actions workreap_award_temp_file_uploader and workreap_temp_file_uploader did not perform nonce checks, or validate that the request is from a valid user in any other way. The endpoints allowed for uploading arbitrary files to the uploads/workreap-temp directory. Uploaded files were neither sanitized nor validated, allowing an unauthenticated visitor to upload executable code such as php scripts.| 
| 20210921T10:00:33Z | CVE-2021-22925 | PoC for exploiting CVE-2021-22925 : curl supports the `-t` command line option, known as `CURLOPT_TELNETOPTIONS`in libcurl. This rarely used option is used to send variable=content pairs toTELNET servers.Due to flaw in the option parser for sending `NEW_ENV` variables, libcurlcould be made to pass on uninitialized data from a stack based buffer to theserver. Therefore potentially revealing sensitive internal information to theserver using a clear-text network protocol.This could happen because curl did not call and use sscanf() correctly whenparsing the string provided by the application. | https://github.com/AlAIAL90/CVE-2021-22925 | curl supports the `-t` command line option, known as `CURLOPT_TELNETOPTIONS`in libcurl. This rarely used option is used to send variable=content pairs toTELNET servers.Due to flaw in the option parser for sending `NEW_ENV` variables, libcurlcould be made to pass on uninitialized data from a stack based buffer to theserver. Therefore potentially revealing sensitive internal information to theserver using a clear-text network protocol.This could happen because curl did not call and use sscanf() correctly whenparsing the string provided by the application.| 
| 20210921T10:00:28Z | CVE-2021-30713 | PoC for exploiting CVE-2021-30713 : A permissions issue was addressed with improved validation. This issue is fixed in macOS Big Sur 11.4. A malicious application may be able to bypass Privacy preferences. Apple is aware of a report that this issue may have been actively exploited.. | https://github.com/AlAIAL90/CVE-2021-30713 | A permissions issue was addressed with improved validation. This issue is fixed in macOS Big Sur 11.4. A malicious application may be able to bypass Privacy preferences. Apple is aware of a report that this issue may have been actively exploited..| 
| 20210921T10:00:23Z | CVE-2021-30783 | PoC for exploiting CVE-2021-30783 : An access issue was addressed with improved access restrictions. This issue is fixed in macOS Big Sur 11.5, Security Update 2021-004 Catalina, Security Update 2021-005 Mojave. A sandboxed process may be able to circumvent sandbox restrictions. | https://github.com/AlAIAL90/CVE-2021-30783 | An access issue was addressed with improved access restrictions. This issue is fixed in macOS Big Sur 11.5, Security Update 2021-004 Catalina, Security Update 2021-005 Mojave. A sandboxed process may be able to circumvent sandbox restrictions.| 
| 20210921T08:33:31Z | CVE-2021-26084 | [CVE-2021-26084] Confluence pre-auth RCE test script | https://github.com/ludy-dev/CVE-2021-26084_PoC | In affected versions of Confluence Server and Data Center, an OGNL injection vulnerability exists that would allow an unauthenticated attacker to execute arbitrary code on a Confluence Server or Data Center instance. The affected versions are before version 6.13.23, from version 6.14.0 before 7.4.11, from version 7.5.0 before 7.11.6, and from version 7.12.0 before 7.12.5.| 
| 20210921T04:31:00Z | CVE-2021-30860 | Scan for evidence of CVE-2021-30860 (FORCEDENTRY) exploit | https://github.com/Levilutz/CVE-2021-30860 | An integer overflow was addressed with improved input validation. This issue is fixed in Security Update 2021-005 Catalina, iOS 14.8 and iPadOS 14.8, macOS Big Sur 11.6, watchOS 7.6.2. Processing a maliciously crafted PDF may lead to arbitrary code execution. Apple is aware of a report that this issue may have been actively exploited.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210921T20:03:26Z | Config files for my GitHub profile. | https://github.com/kleex1234/kleex1234 | 0 | 0| 
| 20210921T16:08:40Z | Projet d%automatisations d%éléments de récupérations de données de grafana en passant par pypetter | https://github.com/CinquinAndy/klee_pypetter_grafana_auto_download_csv | 0 | 0| 
| 20210921T15:33:29Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2782 | 75| 
| 20210921T11:53:25Z | Null | https://github.com/jqhong/klee-native | 0 | 0| 
| 20210921T06:53:46Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1777 | 505| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210921T23:51:30Z | Exploiting Causal Structure for Transportability in Online, Multi-Agent Environments | https://github.com/axelbrowne/ECS4TOMAE | 0 | 0| 
| 20210921T22:53:43Z | Ded Security Framework is a tool aimed at security professionals | https://github.com/dedsecurity/dedsecurity-framework | 10 | 7| 
| 20210921T22:37:41Z | Our main goal is to share tips from some well-known bughunters. Using recon methodology, we are able to find subdomains, apis, and tokens that are already exploitable, so we can report them. We wish to influence Onelinetips and explain the commands, for the better understanding of new hunters.. | https://github.com/KingOfBugbounty/KingOfBugBountyTips | 2425 | 413| 
| 20210921T22:12:18Z | An attempt of automating the exploitation workflow of basic OSCP like buffer overflows in python | https://github.com/lyxo/autoOverflow | 0 | 0| 
| 20210921T21:22:00Z | AD Enum is a pentesting tool that allows to find misconfiguration through the the protocol LDAP and exploit some of those weaknesses with kerberos. | https://github.com/SecuProject/ADenum | 7 | 1| 
| 20210921T21:18:53Z | One Click root Exploit for Unobtainium Machine [HackTheBox] | https://github.com/Rajchowdhury420/Unobtainium-HTB-Exploit | 1 | 0| 
| 20210921T21:11:53Z | Null | https://github.com/AbdaalRuhaani/RuhaaniExploits | 0 | 0| 
| 20210921T19:51:25Z | Modular penetration testing platform that enables you to write, test, and execute exploit code. | https://github.com/EntySec/HatSploit | 91 | 32| 
| 20210921T19:46:06Z | pwninit - automate starting binary exploit challenges | https://github.com/io12/pwninit | 230 | 13| 
| 20210921T19:13:29Z | The AWS exploitation framework, designed for testing the security of Amazon Web Services environments. | https://github.com/RhinoSecurityLabs/pacu | 2305 | 419| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210921T23:34:41Z | A workflow to create/manage a backdoor admin account and rotate the password. E.g. Another LAPS workflow. | https://github.com/Rocketman-Tech/BreakGlassAdmin | 0 | 1| 
| 20210921T21:04:05Z | Is a simple backdoor with keylogger integrate and another stuff | https://github.com/alecksandr26/BackDoor_C | 0 | 0| 
| 20210921T19:59:12Z | Null | https://github.com/ahmedwali0/backdoor | 0 | 0| 
| 20210921T19:07:59Z | Null | https://github.com/kendragon016/backdoor | 0 | 0| 
| 20210921T17:26:58Z | Reverse Shell en GOLANG | https://github.com/thiagous06/go-reverseshell | 1 | 0| 
| 20210921T16:12:35Z | A LKM rootkit targeting 4.x and 5.x kernel versions which opens a backdoor that can spawn a reverse shell to a remote host, launch malware and more. | https://github.com/h3xduck/Umbra | 35 | 5| 
| 20210921T13:38:32Z | A sample app to demonstrate how to create Xamarin UITests using the Page Object architecture, Backdoor Methods and App Links (aka Deep Linking) | https://github.com/brminnick/UITestSampleApp | 36 | 27| 
| 20210921T11:43:31Z | pybotnet -   A Python Library for building Botnet , Trojan or BackDoor for windows and linux with Telegram control panel  | https://github.com/onionj/pybotnet | 22 | 12| 
| 20210921T03:17:01Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 317 | 58| 
| 20210921T02:06:16Z | Phone Hacking Series 6 - iPhone Backdoor - binaries | https://github.com/jonathandata1/phone_hacking_6 | 9 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210921T15:01:46Z | Symbolica%s open-source symbolic execution engine. | https://github.com/SymbolicaDev/Symbolica | 28 | 2| 
| 20210921T14:57:43Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 158 | 34| 
| 20210921T10:12:01Z | A Ghidra extension that allows you to run Angr symbolic execution using the Pcode from Ghidra. | https://github.com/jdkleuver/PcodeSym | 1 | 0| 
| 20210921T08:02:02Z | A unit test-like interface for fuzzing and symbolic execution | https://github.com/trailofbits/deepstate | 661 | 66| 
| 20210921T06:53:46Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1777 | 505| 
| 20210921T05:49:36Z | A symbolic execution engine for LLVM IR | https://github.com/insufficiently-caffeinated/caffeine | 7 | 4| 
| 20210921T05:48:22Z | RAUK: Automatic Schedulability Analysis of RTIC Applications Using Symbolic Execution | https://github.com/markhakansson/master-thesis | 5 | 0| 
| 20210921T01:44:17Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 472 | 74| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210921T12:31:47Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 24 | 5| 
| 20210921T11:40:42Z | Code for the paper %FlowLens: Enabling Efficient Flow Classification for ML-based Network Security Applications% [NDSS %21] | https://github.com/dmbb/FlowLens | 7 | 1| 
| 20210921T11:36:28Z | Original implementation of FlowPrint as in the NDSS %20 paper | https://github.com/Thijsvanede/FlowPrint | 58 | 20| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210921T23:36:09Z | Fuzzy logic with microcontroller device to determine of watering time for plants based on temperature and humidity using the DHT11 sensor module. | https://github.com/ganiadiw/arduino-fuzzification | 0 | 0| 
| 20210921T23:02:44Z | A ground-truth fuzzing benchmark suite based on real programs with real bugs. | https://github.com/HexHive/magma | 135 | 39| 
| 20210921T22:57:08Z | Tool for fuzzing with style 👌 | https://github.com/essentialkaos/fz | 1 | 0| 
| 20210921T22:54:01Z | Null | https://github.com/psuchta/fuzzy-parking | 0 | 0| 
| 20210921T22:35:16Z | An investigation of American Fuzzy Lop++ as a fuzzer | https://github.com/hark130/hardy-remix | 0 | 0| 
| 20210921T21:50:26Z | Coding practice for HTML/CSS/anything else web based | https://github.com/FuzzyPumpkin/FuzzyPumpkin.github.io | 5 | 1| 
| 20210921T21:23:40Z | A fork and successor of the Sulley Fuzzing Framework | https://github.com/jtpereyda/boofuzz | 1309 | 259| 
| 20210921T21:15:13Z | Null | https://github.com/mntzj/fuzzy-netlify | 0 | 0| 
| 20210921T21:08:23Z | A Modular Open-Source Hardware Fuzzing Framework | https://github.com/ekiwi/rtl-fuzz-lab | 1 | 0| 
| 20210921T21:01:36Z | Go library that provides fuzzy string matching optimized for filenames and code symbols in the style of Sublime Text, VSCode, IntelliJ IDEA et al. | https://github.com/sahilm/fuzzy | 1042 | 52| 



# 日更新程序
