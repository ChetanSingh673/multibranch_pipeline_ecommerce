### Ports to Enable in Security Group

| Service | Port |
| :--- | :--- |
| HTTP | 80 |
| HTTPS | 443 |
| SSH | 22 |
| Jenkins | 8080 |
| SonarQube | 9000 |
| Prometheus | 9090 |
| Node Exporter | 9100 |
| Grafana | 3000 |
---

## Prerequisites
---

This guide assumes an Ubuntu/Debian-like environment and sudo privileges.

---
## System Update & Common Packages
---

```bash
sudo apt update
sudo apt upgrade -y

# Common tools
sudo apt install -y bash-completion wget git zip unzip curl jq net-tools build-essential ca-certificates apt-transport-https gnupg fontconfig
