# Platform Mimarisi v1

Durum: Taslak

## Genel Bakış

AkpinarLabs Platformu modüler ve servis odaklı bir mimari üzerine inşa edilmiştir.

Her temel platform bileşeni; güvenlik, ölçeklenebilirlik ve yönetilebilirliği artırmak amacıyla kendine ait ayrı bir sanal makine üzerinde çalışacaktır.

---

## Platform Yapısı

İnternet

↓

Cloudflare

↓

FortiGate Firewall

↓

Proxmox VE

↓

VM100  core-01

↓

Docker Platformu

↓

Uygulamalar

---

## Sanal Makineler

| VM ID | Hostname | Görev |
|--------|----------|--------|
| VM100 | core-01 | Platform Çekirdek Servisleri |
| VM101 | db-01 | Veritabanı Servisleri |
| VM102 | ai-01 | Yapay Zekâ Servisleri |
| VM103 | monitor-01 | İzleme ve Log Yönetimi |
| VM104 | dev-01 | Geliştirme ve Test |
| VM105 | backup-01 | Yedekleme Servisleri |

---

## Tasarım İlkeleri

- Her Sanal Makinenin Tek Bir Sorumluluğu Vardır
- Güvenlik Önceliklidir
- Kolay Yedeklenebilir
- Bağımsız Ölçeklenebilir
- Yüksek Erişilebilirliğe Hazır
- Öncelik Self Hosted

---

Bu belge AkpinarLabs Platformu'nun üst düzey mimarisini tanımlar.
