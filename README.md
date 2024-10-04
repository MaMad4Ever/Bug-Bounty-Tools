# Tools-for-Bug-Hunters

Here you can find links to a bunch of useful tools for Bug Bounty Hunting.

### Proxy & Network Sniffer
| Name 	| Description 	|
|------	|-------------	|
|[Burp Suite](https://portswigger.net/burp)|A Proxy to intercept and manipulate Web Traffic (free & paid version). [Here](/assets/setup.md#setup) you can find Tips & Tricks to get started with Burp.
|[OWASP Zap Proxy](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)|A Proxy to intercept and manipulate Web Traffic (free).
|[Wireshark](https://www.wireshark.org)|Wireshark is a network protocol analyzer that lets you capture and read network packets.


### Subdomain Enumeration and DNS Resolver
| Name 	| Description 	|
|------	|-------------  |
|[MassDNS](https://github.com/blechschmidt/massdns)|A high-performance DNS stub resolver for bulk lookups and reconnaissance (subdomain enumeration)|
|[Amass](https://github.com/OWASP/Amass)|Uses a variety of different techniques to gather subdomains and can build a network map of the target. Very good export options.|
|[Knock](https://github.com/guelfoweb/knock)|Knockpy is a portable and modular python3 tool designed to quickly enumerate subdomains on a target domain through passive reconnaissance and dictionary scan.|
|[Sublist3r](https://github.com/aboul3la/Sublist3r)|Fast subdomains enumeration tool for penetration testers.|
|[Turbolist3r](https://github.com/fleetcaptain/Turbolist3r)|Subdomain enumeration tool with analysis features for discovered domains|
|[subfinder](https://github.com/projectdiscovery/subfinder)|subfinder is a subdomain discovery tool that discovers valid subdomains for websites by using passive online sources. It has a simple modular architecture and is optimized for speed. subfinder is built for doing one thing only - passive subdomain enumeration, and it does that very well.|
|[dnsgen](https://github.com/ProjectAnte/dnsgen)|generates a combination of domain names from the provided input.|
|[dnsx](https://github.com/projectdiscovery/dnsx)|dnsx is a fast and multi-purpose DNS toolkit allow to run multiple DNS queries of your choice with a list of user-supplied resolvers.|

### Subdomain Takeovers
| Name 	| Description   |
|------	|-------------  |
|[SubOver](https://github.com/Ice3man543/SubOver)|A Powerful Subdomain Takeover Tool|
|[Sub404](https://github.com/r3curs1v3-pr0xy/sub404)|Sub 404 is a tool written in python which is used to check possibility of subdomain takeover vulnerability and it is fast as it is asynchronous.|

### Fuzzing
| Name 	| Description   |
|------	|-------------  |
|[FFuF](https://github.com/ffuf/ffuf)|A very fast Fuzzing Tool to brute force directories or other parameters. Highly configurable.|
|[dirsearch](https://github.com/maurosoria/dirsearch)|dirsearch is a simple command-line tool designed to brute force directories and files in websites|
|[FeroxBuster](https://github.com/epi052/feroxbuster)|A simple, fast, recursive content discovery tool written in Rust|
|[Wfuzz](https://github.com/xmendez/wfuzz)|Wfuzz has been created to facilitate the task in web applications assessments and it is based on a simple concept: it replaces any reference to the FUZZ keyword by the value of a given payload.|

### Crawling Web
| Name 	| Description   |
|------	|-------------  |
|[katana](https://github.com/projectdiscovery/katana)|A next-generation crawling and spidering framework.|
|[GoSpider](https://github.com/jaeles-project/gospider)|GoSpider - Fast web spider written in Go|

### Content Discovery
| Name 	| Description 	    |
|------	|-------------    	|
|[httpx](https://github.com/projectdiscovery/httpx)|A fast and multi-purpose HTTP toolkit that allows running multiple probes.|
|[httprobe](https://github.com/tomnomnom/httprobe)|Take a list of domains and probe for working HTTP and HTTPS servers.|
|[gau](https://github.com/lc/gau)|Fetch known URLs from AlienVault's Open Threat Exchange, the Wayback Machine, and Common Crawl.|
|[gf](https://github.com/tomnomnom/gf)|A wrapper around grep to avoid typing common patterns.|
|[waybackurls](https://github.com/tomnomnom/waybackurls)|Fetch all the URLs that the Wayback Machine knows about for a domain|

### Recon Framework
| Name 	| Description 	    |
|------	|-------------    	|
|[sn1per](https://github.com/1N3/Sn1per)|Discover hidden assets and vulnerabilities in your environment.|
|[Raccoon](https://github.com/evyatarmeged/Raccoon)| A high performance offensive security tool for reconnaissance and vulnerability scanning|
|[LazyRecon](https://github.com/capt-meelo/LazyRecon)| An automated approach to performing recon for bug bounty hunting and penetration testing.|

#### OSINT Search Engines
| Name 	| Description 	    |
|------	|-------------      |
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

### Vulnerability Scanner:
| Name 	| Description 	    |
|------	|-------------    	|
|[sqlmap](http://sqlmap.org/)|sqlmap is an open-source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers.|
|[NoSQLMap](https://github.com/codingo/NoSQLMap)|Automated NoSQL database enumeration and web application exploitation tool.|
|[Nuclei](https://github.com/projectdiscovery/nuclei)|"Nuclei is a fast tool for configurable targeted scanning based on templates offering massive extensibility and ease of use."|
|[XSStrike](https://github.com/s0md3v/XSStrike)|XSStrike is a Cross Site Scripting detection suite equipped with four hand written parsers, an intelligent payload generator, a powerful fuzzing engine and an incredibly fast crawler.|
|[X-Recon](https://github.com/joshkar/X-Recon)|A utility for detecting webpage inputs and conducting XSS scans.|
|[WPScan](https://github.com/wpscanteam/wpscan)|WPScan WordPress security scanner. Written for security professionals and blog maintainers to test the security of their WordPress websites.|

### Network Scanners
| Name 	| Description 	    |
|------	|-------------    	|
|[Nmap](https://nmap.org)|A well known and powerful Tool for port scanning. Nmap provides the possibility to use scripts to further customize its functionality. |
|[Masscan](https://github.com/robertdavidgraham/masscan)|This is an Internet-scale port scanner. It can scan the entire Internet in under 6 minutes, transmitting 10 million packets per second, from a single machine.|
|[Naabu](https://github.com/projectdiscovery/naabu)|A fast port scanner written in go with a focus on reliability and simplicity. Designed to be used in combination with other tools for attack surface discovery in bug bounties and pentests.|

### Notes & Organization
| Name 	| Description 	    |
|------	|-------------    	|
|[Notion](https://notion.so)|"Write, plan, collaborate, and get organized — all in one tool."|
|[Xmind](https://www.xmind.net/)|XMind, a full-featured mind mapping and brainstorming tool, designed to generate ideas, inspire creativity, brings productivity in a remote WFH team.|
|[Obsidian](https://obsidian.md/)|Obsidian is the private and flexible writing app that adapts to the way you think.|

### Wordlists
| Name 	| Description 	    |
|------	|-------------    	|
|[SecLists](https://github.com/danielmiessler/SecLists)|A huge collection of word lists for hacking.|
|[AssetNote's Wordlists](https://wordlists.assetnote.io/)| Collection of wordlists created by AssetNote.|

---
