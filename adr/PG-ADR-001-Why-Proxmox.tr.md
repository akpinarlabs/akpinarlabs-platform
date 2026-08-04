# PG-ADR-001

# Neden Proxmox?

## Durum

Kabul Edildi

---

## Bağlam

AkpinarLabs Platformu; üretim servisleri, geliştirme ortamları ve gelecekteki yapay zekâ altyapısını çalıştırabilecek esnek, ölçeklenebilir ve kendi sunucumuzda barındırılabilen bir sanallaştırma platformuna ihtiyaç duymaktadır.

Platform aşağıdaki özellikleri desteklemelidir:

- Sanal Makineler
- Linux Konteynerleri
- Snapshot Yönetimi
- Yedekleme
- Canlı Taşıma (İleride)
- High Availability (İleride)
- PCI Passthrough (İleride)

---

## Değerlendirilen Alternatifler

- VMware ESXi
- Microsoft Hyper-V
- XCP-ng
- Sadece Docker
- Bare Metal Linux

---

## Karar

AkpinarLabs'ın ana sanallaştırma platformu olarak **Proxmox VE** seçilmiştir.

---

## Gerekçeler

- Açık Kaynak
- Geniş Topluluk
- Güçlü Web Arayüzü
- Yerleşik LXC Desteği
- Yerleşik KVM Desteği
- Snapshot Özelliği
- Kolay Yedekleme
- Esnek Depolama Yapısı
- REST API
- Güçlü Dokümantasyon

---

## Sonuçlar

### Avantajlar

- Düşük Maliyet
- Kolay Yönetim
- Öğrenmeye Uygun Platform
- Kurumsal Özellikler
- Ölçeklenebilir Yapı

### Dezavantajlar

- Linux bilgisi gerektirir.
- Cluster yapısı dikkatli planlanmalıdır.

---

## Tarih

2026

---

**Chief Builder**

Ferhat Akpınar
