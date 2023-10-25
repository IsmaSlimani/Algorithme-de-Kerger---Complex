# Projet Complexité, algorithmes randomisés et approchés

# Algorithme de Karger

En théorie des graphes, une coupe d’un graphe est une partition des sommets en deux
sous-ensembles disjoints.
On appelle cardinal d’une coupe l’ensemble des arêtes ayant une extrémité dans chaque
sous-ensemble de la partition. Une coupe minimum d’un graphe est donc, une coupe contenant un nombre minimal d’arêtes.

Il peut y avoir pour un même graphe, plusieurs coupes minimums, c’est-à-dire plusieurs coupes différentes mais de même cardinal : le cardinal minimum.
Le problème de la coupe minimum consiste alors, étant donné un graphe, à déterminer
une coupe minimum.

Pour ce faire, l’une des solutions étudiées en cours est l’algorithme de Karger.
L’algorithme de Karger est un algorithme probabiliste qui permet de déterminer une
coupe minimum d’un graphe non orienté à partir d’une méthode de contraction d’arête.
Cette procédure consiste, étant donné un graphe G et une arête aléatoire e = (u, v), à
fusionner les sommets u et v pour former un unique sommet uv relié à la fois aux voisins
de u et aux voisins de v (en évitant les boucles).

L’algorithme consiste simplement à répéter l’opération de contraction plusieurs fois sur
le graphe jusqu’à n’avoir que deux sommets. Les deux sommets représentent la partition
de sommets, et les arêtes entre eux deux sont les arêtes de la coupe.

Notre travail consiste donc à évaluer la complexité de l’algorithme de Karger ainsi que
de ses améliorations à travers trois parties distinctes que voici :

— Implémentation et analyse de l’algorithme de Karger sur deux structures de données
de graphes

— Amplification du succès de l’algorithme en étudiant la complexité et probabilité de
succès de l’algorithme de Karger itéré

— Étude de l’algorithme de Karger-Stein
L’objectif étant de répondre à toutes les questions de l’énoncé du projet à travers ce
rapport ainsi que le code joint.

