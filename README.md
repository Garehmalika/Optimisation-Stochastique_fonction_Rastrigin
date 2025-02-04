**Optimisation de la fonction de Rastrigin avec le Recuit Simulé et l'Algorithme Génétique**

**Description du Projet**
Ce projet explore deux méthodes d'optimisation pour résoudre le problème d'optimisation de la fonction de Rastrigin, une fonction de test couramment utilisée dans l'optimisation numérique en raison de ses nombreux minima locaux. Les deux méthodes implémentées dans ce projet sont :

Recuit Simulé (Simulated Annealing) : Une technique d'optimisation stochastique inspirée du processus de refroidissement des métaux.
Algorithme Génétique (Genetic Algorithm) : Un algorithme d'optimisation inspiré du processus de sélection naturelle.
Fonction de Rastrigin

La fonction de Rastrigin est définie par :
![Formule de Rastrigin](path/to/rastrigin_formula.png)

Avec :

- \( A = 10 \) (un paramètre constant).
- \( n \) est le nombre de variables d'entrée (dans ce projet, \( n = 2 \)).
- \( x_i \in [-5.12, 5.12] \) pour chaque variable \( x_i \).




où **A = 10** et :

$$
x_i \in [-5.12 ; 5.12]
$$

Son **minimum global** se trouve à **l'origine**, où sa valeur est **nulle**.
Avec 
𝐴
=
10
A=10 et 
𝑥
𝑖
∈
[
−
5.12
,
5.12
]
x 
i
 ∈[−5.12,5.12], et où 
𝑛
n est le nombre de variables. Le but est de trouver le minimum global, qui est en 
(
0
,
0
)
(0,0) et a une valeur de 
0
0.

**Objectifs:**
Comparer les performances de l'algorithme génétique et du recuit simulé appliqués à la fonction de Rastrigin.
Étudier l'impact des différents paramètres (taille de population, nombre de générations, taux de croisement, etc.) sur la convergence des deux méthodes.
Visualiser les résultats de chaque méthode, notamment la convergence de la fonction et les meilleures solutions trouvées.
