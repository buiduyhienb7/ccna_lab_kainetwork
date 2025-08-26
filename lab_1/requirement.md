# CCNA LAB 1

Lab requirements:

1. Configure IP addresses for the devices as shown in the topology diagram.

2. Trunking: Configure trunk links using dot1q encapsulation on the connections indicated in the topology.

3. VTP: Configure VTP on switches DS1, DS2, SW1, and SW2 using the domain cisco123, with DS1 & DS2 acting as Servers, and SW1 & SW2 acting as Clients that learn VLAN information from the Server switches.

4. VLAN: create VLAN 10 on DS1, create VLAN 20 on DS2, create VLAN 90 on S1 and assign VLANs to the corresponding ports.

5. Inter-VLAN Routing: Configure VLANs on BR1 to ensure PCs in VLAN 3 can communicate with PCs in VLAN 4.

6. Routing: Configure OSPF on devices R1, R2, DS1, DS2, and S1 to ensure network convergence; Configure a default route on R1 and R2, advertise the default route into the OSPF domain.

7. DHCP: Configure DHCP on switch S1 to provide IP addresses to PCs in VLAN 10 and VLAN 20. Also configure DHCP on R3.

8. NAT: Configure NAT on R1, R2, and R3 to ensure internal network devices can access the Internet.

9. VPN: Configure GRE VPN on R1, R2, and R3 to ensure PCs PC3 and PC4 can access the Server through two paths.

10. ACL: 

    a. Configure an ACL on R3 so that PCs in the 10.0.30.0/24 and 10.0.40.0/24 networks can only access the Server

    b. Configure ACLs on DS1 and DS2 so that the Server can ping the PCs, but the PCs cannot ping the Server.

Network diagram:

![Network Diagram](image_lab1.png)

