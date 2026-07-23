# Security & OSINT Resources

A curated, categorized set of tools for infrastructure defense, threat intelligence, malware analysis, code security, and open-source intelligence research. Links are periodically checked for availability.

## Table of Contents
1. [Network & Infrastructure Defense](#network--infrastructure-defense)
2. [Domain, DNS & Web Reconnaissance](#domain-dns--web-reconnaissance)
3. [Threat Intelligence & OSINT Frameworks](#threat-intelligence--osint-frameworks)
4. [Malware Analysis & Sandboxing](#malware-analysis--sandboxing)
5. [Web Application & Code Security](#web-application--code-security)
6. [Endpoint Visibility, Incident Response & Password Recovery](#endpoint-visibility-incident-response--password-recovery)
7. [Identity & Account OSINT](#identity--account-osint)
8. [Data Breach & Credential Exposure Monitoring](#data-breach--credential-exposure-monitoring)
9. [Privacy, Anonymity & Secure Communication](#privacy-anonymity--secure-communication)
10. [Open Data, File & Dataset Discovery](#open-data-file--dataset-discovery)
11. [Public Records, Legal & Government Transparency](#public-records-legal--government-transparency)
12. [Geolocation & Financial Tracing](#geolocation--financial-tracing)
13. [Research Utilities & Ephemeral Infrastructure](#research-utilities--ephemeral-infrastructure)
14. [Sandboxing & Virtual Environments](#sandboxing--virtual-environments)
15. [Synthetic Test Data Generation (QA/Dev)](#synthetic-test-data-generation-qadev)
16. [Automation, Scripting & Utilities](#automation-scripting--utilities)

---

### Network & Infrastructure Defense
* [Nmap](https://nmap.org/): Network discovery and port scanning utility.
* [Wireshark](https://www.wireshark.org/): Packet capture and protocol analysis tool.
* [Snort](https://www.snort.org/): Network intrusion detection system.
* [OpenVAS Scanner](https://www.openvas.org/): Open-source vulnerability scanning.
* [Shodan](https://www.shodan.io/): Search engine for Internet-connected devices and infrastructure.
* [Censys](https://censys.io/): Attack surface discovery and internet-wide scan data repository.
* [Netcraft](http://www.netcraft.com/): Internet research and anti-phishing data provider.
* [Proxmark3](http://hackerwarehouse.com/product/proxmark3-rdv2-kit/): Hardware tool for RFID cloning and physical security auditing.
* [Boscloner](http://www.boscloner.com/): RFID cloning and badge capturing utility.

### Domain, DNS & Web Reconnaissance
* [domainbigdata](https://domainbigdata.com/): Historical WHOIS, DNS, and domain-ownership correlation lookup.
* [dnslytics](https://dnslytics.com/): Reverse IP, hosting, and DNS infrastructure lookup.
* [SecurityTrails](https://securitytrails.com/): Historical and passive DNS data platform for domain research.
* [Internetdb.shodan.io](https://internetdb.shodan.io/): Shodan's free bulk IP-to-open-ports/vulnerability lookup API.
* [GreyNoise Intelligence](https://www.greynoise.io/viz/): Distinguishes internet background scanner noise from targeted attack traffic.
* [FOFA](https://fofa.so/): Cyberspace search engine for internet-facing assets and services.
* [zoomeye](https://www.zoomeye.org/): Cyberspace search engine indexing internet-connected devices and web services.
* [ViewDNS.info](https://viewdns.info/): Collection of DNS, WHOIS, and IP lookup utilities.
* [ONYPHE](https://www.onyphe.io/): Cyber-defense search engine indexing internet-wide scan and passive DNS data.
* [IPLeak](https://ipleak.net/): Checks a browser/VPN connection for IP, DNS, and WebRTC leaks.
* [Robtex](https://www.robtex.com/): DNS, routing, and IP-address relationship lookup tool.
* [Website search tool](https://www.aware-online.com/en/osint-tools/website-search-tool/): Guide/tool for general website reconnaissance.
* [Wappalyzer](https://www.wappalyzer.com/lookup/): Identifies the technology stack behind a website.
* [photon](https://pypi.org/project/photon/): Fast, lightweight Python web crawler for OSINT and recon.
* [Technology Lookup](https://osint.sh/stack/): Identifies web technologies used by a target site.
* [BuiltWith Technology Lookup](https://builtwith.com/): Website technology profiler.
* [NMAP Online](https://osint.sh/nmap/): Browser-based Nmap port-scan utility.
* [Nmap Checker Tool](https://shadowcrypt.net/tools/nmap): Web-based Nmap scan wrapper.
* [Free online network tools](https://centralops.net/co/): Suite of WHOIS, DNS, ping, and traceroute utilities.
* [Google Transparency Report](https://transparencyreport.google.com/https/certificates): Google's certificate transparency log search.
* [Certificate Search](https://osint.sh/crt/): TLS certificate transparency lookup.
* [CRT](https://crt.sh/): crt.sh certificate transparency log search engine.
* [LeakIX](https://leakix.net/): Search engine for exposed services, misconfigurations, and leaked data.
* [DomainWatch](https://domainwat.ch/): Domain and DNS record change monitoring/history tool.
* [URL and website scanner](https://urlscan.io/): Sandboxed scanner for analyzing and visualizing website behavior.
* [dnsdumpster](https://dnsdumpster.com/): Free DNS reconnaissance and subdomain discovery tool.
* [SimilarWeb](https://www.similarweb.com/): Website traffic and analytics estimation tool.
* [Website Information](https://one-plus.github.io/WebsiteInformation): Aggregated OSINT lookup for a given domain.
* [IP search - Network Entity Reputation Database](https://nerd.cesnet.cz/nerd/ips/): Passive-DNS/IP reputation lookup from CESNET.
* [Reverse Domain](https://osint.sh/domain/): Reverse WHOIS/domain lookup tool.
* [Poodle Check](https://osint.sh/poodle/): Tests a server for the POODLE SSL vulnerability.
* [Heartbleed Check](https://osint.sh/heartbleed/): Tests a server for the Heartbleed OpenSSL vulnerability.
* [DNS History Lookup](https://osint.sh/dnshistory/): Historical DNS record lookup tool.
* [Subdomain Finder](https://osint.sh/subdomain/): Subdomain enumeration tool.
* [Reverse IP Lookup](https://osint.sh/reverseip/): Finds other domains hosted on the same IP.
* [Reverse Google Adsense](https://osint.sh/adsense/): Finds other sites sharing the same Google AdSense ID.
* [Reverse Google Analytics](https://osint.sh/analytics/): Finds other sites sharing the same Google Analytics ID.
* [Reverse MX Record](https://osint.sh/reversemx/): Finds domains sharing the same mail server.
* [IP GEO Location Lookup](https://osint.sh/ip/): Geolocates an IP address.
* [IANA â€” Root Zone Database](https://www.iana.org/domains/root/db): Authoritative registry of top-level domains.
* [Punkspider](https://punkspider.org/): Continuously scanning search engine for web app vulnerabilities.
* [metabigor](https://github.com/j3ssie/metabigor): OSINT recon automation tool that works without API keys.
* [WHOIS Service](https://whoismind.com/): Domain WHOIS lookup service.
* [Whois Search](https://webwhois.verisign.com/webwhois-ui/index.jsp?language=en_US): Official Verisign WHOIS lookup for .com/.net domains.
* [Who.is](https://who.is/): Domain WHOIS and website info lookup.
* [Whoxy](https://www.whoxy.com/): WHOIS API and historical/reverse WHOIS lookup service.
* [Whois History](https://osint.sh/whoishistory/): Historical WHOIS record lookup.
* [Google Dork Cheatsheet](https://github.com/robyfirnandoyusuf/Google-Dork-Cheatsheet): Reference list of Google dork search operators.
* [metagoofil](https://github.com/opsdisk/metagoofil): Extracts metadata from public documents found via search engines.
* [webdork](https://github.com/HACKE-RC/webdork): Automated Google dorking / vulnerability discovery tool.
* [ATSCAN](https://github.com/AlisamTechnology/ATSCAN): Multi-engine dork scanner for server, site, and vulnerability discovery.
* [pagodo](https://github.com/opsdisk/pagodo): Automates Google Hacking Database dork queries against a target domain.

### Threat Intelligence & OSINT Frameworks
* [MISP](https://www.misp-project.org/): Open-source threat intelligence platform for sharing IoCs.
* [OpenCTI](https://github.com/OpenCTI-Platform/opencti): Threat intelligence management and knowledge mapping.
* [AlienVault OTX](https://otx.alienvault.com/): Open threat exchange platform for community-driven threat data.
* [ThreatConnect](https://www.threatconnect.com/): Enterprise threat intelligence platform for aggregating and acting on threat data.
* [PassiveTotal](https://www.google.com/search?q=https://www.passivetotal.org/): Infrastructure threat intelligence and passive DNS analysis.
* [Malware-Traffic-Analysis.net](http://malware-traffic-analysis.net/): Resource for analyzing pcap files and exploit kit traffic.
* [VirusShare](https://virusshare.com/): Repository for accessing and researching malware samples.
* [VX Vault](http://vxvault.net/ViriList.php): Tracking and database for malicious downloads and malware variants.
* [DomainTools](https://whois.domaintools.com/): DNS research, IP address history, and Whois lookup utility.
* [Cyberthreat Real-Time Map](https://cybermap.kaspersky.com/): Live global cyberattack visualization (Kaspersky).
* [Live Cyber Attack Threat Map](https://www.checkpoint.com/ThreatPortal/livemap.html): Real-time visualization of detected global cyberattacks (Check Point).
* [Digital Attack Map](https://www.digitalattackmap.com/): Live DDoS attack visualization built on Arbor Networks data.
* [Cyber Threat Map](https://www.fireeye.com/cyber-map/threat-map.html): Real-time visualization of tracked cyberattacks (FireEye).
* [Bitdefender Threat Map](https://threatmap.bitdefender.com/): Live global malware and attack visualization.
* [Cyber Threat Intelligence](https://pulsedive.com/): Free threat intelligence lookup and IOC enrichment platform.
* [Cisco Talos Intelligence Group](https://talosintelligence.com/): Threat intelligence research and reputation lookup.
* [Fortinet Threat Map](https://threatmap.fortiguard.com/): Live visualization of Fortinet-observed global threats.
* [FortiGuard](http://www.fortiguard.com/): Fortinet's threat intelligence and security services portal.
* [ThreatMiner](https://www.threatminer.org/): Threat intelligence data-mining and IOC lookup platform.
* [intelowlproject/IntelOwl](https://github.com/intelowlproject/IntelOwl): Open-source platform for automating IOC/threat intel analysis.
* [NETSCOUT Cyber Threat Horizon](https://horizon.netscout.com/): Live global DDoS attack visualization.
* [APTnotes](https://github.com/aptnotes/data): Archive of publicly released APT threat reports and attribution research.
* [OH SHINT! Welcome Aboard](https://ohshint.gitbook.io/): OSINT blog and curated resource collection.
* [sinwindie/OSINT](https://github.com/sinwindie/OSINT): GitHub-hosted OSINT tool and resource list.
* [OSINT Framework](https://osintframework.com/): Interactive tree of categorized OSINT tools and techniques.
* [jivoi/awesome-osint](https://github.com/jivoi/awesome-osint): Curated GitHub list of OSINT tools.
* [OSINT Tools](https://www.osinttechniques.com/osint-tools.html): Directory of OSINT tools by category.
* [OSINT tools for investigating websites](https://www.aware-online.com/en/osint-tools/website-tools/): Guide to website-investigation OSINT tools.
* [Shodan Cheat Sheet](https://thedarksource.com/shodan-cheat-sheet/): Reference guide for Shodan search syntax and dorks.
* [Week in OSINT](https://sector035.nl/articles/category:week-in-osint): Recurring roundup of new OSINT tools and techniques.
* [QueryTool](https://github.com/oryon-osint/querytool): OSINT query-building and lookup utility.
* [Investigating the source code of a website](https://www.aware-online.com/en/osint-tutorials/investigating-the-source-code-of-a-website/): Tutorial on OSINT via page-source inspection.
* [Find open FTP Servers](https://www.aware-online.com/en/osint-tutorials/find-open-ftp-servers/): Tutorial on discovering exposed FTP servers.
* [Webint Master](https://webintmaster.com/): OSINT blog and tool directory.
* [DFIR Diva](https://dfirdiva.com/hooked-on-osint/): Digital forensics and incident response OSINT resource blog.
* [Boolean Strings | Tools](https://booleanstrings.com/tools/): Directory of X-ray/boolean search OSINT tools.
* [osintme.com](https://www.osintme.com/): OSINT techniques and tool review blog.
* [Jake Creps](https://jakecreps.com/): OSINT researcher's blog and training resources.
* [reKnowledge](https://www.reknowledge.tech/): OSINT and threat intelligence blog.
* [@Ivan30394639 OSINT tools collection](https://cipher387.github.io/osint_stuff_tool_collection/): Large curated list of OSINT tools.
* [The Top 132 Osint Open Source Projects](https://awesomeopensource.com/projects/osint): Aggregated ranking of open-source OSINT projects.
* [Awesome Deblurring](https://github.com/subeeshvasu/Awesome-Deblurring): Curated list of image deblurring/deconvolution research and tools.
* [OSINT.SH](https://osint.sh/): Suite of free OSINT lookup utilities (DNS, IP, certs, etc.).
* [OSINT Techniques](https://www.osinttechniques.com/): Blog covering OSINT methodology and tools.
* [Ph055a OSINT_Collection](https://github.com/Ph055a/OSINT_Collection): GitHub-hosted OSINT tool collection.
* [MetaOSINT](https://metaosint.github.io/): Curated directory of OSINT tools by category.
* [Osint.support](https://osint.support/): OSINT tutorials, Chrome extensions, and technique write-ups.

### Malware Analysis & Sandboxing
* [YARA](https://virustotal.github.io/yara/): Malware identification and rule matching.
* [Ghidra](https://ghidra-sre.org/): Software reverse engineering framework.
* [VirusTotal](https://www.virustotal.com/): Online scanner utilizing multiple antivirus engines to analyze files and URLs.
* [Hybrid-Analysis](https://www.hybrid-analysis.com/): Automated malware analysis powered by VxStream Sandbox.
* [Malwr](https://www.google.com/search?q=https://malwr.com/): Free malware analysis service utilizing Cuckoo Sandbox.
* [Valkyrie](https://valkyrie.comodo.com/): Advanced file analysis and verdict system.
* [Metadefender](https://www.google.com/search?q=https://www.metadefender.com/%23!/scan-file): Free file scanning utilizing multiple antivirus engines.
* [Malpedia](https://malpedia.caad.fkie.fraunhofer.de/): Free, curated malware family reference and classification database.
* [Interactive Online Malware Analysis Sandbox](https://app.any.run/): Interactive sandbox for detonating and observing live malware behavior.
* [Maltiverse](https://maltiverse.com/search): Threat intelligence platform for aggregating and searching IOCs.
* [Jotti's malware scan](https://virusscan.jotti.org/): Free multi-engine file scanning service.
* [theZoo](https://github.com/ytisf/theZoo): Live malware sample repository for research purposes.
* [exploit-database-papers](https://github.com/offensive-security/exploitdb-papers): Archive of Exploit-DB's technical whitepapers.
* [exploitdb-bin-sploits](https://github.com/offensive-security/exploitdb-bin-sploits): Binary exploit-file archive from Exploit-DB.

### Web Application & Code Security
* [OWASP ZAP](https://www.zaproxy.org/): Automated web application and API security testing.
* [Burp Community](https://portswigger.net/burp/communitydownload): Manual web security testing and proxying.
* [Gitleaks](https://github.com/gitleaks/gitleaks): Static analysis for detecting secrets and API keys in repositories.
* [Semgrep CE](https://semgrep.dev/): Static Application Security Testing for code pattern matching.
* [Checkov](https://www.checkov.io/): Static code analysis for Infrastructure-as-Code misconfigurations.
* [Exploit-DB](https://www.exploit-db.com/): Offensive Security's exploit and vulnerability database.
* [GHDB](https://www.exploit-db.com/google-hacking-database/): The Google Hacking Database.
* [Sucuri SiteCheck](https://sitecheck.sucuri.net/): Free website malware and security scanner.
* [Source Code Search Engine](https://publicwww.com/): Searches source code of web pages across the internet.
* [Grep.app](https://grep.app/): Full-text code search across public GitHub repositories.
* [NerdyData](https://www.nerdydata.com/): Source code search engine for sites using specific code snippets/libraries.
* [GitHub Code Search](https://github.com/search): Native GitHub code search across public repositories.
* [Bitbucket Repo Search](https://bitbucket.org/repo/all/): Search across public Bitbucket repositories.
* [Shhgit](https://github.com/eth0izzle/shhgit): Real-time scanner for secrets and credentials committed to GitHub.
* [git-hound](https://github.com/tillson/git-hound): Finds exposed secrets in GitHub repos and gists.
* [Webfinery | Source Code Search](https://webfinery.com/search): Source code and website search engine.
* [Online IDE and Paste Search Engine](https://redhuntlabs.com/online-ide-search): Searches public paste sites and online IDEs for leaked code/secrets.
* [searchcode](https://searchcode.com/): Source code search engine across many code hosts.
* [Sourcegraph](https://about.sourcegraph.com/): Universal code search and navigation platform.
* [Awesome Open Source](https://awesomeopensource.com/): Directory/index of open-source GitHub projects by category.
* [Zen](https://github.com/s0md3v/Zen): Automated GitHub secrets/dork scanning tool.
* [GitDorker](https://github.com/obheda12/GitDorker): Automates GitHub dorking to find exposed secrets and sensitive files.

### Endpoint Visibility, Incident Response & Password Recovery
* [osquery](https://osquery.io/): Endpoint visibility and monitoring using SQL queries.
* [Falco](https://falco.org/): Cloud-native runtime threat detection for containers and hosts.
* [Velociraptor](https://docs.velociraptor.app/): Digital Forensics and Incident Response collection and live response.
* [Metasploit](https://www.metasploit.com/): Exploit validation and penetration testing framework.
* [Hashcat](https://hashcat.net/hashcat/): Advanced password recovery and cryptographic audit utility.
* [CrackStation](https://crackstation.net): Free hash-lookup/rainbow-table password recovery service.
* [Hashmob Community](https://hashmob.net/search): Community hash-cracking collaboration platform.
* [Hashes.com](https://hashes.com/en/decrypt/hash): Hash identification and crowd-sourced cracking service.
* [Online Password Hash Crack](https://www.onlinehashcrack.com/): Free online hash-cracking utility for common algorithms.
* [Md5 Decrypt & Encrypt](https://md5decrypt.net/en/): MD5 hash lookup/reverse-lookup database.
* [MD5 reverse lookup](https://md5.gromweb.com/): MD5 hash reverse-lookup database.
* [Ultimate Hashing](https://md5hashing.net/): Hash generation and lookup utility.

### Identity & Account OSINT
* [WhatsMyName Web](https://whatsmyname.app/): Checks username existence across hundreds of sites.
* [maigret](https://pypi.org/project/maigret/): Collects a person's account info across many sites by username.
* [sherlock](https://github.com/sherlock-project/sherlock): Command-line tool for hunting usernames across social networks.
* [socialscan](https://pypi.org/project/socialscan/): Checks email/username availability across platforms without triggering notifications.
* [socid-extractor](https://pypi.org/project/socid-extractor/): Extracts identifiers (IDs, tokens) from social media profile pages.
* [social-analyzer](https://pypi.org/project/social-analyzer/): Finds a person's profiles across social networks and platforms.
* [snoop](https://github.com/snooppr/snoop): Username search across a large number of sites.
* [quidam](https://pypi.org/project/quidam/): Aggregates public info tied to a username/profile.
* [Epieos Email Lookup](https://epieos.com/): Finds accounts and public info linked to an email address.
* [holehe](https://pypi.org/project/holehe/): Checks if an email address is registered on numerous websites.
* [email2phonenumber](https://github.com/martinvigo/email2phonenumber): OSINT tool to recover a phone number associated with an email/account.
* [Trumail](https://trumail.io/): Email address validation and deliverability-checking API.
* [Email Verifier](https://hunter.io/email-verifier): Verifies whether an email address is valid and deliverable.
* [Verify Email](https://verify-email.org/): Free email-address validity checker.
* [Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx): Parses and analyzes email headers for routing/authentication info.
* [Proofy](https://proofy.io/): Bulk email verification and validation service.
* [Email Permutator](http://metricsparrow.com/toolkit/email-permutator/): Generates likely email address formats for a name/domain.
* [Phonebook.cz](https://phonebook.cz/): Finds email addresses, subdomains, and URLs tied to a domain.
* [Emailrep.io](https://emailrep.io/): Reputation and risk-scoring lookup for email addresses.
* [EmailHarvester](https://pypi.org/project/EmailHarvester/): Harvests email addresses tied to a domain from search engines.
* [h8mail](https://pypi.org/project/h8mail/): Email OSINT and breach-hunting tool for password leaks.
* [WhatBreach](https://github.com/Ekultek/WhatBreach): Finds which data breaches an email address appears in.
* [buster](https://github.com/sham00n/buster): Gathers info tied to an email address (social profiles, breaches, domains).
* [ProtOSINT](https://github.com/pixelbubble/ProtOSINT): Investigates Gmail/Google accounts and associated info.
* [GHunt](https://github.com/mxrch/GHunt): OSINT tool for investigating Google accounts (Gmail, Maps reviews, etc.) via email.

### Data Breach & Credential Exposure Monitoring
* [Have I been pwned](https://haveibeenpwned.com/): Checks whether an email/account appears in known data breaches.
* [Intelligence X](https://intelx.io/): Search engine for leaked data, darknet content, and document archives.

### Privacy, Anonymity & Secure Communication
* [Privacy Services by Michael Bazzell](https://inteltechniques.com/workbook.html): Personal data-removal and privacy-hardening workbook/guide.
* [Privacy Guides](https://privacyguides.org/): Independent, community-run directory of privacy-respecting software/services.
* [Surveillance Self-Defense](https://ssd.eff.org/): EFF's guide to protecting against surveillance.
* [gofoss.net](https://gofoss.net/): Directory of free/open-source privacy-respecting software alternatives.
* [Consumer Reports Security Planner](https://securityplanner.consumerreports.org/): Personalized digital security recommendation tool.
* [Security in a Box](https://securityinabox.org/en/): Digital security guide for at-risk users and activists.
* [Counter-OSINT guide for Russians](https://github.com/soxoj/counter-osint-guide-ru): Guide to reducing one's own OSINT/doxxing exposure.
* [PRISM Break](https://prism-break.org/en/): Directory of alternatives to mass-surveillance-prone services.
* [Metacleaner.com](https://metacleaner.com/): Strips metadata from uploaded files/images.
* [Image Scrubber](https://everestpipkin.github.io/image-scrubber/): Removes EXIF metadata and blurs faces in photos before sharing.
* [View Exif data online, remove Exif online](http://www.verexif.com/en/): Views and strips EXIF metadata from images.
* [StegOnline](https://stegonline.georgeom.net/upload): Browser-based steganography encode/decode tool.
* [Signal](https://signal.org/): End-to-end encrypted messaging and calling app.
* [Element](https://element.io/): Encrypted messaging client for the Matrix protocol.
* [Briar](https://briarproject.org/): Peer-to-peer encrypted messaging app that works offline/over Tor.
* [Jami.net](https://jami.net/): Distributed, end-to-end encrypted messaging and calling platform.
* [Jitsi Meet](https://meet.jit.si/): Free, open-source encrypted video conferencing.
* [Rocket.Chat](https://rocket.chat/): Open-source, self-hostable team chat platform.
* [Wire](https://wire.com/en/): End-to-end encrypted messaging and collaboration platform.
* [Telegram](https://www.telegram.org/): Cloud-based messaging app with optional encrypted chats.
* [Brave Talk](https://talk.brave.com/): Privacy-focused video conferencing built into Brave browser.
* [The Tor Project](https://www.torproject.org/download/): Free software for anonymous browsing over the Tor network.
* [Brave Browser](https://brave.com/): Privacy-focused browser with built-in tracker/ad blocking.
* [Psiphon](https://www.psiphon.ca/): Circumvention tool for bypassing internet censorship.
* [ProtonVPN](https://protonvpn.com/): No-logs VPN service from the makers of Proton Mail.
* [hide.me VPN](https://hide.me/en/): Commercial VPN service.
* [AdGuard VPN](https://adguard-vpn.com/en/welcome.html): VPN service from the AdGuard team.
* [I2P](https://geti2p.net/en/download): Anonymizing network layer for censorship-resistant communication.
* [VPN Services](https://privacyguides.org/providers/vpn/): Curated comparison of recommended VPN providers.
* [Browser Recommendations](https://privacyguides.org/browsers/): Curated list of privacy-respecting browsers.
* [Getsession.org](https://getsession.org/): Decentralized, metadata-resistant encrypted messenger.

### Open Data, File & Dataset Discovery
* [Open Directory Finder](https://odfinder.github.io/): Finds open/exposed web directories via search engines.
* [Filetype search tool](https://www.aware-online.com/en/osint-tools/filetype-search-tool/): Guide/tool for filetype-specific search dorking.
* [Opendirsearch.abifog.com](https://opendirsearch.abifog.com/): Open directory search engine.
* [Archive-it.org](https://archive-it.org/): Web archiving service for institutions and researchers.
* [Odcrawler.xyz](https://odcrawler.xyz/): Crawls and indexes open directories.
* [Document Search](https://one-plus.github.io/DocumentSearch): Aggregated search across document-hosting platforms.
* [FONETASK](http://fonetask.com/): Small web utility tool (see link for current functionality).
* [Web archive search tool](https://www.aware-online.com/osint-tools/web-archive-search-tool/): Guide to searching web archives for OSINT.
* [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets): Curated GitHub list of public datasets by topic.
* [Drivesearch.kwebpia.net](http://drivesearch.kwebpia.net/): Searches publicly shared cloud drive files.
* [Filechef.com](https://www.filechef.com/): Open directory/file search engine.
* [Mamont's open FTP Index](https://www.mmnt.net/): Index of publicly accessible open FTP servers.
* [Direct Download Almost Anything](https://ewasion.github.io/opendirectory-finder/): Open directory search/crawler tool.
* [Datasetsearch.research.google.com](https://datasetsearch.research.google.com/): Google's dataset search engine.
* [Kaggle](https://www.kaggle.com/search?q=): Data science community platform with searchable public datasets.
* [Data.gov](https://www.data.gov/): US federal government's open data portal.
* [data.world](https://data.world/): Collaborative open-data hosting and search platform.
* [BigQuery public datasets](https://cloud.google.com/bigquery/public-data/): Google Cloud's collection of publicly queryable datasets.
* [DSC Data Science Search Engine](https://www.datasciencecentral.com/page/search): Search engine for data-science articles and resources.
* [Datasetlist.com](https://www.datasetlist.com/): Curated directory of machine-learning datasets.
* [OpenData by Socrata](https://opendata.socrata.com/): Government/civic open-data hosting platform.
* [Opensanctions.org](https://opensanctions.org/): Open database of sanctioned entities, PEPs, and watchlists.
* [FiveThirtyEight](https://fivethirtyeight.com/?s=): Data journalism site with searchable public datasets.

### Public Records, Legal & Government Transparency
* [MuckRock](https://www.muckrock.com/): FOIA request filing and public-records archive platform.
* [CourtListener](https://www.courtlistener.com/): Free searchable database of US court opinions and dockets.
* [Public Access to Court Electronic Records](https://pacer.uscourts.gov/): Official US federal court records access (PACER).
* [Canadian Legal Information Institute](https://www.canlii.org/en/): Free searchable database of Canadian case law and legislation.
* [LittleSis](https://littlesis.org/): Database mapping relationships between powerful people and organizations.
* [Nonprofit Explorer](https://projects.propublica.org/nonprofits/): Searchable database of US nonprofit tax filings (ProPublica).
* [EFF Atlas of Surveillance](https://atlasofsurveillance.org/): Database documenting police surveillance technology use in the US.

### Geolocation & Financial Tracing
* [Mapillary](https://www.mapillary.com/app/): Crowd-sourced street-level imagery platform.
* [OpenStreetMap](https://www.openstreetmap.org/): Free, editable, crowd-sourced world map.
* [GeoNames](https://www.geonames.org/): Free geographical database of place names and coordinates.
* [Earth Engine Dataset](https://developers.google.com/earth-engine/datasets/): Google's catalog of public geospatial/satellite datasets.
* [Bitcoin Explorer](https://blockchair.com/bitcoin): Multi-chain blockchain explorer and search engine.
* [Ethereum Block Explorer](https://etherscan.io/): Explorer for Ethereum transactions, addresses, and contracts.
* [Blockchain Explorer](https://www.blockchain.com/explorer): Explorer for Bitcoin and other blockchain transactions.
* [Blockcypher](https://live.blockcypher.com/): Blockchain explorer and API for Bitcoin and other chains.

### Research Utilities & Ephemeral Infrastructure
* [unfurl](https://dfir.blog/unfurl/): Visualizes what can be extracted from a URL (timestamps, IDs, etc.) for OSINT.
* [Wolfram Alpha](https://www.wolframalpha.com/): Computational knowledge engine.
* [Cryptpad.fr](https://cryptpad.fr/): End-to-end encrypted, collaborative office suite.
* [MindMup 2](https://app.mindmup.com/map/new): Free online mind-mapping tool.
* [Dotspotter](https://www.forensicdots.de/): Forensic tool for matching printer/scanner tracking dots.
* [Encrypted Pastebin](https://defuse.ca/pastebin.htm): Client-side encrypted paste-sharing tool.
* [PrivateBin](https://privatebin.net/): Minimalist, encrypted, self-destructing pastebin.
* [Bin.disroot.org](https://bin.disroot.org/): Disroot's hosted PrivateBin instance.
* [Framadrop](https://framadrop.org/en/): Encrypted, self-destructing file-sharing service.
* [Pad.riseup.net](https://pad.riseup.net/): Riseup's hosted collaborative text-editing pad.
* [EtherCalc](https://ethercalc.net/): Collaborative, real-time online spreadsheet.
* [Proofread Bot](https://proofreadbot.com/): Automated grammar and proofreading checker.
* [Write.as](https://write.as/): Minimalist, privacy-focused blogging/writing platform.
* [Cryptee](https://crypt.ee/): Encrypted document and photo storage/editor.
* [dudle](https://dudle.inf.tu-dresden.de/anonymous/): Anonymous online scheduling/polling tool.
* [Airborn.io](https://www.airborn.io/): Lightweight web-based productivity utility (see link for current functionality).
* [ZOOM URL Generator](https://skyzh.github.io/zoom-url-generator/): Generates/formats Zoom meeting join links.
* [Tor2web](https://www.tor2web.org/): Gateway for accessing Tor .onion sites from a regular browser.
* [archive.is](https://archive.is/): Web page archiving and snapshot service.
* [Wayback Machine](https://web.archive.org/): Internet Archive's historical web page snapshot service.
* [waybackpy](https://pypi.org/project/waybackpy/): Python API/CLI wrapper for the Wayback Machine.
* [CachedPages](http://www.cachedpages.com/): Retrieves cached versions of web pages.
* [Google Cached Pages of Any Website](https://cachedview.com/): Tool for viewing cached versions of pages.
* [Oldweb.today](http://oldweb.today/): Emulates old browsers to view archived web pages as originally rendered.
* [Unpaywall](https://unpaywall.org/products/extension): Browser extension that finds free, legal full-text versions of paywalled papers.
* [DeepL](https://www.deepl.com/translator): Neural machine translation service.
* [Project CSV](https://projectcsv.github.io/): Browser-based CSV viewing/editing tool.
* [CSV to HTML](https://codepen.io/RYJASM/pen/LVEWgV): Converts CSV data into an HTML table.
* [Monaco Editor](https://microsoft.github.io/monaco-editor/playground.html): VS Code's underlying browser-based code editor, in playground form.
* [Online FlowChart Editor](https://mermaid-js.github.io/mermaid-live-editor/): Live editor for Mermaid diagram syntax.
* [Markdown Editor](https://markdown-editor.github.io/): Browser-based Markdown editor/previewer.
* [SQL Editor](https://www.mycompiler.io/new/sql): Browser-based SQL query runner/sandbox.
* [SQLite Viewer](https://inloop.github.io/sqlite-viewer/): Browser-based SQLite database file viewer.
* [OCR Text Extractor](https://osint.sh/ocr/): Extracts text from images via OCR.
* [Tophonetics.com](https://tophonetics.com/): IPA phonetic transcription tool for English.
* [Google Translate](https://translate.google.com/): Machine translation service.
* [Multi Translate](https://translate.mix.pink/): Simultaneous multi-engine translation comparison tool.
* [Yandex.Translate](https://translate.yandex.com/): Yandex's machine translation service.
* [Bing Microsoft Translator](https://www.bing.com/translator): Microsoft's machine translation service.
* [Reverso](https://www.reverso.net/text_translation.aspx?lang=EN): Translation and contextual usage-example tool.
* [Translate](https://www.translatedict.com/): Free online translation tool.
* [text to speech online](https://www.naturalreaders.com/online/): Converts text to spoken audio.
* [TTSReader](https://ttsreader.com/): Free browser-based text-to-speech reader.
* [Online Sequencer](https://onlinesequencer.net/): Browser-based music sequencer/composer.
* [FetchRSS](https://fetchrss.com/): Generates RSS feeds for sites that lack one.
* [arXiv.org](https://arxiv.org/): Open-access preprint repository for physics, math, CS, and related fields.
* [bioRxiv.org](https://www.biorxiv.org/): Open-access preprint repository for biology.
* [Project Gutenberg](https://www.gutenberg.org/): Free library of public-domain e-books.
* [MEGA](https://mega.io/): End-to-end encrypted cloud storage and file-sharing service.
* [transfer.sh](https://transfer.sh/): Simple, command-line-friendly temporary file-hosting service.
* [Upload | Disroot](https://disroot.org/en/services/upload): Disroot's file-upload/sharing service.
* [Chibisafe.moe](https://chibisafe.moe/): Self-hostable file-upload/sharing service.
* [Send](https://send.actionsack.com/): Encrypted, self-destructing file-sharing service (Firefox Send successor).
* [Upload files to IPFS from Browser](https://anarkrypto.github.io/upload-files-to-ipfs-from-browser-panel/public/): Uploads files to IPFS directly from a browser.
* [Imgur Album Downloader](https://dschep.github.io/imgur-album-downloader/#/): Bulk-downloads images from an Imgur album.
* [Export Comments](https://exportcomments.com/): Exports comments from social media posts to a spreadsheet.
* [Image Extractor](https://extract.pics/): Extracts all images from a given web page/URL.
* [Loader.to](https://loader.to/): Converts and downloads audio/video from URLs.
* [Commentexporter.com](https://www.commentexporter.com/): Exports social media comments for analysis.
* [Link Gopher](https://sites.google.com/site/linkgopher/): Extracts all hyperlinks from a web page.
* [Page Links Extractor Tool](https://shadowcrypt.net/tools/pagelinks): Extracts all links from a given web page.
* [Online Tool to Extract Links from any Web Page](https://hackertarget.com/extract-links/): Extracts and lists all links on a page.
* [10minutemail.com](https://10minutemail.com/): Disposable temporary email address generator.
* [AnonAddy](https://anonaddy.com/): Anonymous email-alias/forwarding service.
* [SimpleLogin](https://simplelogin.io/): Open-source email-alias and forwarding service.
* [MailDrop](https://maildrop.cc/): Disposable email inbox service.
* [Send text free](https://globfone.com/send-text/): Sends free anonymous SMS messages online.
* [Free Fax](https://faxzero.com/): Sends free faxes online.
* [Receive-sms-now.com](http://receive-sms-now.com/): Free temporary/disposable phone number for receiving SMS.
* [Receive SMS Online](https://hs3x.com/): Free temporary phone numbers for receiving SMS.
* [Receive SMS Online for FREE](http://freesmsverification.com/): Free temporary phone numbers for receiving SMS.
* [Smstome.com](https://smstome.com): Free temporary phone numbers for receiving SMS.
* [Amazon SNS](https://aws.amazon.com/sns/): AWS notification service, usable for sending SMS/programmatic messages.
* [Twilio](https://www.twilio.com/): Programmable SMS, voice, and communications API platform.
* [One-time Mobile by @OsintStash](https://threader.app/thread/1199785692274077696): Thread explaining a one-time-use mobile number technique for OSINT.

### Sandboxing & Virtual Environments
* [Kasm](https://kasmweb.com/): Browser-based disposable virtual desktop/browser workspace.
* [Bluestacks](https://www.bluestacks.com/): Android emulator for running mobile apps on desktop.
* [Genymotion](https://www.genymotion.com/): Android emulator for testing and development.
* [PrimeOS](https://www.primeos.in/): Android-x86-based OS for running Android apps on PCs.
* [BigNox](https://www.bignox.com/): Android emulator (NoxPlayer) for desktop.
* [Memuplay.com](https://www.memuplay.com/): Android emulator for desktop.
* [Ldplayer.net](https://www.ldplayer.net/): Android emulator geared toward gaming.

### Synthetic Test Data Generation (QA/Dev)
* [Username Generator](https://www.lastpass.com/features/username-generator): Generates random usernames for account creation.
* [Fake Name Generator](https://www.fakenamegenerator.com/): Generates complete synthetic identities for testing purposes.
* [Resume Generator](https://thisresumedoesnotexist.com/): Generates AI-created fake resumes.
* [International Name Generator](https://www.behindthename.com/random/): Generates random names by culture/nationality.
* [Windows Phone IMEI Generator](https://wpimeigenerator.github.io/): Generates syntactically valid test IMEI numbers.
* [IMEI Number Generator](https://dyrk.org/tools/imei/): Generates syntactically valid test IMEI numbers.
* [This Rental Does Not Exist](https://thisrentaldoesnotexist.com/): AI-generated fake rental listing generator.
* [Face Photo Generator](https://thispersondoesnotexist.com/): AI-generated photorealistic synthetic faces.
* [Random Face Generator](https://fakeinfo.net/random-face-generator): Generates synthetic faces for placeholder/test use.
* [IID Generator by Georgy Bunin](https://georgybu.github.io/IID_Generator/): Generates random IDs/identifiers.
* [GUID/UUID and short GUID generator](https://richardkundl.github.io/shortguid/): Generates GUIDs/UUIDs for development use.
* [Nano ID CC](https://zelark.github.io/nano-id-cc/): Generates compact, URL-safe unique IDs.
* [Dating Profile Generator](https://www.dating-profile-generator.org.uk/): Generates fake dating-profile text for testing/parody.
* [Fake Company Name Generator](https://fakeinfo.net/company-name-generator): Generates placeholder company names.
* [Twitter Profile Generator](https://fakeinfo.net/fake-twitter-profile-generator): Generates a mock Twitter profile for design/testing use.
* [Fake Youtube Channel Generator](https://fakeinfo.net/fake-youtube-channel-generator): Generates a mock YouTube channel for design/testing use.
* [Resume Builder](https://vinaysomawat.github.io/Resume-Builder/): Builds a formatted resume from user input.
* [Fake Generator Tools](https://fauxid.com/tools): Collection of synthetic test-data generators.

### Automation, Scripting & Utilities
* [CyberChef](https://gchq.github.io/CyberChef/): Web-based utility for data encoding, decoding, and analysis.
* [Awesome-AutoHotkey](https://github.com/ahkscript/awesome-AutoHotkey#clipboard): Curated list of AutoHotkey libraries and scripts for Windows automation.
* [Convert Case](https://convertcase.net/): Utility for rapid string manipulation and text formatting.
* [mitaka](https://github.com/ninoseki/mitaka): Browser extension for running OSINT searches on selected text (IPs, hashes, domains).
* [Frack](https://github.com/sensepost/Frack): Framework for brute-forcing and OSINT reconnaissance.
* [pywhat](https://pypi.org/project/pywhat/): Identifies what type of data a given string is (hash, IP, crypto address, etc.).
* [theHarvester](https://pypi.org/project/theHarvester/): Gathers emails, subdomains, hosts, and names from public sources.
* [Online Tools](https://emn178.github.io/online-tools/): Collection of browser-based hashing/encoding utilities.
* [Graphviz Online](https://dreampuf.github.io/GraphvizOnline/): Browser-based Graphviz diagram renderer.
* [CodePen](https://codepen.io/): Online code editor and sharing platform for front-end snippets.
* [Diceware Generator](https://www.rempe.us/diceware/#eff): Generates diceware passphrases for secure password creation.
* [Checkphish.ai](https://checkphish.ai/): Free AI-based phishing/malicious URL scanner.
* [x86 and x64 Intel Assembler](https://defuse.ca/online-x86-assembler.htm): Online assembler for x86/x64 instructions.
* [Big Number Calculator](https://defuse.ca/big-number-calculator.htm): Arbitrary-precision number calculator.
* [Text and File Hash Calculator](https://defuse.ca/checksums.htm): Computes hashes for text or uploaded files.
* [HTML Sanitizer Tool](https://defuse.ca/html-sanitize.htm): Strips potentially malicious markup from HTML.
* [URL Decoder/Encoder](https://meyerweb.com/eric/tools/dencoder/): Encodes/decodes URL-escaped strings.
* [ODA - The Online Disassembler](https://onlinedisassembler.com/odaweb/): Browser-based binary disassembler.
* [Disasm.pro](https://disasm.pro/): Online multi-architecture disassembler.
* [Decompiler.com](http://www.decompiler.com/): Online Java/.NET decompiler.
* [Google Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb): Free hosted Jupyter notebook environment.
* [Compiler Explorer](https://godbolt.org/): Shows generated assembly for source code across many compilers.
* [HTML editor](https://onlinehtmleditor.dev/): Browser-based live HTML/CSS/JS editor.
* [Online Color Picker](https://colorpicker.me/): Browser-based color picker/palette tool.
* [Convert text to image file](https://text2image.com/en/): Renders plain text as an image file.
* [Data Structure : Infix Postfix Prefix - Converter & Evaluator](https://raj457036.github.io/Simple-Tools/prefixAndPostfixConvertor.html): Converts and evaluates infix/postfix/prefix expressions.
* [RSA encryption, decryption and prime calculator](https://canihavesomecoffee.github.io/js-rsa-tool/): Browser-based RSA key/encryption calculator.
* [Tools.digitalmethods.net](https://tools.digitalmethods.net/beta/searchEngineScraper/): Digital-methods research toolset (search engine scraping, etc.).
* [Steganography Online](https://stylesuxx.github.io/steganography/): Browser-based image steganography encode/decode tool.
* [Torrent to Magnet](https://nutbread.github.io/t2m/): Converts a .torrent file into a magnet link.
* [Anonymous YouTube Playlists](https://neverducky.github.io/anonymous-youtube-playlists/): Creates YouTube playlists without a linked account.
* [Vega Editor](https://vega.github.io/editor/#/): Browser-based editor for Vega/Vega-Lite data visualizations.
* [DISA Code Template Generator](https://duncanford.github.io/disa-code-generator): Generates STIG/DISA compliance code templates.
* [Canary Tokens](http://canarytokens.org/generate): Generates trackable "canary" tokens/files to detect unauthorized access.
* [explainshell.com](https://explainshell.com/): Explains what a given shell command and its flags do.
* [osint-cli-tool-skeleton](https://pypi.org/project/osint-cli-tool-skeleton/): Python project skeleton/template for building OSINT CLI tools.
