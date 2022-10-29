# Consul monitoring stack in Docker

`Consul` Service Discovery configuration with `VictoriaMetrics` metrics storage, `Prometheus` metrics scraping server and `Grafana` monitoring metrics dashboards configuration.

Just run `docker-compose.yaml` to see the magic:

```bash
docker-compose up -d
```

## Endpoints

- Consul – <http://127.0.0.1:8500>
- Grafana – <http://127.0.0.1:3000>
- Prometheus – <http://127.0.0.1:9090>
- Node Exporter – <http://127.0.0.1:9100>
- VictoriaMetrics – <http://127.0.0.1:8428>
