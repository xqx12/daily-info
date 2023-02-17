# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230216 | 用于研究windows进程执行技术的工具包 | https://github.com/daem0nc0re/TangledWinExec/tree/main/ReflectiveDLLInjection| 
| 20230216 | 从零开始写一个调试器，系列之一 | http://www.timdbg.com/posts/writing-a-debugger-from-scratch-part-1/| 
| 20230216 | 从攻防两个不同维度分析网络安全中双方的对抗。以Sysmon日志、ATT&CK标签日志、操作系统日志的分析实践为实例。 | https://www.freebuf.com/articles/es/357478.html| 
| 20230216 | 介绍linux内核的漏洞缓解机制及绕过方法，最后解释了CVE-2022-0847的漏洞利用方法，该方法不受漏洞缓解机制的限制 | http://blog.topsec.com.cn/linux%e5%86%85%e6%a0%b8%e5%b8%b8%e7%94%a8%e4%bf%9d%e6%8a%a4%e5%92%8c%e7%bb%95%e8%bf%87%e6%8a%80%e6%9c%af/| 
| 20230216 | IBM WebSphere Liberty 在其轻量级第三方身份验证 (LTPA) 协议的实现中存在缺陷，攻击者可构造任意其他用户的令牌。 | http://pretalx.hackerhotel.nl/hackerhotel-2023/talk/7JEEWB/| 
| 20230216 | 使用ChatGPT对取证及攻击识别方向的一些实验，作者使用Meterpreter、PowerShell Empire 感染系统后，对产生的进程、服务行为输入到ChatGPT中，其在恶意进程识别、服务安装和加密程序检查上表现良好。 | https://securelist.com/ioc-detection-experiments-with-chatgpt/108756/| 
| 20230216 | Arris Router Firmware远程代码执行漏洞(CVE-2022-45701)的漏洞利用，影响多个型号（TG2482A, TG2492, SBG10）设备。 | http://packetstormsecurity.com/files/171001| 
| 20230216 | 如何在不把服务端打DoS的情况下检测服务端的原型污染漏洞 | https://portswigger.net/research/server-side-prototype-pollution| 
| 20230216 | Rustproofing Linux (Part 3/4 Integer Overflows) | http://research.nccgroup.com/2023/02/14/rustproofing-linux-part-3-4-integer-overflows/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230216 | 某 T 路由器固件解压缩探秘 | https://paper.seebug.org/2048/| 
| 20230216 | Java反序列化预备全知 | https://xz.aliyun.com/t/12155| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230216T23:58:37Z | CVE-2022-4903 | A vulnerability was found in CodenameOne 7.0.70. It has been classified as problematic. Affected is an unknown function. The manipulation leads to use of implicit intent for sensitive communication. It is possible to launch the attack remotely. Upgrading to version 7.0.71 is able to address this issue. The name of the  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4903 | | 
| 20230216T23:58:34Z | CVE-2023-24344 | D-Link N300 WI-FI Router DIR-605L v2.13B01 was discovered to contain a stack overflow via the webpage parameter at /goform/formWlanGuestSetup. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-24344 | | 
| 20230216T23:58:30Z | CVE-2023-24343 | D-Link N300 WI-FI Router DIR-605L v2.13B01 was discovered to contain a stack overflow via the curTime parameter at /goform/formSchedule. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-24343 | | 
| 20230216T23:58:27Z | CVE-2023-24346 | D-Link N300 WI-FI Router DIR-605L v2.13B01 was discovered to contain a stack overflow via the wan_connected parameter at /goform/formEasySetupWizard3. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-24346 | | 
| 20230216T23:58:24Z | CVE-2023-24345 | D-Link N300 WI-FI Router DIR-605L v2.13B01 was discovered to contain a stack overflow via the curTime parameter at /goform/formSetWanDhcpplus. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-24345 | | 
| 20230216T23:58:20Z | CVE-2023-24347 | D-Link N300 WI-FI Router DIR-605L v2.13B01 was discovered to contain a stack overflow via the webpage parameter at /goform/formSetWanDhcpplus. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-24347 | | 
| 20230216T23:58:14Z | CVE-2023-25151 | opentelemetry-go-contrib is a collection of extensions for OpenTelemetry-Go. The v0.38.0 release of `go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp` uses the `httpconv.ServerRequest` function to annotate metric measurements for the `http.server.request_content_length`, `http.server.response_content_lengt CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-25151 | | 
| 20230216T23:58:10Z | CVE-2023-0821 | HashiCorp Nomad and Nomad Enterprise 1.2.15 up to 1.3.8, and 1.4.3 jobs using a maliciously compressed artifact stanza source can cause excessive disk usage. Fixed in 1.2.16, 1.3.9, and 1.4.4. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0821 | | 
| 20230216T23:58:06Z | CVE-2022-47703 | TIANJIE CPE906-3 is vulnerable to password disclosure. This is present on Software Version WEB5.0_LCD_20200513, Firmware Version MV8.003, and Hardware Version CPF906-V5.0_LCD_20200513. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-47703 | | 
| 20230216T23:58:02Z | CVE-2022-44299 | SiteServerCMS 7.1.3 sscms has a file read vulnerability. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-44299 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230216T07:29:23Z | Null | https://github.com/Mjzo/Kleene-Closure-Glossery | 0 | 0| 
| 20230216T02:19:14Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2156 | 606| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230216T22:56:26Z | Backdoor command execution in PHP 8.1.0-dev  | https://github.com/Anasi10/PHP-8.1.0-exploit | 0 | 0| 
| 20230216T22:43:15Z | A powerful and sophisticated tool for detecting and exploiting open redirect vulnerabilities using the sed utility and a selected list of carefully crafted payloads with encoding techniques. | https://github.com/blackhatethicalhacking/OpenRediWrecked | 2 | 0| 
| 20230216T22:25:49Z | Null | https://github.com/codingcore12/SILENT-EXCEL-XLS-EXPLOIT-CLEAN-mk | 1 | 0| 
| 20230216T22:24:53Z | Null | https://github.com/codingcore12/SILENT-PDF-EXPLOIT-CLEAN-mk | 1 | 0| 
| 20230216T22:23:23Z | Null | https://github.com/codingcore12/SILENT-DOC-EXPLOIT-CLEAN-mk | 1 | 0| 
| 20230216T21:21:11Z | Progress in Nightmare Intro to Binary Exploitation Course | https://github.com/remiliacmdlet/Nightmare | 0 | 0| 
| 20230216T21:16:46Z | One of the BEST up to date iReady hacks. Similar to iReady Overload. | https://github.com/notplu/Nullify | 44 | 47| 
| 20230216T13:43:36Z | GitOps Repository | https://github.com/app-studio-test/loadnomc5424-tenant-app-AGctX-exploit-lets | 0 | 0| 
| 20230216T13:07:21Z | GitOps Repository | https://github.com/app-studio-test/loadfodr5529-tenant-app-n_a3F-benefit-exploit | 0 | 0| 
| 20230216T13:07:20Z | GitOps Repository | https://github.com/app-studio-test/loadyexh1779-tenant-app--DGpo-suffer-exploit | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230216T22:56:26Z | Backdoor command execution in PHP 8.1.0-dev  | https://github.com/Anasi10/PHP-8.1.0-exploit | 0 | 0| 
| 20230216T12:54:04Z | Implementation of paper %More is Better (Mostly): On the Backdoor Attacks in Federated Graph Neural Networks% | https://github.com/xujing1994/bkd_fedgnn | 1 | 0| 
| 20230216T09:52:43Z | Null | https://github.com/agungsoboru/backdoor | 0 | 0| 
| 20230216T09:43:45Z | Code and data for paper %BITE: Textual Backdoor Attacks with Iterative Trigger Injection% | https://github.com/INK-USC/BITE | 0 | 0| 
| 20230216T04:29:01Z | Statically-linked ssh server with reverse shell functionality for CTFs and such | https://github.com/Fahrj/reverse-ssh | 672 | 98| 
| 20230216T02:58:59Z | The all-in-one website backdoor tool for white hat hackers  | https://github.com/NSXSoftware/anchovE | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230216T05:01:34Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 621 | 111| 
| 20230216T02:19:14Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2156 | 606| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230216T15:39:04Z | DroneSecurity (NDSS 2023) | https://github.com/RUB-SysSec/DroneSecurity | 1 | 0| 
| 20230216T15:13:11Z | find relevant security papers published in the top-4 conferences (S&P, USENIX, CCS, NDSS) | https://github.com/Kyle-Kyle/top4grep | 37 | 2| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230216T23:51:21Z | Null | https://github.com/julianfere/fuzzy-garbanzo | 0 | 0| 
| 20230216T23:04:44Z | Ethereum smart contract fuzzer | https://github.com/crytic/echidna | 1937 | 247| 
| 20230216T21:51:36Z | Null | https://github.com/h738020239a/fuzzy-space-pancake | 0 | 0| 
| 20230216T21:30:36Z | Null | https://github.com/jereczek12/ZSI-samochod-fuzzy | 0 | 0| 
| 20230216T20:24:40Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8378 | 1825| 
| 20230216T17:50:30Z | Null | https://github.com/JeffafaV/Grammar-Based-Fuzzing-Example | 0 | 0| 
| 20230216T17:31:02Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2650 | 181| 
| 20230216T16:22:57Z | Null | https://github.com/wjl88/svelte-fuzzy-demos | 0 | 0| 
| 20230216T13:59:46Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 3421 | 687| 
| 20230216T13:14:52Z | Null | https://github.com/Fleurvb/fuzzy_inventions | 0 | 0| 



# 日更新程序
