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
