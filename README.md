# Haskellmc systemd files

Systemd service file for the haskellmc modpack.

## Installation

```bash
git clone https://github.com/tkaden4/haskell-modpack-server-service haskellmc
# Install the `.service` file
cp haskellmc/haskellmc.service /etc/systemd/system/haskellmc.service
```

You must have the server installed at `/opt/haskellmc/`
