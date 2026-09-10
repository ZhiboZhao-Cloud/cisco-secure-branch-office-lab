# cisco-secure-branch-office-lab
Cisco Packet Tracer branch office network lab with VLANs, Router-on-a-Stick, DHCP, ACLs, NAT/PAT and simulated Internet access.


# Cisco Secure Branch Office Network Lab

## Project Overview

This project implements a simulated small branch office network using Cisco Packet Tracer.

The network is segmented into Administration, Sales, Technical Support, and Server VLANs. Inter-VLAN routing is implemented using Router-on-a-Stick, while DHCP provides dynamic IPv4 addressing to employee devices.

Extended ACLs restrict communication between the Sales and Technical Support departments. NAT/PAT and a static default route provide simulated Internet access through an ISP router to an external web server.

The project was built from a blank Packet Tracer workspace and includes configuration files, verification evidence, and troubleshooting documentation.

## Network Topology

## Objectives

## Technologies Used

- VLAN segmentation
- Access ports
- IEEE 802.1Q trunking
- Router-on-a-Stick
- Inter-VLAN routing
- DHCP
- Static IPv4 addressing
- Extended ACLs
- Static default routing
- NAT/PAT (overload)
- HTTP
- Cisco IOS verification commands

## Device Inventory

| Device | Platform | Role |
|---|---|---|
| EDGE-R1 | Cisco 2911 | Inter-VLAN routing, DHCP, ACL and NAT/PAT |
| ISP-R1 | Cisco 2911 | Simulated ISP router |
| SW1 | Cisco 2960 | Primary access switch |
| SW2 | Cisco 2960 | Secondary access switch |
| ADMIN-PC1/2 | PC | Administration clients |
| SALES-PC1/2 | PC | Sales clients |
| SUPPORT-PC1/2 | PC | Technical Support clients |
| FILE-SERVER | Server | Internal server |
| PUBLIC-WEB | Server | Simulated external HTTP server |

## VLAN and IP Addressing Plan

| VLAN | Department | Network | Default Gateway |
|---|---|---|---|
| 10 | Administration | 10.10.10.0/24 | 10.10.10.1 |
| 20 | Sales | 10.10.20.0/24 | 10.10.20.1 |
| 30 | Technical Support | 10.10.30.0/24 | 10.10.30.1 |
| 40 | Servers | 10.10.40.0/24 | 10.10.40.1 |
## Port Assignment

## Network Design

### VLAN Segmentation

### Router-on-a-Stick

### DHCP

### Access Control Lists

### WAN and Default Route

### NAT/PAT

## Verification

## Troubleshooting

## Repository Structure

## What I Learned
