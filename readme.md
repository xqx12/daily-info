# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210627 | 利用 Hook 技术打造通用的 Webshell | https://jayl1n.github.io/2021/06/25/use-inlinehook-technology-to-make-a-more-general-webshell/| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210627T23:32:42Z | CVE-2021-27850 | A Proof of concept for CVE-2021-27850 affecting Apache Tapestry and leading to unauthencticated remote code execution. | https://github.com/kahla-sec/CVE-2021-27850_POC | A critical unauthenticated remote code execution vulnerability was found all recent versions of Apache Tapestry. The affected versions include 5.4.5, 5.5.0, 5.6.2 and 5.7.0. The vulnerability I have found is a bypass of the fix for CVE-2019-0195. Recap: Before the fix of CVE-2019-0195 it was possible to download arbitrary class files from the classpath by providing a crafted asset file URL. An attacker was able to download the file `AppModule.class` by requesting the URL `http://localhost:8080/assets/something/services/AppModule.class` which contains a HMAC secret key. The fix for that bug was a blacklist filter that checks if the URL ends with `.class`, `.properties` or `.xml`. Bypass: Unfortunately, the blacklist solution can simply be bypassed by appending a `/` at the end of the URL: `http://localhost:8080/assets/something/services/AppModule.class/` The slash is stripped after the blacklist check and the file `AppModule.class` is loaded into the response. This class usually contains the HMAC secret key which is used to sign serialized Java objects. With the knowledge of that key an attacker can sign a Java gadget chain that leads to RCE (e.g. CommonsBeanUtils1 from ysoserial). Solution for this vulnerability: * For Apache Tapestry 5.4.0 to 5.6.1, upgrade to 5.6.2 or later. * For Apache Tapestry 5.7.0, upgrade to 5.7.1 or later.| 
| 20210627T20:11:26Z | CVE-2021-31955 | Null | https://github.com/mavillon1/CVE-2021-31955-POC | | 
| 20210627T15:49:59Z | CVE-2021-32537 | PoC for CVE-2021-32537: an out-of-bounds memory access that leads to pool corruption in the Windows kernel. | https://github.com/0vercl0k/CVE-2021-32537 | 未查询到CVE信息| 
| 20210627T04:48:33Z | CVE-2020-10558 | TESLA MODEL 3 HACK | https://github.com/AmazingOut/Tesla-CVE-2020-10558 | The driving interface of Tesla Model 3 vehicles in any release before 2020.4.10 allows Denial of Service to occur due to improper process separation, which allows attackers to disable the speedometer, web browser, climate controls, turn signal visual and sounds, navigation, autopilot notifications, along with other miscellaneous functions from the main screen.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210627T20:07:31Z | Personal Blog | https://github.com/klee1611/klee1611.github.io | 0 | 0| 
| 20210627T18:31:31Z | Null | https://github.com/JaimePSantos/ResearchKlee | 0 | 0| 
| 20210627T09:35:23Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 685 | 15| 
| 20210627T04:51:57Z | Null | https://github.com/Chiyukichan/klee_file | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210627T23:45:58Z | Resources for the Kr00k vulnerability (CVE-2019-15126) | https://github.com/raul23/Kr00k | 0 | 0| 
| 20210627T23:43:56Z | Fix exploits on anarchy minecraft servers | https://github.com/moom0o/AnarchyExploitFixes | 45 | 11| 
| 20210627T23:37:34Z | A collection of great discord bugs and exploits. | https://github.com/Passive/discord-exploits | 6 | 0| 
| 20210627T23:37:04Z | Modular penetration testing platform that enables you to write, test, and execute exploit code. | https://github.com/EntySec/HatSploit | 66 | 23| 
| 20210627T23:17:28Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9601 | 1571| 
| 20210627T23:12:31Z | Bcrypt Cracker & Exploitation Toolkit. | https://github.com/duckstroms/poll-bcrypt | 2 | 0| 
| 20210627T23:07:47Z | Makes it so that you can craft ores, non OP (cannot be exploited with Fortune). (Datapack) | https://github.com/zaydam1000000/craftable_ores | 0 | 0| 
| 20210627T22:34:06Z | SSRF search vulnerabilities exploitation extended. | https://github.com/duckstroms/ssrf-search | 12 | 3| 
| 20210627T22:03:18Z | Its a framework filled with alot of options and hacking tools you use directly in the script from brute forcing to payload making im still adding more stuff i now have another tool out called htkl-lite its hackers-tool-kit just not as big and messy to see updates check on my instagram @tuf_unkn0wn or if there are any problems message me on instagram | https://github.com/unkn0wnh4ckr/hackers-tool-kit | 241 | 101| 
| 20210627T21:33:55Z | Exploit MsIo vulnerable driver | https://github.com/kkent030315/MsIoExploit | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210627T23:08:17Z | Une simple Backdoor, donnant accés à l%ensemble des fichiers d%un ordinateur. | https://github.com/billythegoat356/F0rs4k3n | 2 | 0| 
| 20210627T21:45:25Z | You can make reverse shells ^-^ | https://github.com/6icada/BackDoorAccess | 0 | 0| 
| 20210627T21:23:45Z | Null | https://github.com/TRehderK/Backdoor | 0 | 0| 
| 20210627T21:07:30Z | PHP Backboor , Shell Backdoor list , Bypass shell backdoor  (For Educational Purposes Only).  | https://github.com/webshell-archive/PHP | 1 | 0| 
| 20210627T15:54:45Z | - PROJECT BACKDOOR | https://github.com/NonStopBle/Backdoor | 0 | 0| 
| 20210627T13:30:19Z | Null | https://github.com/FierzaEriez/Mini-Shell-Backdoor | 0 | 0| 
| 20210627T11:18:42Z | Ethical hacking backdoor malware source, do not use this program with unauthorized parties | https://github.com/icrescenti/YWV4 | 0 | 0| 
| 20210627T05:39:38Z | Windows Reverse Shell | https://github.com/knight8645726/Backdoor | 0 | 0| 
| 20210627T02:40:04Z | Null | https://github.com/Coops0/Anti-Backdoor | 0 | 0| 
| 20210627T01:04:51Z | Pytorch implementation of backdoor unlearning. | https://github.com/fmy266/Pytorch-Backdoor-Unlearning | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210627T20:50:09Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2367 | 348| 
| 20210627T18:59:44Z | Symbolic-execution-based verifier for the Viper intermediate verification language. | https://github.com/viperproject/silicon | 19 | 11| 
| 20210627T10:38:41Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 422 | 62| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210627T23:58:55Z | A fuzzer without the fuzz (or the wait). | https://github.com/cyberrumor/sitemap | 0 | 0| 
| 20210627T23:54:49Z | Null | https://github.com/kwky/Fuzzing-Assignment | 0 | 0| 
| 20210627T23:39:45Z | Null | https://github.com/DanielEbert/EmulatedFirmwareFuzzing | 0 | 0| 
| 20210627T23:06:54Z | Null | https://github.com/opimentel-github/fuzzy-tools | 0 | 0| 
| 20210627T22:47:57Z | Graph neural network for search fuzzy formula model | https://github.com/Apich238/neural-fuzzy-sat-solver | 0 | 0| 
| 20210627T22:35:14Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210627T22:08:18Z | CBOR codec (in Go) with CBOR tags, Go struct tags (toarray/keyasint/omitempty), float64/32/16, big.Int, and fuzz tested billions of execs for reliable RFC 7049 & RFC 8949.  | https://github.com/fxamacker/cbor | 284 | 21| 
| 20210627T20:39:44Z | Fuzz testing tool for big data applications using a systematic exploration of higher order mutations. | https://github.com/LvKvA/SysFuzz | 0 | 0| 
| 20210627T19:37:38Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6420 | 1304| 
| 20210627T19:14:43Z | Web fuzzer for penetration testing and bruteforcing | https://github.com/aga7hokakological/fuzzWeb | 0 | 0| 



# 日更新程序
