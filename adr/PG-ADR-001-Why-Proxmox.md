# PG-ADR-001

# Why Proxmox?

**Status:** Accepted

**Date:** 2026

---

# Context

AkpinarLabs requires a modern, flexible and self-hosted virtualization platform capable of running production services, development environments and future AI workloads.

The platform must support:

- Virtual Machines (KVM)
- Linux Containers (LXC)
- Snapshot Management
- Backup
- REST API
- Storage Flexibility
- High Availability (future)
- Live Migration (future)
- PCI Passthrough (future)

The chosen platform should also provide a low-cost solution suitable for long-term learning, experimentation and production use.

---

# Alternatives Considered

- VMware ESXi
- Microsoft Hyper-V
- XCP-ng
- Bare Metal Linux
- Docker Only

---

# Decision

AkpinarLabs adopts **Proxmox VE** as the primary virtualization platform for the entire infrastructure.

All production services, development environments and future platform components will be deployed on Proxmox unless there is a documented architectural reason to choose another solution.

---

# Reasons

Proxmox was selected because it provides:

- Open Source
- Enterprise-grade virtualization
- Native KVM support
- Native LXC support
- Snapshot management
- Flexible storage architecture
- Built-in backup capabilities
- Excellent web interface
- REST API
- Large community
- Excellent documentation
- Low operational cost
- Easy maintenance

---

# Consequences

## Positive

- Low infrastructure cost
- Easy VM and container management
- Scalable architecture
- Strong learning platform
- Suitable for education and production
- Excellent integration with Docker and future Kubernetes deployments

## Negative

- Requires Linux knowledge
- Cluster configuration requires planning
- Enterprise repository requires a subscription (Community repository will be used)

---

# Future Impact

This decision becomes the foundation of the entire AkpinarLabs Platform.

Future infrastructure components including Docker, Coolify, PostgreSQL, Redis, MinIO, AI services and application hosting will be deployed on top of Proxmox.

---

# References

- https://www.proxmox.com/
- https://pve.proxmox.com/wiki/

---

# Approved By

**Chief Builder**

Ferhat Akpınar

AkpinarLabs
