🛡️ Open-Source Threat Intelligence Feeds

By ArmoredPCS

Aggregated Open-Source Threat Intelligence for Security Operations

A collection of publicly available Threat Intelligence (CTI) feeds, maintained and organized by ArmoredPCS, providing security professionals, SOC teams, MSSPs and researchers with access to multiple threat intelligence sources.

The project aims to simplify the collection and consumption of Open-Source Intelligence (OSINT) by bringing different threat feeds together in one centralized repository.

🎯 Project Overview

Threat intelligence is essential for identifying, detecting and preventing malicious activity.

This project brings together different open-source threat intelligence providers, offering publicly available Indicators of Compromise (IOCs), including:

Malicious IP addresses

Malicious domains

Malicious URLs

File hashes (MD5, SHA1, SHA256)

Botnet infrastructure

Phishing infrastructure

Malware-related indicators

Known malicious network infrastructure

The collected feeds can be integrated into SIEM, SOAR, EDR, XDR, NDR, firewalls and other security solutions.

📡 Threat Intelligence Sources

The repository includes feeds from various established open-source threat intelligence providers.

Provider

Intelligence

URLhaus

Malicious URLs

ThreatFox

Malware IOCs

Feodo Tracker

Botnet C2 IPs

Spamhaus

Malicious IPs and domains

Emerging Threats

Network threat indicators

CINS Army

Suspicious IP addresses

Blocklist.de

Attacking IP addresses

PhishTank

Phishing URLs

Feed availability, formats and update frequency depend on the original provider.

⚙️ Integration

The feeds can be consumed by different security platforms and automation solutions.

Supported use cases include:

SIEM: Import indicators for correlation and alert enrichment.

SOAR: Automate IOC ingestion, enrichment and incident response.

EDR/XDR: Enrich endpoint detections with external threat intelligence.

Firewalls: Use supported indicators as External Dynamic Lists (EDLs).

NDR/NSM: Identify suspicious network communications.

MISP: Import and correlate threat intelligence events.

Automation: Integrate feeds into custom Python scripts, n8n workflows and other automation pipelines.

🔄 Feed Updates

Threat intelligence is continuously changing. Feeds should be refreshed periodically to ensure indicators remain relevant.

Recommended practices:

Automate feed retrieval.

Validate and normalize indicators.

Remove duplicates.

Track indicator source and timestamps.

Apply expiration and confidence policies.

Validate indicators before deploying blocking rules.

⚠️ Important Disclaimer

This project aggregates publicly available threat intelligence feeds for research, defensive security and educational purposes.

ArmoredPCS does not own or maintain the original third-party intelligence sources unless explicitly stated.

Indicators may be outdated, inaccurate or false positives.

Always validate indicators before blocking legitimate traffic.

Respect the licensing, terms of use and attribution requirements of each provider.

Use the information responsibly and only for authorized security operations.

Threat intelligence is not a substitute for proper security analysis.

🤝 Contributions

Contributions are welcome!

If you know additional reliable open-source threat intelligence providers or have suggestions for improving the repository:

Fork this repository.

Create a feature branch.

Submit your changes.

Open a Pull Request with a description of your contribution.

🏢 About ArmoredPCS

ArmoredPCS provides cybersecurity solutions and services focused on improving organizational security through defensive security technologies, threat intelligence, security monitoring and automation.

Website: https://armoredpcs.gr
