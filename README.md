# OSCP omnibus
a collection of OSCP resources for everyone 📚

## Books
- [Network Security Assessment, 2nd Ed.](http://shop.oreilly.com/product/9780596510305.do)
- [Hacking: The Art of Exploitation, 2nd Ed.](https://nostarch.com/hacking2.htm)

## Other Resources by Topic

### Information Gathering
#### Passive
- [Google Filetype Conversions](http://www.googleguide.com/file_type.html) - a nifty guide to filetype specifications that work in Google dorks

#### Active
- [Hackertarget Nmap Cheat Sheet](https://hackertarget.com/nmap-cheatsheet-a-quick-reference-guide/) - handy guide to Nmap commands
- [smb NSE Library](https://nmap.org/nsedoc/lib/smb.html#script-args) - pretty much all the details you'd ever need to know about interacting with SMB via Nmap Scripting Engine
- [A New Look at Null Sessions and User Enumeration](https://sensepost.com/blog/2018/a-new-look-at-null-sessions-and-user-enumeration/) - if you regularly use enum4linux or rpcclient, then read this! it may save you from false negatives.
- [AutoRecon](https://github.com/Tib3rius/AutoRecon) - a powerful, time-saving network recon tool 


### Vulns
- [IP Traffic Accounting with iptables](https://www.cyberciti.biz/faq/linux-configuring-ip-traffic-accounting/) - all about traffic accounting with iptables

### Buffer Overflows
- [dostackbufferoverflowgood](https://github.com/justinsteven/dostackbufferoverflowgood) - guide and workshop on stack buffer overflows complete with vulnerable executable
- [Vortex's Guide to PWK/OSCP Stack Buffer Overflow Practice](https://www.vortex.id.au/2017/05/pwkoscp-stack-buffer-overflow-practice/) - I think this is where I found out about dostackbufferoverflowgood!

### Exploit Development
- [Mona.py Manual](https://www.corelan.be/index.php/2011/07/14/mona-py-the-manual/) - guide to the mona.py pycommand for Immunity Debugger
- [Corelan Exploit Development Tutorials](https://www.corelan.be/index.php/category/security/exploit-writing-tutorials/page/4/) - starting at the oldest and working toward the newer material, these tutorials begin with stack buffer overflow-based exploits and get progressively more complex
- [0x7 Exploit Tutorial: Bad Character Analysis](http://www.primalsecurity.net/0x7-exploit-tutorial-bad-character-analysis/) - A brief tutorial on bad character analysis for shellcode development

### Working with Exploits
I've been spending a lot of time reading up on pointers in C for this section.
- [The Basics and Pitfalls of Pointers in C](https://hackaday.com/2018/04/04/the-basics-and-pitfalls-of-pointers-in-c/)
- [When 4 + 1 Equals 8: An Advanced Take on Pointers in C](https://hackaday.com/2018/04/19/when-4-1-equals-8-an-advanced-take-on-pointers-in-c/)
- [C Pointer Arithmetic](https://www.tutorialspoint.com/cprogramming/c_pointer_arithmetic.htm)
- [Learn about pointers in C](https://www.scaler.com/topics/c/pointers-in-c/)

### Post-Exploitation
#### Upgrading Shells & Transferring Files
- [Transferring Files from Kali to Windows](https://blog.ropnop.com/transferring-files-from-kali-to-windows/) - I like the Python webserver one-liner
- [Upgrading Simple Shells to Fully Interactive TTYs](https://blog.ropnop.com/upgrading-simple-shells-to-fully-interactive-ttys/)
- [Spawning a TTY Shell](https://netsec.ws/?p=337)
- [Flying a Cylon Raider](https://blog.cobaltstrike.com/2015/11/18/flying-a-cylon-raider/) - video on post-exploitation without Meterpreter
- [PowerShell Download Cradles](https://gist.github.com/HarmJ0y/bb48307ffa663256e239)
- [LOLBAS](https://lolbas-project.github.io/) - binaries, scripts, and libraries for living off the land in Windows

#### SQL
- [Accessing and Hacking MSSQL from Backtrack Linux](https://www.adampalmer.me/iodigitalsec/2013/08/10/accessing-and-hacking-mssql-from-backtrack-linux/) - Good info about sqsh and xp_cmdshell
- [SQL Cheat Sheet](http://www.sqltutorial.org/sql-cheat-sheet/)

### Privilege Escalation
#### Windows
- [PayloadsAllTheThings - Windows Privilege Escalation](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Windows%20-%20Privilege%20Escalation.md) - explanations and tools for lots of privesc methods
- [Windows Privilege Escalation Techniques and Scripts](https://github.com/frizb/Windows-Privilege-Escalation) - detailed writeup of privesc methods
- [Windows Privilege Escalation - An Approach for Penetration Testers](https://sec-consult.com/en/blog/2019/04/windows-privilege-escalation-an-approach-for-penetration-testers/)
- [icacls](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/icacls#remarks) - lists all the possible permissions you might see when running icacls against a file
- [Windows Privilege Escalation Techniques (local) - Tradecraft Security Weekly #02](https://youtu.be/DlJyKgfkoKQ) - video on Windows privesc techniques
- [Windows Privilege Escalation for OSCP & Beyond!](https://www.udemy.com/course/windows-privilege-escalation/) -  Udemy course by [Tib3rius](https://twitter.com/TibSec)

##### Scripts/Executables
- [PowerUp.ps1](https://github.com/PowerShellMafia/PowerSploit/blob/master/Privesc/PowerUp.ps1) - privesc script from the PowerSploit project
- [Windows Privesc Check](https://github.com/pentestmonkey/windows-privesc-check) - EXE that checks for common privesc opportunities
- [SessionGopher](https://github.com/Arvanaghi/SessionGopher) - script for digging up stored session information
- [Powerless](https://github.com/M4ximuss/Powerless) - script for privesc in environments that lack PowerShell

#### Linux
- [PayloadsAllTheThings - Linux Privilege Escalation](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Linux%20-%20Privilege%20Escalation.md) - explanations and tools for lots of privesc methods
- [LinEnum.sh](https://github.com/rebootuser/LinEnum) - privesc shell script
- [GTFOBins](https://gtfobins.github.io/) - Unix binaries that can be used to bypass security restrictions and sometimes escalate privileges
- [Linux Privilege Escalation - Tradecraft Security Weekly #22](https://www.youtube.com/watch?v=oYHAi0cgur4) - video on Linux privesc techniques
- [Linux Privilege Escalation for OSCP & Beyond!](https://www.udemy.com/share/101YYoA0QdcVZVQHQ=/) - Udemy course by [Tib3rius](https://twitter.com/TibSec)

### Web Application Attacks
- [XSS Filter Evasion Cheat Sheet - OWASP](https://www.owasp.org/index.php/XSS_Filter_Evasion_Cheat_Sheet) - XSS filter evasion techniques
- [WordPress Vulnerability Discovery and Exploitation - Tradecraft Security Weekly #6](https://www.youtube.com/watch?v=yUIml8H1flI) - video on WordPress vulnerabilities (it's usually the plugins)
- [Basic and Advanced SQL Injection Techniques](https://youtu.be/clU9ce3erVs) - video with good explanations of various types of SQL injection vulnerabilities and exploitation techniques
### Tunneling and Port Redirection
- [Dynamic Port Forwarding (SSH)](https://netsec.ws/?p=278) - brief walkthrough of dynamic SSH port forwarding with proxychains
- [Evading Filters with Traffic Tunnels](https://implicitdeny.org/2016/08/evading-filters-traffic-tunnels/)
- [How to tunnel SSH over SSL/TLS](https://gist.github.com/bwann/82ed679e94972666808d97587d276677)  - quick guide to client and server setup of stunnel
- [Using Stunnel](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/security_guide/sec-using_stunnel) - red hat stunnel docs

### Metasploit
- [Metasploit Cheat Sheet](https://www.sans.org/security-resources/sec560/misc_tools_sheet_v1.pdf)
- [Shikata Ga Nai Encoder Still Going Strong](https://www.fireeye.com/blog/threat-research/2019/10/shikata-ga-nai-encoder-still-going-strong.html) - a good post from FireEye on Shikata Ga Nai
- [Porting Exploits - Metasploit Unleashed](https://www.offensive-security.com/metasploit-unleashed/porting-exploits/)

---
### Other Random Stuff
- [Mimikatz Cheat Sheet](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Windows%20-%20Mimikatz.md)
- [basic terminator config](https://github.com/alexiasa/oscp-omnibus/blob/master/terminator_config) - multi-tab, multi-pane terminator config with installation instructions [here](https://github.com/alexiasa/oscp-omnibus/blob/master/terminator_config.md)
