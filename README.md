# cf-k6-buildpack

Buildpack to install k6 to a Cloud Foundry app

# What does this buildpack do?

This buildpack simply installs the k6 binary to a Cloud Foundry app. The k6 binary will be copied to the `app` directory.

## File and Versions
The k6 binary in this repo was built with the following command:

```
xk6 build latest \
  --with github.com/oleiade/xk6-kv
```

Here is the version of k6, and extensions and versions included:

- `k6` - v0.51.0 (go1.21.0, windows/amd64)
- `xk6-kv` - https://github.com/grafana/k6/releases/tag/v0.50.0

# License

MIT License