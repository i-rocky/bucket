# Rocky Scoop Bucket

Personal Scoop bucket for Rocky's CLI tools.

## Install
```powershell
scoop bucket add rocky https://github.com/i-rocky/scoop-bucket
```

## Apps
- [`watch`](https://github.com/i-rocky/watch) — GNU watch for Windows that feels like Linux/macOS.
- [`pixr`](https://github.com/i-rocky/pixr) — Cross-platform CLI for image manipulation (resize, crop, pad, convert).
- [`dockerx`](https://github.com/i-rocky/dockerx) — Hardened Docker dev environment launcher.
- [`caffeinate`](https://github.com/i-rocky/caffeinate) — Cross-platform caffeinate command for Linux and Windows.
- [`docker-win-net-connect`](https://github.com/i-rocky/docker-win-net-connect) — WireGuard tunnel between Windows host and Docker Desktop VM for subnet access.

## Auto-update
This bucket includes a GitHub Actions workflow that runs `checkver.ps1` to
update manifests automatically.
