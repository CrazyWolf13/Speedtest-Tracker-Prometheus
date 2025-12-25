## Speedtest-Tracker-Prometheus

> [!NOTE]  
> Special Thanks to @masterwishx for creating this awesome dashboard, please leave credits to him, as I've only adapted this board to work with Prometheus instead of InfluxDBv2!
> Here is the Original Repository: https://github.com/masterwishx/Speedtest-Tracker-v2-InfluxDBv2

A dashboard to display data exported by Speedtest Tracker. Avalible Now at Grafana Dashboard 17808
(https://grafana.com/grafana/dashboards/17808-speedtest-tracker-v2-influxdbv2/)

This dashboard shows data collected by Speedtest Tracker https://github.com/alexjustesen/speedtest-tracker and scraped by Prometheus.

### Info
![Screenshot 2024-08-14 202917](https://github.com/user-attachments/assets/aab1ed25-2e70-4486-b540-4da6306418b6)
![Screenshot 2024-08-14 202935](https://github.com/user-attachments/assets/37685a7d-9d58-4987-a4dd-2ebeabaebc49)

### Updates

- **25.12.2025**
  - Initial Version, converted from InfluxDB to Prometheus

### Steps

```
1. Activate Prometheus Integration like described here: https://docs.speedtest-tracker.dev/settings/data-platforms/prometheus

2. Configure Grafana to use your Prometheus instance.

4. Load Dashboard in Grafana

7. Enjoy
```

![image](https://raw.githubusercontent.com/alexjustesen/speedtest-tracker-docs/refs/heads/main/.gitbook/assets/prometheus_settings.png)
[How to: Add Prometheus Datasource to Grafana](https://grafana.com/docs/grafana/latest/datasources/prometheus/configure/)
