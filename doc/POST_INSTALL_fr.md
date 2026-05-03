DMARCguard est installe.

Acces : <https://__DOMAIN____PATH__>

Prochaines etapes :

1. Verifiez que votre adresse DMARC `rua` pointe vers la boite YunoHost dediee configuree a l'installation.
2. Attendez les rapports agreges (souvent 24-48h).
3. Si aucun rapport n'apparait, verifiez les logs : `sudo journalctl -u __ID__ -f`
