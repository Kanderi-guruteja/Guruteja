# AI Operations Triage  
**Author: Guruteja Kanderi**

The idea is to build an AI model to detect anomalies inside the organization and alert the operations team.

Usually, this can be done with Prometheus by extracting Prometheus telemetry data to Grafana and checking the KPIs. We can configure Grafana to send notifications to Slack or Microsoft Teams by setting up channel configurations based on KPI thresholds.

But here, I would like to get Prometheus data, highly stimulative APIs, or any other important server metrics — summarize them, elaborate the error, and notify the on-field support engineer based on the severity.

I would also like to organize the KPI alerts and provide options for automatic KPI issue triage.
