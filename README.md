# Haskellmc systemd files

Systemd service file for the haskellmc modpack.

## Installation

```bash
git clone https://github.com/tkaden4/haskellmc
# Install the `.service` file
cp haskellmc/haskellmc.service /etc/systemd/system/haskellmc.service
systemctl daemon-reload
```

You must have the server installed at `/opt/haskellmc/`
