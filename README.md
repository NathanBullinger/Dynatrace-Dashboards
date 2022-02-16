# Dynatrace Dashboards

This repository contains JSON files used to populate dashboards via API call or manual import. To import a dashboard via the UI, navigate to the 'Dashboards' page in your Dynatrace tenant and select 'Import Dashboard'. Management Zones are the recommended approach for filtering. 

Dynatrace Dashboard API Docs: https://www.dynatrace.com/support/help/shortlink/api-config-dashboards

Dynatrace Data Explorer Docs: https://www.dynatrace.com/support/help/shortlink/explorer


### Monitoring Overview Dashboard

A high-level monitoring dashboard containing a variety of commonly used metrics.

![Overview](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/Header.png)
![Host Health](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/Host%20Health.png)
![Service Health](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/Service%20Health.png)
![Process Health](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/Process%20Health.png)
![Database Health](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/Database%20Health.png)

[Link](https://github.com/NathanBullinger/Dynatrace-Dashboards/blob/master/Dashboard%20JSON%20Files/On-premise%20Application.json)

### Monitoring Overview Dashboard w/ Synthetic

Identical to Monitoring Overview, with the addition of synthetic HTTP monitor information

[Link](https://github.com/NathanBullinger/Dynatrace-Dashboards/blob/master/Dashboard%20JSON%20Files/On-premise%20Application%20with%20HTTP%20monitor.json)

![Synthetic Overview](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/On-prem%20App%20with%20Synthetic%20-%20Overview.png)

![Synthetic Overview](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/On-prem%20App%20with%20Synthetic%20-%20Details.png)

### PaaS Application Overview Dashboard

Identical to Monitoring Overview, with a non-operational focus on PaaS application health (i.e. no Host Health)

[Link](https://github.com/NathanBullinger/Dynatrace-Dashboards/blob/master/Dashboard%20JSON%20Files/PaaS%20Application.json)

### PaaS Application Overview Dashboard w/ Synthetic

Identical to PaaS Application Overview, with the addition of synthetic HTTP monitor information

[Link](https://github.com/NathanBullinger/Dynatrace-Dashboards/blob/master/Dashboard%20JSON%20Files/PaaS%20Application%20with%20HTTP%20Monitor.json)

### AWS Missing Permissions

Summary of Missing AWS Permissions that may prevent metric capture by Dynatrace. Use to...

 1. identify any integrations/credentials that have missing data
 2. identify missing permissions for a particular account
 3. validate that accounts have the appropriate permission level
 4. track any new missing permissions due to changes within AWS, or if new permissions are required for monitoring purposes

[Link](https://github.com/NathanBullinger/Dynatrace-Dashboards/blob/master/Dashboard%20JSON%20Files/AWS%20Missing%20Permissions.json)

![AWS Missing Permissions](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/AWS%20Missing%20Permissions.png)


### ActiveGate Health

Summary of ActiveGate health, including messages dropped/recieved, Network statistics, JVM/System CPU + Memory usage, and Extension/Synthetic engine health. 

[Link](https://github.com/NathanBullinger/Dynatrace-Dashboards/blob/master/Dashboard%20JSON%20Files/ActiveGate%20Health.json)

![ActiveGate Health](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/ActiveGateHealth.png)

### HTTP Monitor Overview

Summary of HTTP monitor health, featuring standard availability and response time metrics

[Link]()

![HTTP Monitor 1](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/HTTP%20Monitor%20Overview%201.png)
![HTTP Monitor 2](https://raw.githubusercontent.com/NathanBullinger/Dynatrace-Dashboards/master/Dashboard%20Images/HTTP%20Monitor%20Overview%202.png)
