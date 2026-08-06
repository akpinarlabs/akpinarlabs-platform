# Proxmox Storage Standard v1

## Purpose

This document defines the temporary storage layout for the AkpinarLabs platform.

This layout is designed to support the current hardware while remaining easy to migrate once additional SSD storage becomes available.

---

# Current Storage Layout

## Disk 1

Type

SSD

Purpose

- Proxmox VE
- VM system disks
- LXC system disks

---

## Disk 2

Type

HDD

Purpose

- Docker persistent volumes
- Shared application data
- General storage

---

## Disk 3

Type

HDD

Purpose

- Backups
- ISO images
- VM Templates
- Snapshots

---

## Disk 4

Type

HDD

Purpose

- AI Models
- Datasets
- Media
- Archive

---

# Future Plan

After resolving the SSD compatibility issue:

- SSDs will host production VM workloads.
- HDDs will become dedicated data and backup storage.
- Existing data will be migrated without changing the architecture.

---

# Design Goals

- Simple
- Reliable
- Easy to migrate
- Low maintenance
- Production-ready
