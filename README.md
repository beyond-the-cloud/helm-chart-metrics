# helm-chart-metrics

Repository for Prometheus &amp; Grafana Helm Chart
## Deploy the helm chart

1. Download dependencies

    ```bash
    cd metrics
    helm dependency update
    ```

2. Install the helm chart

    ```bash
    helm install prometheus .
    ```
