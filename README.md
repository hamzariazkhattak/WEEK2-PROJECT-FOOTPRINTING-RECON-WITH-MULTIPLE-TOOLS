# Week 2 – Project Module 1
## Footprinting & Reconnaissance Attacks with Multiple Kali Linux Tools

### 📌 Project Overview

This project focuses on **Footprinting and Reconnaissance**, the initial phase of ethical hacking and penetration testing.

The objective was to perform reconnaissance on the publicly accessible domain `networkwalks.com` using multiple built-in Kali Linux tools. The purpose was to gather publicly available information about the target's domain registration, DNS infrastructure, web technologies, HTTP response headers, and Web Application Firewall (WAF).

By using different reconnaissance tools, I developed a basic understanding of how security professionals identify and analyze a target's publicly exposed information before conducting further security assessments.

### 🎯 Project Objectives

- Identify domain registration information.
- Discover technologies used by the target website.
- Resolve the domain name to its IP address.
- Analyze HTTP response headers.
- Identify the presence of a Web Application Firewall.
- Enumerate DNS records and understand the target's DNS infrastructure.

### 🛠️ Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Kali Linux | Penetration testing environment |
| WHOIS | Domain registration information |
| WhatWeb | Website technology fingerprinting |
| Nslookup | DNS resolution and IP discovery |
| cURL | HTTP response header analysis |
| WAFW00F | Web Application Firewall detection |
| DNSRecon | DNS record enumeration |

### 🔍 Tasks Performed

#### 1. WHOIS – Domain Information Gathering

**Command:**
```bash
whois networkwalks.com
```

Used WHOIS to retrieve publicly available domain registration details, including registrar information, registration dates, and name servers.

#### 2. WhatWeb – Website Technology Fingerprinting

**Command:**
```bash
whatweb networkwalks.com
```

Used WhatWeb to identify the technologies and software components associated with the target website, including its web platform, frameworks, and other detectable technologies.

#### 3. Nslookup – IP Address Discovery

**Command:**
```bash
nslookup networkwalks.com
```

Used Nslookup to resolve the target domain name into its corresponding IP address through DNS queries.

#### 4. cURL – HTTP Header Analysis

**Command:**
```bash
curl -I https://networkwalks.com
```

Analyzed HTTP response headers to identify server information, response status, cookies, redirects, and other exposed HTTP-related details.

#### 5. WAFW00F – Firewall Detection

**Command:**
```bash
wafw00f networkwalks.com
```

Used WAFW00F to detect whether the target website was protected by a Web Application Firewall and identify the detected firewall technology.

#### 6. DNSRecon – DNS Enumeration

**Command:**
```bash
dnsrecon -d networkwalks.com
```

Performed DNS enumeration to identify publicly available DNS records, including name servers, mail servers, SPF, TXT, and service records.

### 📊 Project Outcome

Successfully performed all six reconnaissance tasks using Kali Linux tools.

The assessment demonstrated how publicly available information can reveal important details about a website's domain registration, hosting infrastructure, web technologies, HTTP configuration, firewall protection, and DNS environment.

This project provided practical experience in:

- Passive reconnaissance techniques.
- Domain and DNS information gathering.
- Website technology identification.
- HTTP header inspection.
- Web Application Firewall detection.
- DNS enumeration using Kali Linux.

### ⚖️ Ethical Considerations

This project was performed for educational purposes as part of cybersecurity and ethical hacking training.

Reconnaissance activities should only be conducted against systems for which appropriate authorization has been granted.

---

### 👨‍💻 Project Information

**Project:** Week 2 – Project Module 1  
**Tester Name:** Hamza Riaz (Intern)  
**Training Organization:** NetworkWalks  
**Environment:** Kali Linux  
**Category:** Cybersecurity | Ethical Hacking | Footprinting & Reconnaissance
