# Coreum Network monitoring tool

This docker compose bundle runs a prometheus scraper and feeds it into Grafana. 
Currently Tendermint metrics are scraped and show in the graphs.

https://docs.tendermint.com/master/nodes/metrics.html

Tendermint Promtheus port is set to default: 26660

* Make sure Docker is installed and running.

To run the bundle type:

```
docker-compose up -d
```


Navigate to:

```http://localhost:3100/d/UJyurCTWz/coreum-network-monitoring?orgId=1&from=now-5m&to=now&refresh=1s```


To stop:

```
docker-compose down
```

