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
| 20210605T12:12:57Z | CVE-2021-31251 | PoC for exploiting CVE-2021-31251 | https://github.com/JamesGeeee/CVE-2021-31251 | An authentication bypass in telnet server in BF-430 and BF431 232/422 TCP/IP Converter, BF-450M and SEMAC from CHIYU Technology Inc allows obtaining a privileged connection with the target device by supplying a specially malformed request and an attacker may force the remote telnet server to believe that the user has already authenticated.| 
| 20210605T12:12:55Z | CVE-2021-31250 | PoC for exploiting CVE-2021-31250 | https://github.com/JamesGeeee/CVE-2021-31250 | Multiple storage XSS vulnerabilities were discovered on BF-430, BF-431 and BF-450M TCP/IP Converter devices from CHIYU Technology Inc due to a lack of sanitization of the input on the components man.cgi, if.cgi, dhcpc.cgi, ppp.cgi.| 
| 20210605T12:12:53Z | CVE-2021-31249 | PoC for exploiting CVE-2021-31249 | https://github.com/JamesGeeee/CVE-2021-31249 | A CRLF injection vulnerability was found on BF-430, BF-431, and BF-450M TCP/IP Converter devices from CHIYU Technology Inc due to a lack of validation on the parameter redirect= available on multiple CGI components.| 
| 20210605T12:12:52Z | CVE-2021-26928 | PoC for exploiting CVE-2021-26928 | https://github.com/JamesGeeee/CVE-2021-26928 |  BIRD through 2.0.7 does not provide functionality for password authentication of BGP peers. Because of this, products that use BIRD (which may, for example, include Tigera products in some configurations, as well as products of other vendors) may have been susceptible to route redirection for Denial of Service and/or Information Disclosure. NOTE: a researcher has asserted that the behavior is within Tigera’s area of responsibility; however, Tigera disagrees.| 
| 20210605T12:12:50Z | CVE-2021-32641 | PoC for exploiting CVE-2021-32641 | https://github.com/JamesGeeee/CVE-2021-32641 | auth0-lock is Auth0%s signin solution. Versions of nauth0-lock before and including `11.30.0` are vulnerable to reflected XSS. An attacker can execute arbitrary code when the library%s `flashMessage` feature is utilized and user input or data from URL parameters is incorporated into the `flashMessage` or the library%s `languageDictionary` feature is utilized and user input or data from URL parameters is incorporated into the `languageDictionary`. The vulnerability is patched in version 11.30.1.| 
| 20210605T12:12:49Z | CVE-2021-32638 | PoC for exploiting CVE-2021-32638 | https://github.com/JamesGeeee/CVE-2021-32638 | Github%s CodeQL action is provided to run CodeQL-based code scanning on non-GitHub CI/CD systems and requires a GitHub access token to connect to a GitHub repository. The runner and its documentation previously suggested passing the GitHub token as a command-line parameter to the process instead of reading it from a file, standard input, or an environment variable. This approach made the token visible to other processes on the same machine, for example in the output of the `ps` command. If the CI system publicly exposes the output of `ps`, for example by logging the output, then the GitHub access token can be exposed beyond the scope intended. Users of the CodeQL runner on 3rd-party systems, who are passing a GitHub token via the `--github-auth` flag, are affected. This applies to both GitHub.com and GitHub Enterprise users. Users of the CodeQL Action on GitHub Actions are not affected. The `--github-auth` flag is now considered insecure and deprecated. The undocumented `--external-repository-token` flag has been removed. To securely provide a GitHub access token to the CodeQL runner, users should **do one of the following instead**: Use the `--github-auth-stdin` flag and pass the token on the command line via standard input OR set the `GITHUB_TOKEN` environment variable to contain the token, then call the command without passing in the token. The old flag remains present for backwards compatibility with existing workflows. If the user tries to specify an access token using the `--github-auth` flag, there is a deprecation warning printed to the terminal that directs the user to one of the above options. All CodeQL runner releases codeql-bundle-20210304 onwards contain the patches. We recommend updating to a recent version of the CodeQL runner, storing a token in your CI system%s secret storage mechanism, and passing the token to the CodeQL runner using `--github-auth-stdin` or the `GITHUB_TOKEN` environment variable. If still using the old flag, ensure that process output, such as from `ps`, is not persisted in CI logs.| 
| 20210605T12:12:01Z | CVE-2020-13956 | PoC for exploiting CVE-2020-13956 | https://github.com/JamesGeeee/CVE-2020-13956 | Apache HttpClient versions prior to version 4.5.13 and 5.0.3 can misinterpret malformed authority component in request URIs passed to the library as java.net.URI object and pick the wrong target host for request execution.| 
| 20210605T12:11:59Z | CVE-2021-22207 | PoC for exploiting CVE-2021-22207 | https://github.com/JamesGeeee/CVE-2021-22207 | | 
| 20210605T12:11:57Z | CVE-2021-25217 | PoC for exploiting CVE-2021-25217 | https://github.com/JamesGeeee/CVE-2021-25217 | In ISC DHCP 4.1-ESV-R1 -> 4.1-ESV-R16, ISC DHCP 4.4.0 -> 4.4.2 (Other branches of ISC DHCP (i.e., releases in the 4.0.x series or lower and releases in the 4.3.x series) are beyond their End-of-Life (EOL) and no longer supported by ISC. From inspection it is clear that the defect is also present in releases from those series, but they have not been officially tested for the vulnerability), The outcome of encountering the defect while reading a lease that will trigger it varies, according to: the component being affected (i.e., dhclient or dhcpd) whether the package was built as a 32-bit or 64-bit binary whether the compiler flag -fstack-protection-strong was used when compiling In dhclient, ISC has not successfully reproduced the error on a 64-bit system. However, on a 32-bit system it is possible to cause dhclient to crash when reading an improper lease, which could cause network connectivity problems for an affected system due to the absence of a running DHCP client process. In dhcpd, when run in DHCPv4 or DHCPv6 mode: if the dhcpd server binary was built for a 32-bit architecture AND the -fstack-protection-strong flag was specified to the compiler, dhcpd may exit while parsing a lease file containing an objectionable lease, resulting in lack of service to clients. Additionally, the offending lease and the lease immediately following it in the lease database may be improperly deleted. if the dhcpd server binary was built for a 64-bit architecture OR if the -fstack-protection-strong compiler flag was NOT specified, the crash will not occur, but it is possible for the offending lease and the lease which immediately followed it to be improperly deleted.| 
| 20210605T12:06:53Z | CVE-2021-21985 | CVE-2021-21985 VMware vCenter Server远程代码执行漏洞 EXP (更新可回显EXP) | https://github.com/r0ckysec/CVE-2021-21985 | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 


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
| 20210605T12:12:57Z | PoC for exploiting CVE-2021-31251 | https://github.com/JamesGeeee/CVE-2021-31251 | 0 | 0| 
| 20210605T12:12:55Z | PoC for exploiting CVE-2021-31250 | https://github.com/JamesGeeee/CVE-2021-31250 | 0 | 0| 
| 20210605T12:12:53Z | PoC for exploiting CVE-2021-31249 | https://github.com/JamesGeeee/CVE-2021-31249 | 0 | 0| 
| 20210605T12:12:52Z | PoC for exploiting CVE-2021-26928 | https://github.com/JamesGeeee/CVE-2021-26928 | 0 | 0| 
| 20210605T12:12:50Z | PoC for exploiting CVE-2021-32641 | https://github.com/JamesGeeee/CVE-2021-32641 | 0 | 0| 
| 20210605T12:12:49Z | PoC for exploiting CVE-2021-32638 | https://github.com/JamesGeeee/CVE-2021-32638 | 0 | 0| 
| 20210605T12:12:01Z | PoC for exploiting CVE-2020-13956 | https://github.com/JamesGeeee/CVE-2020-13956 | 0 | 0| 
| 20210605T12:11:59Z | PoC for exploiting CVE-2021-22207 | https://github.com/JamesGeeee/CVE-2021-22207 | 0 | 0| 
| 20210605T12:11:57Z | PoC for exploiting CVE-2021-25217 | https://github.com/JamesGeeee/CVE-2021-25217 | 0 | 0| 
| 20210605T12:02:48Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 24 | 11| 


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
