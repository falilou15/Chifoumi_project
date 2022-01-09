Apres relexion, j'ai decomposer mon projet en plusieurs parties :

- Mettre en place les regles du jeu ( Pierre > Ciseaux / Ciseaux > Papier / Papier > Pierre )
- Faire l'ascpet aléatoire à l'aide du module Random
- Faire en sorte que le joueur puisse choisir entre Pierre, Papier et Ciseaux
- Créer le système de points, et faire en sorte que la partie se finnise quand un des deux joueurs à 3 points

19/12/2021 : Début du projet, je cherche un moyen de décompser mon projet en plusieur partie
21/12/2021 : J'ai penser au fait qu'assosié la pierre a un chiffre, le papier a un chiffre et le ciseaux à un chiffre était une bonne idée,
donc j'ai décider de créer la fonction "ecrire" qui associe le nombre 1 à la pierre, le nombre 2 au papier et lme nombre 3 aux ciseaux.
22/12/2021 : Création des variables "ton_score" qui représente le score du joueur, "mon_score" qui représente le score du robot et "fin" qui représente le nombre de points nécessaires pour gagner le jeu.
27/12/2021 : Création de la fonction "augmenter_scores", qui est chargée de mettre à jour les scores des joueurs en fonctions de leur coup, or j'ai rencontrer un probleme car sans le "global" un message d'érreur apparaissait, j'ai du faire des recherche pour touver que le "global" est indispensable, sous peine du message d'erreur "UnboundLocalError: local variable 'mon_score' referenced before assignment " j'ai alors apris que les variables mon_coup et ton_coup sont globales. Cela signifie qu'elles ont été déclarées dans le programme principal, donc hors de la procédure.
06/01/2022 : Mise en place de l'affichage du programme pour povoir jouer au jeu.
08/01/2022 et 09/01/2022 : Réddation du GitHub et preparation pour l'oral.
