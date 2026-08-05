**Network Security Threats Research Report**



**Task 4**: Research Report on Common Network Security Threats



**Internship**: Oasis Infobyte Cyber Security Internship

**Task**:4 – Research Report on Common Network Security Threats

**Prepared by**: Harish B

**Date**: August 2026



\---



**Table of Contents:-**



1\. Introduction

2\. What is Network Security?

3\. Common Network Security Threats



&#x20;  \* Denial-of-Service (DoS) Attack

&#x20;  \* Distributed Denial-of-Service (DDoS) Attack

&#x20;  \* Man-in-the-Middle (MITM) Attack

&#x20;  \* IP Spoofing

&#x20;  \* ARP Spoofing

&#x20;  \* DNS Spoofing

4\. Real-World Examples

5\. Prevention and Mitigation Techniques

6\. Best Practices for Network Security

7\. Conclusion

8\. References



\---



**1. Introduction:-**



Modern organizations depend heavily on computer networks to communicate and store sensitive information. As technology grows, cybercriminals continuously develop new methods to attack networks and compromise systems. Understanding common network security threats is essential for protecting confidential data, maintaining service availability, and ensuring business continuity.



This report explains several common network attacks, their working principles, their impact on organizations, real-world examples, and effective countermeasures.



\---



&#x20;**2. What is Network Security?**



Network security is the practice of protecting computer networks from unauthorized access, misuse, attacks, and data theft. It combines hardware devices, software solutions, security policies, and best practices to ensure:



1\. Confidentiality

2\. Integrity

3\. Availability (CIA Triad)



Network security protects servers, computers, routers, switches, cloud services, and user data from cyber threats.



\---



**3. Common Network Security Threats:-**



&#x20;**3.1 Denial-of-Service (DoS) Attack:**



**Definition:**



A Denial-of-Service (DoS) attack is an attack where a single computer floods a target server or network with excessive traffic, making it unavailable to legitimate users.



&#x20;**How It Works:**



1\. The attacker sends a large number of requests.

2\. The server becomes overloaded.

3\. Resources such as CPU, memory, and bandwidth are exhausted.

4\. Legitimate users cannot access the service.



&#x20;**Impact:**



1\. Website downtime

2\. Business interruption

3\. Financial loss

4\. Customer dissatisfaction

5\. Reduced productivity



&#x20;**Prevention:**



1\. Configure firewalls

2\. Enable rate limiting

3\. Use Intrusion Prevention Systems (IPS)

4\. Monitor abnormal traffic

5\. Deploy Web Application Firewalls (WAF)



\---



&#x20;**3.2 Distributed Denial-of-Service (DDoS) Attack:**



&#x20;**Definition:**



A DDoS attack is similar to a DoS attack but uses thousands or millions of compromised devices (botnets) to attack the victim simultaneously.



&#x20;**How It Works:**



1\. Malware infects many devices.

2\. These devices become part of a botnet.

3\. The attacker controls the botnet.

4\. All devices send traffic to the target at once.

5\. The server becomes unavailable.



&#x20;**Impact:**



1\. Large-scale service outages

2\. High bandwidth consumption

3\. Revenue loss

4\. Damage to business reputation



&#x20;**Prevention:**



1\. DDoS protection services

2\. Content Delivery Networks (CDNs)

3\. Load balancing

4\. Traffic filtering

5\. Cloud-based DDoS mitigation



\---



&#x20;**3.3 Man-in-the-Middle (MITM) Attack:**



&#x20;**Definition:**



A Man-in-the-Middle (MITM) attack occurs when an attacker secretly intercepts communication between two parties without their knowledge.



&#x20;**How It Works:**



1\. User connects to a network.

2\. Attacker positions themselves between the user and server.

3\. Data passes through the attacker.

4\. The attacker reads or modifies the information.

5\. Data is forwarded to the destination.



&#x20;**Impact:**



1\. Password theft

2\. Financial fraud

3\. Identity theft

4\. Data manipulation

5\. Confidential information leakage



**Prevention:**



1\. HTTPS websites

2\. SSL/TLS encryption

3\. VPN usage

4\. Multi-Factor Authentication (MFA)

5\. Avoid public Wi-Fi for sensitive activities



\---



&#x20;**3.4 IP Spoofing:**



&#x20;**Definition:**



IP Spoofing is a technique where an attacker forges the source IP address of packets to appear as a trusted system.



&#x20;**How It Works:**



1\. The attacker changes the packet's source IP address.

2\. The victim believes the traffic is from a trusted device.

3\. The attacker bypasses certain security controls.



&#x20;**Impact:**



1\. Bypass firewall rules

2\. Hide attacker identity

3\. Launch DoS attacks

4\. Unauthorized access



&#x20;**Prevention:**



1\. Packet filtering

2\. Ingress and Egress filtering

3\. Authentication mechanisms

4\. Network monitoring



\---



&#x20;**3.5 ARP Spoofing:**



&#x20;**Definition:**



ARP Spoofing is an attack where fake ARP messages are sent to associate the attacker's MAC address with another device's IP address.



&#x20;**How It Works:**



1\. Attacker sends fake ARP replies.

2\. Victim updates its ARP table.

3\. Traffic is redirected to the attacker.

4\. Data is intercepted or modified.



&#x20;**Impact:**



1\. MITM attacks

2\. Session hijacking

3\. Data theft

4\. Network disruption



&#x20;**Prevention:**



1\. Static ARP entries

2\. Dynamic ARP Inspection (DAI)

3\. Secure switches

4\. Network segmentation



\---



&#x20;**3.6 DNS Spoofing:**



&#x20;**Definition:**



DNS Spoofing (DNS Cache Poisoning) redirects users to malicious websites by providing false DNS responses.



&#x20;**How It Works:**



1\. User requests a website.

2\. Fake DNS information is returned.

3\. User is redirected to a malicious website.

4\. Sensitive information may be stolen.



&#x20;**Impact:**



1\. Credential theft

2\. Malware infection

3\. Phishing attacks

4\. Financial fraud



&#x20;**Prevention:**



1\. DNSSEC

2\. Secure DNS servers

3\. Regular cache clearing

4\. HTTPS verification



\---



&#x20;**4. Real-World Examples:-**



&#x20;**Example 1**: Dyn DDoS Attack (2016):



Attackers used the Mirai Botnet to launch a massive DDoS attack against Dyn, a major DNS provider. Popular websites such as Twitter, Netflix, Reddit, Spotify, and GitHub experienced significant outages.



**Lesson:** Secure IoT devices and implement DDoS protection.



\---



&#x20;**Example 2**: Gmail MITM Attack on Public Wi-Fi:



Attackers have intercepted user traffic on unsecured public Wi-Fi networks to capture login credentials and sensitive information.



**Lesson**: Always use HTTPS and VPN services on public networks.



\---



&#x20;**Example 3**: DNS Cache Poisoning:



Several organizations have experienced DNS cache poisoning attacks that redirected users to fake banking and login websites.



**Lesson**: Deploy DNSSEC and secure DNS infrastructure.



\---



&#x20;**Example 4**: GitHub DDoS Attack (2018):



GitHub experienced one of the largest DDoS attacks, peaking at approximately 1.35 Tbps. The attack was mitigated quickly using cloud-based DDoS protection.



**Lesson**: Cloud mitigation services help defend against large-scale attacks.



\---



&#x20;**5. Prevention and Mitigation Techniques:-**



| Threat       | Prevention                                |

| ------------ | ----------------------------------------- |

| DoS          | Firewalls, Rate Limiting, IPS             |

| DDoS         | CDN, Load Balancer, Cloud DDoS Protection |

| MITM         | HTTPS, SSL/TLS, VPN, MFA                  |

| IP Spoofing  | Packet Filtering, Authentication          |

| ARP Spoofing | Dynamic ARP Inspection, Static ARP        |

| DNS Spoofing | DNSSEC, Secure DNS Servers                |



\---



&#x20;**6. Best Practices for Network Security:-**



\* Keep systems updated with the latest security patches.

\* Use strong passwords and Multi-Factor Authentication.

\* Install antivirus and endpoint protection.

\* Enable firewalls on all systems.

\* Monitor network traffic regularly.

\* Encrypt sensitive communications using HTTPS and VPNs.

\* Disable unused network services.

\* Conduct regular vulnerability assessments.

\* Train employees to recognize phishing attacks.

\* Maintain regular backups of important data.



\---



&#x20;**7. Conclusion:-**



Network security threats continue to evolve as cybercriminals develop more sophisticated attack techniques. Threats such as DoS, DDoS, MITM, IP Spoofing, ARP Spoofing, and DNS Spoofing can cause significant financial losses, service disruption, and data breaches. Organizations can reduce these risks by implementing layered security controls, encryption, firewalls, intrusion detection systems, secure authentication, and continuous monitoring. A proactive approach to cybersecurity is essential for maintaining secure and reliable networks.



\---



&#x20;**8. References:-**



1\. NIST Cybersecurity Framework

2\. OWASP Foundation

3\. Cisco Networking Academy

4\. Cloudflare Learning Center

5\. Microsoft Security Documentation

6\. IBM Cybersecurity Learning Resources



