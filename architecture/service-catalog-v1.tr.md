# Servis Kataloğu v1

Durum: Taslak

## Amaç

Bu belge AkpinarLabs Platformu üzerinde çalışacak tüm servisleri tanımlar.

---

| Servis | VM | Konteyner | Public | Görevi |
|---------|----|-----------|--------|---------|
| Coolify | core-01 | Evet | Evet | Uygulama Yayınlama Platformu |
| Nginx Proxy Manager | core-01 | Evet | Hayır | Reverse Proxy Yönetimi |
| PostgreSQL | db-01 | Evet | Hayır | Ana Veritabanı |
| Redis | db-01 | Evet | Hayır | Önbellek ve Kuyruk |
| MinIO | db-01 | Evet | Hayır | Nesne Depolama |
| Ollama | ai-01 | Evet | Hayır | Yerel LLM Motoru |
| Open WebUI | ai-01 | Evet | Evet | Yapay Zekâ Arayüzü |
| Grafana | monitor-01 | Evet | Evet | Dashboard |
| Prometheus | monitor-01 | Evet | Hayır | Metrik Toplama |
| Loki | monitor-01 | Evet | Hayır | Log Yönetimi |
| Uptime Kuma | monitor-01 | Evet | Evet | Servis İzleme |
| Portainer *(İsteğe Bağlı)* | core-01 | Evet | Hayır | Docker Yönetimi |

---

## Gelecekte Eklenecek Servisler

- Authentik
- Vaultwarden
- Gitea
- Forgejo
- Harbor
- Proxmox Backup Server
- Wazuh
- Home Assistant (İsteğe Bağlı)

---

Bu katalog platform geliştikçe güncellenecektir.
