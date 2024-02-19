# Mastering_Networking_Concepts-Projects

Project #1: IPsec tunnel with VPN

Tried my hand at making an IPsec VPN for one company to connect to another company's network. By also emphasizing this to be secure, it has been encrypted and authenticated over the internet. Highlights the CIA triad as well. 

The need for a VPN highlights the vulnerability of unauthorized users trying to break down a company's security posture. Add to the unsecured layer of sending information over an unsecured network line, and a security threat is bound to happen. The VPN configuration also will be between the system-a and system-c, to make sure that these are the only devices that will be connecting to the IPsec VPN.

Configuration details:
1. VPN Type: IPsec tunnel
2. Tunnel Protocol: Internet Security Association and Key Management Protocol (ISAKMP-IKEv2)
3. Failover Strategy: Utilizing Port-Channel and Double-Homed Single ISP (WAN topology)
4. Traffic Filtering: Implemented Extended Access-List
5. IP Addressing Plan: Employing Internet Protocol Version 4 (IPv4) addressing scheme
