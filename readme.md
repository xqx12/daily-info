# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230116 | 深入解读syzkaller源码及其设计系列 | https://f0rm2l1n.github.io/2021-02-02-syzkaller-diving-01/| 
| 20230116 | 通过一处CSRF漏洞接管Yahoo任意账户，笔者找到一处http patch方法的csrf漏洞，利用后端框架的问题覆盖成为任意http方法，最终实现修改任意账户密码等行为。 | https://infosecwriteups.com/csrf-leads-to-account-takeover-in-yahoo-aa96c678d2aa?gi=c86109ae76ee&source=rss----7b722bfd1b8d---4| 
| 20230116 | CVE-2023-0179 内核栈溢出POC以及详细分析。该漏洞可以通过覆盖栈上的变量来RCE。 | https://www.reddit.com/r/netsec/comments/10d98w1/cve20230179_linux_kernel_stack_buffer_overflow_in/| 
| 20230116 | Windows Defender AsProtect堆溢出漏洞的详细利用过程。 | https://www.pixiepointsecurity.com/blog/nday-cve-2021-31985.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230116 | 文件上传漏洞总结 | https://www.sec-wiki.com/site/login| 
| 20230116 | SecWiki周刊（第463期) | https://www.sec-wiki.com/weekly/463| 
| 20230116 | JPCERT/CC 如何在云端自动化恶意软件分析 | https://mp.weixin.qq.com/s/xt4VX7UTBHab_Kuj9iEXcg| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230116T21:14:22Z | CVE-2022-47630 | Trusted Firmware-A through 2.8 has an out-of-bounds read in the X.509 parser for parsing boot certificates. This affects downstream use of get_ext and auth_nvctr. Attackers might be able to trigger dangerous read side effects or obtain sensitive information about microarchitectural state. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-47630 | | 
| 20230116T21:14:17Z | CVE-2023-0327 | A vulnerability was found in saemorris TheRadSystem. It has been classified as problematic. Affected is an unknown function of the file users.php. The manipulation of the argument q leads to cross site scripting. It is possible to launch the attack remotely. VDB-218454 is the identifier assigned to this vulnerability. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0327 | | 
| 20230116T17:59:11Z | CVE-2022-4658 | The RSSImport WordPress plugin through 4.6.1 does not validate and escape one of its shortcode attributes, which could allow users with a role as low as contributor to perform Stored Cross-Site Scripting attack. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4658 | | 
| 20230116T17:59:07Z | CVE-2022-4655 | The Welcart e-Commerce WordPress plugin before 2.8.9 does not validate and escapes one of its shortcode attributes, which could allow users with a role as low as a contributor to perform a Stored Cross-Site Scripting attack. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4655 | | 
| 20230116T17:59:02Z | CVE-2022-4653 | The Greenshift WordPress plugin before 4.8.9 does not validate and escape one of its shortcode attributes, which could allow users with a role as low as contributor to perform Stored Cross-Site Scripting attack. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4653 | | 
| 20230116T17:58:59Z | CVE-2022-4648 | The Real Testimonials WordPress plugin before 2.6.0 does not validate and escape some of its shortcode attributes before outputting them back in the page, which could allow users with a role as low as contributor to perform Stored Cross-Site Scripting attacks which could be used against high privilege users such as adm CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4648 | | 
| 20230116T17:58:54Z | CVE-2022-4578 | The Video Conferencing with Zoom WordPress plugin before 4.0.10 does not validate and escape some of its shortcode attributes before outputting them back in the page, which could allow users with a role as low as contributor to perform Stored Cross-Site Scripting attacks which could be used against high privilege users CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4578 | | 
| 20230116T17:58:50Z | CVE-2022-4571 | The Seriously Simple Podcasting WordPress plugin before 2.19.1 does not validate and escape some of its shortcode attributes before outputting them back in the page, which could allow users with a role as low as contributor to perform Stored Cross-Site Scripting attacks which could be used against high privilege users  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4571 | | 
| 20230116T17:58:46Z | CVE-2022-4549 | The Tickera WordPress plugin before 3.5.1.0 does not have CSRF check in place when updating its settings, which could allow attackers to make a logged-in admin change them via a CSRF attack. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4549 | | 
| 20230116T17:58:42Z | CVE-2022-4547 | The Conditional Payment Methods for WooCommerce WordPress plugin through 1.0 does not properly sanitise and escape a parameter before using it in a SQL statement, leading to a SQL injection exploitable by [high privilege users such as admin,users with a role as low as admin. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-4547 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230116T08:35:19Z | An open-source Simplified Chinese font derived from Klee One. | https://github.com/lxgw/LxgwWenkaiGB | 193 | 1| 
| 20230116T05:26:06Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2140 | 604| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230116T22:58:18Z | The Voidware Blatant config for Mobile Exploits | https://github.com/SystemXVoid/VoidwareMBConfig | 0 | 0| 
| 20230116T21:59:15Z | Bookmarklet exploit that can force-disable extensions installed on Chrome. Also has a very fancy GUI to manage all extensions! | https://github.com/3kh0/ext-remover | 135 | 121| 
| 20230116T21:24:08Z | During the exploitation phase of a pen test or ethical hacking engagement, you will ultimately need to try to cause code to run on target system computers. Whether accomplished by phishing emails, delivering a payload through an exploit, or social engineering, running code on target computers is part of most penetration tests. That means that you will need to be able to bypass antivirus software or other host-based protection for successful exploitation. The most effective way to avoid antivirus detection on your target%s computers is to create your own customized backdoor. Here is a simple way to evade anti-virus software when creating backdoors! | https://github.com/RoseSecurity/Anti-Virus-Evading-Payloads | 471 | 56| 
| 20230116T20:44:32Z | Null | https://github.com/codingcore12/SILENT-DOC-EXPLOIT-CLEAN-re | 1 | 0| 
| 20230116T19:55:03Z | roblox exploits repo | https://github.com/Monochrome-DEV/roblos-exploitings | 0 | 0| 
| 20230116T16:59:16Z | Cobalt Strike is a post-exploitation framework designed to be extended and customized by the user community. Several excellent tools and scripts have been written and published, but they can be challenging to locate. Community Kit is a central repository of extensions written by the user community to extend the capabilities of Cobalt Strike. The Cobalt Strike team acts as the curator and provides this kit to showcase this fantastic work. | https://github.com/Cobalt-Strike/community_kit | 159 | 2| 
| 20230116T13:42:21Z | This repository is primarily maintained by Omar Santos (@santosomar) and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 12592 | 2162| 
| 20230116T13:29:05Z | Learn & Contribute on previously exploited vulnerabilities across several EVM projects. | https://github.com/coinspect/learn-evm-attacks | 565 | 56| 
| 20230116T12:36:22Z | A C# MS SQL toolkit designed for offensive reconnaissance and post-exploitation.  | https://github.com/skahwah/SQLRecon | 297 | 67| 
| 20230116T11:52:00Z | A solution to the Travelling Sales Man problem using Genetic Algorithm that implements Elitism for optimization, Edge Adjacency Table operation for Exploration and Mutation for Exploitation. | https://github.com/samuelmunyoki/Travelling-Sales-Man-Problem | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230116T23:37:09Z | Hacking tools pack & backdoors generator. | https://github.com/AdrMXR/KitHack | 1204 | 167| 
| 20230116T21:24:08Z | During the exploitation phase of a pen test or ethical hacking engagement, you will ultimately need to try to cause code to run on target system computers. Whether accomplished by phishing emails, delivering a payload through an exploit, or social engineering, running code on target computers is part of most penetration tests. That means that you will need to be able to bypass antivirus software or other host-based protection for successful exploitation. The most effective way to avoid antivirus detection on your target%s computers is to create your own customized backdoor. Here is a simple way to evade anti-virus software when creating backdoors! | https://github.com/RoseSecurity/Anti-Virus-Evading-Payloads | 471 | 56| 
| 20230116T19:25:13Z | The BackDoor of HIPHP gives you the power to control websites based on PHP using HTTP/HTTPS protocol. By sending files, tokens and commands through port 80%s POST/GET method, users can access a range of activities such as downloading and editing files. It also allows for connecting to Tor networks with password protection for extra security. | https://github.com/yasserbdj96/hiphp | 36 | 10| 
| 20230116T19:13:12Z | This is a shortened code of the Roblox Lua Crash, this exploit needs Serverside to kick the other players. This will crash everybody%s roblox client. Also, you backdoor exploiters, you can get it and ruin other%s fun. | https://github.com/IvanTheProtogen/Roblox-Crash-Lua | 0 | 0| 
| 20230116T19:11:49Z | Official repository of paper BEAGLE: Forensics of Deep Learning Backdoor Attack for Better Defense | https://github.com/Megum1/BEAGLE | 1 | 0| 
| 20230116T13:58:34Z | Null | https://github.com/Deepu-duck/Backdoor | 0 | 0| 
| 20230116T07:01:45Z | Null | https://github.com/marcusd7/Chameleon-durable-backdoor | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230116T21:19:50Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3274 | 464| 
| 20230116T19:07:00Z | The symbolic execution engine powering the K Framework | https://github.com/runtimeverification/haskell-backend | 183 | 42| 
| 20230116T15:58:17Z | Unicorn: Symbolic Execution, Bounded Model Checking, and Code Optimization of RISC-V Code using Classical Solvers and Quantum Computers | https://github.com/cksystemsgroup/unicorn | 13 | 4| 
| 20230116T15:37:29Z | Open-source symbolic execution framework: https://maat.re | https://github.com/trailofbits/maat | 537 | 31| 
| 20230116T10:58:03Z | Bachelor thesis, attempting decompilation using symbolic execution | https://github.com/lokegustafsson/thesis-decompilation | 1 | 0| 
| 20230116T05:26:06Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 2140 | 605| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230116T14:35:43Z | Anomaly Detection in the Open World: Normality Shift Detection, Explanation, and Adaptation (NDSS%23). | https://github.com/dongtsi/OWAD | 5 | 1| 
| 20230116T10:17:44Z | ConfFuzz NDSS Data Set | https://github.com/conffuzz/conffuzz-ndss-data | 1 | 1| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230116T23:34:18Z | Null | https://github.com/AbanoubSamir004/Fuzzy_CMean_VS__Kmean | 0 | 0| 
| 20230116T22:05:34Z | GraphQLmap is a scripting engine to interact with a graphql endpoint for pentesting purposes. - Do not use for illegal testing ;) | https://github.com/swisskyrepo/GraphQLmap | 960 | 158| 
| 20230116T13:57:00Z | SecLists is the security tester%s companion. It%s a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. | https://github.com/danielmiessler/SecLists | 44262 | 22004| 
| 20230116T13:41:14Z | Ethereum smart contract fuzzer | https://github.com/crytic/echidna | 1871 | 241| 
| 20230116T13:20:44Z | DeepFuzz 논문만 보고 구현 | https://github.com/KEEPER31337/DeepFuzz | 0 | 2| 
| 20230116T13:19:03Z | Test repo With public visibility | https://github.com/jlec/test-fuzzy-public | 0 | 0| 
| 20230116T13:17:07Z | DeepFuzz 논문만 보고 구현 | https://github.com/1004-head/DeepFuzz | 0 | 0| 
| 20230116T13:15:39Z | Null | https://github.com/TheFuzzyUngulate/fuzzyungulate.github.io | 0 | 0| 
| 20230116T12:42:22Z | ✨🔐 CNCF Fuzzers | https://github.com/cncf/cncf-fuzzing | 62 | 26| 
| 20230116T12:04:19Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8277 | 1805| 



# 日更新程序
