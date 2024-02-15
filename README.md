# Monitoring System with Prometheus and Grafana

## Overview

This project aims to provide a comprehensive monitoring system using Prometheus and Grafana. It allows monitoring various services such as Apache HTTP Server, MySQL, PostgreSQL, system resources, and network performance.

## Features

- **Prometheus**: Collects and stores metrics from the monitored services.
- **Grafana**: Visualizes metrics through customizable dashboards.
- **Node Exporter**: Collects system-level metrics from Linux servers.
- **Apache Exporter**: Monitors Apache HTTP Server metrics.
- **MySQL Exporter**: Monitors MySQL database metrics.
- **PostgreSQL Exporter**: Monitors PostgreSQL database metrics.
- **Blackbox Exporter**: Monitors network performance metrics.
- **Alertmanager**: Handles alerts and notifications based on defined rules.

## Prerequisites

- Docker and Docker Compose installed on your system.

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/monitoring-system.git




   # Monitoring System

## Getting Started

**1. Navigate to the project directory:**

```bash
cd monitoring-system


**2. Update configurations:**

- Modify `docker-compose.yml` with your specific configurations for services and exporters.
- Update configuration files in respective directories (prometheus/, grafana/, exporters/, alertmanager/).

**3. Start the monitoring stack:**

bash
docker-compose up -d


## Accessing Services

**Prometheus:**

- Open http://localhost:9090 in your browser to access the Prometheus UI.

**Grafana:**

- Open http://localhost:3000 in your browser to access the Grafana UI.
- Login with username `admin` and password `<YOUR_ADMIN_PASSWORD>`.

**Import Dashboards (optional):**

- If you have custom dashboards, you can import them into Grafana from the `grafana/dashboards/` directory.

## Configuration

- `prometheus/prometheus.yml`: Prometheus configuration file.
- `grafana/grafana.ini`: Grafana configuration file.
- Exporter configuration files under the `exporters/` directory.
- `alertmanager/alertmanager.yml`: Alertmanager configuration file.

## Customization

- Adjust scrape targets, alerting rules, and dashboard configurations as per your monitoring requirements.
- Customize Grafana dashboards to visualize metrics relevant to your infrastructure.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Boni Yeamin


