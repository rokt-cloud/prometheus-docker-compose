# Simple Prometheus Docker Compose Setup

This docker compose file allows you to spin up a local dev prometheus environment. Do not use in production!

Simply run

`docker-compose up`

and you can then access the prometheus UI under

`http://localhost:9090/`

and the alertmanager UI

`http://localhost:9093/`

If you want to add static custom targets, configure the `scrape_configs` in the `prometheus/prometheus.yaml` file.
