# fotomein

sudo firewall-cmd --add-port=2283/tcp --permanent
sudo firewall-cmd --reload


podman network create shared-network
podman-compose up -d
podman restart

