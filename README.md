# CVE-2016-0051
Proof-of-concept BSoD (Blue Screen of Death) and Elevation of Privilege (to SYSTEM) code for my CVE-2016-0051 (MS-016).

### EoP to SYSTEM on Windows 7 SP1 x86

![Elevation of Privilege on Windows 7 x86 before the patch](eop_win7x86.gif)

### BSoD on a Windows 10 x64

![Crash on a Windows 10 x64 before the patch](bsod_win10x64.gif)

### Links

* [Microsoft Security Bulletin MS16-016](https://technet.microsoft.com/en-us/library/security/ms16-016.aspx)
* [Microsoft Acknowledgements page](https://technet.microsoft.com/library/security/mt674627.aspx)
* [A variant of this PoC where the shell will be spawn in the same CMD](https://github.com/hexx0r/CVE-2016-0051) by hexx0r

### Timeline

* 2015.09.18. Vulnerability found
* 2015.09.24. Reported to MSRC (Microsoft Security Response Center) with this proof-of-concept code
* 2015.09.25. MSRC filed the report, provided point of contact information and sent the info to their analysts
* 2015.09.30. MSRC reproduced the issue, started to investigate whether they will fix it or not
* 2015.10.16. MSRC confirmed that it is exploitable and that they will fix in an upcoming patch release, asked for acknowledgement information
* 2016.02.09. Vulnerability fixed in the 2016 February Patch Tuesday update
* 2016.02.09. BSoD PoC published here
* 2016.02.11. MSRC confirmed to me that they fixed the vulnerability
* 2016.02.15. EoP published here

### Details

TODO
