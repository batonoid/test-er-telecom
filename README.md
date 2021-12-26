# test-er-telecom
# Quick start Grafana+Prom+Note-exporter and jBPM+Postgresql
docker-compose up -d 

# Service availability
- Grafana http://<ip/host>/grafana
- jBPM http://<ip/host>/ or http://<ip/host>/business-central/

# Default credentials
- Grafana admin admin
- jBPM wbadmin wbadmin

# About project
- The grafana has a "Docker host" dashboard, it shows the main indicators of the host machine.
- Application ports, except for Nginx, are closed for external access, Nginx proxies two applications to port 80 from ports 3000 (grafana) and 8080 (jBPM).
