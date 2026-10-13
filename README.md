# Senior High School Network Design

## Overview

This project involves the design and simulation of a computer network for a senior high school using Cisco Packet Tracer. The network is designed to support communication between departments, provide access to shared services, and enable connectivity to an external network.

The design focuses on network segmentation, efficient IP address allocation, centralized services, and connectivity between the school's internal network and an external network.

## Project Objectives

- Design a structured network for a senior high school.
- Segment departmental devices using VLANs.
- Apply Variable Length Subnet Masking (VLSM) for IP address allocation.
- Configure inter-VLAN routing.
- Provide network services such as DHCP and DNS.
- Implement and test NAT/PAT for external network connectivity.

## Technologies and Concepts

- Cisco Packet Tracer
- VLANs and trunking
- IPv4 addressing and subnetting
- Variable Length Subnet Masking (VLSM)
- Inter-VLAN routing
- DHCP and DNS
- Network Address Translation (NAT/PAT)

## Network Architecture

The proposed architecture includes departmental access switches, switching infrastructure for connectivity to network services, a router, and an ISP-connected external network.

The design uses VLANs to separate departmental traffic logically and VLSM to allocate IP address space according to network requirements.

## Verification

Connectivity was tested from an internal departmental PC to an external server in the simulated network. Additional configuration details and screenshots will be documented as the project files are organized.

## Project Files

- `school-network.pkt` — Cisco Packet Tracer simulation file.
- `screenshots/` — Selected images showing the network architecture and verification results.

## Scope

This is an academic network design and simulation project. The external network and server are simulated in Cisco Packet Tracer and do not represent a connection to a live ISP or the public internet.
