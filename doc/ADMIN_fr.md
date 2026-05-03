DMARCguard fonctionne comme un service systemd, derriere nginx.

Chemins utiles :

- Binaire et configuration applicative : `__INSTALL_DIR__`
- Base SQLite : `__DATA_DIR__/db.sqlite`
- Logs : `/var/log/__ID__/__ID__.log`

Les parametres IMAP sont ecrits dans `__INSTALL_DIR__/config.json`.

Comportement par defaut : les messages traites sont marques comme lus (`mark_as_seen=true`).
Pour le nettoyage, vous pouvez configurer une retention cote serveur ou des regles de boite pour supprimer les messages lus.
Il est fortement recommande d'utiliser une boite dediee uniquement aux rapports DMARC.
