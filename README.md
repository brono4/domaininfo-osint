# 🌐 DomainInfo.site — Website Intelligence & OSINT Tool

**DomainInfo.site** is a fast, lightweight, and privacy-respecting **web-based reconnaissance & OSINT platform** that collects and correlates **publicly available technical information** about domains and websites in a single, easy-to-read report.

The tool is built for **penetration testers, cybersecurity students, OSINT researchers, SOC analysts, and website owners** who need quick visibility into a target’s infrastructure without performing intrusive scans.

🔗 **Live Website:** [https://domaininfo.site/](https://domaininfo.site/)

---

## 🎯 Project Goals

- Provide **quick passive reconnaissance** without exploiting targets
    
- Centralize OSINT data into **one structured report**
    
- Help users **identify misconfigurations, exposed data, and attack surfaces**
    
- Support **learning, research, and defensive security workflows**
    

---

## ✨ Features Overview

DomainInfo.site performs **passive reconnaissance** and aggregates data from multiple public and open-source intelligence providers.

---

## 🔍 1. IP Address & Server Information

This module resolves the domain and extracts core network information:

- IPv4 address resolution
    
- IPv6 address resolution (multiple AAAA records supported)
    
- `ip2long` conversion (IPv4 integer format)
    
- Basic server availability overview
    

📌 Useful for identifying hosting infrastructure and IP ranges.

---

## 🌍 2. IP Geolocation

Maps the resolved IPv4 address to geographic metadata:

- Country
    
- Region / state
    
- City
    
- Latitude & longitude
    
- Timezone
    
- Interactive map visualization
    

📌 Helps with infrastructure mapping and compliance checks.

---

## 🔌 3. Web Port Scanning

Performs **safe, limited port checks** on common web services:

- **80 (HTTP)**
    
- **443 (HTTPS)**
    

Each port is marked as:

- `OPEN`
    
- `CLOSED`
    

📌 Designed to avoid aggressive scanning while confirming service exposure.

---

## 🛡️ 4. VPN Detection & Website Rank

- Detects potential VPN or proxy usage
    
- Provides a basic website popularity / visibility rank
    

📌 Useful for OSINT context and infrastructure profiling.

---

## 🧩 5. CMS Detection

Attempts to fingerprint the website’s CMS using passive indicators:

- WordPress
    
- Joomla
    
- Drupal
    
- Other known CMS platforms
    

If no reliable indicators are found, the result is:

- **Unknown CMS**
    

📌 Helps identify potential CMS-specific attack surfaces.

---

## 📧 6. MX Records Discovery

Extracts mail server configuration:

- Mail Exchange (MX) records
    
- Priority values
    
- Mail server hostnames
    

📌 Useful for email security assessments and phishing investigations.

---

## 🕵️ 7. Google Dorking (OSINT)

Automated **Google dork queries** to identify publicly indexed information related to the domain, including:

- Pastebin leaks
    
- Exposed credentials or configs
    
- Indexed directories
    
- Sensitive documents
    
- Public code snippets
    

📌 Helps discover accidental data exposure.

---

## 📜 8. WHOIS Information

Provides full WHOIS domain data:

- Domain registrar
    
- Registrar IANA ID
    
- Creation date
    
- Expiration date
    
- Last update date
    
- Domain status flags
    
- Name servers
    
- DNSSEC status
    

📌 Essential for ownership verification and lifecycle analysis.

---

## 🌐 9. DNS Records Profile

Displays a complete DNS snapshot:

- **A** records (IPv4)
    
- **AAAA** records (IPv6)
    
- **NS** records
    
- **MX** records
    
- **TXT** records (SPF, verification tokens, etc.)
    
- **CAA** records
    
- TTL values
    
- Priority values
    

📌 Helps detect misconfigurations and security weaknesses.

---

## 🌱 10. Subdomains & Email Enumeration

Passive discovery of:

- Common subdomains
    
- Service-specific subdomains
    
- Publicly indexed email addresses (OSINT)
    

📌 Useful for expanding the attack surface during recon.

---

## 🧭 11. Name Servers Details

Detailed nameserver information:

- Nameserver hostnames
    
- IPv4 addresses
    
- IPv6 addresses
    

📌 Helps analyze DNS infrastructure redundancy and resilience.

---

## 🕰️ 12. Web Archive Integration

- Retrieves historical website snapshots from public archives
    
- Allows tracking:
    
    - Content changes
        
    - Removed pages
        
    - Legacy endpoints
        

📌 Valuable for forensic analysis and vulnerability research.

---

## 🚨 13. CVE Lookup

Correlates domain-related technologies with known vulnerabilities:

- CVE titles
    
- Direct links to:
    
    - NVD (National Vulnerability Database)
        
    - CVE Details
        
- Historical and recent vulnerabilities
    

📌 Helps prioritize security risks during assessments.

---

## ⚠️ Legal & Ethical Disclaimer

> DomainInfo.site collects **only publicly available information**.  
> No exploitation, credential attacks, or intrusive scans are performed.
> 
> This tool is intended **strictly for educational, research, and defensive security purposes**.  
> Any misuse is the sole responsibility of the user.

---

## 🚀 Future Improvements (Roadmap)

- Security headers analysis
    
- SSL/TLS certificate inspection
    
- Reverse IP lookup
    
- Technology stack detection
    
- Export reports (JSON / PDF)
    
- Public API access
    

---

[![Visit Website](https://img.shields.io/badge/🌐%20Visit-DomainInfo.site-blue?style=for-the-badge)](https://domaininfo.site/)

## 👨‍💻 Author

**Brono**  
Cybersecurity & Network Infrastructure Student  
Focused on **Pentesting, and Web Security**
