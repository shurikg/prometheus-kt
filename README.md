# prometheus-kt

The idea of this repo is learn how to create E2E solution of prometheus, prometheues exporter and grafana dashboard.

The steps of training.

1. Create jenkins with dummy job that generate dummy request.log file ( similar to the nexus request.log file )
2. Create exporter that will extract metrics from this dummy request.log file
3. Create prometheus and use exporter to get relevant metrics
4. Create dashboard in grafana for collected metrics.

