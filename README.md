
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

### Post-Exploitation
- [Transferring Files from Kali to Windows](https://blog.ropnop.com/transferring-files-from-kali-to-windows/) - I like the Python webserver one-liner
- [Upgrading Simple Shells to Fully Interactive TTYs](https://blog.ropnop.com/upgrading-simple-shells-to-fully-interactive-ttys/)

### Privilege Escalation
- [Accessing and Hacking MSSQL from Backtrack Linux](https://www.adampalmer.me/iodigitalsec/2013/08/10/accessing-and-hacking-mssql-from-backtrack-linux/) - Good info about sqsh and xp_cmdshell
- [SQL Cheat Sheet](http://www.sqltutorial.org/sql-cheat-sheet/)

### Client Side Attacks
- [icacls](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/icacls#remarks) - lists all the possible permissions you might see when running icacls against a file
