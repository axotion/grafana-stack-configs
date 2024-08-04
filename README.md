## Example of LGTM stack that serves as a APM (Application Performance Monitoring) tool for a Node.js application. 

<img width="1334" alt="Screenshot 2024-08-04 at 23 13 49" src="https://github.com/user-attachments/assets/3e32f7ab-9a77-49c2-80cc-8292d58726e9">


## Stack
- Loki - for log aggregation
- Grafana - for visualization
- Prometheus - for storing short-term metrics from Tempo and Application API
- Tempo - for tracing
- Otel Collector - for collecting logs, metrics and traces from Api and redirecting them to Loki, Prometheus and Tempo
- Pyroscope - Collect profiles from Application API

## Screenshoots from Grafana

### Tempo
<img width="2714" alt="Screenshot 2024-08-04 at 23 24 15" src="https://github.com/user-attachments/assets/15dbee50-23d3-4133-84a0-bc937badf6b1">

### Dashboard from Loki data
<img width="2701" alt="Screenshot 2024-08-04 at 23 22 43" src="https://github.com/user-attachments/assets/adc8cbe0-69c0-4aba-b29a-639d3bae7604">

### Pyroscope
<img width="2697" alt="Screenshot 2024-08-04 at 23 21 57" src="https://github.com/user-attachments/assets/0b412a23-025f-45b6-a55d-e8106421f75a">

### Dashboard from OTLP Collector -> Prometheus data
<img width="2701" alt="Screenshot 2024-08-04 at 23 19 55" src="https://github.com/user-attachments/assets/3d3877c4-573e-443e-a68b-e1e6a9417057">

### Dashboard from API exposed metrics for prometheus
<img width="2714" alt="Screenshot 2024-08-04 at 23 18 27" src="https://github.com/user-attachments/assets/ece49bbc-cb79-453b-8ac6-6114d634849d">
