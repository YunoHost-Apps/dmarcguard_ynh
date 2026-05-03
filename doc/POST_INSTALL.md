DMARCguard is installed.

Access it at: <https://__DOMAIN____PATH__>

Next steps:

1. Ensure your DMARC `rua` address points to your dedicated YunoHost mailbox configured during install.
2. Wait for aggregate reports (often 24-48h).
3. Check app logs if no report appears: `sudo journalctl -u __ID__ -f`
