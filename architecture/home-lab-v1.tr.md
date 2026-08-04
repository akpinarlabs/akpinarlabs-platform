# 🏠 HomeLab Mimarisi v1

**Sürüm:** 1.0

**Durum:** Aktif

**Tarih:** 2026

---

# Amaç

Bu belge, AkpinarLabs HomeLab altyapısının fiziksel ve mantıksal mimarisini tanımlar.

HomeLab; AkpinarLabs bünyesinde geliştirilecek tüm yazılım, yapay zekâ, robotik, mobil uygulama ve bulut servislerinin geliştirme, test ve üretim ortamı olarak kullanılacaktır.

Bu altyapı yalnızca bir ev sunucusu değildir.

AkpinarLabs Platformu'nun temel mühendislik altyapısını oluşturur.

---

# Hedefler

HomeLab aşağıdaki hedefler doğrultusunda tasarlanmıştır.

- Kendi kendine yetebilen (Self-Hosted) altyapı
- Bulut tabanlı mimari
- Yapay zekâ çalıştırmaya hazır platform
- Güvenli ağ yapısı
- Kolay yönetilebilir sanallaştırma
- Merkezi servis yönetimi
- Eğitim ve Ar-Ge ortamı
- Üretim servisleri
- Gelecekte yüksek erişilebilirlik desteği

---

# Fiziksel Mimari

```
İnternet
        │
        ▼
1 Gbps Fiber İnternet
        │
        ▼
Statik IP Adresi
213.153.252.54
        │
        ▼
Zyxel EX3501-T0 Modem
        │
        ▼
FortiGate 30D
        │
        ▼
HP ProLiant ML350 G6
        │
        ▼
Proxmox VE
        │
        ▼
Sanal Makineler
        │
        ▼
Docker / Uygulamalar
```

---

# Donanım

## Sunucu

HP ProLiant ML350 G6

---

## İşlemci

Intel Xeon E5620

---

## Bellek

48 GB RAM

İleride yükseltilecektir.

---

## Depolama

Mevcut:

- 240 GB SSD (Sistem Diski)
- 1 TB HDD
- 1 TB HDD
- 1 TB HDD

Planlanan:

- +240 GB SSD
- +240 GB SSD

---

# Sanallaştırma Platformu

Hypervisor olarak **Proxmox VE** kullanılmaktadır.

Platform üzerinde;

- KVM Sanal Makineler
- LXC Konteynerler

çalıştırılacaktır.

---

# Ağ Yapısı

Yerel Ağ

192.168.1.0/24

Gateway

FortiGate 30D

192.168.1.99

---

# Aktif Servisler

Şu anda çalışan servisler:

- Nginx Proxy Manager
- Pangolin
- Eğitim Laboratuvarları
- Siber Güvenlik Laboratuvarları
- Geliştirme Ortamları

---

# Gelecekte Eklenecek Servisler

- Docker
- Coolify
- PostgreSQL
- Redis
- MinIO
- Git Sunucusu
- CI/CD
- AI Platformu
- Ollama
- Object Storage
- Monitoring
- Merkezi Log Yönetimi
- Kimlik Yönetimi
- Yedekleme Sunucusu

---

# Uzun Vadeli Vizyon

HomeLab yalnızca kişisel bir sunucu değildir.

AkpinarLabs Platformu'nun tamamı bu altyapı üzerinde geliştirilecek, test edilecek ve yayınlanacaktır.

Her mobil uygulama,

her web servisi,

her API,

her yapay zekâ modeli,

her robotik proje,

önce bu HomeLab üzerinde doğacaktır.

---

# Tasarım İlkeleri

Bu altyapı aşağıdaki prensiplere göre geliştirilmektedir.

- Açık Kaynak Önceliklidir
- Dokümantasyon Önce Gelir
- Güvenlik Tasarımın Bir Parçasıdır
- Ölçeklenebilirlik
- Tekrar Üretilebilirlik
- Basitlik
- Sürekli Gelişim

---

# Sonraki Aşamalar

Bu belge ilerleyen sürümlerde aşağıdaki bölümlerle genişletilecektir.

- Ağ Topolojisi
- VLAN Yapısı
- Firewall Kuralları
- Sanal Makine Mimarisi
- Docker Mimarisi
- Yapay Zekâ Katmanı
- Depolama Mimarisi
- İzleme Sistemi
- Yedekleme Stratejisi
- Felaket Kurtarma Planı

---

**Chief Builder**

Ferhat Akpınar

AkpinarLabs
