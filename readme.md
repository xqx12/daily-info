# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210607 | Kubernetes Goat - Vulnerable by Design Kubernetes Cluster | https://github.com/madhuakula/kubernetes-goat| 
| 20210607 | Tavis 对密码管理器攻击面的分析 | https://lock.cmpxchg8b.com/passmgrs.html| 
| 20210607 | Learning JNDI Injection From CVE-2021-21985 | https://y4y.space/2021/06/04/learning-jndi-injection-from-cve-2021-21985/| 
| 20210607 | Finding SSRF via HTML Injection inside a PDF file on AWS EC2 | https://blog.appsecco.com/finding-ssrf-via-html-injection-inside-a-pdf-file-on-aws-ec2-214cc5ec5d90?gi=5fd60a294535| 
| 20210607 | Hacking 智能电表，作者通过逆向分析数据传输协议，绘制了一张周围所有电表的坐标图 | https://www.youtube.com/watch?v=Y_sh605Q7oA| 
| 20210607 | Apache Airflow 1.10.10. RCE 漏洞分析 | https://infosecwriteups.com/poc-exploit-from-a-cve-apache-airflow-1-10-10-rce-e2c764f2a6f0?gi=ca54d338aeec| 
| 20210607 | 从 navigator 对象、网络延迟、TCP/IP 指纹等角度检测 Brightdata 数据采集器 | https://incolumitas.com/2021/06/05/detecting-brightdata-data-collector-as-bot/| 
| 20210607 | Project Zero 对 Linux 内核处理 VM_IO,VM_PFNMAP vmas 不当导致漏洞（CVE-2021-22543）的分析 | https://github.com/google/security-research/security/advisories/GHSA-7wq5-phmq-m584| 
| 20210607 | Zon8 分享了他们收集的 V8 漏洞的 PoC | https://github.com/zon8research/v8-vulnerabilities| 
| 20210607 | 通过对Docker 镜像逆向工程。 | https://theartofmachinery.com/2021/03/18/reverse_engineering_a_docker_image.html| 
| 20210607 | TeX 安全模式绕过研究 | https://paper.seebug.org/1596/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210607 | InForSec学术交流会 参会小计DAY1 | https://mp.weixin.qq.com/s/oDkL6J4lHSRskvNgD7yj-w| 
| 20210607 | InForSec学术交流会 参会小计DAY1 | /news/29263| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210607T23:46:03Z | CVE-2021-20259 | PoC for exploiting CVE-2021-20259 | https://github.com/JamesGeeee/CVE-2021-20259 | A flaw was found in the Foreman project. The Proxmox compute resource exposes the password through the API to an authenticated local attacker with view_hosts permission. The highest threat from this vulnerability is to data confidentiality and integrity as well as system availability. Versions before foreman_fog_proxmox 0.13.1 are affected| 
| 20210607T23:45:57Z | CVE-2020-25716 | PoC for exploiting CVE-2020-25716 | https://github.com/JamesGeeee/CVE-2020-25716 | A flaw was found in Cloudforms. A role-based privileges escalation flaw where export or import of administrator files is possible. An attacker with a specific group can perform actions restricted only to system administrator. This is the affect of an incomplete fix for CVE-2020-10783. The highest threat from this vulnerability is to data confidentiality and integrity. Versions before cfme 5.11.10.1 are affected| 
| 20210607T23:45:52Z | CVE-2020-1750 | PoC for exploiting CVE-2020-1750 | https://github.com/JamesGeeee/CVE-2020-1750 | A flaw was found in the machine-config-operator that causes an OpenShift node to become unresponsive when a container consumes a large amount of memory. An attacker could use this flaw to deny access to schedule new pods in the OpenShift cluster. This was fixed in openshift/machine-config-operator 4.4.3, openshift/machine-config-operator 4.3.25, openshift/machine-config-operator 4.2.36.| 
| 20210607T23:08:30Z | CVE-2020-4732 | PoC for exploiting CVE-2020-4732 | https://github.com/JamesGeeee/CVE-2020-4732 | | 
| 20210607T18:43:43Z | CVE-2021-22911 | Pre-Auth Blind NoSQL Injection leading to Remote Code Execution in Rocket Chat 3.12.1 | https://github.com/CsEnox/CVE-2021-22911 | A improper input sanitization vulnerability exists in Rocket.Chat server 3.11, 3.12 & 3.13 that could lead to unauthenticated NoSQL injection, resulting potentially in RCE.| 
| 20210607T15:32:59Z | CVE-2020-0041 | My implementation for an exploit of the CVE-2020-0041 bug | https://github.com/Byte-Master-101/CVE_2020_0041 | In binder_transaction of binder.c, there is a possible out of bounds write due to an incorrect bounds check. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android kernelAndroid ID: A-145988638References: Upstream kernel| 
| 20210607T13:46:24Z | CVE-2021-27965 | stack based buffer overflow in MsIo64.sys, Proof of Concept Local Privilege Escalation to nt authority/system | https://github.com/mathisvickie/CVE-2021-27965 | The MsIo64.sys driver before 1.1.19.1016 in MSI Dragon Center before 2.0.98.0 has a buffer overflow that allows privilege escalation via a crafted 0x80102040, 0x80102044, 0x80102050, or 0x80102054 IOCTL request.| 
| 20210607T09:47:13Z | CVE-2021-3572 | A simple repository helping to test CVE-2021-3572 in PyPA/pip | https://github.com/frenzymadness/CVE-2021-3572 | | 
| 20210607T07:48:02Z | cve-2021-33879 | GameLoop update MITM | https://github.com/mmiszczyk/cve-2021-33879 | Tencent GameLoop before 4.1.21.90 downloaded updates over an insecure HTTP connection. A malicious attacker in an MITM position could spoof the contents of an XML document describing an update package, replacing a download URL with one pointing to an arbitrary Windows executable. Because the only integrity check would be a comparison of the downloaded file%s MD5 checksum to the one contained within the XML document, the downloaded executable would then be executed on the victim%s machine.| 
| 20210607T07:13:54Z | CVE-2020-27688 | CVE-2020-27688 | https://github.com/matthiasmaes/CVE-2020-27688 | RVToolsPasswordEncryption.exe in RVTools 4.0.6 allows users to encrypt passwords to be used in the configuration files. This encryption used a static IV and key, and thus using the Decrypt() method from VISKD.cs from the RVTools.exe executable allows for decrypting the encrypted passwords. The accounts used in the configuration files have access to vSphere instances.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210607T22:52:38Z | Git Blog | https://github.com/klee30810/klee30810.github.io | 0 | 0| 
| 20210607T20:55:16Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 17 | 0| 
| 20210607T13:47:15Z | A library for concolic execution of RV32 instruction set simulators | https://github.com/agra-uni-bremen/clover | 1 | 0| 
| 20210607T08:23:58Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 652 | 15| 
| 20210607T04:48:04Z | Dodoco doko? | https://github.com/RiceFT/klee | 0 | 0| 
| 20210607T00:38:06Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 144 | 14| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210607T23:46:03Z | PoC for exploiting CVE-2021-20259 | https://github.com/JamesGeeee/CVE-2021-20259 | 0 | 0| 
| 20210607T23:45:57Z | PoC for exploiting CVE-2020-25716 | https://github.com/JamesGeeee/CVE-2020-25716 | 0 | 0| 
| 20210607T23:45:52Z | PoC for exploiting CVE-2020-1750 | https://github.com/JamesGeeee/CVE-2020-1750 | 0 | 0| 
| 20210607T23:16:30Z | labsecurity is a framework and its use is for ethical hacking and computer security | https://github.com/dylan14567/labsecurity | 1 | 3| 
| 20210607T23:08:30Z | PoC for exploiting CVE-2020-4732 | https://github.com/JamesGeeee/CVE-2020-4732 | 0 | 0| 
| 20210607T22:52:23Z | Ryan Johnson and His Exploits | https://github.com/ryancj14/LinkToTheNow | 0 | 0| 
| 20210607T22:45:44Z | Desktop application mixed with database allowing to allocate patients in a clinic rooms with the goal of avoiding health-based conficts between them and exploiting user authorization to granting access and organise the clinic. Project being meant as a base for mine and my team%s future Engineer%s Thesis. | https://github.com/Too55/pz_project | 1 | 1| 
| 20210607T22:03:02Z | Dont touch | https://github.com/MaSKaThGod/Anime-Exploit | 0 | 0| 
| 20210607T21:35:17Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9542 | 1549| 
| 20210607T21:01:48Z | Null | https://github.com/WackyHacker/ExploitLFI | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210607T23:27:38Z | A workflow to create/manage a backdoor admin account and rotate the password. E.g. Another LAPS workflow. | https://github.com/Rocketman-Tech/BreakGlassAdmin | 0 | 0| 
| 20210607T21:33:49Z | Python AV Evasion Tools | https://github.com/G1ft3dC0d3/MsfMania | 141 | 30| 
| 20210607T16:06:55Z | Demo page for the backdoorthen package | https://github.com/johanfive/backdoordemo | 0 | 0| 
| 20210607T14:51:49Z | Null | https://github.com/N0Clew/Backdoor-Router | 0 | 0| 
| 20210607T12:58:31Z | OWASP ZAP add-on containing the web-backdoors and attack files from FuzzDB | https://github.com/zaproxy/fuzzdb-offensive | 6 | 6| 
| 20210607T11:48:15Z | Windows 10 PRO Activator - No more backdoors via loaders from China and neither you will need any crack anymore that is valid for a week or two. This is script is written for powershell/cmd. This script will also removing all bloatware from Windows 10. Edit the script after your needs. | https://github.com/wuseman/wLoader | 64 | 16| 
| 20210607T11:43:21Z | PHP 8.1.0-dev Backdoor System Shell Script | https://github.com/flast101/php-8.1.0-dev-backdoor-rce | 8 | 2| 
| 20210607T10:08:43Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 248 | 43| 
| 20210607T09:32:32Z | An exploit for %zerodium% backdoor in PHP 8.1.0-dev via User-Agent | https://github.com/fahmifj/php-8.1.0-dev-zerodium-rce | 0 | 0| 
| 20210607T06:28:18Z | Undetectable & Xor encrypting with custom KEY (FUD Metasploit Rat) bypass Top Antivirus like BitDefender,Malwarebytes,Avast,ESET-NOD32,AVG,... & Automatically Add ICON and MANIFEST to excitable | https://github.com/persianhydra/Xeexe-TopAntivirusEvasion | 466 | 106| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210607T23:49:33Z | SecLists is the security tester%s companion. It%s a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. | https://github.com/danielmiessler/SecLists | 31884 | 16435| 
| 20210607T23:37:52Z | Input Police (Codename: The Fuzz (or Fuzz police)) is an open source fuzzing software with privacy in mind that also shows alternative fuzzing software solutions. | https://github.com/seanpm2001/Input-police | 1 | 1| 
| 20210607T23:16:12Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210607T23:14:54Z | Fuzz pidgin dbus by using AFL++ and clang%s ASAN | https://github.com/wh1t3h47/afl_pidgin | 0 | 0| 
| 20210607T22:48:02Z | Null | https://github.com/opimentel-github/fuzzy-torch | 1 | 0| 
| 20210607T22:42:17Z | Null | https://github.com/Blackbackofficial/neuro-fuzzy-systems | 0 | 0| 
| 20210607T21:23:03Z | Simple CI program for running fuzzing over TezEdge. | https://github.com/tezedge/fuzzing-ci | 5 | 0| 
| 20210607T21:05:05Z | Binary Ninja helper plugin for fuzzable target discovery | https://github.com/ex0dus-0x/fuzzable | 0 | 0| 
| 20210607T21:04:20Z | Personal website of Laurence Hughes | https://github.com/fuzzylogicxx/fuzzylogic | 4 | 1| 
| 20210607T20:53:37Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2341 | 128| 



# 日更新程序
