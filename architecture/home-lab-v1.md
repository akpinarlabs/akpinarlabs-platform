# HomeLab Architecture v1

Version: 1.0

Status: Active

Date: 2026

---

# Purpose

This document describes the physical and logical architecture of the AkpinarLabs HomeLab.

The HomeLab serves as the primary development, testing and production environment for all AkpinarLabs services.

Future cloud infrastructure, AI services, mobile backends and educational platforms will be built on top of this environment.

---

# Objectives

The HomeLab is designed to provide:

- Self-hosted infrastructure
- Cloud-native platform
- AI-ready architecture
- High availability (future)
- Secure networking
- Automated deployments
- Learning environment
- Production services

---

# Physical Architecture

Internet

↓

1 Gbps Fiber Connection

↓

Static Public IP

213.153.252.54

↓

Zyxel EX3501-T0

↓

FortiGate 30D

↓

HP ProLiant ML350 G6

↓

Proxmox VE

↓

Virtual Machines

↓

Containers

↓

Applications

---

# Hardware

## Server

HP ProLiant ML350 G6

---

## CPU

Intel Xeon E5620

---

## Memory

48 GB RAM

(Upgradeable)

---

## Storage

240 GB SSD (System)

1 TB HDD

1 TB HDD

1 TB HDD

Future:

+240 GB SSD

+240 GB SSD

---

# Hypervisor

Proxmox VE

Version 8

---

# Network

LAN

192.168.1.0/24

Gateway

FortiGate

192.168.1.99

---

# Current Services

Nginx Proxy Manager

Pangolin

Development VMs

Educational Labs

Cyber Security Labs

---

# Future Services

Docker

Coolify

PostgreSQL

Redis

MinIO

Git Server

CI/CD

AI Platform

LLM

Object Storage

Monitoring

Logging

Backup

Identity Management

---

# Long-term Vision

The HomeLab is not only a server.

It is the engineering foundation of the entire AkpinarLabs Platform.

Every application, every API, every AI service and every educational product will first be developed and tested here.

---

Chief Builder

Ferhat Akpınar
