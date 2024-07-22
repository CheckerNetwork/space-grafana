# grafana

## Deployment

```bash
git push
```

Grafana state is persisted across restarts through the use of a fly.io volume mounted at `/var/lib/grafana`.

Volume snapshots can be used to [restore a previous version](https://github.com/filecoin-project/lotus/issues/11589) of the installation.
