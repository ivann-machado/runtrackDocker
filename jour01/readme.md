● Vérifier la version d'installation de docker avec la commande
○ docker --version
![alt text](https://github.com/ivann-machado/runtrackDocker/jour01/image/blob/main/1.png?raw=true)
● Tester les commandes de base dans le terminal :
○ docker info
![alt text](https://github.com/ivann-machado/runtrackDocker/jour01/image/blob/main/2.png?raw=true)
○ docker ps
![alt text](https://github.com/ivann-machado/runtrackDocker/jour01/image/blob/main/3.png?raw=true)
○ docker images
![alt text](https://github.com/ivann-machado/runtrackDocker/jour01/image/blob/main/4.png?raw=true)
○ docker run
![alt text](https://github.com/ivann-machado/runtrackDocker/jour01/image/blob/main/5.png?raw=true)
○ docker stop
![alt text](https://github.com/ivann-machado/runtrackDocker/jour01/image/blob/main/6.png?raw=true)
● Récupérer l’image Docker
○ docker pull
![alt text](https://github.com/ivann-machado/runtrackDocker/jour01/image/blob/main/7.png?raw=true)
○ docker images
![alt text](https://github.com/ivann-machado/runtrackDocker/jour01/image/blob/main/8.png?raw=true)
● Construisez le container Docker
Remplacer xxxx par un port valide
○ docker run -it --rm -p xxxx:80 “nom de l’image”
![alt text](https://github.com/ivann-machado/runtrackDocker/jour01/image/blob/main/9.png?raw=true)
○ Dans l’explorateur internet trouver le moyen d’accéder au
container
![alt text](https://github.com/ivann-machado/runtrackDocker/jour01/image/blob/main/10.png?raw=true)
○ Relancer toutes les commandes de base ci-dessus dans le
terminal de votre choix
● Arrêter votre container
![alt text](https://github.com/ivann-machado/runtrackDocker/jour01/image/blob/main/11.png?raw=true)
○ docker stop container_id
● Supprimer votre container
![alt text](https://github.com/ivann-machado/runtrackDocker/jour01/image/blob/main/12.png?raw=true)
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