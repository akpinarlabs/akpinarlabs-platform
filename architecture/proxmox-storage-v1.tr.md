# Proxmox Depolama Standardı v1

## Amaç

Bu belge, AkpinarLabs platformu için geçici depolama mimarisini tanımlar.

Bu yapı mevcut donanım üzerinde çalışacak şekilde tasarlanmıştır ve ileride SSD sorunu çözüldüğünde kolayca yeni yapıya taşınabilecek şekilde planlanmıştır.

---

# Mevcut Disk Yapısı

## Disk 1

Tür

SSD

Görev

- Proxmox VE
- Sanal makine sistem diskleri
- LXC sistem diskleri

---

## Disk 2

Tür

HDD

Görev

- Docker kalıcı verileri
- Ortak uygulama verileri
- Genel depolama alanı

---

## Disk 3

Tür

HDD

Görev

- Yedekler
- ISO dosyaları
- VM şablonları
- Snapshot dosyaları

---

## Disk 4

Tür

HDD

Görev

- Yapay zeka modelleri
- Veri kümeleri
- Medya dosyaları
- Arşiv

---

# Gelecek Planı

SSD uyumluluk sorunu çözüldüğünde:

- SSD'ler üretim sanal makineleri için kullanılacaktır.
- HDD'ler yalnızca veri ve yedek depolama amacıyla kullanılacaktır.
- Mevcut mimari değiştirilmeden veri taşıma işlemi gerçekleştirilecektir.

---

# Tasarım Hedefleri

- Basit
- Güvenilir
- Kolay taşınabilir
- Düşük bakım gereksinimi
- Üretim ortamına uygun
