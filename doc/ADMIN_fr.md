DMARCguard fonctionne comme un service systemd, derrière nginx.

Chemins utiles :

- Binaire et configuration applicative : `__INSTALL_DIR__`
- Base SQLite : `__DATA_DIR__/db.sqlite`
- Logs : `/var/log/__ID__/__ID__.log`

Les paramètres IMAP sont écrits dans `__INSTALL_DIR__/config.json`.

Comportement par défaut : les messages traités sont marqués comme lus (`mark_as_seen=true`).
Pour le nettoyage, vous pouvez configurer une rétention côté serveur ou des règles de boîte pour supprimer les messages lus.
Il est fortement recommandé d'utiliser une boîte dédiée uniquement aux rapports DMARC.
