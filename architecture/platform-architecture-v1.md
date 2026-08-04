# Platform Architecture v1

Status: Draft

## Overview

The AkpinarLabs Platform is built on a modular, service-oriented architecture.

Each major platform component runs in its own dedicated virtual machine to improve scalability, security and maintainability.

---

## Platform Stack

Internet

↓

Cloudflare

↓

FortiGate Firewall

↓

Proxmox VE

↓

VM100  core-01

↓

Docker Platform

↓

Applications

---

## Virtual Machines

| VM ID | Hostname | Purpose |
|--------|----------|---------|
| VM100 | core-01 | Platform Core Services |
| VM101 | db-01 | Database Services |
| VM102 | ai-01 | Artificial Intelligence |
| VM103 | monitor-01 | Monitoring & Logging |
| VM104 | dev-01 | Development & Testing |
| VM105 | backup-01 | Backup Services |

---

## Design Principles

- One Responsibility Per VM
- Security by Design
- Easy Backup
- Independent Scaling
- High Availability Ready
- Self Hosted First

---

This document defines the high-level architecture of the AkpinarLabs Platform.
