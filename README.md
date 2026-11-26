# Emerald Heights Smart Estate Network

Designed and configured a multi-block smart estate network in Cisco Packet Tracer.

## Topology
- Blocks: A1, A2, B1, B2, C1, C2
- Administration Block: Server SRV-ESTATE, Printer, Office PCs
- Gateway Block: CCTV-NVR, Guard PC
- Devices: 2x Routers 2911 (R1, R2), 2960 Switches, Access Points, PCs, Laptops, Servers

## What I Built
- Segmented network with /28 subnetting
- Inter-router routing between blocks
- WiFi Access Points per block (AP-A1, AP-A2, AP-B1, etc.)
- DNS + HTTP Server hosting internal portal http://portal.estate
- Static IP for Servers, Routers, Gateway devices

## Testing & Result
- ping 192.168.100.114 - 4 Sent, 4 Received, 0% Loss
- Browser http://portal.estate - Loaded "Welcome to Estate Network"
- Blocks A, B, C all connected via WiFi and LAN

## Tools
Cisco Packet Tracer, TCP/IP, Subnetting, DNS, HTTP, WiFi, Routing

## Files
- Emerald_Heights_Smart_Estate.pkt - Full Packet Tracer file
- 01-Topology.png, 02-ping-test.png, 03-portal-website.png
