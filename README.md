# Public Wi-Fi Security Threats

## Overview
Public Wi-Fi networks are widely used in various environments such as airports, cafes, hotels, and universities. While these networks offer convenience, they also introduce significant cybersecurity risks. This repository contains the research paper **"Ασφάλεια δημόσιων Wi-Fi δικτύων" (Public Wi-Fi Network Security)** by **Konstantinos Zafeiropoulos**, which examines the security challenges of public Wi-Fi, including vulnerabilities, attack vectors, and mitigation strategies.

The research focuses on:
- The security weaknesses of public Wi-Fi networks
- Common attack methods, including packet sniffing, Man-in-the-Middle (MITM), and Evil Twin attacks
- The impact of these attacks on user privacy and data security
- Strategies and countermeasures to enhance Wi-Fi security

## Problem Statement
Public Wi-Fi networks often lack proper security mechanisms, making them an attractive target for cybercriminals. Attackers can exploit network vulnerabilities to:
- Intercept and manipulate unencrypted communication
- Steal login credentials, financial data, and personal information
- Create rogue access points (Evil Twin attacks) to deceive users
- Inject malicious code into network traffic
- Exploit session hijacking to gain unauthorized access to user accounts

This research investigates these risks, demonstrating practical attack scenarios and recommending security measures to mitigate them.

## Research Methodology
The study is based on a combination of literature review, vulnerability analysis, and practical experimentation. The research includes:
- Analysis of previous studies on public Wi-Fi security
- Examination of attack methodologies using open-source tools
- Practical demonstrations of vulnerabilities in real-world scenarios
- Evaluation of countermeasures and security best practices

The experiments utilize cybersecurity tools such as:
- **Wireshark** for packet analysis
- **Aircrack-ng** and **Airmon-ng** for wireless network security testing
- **Evil Twin Attack simulation** to analyze rogue access points
- **MITM attack execution** to demonstrate data interception risks

## Common Public Wi-Fi Attacks and Security Risks

### Packet Sniffing and Network Eavesdropping
Attackers capture unencrypted network traffic to extract sensitive information such as usernames, passwords, and banking details.

### Man-in-the-Middle (MITM) Attacks
Cybercriminals intercept communication between a user and a legitimate website, allowing them to modify or steal transmitted data.

### Evil Twin and Rogue Access Points
Hackers set up fake Wi-Fi hotspots mimicking legitimate networks to deceive users into connecting and exposing their credentials.

### Session Hijacking and Side-Jacking
By capturing session cookies, attackers can gain unauthorized access to user accounts without needing login credentials.

### DNS Spoofing and Wi-Fi Phishing
Attackers redirect users to fraudulent websites to harvest login credentials and other sensitive data.

### Ad Injection and Web Tracking Exploits
Some networks inject advertisements or tracking scripts into unencrypted traffic, compromising user privacy.

## Security Best Practices

| Security Measure | Description |
|-----------------|-------------|
| Use a Virtual Private Network (VPN) | Encrypts all network traffic, protecting against MITM and sniffing attacks. |
| Enable HTTPS Everywhere | Ensures secure encrypted communication with websites. |
| Avoid Accessing Sensitive Accounts | Refrain from logging into banking or email accounts over public Wi-Fi. |
| Disable Automatic Wi-Fi Connection | Prevents devices from connecting to rogue access points automatically. |
| Turn Off Wi-Fi When Not in Use | Reduces exposure to tracking and passive attacks. |
| Use Two-Factor Authentication (2FA) | Adds an additional layer of security to prevent unauthorized access. |
| Verify Network Legitimacy | Always confirm the official Wi-Fi network name with the service provider. |
| Use a Firewall and Security Software | Provides protection against malicious network activity and malware injection. |

## Advanced Security Measures
- **Implementation of WPA3 security** to replace outdated WEP/WPA2 encryption.
- **Context-Leashing Authentication** to detect unauthorized access points.
- **Deployment of intrusion detection systems (IDS)** for real-time attack monitoring.
- **Enhanced network monitoring tools** to detect unauthorized data interception.

## Implementation and Experimentation
This research includes practical demonstrations of attack scenarios using cybersecurity tools. The experiments cover:
- **Evil Twin Access Point Attack:** Creating a rogue access point to capture user credentials.
- **MITM Attack via ARP Spoofing:** Intercepting and modifying network traffic.
- **Packet Sniffing with Wireshark:** Capturing and analyzing unencrypted data transmission.
- **Session Hijacking using Cookie Replay Attacks:** Gaining unauthorized access to user accounts.

Each experiment is accompanied by an analysis of its impact and the corresponding mitigation strategies.

## Future Research Directions
- Investigation of **AI-driven intrusion detection systems** for wireless security.
- Exploration of **quantum cryptography applications** for public Wi-Fi protection.
- Development of **blockchain-based authentication mechanisms** to prevent MITM attacks.
- Enhancing security in **IoT devices connected to public Wi-Fi networks**.


## Author and Citation
- **Author**: Konstantinos Zafeiropoulos  
- **Affiliation**: University of West Attica  
- **Field of Research**: Cybersecurity, Network Security, Cryptography  
- **Date**: January 2024  

For citation purposes, please use the following reference:

**Zafeiropoulos, K. (2024). Public Wi-Fi Security Threats. University of West Attica.**

## Contact and Contributions
This repository is open for contributions. If you would like to suggest improvements, submit a pull request or open an issue.

For any inquiries:
- **Email**: ice20390293@uniwa.gr  
- **LinkedIn**: https://www.linkedin.com/in/konstantinos-zafeiropoulos/  
- **GitHub Issues**: For reporting bugs or suggesting enhancements  

Maintaining strong cybersecurity practices is essential for protecting personal and sensitive data. This research aims to raise awareness and provide practical solutions for securing public Wi-Fi networks.

