# Sanal Makine Mimarisi v1

## Amaç

Bu belge, AkpinarLabs platformunda kullanılacak sanal makine mimarisini tanımlar.

Amaç altyapı servislerini, uygulamaları ve yapay zekâ servislerini birbirinden ayırmaktır.

---

# Sanal Makineler

## VM100

Ad

docker-host

Görev

Docker Engine

Docker Compose

Reverse Proxy

Uygulama Containerları

---

## VM101

Ad

monitoring

Görev

Grafana

Prometheus

Uptime Kuma

Loki

---

## VM102

Ad

ai-platform

Görev

Ollama

Open WebUI

Qdrant

Redis

PostgreSQL

---

## VM103

Ad

automation

Görev

n8n

Flowise

Otomasyon Servisleri

---

## VM104

Ad

development

Görev

Geliştirme

Test

Geçici çalışma ortamı

---

# Tasarım İlkeleri

Her VM yalnızca tek bir sorumluluk üstlenir.

Altyapı servisleri birbirinden izole edilir.

Yedekleme kolaydır.

Taşıma kolaydır.

Yatay büyüme kolaydır.
