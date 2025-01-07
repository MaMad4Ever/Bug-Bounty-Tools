# Tools-for-Bug-Hunters

Here you can find links to a bunch of useful tools for Bug Bounty Hunting.

### Proxy & Network Sniffer
| Name 	| Description 	|
|------	|-------------	|
|[Burp Suite](https://portswigger.net/burp)|A Proxy to intercept and manipulate Web Traffic (free & paid version).
|[Caido](https://caido.io/)|A lightweight web security auditing toolkit.
|[OWASP Zap Proxy](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)|A Proxy to intercept and manipulate Web Traffic (free).
|[Wireshark](https://www.wireshark.org)|Wireshark is a network protocol analyzer that lets you capture and read network packets.


### Subdomain Enumeration and DNS Resolver
| Name 	| Description 	|
|------	|-------------  |
|[Crobat](https://github.com/Cgboal/SonarSearch)|A rapid API for the Project Sonar dataset|
|[Chaos Client](https://github.com/projectdiscovery/chaos-client)|Go client to communicate with Chaos DB API.|
|[MassDNS](https://github.com/blechschmidt/massdns)|A high-performance DNS stub resolver for bulk lookups and reconnaissance (subdomain enumeration)|
|[Amass](https://github.com/OWASP/Amass)|Uses a variety of different techniques to gather subdomains and can build a network map of the target. Very good export options.|
|[Metabigor](https://github.com/j3ssie/metabigor)|Wrapper for running rustscan, masscan and nmap more efficient on IP/CIDR.|
|[Knock](https://github.com/guelfoweb/knock)|Knockpy is a portable and modular python3 tool designed to quickly enumerate subdomains on a target domain through passive reconnaissance and dictionary scan.|
|[Sublist3r](https://github.com/aboul3la/Sublist3r)|Fast subdomains enumeration tool for penetration testers.|
|[Turbolist3r](https://github.com/fleetcaptain/Turbolist3r)|Subdomain enumeration tool with analysis features for discovered domains|
|[subfinder](https://github.com/projectdiscovery/subfinder)|subfinder is a subdomain discovery tool that discovers valid subdomains for websites by using passive online sources. It has a simple modular architecture and is optimized for speed. subfinder is built for doing one thing only - passive subdomain enumeration, and it does that very well.|
|[SubBrute](https://github.com/TheRook/subbrute)|A DNS meta-query spider that enumerates DNS records, and subdomains.|
|[BruteX](https://github.com/1N3/BruteX)|Automatically brute force all services running on a target.|
|[dnsgen](https://github.com/ProjectAnte/dnsgen)|generates a combination of domain names from the provided input.|
|[Altdns](https://github.com/infosec-au/altdns)|Altdns is a DNS recon tool that allows for the discovery of subdomains that conform to patterns. Altdns takes in words that could be present in subdomains under a domain (such as test, dev, staging) as well as takes in a list of subdomains that you know of.|
|[shuffleDNS](https://github.com/projectdiscovery/shuffledns)|shuffleDNS is a wrapper around massdns, written in go, that allows you to enumerate valid subdomains using active bruteforce, as well as resolve subdomains with wildcard handling and easy input-output support.|
|[dnsx](https://github.com/projectdiscovery/dnsx)|dnsx is a fast and multi-purpose DNS toolkit allow to run multiple DNS queries of your choice with a list of user-supplied resolvers.|

### Subdomain Takeovers
| Name 	| Description   |
|------	|-------------  |
|[SubOver](https://github.com/Ice3man543/SubOver)|A Powerful Subdomain Takeover Tool|
|[Sub404](https://github.com/r3curs1v3-pr0xy/sub404)|Sub 404 is a tool written in python which is used to check possibility of subdomain takeover vulnerability and it is fast as it is asynchronous.|
|[subjack](https://github.com/haccer/subjack)|Subjack is a Subdomain Takeover tool written in Go designed to scan a list of subdomains concurrently and identify ones that are able to be hijacked. With Go's speed and efficiency, this tool really stands out when it comes to mass-testing. Always double check the results manually to rule out false positives.|

### Fuzzing
| Name 	| Description   |
|------	|-------------  |
|[FFuF](https://github.com/ffuf/ffuf)|A very fast Fuzzing Tool to brute force directories or other parameters. Highly configurable.|
|[dirsearch](https://github.com/maurosoria/dirsearch)|dirsearch is a simple command-line tool designed to brute force directories and files in websites|
|[Kiterunner](https://github.com/assetnote/kiterunner)|Contextual Content Discovery Tool|
|[IIS Short Name Scanner](https://github.com/irsdl/IIS-ShortName-Scanner)|latest version of scanners for IIS short filename (8.3) disclosure vulnerability|
|[dirb](https://github.com/v0re/dirb)|Dirb a tool created by Ramon Pinuaga, this repo it's a Sourceforge fork(Web Fuzzer)|
|[FeroxBuster](https://github.com/epi052/feroxbuster)|A simple, fast, recursive content discovery tool written in Rust|
|[ParamSpider](https://github.com/devanshbatham/ParamSpider)|Mining URLs from dark corners of Web Archives for bug hunting/fuzzing/further probing|
|[Wfuzz](https://github.com/xmendez/wfuzz)|Wfuzz has been created to facilitate the task in web applications assessments and it is based on a simple concept: it replaces any reference to the FUZZ keyword by the value of a given payload.|

### Crawling Web
| Name 	| Description   |
|------	|-------------  |
|[katana](https://github.com/projectdiscovery/katana)|A next-generation crawling and spidering framework.|
|[GoSpider](https://github.com/jaeles-project/gospider)|GoSpider - Fast web spider written in Go|
|[hakrawler](https://github.com/hakluke/hakrawler)|Simple, fast web crawler designed for easy, quick discovery of endpoints and assets within a web application|
|[LinkFinder](https://github.com/GerbenJavado/LinkFinder)|SA python script that finds endpoints in JavaScript files|
|[Robofinder](https://github.com/Spix0r/robofinder)|Robofinder retrieves historical #robots.txt files from #Archive.org, allowing you to uncover previously disallowed directories and paths for any domain—essential for deepening your #OSINT and #recon process.|


### Screenshots
| Name 	| Description   |
|------	|-------------  |
|[EyeWitness](https://github.com/RedSiege/EyeWitness)|EyeWitness is designed to take screenshots of websites provide some server header info, and identify default credentials if known.|
|[gowitness](https://github.com/sensepost/gowitness)|🔍 gowitness - a golang, web screenshot utility using Chrome Headless|
|[webscreenshot](https://github.com/maaaaz/webscreenshot)|A simple script to screenshot a list of websites, based on the url-to-image PhantomJS script.|


### Content Discovery
| Name 	| Description 	    |
|------	|-------------    	|
|[assetfinder](https://github.com/tomnomnom/assetfinder)|Find domains and subdomains related to a given domain.|
|[httpx](https://github.com/projectdiscovery/httpx)|A fast and multi-purpose HTTP toolkit that allows running multiple probes.|
|[httprobe](https://github.com/tomnomnom/httprobe)|Take a list of domains and probe for working HTTP and HTTPS servers.|
|[gau](https://github.com/lc/gau)|Fetch known URLs from AlienVault's Open Threat Exchange, the Wayback Machine, and Common Crawl.|
|[Gobuster](https://github.com/OJ/gobuster)|Directory/File, DNS and VHost busting tool written in Go.|
|[gf](https://github.com/tomnomnom/gf)|A wrapper around grep to avoid typing common patterns.|
|[waybackurls](https://github.com/tomnomnom/waybackurls)|Fetch all the URLs that the Wayback Machine knows about for a domain|
|[DirDar](https://github.com/M4DM0e/DirDar)|DirDar is a tool that searches for (403-Forbidden) directories to break it and get dir listing on it|
|[Arjun](https://github.com/s0md3v/Arjun)|HTTP parameter discovery suite.|
|[x8](https://github.com/Sh1Yo/x8)|Hidden parameters discovery suite|
|[xnLinkFinder](https://github.com/xnl-h4ck3r/xnLinkFinder)|A python tool used to discover endpoints, potential parameters, and a target specific wordlist for a given target|



### Recon Framework
| Name 	| Description 	    |
|------	|-------------    	|
|[sn1per](https://github.com/1N3/Sn1per)|Discover hidden assets and vulnerabilities in your environment.|
|[Raccoon](https://github.com/evyatarmeged/Raccoon)| A high performance offensive security tool for reconnaissance and vulnerability scanning|
|[LazyRecon](https://github.com/capt-meelo/LazyRecon)| An automated approach to performing recon for bug bounty hunting and penetration testing.|
|[Recon-ng](https://github.com/lanmaster53/recon-ng)| Recon-ng is a full-featured reconnaissance framework designed with the goal of providing a powerful environment to conduct open source web-based reconnaissance quickly and thoroughly.|

#### OSINT Search Engines
| Name 	| Description 	    |
|------	|-------------      |
|[chaos](https://chaos.projectdiscovery.io/)|A live, continuously updated API providing comprehensive internet data, including real-time DNS entries across the entire web.|
|[hunter.io](https://www.hunter.io)|Email Enumeration for big corps|
|[intelx.io](https://intelx.io/)|Swiss army Knife of OSINT|
|[Shodan](https://www.shodan.io/)|Search engine that lets you find systems connected to the internet with a variety of filters|
|[Censys](https://censys.io)|"Censys is a public search engine that enables researchers to quickly ask questions about the hosts and networks that compose the Internet."|
|[crt.sh](https://crt.sh)|SSL certificate search tool|
|[Virus Total](https://www.virustotal.com)|WHOIS, DNS, and subdomain recon|
|[ZoomEye](https://www.zoomeye.org/)|Search engine for specific network components|
|[NerdyData](https://nerdydata.com/)|Search Engine for Source Code|
|[Crunchbase](https://www.crunchbase.com/)|For finding Information about Businesses and their acquisitions|
|[Searchcode](https://searchcode.com/)|Helping you find real world examples of functions, API's and libraries over 90 languages across multiple sources|

### Vulnerability Scanner
| Name 	| Description 	    |
|------	|-------------    	|
|[sqlmap](http://sqlmap.org/)|sqlmap is an open-source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers.|
|[NoSQLMap](https://github.com/codingo/NoSQLMap)|Automated NoSQL database enumeration and web application exploitation tool.|
|[Nuclei](https://github.com/projectdiscovery/nuclei)|"Nuclei is a fast tool for configurable targeted scanning based on templates offering massive extensibility and ease of use."|
|[Nikto](https://github.com/sullo/nikto)|Nikto is an Open Source (GPL) web server scanner which performs comprehensive tests against web servers for multiple items, including over 6700 potentially dangerous files/programs, checks for outdated versions of over 1250 servers, and version specific problems on over 270 servers.|
|[XSStrike](https://github.com/s0md3v/XSStrike)|XSStrike is a Cross Site Scripting detection suite equipped with four hand written parsers, an intelligent payload generator, a powerful fuzzing engine and an incredibly fast crawler.|
|[Dalfox](https://github.com/hahwul/dalfox)|🌙🦊 Dalfox is a powerful open-source XSS scanner and utility focused on automation.|
|[Bxss](https://github.com/ethicalhackingplayground/bxss)|Blind XSS Scanner is a tool that can be used to scan for blind XSS vulnerabilities in web applications.|
|[Gxss](https://github.com/KathanP19/Gxss)|A tool to check a bunch of URLs that contain reflecting params.|
|[X-Recon](https://github.com/joshkar/X-Recon)|A utility for detecting webpage inputs and conducting XSS scans.|
|[CORScanner](https://github.com/chenjj/CORScanner)|Fast CORS misconfiguration vulnerabilities scanner.|
|[WPScan](https://github.com/wpscanteam/wpscan)|WPScan WordPress security scanner. Written for security professionals and blog maintainers to test the security of their WordPress websites.|

### Network Scanners
| Name 	| Description 	    |
|------	|-------------    	|
|[Nmap](https://nmap.org)|A well known and powerful Tool for port scanning. Nmap provides the possibility to use scripts to further customize its functionality. |
|[Masscan](https://github.com/robertdavidgraham/masscan)|This is an Internet-scale port scanner. It can scan the entire Internet in under 6 minutes, transmitting 10 million packets per second, from a single machine.|
|[ScanCannon](https://github.com/johnnyxmas/ScanCannon)|External attack surface discovery, enumeration and reconnaissance for massive networks|
|[Naabu](https://github.com/projectdiscovery/naabu)|A fast port scanner written in go with a focus on reliability and simplicity. Designed to be used in combination with other tools for attack surface discovery in bug bounties and pentests.|
|[Aquatone](https://github.com/michenriksen/aquatone)|Aquatone is a tool for visual inspection of websites across a large amount of hosts and is convenient for quickly gaining an overview of HTTP-based attack surface.|
|[RustScan](https://github.com/RustScan/RustScan)|The Modern Port Scanner. Find ports quickly (3 seconds at its fastest). Run scripts through our scripting engine (Python, Lua, Shell supported).|

### Notes & Organization
| Name 	| Description 	    |
|------	|-------------    	|
|[Notion](https://notion.so)|"Write, plan, collaborate, and get organized — all in one tool."|
|[Xmind](https://www.xmind.net/)|XMind, a full-featured mind mapping and brainstorming tool, designed to generate ideas, inspire creativity, brings productivity in a remote WFH team.|
|[Obsidian](https://obsidian.md/)|Obsidian is the private and flexible writing app that adapts to the way you think.|
|[Draw.io](https://app.diagrams.net/)|draw.io is free online diagram software for making flowcharts, process diagrams, org charts, UML, ER and network diagrams.|

### Wordlists
| Name 	| Description 	    |
|------	|-------------    	|
|[SecLists](https://github.com/danielmiessler/SecLists)|A huge collection of word lists for hacking.|
|[AssetNote's Wordlists](https://wordlists.assetnote.io/)|Collection of wordlists created by AssetNote.|
|[fuzzdb](https://github.com/fuzzdb-project/fuzzdb)|It's the first and most comprehensive open dictionary of fault injection patterns, predictable resource locations, and regex for matching server responses.|
|[samlists](https://github.com/the-xentropy/samlists)|Free, libre, effective, and data-driven wordlists for all!|
|[Jason Haddix](https://gist.github.com/jhaddix/86a06c5dc309d08580a018c66354a056)|Jason Haddix Wordlists|


### Others
| Name 	| Description 	    |
|------	|-------------    	|
|[Deduplicate](https://github.com/nytr0gen/deduplicate)|Remove duplicate urls from input|
|[Anew](https://github.com/tomnomnom/anew)|A tool for adding new lines to files, skipping duplicates|
|[unfurl](https://github.com/tomnomnom/unfurl)|Pull out bits of URLs provided on stdin|
|[WhatWeb](https://github.com/urbanadventurer/WhatWeb)|Next generation web scanner|
|[JWT Tool](https://github.com/ticarpi/jwt_tool)|A toolkit for testing, tweaking and cracking JSON Web Tokens|
|[HostHunter](https://github.com/SpiderLabs/HostHunter)|HostHunter a recon tool for discovering hostnames using OSINT techniques.|

---
