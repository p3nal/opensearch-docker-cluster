### An Opensearch docker cluster

I'm using an unsecured image of Opensearch Dashboards so make sure you build that too using:
```bash
cd dashboards
docker build --tag=opensearch-dashboards-no-security .
```
ref: https://opensearch.org/docs/latest/security-plugin/configuration/disable/
