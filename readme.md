## Intro
* A docker-compose stack to demo kafka JMX monitoring and Prometheus alertmanager slack integration

## Run
```bash
cd jmx-prometheus
docker-compose up -d
```

## Alert Rules

Alert Rules
```
shared-assets/prometheus/prometheus-config/alert_rules.yml
```

Slack Config
```
shared-assets/prometheus/alertmanager-config/alertmanager.yml
```