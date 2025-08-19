# Home Network Simulation in Cisco Packet Tracer

This project demonstrates a **home network simulation** using Cisco Packet Tracer.  
The design includes a mix of **wired and wireless devices** connected to a home wireless router.

## Project Contents
- **Documentation/** → # Device Configurations

## Wireless Router (HomeRouter-PT-AC)
- **IP Address:** 192.168.0.1
- **DHCP Range:** 192.168.0.100 – 192.168.0.200
- **SSID:** HomeNet
- **Security:** WPA2-PSK, password = SecureHome123

## Gaming PC
- NIC configured to receive IP via DHCP
- Verified IP = 192.168.0.101

## Laptop
- Wireless NIC connected to SSID: HomeNet
- Authenticated with WPA2 key: SecureHome123
- DHCP-assigned IP = 192.168.0.102

## Smartphone
- Wireless NIC connected to SSID: HomeNet
- DHCP-assigned IP = 192.168.0.103

## Tablet
- Wireless NIC connected to SSID: HomeNet
- DHCP-assigned IP = 192.168.0.104

## Printer (Planned Static IP)
- IP = 192.168.0.50
- Subnet Mask = 255.255.255.0
- Gateway = 192.168.0.1
<img width="850" height="652" alt="image" src="https://github.com/user-attachments/assets/6c9f6faf-9f89-4472-996b-c301f70a6214" />

## Tools Used
- Cisco Packet Tracer v8.x
- Networking protocols: DHCP, ICMP, wireless security (WPA2)

## Features
- Wireless router with DHCP enabled for automatic IP assignment
- Multiple end devices:
  - Gaming PC (wired connection)
  - Laptop (wireless connection)
  - Smartphone (wireless connection)
  - Tablet (wireless connection)
  - Printer (wired connection)
- Secure wireless SSID with WPA2
- End-to-end connectivity tested with `ping`

## Skills Demonstrated
- Network topology design
- Wireless + wired integration
- DHCP configuration for home networks
- Wireless router security setup
- Basic documentation of network projects
