# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210601 | HITB 2021 AMS 会议议题，Android 混合应用（Hybrid Application）的新攻击模型，来自 Ce Qin | https://conference.hitb.org/hitbsecconf2021ams/materials/D2T1%20-%20A%20New%20Attack%20Model%20for%20Hybrid%20Mobile%20Applications%20-%20Ce%20Qin.pdf| 
| 20210601 | 西门子 PLC 代码执行漏洞分析（CVE-2020-15782） | https://claroty.com/2021/05/28/blog-research-race-to-native-code-execution-in-plcs/| 
| 20210601 | HITB 2021 AMS 会议议题 “Lightbranch: Binary Fuzzing with Snapshot-Assisted-Driven Comparison Branches Analysis” | https://conference.hitb.org/hitbsecconf2021ams/materials/D2T2%20-%20Binary%20Fuzzing%20with%20Snapshot-Assisted-Driven%20Comparison%20Branch%20Analysis%20-%20Kijong%20Son.pdf| 
| 20210601 | 来自 USENIX 的一篇 Paper，作者提出一种缓解内核漏洞（Bug）的 Workarounds 方法，以 undo 的方式缓解问题 syscall 带来的影响 | https://www.usenix.org/system/files/sec21fall-talebi.pdf| 
| 20210601 | Finding Memory Bugs with Google Address Sanitizer (ASAN) on Microcontrollers | https://mcuoneclipse.com/2021/05/31/finding-memory-bugs-with-google-address-sanitizer-asan-on-microcontrollers/| 
| 20210601 | Chrome 浏览器 AppCache 机制相关的跨域跳转 URL 泄露漏洞 | https://blog.lbherrera.me/posts/appcache-forgotten-tales/| 
| 20210601 | Pwn2Win CTF 2021 Writeup | https://ptr-yudai.hatenablog.com/entry/2021/05/31/232507| 
| 20210601 | INVSCOV - 这篇 paper 基于 LLVM 与 AFL++ 尝试解决 Fuzz 过程中基于覆盖率的反馈算法不足的问题 | http://www.s3.eurecom.fr/docs/usenixsec21_fioraldi.pdf| 
| 20210601 | Microsoft Hyper-V vmswitch.sys RCE 虚拟机逃逸漏洞 PoC（CVE-2021-28476） | https://github.com/0vercl0k/CVE-2021-28476| 
| 20210601 | 来自Readme的威胁｜疑似长达数年的供应链攻击分析 | https://sec.today/pulses/89023c4c-9ecc-4a28-82dc-8822e660710b/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210601 | 智能合约安全系列 -- 举一反三总结篇 | https://mp.weixin.qq.com/s/ZxrBHgZ5a_IuU0nNySIlwA| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210601T11:26:54Z | CVE-2021-29447 | Wordpress XXE injection 구축 자동화 및 PoC  | https://github.com/dnr6419/CVE-2021-29447 | Wordpress is an open source CMS. A user with the ability to upload files (like an Author) can exploit an XML parsing issue in the Media Library leading to XXE attacks. This requires WordPress installation to be using PHP 8. Access to internal files is possible in a successful XXE attack. This has been patched in WordPress version 5.7.1, along with the older affected versions via a minor release. We strongly recommend you keep auto-updates enabled.| 
| 20210601T11:18:36Z | CVE-2021-2989 | test | https://github.com/dorisroot1/CVE-2021-2989 | 未查询到CVE信息| 
| 20210601T10:41:33Z | CVE-2021-3999 | CVE-2021-3999 | https://github.com/dorisroot1/CVE-2021-3999 | 未查询到CVE信息| 
| 20210601T09:37:59Z | CVE-2021-32620 | PoC for exploiting CVE-2021-32620 | https://github.com/JamesGeee/CVE-2021-32620 | ### Impact A user disabled on a wiki using email verification for registration can re-activate himself by using the activation link provided for his registration. ### Patches The problem has been patched in the following versions of XWiki: 11.10.13, 12.6.7, 12.10.2, 13.0. ### Workarounds It%s possible to workaround the issue by resetting the `validkey` property of the disabled XWiki users. This can be done by editing the user profile with object editor. ### References https://jira.xwiki.org/browse/XWIKI-17942 ### For more information If you have any questions or comments about this advisory: * Open an issue in [Jira](http://jira.xwiki.org) * Email us at [Security mailing-list](mailto:security@xwiki.org)| 
| 20210601T09:37:55Z | CVE-2021-29507 | PoC for exploiting CVE-2021-29507 | https://github.com/JamesGeee/CVE-2021-29507 | ### Impact _What kind of vulnerability is it? Who is impacted?_ The vulnerable component could be crashed when the configuration file is intentionally/ unintentionally containing the special characters. All the applications which are using could fail to generate their dlt logs in system. ### Patches _Has the problem been patched? What versions should users upgrade to?_ There is solution for the problem but the patch is not integrated yet. ### Workarounds _Is there a way for users to fix or remediate the vulnerability without upgrading?_ Check the integrity of information in configuration file manually. ### References _Are there any links users can visit to find out more?_ N/A ### For more information If you have any questions or comments about this advisory: * Open an issue in [ GENIVI/dlt-daemon ](https://github.com/GENIVI/dlt-daemon/issues) * Email us at [Mailinglist](mailto:https://lists.genivi.org/mailman/listinfo/genivi-diagnostic-log-and-trace_lists.genivi.org)| 
| 20210601T09:37:40Z | CVE-2021-29505 | PoC for exploiting CVE-2021-29505 | https://github.com/JamesGeee/CVE-2021-29505 | ### Impact The vulnerability may allow a remote attacker has sufficient rights to execute commands of the host only by manipulating the processed input stream. No user is affected, who followed the recommendation to setup XStream%s security framework with a whitelist limited to the minimal required types. ### Patches If you rely on XStream%s default blacklist of the Security Framework, you will have to use at least version 1.4.17. ### Workarounds See [workarounds](https://x-stream.github.io/security.html#workaround) for the different versions covering all CVEs. ### References See full information about the nature of the vulnerability and the steps to reproduce it in XStream%s documentation for [CVE-2021-xxxxx](https://x-stream.github.io/CVE-2021-xxxxx.html). ### Credits V3geB1rd, white hat hacker from Tencent Security Response Center found and reported the issue to XStream and provided the required information to reproduce it. ### For more information If you have any questions or comments about this advisory: * Open an issue in [XStream](https://github.com/x-stream/xstream/issues) * Email us at [XStream Google Group](https://groups.google.com/group/xstream-user)| 
| 20210601T09:37:36Z | CVE-2021-29492 | PoC for exploiting CVE-2021-29492 | https://github.com/JamesGeee/CVE-2021-29492 | ### Description Envoy does not decode escaped slash sequences `%2F` and `%5C` in HTTP URL paths in versions 1.18.2 and before. A remote attacker may craft a path with escaped slashes, e.g. `/something%2F..%2Fadmin`, to bypass access control, e.g. a block on `/admin`. A backend server could then decode slash sequences and normalize path and provide an attacker access beyond the scope provided for by the access control policy. ### Impact Escalation of Privileges when using RBAC or JWT filters with enforcement based on URL path. Users with back end servers that interpret `%2F` and `/` and `%5C` and `\` interchangeably are impacted. ### Attack Vector URL paths containing escaped slash characters delivered by untrusted client. ### Patches Envoy versions 1.18.3, 1.17.3, 1.16.4, 1.15.5 contain new path normalization option to decode escaped slash characters. ### Workarounds If back end servers treat `%2F` and `/` and `%5C` and `\` interchangeably and a URL path based access control is configured, we recommend reconfiguring back end server to not treat `%2F` and `/` and `%5C` and `\` interchangeably if feasible. ### Credit Ruilin Yang (ruilin.yrl@gmail.com) ### References https://blog.envoyproxy.io https://github.com/envoyproxy/envoy/releases ### For more information If you have any questions or comments about this advisory: * Open an issue in [Envoy repo](https://github.com/envoyproxy/envoy/issues) * Email us at [envoy-security](mailto:envoy-security@googlegroups.com)| 
| 20210601T09:37:32Z | CVE-2020-36375 | PoC for exploiting CVE-2020-36375 | https://github.com/JamesGeee/CVE-2020-36375 | Stack overflow vulnerability in parse_equality Cesanta MJS 1.20.1, allows remote attackers to cause a Denial of Service (DoS) via a crafted file.| 
| 20210601T09:37:29Z | CVE-2020-36374 | PoC for exploiting CVE-2020-36374 | https://github.com/JamesGeee/CVE-2020-36374 | Stack overflow vulnerability in parse_comparison Cesanta MJS 1.20.1, allows remote attackers to cause a Denial of Service (DoS) via a crafted file.| 
| 20210601T09:37:25Z | CVE-2020-36373 | PoC for exploiting CVE-2020-36373 | https://github.com/JamesGeee/CVE-2020-36373 | Stack overflow vulnerability in parse_shifts Cesanta MJS 1.20.1, allows remote attackers to cause a Denial of Service (DoS) via a crafted file.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210601T08:30:57Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1708 | 494| 
| 20210601T02:37:36Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 641 | 15| 
| 20210601T00:42:00Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 10 | 1| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210601T01:59:59Z | A bunch of scripts to exploit my vulnerable web app | https://github.com/kitty14956590/vuln-webapp-scripts | 0 | 0| 
| 20210601T01:50:34Z | This is a plugin for Minecraft that aids in building, as it gives the player creative mode and charges them for each block they place. All exploits are patched as well. | https://github.com/bsalha1/Printer | 2 | 4| 
| 20210601T01:44:56Z | Scripting Utility For ROBLOX. | https://github.com/PcTechery/Bit | 1 | 0| 
| 20210601T01:41:55Z | Config files for my GitHub profile. | https://github.com/Exploiter-HuTao/Exploiter-HuTao | 0 | 0| 
| 20210601T01:24:32Z | An experiment with exploiting ntl dll files to shutdown a computer remotely. | https://github.com/poet5/ss-nullbyte | 0 | 0| 
| 20210601T01:12:12Z | bespoke tooling for offensive security%s Windows Usermode Exploit Dev course (OSED) | https://github.com/epi052/osed-scripts | 30 | 12| 
| 20210601T01:03:53Z | rails-exploit | https://github.com/hoanx-2146/rails-exploit | 0 | 0| 
| 20210601T01:02:48Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 24 | 11| 
| 20210601T00:39:39Z | Exploit Database binary exploits located in the /sploits directory | https://github.com/offensive-security/exploitdb-bin-sploits | 1446 | 505| 
| 20210601T00:19:01Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9514 | 1539| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210601T01:56:24Z | Null | https://github.com/Michaelmw17/fuzzy-lamp-amplify | 0 | 0| 
| 20210601T01:25:33Z | A collection of algorithms for fuzzy search like in Sublime Text. | https://github.com/tajmone/fuzzy-search | 26 | 2| 
| 20210601T00:52:14Z | Null | https://github.com/yanzhoupan/gen-fuzz | 1 | 0| 
| 20210601T00:09:07Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 7 | 5| 



# 日更新程序
