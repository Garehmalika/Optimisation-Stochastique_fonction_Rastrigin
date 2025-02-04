**Optimisation de la fonction de Rastrigin avec le Recuit Simulé et l'Algorithme Génétique**

**Description du Projet**
Ce projet explore deux méthodes d'optimisation pour résoudre le problème d'optimisation de la fonction de Rastrigin, une fonction de test couramment utilisée dans l'optimisation numérique en raison de ses nombreux minima locaux. Les deux méthodes implémentées dans ce projet sont :

Recuit Simulé (Simulated Annealing) : Une technique d'optimisation stochastique inspirée du processus de refroidissement des métaux.
Algorithme Génétique (Genetic Algorithm) : Un algorithme d'optimisation inspiré du processus de sélection naturelle.
Fonction de Rastrigin

La fonction de Rastrigin est définie par :

𝑓
(
𝑥
)
=
𝐴
⋅
𝑛
+
∑
𝑖
=
1
𝑛
[
𝑥
𝑖
2
−
𝐴
⋅
cos
⁡
(
2
𝜋
𝑥
𝑖
)
]
f(x)=A⋅n+ 
i=1
∑
n
​
 [x 
i
2
​
 −A⋅cos(2πx 
i
​
 )]
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
​
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
