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
| 20210605T12:12:01Z | CVE-2020-13956 | PoC for exploiting CVE-2020-13956 | https://github.com/JamesGeeee/CVE-2020-13956 | Apache HttpClient versions prior to version 4.5.13 and 5.0.3 can misinterpret malformed authority component in request URIs passed to the library as java.net.URI object and pick the wrong target host for request execution.| 
| 20210605T12:11:59Z | CVE-2021-22207 | PoC for exploiting CVE-2021-22207 | https://github.com/JamesGeeee/CVE-2021-22207 | Excessive memory consumption in MS-WSP dissector in Wireshark 3.4.0 to 3.4.4 and 3.2.0 to 3.2.12 allows denial of service via packet injection or crafted capture file| 
| 20210605T12:11:57Z | CVE-2021-25217 | PoC for exploiting CVE-2021-25217 | https://github.com/JamesGeeee/CVE-2021-25217 | In ISC DHCP 4.1-ESV-R1 -> 4.1-ESV-R16, ISC DHCP 4.4.0 -> 4.4.2 (Other branches of ISC DHCP (i.e., releases in the 4.0.x series or lower and releases in the 4.3.x series) are beyond their End-of-Life (EOL) and no longer supported by ISC. From inspection it is clear that the defect is also present in releases from those series, but they have not been officially tested for the vulnerability), The outcome of encountering the defect while reading a lease that will trigger it varies, according to: the component being affected (i.e., dhclient or dhcpd) whether the package was built as a 32-bit or 64-bit binary whether the compiler flag -fstack-protection-strong was used when compiling In dhclient, ISC has not successfully reproduced the error on a 64-bit system. However, on a 32-bit system it is possible to cause dhclient to crash when reading an improper lease, which could cause network connectivity problems for an affected system due to the absence of a running DHCP client process. In dhcpd, when run in DHCPv4 or DHCPv6 mode: if the dhcpd server binary was built for a 32-bit architecture AND the -fstack-protection-strong flag was specified to the compiler, dhcpd may exit while parsing a lease file containing an objectionable lease, resulting in lack of service to clients. Additionally, the offending lease and the lease immediately following it in the lease database may be improperly deleted. if the dhcpd server binary was built for a 64-bit architecture OR if the -fstack-protection-strong compiler flag was NOT specified, the crash will not occur, but it is possible for the offending lease and the lease which immediately followed it to be improperly deleted.| 
| 20210605T12:06:53Z | CVE-2021-21985 | CVE-2021-21985 VMware vCenter Server远程代码执行漏洞 EXP (更新可回显EXP) | https://github.com/r0ckysec/CVE-2021-21985 | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210605T11:49:07Z | CVE-2021-21985 | Null | https://github.com/testanull/Project_CVE-2021-21985_PoC | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210605T10:24:27Z | cve-2021-21985 | cve-2021-21985 exploit | https://github.com/xnianq/cve-2021-21985_exp | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210605T10:13:50Z | CVE-2021-21985 | Null | https://github.com/alt3kx/CVE-2021-21985_PoC | | 
| 20210605T10:13:00Z | CVE-2021-27965 | stack based buffer overflow in MsIo64.sys, Proof of Concept Local Privilege Escalation to nt authority/system | https://github.com/mathisvickie/CVE-2021-27965 | The MsIo64.sys driver before 1.1.19.1016 in MSI Dragon Center before 2.0.98.0 has a buffer overflow that allows privilege escalation via a crafted 0x80102040, 0x80102044, 0x80102050, or 0x80102054 IOCTL request.| 


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
| 20210605T12:12:49Z | PoC for exploiting CVE-2021-32638 | https://github.com/JamesGeeee/CVE-2021-32638 | 0 | 0| 
| 20210605T12:12:01Z | PoC for exploiting CVE-2020-13956 | https://github.com/JamesGeeee/CVE-2020-13956 | 0 | 0| 
| 20210605T12:11:59Z | PoC for exploiting CVE-2021-22207 | https://github.com/JamesGeeee/CVE-2021-22207 | 0 | 0| 
| 20210605T12:11:57Z | PoC for exploiting CVE-2021-25217 | https://github.com/JamesGeeee/CVE-2021-25217 | 0 | 0| 
| 20210605T12:02:48Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 24 | 11| 
| 20210605T11:59:51Z | Null | https://github.com/defiexploit/exploit | 0 | 0| 
| 20210605T11:52:49Z | Remote Code Execution EJS Web Applications using express-fileupload | https://github.com/boiledsteak/EJS-Exploit | 0 | 0| 
| 20210605T11:40:11Z | The AWS exploitation framework, designed for testing the security of Amazon Web Services environments. | https://github.com/RhinoSecurityLabs/pacu | 2101 | 377| 
| 20210605T11:34:40Z | Null | https://github.com/WackyHacker/ExploitLFI | 0 | 0| 
| 20210605T10:55:57Z | Null | https://github.com/th3ken-dev/TH3KEN-EDITON | 2 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210605T03:57:46Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 243 | 43| 
| 20210605T00:08:52Z | A simple and easy to use stresser for your ddos (booting) business services. | https://github.com/lolCourtesy/True-Security-Services-io-Shells-Backdoors-Removed | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210605T01:47:38Z | Basic fuzzing input mutator. | https://github.com/00xc/cmutator | 1 | 0| 
| 20210605T01:43:56Z | Null | https://github.com/my000own000files1/Fuzzy | 0 | 0| 
| 20210605T00:53:11Z | 99minutos coverage maps | https://github.com/99minutos/fuzzy-journey | 0 | 0| 



# 日更新程序
