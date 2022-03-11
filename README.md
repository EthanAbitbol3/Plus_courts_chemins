# Plus_courts_chemins

Nous allons considérer des multi graphes orientés pondérés par le temps. Soit G un tel multigraphe.
On va supposer que G est sans circuit et nous allons définir 4 types de “plus courts” chemins qui ont
chacun sa propre importance. Ensuite, nous transformerons ce multigraphe en un graphe classique qui va
nous permettre de concevoir des algorithmes afin de calculer les 4 types de chemins minimaux. Enfin,
nous allons implémenter et tester un algorithme du type 4 par programmation linéaire en faisant appel à
GUROBI.

Supposons que G soit un réseau de transport aérien où chaque sommet
reprèsente un aéroport et le nombre sur chaque arc soit le jour (date) de départ d’un vol dont la
ville de dèpart est l’extrèmité initiale et la destination est l’extrémité finale de l’arc.
