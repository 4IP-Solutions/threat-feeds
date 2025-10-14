# 4IP Threat Feeds
Welcome to the official GitHub repository for 4IP Threat Feeds. This repository hosts a collection of IP and DNS threat feeds designed to block malicious inbound and outbound connections. The feeds are updated as needed to provide the most recent intelligence on known malicious entities, helping enhance security posture and reduce potential attack surfaces for your network or application environment.

## Features
- Comprehensive IP and DNS Threat Data: Continuously updated threat lists featuring known malicious IP addresses, domains, and hosts.
- Inbound and Outbound Threat Blocking: Designed to mitigate risks from malicious entities by blocking both inbound and outbound connections, thus preventing both unauthorized access and data exfiltration.
- Easy Integration: Compatible with various firewall, IDS/IPS, and SIEM systems, enabling quick deployment and integration into existing infrastructure.
- Source Categorization: Our feeds cover a wide range of threats, including botnets, command-and-control servers, malware distribution sites, phishing domains, and other malicious actors.

## Threat Feeds explained
- **blocklist-incoming-ip-asn.txt** = This feed imports external threatfeeds (https://github.com/wallacebrf/dns/) to block known dangerous ASN ip blocks for incoming IP traffic.
- **blocklist-incoming-ip-benelux.txt** = This feed imports external threatfeeds (https://github.com/romainmarcoux/malicious-ip) to block known dangerous IP blocks from Netherlands, Belgium and Luxemburg for incoming IP traffic.
- **blocklist-incoming-ip-eu-west.txt** = This feed imports external threatfeeds (https://github.com/romainmarcoux/malicious-ip) to block known dangerous IP blocks from Netherlands, Belgium, Luxemburg, Germany, France and the UK for incoming IP traffic.
- **blocklist-incoming-ip-high-security.txt** = This feed imports manual list and MANY external threatfeeds from various sources for incoming IP traffic (this contains and blocks a lot of IP's).
- **blocklist-incoming-ip.txt** = This feed imports some manual lists and external threatfeeds from various sources for incoming IP traffic.
- **blocklist-outgoing-dns.txt** = This feed imports some manual lists and external threatfeeds from various sources for outgoing DNS traffic.
- **blocklist-outgoing-ip.txt** = This feed imports some manual lists and external threatfeeds from various sources for outgoing IP traffic.

## Usage
Each feed is available in formats suitable for common network security tools and platforms. Please review the repository documentation for details on feed integration, configuration guidelines, and update schedules.

## Contributions and Feedback
Feedback, issue reporting, and contributions are welcome! Our goal is to continually improve the quality and effectiveness of these threat feeds. Please refer to the CONTRIBUTING.md file for contribution guidelines, and feel free to open issues for any suggestions or questions.

## Disclaimer
These threat feeds are provided "as is" with no warranties. Users should ensure compatibility with their specific network environment and exercise caution when deploying automated blocking.
