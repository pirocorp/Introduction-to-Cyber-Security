# Introduction to Cyber Security

"Introduction to Cyber Security" базови познания в сферата на киберсигурността. 

---------------------------------------------------------------

## Frameworks for Recording Threat Actions

- [ATT&CK Matrix for Enterprise](https://attack.mitre.org/)

---------------------------------------------------------------

## IDS / IPS (Intrusion Detection System / Intrusion Prevention System)

- [Snort](https://www.snort.org/) - Snort is an Open Source Intrusion Prevention System (IPS). Snort IPS uses a series of rules that help define malicious network activity, which is used to find packets that match against them and generate alerts for users. Snort can be deployed to stop these packets, as well. Snort has three primary uses: As a packet sniffer like tcpdump and as a packet logger, which is helpful for network traffic debugging and can be used as a full-blown network intrusion prevention system.
- [Live Cyber Threat Map](https://threatmap.checkpoint.com/) - a real-time map of the computer security attacks occurring at any given time.

---------------------------------------------------------------

## Vulnerabilities `CVE-YEAR OF DISCOVERY-ID`

- [CVE Org](https://www.cve.org/) - Identify, define, and catalog publicly disclosed cybersecurity vulnerabilities
- [ExploitDB](https://www.exploit-db.com/) - Search for Vulnerabilities
- [National Vulnerability Database](https://nvd.nist.gov/) - U.S. government repository of standards-based vulnerability management data represented using the Security Content Automation Protocol (SCAP). This data enables automation of vulnerability management, security measurement, and compliance. The NVD includes databases of security checklist references, security-related software flaws, product names, and impact metrics.
- [CVE Details](https://www.cvedetails.com/) - a complete CVE database enhanced with additional information, including advisories, exploits, tools, source code changes, etc.
- Searchsploit - kali-linux command util

---------------------------------------------------------------

## Hacking Tools 

- [Hydra](https://github.com/vanhauser-thc/thc-hydra) - Brute-Force a Password
- [Responder](https://github.com/SpiderLabs/Responder) - Responder is an open-source tool primarily used for NetBIOS and LLMNR poisoning attacks. NetBIOS (Network Basic Input/Output System) and LLMNR (Link-Local Multicast Name Resolution) facilitate communication between devices on a local network.
- [John the Ripper](https://github.com/openwall/john) - John the Ripper is a fast password cracker, currently available for many flavors of Unix, macOS, Windows, DOS, BeOS, and OpenVMS (the latter requires a contributed patch). Its primary purpose is to detect weak Unix passwords. Besides several crypt(3) password hash types most commonly found on various Unix flavors, supported out of the box are Kerberos/AFS and Windows LM hashes, as well as DES-based tripcodes, plus hundreds of additional hashes and ciphers in "-jumbo" versions.
- [Zero Days Marketplace](https://0day.today/) - Zero Day Vulnerabilities. Zero Day means that they are brand new, and there
is not a fix or patch for them.
- [The Social-Engineer Toolkit (SET)](https://github.com/trustedsec/social-engineer-toolkit) - The Social-Engineer Toolkit is an open-source penetration testing framework designed for social engineering. SET has a number of custom attack vectors that allow you to make a believable attack quickly. SET is a product of TrustedSec, LLC – an information security consulting firm located in Cleveland, Ohio.

---------------------------------------------------------------

## Frameworks to Perform Wi-Fi Attacks

- [Airgeddon](https://github.com/v1s1t0r1sh3r3/airgeddon) - This is a multi-use bash script for Linux systems to audit wireless networks.
- [WiFiPhisher](https://github.com/wifiphisher/wifiphisher) - Wifiphisher is a rogue Access Point framework for conducting red team engagements or Wi-Fi security testing. Using Wifiphisher, penetration testers can quickly achieve a man-in-the-middle position against wireless clients by performing targeted Wi-Fi association attacks.
- [WiFi Exploitation Framework](https://github.com/D3Ext/WEF) - This is an entirely offensive framework to audit wifi networks with different types of attacks for WPA/WPA2, WPS, and WEP, automated handshake cracking, and much more.

---------------------------------------------------------------

## Security Tools

- [OpenVPN](https://openvpn.net/) Virtual Private Network - Infrastructure that allows machines to connect to each other in
a secure way
- [Tor Network](https://www.torproject.org/) This network is used for anonymity online
- [JWT Token](https://jwt.io/) JSON Web Token - Used for authorization in web apps. It relies on a secret to validate its signature. JWT token is instantiated upon a valid login
- [Hashes](https://hashcat.net/wiki/doku.php?id=example_hashes) - Applied algorithm to "obfuscate" a secret

---------------------------------------------------------------

## Example of interesting ports:

- 22 / SSH
- 80 / HTTP
- 443 / HTTPS
- 389 / LDAP

---------------------------------------------------------------

## Example of exciting commands:

- How to Check What Ports are Opened on Your PC
  - Windows:
    - `netstat –an`
    - `netstat –antb`
  - Linux:
    - `ss –nltp`
    - `netstat –tulpn`


