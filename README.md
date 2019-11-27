# Prometheus Monitor

1. Place variables in a .env file.

1. To launch the monitoring stack, run
    ```
    docker-compose up -d
    ```

1. To launch a node-exporter container on a remote host, run:
    ```
    docker-compose up -d node-exporter
    ```

* * *

- Configure `prometheus/prometheus.yml` with the nodes you wish to monitor.

- Store Grafana dashboards in `grafana/dashboards/`

## Future Plans:
- Add cadvisor
- Add alertmanager


Look to expand on this by studying: https://github.com/stefanprodan/dockprom