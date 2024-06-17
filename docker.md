## Docker :

# ---------------- Containers ----------------
- **docker start container** : démarrer le container
- **docker stop container** : arrêter le container
- **docker ps** : afficher la liste des containers démarrés
- **docker ps -a** : afficher la liste de tous les containers (même arrêtés)
- **docker run --name nom_du_conteneur** : renommer un container
- **docker container prune** : supprimer tous les containers arrêtés

# ---------------- Images ----------------
- **docker pull nom_image** : télécharger une image
- **docker images** : afficher la liste des images
- **docker rmi nom_image** : supprimer une image (sauf si le container est en cours d'exécution)

# ---------------- Mode intéractif ----------------
- **docker run -it ubuntu bash** : utiliser le bash d'ubuntu