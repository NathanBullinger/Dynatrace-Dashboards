# Dynatrace Dashboards

This repository contains JSON files used to populate dashboards via API call. All of the dashboards within this repository are intended to be uploadable with no additional configuration required.

Dynatrace API Docs: https://www.dynatrace.com/support/help/shortlink/section-api

### Monitoring Overview Dashboard
![Monitoring Overview](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Sample%20Images/Monitoring%20Overview.png)

A high-level monitoring dashboard containing a variety of "essential" metrics.


### Service Health Dashboard
![Service Health](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Sample%20Images/Service%20Health.png)

A high-level service health dashboard intended to reveal the worst performing services at any given time. This dashboard can be filtered using management zones or optional tagging rules. It is recommended to filter data in large environments to prevent noise and clutter.


### Load Test Analysis Dashboard
![Load Test Analysis](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Sample%20Images/Load%20Test%20Analysis.png)

This dashboard is designed to visually compare volume during load tests to error and response time metrics. This dashboard can be filtered using management zones or optional tagging rules to restrict data to only display services related to the load test.
