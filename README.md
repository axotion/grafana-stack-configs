## Example of LGTM stack that serves as a APM (Application Performance Monitoring) tool for a Node.js application. 

<img width="1334" alt="Screenshot 2024-08-04 at 23 13 49" src="https://github.com/user-attachments/assets/3e32f7ab-9a77-49c2-80cc-8292d58726e9">


### Stack
- Loki - for log aggregation
- Grafana - for visualization
- Prometheus - for storing short-term metrics from Tempo and Application API
- Tempo - for tracing
- Otel Collector - for collecting logs, metrics and traces from Api and redirecting them to Loki, Prometheus and Tempo
- Pyroscope - Collect profiles from Application API
