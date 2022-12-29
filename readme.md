# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221229 | Rust 语言逆向工程学习笔记 | https://brightprogrammer.netlify.app/post/reverse-engineering-rustlang-binaries-0x1-empty-program/| 
| 20221229 | 总结了开发 Linux 内核漏洞利用时可能用到的结构体 | http://blog.csdn.net/panhewu9919/article/details/118112795| 
| 20221229 | Nunchucks HackTheBox Writeup | http://www.hackingarticles.in/nunchucks-hackthebox-walkthrough/| 
| 20221229 | 通过对华为手机EL2级别的安全保护程序HHEE的逆向分析，分析其对内核提取的多种通用保护机制。 | http://blog.impalabs.com/2212_huawei-security-hypervisor.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20221229 | [HTB] Jarvis Writeup | https://mp.weixin.qq.com/s/7eEGFMrYwfjK8ElNjvg6Lg| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20221229T13:58:17Z | CVE-2021-4206 | A flaw was found in the QXL display device emulation in QEMU. An integer overflow in the cursor_alloc() function can lead to the allocation of a small cursor object followed by a subsequent heap-based buffer overflow. This flaw allows a malicious privileged guest user to crash the QEMU process on the host or potentiall CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-4206 | | 
| 20221229T13:58:14Z | CVE-2022-38668 | HTTP applications (servers) based on Crow through 1.0+4 may reveal potentially sensitive uninitialized data from stack memory when fulfilling a request for a static file smaller than 16 KB. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-38668 | | 
| 20221229T13:58:00Z | CVE-2022-20824 | A vulnerability in the Cisco Discovery Protocol feature of Cisco FXOS Software and Cisco NX-OS Software could allow an unauthenticated, adjacent attacker to execute arbitrary code with root privileges or cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper input validat CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-20824 | | 
| 20221229T13:57:53Z | CVE-2022-27777 | A XSS Vulnerability in Action View tag helpers >= 5.2.0 and < 5.2.0 which would allow an attacker to inject content if able to control input into specific attributes. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-27777 | | 
| 20221229T13:57:49Z | CVE-2022-34266 | The libtiff-4.0.3-35.amzn2.0.1 package for LibTIFF on Amazon Linux 2 allows attackers to cause a denial of service (application crash), a different vulnerability than CVE-2022-0562. When processing a malicious TIFF file, an invalid range may be passed as an argument to the memset() function within TIFFFetchStripThing() CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-34266 | | 
| 20221229T13:57:45Z | CVE-2021-20257 | An infinite loop flaw was found in the e1000 NIC emulator of the QEMU. This issue occurs while processing transmits (tx) descriptors in process_tx_desc if various descriptor fields are initialized with invalid values. This flaw allows a guest to consume CPU cycles on the host, resulting in a denial of service. The high CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-20257 | | 
| 20221229T13:57:26Z | CVE-2020-25624 | hw/usb/hcd-ohci.c in QEMU 5.0.0 has a stack-based buffer over-read via values obtained from the host controller driver. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-25624 | | 
| 20221229T13:57:07Z | CVE-2020-25625 | hw/usb/hcd-ohci.c in QEMU 5.0.0 has an infinite loop when a TD list has a loop. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-25625 | | 
| 20221229T13:57:03Z | CVE-2020-25084 | QEMU 5.0.0 has a use-after-free in hw/usb/hcd-xhci.c because the usb_packet_map return value is not checked. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-25084 | | 
| 20221229T13:56:59Z | CVE-2020-27617 | eth_get_gso_type in net/eth.c in QEMU 4.2.1 allows guest OS users to trigger an assertion failure. A guest can crash the QEMU process via packet data that lacks a valid Layer 3 protocol. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-27617 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221229T13:56:38Z | TP-Link Tapo C200 IP camera, on its 1.1.15 firmware version and below, is affected by an unauthenticated RCE vulnerability, present in the uhttpd binary running by default as root. The exploitation of this vulnerability allows an attacker to take full control of the camera. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2021-4045 | 0 | 0| 
| 20221229T13:39:03Z | A post-exploitation toolkit to simulate the weaponization and detection of native Windows binaries based on LOLBas framework.  | https://github.com/WesleyWong420/Build-Your-Own-LOLBins | 0 | 0| 
| 20221229T13:18:30Z | An attacker can exploit this vulnerability to elevate privileges from ring 0 to ring -2, execute arbitrary code in System Management Mode - an environment more privileged than operating system (OS) and completely isolated from it. Running arbitrary code in SMM additionally bypasses SMM-based SPI flash protections again CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-40250 | 0 | 0| 
| 20221229T13:18:19Z | Vulnerability in the Java SE, Java SE Embedded product of Oracle Java SE (component: Security). Supported versions that are affected are Java SE: 7u251, 8u241, 11.0.6 and 14; Java SE Embedded: 8u241. Difficult to exploit vulnerability allows unauthenticated attacker with network access via multiple protocols to comprom CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-2773 | 0 | 0| 
| 20221229T13:18:02Z | Vulnerability in the Java SE, Java SE Embedded product of Oracle Java SE (component: JSSE). Supported versions that are affected are Java SE: 7u251, 8u241, 11.0.6 and 14; Java SE Embedded: 8u241. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTPS to compromise Java SE, Java S CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-2781 | 0 | 0| 
| 20221229T13:16:21Z | An attacker can exploit this vulnerability to elevate privileges from ring 0 to ring -2, execute arbitrary code in System Management Mode - an environment more privileged than operating system (OS) and completely isolated from it. Running arbitrary code in SMM additionally bypasses SMM-based SPI flash protections again CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-40261 | 0 | 0| 
| 20221229T13:16:18Z | A remote file inclusion (RFI) vulnerability in Simple College Website v1.0 allows attackers to execute arbitrary code via a crafted PHP file. This vulnerability is exploitable when the directive allow_url_include is set to On. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-40089 | 0 | 0| 
| 20221229T13:16:14Z | There is a stack buffer overflow vulnerability, which could lead to arbitrary code execution in UEFI DXE driver on some Acer products. An attack could exploit this vulnerability to escalate privilege from ring 3 to ring 0, and hijack control flow during UEFI DXE execution. This affects Altos T110 F3 firmware version <= CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-30426 | 0 | 0| 
| 20221229T13:05:59Z | Vial is a lightweight python framework focused on exploiting Flask applications | https://github.com/CopernicusPY/vial | 1 | 0| 
| 20221229T12:41:51Z | Adobe Experience Manager versions 6.5.13.0 (and earlier) is affected by a reflected Cross-Site Scripting (XSS) vulnerability. If an attacker is able to convince a victim to visit a URL referencing a vulnerable page, malicious JavaScript content may be executed within the context of the victim%s browser. Exploitation of CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-38439 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221229T13:30:01Z | Null | https://github.com/howdout64/backdoor | 0 | 0| 
| 20221229T06:08:38Z | Backdoor Creating | https://github.com/MsecTeam/MsecBackdoor | 0 | 0| 
| 20221229T05:36:12Z | The d8s-yaml package for Python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. The backdoor is the democritus-file-system package. The affected version is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-41380 | 0 | 0| 
| 20221229T05:36:09Z | The d8s-utility package for Python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. The backdoor is the democritus-file-system package. The affected version is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-41381 | 0 | 0| 
| 20221229T05:36:05Z | The d8s-archives package for Python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. The backdoor is the democritus-file-system package. The affected version is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-41383 | 0 | 0| 
| 20221229T05:36:02Z | The d8s-json package for Python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. The backdoor is the democritus-file-system package. The affected version is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-41382 | 0 | 0| 
| 20221229T05:35:58Z | The d8s-html package for Python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. The backdoor is the democritus-urls package. The affected version is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-41385 | 0 | 0| 
| 20221229T05:35:55Z | The d8s-domains package for Python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. The backdoor is the democritus-urls package. The affected version is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-41384 | 0 | 0| 
| 20221229T05:35:48Z | The d8s-utility package for Python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. The backdoor is the democritus-urls package. The affected version is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-41386 | 0 | 0| 
| 20221229T05:01:21Z | The d8s-lists package for Python, as distributed on PyPI, included a potential code-execution backdoor inserted by a third party. The backdoor is the democritus-dicts package. The affected version is 0.1.0. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-42039 | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221229T06:39:58Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 3258 | 459| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221229T09:25:47Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 66 | 15| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20221229T11:27:37Z | Null | https://github.com/lhymmEU/blockchain_fuzzer | 0 | 0| 
| 20221229T09:20:08Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8208 | 1790| 
| 20221229T07:50:26Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 1216 | 158| 
| 20221229T07:40:16Z | Null | https://github.com/fluffos/fluffos-fuzzing-results | 0 | 0| 
| 20221229T07:14:24Z | Null | https://github.com/ahmadkhoirulanam2/Algoritma-Fuzzy-C-means- | 0 | 0| 
| 20221229T07:01:04Z | Null | https://github.com/BlackHat1007/fuzzy-waddle | 0 | 0| 
| 20221229T06:26:57Z | Tugas SPK YGY | https://github.com/AWXND/Logika-Fuzzy | 0 | 0| 
| 20221229T01:51:00Z | Null | https://github.com/snare-dev/fuzzy-octo-invention | 0 | 0| 
| 20221229T01:38:52Z | CBOR codec (RFC 8949) with CBOR tags, Go struct tags (toarray, keyasint, omitempty), float64/32/16, big.Int, and fuzz tested billions of execs.  | https://github.com/fxamacker/cbor | 514 | 47| 



# 日更新程序
