● Vérifier la version d'installation de docker avec la commande
○ docker --version
![alt text](/image/1.png)
● Tester les commandes de base dans le terminal :
○ docker info
![alt text](/image/2.png)
○ docker ps
![alt text](/image/3.png)
○ docker images
![alt text](/image/4.png)
○ docker run
![alt text](/image/5.png)
○ docker stop
![alt text](/image/6.png)
● Récupérer l’image Docker
○ docker pull
![alt text](/image/7.png)
○ docker images
![alt text](/image/8.png)
● Construisez le container Docker
Remplacer xxxx par un port valide
○ docker run -it --rm -p xxxx:80 “nom de l’image”
![alt text](/image/9.png)
○ Dans l’explorateur internet trouver le moyen d’accéder au
container
![alt text](/image/10.pne)
○ Relancer toutes les commandes de base ci-dessus dans le
terminal de votre choix
● Arrêter votre container
![alt text](/image/11.pne)
○ docker stop container_id
● Supprimer votre container
![alt text](/image/12.pne)
○ docker rm container_id

_4
● supprimer l’image Docker
○ docker rmi image_id
● Donner un exemple de ligne de commande pour ces actions
pour supprimer :
○ Un conteneur spécifique
docker rm container_id
○ Plusieurs conteneurs
docker rm container_id1 container_id2...
○ Tous les conteneurs arrêtés
docker container prune
○ Forcer la suppression d'un conteneur actif
docker rm -f container_id
○ Une image spécifique
docker rmi image_id
○ Plusieurs images
docker rmi image_id1 image_id2...
○ Toutes les images inutilisées
docker prune
○ Forcer la suppression d'une image
docker rmi -f image_id
○ Quel erreur est présente dans les commandes données
ci-dessus, donner la correction