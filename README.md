Liste Chaînée Circulaire en C

Description

Ce petit projet est un programme en langage C qui illustre l’utilisation des listes chaînées circulaires.
Une liste circulaire est une structure de données où le dernier élément pointe de nouveau vers le premier, ce qui permet de parcourir la liste en boucle.

Dans ce programme, on peut :
1-insérer un élément en tête de liste
2-insérer un élément en queue de liste
3-afficher tous les éléments de la liste
C’est un exemple pratique pour mieux comprendre la manipulation des pointeurs et des structures en C.

Compilation

Pour compiler le programme, utilisez la commande suivante :
gcc liste.c -o liste

Exécution

Une fois compilé, exécutez le programme avec :

./liste

Exemple d'exécution du programme 

Liste circulaire apres insertions en tete :
1 -> 5 -> 10 -> 20 ->  (retour a 1)

Liste circulaire apres insertions en queue :
10 -> 20 -> (retour a 1)

Objectif pédagogique

Ce programme m’a aidé à mieux comprendre :

comment fonctionne la mémoire dynamique en C (malloc, free)

le chaînage des nœuds avec des pointeurs

la différence entre insertion en tête et insertion en queue

l’intérêt d’une structure circulaire par rapport à une liste simple




