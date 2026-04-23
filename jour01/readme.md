● Vérifier la version d'installation de docker avec la commande\
○ docker --version\
![alt text](/jour01/image/1.png?raw=true)\
● Tester les commandes de base dans le terminal :\
○ docker info\
![alt text](/jour01/image/2.png?raw=true)\
○ docker ps\
![alt text](/jour01/image/3.png?raw=true)\
○ docker images\
![alt text](/jour01/image/4.png?raw=true)\
○ docker run\
![alt text](/jour01/image/5.png?raw=true)\
○ docker stop\
![alt text](/jour01/image/6.png?raw=true)\
● Récupérer l’image Docker\
○ docker pull\
![alt text](/jour01/image/7.png?raw=true)\
○ docker images\
![alt text](/jour01/image/8.png?raw=true)\
● Construisez le container Docker\
Remplacer xxxx par un port valide\
○ docker run -it --rm -p xxxx:80 “nom de l’image”\
![alt text](/jour01/image/9.png?raw=true)\
○ Dans l’explorateur internet trouver le moyen d’accéder au\
container\
![alt text](/jour01/image/10.png?raw=true)\
○ Relancer toutes les commandes de base ci-dessus dans le\
terminal de votre choix\
● Arrêter votre container\
![alt text](/jour01/image/11.png?raw=true)\
○ docker stop container_id\
● Supprimer votre container\
![alt text](/jour01/image/12.png?raw=true)\
○ docker rm container_id\
\
_4\
● supprimer l’image Docker\
○ docker rmi image_id\
● Donner un exemple de ligne de commande pour ces actions\
pour supprimer :\
○ Un conteneur spécifique\
docker rm container_id\
○ Plusieurs conteneurs\
docker rm container_id1 container_id2...\
○ Tous les conteneurs arrêtés\
docker container prune\
○ Forcer la suppression d'un conteneur actif\
docker rm -f container_id\
○ Une image spécifique\
docker rmi image_id\
○ Plusieurs images\
docker rmi image_id1 image_id2...\
○ Toutes les images inutilisées\
docker prune\
○ Forcer la suppression d'une image\
docker rmi -f image_id\
○ Quel erreur est présente dans les commandes données\
ci-dessus, donner la correction\
\
job02
\
● Créer l’image docker à partir de ce projet de sorte que le
fichier dockerfile soit pris en compte\
![alt text](/jour01/image/13.png?raw=true)\
● Lancer l’image docker que vous venez de créer et lancer un
container avec\
![alt text](/jour01/image/14.png?raw=true)\
● Vérifiez s’il est lancé et d’autres commandes de bases que
vous avez faites dans le premier exercice\
![alt text](/jour01/image/15.png?raw=true)\
● Vérifiez le résultat faites en sorte que vos modifications soient
prises en compte dans votre image docker et votre container\
![alt text](/jour01/image/16.png?raw=true)\
● Comprenez ce qu’il faut faire pour que ce soit pris en compte\
![alt text](/jour01/image/17.png?raw=true)\
● Publier sur votre compte docker une image docker, et rendez
la disponible à un membre de votre promo\
![alt text](/jour01/image/18.png?raw=true)\
● Récupérer une image docker d’un membre de votre promo et
refaites les tests et modifications sur celle-ci (citez l’auteur
de l’image d’origine dans la page)\
![alt text](/jour01/image/19.png?raw=true)\
● Publier sur votre Docker l’image modifié du membre de votre
promo\
![alt text](/jour01/image/20.png?raw=true)\
\
job03
\
● Ouvrir docker-desktop
● Placez vous sur le menu à gauche dans “images”\
● Trouver le terminal dans Docker Desktop\
● Chercher l’image docker cité ci-dessus par une commande dans ve dernier\
● Récupérer l’image Docker dans “Docker-Desktop”\
● Observer quand vous avez validé votre commande ce qui c’est passé dans votre fenêtre au dessus\
![alt text](/jour01/image/21.png?raw=true)\
● Lancer un container avec cette image et assignez lui le port 8600 en considérant que l’image est configuré sur le port 8080 et en conservant l'accès à l’invite de commande\
○ Trouvé les deux méthodes avec des ports différents de le faire (invite de commande et ???)\
![alt text](/jour01/image/22.png?raw=true)\
● observer quand vous avez validé votre commande ce qui c’est passé dans votre fenêtre au dessus\
![alt text](/jour01/image/23.png?raw=true)\
● Ouvrir votre explorateur et trouver le moyen d’accéder au container construit\
![alt text](/jour01/image/24.png?raw=true)\
● Accéder et jouer un peu dans votre explorateur internet (faites des captures du jeux en cours “3 au moins”)\
![alt text](/jour01/image/25.png?raw=true)\
● Arrêter votre container par son ID (2 manière de trouver l’ID)\
![alt text](/jour01/image/26.png?raw=true)\
● Supprimer le container (2 manières)\
● observer quand vous avez validé votre commande ce qui c’est passé dans votre fenêtre au dessus\
![alt text](/jour01/image/27.png?raw=true)\
● supprimer l’image docker de super mario (2 manières)\
● observer quand vous avez validé votre commande ce qui c’est passé dans votre fenêtre au dessus\
![alt text](/jour01/image/28.png?raw=true)\
\
job04
\
● créer un fichier index.php affichant les info sur le serveur apache (trouver la commande php pour cela, il n'y aura que la balise php et une commande qui en fait que 10 caractères dans le fichier)\
● créer un dockerfile qui générera un environnement apache pour afficher cette page\
● Application sur le port 80\
● exposer sur le port 8080\
● créer l’image\
![alt text](/jour01/image/29.png?raw=true)\
● créer le container\
![alt text](/jour01/image/30.png?raw=true)\
● faite le tourner\
![alt text](/jour01/image/31.png?raw=true)\
![alt text](/jour01/image/33.png?raw=true)\
● stopper le\
![alt text](/jour01/image/32.png?raw=true)\
\
job05
\
● Créer le fichier Dockerfile et le rédiger.\
● Construire une image Docker pour servir les fichiers du jeu.\
![alt text](/jour01/image/34.png?raw=true)\
● Créer un volume nommé “game-results” pour stocker les résultats dans un fichier resuslts.json et le fichier save.php\
![alt text](/jour01/image/35.png?raw=true)\
● Exécuter le conteneur pour rendre le jeu accessible via un navigateur sur le port 8080.\
● Envoyer les résultats disponibles dans le volume et dans results.json\
![alt text](/jour01/image/36.png?raw=true)\
● Trouver la commande Docker qui permet de vérifier que la création du volume est effective\
![alt text](/jour01/image/37.png?raw=true)\
● faire en sorte que le volume soit lié au container et vérifier que les résultats s’enregistre bien dans le volume dans results.json par le biais du fichier save.php se trouvant aussi dans le volume\
● Trouver la commande qui affiche le contenu du container\
![alt text](/jour01/image/38.png?raw=true)\
● Trouver la commande qui affiche le contenu du volume\
![alt text](/jour01/image/39.png?raw=true)\
● Trouver comment faire ces deux actions dans docker-desktop et le terminal\
![alt text](/jour01/image/40.png?raw=true)\
![alt text](/jour01/image/41.png?raw=true)\
● Afficher le contenu de results.json avec une commande et avec docker-desktop et dans le terminal\
![alt text](/jour01/image/42.png?raw=true)\
● Jouer au morpion pendant plusieurs parties pour générer des résultats\
● Les résultat seront visible dans un fichier results dans le volume\
![alt text](/jour01/image/43.png?raw=true)\
\
job06
\
![alt text](/jour01/image/44.png?raw=true)\
![alt text](/jour01/image/45.png?raw=true)\
○ Testez la connexion entre le backend et la base de données.\
![alt text](/jour01/image/46.png?raw=true)\
![alt text](/jour01/image/47.png?raw=true)\
○ Accédez à Adminer via l'URL http://localhost:8081 pour gérer la base de données.\
![alt text](/jour01/image/48.png?raw=true)\
○ Accès au backend via http://localhost:3000 :
■ Route / : Retourne un message de bienvenue.\
![alt text](/jour01/image/49.png?raw=true)\
■ Route /api/status : Vérifie le statut de la base de données et retourne l'heure actuelle par une api\
![alt text](/jour01/image/50.png?raw=true)\
○ Accès au frontend via http://localhost:8080 affichant l'état de l'API.
![alt text](/jour01/image/51.png?raw=true)\
○ Accès à mysql via http://localhost:3306 :
■ Vous aurez une erreur :
![alt text](/jour01/image/52.png?raw=true)\
■ Trouvez le moyen dans le terminal d’accéder au container et donc au mysql en invite de commande.\
![alt text](/jour01/image/53.png?raw=true)\
■ Une fois dans le shell MySQL afficher la base de données\
![alt text](/jour01/image/54.png?raw=true)\
■ Trouvez la commande pour quitter le shell MySQL\
![alt text](/jour01/image/55.png?raw=true)\