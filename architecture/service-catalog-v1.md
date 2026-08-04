# Service Catalog v1

Status: Draft

## Purpose

This document defines every service that will run on the AkpinarLabs Platform.

---

| Service | VM | Container | Public | Purpose |
|----------|----|-----------|--------|---------|
| Coolify | core-01 | Yes | Yes | Application Deployment Platform |
| Nginx Proxy Manager | core-01 | Yes | No | Reverse Proxy Management |
| PostgreSQL | db-01 | Yes | No | Primary Database |
| Redis | db-01 | Yes | No | Cache & Queue |
| MinIO | db-01 | Yes | No | Object Storage |
| Ollama | ai-01 | Yes | No | Local LLM Engine |
| Open WebUI | ai-01 | Yes | Yes | AI Chat Interface |
| Grafana | monitor-01 | Yes | Yes | Dashboards |
| Prometheus | monitor-01 | Yes | No | Metrics Collection |
| Loki | monitor-01 | Yes | No | Log Aggregation |
| Uptime Kuma | monitor-01 | Yes | Yes | Service Monitoring |
| Portainer *(Optional)* | core-01 | Yes | No | Docker Management |

---

## Future Services

- Authentik
- Vaultwarden
- Gitea
- Forgejo
- Harbor
- Proxmox Backup Server
- Wazuh
- Home Assistant (Optional)

---

This catalog will evolve as new services are introduced.
