# SCTR CMU GHOSTS repo

This is a temporary repo for files needed for Ansible deployment (2023-06-11).

- `docker-compose.yml`: customized (known-working) docker compose for GHOSTS API server
- `ghosts-client-linux-v7.0.0`: most recent GHOSTS client for Linux (needs API server edit in ./config/application.json)
- `ghosts-client-linux-v7.0.0-config`: holds Linux-specific application.json and timeline.json
- `ghosts-client-x64-v7.0.0`: most recent GHOSTS client for Windows (needs API server edit in ./config/application.json)
- `ghosts-client-x64-v7.0.0-config`: holds Windows-specific application.json and timeline.json
- `grafana_config/`: for necessary files to push to API server for Grafana data viz dashboards
- 