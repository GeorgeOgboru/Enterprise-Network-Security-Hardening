# Enterprise Network Security Hardening — Case Study

## Objective
To assess a weakly configured enterprise network against standard security baselines and implement a layered set of controls (logging, access control, intrusion prevention, firewalling, secure management, and encrypted connectivity) that collectively restrict unauthorised access, enable visibility into network activity, and secure communication between sites, while verifying each control through hands-on testing rather than configuration alone.

### Skills Learned
Auditing a live network configuration against expected security baselines and identifying gaps
Designing and implementing centralised logging (Syslog) across routers and switches, including routing traffic to a log server with no native path to it
Enforcing secure administrative access through console and privileged-mode authentication
Deploying a signature-based Intrusion Prevention System (IPS) at a network's central point of traffic convergence
Writing and applying Access Control Lists (ACLs) to restrict traffic from untrusted networks into a DMZ
Designing a Zone-Based Policy Firewall (ZPF): defining security zones, assigning interfaces, and writing explicit policy maps to control traffic between zones
Configuring SNMPv3 for secure, authenticated device management
Implementing authenticated NTP (MD5) to establish a single trusted time source across a network
Building a site-to-site VPN using IPsec with AES encryption and pre-shared key authentication
Validating security controls through structured connectivity testing (ping, PDU tracing) rather than relying on configuration alone
Translating enterprise network segmentation principles (zones, conduits, least-privilege access) into concepts directly transferable to OT/ICS environments and IEC 62443

### Tools Used
Simulation platform: Cisco Packet Tracer
Device OS: Cisco IOS (routers and switches)
Protocols: TCP/IP, NAT, Syslog, SNMPv3, NTP (MD5-authenticated), IPsec/ISAKMP, DNS, HTTP/HTTPS, ICMP
Security controls: IPS (signature-based), ACLs, Zone-Based Policy Firewall (ZPF)

## Visual Evidence

<img width="487" height="691" alt="Screenshot 2026-07-26 042212" src="https://github.com/user-attachments/assets/c15910e1-bf21-40e4-8996-c08bfab6ee6b" />

<img width="497" height="713" alt="image" src="https://github.com/user-attachments/assets/710fe610-ca8b-4029-8362-2530d944752c" />

<img width="566" height="778" alt="image" src="https://github.com/user-attachments/assets/bc3a6a2f-40cc-4d16-876e-b388250f978b" />

<img width="557" height="787" alt="image" src="https://github.com/user-attachments/assets/b95f882b-8e3c-440d-8c54-fb32747be7de" />

<img width="595" height="782" alt="image" src="https://github.com/user-attachments/assets/a3fb2d9c-ebc3-496f-8b53-58b7bc35ed9e" />

<img width="578" height="811" alt="image" src="https://github.com/user-attachments/assets/9547fee4-3e23-4459-b02e-64762b248b32" />

<img width="580" height="806" alt="image" src="https://github.com/user-attachments/assets/9748b700-eb44-47ee-a04e-409982cd2684" />

<img width="587" height="787" alt="image" src="https://github.com/user-attachments/assets/e7b1e7e1-67f4-4a2a-831c-49e068059b2d" />

<img width="567" height="790" alt="image" src="https://github.com/user-attachments/assets/d9ea7bbc-0fdb-47ff-a831-96ef4b0d4010" />

<img width="575" height="811" alt="image" src="https://github.com/user-attachments/assets/4a270481-cce9-497a-9f53-5fee56d4213a" />


