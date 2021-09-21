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


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210921T11:43:41Z | CVE-2021-24499 | Mass exploitation of CVE-2021-24499 unauthenticated upload leading to remote code execution in Workreap theme. | https://github.com/RyouYoo/CVE-2021-24499 | The Workreap WordPress theme before 2.2.2 AJAX actions workreap_award_temp_file_uploader and workreap_temp_file_uploader did not perform nonce checks, or validate that the request is from a valid user in any other way. The endpoints allowed for uploading arbitrary files to the uploads/workreap-temp directory. Uploaded files were neither sanitized nor validated, allowing an unauthenticated visitor to upload executable code such as php scripts.| 
| 20210921T10:00:33Z | CVE-2021-22925 | PoC for exploiting CVE-2021-22925 : curl supports the `-t` command line option, known as `CURLOPT_TELNETOPTIONS`in libcurl. This rarely used option is used to send variable=content pairs toTELNET servers.Due to flaw in the option parser for sending `NEW_ENV` variables, libcurlcould be made to pass on uninitialized data from a stack based buffer to theserver. Therefore potentially revealing sensitive internal information to theserver using a clear-text network protocol.This could happen because curl did not call and use sscanf() correctly whenparsing the string provided by the application. | https://github.com/AlAIAL90/CVE-2021-22925 | curl supports the `-t` command line option, known as `CURLOPT_TELNETOPTIONS`in libcurl. This rarely used option is used to send variable=content pairs toTELNET servers.Due to flaw in the option parser for sending `NEW_ENV` variables, libcurlcould be made to pass on uninitialized data from a stack based buffer to theserver. Therefore potentially revealing sensitive internal information to theserver using a clear-text network protocol.This could happen because curl did not call and use sscanf() correctly whenparsing the string provided by the application.| 
| 20210921T10:00:28Z | CVE-2021-30713 | PoC for exploiting CVE-2021-30713 : A permissions issue was addressed with improved validation. This issue is fixed in macOS Big Sur 11.4. A malicious application may be able to bypass Privacy preferences. Apple is aware of a report that this issue may have been actively exploited.. | https://github.com/AlAIAL90/CVE-2021-30713 | A permissions issue was addressed with improved validation. This issue is fixed in macOS Big Sur 11.4. A malicious application may be able to bypass Privacy preferences. Apple is aware of a report that this issue may have been actively exploited..| 
| 20210921T10:00:23Z | CVE-2021-30783 | PoC for exploiting CVE-2021-30783 : An access issue was addressed with improved access restrictions. This issue is fixed in macOS Big Sur 11.5, Security Update 2021-004 Catalina, Security Update 2021-005 Mojave. A sandboxed process may be able to circumvent sandbox restrictions. | https://github.com/AlAIAL90/CVE-2021-30783 | An access issue was addressed with improved access restrictions. This issue is fixed in macOS Big Sur 11.5, Security Update 2021-004 Catalina, Security Update 2021-005 Mojave. A sandboxed process may be able to circumvent sandbox restrictions.| 
| 20210921T09:12:57Z | CVE-2021-38647 | CVE-2021-38647 AKA "OMIGOD" vulnerability in Windows OMI  | https://github.com/corelight/CVE-2021-38647 | Open Management Infrastructure Remote Code Execution Vulnerability| 
| 20210921T08:53:48Z | CVE-2021-30632 | PoC CVE-2021-30632 - Out of bounds write in V8 | https://github.com/Phuong39/PoC-CVE-2021-30632 | 未查询到CVE信息| 
| 20210921T08:33:31Z | CVE-2021-26084 | [CVE-2021-26084] Confluence pre-auth RCE test script | https://github.com/ludy-dev/CVE-2021-26084_PoC | In affected versions of Confluence Server and Data Center, an OGNL injection vulnerability exists that would allow an unauthenticated attacker to execute arbitrary code on a Confluence Server or Data Center instance. The affected versions are before version 6.13.23, from version 6.14.0 before 7.4.11, from version 7.5.0 before 7.11.6, and from version 7.12.0 before 7.12.5.| 
| 20210921T07:50:47Z | CVE-2021-40444 | Modified code so that we don´t need to rely on CAB archives | https://github.com/Edubr2020/CVE-2021-40444--CABless | Microsoft MSHTML Remote Code Execution Vulnerability| 
| 20210921T04:31:00Z | CVE-2021-30860 | Scan for evidence of CVE-2021-30860 (FORCEDENTRY) exploit | https://github.com/Levilutz/CVE-2021-30860 | An integer overflow was addressed with improved input validation. This issue is fixed in Security Update 2021-005 Catalina, iOS 14.8 and iPadOS 14.8, macOS Big Sur 11.6, watchOS 7.6.2. Processing a maliciously crafted PDF may lead to arbitrary code execution. Apple is aware of a report that this issue may have been actively exploited.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210921T11:53:25Z | Null | https://github.com/jqhong/klee-native | 0 | 0| 
| 20210921T09:53:39Z | Projet d%automatisations d%éléments de récupérations de données de grafana en passant par pypetter | https://github.com/CinquinAndy/klee_pypetter_grafana_auto_download_csv | 0 | 0| 
| 20210921T09:34:20Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2783 | 75| 
| 20210921T06:53:46Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1777 | 505| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210921T12:03:33Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 31 | 18| 
| 20210921T11:38:08Z | Small collection of different compilers exploits. | https://github.com/Pogromca-SCP/CompilersAbuse | 0 | 0| 
| 20210921T11:35:12Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 10081 | 1693| 
| 20210921T11:26:55Z | Null | https://github.com/Apasys/Apasys-Python-Exploit-Sources | 7 | 0| 
| 20210921T11:05:31Z | Agricultural Monitoring exploiting Sentinel 1 and Sentinel 2. SandboxNL contains detailed explanations about the creation and usage of the parcel based Sentinel datasets.  | https://github.com/ManuelHuber-Github/Agricultural-SandboxNL | 0 | 0| 
| 20210921T10:26:49Z | Trojan Rat Builder(310), Ransomware Builder(17), Crypter(72), Miner(9), Worm(8), Botnet(25), Virus Builder(9), Binder(25), Exploit(7), Keylogger & Stealer(40), Proxy Tool(9), Spoofer(11),Fake program & Sample Virus(64),Other & Tools(16). Around 610 tools, that you can use for Hacking. | https://github.com/in-future-world/Hacking-Tools-Pack | 6 | 3| 
| 20210921T10:00:41Z | PoC for exploiting CVE-2019-17495 : A Cascading Style Sheets (CSS) injection vulnerability in Swagger UI before 3.23.11 allows attackers to use the Relative Path Overwrite (RPO) technique to perform CSS-based input field value exfiltration, such as exfiltration of a CSRF token value. In other words, this product intentionally allows the embedding of untrusted JSON data from remote servers, but it was not previously known that <style>@import within the JSON data was a functional attack method. | https://github.com/AlAIAL90/CVE-2019-17495 | 0 | 0| 
| 20210921T10:00:33Z | PoC for exploiting CVE-2021-22925 : curl supports the `-t` command line option, known as `CURLOPT_TELNETOPTIONS`in libcurl. This rarely used option is used to send variable=content pairs toTELNET servers.Due to flaw in the option parser for sending `NEW_ENV` variables, libcurlcould be made to pass on uninitialized data from a stack based buffer to theserver. Therefore potentially revealing sensitive internal information to theserver using a clear-text network protocol.This could happen because curl did not call and use sscanf() correctly whenparsing the string provided by the application. | https://github.com/AlAIAL90/CVE-2021-22925 | 0 | 0| 
| 20210921T10:00:32Z | PoC for exploiting CVE-2013-0340 : expat 2.1.0 and earlier does not properly handle entities expansion unless an application developer uses the XML_SetEntityDeclHandler function, which allows remote attackers to cause a denial of service (resource consumption), send HTTP requests to intranet servers, or read arbitrary files via a crafted XML document, aka an XML External Entity (XXE) issue.  NOTE: it could be argued that because expat already provides the ability to disable external entity expansion, the responsibility for resolving this issue lies with application developers; according to this argument, this entry should be REJECTed, and each affected application would need its own CVE. | https://github.com/AlAIAL90/CVE-2013-0340 | 0 | 0| 
| 20210921T10:00:28Z | PoC for exploiting CVE-2021-30713 : A permissions issue was addressed with improved validation. This issue is fixed in macOS Big Sur 11.4. A malicious application may be able to bypass Privacy preferences. Apple is aware of a report that this issue may have been actively exploited.. | https://github.com/AlAIAL90/CVE-2021-30713 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210921T11:43:31Z | pybotnet -   A Python Library for building Botnet , Trojan or BackDoor for windows and linux with Telegram control panel  | https://github.com/onionj/pybotnet | 22 | 12| 
| 20210921T03:29:56Z | A LKM rootkit targeting 4.x and 5.x kernel versions which opens a backdoor that can spawn a reverse shell to a remote host, launch malware and more. | https://github.com/h3xduck/Umbra | 34 | 5| 
| 20210921T03:17:01Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 317 | 57| 
| 20210921T02:06:16Z | Phone Hacking Series 6 - iPhone Backdoor - binaries | https://github.com/jonathandata1/phone_hacking_6 | 9 | 0| 
| 20210921T01:06:28Z | Null | https://github.com/mlearning-security/countermeasures-against-backdoor-attacks | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210921T10:12:01Z | A Ghidra extension that allows you to run Angr symbolic execution using the Pcode from Ghidra. | https://github.com/jdkleuver/PcodeSym | 1 | 0| 
| 20210921T09:10:31Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 157 | 34| 
| 20210921T08:02:02Z | A unit test-like interface for fuzzing and symbolic execution | https://github.com/trailofbits/deepstate | 661 | 66| 
| 20210921T06:53:46Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1777 | 505| 
| 20210921T05:49:36Z | A symbolic execution engine for LLVM IR | https://github.com/insufficiently-caffeinated/caffeine | 7 | 4| 
| 20210921T05:48:22Z | RAUK: Automatic Schedulability Analysis of RTIC Applications Using Symbolic Execution | https://github.com/markhakansson/master-thesis | 5 | 0| 
| 20210921T01:44:17Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 472 | 74| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210921T11:40:42Z | Code for the paper %FlowLens: Enabling Efficient Flow Classification for ML-based Network Security Applications% [NDSS %21] | https://github.com/dmbb/FlowLens | 7 | 1| 
| 20210921T11:36:28Z | Original implementation of FlowPrint as in the NDSS %20 paper | https://github.com/Thijsvanede/FlowPrint | 58 | 20| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210921T12:03:02Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210921T12:00:44Z | :pig: Tiny and fast fuzzy search in Go | https://github.com/lithammer/fuzzysearch | 653 | 37| 
| 20210921T11:57:45Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210921T11:54:22Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6670 | 1365| 
| 20210921T11:44:43Z | learn/try interesting techics | https://github.com/Si3ver/fuzzy-happiness | 0 | 0| 
| 20210921T11:36:47Z | Tool for fuzzing with style 👌 | https://github.com/essentialkaos/fz | 1 | 0| 
| 20210921T11:11:31Z | Null | https://github.com/nhsd-exeter/dos-service-fuzzy-search-api | 1 | 0| 
| 20210921T10:41:08Z | Null | https://github.com/ShitttCodersInc/fuzzy-octo-rotary-phone | 0 | 0| 
| 20210921T10:38:57Z | Null | https://github.com/ConsenSys/diligence-fuzzing | 4 | 1| 
| 20210921T09:49:01Z | Null | https://github.com/oof-cheburash/FuzzerLib | 0 | 0| 



# 日更新程序
