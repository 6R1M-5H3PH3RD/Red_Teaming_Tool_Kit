# Red_Teaming_Tool_Kit

## Contents
1. [Reconnaissance](https://github.com/MagicBox77/Red_Teaming_Tool_Kit/new/main?readme=1#reconnaissance)
2. [Weaponization](https://github.com/MagicBox77/Red_Teaming_Tool_Kit/new/main?readme=1#weaponization)
3. [Delivery](https://github.com/MagicBox77/Red_Teaming_Tool_Kit/new/main?readme=1#delivery)
4. [Command and Control](https://github.com/MagicBox77/Red_Teaming_Tool_Kit/new/main?readme=1#command-and-control)
5. [Lateral Movement](https://github.com/MagicBox77/Red_Teaming_Tool_Kit/new/main?readme=1#lateral-movement)
6. [Establish Foothold](https://github.com/MagicBox77/Red_Teaming_Tool_Kit/new/main?readme=1#establish-foothold)
7. [Escalate Privileges](https://github.com/MagicBox77/Red_Teaming_Tool_Kit/new/main?readme=1#escalate-privileges)
8. [Data Exfiltration](https://github.com/MagicBox77/Red_Teaming_Tool_Kit/new/main?readme=1#data-exfiltration)
9. [Misc](https://github.com/MagicBox77/Red_Teaming_Tool_Kit/new/main?readme=1#misc)
10. [References](https://github.com/MagicBox77/Red_Teaming_Tool_Kit/new/main?readme=1#references)

# **Reconnaissance**

## Active Intelligence Gathering
### 1. EyeWitness is designed to take screenshots of websites, provide some server header info, and identify default credentials if possible. https://github.com/ChrisTruncer/EyeWitness
### 2. AWSBucketDump is a tool to quickly enumerate AWS S3 buckets to look for loot. https://github.com/jordanpotti/AWSBucketDump
### 3. AQUATONE is a set of tools for performing reconnaissance on domain names. https://github.com/michenriksen/aquatone
### 4. spoofcheck a program that checks if a domain can be spoofed from. The program checks SPF and DMARC records for weak configurations that allow spoofing. https://github.com/BishopFox/spoofcheck
### 6. Nmap is used to discover hosts and services on a computer network, thus building a “map” of the network. https://github.com/nmap/nmap
### 7. dnsrecon a tool DNS Enumeration Script. https://github.com/darkoperator/dnsrecon
### 8. dirsearch is a simple command line tool designed to brute force directories and files in websites. https://github.com/maurosoria/dirsearch
### 9. Sn1per automated pentest recon scanner. https://github.com/1N3/Sn1per

## Passive Intelligence Gathering
### 1.Social Mapper OSINT Social Media Mapping Tool, takes a list of names & images (or LinkedIn company name) and performs automated target searching on a huge scale across multiple social media sites. Not restricted by APIs as it instruments a browser using Selenium. Outputs reports to aid in correlating targets across sites. https://github.com/SpiderLabs/social_mapper
### 2.skiptracer OSINT scraping framework, utilizes some basic python webscraping (BeautifulSoup) of PII paywall sites to compile passive information on a target on a ramen noodle budget. https://github.com/xillwillx/skiptracer
### 3.FOCA (Fingerprinting Organizations with Collected Archives) is a tool used mainly to find metadata and hidden information in the documents its scans. https://github.com/ElevenPaths/FOCA
### 4.theHarvester is a tool for gathering subdomain names, e-mail addresses, virtual hosts, open ports/ banners, and employee names from different public sources. https://github.com/laramies/theHarvester
### 5.Metagoofil is a tool for extracting metadata of public documents (pdf,doc,xls,ppt,etc) availables in the target websites. https://github.com/laramies/metagoofil
### 6.SimplyEmail Email recon made fast and easy, with a framework to build on. https://github.com/killswitch-GUI/SimplyEmail
### 7.truffleHog searches through git repositories for secrets, digging deep into commit history and branches. https://github.com/dxa4481/truffleHog
### 8.Just-Metadata is a tool that gathers and analyzes metadata about IP addresses. It attempts to find relationships between systems within a large dataset. https://github.com/ChrisTruncer/Just-Metadata
### 9.typofinder a finder of domain typos showing country of IP address. https://github.com/nccgroup/typofinder
### 10.pwnedOrNot is a python script which checks if the email account has been compromised in a data breach, if the email account is compromised it proceeds to find passwords for the compromised account. https://github.com/thewhiteh4t/pwnedOrNot
### 11.GitHarvester This tool is used for harvesting information from GitHub like google dork. https://github.com/metac0rtex/GitHarvester
### 12.pwndb is a python command-line tool for searching leaked credentials using the Onion service with the same name. https://github.com/davidtavarez/pwndb/
### 13.LinkedInt LinkedIn Recon Tool. https://github.com/vysecurity/LinkedInt
### 14.CrossLinked LinkedIn enumeration tool to extract valid employee names from an organization through search engine scraping. https://github.com/m8r0wn/CrossLinked
### 15.findomain is a fast domain enumeration tool that uses Certificate Transparency logs and a selection of APIs. https://github.com/Edu4rdSHL/findomain

## Frameworks
### 1. Maltego is a unique platform developed to deliver a clear threat picture to the environment that an organization owns and operates. https://www.paterva.com/web7/downloads.php
### 2. SpiderFoot the open source footprinting and intelligence-gathering tool. https://github.com/smicallef/spiderfoot
### 3. datasploit is an OSINT Framework to perform various recon techniques on Companies, People, Phone Number, Bitcoin Addresses, etc., aggregate all the raw data, and give data in multiple formats. https://github.com/DataSploit/datasploit
### 4. Recon-ng is a full-featured Web Reconnaissance framework written in Python. https://bitbucket.org/LaNMaSteR53/recon-ng

# **Weaponization**
### 1.WinRAR Remote Code Execution Proof of Concept exploit for CVE-2018-20250. https://github.com/WyAtu/CVE-2018-20250
### 2.Composite Moniker Proof of Concept exploit for CVE-2017-8570. https://github.com/rxwx/CVE-2017-8570
### 3.Exploit toolkit CVE-2017-8759 is a handy python script which provides pentesters and security researchers a quick and effective way to test Microsoft .NET Framework RCE. https://github.com/bhdresh/CVE-2017-8759
### 4.CVE-2017-11882 Exploit accepts over 17k bytes long command/code in maximum. https://github.com/unamer/CVE-2017-11882
### 5.Adobe Flash Exploit CVE-2018-4878. https://github.com/anbai-inc/CVE-2018-4878
### 6.Exploit toolkit CVE-2017-0199 is a handy python script which provides pentesters and security researchers a quick and effective way to test Microsoft Office RCE. https://github.com/bhdresh/CVE-2017-0199
### 7.demiguise is a HTA encryption tool for RedTeams. https://github.com/nccgroup/demiguise
### 8.Office-DDE-Payloads collection of scripts and templates to generate Office documents embedded with the DDE, macro-less command execution technique. https://github.com/0xdeadbeefJERKY/Office-DDE-Payloads
### 9.CACTUSTORCH Payload Generation for Adversary Simulations. https://github.com/mdsecactivebreach/CACTUSTORCH
### 10.SharpShooter is a payload creation framework for the retrieval and execution of arbitrary CSharp source code. https://github.com/mdsecactivebreach/SharpShooter
### 11.Don’t kill my cat is a tool that generates obfuscated shellcode that is stored inside of polyglot images. The image is 100% valid and also 100% valid shellcode. https://github.com/Mr-Un1k0d3r/DKMC
### 12.Malicious Macro Generator Utility Simple utility design to generate obfuscated macro that also include a AV / Sandboxes escape mechanism. https://github.com/Mr-Un1k0d3r/MaliciousMacroGenerator
### 13.SCT Obfuscator Cobalt Strike SCT payload obfuscator. https://github.com/Mr-Un1k0d3r/SCT-obfuscator
### 14.Invoke-Obfuscation PowerShell Obfuscator. https://github.com/danielbohannon/Invoke-Obfuscation
### 15.Invoke-CradleCrafter PowerShell remote download cradle generator and obfuscator. https://github.com/danielbohannon/Invoke-CradleCrafter
### 16.Invoke-DOSfuscation cmd.exe Command Obfuscation Generator & Detection Test Harness. https://github.com/danielbohannon/Invoke-DOSfuscation
### 1 .morphHTA Morphing Cobalt Strike’s evil.HTA. https://github.com/vysec/morphHTA
### 2 .Unicorn is a simple tool for using a PowerShell downgrade attack and inject shellcode straight into memory. https://github.com/trustedsec/unicorn
### 3 .Shellter is a dynamic shellcode injection tool, and the first truly dynamic PE infector ever created. https://www.shellterproject.com/
### 4 .EmbedInHTML Embed and hide any file in an HTML file. https://github.com/Arno0x/EmbedInHTML
### 5 .SigThief Stealing Signatures and Making One Invalid Signature at a Time. https://github.com/secretsquirrel/SigThief
### 6 .Veil is a tool designed to generate metasploit payloads that bypass common anti-virus solutions. https://github.com/Veil-Framework/Veil
### 7 .CheckPlease Sandbox evasion modules written in PowerShell, Python, Go, Ruby, C, C#, Perl, and Rust. https://github.com/Arvanaghi/CheckPlease
### 8 .Invoke-PSImage is a tool to embeded a PowerShell script in the pixels of a PNG file and generates a oneliner to execute. https://github.com/peewpw/Invoke-PSImage
### 9 .LuckyStrike a PowerShell based utility for the creation of malicious Office macro documents. To be used for pentesting or educational purposes only. https://github.com/curi0usJack/luckystrike
### 10.ClickOnceGenerator Quick Malicious ClickOnceGenerator for Red Team. The default application a simple WebBrowser widget that point to a website of your choice. https://github.com/Mr-Un1k0d3r/ClickOnceGenerator
### 11.macro_pack is a tool by @EmericNasi used to automatize obfuscation and generation of MS Office documents, VB scripts, and other formats for pentest, demo, and social engineering assessments. https://github.com/sevagas/macro_pack
### 12.StarFighters a JavaScript and VBScript Based Empire Launcher. https://github.com/Cn33liz/StarFighters
### 13.nps_payload this script will generate payloads for basic intrusion detection avoidance. It utilizes publicly demonstrated techniques from several different sources. https://github.com/trustedsec/nps_payload
### 14.SocialEngineeringPayloads a collection of social engineering tricks and payloads being used for credential theft and spear phishing attacks. https://github.com/bhdresh/SocialEngineeringPayloads
### 15.The Social-Engineer Toolkit is an open-source penetration testing framework designed for social engineering. https://github.com/trustedsec/social-engineer-toolkit
### 16.Phishery is a Simple SSL Enabled HTTP server with the primary purpose of phishing credentials via Basic Authentication. https://github.com/ryhanson/phishery
### 17.PowerShdll run PowerShell with rundll32. Bypass software restrictions. https://github.com/p3nt4/PowerShdll
### 18.Ultimate AppLocker ByPass List The goal of this repository is to document the most common techniques to bypass AppLocker. https://github.com/api0cradle/UltimateAppLockerByPassList
### 19.Ruler is a tool that allows you to interact with Exchange servers remotely, through either the MAPI/HTTP or RPC/HTTP protocol. https://github.com/sensepost/ruler
### 20.Generate-Macro is a standalone PowerShell script that will generate a malicious Microsoft Office document with a specified payload and persistence method. https://github.com/enigma0x3/Generate-Macro
### 21.Malicious Macro MSBuild Generator Generates Malicious Macro and Execute Powershell or Shellcode via MSBuild Application Whitelisting Bypass. https://github.com/infosecn1nja/MaliciousMacroMSBuild
### 22.Meta Twin is designed as a file resource cloner. Metadata, including digital signature, is extracted from one file and injected into another. https://github.com/threatexpress/metatwin
### 23.WePWNise generates architecture independent VBA code to be used in Office documents or templates and automates bypassing application control and exploit mitigation software. https://github.com/mwrlabs/wePWNise
### 24.DotNetToJScript a tool to create a JScript file which loads a .NET v2 assembly from memory. https://github.com/tyranid/DotNetToJScript
### 25.PSAmsi is a tool for auditing and defeating AMSI signatures. https://github.com/cobbr/PSAmsi
### 26.Reflective DLL injection is a library injection technique in which the concept of reflective programming is employed to perform the loading of a library from memory into a host process. https://github.com/stephenfewer/ReflectiveDLLInjection
### 27.ps1encode use to generate and encode a powershell based metasploit payloads. https://github.com/CroweCybersecurity/ps1encode
### 28.Worse PDF turn a normal PDF file into malicious. Use to steal Net-NTLM Hashes from windows machines. https://github.com/3gstudent/Worse-PDF
### 29.SpookFlare has a different perspective to bypass security measures and it gives you the opportunity to bypass the endpoint countermeasures at the client-side detection and network-side detection. https://github.com/hlldz/SpookFlare
### 30.GreatSCT is an open source project to generate application white list bypasses. This tool is intended for BOTH red and blue team. https://github.com/GreatSCT/GreatSCT
### 31.nps running powershell without powershell. https://github.com/Ben0xA/nps
### 32.Meterpreter_Paranoid_Mode.sh allows users to secure your staged/stageless connection for Meterpreter by having it check the certificate of the handler it is connecting to. https://github.com/r00t-3xp10it/Meterpreter_Paranoid_Mode-SSL
### 33.The Backdoor Factory (BDF) is to patch executable binaries with user desired shellcode and continue normal execution of the prepatched state. https://github.com/secretsquirrel/the-backdoor-factory
### 34.MacroShop a collection of scripts to aid in delivering payloads via Office Macros. https://github.com/khr0x40sh/MacroShop
### 35.UnmanagedPowerShell Executes PowerShell from an unmanaged process. https://github.com/leechristensen/UnmanagedPowerShell
### 36.evil-ssdp Spoof SSDP replies to phish for NTLM hashes on a network. Creates a fake UPNP device, tricking users into visiting a malicious phishing page. https://gitlab.com/initstring/evil-ssdp
### 37.Ebowla Framework for Making Environmental Keyed Payloads. https://github.com/Genetic-Malware/Ebowla
### 38.make-pdf-embedded a tool to create a PDF document with an embedded file. https://github.com/DidierStevens/DidierStevensSuite/blob/master/make-pdf-embedded.py
### 39.avet (AntiVirusEvasionTool) is targeting windows machines with executable files using different evasion techniques. https://github.com/govolution/avet
### 40.EvilClippy A cross-platform assistant for creating malicious MS Office documents. Can hide VBA macros, stomp VBA code (via P-Code) and confuse macro analysis tools. Runs on Linux, OSX and Windows. https://github.com/outflanknl/EvilClippy
### 41.CallObfuscator Obfuscate windows apis from static analysis tools and debuggers. https://github.com/d35ha/CallObfuscator
### 42.Donut is a shellcode generation tool that creates position-independant shellcode payloads from .NET Assemblies. This shellcode may be used to inject the Assembly into arbitrary Windows processes. https://github.com/TheWover/donut

# **Delivery**
## Phishing
### 1 . King Phisher is a tool for testing and promoting user awareness by simulating real world phishing attacks. https://github.com/securestate/king-phisher
### 2 . FiercePhish is a full-fledged phishing framework to manage all phishing engagements. It allows you to track separate phishing campaigns, schedule sending of emails, and much more. https://github.com/Raikia/FiercePhish
### 3 . ReelPhish is a Real-Time Two-Factor Phishing Tool. https://github.com/fireeye/ReelPhish/
### 4 . Gophish is an open-source phishing toolkit designed for businesses and penetration testers. It provides the ability to quickly and easily setup and execute phishing engagements and security awareness training. https://github.com/gophish/gophish
### 5 . CredSniper is a phishing framework written with the Python micro-framework Flask and Jinja2 templating which supports capturing 2FA tokens. https://github.com/ustayready/CredSniper
### 6 . PwnAuth a web application framework for launching and managing OAuth abuse campaigns. https://github.com/fireeye/PwnAuth
### 7 . Phishing Frenzy Ruby on Rails Phishing Framework. https://github.com/pentestgeek/phishing-frenzy
### 8 . Phishing Pretexts a library of pretexts to use on offensive phishing engagements. https://github.com/L4bF0x/PhishingPretexts
### 9 . Modlishka is a flexible and powerful reverse proxy, that will take your ethical phishing campaigns to the next level. https://github.com/drk1wi/Modlishka
### 10. Evilginx2 is a man-in-the-middle attack framework used for phishing credentials and session cookies of any web service. https://github.com/kgretzky/evilginx2
### 11. Watering Hole Attack
### 12. BeEF is short for The Browser Exploitation Framework. It is a penetration testing tool that focuses on the web browser. https://github.com/beefproject/beef

# **Command and Control**
## Remote Access Tools
### 1 . Cobalt Strike is software for Adversary Simulations and Red Team Operations. https://cobaltstrike.com/
### 2 . Empire is a post-exploitation framework that includes a pure-PowerShell2.0 Windows agent, and a pure Python 2.6/2.7 Linux/OS X agent. https://github.com/EmpireProject/Empire
### 3 . Metasploit Framework is a computer security project that provides information about security vulnerabilities and aids in penetration testing and IDS signature development. https://github.com/rapid7/metasploit-framework
### 4 . SILENTTRINITY A post-exploitation agent powered by Python, IronPython, C#/.NET. https://github.com/byt3bl33d3r/SILENTTRINITY
### 5 . Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) remote administration and post-exploitation tool mainly written in python. https://github.com/n1nj4sec/pupy
### 6 . Koadic or COM Command & Control, is a Windows post-exploitation rootkit similar to other penetration testing tools such as Meterpreter and Powershell Empire. https://github.com/zerosum0x0/koadic
### 7 . PoshC2 is a proxy aware C2 framework written completely in PowerShell to aid penetration testers with red teaming, post-exploitation and lateral movement. https://github.com/nettitude/PoshC2_Python
### 8 . Gcat a stealthy Python based backdoor that uses Gmail as a command and control server. https://github.com/byt3bl33d3r/gcat
### 9 . TrevorC2 is a legitimate website (browsable) that tunnels client/server communications for covert command execution. https://github.com/trustedsec/trevorc2
### 10. Merlin is a cross-platform post-exploitation HTTP/2 Command & Control server and agent written in golang. https://github.com/Ne0nd0g/merlin
### 11. Quasar is a fast and light-weight remote administration tool coded in C#. Providing high stability and an easy-to-use user interface, Quasar is the perfect remote administration solution for you. https://github.com/quasar/QuasarRAT
### 12. Covenant is a .NET command and control framework that aims to highlight the attack surface of .NET, make the use of offensive .NET tradecraft easier, and serve as a collaborative command and control platform for red teamers. https://github.com/cobbr/Covenant
### 13. FactionC2 is a C2 framework which use websockets based API that allows for interacting with agents and transports. https://github.com/FactionC2/
### 14. DNScat2 is a tool is designed to create an encrypted command-and-control (C&C) channel over the DNS protocol. https://github.com/iagox86/dnscat2
### 15. Sliver is a general purpose cross-platform implant framework that supports C2 over Mutual-TLS, HTTP(S), and DNS. https://github.com/BishopFox/sliver
### 16. EvilOSX An evil RAT (Remote Administration Tool) for macOS / OS X. https://github.com/Marten4n6/EvilOSX
### 17. EggShell is a post exploitation surveillance tool written in Python. It gives you a command line session with extra functionality between you and a target machine. https://github.com/neoneggplant/EggShell

## Staging
### 1 .Rapid Attack Infrastructure (RAI) Red Team Infrastructure… Quick… Fast… Simplified One of the most tedious phases of a Red Team Operation is usually the infrastructure setup. This usually entails a teamserver or controller, domains, redirectors, and a Phishing server. https://github.com/obscuritylabs/RAI
### 2 .Red Baron is a set of modules and custom/third-party providers for Terraform which tries to automate creating resilient, disposable, secure and agile infrastructure for Red Teams. https://github.com/byt3bl33d3r/Red-Baron
### 3 .EvilURL generate unicode evil domains for IDN Homograph Attack and detect them. https://github.com/UndeadSec/EvilURL
### 4 .Domain Hunter checks expired domains, bluecoat categorization, and Archive.org history to determine good candidates for phishing and C2 domain names. https://github.com/threatexpress/domainhunter
### 5 .PowerDNS is a simple proof of concept to demonstrate the execution of PowerShell script using DNS only. https://github.com/mdsecactivebreach/PowerDNS
### 6 .Chameleon a tool for evading Proxy categorisation. https://github.com/mdsecactivebreach/Chameleon
### 7 .CatMyFish Search for categorized domain that can be used during red teaming engagement. Perfect to setup whitelisted domain for your Cobalt Strike beacon C&C. https://github.com/Mr-Un1k0d3r/CatMyFish
### 8 .Malleable C2 is a domain specific language to redefine indicators in Beacon’s communication. https://github.com/rsmudge/Malleable-C2-Profiles
### 9 .Malleable-C2-Randomizer This script randomizes Cobalt Strike Malleable C2 profiles through the use of a metalanguage, hopefully reducing the chances of flagging signature-based detection controls. https://github.com/bluscreenofjeff/Malleable-C2-Randomizer
### 10.FindFrontableDomains search for potential frontable domains. https://github.com/rvrsh3ll/FindFrontableDomains
### 11.Postfix-Server-Setup Setting up a phishing server is a very long and tedious process. It can take hours to setup, and can be compromised in minutes. https://github.com/n0pe-sled/Postfix-Server-Setup
### 12.DomainFrontingLists a list of Domain Frontable Domains by CDN. https://github.com/vysec/DomainFrontingLists
### 13.Apache2-Mod-Rewrite-Setup Quickly Implement Mod-Rewrite in your infastructure. https://github.com/n0pe-sled/Apache2-Mod-Rewrite-Setup
### 14.mod_rewrite rule to evade vendor sandboxes. https://gist.github.com/curi0usJack/971385e8334e189d93a6cb4671238b10
### 15.external_c2 framework a python framework for usage with Cobalt Strike’s External C2. https://github.com/Und3rf10w/external_c2_framework
### 16.Malleable-C2-Profiles A collection of profiles used in different projects using Cobalt Strike https://www.cobaltstrike.com/. https://github.com/xx0hcd/Malleable-C2-Profiles
### 17.ExternalC2 a library for integrating communication channels with the Cobalt Strike External C2 server. https://github.com/ryhanson/ExternalC2
### 18.cs2modrewrite a tools for convert Cobalt Strike profiles to modrewrite scripts. https://github.com/threatexpress/cs2modrewrite
### 19.e2modrewrite a tools for convert Empire profiles to Apache modrewrite scripts. https://github.com/infosecn1nja/e2modrewrite
### 20.redi automated script for setting up CobaltStrike redirectors (nginx reverse proxy, letsencrypt). https://github.com/taherio/redi
### 21.cat-sites Library of sites for categorization. https://github.com/audrummer15/cat-sites
### 22.ycsm is a quick script installation for resilient redirector using nginx reverse proxy and letsencrypt compatible with some popular Post-Ex Tools (Cobalt Strike, Empire, Metasploit, PoshC2). https://github.com/infosecn1nja/ycsm
### 23.Domain Fronting Google App Engine. https://github.com/redteam-cyberark/Google-Domain-fronting
### 24.DomainFrontDiscover Scripts and results for finding domain frontable CloudFront domains. https://github.com/peewpw/DomainFrontDiscover
### 25.Automated Empire Infrastructure https://github.com/bneg/RedTeam-Automation
### 26.Serving Random Payloads with NGINX. https://gist.github.com/jivoi/a33ace2e25515a31aa2ffbae246d98c9
### 27.meek is a blocking-resistant pluggable transport for Tor. It encodes a data stream as a sequence of HTTPS requests and responses. https://github.com/arlolra/meek
### 28.CobaltStrike-ToolKit Some useful scripts for CobaltStrike. https://github.com/killswitch-GUI/CobaltStrike-ToolKit
### 29.mkhtaccess_red Auto-generate an HTaccess for payload delivery — automatically pulls ips/nets/etc from known sandbox companies/sources that have been seen before, and redirects them to a benign payload. https://github.com/violentlydave/mkhtaccess_red
### 30.RedFile a flask wsgi application that serves files with intelligence, good for serving conditional RedTeam payloads. https://github.com/outflanknl/RedFile
### 31.keyserver Easily serve HTTP and DNS keys for proper payload protection. https://github.com/leoloobeek/keyserver
### 32.DoHC2 allows the ExternalC2 library from Ryan Hanson (https://github.com/ryhanson/ExternalC2) to be leveraged for command and control (C2) via DNS over HTTPS (DoH). This is built for the popular Adversary Simulation and Red Team Operations Software Cobalt Strike (https://www.cobaltstrike.com). https://github.com/SpiderLabs/DoHC2
### 33.HTran is a connection bouncer, a kind of proxy server. A “listener” program is hacked stealthily onto an unsuspecting host anywhere on the Internet. https://github.com/HiwinCN/HTran

## **Lateral Movement**
### 1 .CrackMapExec is a swiss army knife for pentesting networks. https://github.com/byt3bl33d3r/CrackMapExec
### 2 .PowerLessShell rely on MSBuild.exe to remotely execute PowerShell scripts and commands without spawning powershell.exe. https://github.com/Mr-Un1k0d3r/PowerLessShell
### 3 .GoFetch is a tool to automatically exercise an attack plan generated by the BloodHound application. https://github.com/GoFetchAD/GoFetch
### 4 .ANGRYPUPPY a bloodhound attack path automation in CobaltStrike. https://github.com/vysec/ANGRYPUPPY
### 5 .DeathStar is a Python script that uses Empire’s RESTful API to automate gaining Domain Admin rights in Active Directory environments using a variety of techinques. https://github.com/byt3bl33d3r/DeathStar
### 6 .SharpHound C# Rewrite of the BloodHound Ingestor. https://github.com/BloodHoundAD/SharpHound
### 7 .BloodHound.py is a Python based ingestor for BloodHound, based on Impacket. https://github.com/fox-it/BloodHound.py
### 8 .Responder is a LLMNR, NBT-NS and MDNS poisoner, with built-in HTTP/SMB/MSSQL/FTP/LDAP rogue authentication server supporting NTLMv1/NTLMv2/LMv2, Extended Security NTLMSSP and Basic HTTP authentication. https://github.com/SpiderLabs/Responder
### 9 .SessionGopher is a PowerShell tool that uses WMI to extract saved session information for remote access tools such as WinSCP, PuTTY, SuperPuTTY, FileZilla, and Microsoft Remote Desktop. It can be run remotely or locally. https://github.com/fireeye/SessionGopher
### 10.PowerSploit is a collection of Microsoft PowerShell modules that can be used to aid penetration testers during all phases of an assessment. https://github.com/PowerShellMafia/PowerSploit
### 11.Nishang is a framework and collection of scripts and payloads which enables usage of PowerShell for offensive security, penetration testing and red teaming. Nishang is useful during all phases of penetration testing. https://github.com/samratashok/nishang
### 12.Inveigh is a Windows PowerShell LLMNR/mDNS/NBNS spoofer/man-in-the-middle tool. https://github.com/Kevin-Robertson/Inveigh
### 13.PowerUpSQL a PowerShell Toolkit for Attacking SQL Server. https://github.com/NetSPI/PowerUpSQL
### 14.MailSniper is a penetration testing tool for searching through email in a Microsoft Exchange environment for specific terms (passwords, insider intel, network architecture information, etc.). https://github.com/dafthack/MailSniper
### 15.DomainPasswordSpray is a tool written in PowerShell to perform a password spray attack against users of a domain. https://github.com/dafthack/DomainPasswordSpray
### 16.WMIOps is a powershell script that uses WMI to perform a variety of actions on hosts, local or remote, within a Windows environment. It’s designed primarily for use on penetration tests or red team engagements. https://github.com/ChrisTruncer/WMIOps
### 17.Mimikatz is an open-source utility that enables the viewing of credential information from the Windows lsass. https://github.com/gentilkiwi/mimikatz
### 18.LaZagne project is an open source application used to retrieve lots of passwords stored on a local computer. https://github.com/AlessandroZ/LaZagne
### 19.mimipenguin a tool to dump the login password from the current linux desktop user. Adapted from the idea behind the popular Windows tool mimikatz. https://github.com/huntergregal/mimipenguin
### 20.PsExec is a light-weight telnet-replacement that lets you execute processes on other systems, complete with full interactivity for console applications, without having to manually install client software. https://docs.microsoft.com/en-us/sysinternals/downloads/psexec
### 21.KeeThief allows for the extraction of KeePass 2.X key material from memory, as well as the backdooring and enumeration of the KeePass trigger system. https://github.com/HarmJ0y/KeeThief
### 22.PSAttack combines some of the best projects in the infosec powershell community into a self contained custom PowerShell console. https://github.com/jaredhaight/PSAttack
### 23.Internal Monologue Attack Retrieving NTLM Hashes without Touching LSASS. https://github.com/eladshamir/Internal-Monologue
### 24.Impacket is a collection of Python classes for working with network protocols. Impacket is focused on providing low-level programmatic access to the packets and for some protocols (for instance NMB, SMB1-3 and MS-DCERPC) the protocol implementation itself. https://github.com/CoreSecurity/impacket
### 25.icebreaker gets plaintext Active Directory credentials if you’re on the internal network but outside the AD environment. https://github.com/DanMcInerney/icebreaker
### 26.Living Off The Land Binaries and Scripts (and now also Libraries) The goal of these lists are to document every binary, script and library that can be used for other purposes than they are designed to. https://github.com/api0cradle/LOLBAS
### 27.WSUSpendu for compromised WSUS server to extend the compromise to clients. https://github.com/AlsidOfficial/WSUSpendu
### 28.Evilgrade is a modular framework that allows the user to take advantage of poor upgrade implementations by injecting fake updates. https://github.com/infobyte/evilgrade
### 29.NetRipper is a post exploitation tool targeting Windows systems which uses API hooking in order to intercept network traffic and encryption related functions from a low privileged user, being able to capture both plain-text traffic and encrypted traffic before encryption/after decryption. https://github.com/NytroRST/NetRipper
### 30.LethalHTA Lateral Movement technique using DCOM and HTA. https://github.com/codewhitesec/LethalHTA
### 31.Invoke-PowerThIEf an Internet Explorer Post Exploitation library. https://github.com/nettitude/Invoke-PowerThIEf
### 32.RedSnarf is a pen-testing / red-teaming tool for Windows environments. https://github.com/nccgroup/redsnarf
### 33.HoneypotBuster Microsoft PowerShell module designed for red teams that can be used to find honeypots and honeytokens in the network or at the host. https://github.com/JavelinNetworks/HoneypotBuster
### 34.PAExec lets you launch Windows programs on remote Windows computers without needing to install software on the remote computer first. https://www.poweradmin.com/paexec/

# Establish Foothold
### 1. Tunna is a set of tools which will wrap and tunnel any TCP communication over HTTP. It can be used to bypass network restrictions in fully firewalled environments. https://github.com/SECFORCE/Tunna
### 2. reGeorg the successor to reDuh, pwn a bastion webserver and create SOCKS proxies through the DMZ. Pivot and pwn. https://github.com/sensepost/reGeorg
### 3. Blade is a webshell connection tool based on console, currently under development and aims to be a choice of replacement of Chooper. https://github.com/wonderqs/Blade
### 4. TinyShell Web Shell Framework. https://github.com/threatexpress/tinyshell
### 5. PowerLurk is a PowerShell toolset for building malicious WMI Event Subsriptions. https://github.com/Sw4mpf0x/PowerLurk
### 6. DAMP The Discretionary ACL Modification Project: Persistence Through Host-based Security Descriptor Modification. https://github.com/HarmJ0y/DAMP

# **Escalate Privileges**
## Domain Escalation
### 1 . PowerView is a PowerShell tool to gain network situational awareness on Windows domains. https://github.com/PowerShellMafia/PowerSploit/blob/master/Recon/PowerView.ps1
### 2 . Get-GPPPassword Retrieves the plaintext password and other information for accounts pushed through Group Policy Preferences. https://github.com/PowerShellMafia/PowerSploit/blob/master/Exfiltration/Get-GPPPassword.ps1
### 3 . Invoke-ACLpwn is a tool that automates the discovery and pwnage of ACLs in Active Directory that are unsafe configured. https://github.com/fox-it/Invoke-ACLPwn
### 4 . BloodHound uses graph theory to reveal the hidden and often unintended relationships within an Active Directory environment. https://github.com/BloodHoundAD/BloodHound
### 5 . PyKEK (Python Kerberos Exploitation Kit), a python library to manipulate KRB5-related data. https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS14-068/pykek
### 6 . Grouper a PowerShell script for helping to find vulnerable settings in AD Group Policy. https://github.com/l0ss/Grouper
### 7 . ADRecon is a tool which extracts various artifacts (as highlighted below) out of an AD environment in a specially formatted Microsoft Excel report that includes summary views with metrics to facilitate analysis. https://github.com/sense-of-security/ADRecon
### 8 . ADACLScanner one script for ACL’s in Active Directory. https://github.com/canix1/ADACLScanner
### 9 . ACLight a useful script for advanced discovery of Domain Privileged Accounts that could be targeted – including Shadow Admins. https://github.com/cyberark/ACLight
### 10. LAPSToolkit a tool to audit and attack LAPS environments. https://github.com/leoloobeek/LAPSToolkit
### 11. PingCastle is a free, Windows-based utility to audit the risk level of your AD infrastructure and check for vulnerable practices. https://www.pingcastle.com/download
### 12. RiskySPNs is a collection of PowerShell scripts focused on detecting and abusing accounts associated with SPNs (Service Principal Name). https://github.com/cyberark/RiskySPN
### 13. Mystique is a PowerShell tool to play with Kerberos S4U extensions, this module can assist blue teams to identify risky Kerberos delegation configurations as well as red teams to impersonate arbitrary users by leveraging KCD with Protocol Transition. https://github.com/machosec/Mystique
### 14. Rubeus is a C# toolset for raw Kerberos interaction and abuses. It is heavily adapted from Benjamin Delpy’s Kekeo project. https://github.com/GhostPack/Rubeus
### 15. kekeo is a little toolbox I have started to manipulate Microsoft Kerberos in C (and for fun). https://github.com/gentilkiwi/kekeo

## Local Escalation
### 1.UACMe is an open source assessment tool that contains many methods for bypassing Windows User Account Control on multiple versions of the operating system. https://github.com/hfiref0x/UACME
### 2.windows-kernel-exploits a collection windows kernel exploit. https://github.com/SecWiki/windows-kernel-exploits
### 3.PowerUp aims to be a clearinghouse of common Windows privilege escalation vectors that rely on misconfigurations. https://github.com/PowerShellMafia/PowerSploit/blob/master/Privesc/PowerUp.ps1
### 4.The Elevate Kit demonstrates how to use third-party privilege escalation attacks with Cobalt Strike’s Beacon payload. https://github.com/rsmudge/ElevateKit
### 5.Sherlock a powerShell script to quickly find missing software patches for local privilege escalation vulnerabilities. https://github.com/rasta-mouse/Sherlock
### 6.Tokenvator a tool to elevate privilege with Windows Tokens. https://github.com/0xbadjuju/Tokenvator

# **Data Exfiltration**
### 1. CloakifyFactory & the Cloakify Toolset – Data Exfiltration & Infiltration In Plain Sight; Evade DLP/MLS Devices; Social Engineering of Analysts; Defeat Data Whitelisting Controls; Evade AV Detection. https://github.com/TryCatchHCF/Cloakify
### 2. DET (is provided AS IS), is a proof of concept to perform Data Exfiltration using either single or multiple channel(s) at the same time. https://github.com/sensepost/DET
### 3. DNSExfiltrator allows for transfering (exfiltrate) a file over a DNS request covert channel. This is basically a data leak testing tool allowing to exfiltrate data over a covert channel. https://github.com/Arno0x/DNSExfiltrator
### 4. PyExfil a Python Package for Data Exfiltration. https://github.com/ytisf/PyExfil
### 5. Egress-Assess is a tool used to test egress data detection capabilities. https://github.com/ChrisTruncer/Egress-Assess
### 6. Powershell RAT python based backdoor that uses Gmail to exfiltrate data as an e-mail attachment. https://github.com/Viralmaniar/Powershell-RAT

# **Misc**
## Adversary Emulation
### 1. MITRE CALDERA – An automated adversary emulation system that performs post-compromise adversarial behavior within Windows Enterprise networks. https://github.com/mitre/caldera
### 2. APTSimulator – A Windows Batch script that uses a set of tools and output files to make a system look as if it was compromised. https://github.com/NextronSystems/APTSimulator
### 3. Atomic Red Team – Small and highly portable detection tests mapped to the Mitre ATT&CK Framework. https://github.com/redcanaryco/atomic-red-team
### 4. Network Flight Simulator – flightsim is a lightweight utility used to generate malicious network traffic and help security teams to evaluate security controls and network visibility. https://github.com/alphasoc/flightsim
### 5. Metta – A security preparedness tool to do adversarial simulation. https://github.com/uber-common/metta
### 6. Red Team Automation (RTA) – RTA provides a framework of scripts designed to allow blue teams to test their detection capabilities against malicious tradecraft, modeled after MITRE ATT&CK. https://github.com/endgameinc/RTA

## Wireless Networks
### 1 . Wifiphisher is a security tool that performs Wi-Fi automatic association attacks to force wireless clients to unknowingly connect to an attacker-controlled Access Point. https://github.com/wifiphisher/wifiphisher
### 2 . mana toolkit for wifi rogue AP attacks and MitM. https://github.com/sensepost/mana
### 3 . Embedded & Peripheral Devices Hacking
### 4 . magspoof a portable device that can spoof/emulate any magnetic stripe, credit card or hotel card “wirelessly”, even on standard magstripe (non-NFC/RFID) readers. https://github.com/samyk/magspoof
### 5 . WarBerryPi was built to be used as a hardware implant during red teaming scenarios where we want to obtain as much information as possible in a short period of time with being as stealth as possible. https://github.com/secgroundzero/warberry
### 6 . P4wnP1 is a highly customizable USB attack platform, based on a low cost Raspberry Pi Zero or Raspberry Pi Zero W (required for HID backdoor). https://github.com/mame82/P4wnP1
### 7 . malusb HID spoofing multi-OS payload for Teensy. https://github.com/ebursztein/malusb
### 8 . Fenrir is a tool designed to be used “out-of-the-box” for penetration tests and offensive engagements. Its main feature and purpose is to bypass wired 802.1x protection and to give you an access to the target network. https://github.com/Orange-Cyberdefense/fenrir-ocd
### 9 . poisontap exploits locked/password protected computers over USB, drops persistent WebSocket-based backdoor, exposes internal router, and siphons cookies using Raspberry Pi Zero & Node.js. https://github.com/samyk/poisontap
### 10. WHID WiFi HID Injector – An USB Rubberducky / BadUSB On Steroids. https://github.com/whid-injector/WHID
### 11. PhanTap is an ‘invisible’ network tap aimed at red teams. With limited physical access to a target building, this tap can be installed inline between a network device and the corporate network. https://github.com/nccgroup/phantap

## Software For Team Communication
### 1. RocketChat is free, unlimited and open source. Replace email & Slack with the ultimate team chat software solution. https://rocket.chat
### 2. Etherpad is an open source, web-based collaborative real-time editor, allowing authors to simultaneously edit a text document https://etherpad.org/

## Log Aggregation
### 1. RedELK Red Team’s SIEM – easy deployable tool for Red Teams used for tracking and alarming about Blue Team activities as well as better usability in long term operations. https://github.com/outflanknl/RedELK/
### 2. CobaltSplunk Splunk Dashboard for CobaltStrike logs. https://github.com/vysec/CobaltSplunk
### 3. Red Team Telemetry A collection of scripts and configurations to enable centralized logging of red team infrastructure. https://github.com/ztgrace/red_team_telemetry
### 4. Elastic for Red Teaming Repository of resources for configuring a Red Team SIEM using Elastic. https://github.com/SecurityRiskAdvisors/RedTeamSIEM
### 5. Ghostwriter is a Django project written in Python 3.7 and is designed to be used by a team of operators. https://github.com/GhostManager/Ghostwriter

## C# Offensive Framework
### 1. SharpSploit is a .NET post-exploitation library written in C# that aims to highlight the attack surface of .NET and make the use of offensive .NET easier for red teamers. https://github.com/cobbr/SharpSploit
### 2. GhostPack is (currently) a collection various C# implementations of previous PowerShell functionality, and includes six separate toolsets being released today- Seatbelt, SharpUp, SharpRoast, SharpDump, SafetyKatz, and SharpWMI. https://github.com/GhostPack
### 3. SharpWeb .NET 2.0 CLR project to retrieve saved browser credentials from Google Chrome, Mozilla Firefox and Microsoft Internet Explorer/Edge. https://github.com/djhohnstein/SharpWeb
### 4. reconerator C# Targeted Attack Reconnissance Tools. https://github.com/stufus/reconerator
### 5. SharpView C# implementation of harmj0y’s PowerView. https://github.com/tevora-threat/SharpView
### 6. Watson is a (.NET 2.0 compliant) C# implementation of Sherlock. https://github.com/rasta-mouse/Watson

##Labs
### 1. Detection Lab This lab has been designed with defenders in mind. Its primary purpose is to allow the user to quickly build a Windows domain that comes pre-loaded with security tooling and some best practices when it comes to system logging configurations. https://github.com/clong/DetectionLab
### 2. Modern Windows Attacks and Defense Lab This is the lab configuration for the Modern Windows Attacks and Defense class that Sean Metcalf (@pyrotek3) and I teach. https://github.com/jaredhaight/WindowsAttackAndDefenseLab
### 3. Invoke-UserSimulator Simulates common user behaviour on local and remote Windows hosts. https://github.com/ubeeri/Invoke-UserSimulator
### 4. Invoke-ADLabDeployer Automated deployment of Windows and Active Directory test lab networks. Useful for red and blue teams. https://github.com/outflanknl/Invoke-ADLabDeployer
### 5. Sheepl Creating realistic user behaviour for supporting tradecraft development within lab environments. https://github.com/SpiderLabs/sheepl

## Scripts
### Aggressor Scripts is a scripting language for red team operations and adversary simulations inspired by scriptable IRC clients and bots.
1 . https://github.com/invokethreatguy/CSASC
2 . https://github.com/secgroundzero/CS-Aggressor-Scripts
3 . https://github.com/Und3rf10w/Aggressor-scripts
4 . https://github.com/harleyQu1nn/AggressorScripts
5 . https://github.com/rasta-mouse/Aggressor-Script
6 . https://github.com/RhinoSecurityLabs/Aggressor-Scripts
7 . https://github.com/bluscreenofjeff/AggressorScripts
8 . https://github.com/001SPARTaN/aggressor_scripts
9 . https://github.com/360-A-Team/CobaltStrike-Toolset
10. https://github.com/FortyNorthSecurity/AggressorAssessor
11. https://github.com/ramen0x3f/AggressorScripts

### A collection scripts useful for red teaming and pentesting
1 . https://github.com/FuzzySecurity/PowerShell-Suite
2 . https://github.com/nettitude/Powershell
3 . https://github.com/Mr-Un1k0d3r/RedTeamPowershellScripts
4 . https://github.com/threatexpress/red-team-scripts
5 . https://github.com/SadProcessor/SomeStuff
6 . https://github.com/rvrsh3ll/Misc-Powershell-Scripts
7 . https://github.com/enigma0x3/Misc-PowerShell-Stuff
8 . https://github.com/ChrisTruncer/PenTestScripts
9 . https://github.com/bluscreenofjeff/Scripts
10. https://github.com/xorrior/RandomPS-Scripts
11. https://github.com/xorrior/Random-CSharpTools
12. https://github.com/leechristensen/Random
13. https://github.com/mgeeky/Penetration-Testing-Tools/tree/master/social-engineering

# **References**
### 1 . MITRE’s ATT&CK™ is a curated knowledge base and model for cyber adversary behavior, reflecting the various phases of an adversary’s lifecycle and the platforms they are known to target. https://attack.mitre.org/wiki/Main_Page
### 2 . Cheat Sheets for various projects (Beacon/Cobalt Strike,PowerView, PowerUp, Empire, and PowerSploit). https://github.com/HarmJ0y/CheatSheets
### 3 . PRE-ATT&CK Adversarial Tactics, Techniques & Common Knowledge for Left-of-Exploit. https://attack.mitre.org/pre-attack/index.php/Main_Page
### 4 . Adversary OPSEC consists of the use of various technologies or 3rd party services to obfuscate, hide, or blend in with accepted network traffic or system behavior. https://attack.mitre.org/pre-attack/index.php/Adversary_OPSEC
### 5 . Adversary Emulation Plans To showcase the practical use of ATT&CK for offensive operators and defenders, MITRE created Adversary Emulation Plans. https://attack.mitre.org/wiki/Adversary_Emulation_Plans
### 6 . Red-Team-Infrastructure-Wiki Wiki to collect Red Team infrastructure hardening resources. https://github.com/bluscreenofjeff/Red-Team-Infrastructure-Wiki
### 7 . Advanced Threat Tactics – Course and Notes This is a course on red team operations and adversary simulations. https://blog.cobaltstrike.com/2015/09/30/advanced-threat-tactics-course-and-notes
### 8 . Red Team Tips as posted by @vysecurity on Twitter. https://vincentyiu.co.uk/red-team-tips
### 9 . Awesome Red Teaming List of Awesome Red Team / Red Teaming Resources. https://github.com/yeyintminthuhtut/Awesome-Red-Teaming
### 10. APT & CyberCriminal Campaign Collection This is a collection of APT and CyberCriminal campaigns. Please fire issue to me if any lost APT/Malware events/campaigns. https://github.com/CyberMonitor/APT_CyberCriminal_Campagin_Collections
### 11. ATT&CK for Enterprise Software is a generic term for custom or commercial code, operating system utilities, open-source software, or other tools used to conduct behavior modeled in ATT&CK. https://attack.mitre.org/wiki/Software
### 12. Planning a Red Team exercise This document helps inform red team planning by contrasting against the very specific red team style described in Red Teams. https://github.com/magoo/redteam-plan
### 13. Awesome Lockpicking a curated list of awesome guides, tools, and other resources related to the security and compromise of locks, safes, and keys. https://github.com/meitar/awesome-lockpicking
### 14. Awesome Threat Intelligence a curated list of awesome Threat Intelligence resources. https://github.com/hslatman/awesome-threat-intelligence
### 15. APT Notes Need some scenario? APTnotes is a repository of publicly-available papers and blogs (sorted by year) related to malicious campaigns/activity/software that have been associated with vendor-defined APT (Advanced Persistent Threat) groups and/or tool-sets. https://github.com/aptnotes/data
### 16. TIBER-EU FRAMEWORK The European Framework for Threat Intelligence-based Ethical Red Teaming (TIBER-EU), which is the first Europe-wide framework for controlled and bespoke tests against cyber attacks in the financial market. http://www.ecb.europa.eu/pub/pdf/other/ecb.tiber_eu_framework.en.pdf
### 17. CBEST Implementation Guide CBEST is a framework to deliver controlled, bespoke, intelligence-led cyber security tests. The tests replicate behaviours of threat actors, assessed by the UK Government and commercial intelligence providers as posing a genuine threat to systemically important financial institutions. https://www.crest-approved.org/wp-content/uploads/2014/07/CBEST-Implementation-Guide.pdf
### 18. Red Team: Adversarial Attack Simulation Exercise Guidelines for the Financial Industry in Singapore The Association of Banks in Singapore (ABS), with support from the Monetary Authority of Singapore (MAS), has developed a set of cybersecurity assessment guidelines today to strengthen the cyber resilience of the financial sector in Singapore. Known as the Adversarial Attack Simulation Exercises (AASE) Guidelines or “Red Teaming” Guidelines, the Guidelines provide financial institutions (FIs) with best practices and guidance on planning and conducting Red Teaming exercises to enhance their security testing. https://abs.org.sg/docs/library/abs-red-team-adversarial-attack-simulation-exercises-guidelines-v1-06766a69f299c69658b7dff00006ed795.pdf
