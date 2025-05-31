# Mysql Monitoring via Mysql Exporter

[![PostgreSQL](mysql.png)](https://youtu.be/x8uAQfbeJ-8)


### Prerequisitis

Docker and Docker compose should be installed


### Start the Prometheus and Grafana

Run the docker-comose.yml file to provision the container or Grafana and Prometheus.

cd docker-setup-mysql 
docker-compose up -d

### Start the Mysql and Mysql Exporter

cd dmysql-and-mysqlexporter
docker-compose up -d

### View the Data in Dashboard
Use Public Dashboard Id - 14057 Reference - Link https://grafana.com/grafana/dashboards/14057-mysql/