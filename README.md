# PGinD - Prometheus + Grafana in Docker

o11y (observability)

grafanaのdashboardカッコ良いね!!!

## Quick Start
```bash
$ git clone ...

# access https://api.slack.com/apps
# to create a Slack app and generate a webhook URL
$ cp alertmanager/config.yaml.example alertmanager/config.yaml
# add slack webhook URL to alertmanager/config.yaml

$ docker compose up -d
# Grafana at http://localhost:3000
# Prometheus at http://localhost:9090

$ docker compose down
```

## References
- https://hub.docker.com/r/grafana/grafana
- https://hub.docker.com/r/prom/prometheus
- https://grafana.com/docs/grafana/latest/setup-grafana/installation/docker/
- https://prometheus.io/docs/prometheus/latest/installation/
