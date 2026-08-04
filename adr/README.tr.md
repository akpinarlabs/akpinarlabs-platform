# 🏛 Mimari Karar Kayıtları (ADR)

AkpinarLabs Platformu geliştirilirken alınan tüm önemli mühendislik kararları bu dizinde belgelenmektedir.

Bizim yaklaşımımıza göre mimari kararlar, kaynak kod kadar değerlidir.

Her önemli teknik karar aşağıdaki sorulara cevap vermelidir:

- Bu karar neden alındı?
- Hangi alternatifler değerlendirildi?
- Neden tercih edilmediler?
- Bu kararın sonuçları nelerdir?
- Bu süreçten ne öğrendik?

Bu sayede gelecekte projeye katkı sağlayacak herkes yalnızca **neyin** geliştirildiğini değil, **neden** geliştirildiğini de anlayabilir.

---

## ADR Yapısı

Her Mimari Karar Kaydı aşağıdaki bölümlerden oluşur:

1. Durum
2. Bağlam
3. Değerlendirilen Alternatifler
4. Karar
5. Gerekçeler
6. Sonuçlar
7. Kaynaklar (isteğe bağlı)

---

## Dosya İsimlendirme Standardı

```
PG-ADR-001-Why-Proxmox.md
PG-ADR-002-Why-Docker.md
PG-ADR-003-Why-PostgreSQL.md
```

Her ADR yalnızca tek bir mimari kararı temsil eder.

---

## Temel İlkemiz

> **Uygulamadan önce mimari.**

Hiçbir önemli geliştirme, mimari kararı belgelenmeden başlamaz.

---

**Chief Builder**

Ferhat Akpınar

AkpinarLabs
