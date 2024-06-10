
Reconstruction probabiliste de la généalogie dans une population de rosiers de type diploïde et tetraploïde. Finalisation d'un programme de reconstruction et de visualisation de la généalogie sur un jeu de données
diploïde 2x et tétraploïde 4x.

1 - Reprogrammer la reconstruction généalogique 2x 
2 - Programmer la reconstruction généalogique 4x avec dosage connu

Chaque dose allélique est connue, c’est-à-dire que si un
individu a moins de quatre allèles pour un marqueur (ex : allèles A, B et C), on connait la dose des
allèles (ex : AABC).

Script : nécessite de faire une fonction genererEnfVirt44 (distincte de genererEnfVirt22)

- genere la liste des enfants virtuels a partir du genotype des parents pour le schema 4x-4x
- in : genotype des parents (vecteurs de taille 4)
- out : liste des enfants virtuels (matrice de 36 lignes et 4 colonnes)