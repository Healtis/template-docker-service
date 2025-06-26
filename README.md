# Template Docker Service
Ce repository détaille l'arborescence qui doit être utilisé dans le cadre de déploiement de service Docker.  

## Après la récupération du répertoire
Après la récupération du répertoire et avant utilisation, il faut :
- Décommenter les lignes dans le fichier `.gitignore`
- Supprimer le fichier `.gitkeep` dans les répertoires suivants :
1. `/data`
2. `/logs`
3. `/scripts`
4. `/secrets`

Cela aura pour objectif de ne pas envoyer les données confidentielles sur le répertoire distant pendant le développement. 