DMARCguard runs as a systemd service and is reverse-proxied by nginx.

Useful paths:

- Binary and app config: `__INSTALL_DIR__`
- Runtime database: `__DATA_DIR__/db.sqlite`
- Logs: `/var/log/__ID__/__ID__.log`

The IMAP settings are written in `__INSTALL_DIR__/config.json`.

Default behavior: processed messages are marked as read (`mark_as_seen=true`).
For mailbox cleanup, you can configure server-side retention or mailbox rules to delete read messages.
Using a mailbox dedicated only to DMARC reports is strongly recommended.
