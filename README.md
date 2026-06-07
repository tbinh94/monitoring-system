# Monitoring System with Prometheus, Grafana and Alertmanager

## Overview

A self-hosted monitoring system deployed on Ubuntu Server using Docker Compose.

The system collects infrastructure metrics, visualizes them through Grafana dashboards, and sends automated Telegram notifications when alert conditions are triggered.

## Features

* Real-time monitoring of CPU, Memory, Disk and Network usage
* Prometheus metrics collection
* Grafana dashboards
* Alert rules based on resource thresholds
* Telegram notification integration
* Docker Compose deployment

## Architecture

Node Exporter → Prometheus → Alertmanager → Telegram

```
                 ↓

             Grafana
```

## Technologies

* Ubuntu Server
* Docker Compose
* Prometheus
* Grafana
* Node Exporter
* Alertmanager
* Telegram Bot API

## Screenshots

### Docker Containers

![Docker](screenshots/docker-containers-running.png)

### Grafana Dashboard

![Grafana](screenshots/grafana-dashboard.png)

### Alert Rules

![Rules](screenshots/prometheus-alert-rules.png)

### Alert Firing

![Alert](screenshots/prometheus-alert-firing.png)

### Telegram Notification

![Telegram](screenshots/telegram-alert.png)

