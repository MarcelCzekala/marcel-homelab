# marcel-homelab

My personal 24/7 homelab for learning Linux System Administration, Docker and GPU computing.

## About the project

Building hands-on experience with server management, containerization and AI infrastructure on my own hardware.

## Current Stack

### AI & GPU
- **Ollama** + **Open WebUI** — local LLMs with full GPU acceleration (RTX 3060 Ti 8GB)

### Monitoring
- Prometheus + Grafana
- NVIDIA DCGM Exporter (GPU metrics)
- Node Exporter

### Tools
- Docker & Docker Compose
- Portainer
- Tailscale

## Screenshots

**nvidia-smi**
![nvidia-smi](docs/screenshots/nvidia-smi.png)

**Running containers (docker ps)**
![docker ps](docs/screenshots/docker-ps.png)

**GPU Monitoring Dashboard**
![GPU Dashboard](docs/screenshots/grafana_load.png)

**System Overview**
![System Dashboard](docs/screenshots/grafana-system.png)

**Open WebUI**
![Open WebUI](docs/screenshots/openwebui_chat.png)

## Hardware
- CPU: AMD Ryzen 5 3500
- GPU: NVIDIA RTX 3060 Ti 8 GB
- RAM: 16 GB
- Storage: 256 GB SSD + 1 TB HDD

## Next steps
- Ansible playbooks
- Custom Bash automation scripts
- More security tools (CrowdSec, etc.)

---

Last updated: May 2026
=======
