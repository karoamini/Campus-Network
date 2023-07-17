# Campus-Network
As part of my coursework at Polimi University, I undertook a project focused on optimizing and configuring a network infrastructure. The project involved implementing the following configurations and optimizations:

Host Names and Interface Shutdown:
I configured host names for devices and optimized the network by shutting down unused interfaces, ensuring efficient resource utilization.

Password Configuration:
To enhance network security, I configured enable passwords and vty passwords for Cisco devices.

VTP Configuration:
I utilized VTP (VLAN Trunking Protocol) in transparent mode with the domain "Polimi" for streamlined VLAN configuration and management.

VLAN and Trunking Configuration:
I added VLANs 10, 20, 30, and 100 to the VLAN database and configured the ports between switches as trunks, enabling efficient data transfer.

Access Port Configuration:
To establish connectivity with PCs, I configured access ports on the links to the respective devices, ensuring seamless communication.

Link Verification with CDP and LLDP:
I utilized CDP (Cisco Discovery Protocol) and LLDP (Link Layer Discovery Protocol) to verify link connectivity and gather network device information, ensuring network reliability.

Spanning Tree Optimization:
To improve network performance and eliminate loops, I optimized the Spanning Tree Protocol. Core1 was set as the root for odd VLANs, while Core2 served as the root for even VLANs.

Etherchannel Configuration:
I configured Etherchannel on the core switches, enhancing link aggregation and providing increased bandwidth and redundancy.

Layer 3 Inter-VLAN Routing:
To enable inter-VLAN communication, I implemented Layer 3 interVLAN routing on the core switches. Each VLAN was assigned a corresponding IP address, ensuring efficient routing within the network.

Access Layer Switch Configuration:
The access layer switches were assigned management IP addresses in VLAN 1, enabling easy network administration and monitoring.

HSRP Configuration:
I configured and optimized HSRP (Hot Standby Router Protocol) for fault-tolerant and reliable routing, ensuring seamless network operation in case of primary router failures.

EIGRP Configuration:
I configured EIGRP (Enhanced Interior Gateway Routing Protocol) on the core switches and ISR (Integrated Services Router), improving routing efficiency and load balancing within the network.

PC and Server Configuration:
I assigned IP addresses to PCs and the server in their respective VLANs, enabling seamless communication and network resource access.

Connectivity Verification:
I verified the connectivity between PCs, the server, and switches, ensuring successful communication and proper network functioning.

Router Configuration:
I configured the ISR router's g0/0/1 interface for DHCP and enabled NAT (Network Address Translation) to allow internal network communication through the ISR g0/0/1 interface using PAT (Port Address Translation).

Verification of External Connectivity:
I verified that PCs could successfully ping cisco.com, ensuring connectivity to external networks.

Through this project, I gained practical expertise in optimizing network infrastructure, implementing key protocols and configurations, and ensuring efficient and reliable network operations. It provided me with valuable insights into network management, troubleshooting, and design principles.
