# Docker Monitoring Stack (Prometheus + Grafana + Node Exporter + cAdvisor)

Dieses Repository enthält einen einfachen Monitoring-Stack auf Basis von Docker und Docker Compose.

## Komponenten

- **Prometheus** – Zeitreihen-Datenbank für Metriken
- **Node Exporter** – Systemmetriken des Hosts (CPU, RAM, Disk, usw.)
- **cAdvisor** – Metriken für Docker-Container
- **Grafana** – Visualisierung der Metriken (Dashboards)

## Voraussetzungen

- Docker
- Docker Compose (oder `docker compose` CLI)
- Empfohlen: Linux-Host (für vollständige cAdvisor / Node-Exporter-Daten)

## Start

Im Projektverzeichnis:

```bash
docker compose up -d
# oder alternativ:
# docker-compose up -d

