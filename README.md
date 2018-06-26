# Geth prometheus metrics

Collect and visualize [geth](https://github.com/ethereum/go-ethereum) metrics with prometheus and grafana.

## Run example

```bash
> docker-compose up -d
```

Runs `geth --rinkeby`, prometheus and grafana.
Open `localhost:10007` (admin:admin) for explore geth metrics dashboard.

## Dashboard

![Dashboard Screenshot](screen.png)

## Snapshot

See dashboard [snapshot](https://snapshot.raintank.io/dashboard/snapshot/nxZB4UEhyo2zvMZNzBUfb7jlTAnE57fF?orgId=2).

## TODOS

* check and fix pannels units;
