DMARCguard necessite des identifiants IMAP valides pour recuperer les rapports DMARC agreges.

Preparation avant installation :

1. Creez une boite dediee sur votre serveur mail YunoHost (par exemple `dmarc@votredomaine.tld`). Il est recommande d'utiliser cette boite uniquement pour les rapports DMARC.
2. Pointez votre politique DMARC vers cette boite (`rua=mailto:dmarc@votredomaine.tld`).
3. Utilisez l'hote/port IMAP et les identifiants de cette boite pendant l'installation.

Par defaut, les messages traites sont marques comme lus. Vous pouvez aussi configurer votre serveur mail ou des regles de boite pour supprimer periodiquement les messages lus de cette boite dediee.
