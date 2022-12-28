# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221227 | Netcomm - 未经身份验证的远程代码执行 | http://github.com/scarvell/advisories/blob/main/2022_netcomm_nf20mesh_unauth_rce.md| 
| 20221227 | BlueNoroff(Lazarus子组)使用新的办法在投递载荷的时候bypass MoTW | https://securelist.com/bluenoroff-methods-bypass-motw/108383/| 
| 20221227 | GuLoader 恶意软件实现了大量反分析和反调试功能，其中包括利用硬件断点来 unhook NTDLL 里面的 hook | https://thehackernews.com/2022/12/guloader-malware-utilizing-new.html| 
| 20221227 | 通过将CPU的供电电路变成Transmitter来从隔离的机器上偷数据。 | http://www.kaspersky.co.uk/blog/covid-bit-attack/25340/?reseller=gb_kdaily-social_acq_ona_smm__all_b2c_some_sma_______&utm_source=twitter&utm_medium=social&utm_campaign=gl_kdaily-social_ag0241&utm_content=sm-post&utm_term=gl_twitter_organic_72416tfy2yk0j7f| 
| 20221227 | Linux ksmbd UAF漏洞，可以导致RCE。 | https://sec.today/pulses/6867628a-3297-441b-ba18-470fcaf34528/| 
| 20221227 | 如何在开启了Windows Defender Credential Guard保护的情况下获取NTLM hash。该方法主要通过控制LSASS进程的ALPC 通信通道与LSAIso进程通信，利用加密脆弱性破解NTLM hash。 | https://research.ifcr.dk/pass-the-challenge-defeating-windows-defender-credential-guard-31a892eee22?gi=56a7be7c11fe| 
| 20221227 | CVE-2022-28672:Foxit PDF Reader UAF造成的RCE利用 | http://hacksys.io/blogs| 
| 20221227 | CVE-2022-41040 and CVE-2022-41082 – zero-days in MS Exchange | http://securelist.com/cve-2022-41040-and-cve-2022-41082-zero-days-in-ms-exchange/108364/?reseller=gb_kdaily-social_acq_ona_smm__all_b2c_some_sma_______&utm_source=twitter&utm_medium=social&utm_campaign=gl_kdaily-social_ag0241&utm_content=sm-post&utm_term=gl_twitter_organic_bvf6zky241ysqhz| 
| 20221227 | A public collection of POCs & Exploits (MacOS) | https://github.com/jhftss/POC| 
| 20221227 | Linux kernel ksmbd UAF RCE漏洞，ZDI-22-1690，CVSS SCORE：10.0 高危漏洞 | https://gbhackers.com/critical-linux-kernel-vulnerability/amp/| 
| 20221227 | Heap Overflows on iOS ARM64: Heap Spraying, Use-After-Free (Part 3) | https://www.inversecos.com/2022/07/heap-overflows-on-ios-arm64-heap.html?m=1| 
| 20221227 | Azure 中的无密码持久性驻留和特权提升 | https://posts.specterops.io/passwordless-persistence-and-privilege-escalation-in-azure-98a01310be3f?gi=4379de1ba1cb| 
| 20221227 | 通过dlopen从内存中加载php扩展以权限维持 | http://adepts.of0x.cc/dlopen-from-memory-PHP/| 
| 20221227 | 分析关于Shlayer恶意软件通过修改DMG文件的头结构在其嵌入其加密后的通信配置,并介绍其如何提取解密的全过程 | http://objective-see.org/blog/blog_0x70.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20221227T13:34:49Z | CVE-2022-3427 | The Corner Ad plugin for WordPress is vulnerable to Cross-Site Request Forgery in versions up to, and including, 1.0.56. This is due to missing or incorrect nonce validation on its corner_ad_settings_page function. This makes it possible for unauthenticated attackers to trigger the deletion of ads via forged request gr CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-3427 | | 
| 20221227T13:34:45Z | CVE-2022-20544 | In onOptionsItemSelected of ManageApplications.java, there is a possible bypass of profile owner restrictions due to a missing permission check. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Andr CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20544 | | 
| 20221227T13:34:42Z | CVE-2022-20543 | In multiple locations, there is a possible display crash loop due to improper input validation. This could lead to local denial of service with system execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-13Android ID: A-238178261 CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20543 | | 
| 20221227T13:34:38Z | CVE-2022-20541 | In phNxpNciHal_ioctl of phNxpNciHal.cc, there is a possible out of bounds read due to a missing bounds check. This could lead to local information disclosure with System execution privileges needed. User interaction is needed for exploitation.Product: AndroidVersions: Android-13Android ID: A-238083126 CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20541 | | 
| 20221227T13:34:35Z | CVE-2022-20540 | In SurfaceFlinger::doDump of SurfaceFlinger.cpp, there is possible arbitrary code execution due to a use after free. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-13Android ID: A-23729150 CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20540 | | 
| 20221227T13:34:31Z | CVE-2022-20539 | In parameterToHal of Effect.cpp, there is a possible out of bounds write due to a missing bounds check. This could lead to local escalation of privilege in the audio server with System execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-13Android ID: A-23729142 CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20539 | | 
| 20221227T13:34:28Z | CVE-2022-20538 | In getSmsRoleHolder of RoleService.java, there is a possible way to determine whether an app is installed, without query permissions, due to side channel information disclosure. This could lead to local information disclosure with no additional execution privileges needed. User interaction is not needed for exploitatio CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20538 | | 
| 20221227T13:34:25Z | CVE-2022-40435 | Employee Performance Evaluation System v1.0 was discovered to contain a persistent cross-site scripting (XSS) vulnerability via adding new entries under the Departments and Designations module. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-40435 | | 
| 20221227T13:34:05Z | CVE-2022-37177 | ** DISPUTED ** HireVue Hiring Platform V1.0 suffers from Use of a Broken or Risky Cryptographic Algorithm. NOTE: this is disputed by the vendor for multiple reasons, e.g., it is inconsistent with CVE ID assignment rules for cloud services, and no product with version V1.0 exists. Furthermore, the rail-fence cipher has  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-37177 | | 
| 20221227T13:34:01Z | CVE-2022-32531 | The Apache Bookkeeper Java Client (before 4.14.6 and also 4.15.0) does not close the connection to the bookkeeper server when TLS hostname verification fails. This leaves the bookkeeper client vulnerable to a man in the middle attack. The problem affects BookKeeper client prior to versions 4.14.6 and 4.15.1. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-32531 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221227T15:23:28Z | chi-kleen cleaning company | https://github.com/adepeter1234/chi-kleen | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221227T15:25:00Z | Spacecraft Simulation Environment Core codes | https://github.com/ut-issl/s2e-core | 26 | 7| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221227T23:49:31Z | Two errors in the %asn1_find_node()% function (lib/parser_aux.c) within GnuTLS libtasn1 version 4.10 can be exploited to cause a stacked-based buffer overflow by tricking a user into processing a specially crafted assignments file via the e.g. asn1Coding utility. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2017-6891 | 0 | 0| 
| 20221227T23:46:08Z | A vulnerability classified as problematic has been found in SourceCodester Human Resource Management System 1.0. Affected is an unknown function of the file /hrm/employeeview.php. The manipulation of the argument search leads to cross site scripting. It is possible to launch the attack remotely. The exploit has been di CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4279 | 0 | 0| 
| 20221227T13:32:01Z | By exploiting a time of check to time of use (TOCTOU) race condition during the Endpoint Security for Linux Threat Prevention and Firewall (ENSL TP/FW) installation process, a local user can perform a privilege escalation attack to obtain administrator privileges for the purpose of executing arbitrary code through inse CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-23892 | 0 | 0| 
| 20221227T13:27:16Z | A vulnerability classified as problematic has been found in chbrown rfc6902. This affects an unknown part of the file pointer.ts. The manipulation leads to improperly controlled modification of object prototype attributes (%prototype pollution%). The exploit has been disclosed to the public and may be used. The name of CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-4245 | 0 | 0| 
| 20221227T13:25:29Z | A vulnerability has been found in RainyGao DocSys and classified as critical. Affected by this vulnerability is an unknown functionality of the component com.DocSystem.controller.UserController#getUserImg. The manipulation leads to path traversal: %../filedir%. The attack can be launched remotely. The exploit has been  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4511 | 0 | 0| 
| 20221227T13:24:58Z | An exploitable firmware modification vulnerability was discovered on TP-Link TL-WR743ND V1. An attacker can conduct a MITM (Man-in-the-Middle) attack to modify the user-uploaded firmware image and bypass the CRC check, allowing attackers to execute arbitrary code or cause a Denial of Service (DoS). This affects v3.12.2 CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46432 | 0 | 0| 
| 20221227T13:24:35Z | An exploitable firmware modification vulnerability was discovered on the Netgear XWN5001 Powerline 500 WiFi Access Point. An attacker can conduct a MITM (Man-in-the-Middle) attack to modify the user-uploaded firmware image and bypass the CRC check, allowing attackers to execute arbitrary code or cause a Denial of Servi CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46424 | 0 | 0| 
| 20221227T13:24:31Z | An exploitable firmware modification vulnerability was discovered on the Netgear WNR2000v1 router. An attacker can conduct a MITM (Man-in-the-Middle) attack to modify the user-uploaded firmware image and bypass the CRC check, allowing attackers to execute arbitrary code or cause a Denial of Service (DoS). This affects  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46423 | 0 | 0| 
| 20221227T12:53:18Z | A vulnerability, which was classified as problematic, was found in Opencaching Deutschland oc-server3. Affected is an unknown function of the file htdocs/lang/de/ocstyle/varset.inc.php. The manipulation of the argument varvalue leads to cross site scripting. It is possible to launch the attack remotely. The exploit has CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4514 | 0 | 0| 
| 20221227T12:52:30Z | The backup module has a path traversal vulnerability. Successful exploitation of this vulnerability causes unauthorized access to other system files. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-41591 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221227T23:52:06Z | Insecure permissions in Telos Alliance Omnia MPX Node v1.0.0 to v1.4.9 allow attackers to manipulate and access system settings with backdoor account low privilege, this can lead to change hardware settings and execute arbitrary commands in vulnerable system functions that is requires high privilege to access. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-45562 | 0 | 0| 
| 20221227T20:54:37Z | Windows webcam backdoor created with msfvenom | https://github.com/Tomfunand/Windows-Webcam-Hack | 0 | 0| 
| 20221227T18:46:16Z | backdoor | https://github.com/stapitop/backdoor | 0 | 0| 
| 20221227T14:47:34Z | vSphere_selfuse commit 2a9fe074a64f6a0dd8ac02f21e2f10d66cac5749 was discovered to contain a code execution backdoor via the request package. This vulnerability allows attackers to access sensitive user information and digital currency keys, as well as escalate privileges. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46996 | 0 | 0| 
| 20221227T14:46:53Z | Python3-RESTfulAPI commit d9907f14e9e25dcdb54f5b22252b0e9452e3970e and e772e0beee284c50946e94c54a1d43071ca78b74 was discovered to contain a code execution backdoor via the request package. This vulnerability allows attackers to access sensitive user information and digital currency keys, as well as escalate privileges. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46609 | 0 | 0| 
| 20221227T14:46:50Z | Passhunt commit 54eb987d30ead2b8ebbf1f0b880aa14249323867 was discovered to contain a code execution backdoor via the request package. This vulnerability allows attackers to access sensitive user information and digital currency keys, as well as escalate privileges. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46997 | 0 | 0| 
| 20221227T14:30:20Z | keylogger搭載してるというか、それに特化したハッキングツール。 | https://github.com/ware255/yuki | 0 | 0| 
| 20221227T14:14:36Z | A support user exists on the device and appears to be a backdoor for Technical Support staff. The default password for this account is “support” and cannot be changed by a user via any normally accessible means. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-47209 | 0 | 0| 
| 20221227T13:21:55Z | THE BEST BACDOOR FOR FIVEM (I AM NOT RESPONSIBLE FOR THE CHARGES MADE WITH THIS SCRIPT) | https://github.com/nutria22/fivem-backdoor | 0 | 0| 
| 20221227T07:48:54Z | Flareon: Stealthy Backdoor Injection via Poisoned Augmentation | https://github.com/lafeat/flareon | 1 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221227T20:41:36Z | Open-source symbolic execution framework: https://maat.re | https://github.com/trailofbits/maat | 525 | 30| 
| 20221227T19:01:14Z | The npm package %tar% (aka node-tar) before versions 4.4.18, 5.0.10, and 6.1.9 has an arbitrary file creation/overwrite and arbitrary code execution vulnerability. node-tar aims to guarantee that any file whose location would be modified by a symbolic link is not extracted. This is, in part, achieved by ensuring that e CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-37712 | 0 | 0| 
| 20221227T19:01:10Z | The npm package %tar% (aka node-tar) before versions 4.4.16, 5.0.8, and 6.1.7 has an arbitrary file creation/overwrite and arbitrary code execution vulnerability. node-tar aims to guarantee that any file whose location would be modified by a symbolic link is not extracted. This is, in part, achieved by ensuring that ex CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-37701 | 0 | 0| 
| 20221227T16:08:14Z | There exists a path traversal vulnerability in the Android Google Search app. This is caused by the incorrect usage of uri.getLastPathSegment. A symbolic encoded string can bypass the path logic to get access to unintended directories. An attacker can manipulate paths that could lead to code execution on the device. We CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-29580 | 0 | 0| 
| 20221227T08:28:02Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 26 | 5| 
| 20221227T08:12:29Z | Symbolic-execution-based verifier for the Viper intermediate verification language. | https://github.com/viperproject/silicon | 53 | 25| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221227T01:55:03Z | Shell Extension para exibir os ícones de roms do Nintendo DS no Windows Explorer | https://github.com/pablorobert/NDSShellExtension | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221227T20:16:51Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8203 | 1788| 
| 20221227T20:14:10Z | FuzzBench - Fuzzer benchmarking as a service. | https://github.com/google/fuzzbench | 865 | 185| 
| 20221227T13:28:14Z | Null | https://github.com/kwen1510/fuzzy-search | 0 | 0| 
| 20221227T13:19:54Z | A fuzzy positive/negative covid prediction system base on occurrence and confirmability matrices. | https://github.com/miladbarooni/FuzzyCovidDetection | 0 | 0| 
| 20221227T13:02:07Z | This blog written_Patika.dev_Introduction to Data Science | https://github.com/hlttcamm/FUZZY-LOGIC-SYSTEMS-AT-MATLAB | 0 | 0| 
| 20221227T12:31:26Z | Null | https://github.com/Danday999/fuzzy-memory | 1 | 0| 
| 20221227T11:21:24Z | Mozilla developers Bryce Seager van Dyk and the Mozilla Fuzzing Team reported potential vulnerabilities present in Firefox 101. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability affects Firefox CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-34485 | 0 | 0| 
| 20221227T11:20:47Z | Mozilla developers Gabriele Svelto, Timothy Nikkel, Randell Jesup, Jon Coppeard, and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 100. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code.  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-31748 | 0 | 0| 
| 20221227T11:20:15Z | Mozilla developers and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 102. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability affects Firefox ESR < 102.1, Firefox < 103, CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-2505 | 0 | 0| 
| 20221227T11:20:12Z | Mozilla developers Andrew McCreight, Gabriele Svelto, Tom Ritter and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 99 and Firefox ESR 91.8. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary co CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-29917 | 0 | 0| 



# 日更新程序
