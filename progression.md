Apres relexion, j'ai decomposer mon projet en plusieurs parties :

- Mettre en place les regles du jeu ( Pierre > Ciseaux / Ciseaux > Papier / Papier > Pierre )
- Faire l'ascpet aléatoire à l'aide du module Random
- Faire en sorte que le joueur puisse choisir entre Pierre, Papier et Ciseaux
- Créer le système de points, et faire en sorte que la partie se finnise quand un des deux joueurs à 3 points

19/12/2021 : Début du projet, je cherche un moyen de décompser mon projet en plusieurs parties

21/12/2021 : J'ai pensé que associé la pierre a un chiffre, le papier a un chiffre et le ciseau à un chiffre était une bonne idée,
donc j'ai décidé de créer la fonction "écrire" qui associe le nombre 1 à la pierre, le nombre 2 au papier et lme nombre 3 aux ciseaux.

22/12/2021 : Création des variables "ton_score" qui représente le score du joueur, "mon_score" qui représente le score du robot et "fin" qui représente le nombre de points nécessaires pour gagner le jeu.

27/12/2021 : Création de la fonction "augmenter_scores", qui est chargée de mettre à jour les scores des joueurs en fonction de leur coup, or j'ai rencontré un problème car sans le "global" un message d'erreur apparaissait, j'ai dû faire des recherche pour trouver que le "global" est indispensable, sous peine du message d'erreur "UnboundLocalError: local variable 'mon_score' referenced before assignment " j'ai alors apris que les variables mon_coup et ton_coup sont globales. Cela signifie qu'elles ont été déclarées dans le programme principal, donc hors de la procédure.

06/01/2022 : Mise en place de l'affichage du programme pour pouvoir jouer au jeu.

08/01/2022 et 09/01/2022 : Réddation du GitHub et preparation pour l'oral.

Ce que j'ai retenu :

- Les procédures et les fonctions permettent de découper le programme en sous-programmes.
- Cela permet d'augmenter la lisibilité et d'éviter d'écrire plusieurs fois la même chose.
- La différence entre une fonction et une procédure, c'est qu'une fonction renvoie une ou plusieurs valeurs.
- Ce qu'étaient des variables globales
