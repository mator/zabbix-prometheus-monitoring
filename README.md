# Prometheus monitoring by zabbix

Currently monitored items:
- number of targets
- number of series/metrics
- number of queries being executed or waiting
- number of series appended in 5m interval

# installation

- add/copy prometheus.conf to /etc/zabbix/zabbix-agent.d/ and restart zabbix-agent 
- import prometheus template xml to zabbix
- link template to prometheus hosts

# usage

use "latest data" view for items being gathered
