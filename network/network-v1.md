# Network Architecture v1

Version: 1.0

Status: Active

Date: 2026

---

# Purpose

This document describes the complete network architecture of the AkpinarLabs Platform.

---

# Internet

Fiber Internet Connection

Static Public IP Address

(Private)

---

# Edge Network

ISP

↓

Zyxel EX3501-T0

↓

FortiGate 30D

↓

Local Network

↓

HP ML350 G6

↓

Proxmox VE

↓

Virtual Machines

↓

Containers

↓

Applications

---

# WAN

Public Static IP

213.153.252.54

---

# LAN

Network

192.168.1.0/24

Gateway

192.168.1.99

---

# Core Components

Firewall

FortiGate 30D

Reverse Proxy

Nginx Proxy Manager

Cloud DNS

Cloudflare

Hypervisor

Proxmox VE

Wireless

UniFi Access Point

---

# Current Services

Nginx Proxy Manager

192.168.1.88

Pangolin

192.168.1.113

Cyber-W Workstation

192.168.1.150

UniFi AP

192.168.1.115

Gateway

192.168.1.99

---

# Network Principles

- Security First
- Least Privilege
- Self Hosted
- Zero Trust Ready
- Cloud Integrated
- Easy Maintenance
- Fully Documented

---

# Future

Docker Network

Internal DNS

WireGuard

VLAN Segmentation

Monitoring

Service Discovery

Load Balancing

High Availability

---

Chief Builder

Ferhat Akpınar
