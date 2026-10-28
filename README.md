# scoop-bucket

Personal [Scoop](https://scoop.sh) bucket.

## Usage

```powershell
scoop bucket add rifqiabd https://github.com/rifqiabd/scoop-bucket
scoop install rifqiabd/win-service-manager
```

Run it as `win-service-manager` or the shorter `wsm` shim:

```powershell
wsm
wsm -version
```

## Available manifests

| Manifest | Description |
| --- | --- |
| [win-service-manager](bucket/win-service-manager.json) | Terminal UI for managing Windows services |

## Updating

```powershell
scoop update
scoop update win-service-manager
```
