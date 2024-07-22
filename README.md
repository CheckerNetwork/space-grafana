# grafana

## Deployment

```bash
git push
```

Grafana state is persisted across restarts through the use of a fly.io volume mounted at `/var/lib/grafana`.

Volume snapshots can be used to restore a previous version of the installation.
