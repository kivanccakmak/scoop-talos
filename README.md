# Talos Scoop bucket

Install Talos CLI on Windows:

```powershell
scoop bucket add talos https://github.com/kivanccakmak/scoop-talos
scoop install talos/talcli
talcli login --device
```

The package checksum is pinned per architecture. Release binaries are
Authenticode-signed and timestamped by Talos.
Scoop bucket for Talos command-line tools
