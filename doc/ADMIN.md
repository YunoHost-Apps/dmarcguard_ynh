DMARCguard runs as a systemd service and is reverse-proxied by nginx.

Useful paths:

- Binary and app config: `__INSTALL_DIR__`
- Runtime database: `__DATA_DIR__/db.sqlite`
- Logs: `/var/log/__ID__/__ID__.log`

The IMAP settings are written in `__INSTALL_DIR__/config.json`.

To update IMAP credentials, edit `config.json` and restart the app:

```bash
sudo systemctl restart __ID__
```
