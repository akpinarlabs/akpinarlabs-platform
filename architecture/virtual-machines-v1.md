# Virtual Machine Architecture v1

## Purpose

This document defines the virtual machine architecture used by the AkpinarLabs platform.

The goal is to separate infrastructure services from applications and AI workloads.

---

# Virtual Machines

## VM100

Name

docker-host

Purpose

Docker Engine

Docker Compose

Reverse Proxy

Application Containers

---

## VM101

Name

monitoring

Purpose

Grafana

Prometheus

Uptime Kuma

Loki

---

## VM102

Name

ai-platform

Purpose

Ollama

Open WebUI

Qdrant

Redis

PostgreSQL

---

## VM103

Name

automation

Purpose

n8n

Flowise

Automation Services

---

## VM104

Name

development

Purpose

Development

Testing

Temporary workloads

---

# Principles

One responsibility per VM.

Infrastructure is isolated.

Easy backup.

Easy migration.

Easy scaling.
