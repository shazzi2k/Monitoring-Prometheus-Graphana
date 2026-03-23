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

## 🧭 Architecture

Prometheus collects system metrics from the host using Node Exporter.

Grafana connects to Prometheus as a data source and visualises these metrics through dashboards.

---

## 🚀 Overview

This project provides a monitoring stack for a self-hosted game server environment.

It collects system metrics such as CPU, memory, and disk usage, and displays them in real-time dashboards using Grafana.

---

## 🔮 Future Improvements

- Container-level monitoring (cAdvisor)
- Alerting (e.g. high CPU usage)
- Integration with Discord bot for notifications


---

## ▶️ Usage

```bash
docker compose up -d

Grafana: http://localhost:3000

Prometheus: http://localhost:9090


