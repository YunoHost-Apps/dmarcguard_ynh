DMARCguard fonctionne comme un service systemd, derriere nginx.

Chemins utiles :

- Binaire et configuration applicative : `__INSTALL_DIR__`
- Base SQLite : `__DATA_DIR__/db.sqlite`
- Logs : `/var/log/__ID__/__ID__.log`

Les parametres IMAP sont ecrits dans `__INSTALL_DIR__/config.json`.

Pour modifier les identifiants IMAP, editez `config.json` puis redemarrez :

```bash
sudo systemctl restart __ID__
```
