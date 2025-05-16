# Banking Network Architecture - Cisco Packet Tracer  

## **Project Overview**  
This project simulates a **4-floor Banking Network** in Cisco Packet Tracer, featuring:  
- **Department-wise VLAN segmentation** (Finance, HR, Operations, etc.)  
- **OSPF dynamic routing** for efficient traffic management  
- **Switch security** (Port Security, DHCP Snooping)  
- **Inter-VLAN routing & DHCP Helper** for seamless communication  
- **Wireless network integration**  
- **Static IP assignment for servers**  

## **Network Topology**  
- **4 Floors**, each with **3 departments** (PCs, Printers, Switches)  
- **Server Room** on the 4th floor (DNS, DHCP, Web Server)  
- **Core Router per floor** + **Department-specific switches**

![image alt](https://github.com/chathuraz/Banking-Network-Architecture/blob/2212b512b9c2fe19917e62c623acfd77db72fda0/Network%20Project%205%20(Bank%20Network%20Design).drawio.png)

## **Configuration Steps**  
1. **Basic Device Setup** (Hostnames, SSH, Secured Access)  
2. **VLAN Assignment & Trunk/Access Ports**  
3. **Switchport Security** (MAC Limiting, Violation Actions)  
4. **Subnetting & IP Addressing** (VLAN-based Subnets)  
5. **OSPF Routing** (Dynamic Path Selection)  
6. **Static IP for Servers**  
7. **DHCP Configuration** (Scope, Helper Addresses)  
8. **Inter-VLAN Routing** (Layer 3 Switching)  
9. **Wireless Network Setup** (SSID, Security)  
10. **Verification & Testing** (Ping, Traceroute, SSH)  

## **Technologies Used**  
- **Cisco Packet Tracer**  
- **VLANs & Trunking (802.1Q)**  
- **OSPF (Dynamic Routing Protocol)**  
- **Port Security & DHCP Snooping**  
- **Inter-VLAN Routing (Router-on-a-Stick)**  
- **Wireless LAN (WPA2 Security)**  

## **How to Use**  
1. Open the `.pkt` file in **Cisco Packet Tracer**.  
2. Explore the configurations via CLI on routers/switches.  
3. Test connectivity between VLANs & wireless devices.  

## **Future Improvements**  
- Implement **HSRP** for router redundancy  
- Add **Firewall & IDS/IPS** for enhanced security  
- Integrate **VPN** for remote access  

**Feel free to contribute or suggest enhancements!**  

📥 **Download & Explore:** [GitHub Repo Link]  
#Networking #Cisco #CyberSecurity #BankingTech #ITInfrastructure  
