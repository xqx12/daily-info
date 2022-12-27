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
| 20221227T13:24:21Z | CVE-2022-39304 | ghinstallation provides transport, which implements http.RoundTripper to provide authentication as an installation for GitHub Apps. In ghinstallation version 1, when the request to refresh an installation token failed, the HTTP request and response would be returned for debugging. The request contained the bearer JWT f CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-39304 | | 
| 20221227T13:24:17Z | CVE-2022-38873 | D-Link devices DAP-2310 v2.10rc036 and earlier, DAP-2330 v1.06rc020 and earlier, DAP-2360 v2.10rc050 and earlier, DAP-2553 v3.10rc031 and earlier, DAP-2660 v1.15rc093 and earlier, DAP-2690 v3.20rc106 and earlier, DAP-2695 v1.20rc119_beta31 and earlier, DAP-3320 v1.05rc027 beta and earlier, DAP-3662 v1.05rc047 and earli CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-38873 | | 
| 20221227T13:24:14Z | CVE-2022-4515 | A flaw was found in Exuberant Ctags in the way it handles the "-o" option. This option specifies the tag filename. A crafted tag filename specified in the command line or in the configuration file results in arbitrary command execution because the externalSortTags() in sort.c calls the system(3) function in an unsafe w CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4515 | | 
| 20221227T13:24:10Z | CVE-2022-43875 | IBM Financial Transaction Manager for SWIFT Services for Multiplatforms 3.2.4 could allow an authenticated user to lock additional RM authorizations, resulting in a denial of service on displaying or managing these authorizations. IBM X-Force ID: 240034. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-43875 | | 
| 20221227T13:24:07Z | CVE-2022-43872 | IBM Financial Transaction Manager 3.2.4 authorization checks are done incorrectly for some HTTP requests which allows getting unauthorized technical information (e.g. event log entries) about the FTM SWIFT system. IBM X-Force ID: 239708. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-43872 | | 
| 20221227T13:24:04Z | CVE-2022-23537 | PJSIP is a free and open source multimedia communication library written in C language implementing standard based protocols such as SIP, SDP, RTP, STUN, TURN, and ICE. Buffer overread is possible when parsing a specially crafted STUN message with unknown attribute. The vulnerability affects applications that uses STUN CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-23537 | | 
| 20221227T13:24:00Z | CVE-2022-4619 | The Sidebar Widgets by CodeLights plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the ‘Extra CSS class’ parameter in versions up to, and including, 1.4 due to insufficient input sanitization and output escaping. This makes it possible for authenticated attackers, with administrator-level permissio CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4619 | | 
| 20221227T13:23:56Z | CVE-2022-46020 | WBCE CMS v1.5.4 can implement getshell by modifying the upload file type. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-46020 | | 
| 20221227T13:23:37Z | CVE-2022-20527 | In HalCoreCallback of halcore.cc, there is a possible out of bounds read due to a missing bounds check. This could lead to local information disclosure from the NFC firmware with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-13Android ID: A- CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20527 | | 
| 20221227T13:23:33Z | CVE-2022-20515 | In onPreferenceClick of AccountTypePreferenceLoader.java, there is a possible way to retrieve protected files from the Settings app due to a confused deputy. This could lead to local information disclosure with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVe CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20515 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221227T12:53:18Z | A vulnerability, which was classified as problematic, was found in Opencaching Deutschland oc-server3. Affected is an unknown function of the file htdocs/lang/de/ocstyle/varset.inc.php. The manipulation of the argument varvalue leads to cross site scripting. It is possible to launch the attack remotely. The exploit has CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4514 | 0 | 0| 
| 20221227T12:52:30Z | The backup module has a path traversal vulnerability. Successful exploitation of this vulnerability causes unauthorized access to other system files. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-41591 | 0 | 0| 
| 20221227T12:52:26Z | Some smartphones have authentication-related (including session management) vulnerabilities as the setup wizard is bypassed. Successful exploitation of this vulnerability affects the smartphone availability. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-41590 | 0 | 0| 
| 20221227T12:52:16Z | The multi-screen collaboration module has a path traversal vulnerability. Successful exploitation of this vulnerability may affect data confidentiality. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-46856 | 0 | 0| 
| 20221227T12:51:44Z | The Blue Admin WordPress plugin through 21.06.01 does not sanitise or escape its %Logo Title% setting before outputting in a page, leading to a Stored Cross-Site Scripting issue. Furthermore, the plugin does not have CSRF check in place when saving its settings, allowing the issue to be exploited via a CSRF attack. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-24581 | 0 | 0| 
| 20221227T12:45:02Z | The package smoothie from 1.31.0 and before 1.36.1 are vulnerable to Cross-site Scripting (XSS) due to improper user input sanitization in strokeStyle and tooltipLabel properties. Exploiting this vulnerability is possible when the user can control these properties. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-25929 | 0 | 0| 
| 20221227T12:44:56Z | The package vm2 before 3.9.10 are vulnerable to Arbitrary Code Execution due to the usage of prototype lookup for the WeakMap.prototype.set method. Exploiting this vulnerability leads to access to a host object and a sandbox compromise. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-25893 | 0 | 0| 
| 20221227T12:20:42Z | The vampire legacies script roblox by ROOT44 want to buy script contact mehttps://root44xs.neocities.org/contact | https://github.com/ROOT44x/The-vampire-legacies-script-selling- | 0 | 0| 
| 20221227T12:07:19Z | Adobe Illustrator versions 26.5.1 (and earlier), and 27.0 (and earlier) are affected by an out-of-bounds read vulnerability that could lead to disclosure of sensitive memory. An attacker could leverage this vulnerability to bypass mitigations such as ASLR. Exploitation of this issue requires user interaction in that a  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-44500 | 0 | 0| 
| 20221227T12:07:16Z | Adobe Illustrator versions 26.5.1 (and earlier), and 27.0 (and earlier) are affected by an out-of-bounds read vulnerability that could lead to disclosure of sensitive memory. An attacker could leverage this vulnerability to bypass mitigations such as ASLR. Exploitation of this issue requires user interaction in that a  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-44499 | 0 | 0| 


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
| 20221227T13:19:54Z | A fuzzy positive/negative covid prediction system base on occurrence and confirmability matrices. | https://github.com/miladbarooni/FuzzyCovidDetection | 0 | 0| 
| 20221227T13:02:07Z | This blog written_Patika.dev_Introduction to Data Science | https://github.com/hlttcamm/FUZZY-LOGIC-SYSTEMS-AT-MATLAB | 0 | 0| 
| 20221227T12:31:26Z | Null | https://github.com/Danday999/fuzzy-memory | 1 | 0| 
| 20221227T11:21:24Z | Mozilla developers Bryce Seager van Dyk and the Mozilla Fuzzing Team reported potential vulnerabilities present in Firefox 101. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability affects Firefox CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-34485 | 0 | 0| 
| 20221227T11:20:47Z | Mozilla developers Gabriele Svelto, Timothy Nikkel, Randell Jesup, Jon Coppeard, and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 100. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code.  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-31748 | 0 | 0| 
| 20221227T11:20:15Z | Mozilla developers and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 102. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability affects Firefox ESR < 102.1, Firefox < 103, CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-2505 | 0 | 0| 
| 20221227T11:20:12Z | Mozilla developers Andrew McCreight, Gabriele Svelto, Tom Ritter and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 99 and Firefox ESR 91.8. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary co CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-29917 | 0 | 0| 
| 20221227T11:20:09Z | Mozilla developers Gabriele Svelto, Randell Jesup and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 99. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability affects Firef CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-29918 | 0 | 0| 
| 20221227T11:19:47Z | Mozilla developers and community members Randell Jesup, Sebastian Hengst, and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 98. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vul CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-28288 | 0 | 0| 
| 20221227T10:47:27Z | Mozilla developers and community members Gabriele Svelto, Sebastian Hengst, Randell Jesup, Luan Herrera, Lars T Hansen, and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 96. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-0511 | 0 | 0| 



# 日更新程序
