# Ağ Mimarisi v1

Sürüm: 1.0

Durum: Aktif

Tarih: 2026

---

# Amaç

Bu belge, AkpinarLabs Platformu'nun genel ağ mimarisini tanımlar.

Güvenlik nedeniyle iç IP adresleri, firewall kuralları, DNS kayıtları ve altyapı detayları bu herkese açık dokümantasyonda paylaşılmamaktadır.

---

# İnternet

Fiber İnternet Bağlantısı

Statik Genel IP

(Gizli)

---

# Üst Düzey Ağ Mimarisi

İnternet

↓

Cloudflare

↓

Firewall

↓

Özel Ağ

↓

Sanallaştırma Platformu

↓

Uygulamalar

↓

Kullanıcılar

---

# Ağ Katmanları

## Kenar Katmanı

- Fiber İnternet
- Cloudflare
- Kurumsal Firewall

## Çekirdek Katmanı

- Özel Yerel Ağ
- Sanallaştırma Platformu

## Platform Katmanı

- Reverse Proxy
- Uygulama Servisleri
- Yapay Zekâ Servisleri
- Geliştirme Ortamı

---

# Altyapı Bileşenleri

- Kurumsal Firewall
- Reverse Proxy
- Sanallaştırma Platformu
- Kablosuz Ağ
- Geliştirme Bilgisayarları

---

# Ağ Tasarım İlkeleri

- Güvenlik Önceliklidir
- En Az Yetki Prensibi
- Zero Trust Uyumlu
- Self Hosted
- Bulut Entegrasyonu
- Yüksek Erişilebilirlik Hazır
- Tam Dokümantasyon

---

# Gelecek

- VLAN Yapısı
- WireGuard VPN
- Internal DNS
- Service Discovery
- Monitoring
- Load Balancing
- Çok Düğümlü Altyapı

---

# Güvenlik Notu

Güvenlik nedeniyle iç IP adresleri, firewall kuralları, DNS kayıtları ve altyapı detayları herkese açık olan bu dokümanda paylaşılmamaktadır.

---

Chief Builder

Ferhat Akpınar
