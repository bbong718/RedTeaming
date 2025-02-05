# Reconnaissance Tools Guide
Welcome to the Reconnaissance Tools Guide! This guide is designed to help you gather essential information about a target before any exploitation attempt. The information collected will assist in understanding the target's structure, vulnerabilities, and potential entry points.

## Categories of Reconnaissance Tools
### 1. Social Media Scanning
**Purpose:** Extract detailed information from social media platforms.

* **OSINT Framework:** A comprehensive guide to OSINT tools that can be used across various platforms.
    - **What it Collects:** Various publicly available information like employee details, project involvements, etc.
* **Sherlock:** Footprinting tool for identifying individuals' presence across major social networks.

    - What it Collects: Username availability and active profiles on different platforms.
* **Hunter.io:** Tool for gathering email addresses from a given domain.

    - What it Collects: Email patterns and employee emails, aiding in spear-phishing attempts.

### 2. Domain Scanning
**Purpose:** Gather information about domains and subdomains.

* **Maltego:** Open-source investigation tool with powerful graph visualization.

    - **What it Collects:** Subdomains, domain ownership details, network relationships.

* **Recon-ng:** Advanced OSINT framework for gathering domain-related information.

    - **What it Collects:** Domain registration info, Whois data, DNS records.

* **TheHarvester:** Tool designed to gather email addresses and domain names via search engines.

    - **What it Collects:** Emails, subdomains through Google, Bing, and other search engines.

### 3. Metasploit Recon Modules
**Purpose:** Utilize built-in modules for information gathering within the Metasploit framework.

* **Auxiliary Gather Modules:** Modules like `http_version`, `email_collector`, etc.

    - **What they Collect:** HTTP versions, email addresses, and other metadata from web servers.

### 4. DNS Scan Tools
**Purpose:** Identify domain name system records.

* **Dig:** Command-line tool for querying DNS name servers.

    - **What it Collects:** NS, MX, CNAME records.

* **Fierce:** Tool to identify subdomains by analyzing DNS zone transfers and other queries.

    - **What it Collects:** Subdomains, DNS servers, mail servers.

* **DNSrecon:** Perl script for advanced DNS analysis.

    - **What it Collects:** SPF records, DKIM keys, CNAME lookups.

### 5. Port Scanning Tools
**Purpose:** Detect open ports and services on network interfaces.

* **Nmap:** Network exploration tool for detailed port scanning.

    - **What it Collects:** Open ports, running services, version information.

* **Masscan:** High-speed port scanner designed to scan large ranges quickly.

    - **What it Collects:** Active hosts on the network and open ports.

### 6. Vulnerability Scan Tools
**Purpose:** Identify known vulnerabilities in services and software.

* **Nessus:** Comprehensive vulnerability scanning tool.

    - **What it Detects:** Known vulnerabilities, misconfigurations, potential exploits.

* **OpenVAS:** Open-source vulnerability management system.

    - **What it Detects:** Weak points in network configurations, applications, etc.

### 7. Whois Tools
**Purpose:** Obtain ownership details of domains and IP addresses.

* **command-line whois:** Basic tool for querying domain registration information.

    - **What it Collects:** Domain registrar, expiry dates, name servers.

### 8. Web Scraping Tools
**Purpose:** Extract data from websites for OSINT gathering.

* **BeautifulSoup (Python library):** Used for web scraping tasks.

    - **What it Extracts:** HTML content, text mining contact info.

* **Scrapy (Python framework):** For more complex web crawling jobs.

    - **What it Extracts:** Structured data from websites.

### 9. Network Mapping Tools
**Purpose:** Visualize and understand network infrastructure.

* **Netmapper:** Tool for creating visual networks based on IP address ranges.

    - **What it Provides:** Graphical representation of network topology.

* **LANsweeper:** LAN discovery tool to map and inventory devices.

    - **What it Discovers:** Connected devices, IP allocation, device details.

## Ethical Considerations
Always ensure that reconnaissance activities are conducted within legal boundaries. Unauthorized access or data gathering can lead to severe consequences, including legal actions and loss of trust. Always have explicit authorization before conducting any form of probing or information gathering against a target network.

---
This guide serves as a reference for the tools available in each category of reconnaissance. By organizing your recon efforts with these tools, you can efficiently gather actionable intelligence about your target. Remember to align your activities with legal and ethical standards at all times.