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
Network Topology Full Callister Inc. diagram, the lead image for both GitHub and LinkedIn.

Show Image

Firewall Zone Creation CLI config defining the INTERNAL/PUBLIC/DMZ zones.

Show Image

Firewall Zone Interface Assignment Mapping interfaces to zones, completing the ZPF configuration.

Show Image

Zone Policy in Action — Before and After Manchester–DMZ allowed, Cambridge–DMZ blocked: the pair proving the zone policy worked exactly as designed, and the strongest evidence in the whole report.

Show Image Show Image
