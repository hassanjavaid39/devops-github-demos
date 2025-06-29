# 📊 Prometheus + Grafana + Alertmanager Monitoring Stack

This project sets up a production-grade monitoring stack using Docker Compose, featuring:

- 🔍 Prometheus – collects and stores time-series metrics
- 📈 Grafana – visualizes metrics in real-time dashboards
- 🖥️ Node Exporter – provides OS/server-level metrics
- ⚠️ Alertmanager – sends alerts on rule violations (e.g., CPU > 80%)

This setup is designed to simulate a real DevOps monitoring environment using open-source tools.

---

## 🚀 Quick Start

Make sure Docker is installed on your system.

```bash
git clone https://github.com/hassanjavaid39/prometheus-grafana-monitoring.git
cd prometheus-grafana-monitoring
docker-compose up -d

