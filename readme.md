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


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20221227T13:32:01Z | CVE-2021-23892 | By exploiting a time of check to time of use (TOCTOU) race condition during the Endpoint Security for Linux Threat Prevention and Firewall (ENSL TP/FW) installation process, a local user can perform a privilege escalation attack to obtain administrator privileges for the purpose of executing arbitrary code through inse CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-23892 | | 
| 20221227T13:31:54Z | CVE-2021-31843 | Improper privileges management vulnerability in McAfee Endpoint Security (ENS) Windows prior to 10.7.0 September 2021 Update allows local users to access files which they would otherwise not have access to via manipulating junction links to redirect McAfee folder operations to an unintended location. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-31843 | | 
| 20221227T13:31:50Z | CVE-2021-31854 | A command Injection Vulnerability in McAfee Agent (MA) for Windows prior to 5.7.5 allows local users to inject arbitrary shell code into the file cleanup.exe. The malicious clean.exe file is placed into the relevant folder and executed by running the McAfee Agent deployment feature located in the System Tree. An attack CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-31854 | | 
| 20221227T13:31:47Z | CVE-2021-3485 | An Improper Input Validation vulnerability in the Product Update feature of Bitdefender Endpoint Security Tools for Linux allows a man-in-the-middle attacker to abuse the DownloadFile function of the Product Update to achieve remote code execution. This issue affects: Bitdefender Endpoint Security Tools for Linux versi CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-3485 | | 
| 20221227T13:31:44Z | CVE-2022-1401 | Improper Access Control vulnerability in the /Exago/WrImageResource.adx route as used in Device42 Asset Management Appliance allows an unauthenticated attacker to read sensitive server files with root permissions. This issue affects: Device42 CMDB versions prior to 18.01.00. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-1401 | | 
| 20221227T13:31:40Z | CVE-2022-3369 | An Improper Access Control vulnerability in the bdservicehost.exe component, as used in Bitdefender Engines for Windows, allows an attacker to delete privileged registry keys by pointing a Registry symlink to a privileged key. This issue affects: Bitdefender Engines versions prior to 7.92659. It also affects Bitdefende CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-3369 | | 
| 20221227T13:31:37Z | CVE-2022-32948 | An out-of-bounds read was addressed with improved bounds checking. This issue is fixed in iOS 15.6 and iPadOS 15.6, macOS Monterey 12.5. An app may be able to execute arbitrary code with kernel privileges. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-32948 | | 
| 20221227T13:31:33Z | CVE-2022-45484 | A vulnerability has been identified in JT2Go (All versions), Teamcenter Visualization V13.2 (All versions < V13.2.0.12), Teamcenter Visualization V13.3 (All versions < V13.3.0.8), Teamcenter Visualization V13.3 (All versions >= V13.3.0.8), Teamcenter Visualization V14.0 (All versions < V14.0.0.4), Teamcenter Visualizat CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-45484 | | 
| 20221227T13:31:30Z | CVE-2020-4497 | IBM Spectrum Protect Plus 10.1.0 through 10.1.12 discloses sensitive information due to unencrypted data being used in the communication flow between Spectrum Protect Plus vSnap and its agents. An attacker could obtain information using main in the middle techniques. IBM X-Force ID: 182106. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-4497 | | 
| 20221227T13:31:23Z | CVE-2022-38131 | RStudio Connect is affected by an Open Redirect issue. The vulnerability could allow an attacker to redirect users to malicious websites. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-38131 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221227T13:32:01Z | By exploiting a time of check to time of use (TOCTOU) race condition during the Endpoint Security for Linux Threat Prevention and Firewall (ENSL TP/FW) installation process, a local user can perform a privilege escalation attack to obtain administrator privileges for the purpose of executing arbitrary code through inse CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-23892 | 0 | 0| 
| 20221227T13:27:16Z | A vulnerability classified as problematic has been found in chbrown rfc6902. This affects an unknown part of the file pointer.ts. The manipulation leads to improperly controlled modification of object prototype attributes (%prototype pollution%). The exploit has been disclosed to the public and may be used. The name of CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-4245 | 0 | 0| 
| 20221227T13:25:29Z | A vulnerability has been found in RainyGao DocSys and classified as critical. Affected by this vulnerability is an unknown functionality of the component com.DocSystem.controller.UserController#getUserImg. The manipulation leads to path traversal: %../filedir%. The attack can be launched remotely. The exploit has been  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4511 | 0 | 0| 
| 20221227T13:24:58Z | An exploitable firmware modification vulnerability was discovered on TP-Link TL-WR743ND V1. An attacker can conduct a MITM (Man-in-the-Middle) attack to modify the user-uploaded firmware image and bypass the CRC check, allowing attackers to execute arbitrary code or cause a Denial of Service (DoS). This affects v3.12.2 CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46432 | 0 | 0| 
| 20221227T13:24:35Z | An exploitable firmware modification vulnerability was discovered on the Netgear XWN5001 Powerline 500 WiFi Access Point. An attacker can conduct a MITM (Man-in-the-Middle) attack to modify the user-uploaded firmware image and bypass the CRC check, allowing attackers to execute arbitrary code or cause a Denial of Servi CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46424 | 0 | 0| 
| 20221227T13:24:31Z | An exploitable firmware modification vulnerability was discovered on the Netgear WNR2000v1 router. An attacker can conduct a MITM (Man-in-the-Middle) attack to modify the user-uploaded firmware image and bypass the CRC check, allowing attackers to execute arbitrary code or cause a Denial of Service (DoS). This affects  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46423 | 0 | 0| 
| 20221227T12:53:18Z | A vulnerability, which was classified as problematic, was found in Opencaching Deutschland oc-server3. Affected is an unknown function of the file htdocs/lang/de/ocstyle/varset.inc.php. The manipulation of the argument varvalue leads to cross site scripting. It is possible to launch the attack remotely. The exploit has CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4514 | 0 | 0| 
| 20221227T12:52:30Z | The backup module has a path traversal vulnerability. Successful exploitation of this vulnerability causes unauthorized access to other system files. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-41591 | 0 | 0| 
| 20221227T12:52:26Z | Some smartphones have authentication-related (including session management) vulnerabilities as the setup wizard is bypassed. Successful exploitation of this vulnerability affects the smartphone availability. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-41590 | 0 | 0| 
| 20221227T12:52:16Z | The multi-screen collaboration module has a path traversal vulnerability. Successful exploitation of this vulnerability may affect data confidentiality. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-46856 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221227T13:21:55Z | THE BEST BACDOOR FOR FIVEM (I AM NOT RESPONSIBLE FOR THE CHARGES MADE WITH THIS SCRIPT) | https://github.com/nutria22/fivem-backdoor | 0 | 0| 
| 20221227T07:48:54Z | Flareon: Stealthy Backdoor Injection via Poisoned Augmentation | https://github.com/lafeat/flareon | 1 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221227T08:28:02Z | Symbolic execution tool for Sail ISA specifications | https://github.com/rems-project/isla | 26 | 5| 
| 20221227T08:12:29Z | Symbolic-execution-based verifier for the Viper intermediate verification language. | https://github.com/viperproject/silicon | 53 | 25| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221227T01:55:03Z | Shell Extension para exibir os ícones de roms do Nintendo DS no Windows Explorer | https://github.com/pablorobert/NDSShellExtension | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221227T13:28:14Z | Null | https://github.com/kwen1510/fuzzy-search | 0 | 0| 
| 20221227T13:19:54Z | A fuzzy positive/negative covid prediction system base on occurrence and confirmability matrices. | https://github.com/miladbarooni/FuzzyCovidDetection | 0 | 0| 
| 20221227T13:02:07Z | This blog written_Patika.dev_Introduction to Data Science | https://github.com/hlttcamm/FUZZY-LOGIC-SYSTEMS-AT-MATLAB | 0 | 0| 
| 20221227T12:31:26Z | Null | https://github.com/Danday999/fuzzy-memory | 1 | 0| 
| 20221227T11:21:24Z | Mozilla developers Bryce Seager van Dyk and the Mozilla Fuzzing Team reported potential vulnerabilities present in Firefox 101. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability affects Firefox CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-34485 | 0 | 0| 
| 20221227T11:20:47Z | Mozilla developers Gabriele Svelto, Timothy Nikkel, Randell Jesup, Jon Coppeard, and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 100. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code.  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-31748 | 0 | 0| 
| 20221227T11:20:15Z | Mozilla developers and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 102. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability affects Firefox ESR < 102.1, Firefox < 103, CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-2505 | 0 | 0| 
| 20221227T11:20:12Z | Mozilla developers Andrew McCreight, Gabriele Svelto, Tom Ritter and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 99 and Firefox ESR 91.8. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary co CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-29917 | 0 | 0| 
| 20221227T11:20:09Z | Mozilla developers Gabriele Svelto, Randell Jesup and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 99. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability affects Firef CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-29918 | 0 | 0| 
| 20221227T11:19:47Z | Mozilla developers and community members Randell Jesup, Sebastian Hengst, and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 98. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vul CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-28288 | 0 | 0| 



# 日更新程序
