# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210605 | 来自Readme的威胁-疑似长达数年的供应链攻击分析 | https://security.tencent.com/index.php/blog/msg/192| 
| 20210605 | EISS2021-办公网零信任安全建设实践 | https://www.anquanke.com/post/id/241954| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210605T12:19:05Z | CVE-2021-25328 | PoC for exploiting CVE-2021-25328 | https://github.com/JamesGeeee/CVE-2021-25328 | Skyworth Digital Technology RN510 V.3.1.0.4 RN510 V.3.1.0.4 contains a buffer overflow vulnerability in /cgi-bin/app-staticIP.asp. An authenticated attacker can send a specially crafted request to endpoint which can lead to a denial of service (DoS) or possible code execution on the device.| 
| 20210605T12:19:04Z | CVE-2021-25327 | PoC for exploiting CVE-2021-25327 | https://github.com/JamesGeeee/CVE-2021-25327 | Skyworth Digital Technology RN510 V.3.1.0.4 contains a cross-site request forgery (CSRF) vulnerability in /cgi-bin/net-routeadd.asp and /cgi-bin/sec-urlfilter.asp. Missing CSRF protection in devices can lead to XSRF, as the above pages are vulnerable to cross-site scripting (XSS).| 
| 20210605T12:19:02Z | CVE-2020-13558 | PoC for exploiting CVE-2020-13558 | https://github.com/JamesGeeee/CVE-2020-13558 | A code execution vulnerability exists in the AudioSourceProviderGStreamer functionality of Webkit WebKitGTK 2.30.1. A specially crafted web page can lead to a use after free.| 
| 20210605T12:18:58Z | CVE-2021-23983 | PoC for exploiting CVE-2021-23983 | https://github.com/JamesGeeee/CVE-2021-23983 | By causing a transition on a parent node by removing a CSS rule, an invalid property for a marker could have been applied, resulting in memory corruption and a potentially exploitable crash. This vulnerability affects Firefox < 87.| 
| 20210605T12:18:54Z | CVE-2021-30159 | PoC for exploiting CVE-2021-30159 | https://github.com/JamesGeeee/CVE-2021-30159 | An issue was discovered in MediaWiki before 1.31.12 and 1.32.x through 1.35.x before 1.35.2. Users can bypass intended restrictions on deleting pages in certain %fast double move% situations. MovePage::isValidMoveTarget() uses FOR UPDATE, but it%s only called if Title::getArticleID() returns non-zero with no special flags. Next, MovePage::moveToInternal() will delete the page if getArticleID(READ_LATEST) is non-zero. Therefore, if the page is missing in the replica DB, isValidMove() will return true, and then moveToInternal() will unconditionally delete the page if it can be found in the master.| 
| 20210605T12:18:51Z | CVE-2021-30178 | PoC for exploiting CVE-2021-30178 | https://github.com/JamesGeeee/CVE-2021-30178 | An issue was discovered in the Linux kernel through 5.11.11. synic_get in arch/x86/kvm/hyperv.c has a NULL pointer dereference for certain accesses to the SynIC Hyper-V context, aka CID-919f4ebc5987.| 
| 20210605T12:18:48Z | CVE-2021-3393 | PoC for exploiting CVE-2021-3393 | https://github.com/JamesGeeee/CVE-2021-3393 | An information leak was discovered in postgresql in versions before 13.2, before 12.6 and before 11.11. A user having UPDATE permission but not SELECT permission to a particular column could craft queries which, under some circumstances, might disclose values from that column in error messages. An attacker could use this flaw to obtain information stored in a column they are allowed to write but not read.| 
| 20210605T12:18:33Z | CVE-2021-3448 | PoC for exploiting CVE-2021-3448 | https://github.com/JamesGeeee/CVE-2021-3448 | A flaw was found in dnsmasq in versions before 2.85. When configured to use a specific server for a given network interface, dnsmasq uses a fixed port while forwarding queries. An attacker on the network, able to find the outgoing port used by dnsmasq, only needs to guess the random transmission ID to forge a reply and get it accepted by dnsmasq. This flaw makes a DNS Cache Poisoning attack much easier. The highest threat from this vulnerability is to data integrity.| 
| 20210605T12:18:29Z | CVE-2021-30123 | PoC for exploiting CVE-2021-30123 | https://github.com/JamesGeeee/CVE-2021-30123 | FFmpeg <=4.3 contains a buffer overflow vulnerability in libavcodec through a crafted file that may lead to remote code execution.| 
| 20210605T12:18:26Z | CVE-2021-29642 | PoC for exploiting CVE-2021-29642 | https://github.com/JamesGeeee/CVE-2021-29642 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210605T06:20:01Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 647 | 15| 
| 20210605T06:05:27Z | A RISC-V RV32 virtual prototype based on riscv-vp with symbolic execution support | https://github.com/agra-uni-bremen/symex-vp | 2 | 0| 
| 20210605T06:02:09Z | A library for concolic execution of RV32 instruction set simulators | https://github.com/agra-uni-bremen/clover | 1 | 0| 
| 20210605T04:33:22Z | Dodoco doko? | https://github.com/RiceFT/klee | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210605T12:19:43Z | PoC for exploiting CVE-2021-28242 | https://github.com/JamesGeeee/CVE-2021-28242 | 0 | 0| 
| 20210605T12:19:35Z | PoC for exploiting CVE-2021-23985 | https://github.com/JamesGeeee/CVE-2021-23985 | 0 | 0| 
| 20210605T12:19:31Z | PoC for exploiting CVE-2021-23987 | https://github.com/JamesGeeee/CVE-2021-23987 | 0 | 0| 
| 20210605T12:19:28Z | PoC for exploiting CVE-2021-23986 | https://github.com/JamesGeeee/CVE-2021-23986 | 0 | 0| 
| 20210605T12:19:23Z | PoC for exploiting CVE-2021-23984 | https://github.com/JamesGeeee/CVE-2021-23984 | 0 | 0| 
| 20210605T12:19:20Z | PoC for exploiting CVE-2021-25327 | https://github.com/JamesGeeee/CVE-2021-25327 | 0 | 0| 
| 20210605T12:19:05Z | PoC for exploiting CVE-2021-25328 | https://github.com/JamesGeeee/CVE-2021-25328 | 0 | 0| 
| 20210605T12:19:02Z | PoC for exploiting CVE-2020-13558 | https://github.com/JamesGeeee/CVE-2020-13558 | 0 | 0| 
| 20210605T12:18:58Z | PoC for exploiting CVE-2021-23983 | https://github.com/JamesGeeee/CVE-2021-23983 | 0 | 0| 
| 20210605T12:18:54Z | PoC for exploiting CVE-2021-30159 | https://github.com/JamesGeeee/CVE-2021-30159 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210605T03:57:46Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 243 | 43| 
| 20210605T00:08:52Z | A simple and easy to use stresser for your ddos (booting) business services. | https://github.com/lolCourtesy/True-Security-Services-io-Shells-Backdoors-Removed | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210605T12:15:17Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 8 | 5| 
| 20210605T12:14:58Z | DOM fuzzer | https://github.com/mevid93/domzzer | 0 | 0| 
| 20210605T12:14:26Z | Null | https://github.com/Sghosh1999/fuzzy_search | 1 | 0| 
| 20210605T11:58:29Z | Here%s the original code and document for this paper. | https://github.com/aaronfeng369/FengLab_Fuzzy_C-means_method_for_breast_tumor_segmentation | 0 | 0| 
| 20210605T11:50:42Z | The Art of Fuzzing | https://github.com/M0dred/fuzzingPaper | 0 | 0| 
| 20210605T11:47:58Z | Thin interface for libFuzzer, an in-process, coverage-guided, evolutionary fuzzing engine. | https://github.com/planetis-m/libfuzzer | 3 | 0| 
| 20210605T11:23:19Z | Recent Fuzzing Paper | https://github.com/wcventure/FuzzingPaper | 871 | 142| 
| 20210605T10:49:16Z | Hyperbox classifier for pattern recognition | https://github.com/kondal461/Fuzzy-Min-Max-Neural-Networks | 0 | 0| 
| 20210605T10:39:46Z | Null | https://github.com/AdaLogics/go-fuzz-headers | 2 | 1| 
| 20210605T10:18:50Z | 1 | https://github.com/cayomitch79/fuzzy-train | 0 | 0| 



# 日更新程序
