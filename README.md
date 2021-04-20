# Jeu de la balle
## Auteur : Lilian Cizeron

### Principe :
Le principe de ce programme est de mettre en place un protocole réseau permettant de joué à un jeu. Le jeu en question est un envoi de paquet aléatoirement vers un poste du réseau, et ainsi de suite, jusqu'à ce que le nombre de rebond tombe à 0. Ensuite, tout le monde envoi son résultat au serveur qui annonce le résultat.

### Fonctionnement :
Les postes sont sur un réseau local, défini dans le fichier `constant.py`. Il y a aussi la possibilité d'activer la recherche des joueurs disponible en décommentant la ligne `#LISTE_IP = network_discovery()`. Le serveur lance le fichier `main_serveur.py`et les clients le fichier `main.py`.
