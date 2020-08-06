**Blue-green** is just a switch from on version to another on one go. **Rolling-Update** a granular switch where you change one at a time. Finally **Canary** is when you do add manual steps in a Rolling One for the sake of monitoring.

In order to pick **what to change** have groups divided geographically, by time, by business use pattern, also internal resources and in all of that find the right granularity

When monitoring keep don't forget to add proper tags, p99 (not only p95 or p90), outliers and anomalies **dashboards**. So you should be **looking for** latency, errors type and but also the amount, throughput and resources saturation such CPU load, Storage capacity)   