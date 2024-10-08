# Introduction-to-Cyber-Security

"Introduction to Cyber Security" базови познания в сферата на киберсигурността. 

---------------------------------------------------------------

## Frameworks for Recording Threat Actions

- [ATT&CK Matrix for Enterprise](https://attack.mitre.org/)

---------------------------------------------------------------

## IDS / IPS (Intrusion Detection System / Intrusion Prevention System)

- [Snort](https://www.snort.org/)

---------------------------------------------------------------

## Vulnerabilities `CVE-YEAR OF DISCOVERY-ID`

- [ExploitDB](https://www.exploit-db.com/) - Search for Vulnerabilities
- Searchsploit - kali-linux command util

---------------------------------------------------------------

## Hacking Tools 

- [Hydra](https://github.com/vanhauser-thc/thc-hydra) - Brute-Force a Password
- [Responder](https://github.com/SpiderLabs/Responder) - Responder is an open-source tool primarily used for NetBIOS and LLMNR poisoning attacks. NetBIOS (Network Basic Input/Output System) and LLMNR (Link-Local Multicast Name Resolution) facilitate communication between devices on a local network.
- [John the Ripper](https://github.com/openwall/john) - John the Ripper is a fast password cracker, currently available for many flavors of Unix, macOS, Windows, DOS, BeOS, and OpenVMS (the latter requires a contributed patch). Its primary purpose is to detect weak Unix passwords. Besides several crypt(3) password hash types most commonly found on various Unix flavors, supported out of the box are Kerberos/AFS and Windows LM hashes, as well as DES-based tripcodes, plus hundreds of additional hashes and ciphers in "-jumbo" versions.
- [Zero Days Marketplace](https://0day.today/) - Zero Day Vulnerabilities. Zero Day means that they are brand new, and there
is not a fix or patch for them

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


