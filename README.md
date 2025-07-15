# grafana

> [!CAUTION]
>
> **This repository is no longer mantained.**

## Deployment

```bash
git push
```

Grafana state is persisted across restarts through the use of a fly.io volume mounted at `/var/lib/grafana`.

Volume snapshots can be used to [restore a previous version](https://fly.io/docs/volumes/snapshots/#restore-a-volume-from-a-snapshot) of the installation.
