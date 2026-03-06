# Proxmox Monitoring Stack

Ansible-based deployment for Prometheus, Alertmanager, Grafana, pve-exporter, node exporter targets, and Ceph monitoring.

Install these in the LXC
apt update
apt install -y git python3 python3-pip pipx
pipx ensurepath
pipx install ansible
pipx inject ansible ansible-lint