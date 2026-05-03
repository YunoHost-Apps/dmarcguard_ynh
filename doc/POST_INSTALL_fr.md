DMARCguard est installé.

Accès : <https://__DOMAIN____PATH__>

Prochaines étapes :

1. Vérifiez que votre adresse DMARC `rua` pointe vers la boîte YunoHost dédiée configurée à l'installation.
2. Attendez les rapports agrégés (souvent 24-48h).
3. Si aucun rapport n'apparaît, vérifiez les logs : `sudo journalctl -u __ID__ -f`
