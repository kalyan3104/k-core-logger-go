# k-core-logger-go

Kalyan3104' logger subsystem written in go

## CLI options

### Logs producer (Kalyan3104 Node)

- `log-level`: comma-separated pairs of (`loggerName`, `logLevel`)
- `log-correlation`: option to include correlation elements in the logs
- `log-logger-name`: option to include logger name in the logs

Example:

```
--log-level="*:INFO,processor:DEBUG" --log-correlation --log-logger-name
```

### Logs viewer

- `level`: comma-separated pairs of (`loggerName`, `logLevel`)
- `correlation`: option to include correlation elements in the logs
- `logger-name`: option to include logger name in the logs

Example:

```
--level="*:INFO,processor:DEBUG" --correlation --logger-name
```
