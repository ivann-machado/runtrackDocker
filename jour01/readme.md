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
