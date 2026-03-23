# 📊 Game Server Monitoring (Prometheus + Grafana)

Monitoring stack for tracking system and container performance using Prometheus and Grafana.

---

## 🚀 Overview

This project provides a lightweight monitoring solution for a self-hosted game server environment.

It collects system metrics and visualises them through dashboards.

---

## ⚙️ Stack

- Prometheus
- Grafana
- Node Exporter

---

## 📁 Structure

game-server-monitoring/
├── docker-compose.yml
├── prometheus/
│ └── prometheus.yml
└── README.md


---

## ▶️ Usage

```bash
docker compose up -d

Grafana: http://localhost:3000

Prometheus: http://localhost:9090
