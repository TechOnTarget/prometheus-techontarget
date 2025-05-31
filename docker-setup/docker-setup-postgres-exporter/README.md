# Postgres Monitoring via Postgres Exporter

[![PostgreSQL](postgres.png)](https://youtu.be/O0Xei_MRuYM)

### Prerequisitis

Docker and Docker compose should be installed


### Start the Prometheus and Grafana

Run the docker-comose.yml file to provision the container or Grafana and Prometheus.

cd docker-setup-postgres-exporter
docker-compose up -d

### Start the Postgres and Postgres Exporter

cd postgres-exporter
docker-compose up -d

### View the Data in Dashboard
PostgreSQL Overview Dashboard
Dashboard ID: 9628
Source: Grafana.com
Features:

Connections, transactions, locks

Buffer cache hit ratios

Table statistics

Disk & I/O usage

https://grafana.com/grafana/dashboards/9628-postgresql-database/


