# Renovate test 2

Part of https://github.com/renovatebot/renovate/discussions/28280.

## Execution command

```
docker run -v ./config.json:/config.json -e RENOVATE_CONFIG_FILE=/config.json -e RENOVATE_TOKEN=********************** -e LOG_LEVEL=debug --rm renovate/renovate
```

Logs for initial execution are at [`initial-log-20240410.txt`](initial-log-20240410.txt). This was run against Renovate 37.280.0.
