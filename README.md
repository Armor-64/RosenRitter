🛡️ ArmoredPCS Threat Intelligence

Open-source threat intelligence aggregation for defensive security operations.

Aggregated. Normalized. Ready for integration.

Open-source Threat Intelligence (OSINT) feeds collected from multiple independent providers, organized and maintained by ArmoredPCS.

A centralized collection of Indicators of Compromise (IOCs), bringing together malicious IP addresses, domains, URLs and file hashes from different threat intelligence sources to support security monitoring, detection and incident response.

Sources · IOC Feeds · Automation · SIEM · SOAR · MISP · EDL

Overview

Threat intelligence is most effective when information from multiple sources can be collected, correlated and consumed from a centralized location.

ArmoredPCS Threat Intelligence aims to simplify this process by aggregating publicly available intelligence feeds from established cybersecurity projects and threat research communities.

Instead of manually collecting indicators from different providers, security teams can leverage a consolidated collection of threat intelligence sources for their defensive security infrastructure.

Multiple sources, one collection. Threat intelligence from different providers is organized into a centralized repository.

IOC-focused intelligence. Collection of malicious IPs, domains, URLs and file hashes for security detection and investigation.

Integration-ready. Designed to support SIEM, SOAR, EDR, XDR, NDR, firewalls and threat intelligence platforms.

Open-source intelligence. Built around publicly available feeds and community-driven threat research.

Automation-friendly. Suitable for scheduled retrieval, parsing, normalization and distribution through automation workflows.

Quick Start

Clone the repository:

git clone https://github.com/ArmoredPCS/Threat-Intelligence.git
cd Threat-Intelligence

Explore the available threat intelligence collections and select the feeds relevant to your security environment.

Individual feeds can be consumed by compatible security platforms or retrieved through automation scripts.

Repository structure and feed endpoints may vary depending on the available collections.

Threat Intelligence Sources

The project consolidates intelligence from multiple open-source providers.

Provider

Intelligence

URLhaus

Malicious URLs

ThreatFox

Malware IOCs

Feodo Tracker

Botnet C2 infrastructure

Spamhaus

Malicious IPs and domains

Emerging Threats

Network threat intelligence

CINS Army

Suspicious IP addresses

Blocklist.de

Attacking IP addresses

PhishTank

Phishing URLs

Feed availability, formats, licensing and update frequency are controlled by the respective providers.

Intelligence Categories

The repository focuses on different types of Indicators of Compromise.

IP Intelligence

Malicious IPv4 and IPv6 addresses

Botnet command-and-control infrastructure

Known attacking IP addresses

Suspicious network infrastructure

Domain Intelligence

Malicious domains

Phishing domains

Malware distribution domains

Command-and-control domains

URL Intelligence

Malware distribution URLs

Phishing URLs

Exploit and payload delivery URLs

File Intelligence

MD5 hashes

SHA1 hashes

SHA256 hashes

Malware-associated file indicators

Integration

Threat intelligence can be used across different defensive security technologies.

SIEM

Import indicators for event correlation, threat hunting and detection engineering.

SOAR

Automate IOC collection, enrichment, investigation and response workflows.

MISP

Use collected intelligence as an additional source for threat intelligence correlation and event enrichment.

Firewalls

Integrate compatible IP and domain feeds into External Dynamic Lists (EDLs) and blocking policies.

EDR / XDR

Enrich endpoint investigations and correlate suspicious activity with known malicious indicators.

NDR / NSM

Identify suspicious network communications and correlate observed traffic against known threat intelligence.

Automation

Integrate feed retrieval and processing into Python scripts, n8n workflows and other automation platforms.

Automation & Processing

Threat intelligence feeds can be processed through automated workflows to improve consistency and operational usability.

Recommended processing pipeline:

Threat Intelligence Providers
            |
            v
      Feed Collection
            |
            v
    Parsing & Validation
            |
            v
   IOC Normalization
            |
            v
    Deduplication
            |
            v
   Feed Distribution
            |
            v
 SIEM / SOAR / EDR / XDR
 Firewall / MISP / NDR

Recommended processing operations:

Validate indicator formats.

Normalize IPs, domains and URLs.

Remove duplicate indicators.

Preserve original source attribution.

Track collection timestamps.

Apply expiration and confidence policies.

Handle feed updates and removed indicators.

Operational Considerations

Threat intelligence requires continuous maintenance to remain useful.

Feed freshness: Retrieve intelligence periodically according to the provider's update schedule.

Indicator validation: Validate indicators before using them in production security policies.

False positives: Multiple sources may contain outdated or incorrectly classified indicators.

Source attribution: Preserve the original provider and indicator context.

Expiration: Avoid keeping indicators indefinitely without reassessment.

Performance: Avoid unnecessarily large or duplicated blocklists.

Security & Disclaimer

This repository is intended for defensive cybersecurity operations, threat research, security monitoring and educational purposes.

Intelligence is collected from publicly available third-party sources.

ArmoredPCS does not claim ownership of third-party intelligence.

Original providers retain their respective rights and licensing requirements.

Indicators may be outdated, inaccurate or generate false positives.

Always validate intelligence before applying blocking policies.

Respect the terms of use and redistribution requirements of each provider.

Use responsibly and only within authorized security environments.

Contributing

Contributions from the cybersecurity community are welcome.

You can help improve the project by:

Suggesting additional open-source threat intelligence providers.

Reporting unavailable or deprecated feeds.

Improving feed parsing and normalization.

Identifying duplicate or unreliable sources.

Improving documentation and automation.

Please submit issues or pull requests with relevant information and source references.

About ArmoredPCS

ArmoredPCS focuses on cybersecurity solutions, defensive security operations, threat intelligence and security automation.

The objective is to make enterprise-grade cybersecurity technologies and intelligence more accessible, practical and manageable.

🌐 Website: https://armoredpcs.gr
