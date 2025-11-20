# Prometheus-monitoring

A complete observability stack built on AWS using Prometheus, Node Exporter, Grafana, and Alertmanager. Includes EC2 provisioning, Prometheus configuration, alerting setup, and dashboards for real-time system monitoring.

This project sets up a complete Prometheus-based monitoring solution on AWS using:

- Prometheus (metrics collection and scraping)
- Node Exporter (system metrics from target EC2 instance)
- Grafana (visualization)
- Alertmanager (alerting via email/webhook)

You will deploy and configure each tool across four EC2 instances:

- Prometheus Server (Ubuntu 22.04)
- Target Node with Node Exporter (Amazon Linux 2)
- Grafana Server (Ubuntu 22.04)
- Alertmanager Server (Ubuntu 22.04)

![Prometheus Web UI IMAGE](./images/Prometheus%20Web%20UI.png)
![Grafana dashboard IMAGE](./images/Grafana%20Dashboard.png)
![Alertmanager web status IMAGE](./images/Alertmanager%20web.png)
