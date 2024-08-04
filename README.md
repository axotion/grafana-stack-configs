Example of LGTM stack that serves as a APM (Application Performance Monitoring) tool for a Node.js application. It uses the following technologies:
- Loki - for log aggregation
- Grafana - for visualization
- Mimir - for storing long-term metrics
- Prometheus - for storing short-term metrics from Tempo and Application API
- Tempo - for tracing
- Otel Collector - for collecting logs, metrics and traces from Api and redirecting them to Loki, Prometheus and Tempo