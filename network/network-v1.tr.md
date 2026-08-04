# Ağ Mimarisi v1

Sürüm: 1.0

Durum: Aktif

Tarih: 2026

---

# Amaç

Bu belge AkpinarLabs Platformu'nun ağ mimarisini tanımlar.

---

# İnternet

Fiber İnternet

1 Gbps İndirme

100 Mbps Yükleme

Statik IP

213.153.252.54

---

# Ağ Akışı

İnternet

↓

Zyxel EX3501-T0

↓

FortiGate 30D

↓

Yerel Ağ

↓

HP ML350 G6

↓

Proxmox VE

↓

Sanal Makineler

↓

Konteynerler

↓

Uygulamalar

---

# WAN

Statik Genel IP

213.153.252.54

---

# LAN

Ağ

192.168.1.0/24

Gateway

192.168.1.99

---

# Temel Bileşenler

Firewall

FortiGate 30D

Reverse Proxy

Nginx Proxy Manager

DNS

Cloudflare

Sanallaştırma

Proxmox VE

Kablosuz Ağ

UniFi Access Point

---

# Aktif Servisler

Nginx Proxy Manager

192.168.1.88

Pangolin

192.168.1.113

Cyber-W

192.168.1.150

UniFi AP

192.168.1.115

Gateway

192.168.1.99

---

# Ağ Tasarım İlkeleri

- Önce Güvenlik
- En Az Yetki
- Self Hosted
- Zero Trust Uyumlu
- Cloud Entegrasyonu
- Kolay Yönetim
- Tam Dokümantasyon

---

# Gelecek

Docker Ağı

Internal DNS

WireGuard

VLAN

Monitoring

Service Discovery

Load Balancing

High Availability

---

Chief Builder

Ferhat Akpınar
