DMARCguard nécessite des identifiants IMAP valides pour récupérer les rapports DMARC agrégés.

Préparation avant installation :

1. Créez une boîte dédiée sur votre serveur mail YunoHost (par exemple `dmarc@votredomaine.tld`). Il est recommandé d'utiliser cette boîte uniquement pour les rapports DMARC.
2. Pointez votre politique DMARC vers cette boîte (`rua=mailto:dmarc@votredomaine.tld`).
3. Utilisez l'hôte/port IMAP et les identifiants de cette boîte pendant l'installation.

Par défaut, les messages traités sont marqués comme lus. Vous pouvez aussi configurer votre serveur mail ou des règles de boîte pour supprimer périodiquement les messages lus de cette boîte dédiée.
