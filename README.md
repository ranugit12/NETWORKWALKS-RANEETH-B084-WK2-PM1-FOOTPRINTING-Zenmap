# NETWORKWALKS-RANEETH-B084-WK2-PM1-FOOTPRINTING-Zenmap
## 📌 Project overview
This project contains the practical implementations of reconnaissance and the tools used to gather information from a company such as NETWORKWALKS in Week 2 project module 1 and using Zenmap to find live hosts on my Subnet and save the topology for analysis in week 2 project module 5. The project also contains the final report containing evidence of work.

## 🔨 Activities performed
**Reconnaissance** : I used the below tools to perform a Recon on NETWORKWALKS with proper                                  authorization.

 - whois: Used to find Domain registration details. (Owner, dates, name servers).
 - whatweb: Fingerprint web technologies (server, CMS, plugins, IP). Results: **Wordpress 7.1.4**, **WP Download Manager 3.3.7.6**.
 - nslookup: Resolve the domain name to its IP address using DNS. Result: **192.232.216.135**.
 - curl -I: Read the HTTP response headers of the website.
 - wafw00f: Detect whether a Web Application Firewall protects the site. Result: **ModSecurity (SpiderLabs)**.
 - dnsrecon: Enumerate all DNS records (NS, MX, SPF, TXT, SRV).



