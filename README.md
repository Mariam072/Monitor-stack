# 📊 Automated Monitoring Stack  
## Prometheus • Alertmanager • Grafana  
### Using Ansible & Podman

This project provides a **fully automated monitoring stack** using **Prometheus**, **Alertmanager**, and **Grafana**, deployed with **Ansible** and running on **Podman** containers.

The stack monitors **multiple nodes**, sends **email alerts**, and automatically starts after a server reboot.

---

## 🧱 Architecture

Monitoring Server runs:
- Prometheus
- Alertmanager
- Grafana

Target Nodes run:
- Node Exporter

