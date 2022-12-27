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
| 20221227T12:53:25Z | CVE-2022-20556 | In launchConfigNewNetworkFragment of NetworkProviderSettings.java, there is a possible way for the guest user to add a new WiFi network due to a missing permission check. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.Prod CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20556 | | 
| 20221227T12:53:21Z | CVE-2022-20557 | In MessageQueueBase of MessageQueueBase.h, there is a possible out of bounds read due to a missing bounds check. This could lead to local escalation of privilege with System execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-13Android ID: A-247092734 CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20557 | | 
| 20221227T12:53:18Z | CVE-2022-4514 | A vulnerability, which was classified as problematic, was found in Opencaching Deutschland oc-server3. Affected is an unknown function of the file htdocs/lang/de/ocstyle/varset.inc.php. The manipulation of the argument varvalue leads to cross site scripting. It is possible to launch the attack remotely. The exploit has CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4514 | | 
| 20221227T12:53:14Z | CVE-2022-44643 | A vulnerability in the label-based access control of Grafana Labs Grafana Enterprise Metrics allows an attacker more access than intended. If an access policy which has label selector restrictions also has been granted access to all tenants in the system, the label selector restrictions will not be applied when using t CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-44643 | | 
| 20221227T12:53:11Z | CVE-2022-4520 | A vulnerability was found in WSO2 carbon-registry up to 4.8.11. It has been rated as problematic. Affected by this issue is some unknown functionality of the file components/registry/org.wso2.carbon.registry.search.ui/src/main/resources/web/search/advancedSearchForm-ajaxprocessor.jsp of the component Advanced Search. T CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4520 | | 
| 20221227T12:53:08Z | CVE-2022-20549 | In authToken2AidlVec of KeyMintUtils.cpp, there is a possible out of bounds write due to an incorrect bounds check. This could lead to local escalation of privilege with System execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-13Android ID: A-242702451 CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20549 | | 
| 20221227T12:53:04Z | CVE-2022-20554 | In removeEventHubDevice of InputDevice.cpp, there is a possible OOB read due to a use after free. This could lead to local escalation of privilege with System execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-13Android ID: A-245770596 CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20554 | | 
| 20221227T12:53:01Z | CVE-2022-20550 | In Multiple Locations, there is a possibility to launch arbitrary protected activities due to a confused deputy. This could lead to local escalation of privilege with User execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android-13Android ID: A-242845514 CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20550 | | 
| 20221227T12:52:58Z | CVE-2022-4522 | A vulnerability classified as problematic was found in CalendarXP up to 10.0.1. This vulnerability affects unknown code. The manipulation leads to cross site scripting. The attack can be initiated remotely. Upgrading to version 10.0.2 is able to address this issue. The name of the patch is e3715b2228ddefe00113296069969 CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4522 | | 
| 20221227T12:52:54Z | 未知编号 | Use-after-free vulnerability in the setInterval method in Adobe Flash Player before 18.0.0.333 and 19.x through 21.x before 21.0.0.182 on Windows and OS X and before 11.2.202.577 on Linux, Adobe AIR before 21.0.0.176, Adobe AIR SDK before 21.0.0.176, and Adobe AIR SDK & Compiler before 21.0.0.176 allows attackers to ex CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2016-0996 | | 


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
| 20221227T13:14:19Z | THE BEST BACDOOR FOR FIVEM (I AM NOT RESPONSIBLE FOR THE CHARGES MADE WITH THIS SCRIPT) | https://github.com/nutria22/fivem-backdoor | 0 | 0| 
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
| 20221227T13:02:07Z | This blog written_Patika.dev_Introduction to Data Science | https://github.com/hlttcamm/FUZZY-LOGIC-SYSTEMS-AT-MATLAB | 0 | 0| 
| 20221227T12:31:26Z | Null | https://github.com/Danday999/fuzzy-memory | 1 | 0| 
| 20221227T11:21:24Z | Mozilla developers Bryce Seager van Dyk and the Mozilla Fuzzing Team reported potential vulnerabilities present in Firefox 101. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability affects Firefox CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-34485 | 0 | 0| 
| 20221227T11:20:47Z | Mozilla developers Gabriele Svelto, Timothy Nikkel, Randell Jesup, Jon Coppeard, and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 100. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code.  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-31748 | 0 | 0| 
| 20221227T11:20:15Z | Mozilla developers and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 102. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability affects Firefox ESR < 102.1, Firefox < 103, CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-2505 | 0 | 0| 
| 20221227T11:20:12Z | Mozilla developers Andrew McCreight, Gabriele Svelto, Tom Ritter and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 99 and Firefox ESR 91.8. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary co CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-29917 | 0 | 0| 
| 20221227T11:20:09Z | Mozilla developers Gabriele Svelto, Randell Jesup and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 99. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability affects Firef CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-29918 | 0 | 0| 
| 20221227T11:19:47Z | Mozilla developers and community members Randell Jesup, Sebastian Hengst, and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 98. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vul CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-28288 | 0 | 0| 
| 20221227T10:47:27Z | Mozilla developers and community members Gabriele Svelto, Sebastian Hengst, Randell Jesup, Luan Herrera, Lars T Hansen, and the Mozilla Fuzzing Team reported memory safety bugs present in Firefox 96. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-0511 | 0 | 0| 
| 20221227T10:45:34Z | Mozilla developers Ashley Hale and the Mozilla Fuzzing Team reported memory safety bugs present in Thunderbird 102.3. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability affects Thunderbird < 102 CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-42932 | 0 | 0| 



# 日更新程序
