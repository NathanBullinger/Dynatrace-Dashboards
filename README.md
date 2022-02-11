# Dynatrace Dashboards

This repository contains JSON files used to populate dashboards via API call or manual import. To import a dashboard via the UI, navigate to the 'Dashboards' page in your Dynatrace tenant and select 'Import Dashboard'. Management Zones are the recommended approach for filtering. 

Dynatrace API Docs: https://www.dynatrace.com/support/help/shortlink/section-api

Dynatrace Data Explorer Docs: https://www.dynatrace.com/support/help/shortlink/explorer


### Monitoring Overview Dashboard

A high-level monitoring dashboard containing a variety of commonly used metrics.

![Overview](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/Header.png)
![Host Health](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/Host%20Health.png)
![Service Health](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/Service%20Health.png)
![Process Health](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/Process%20Health.png)
![Database Health](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/Database%20Health.png)


### Monitoring Overview Dashboard w/ Synthetic

Identical to Monitoring Overview, with the addition of synthetic HTTP monitor information


### PaaS Application Overview Dashboard

Identical to Monitoring Overview, with a non-operational focus on PaaS application health (i.e. no Host Health)


### PaaS Application Overview Dashboard w/ Synthetic

Identical to PaaS Application Overview, with the addition of synthetic HTTP monitor information

### AWS Missing Permissions

Summary of Missing AWS Permissions that may affect the metrics captured by Dynatrace. Use to quickly find any accounts that have missing data, or to validate that existing accounts have the appropriate permission level

![AWS Missing Permissions](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/AWS%20Missing%20Permissions.png)
