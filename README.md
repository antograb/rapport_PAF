# Rapport du Projet d'Application Final - Effet trémolo piloté par un accéléromètre

Dans ce projet, un effet trémolo d'une guitare est réalisé et piloté
par un accéléromètre.

L'effet trémolo est un effet de guitare consistant à faire varier
l'amplitude du signal de la guitare avant de l'amplifier. Ici, il est
réalisé avec un transistor, agissant comme une résistance variable en
faisant varier sa tension de grille avec une sinusoïde. La fréquence de
cette sinusoïde est elle-même générée par un LFO, dont la fréquence
est variée avec un commutateur. Ce commutateur est contrôlé par la
tension de sortie de l'accéléromètre.

Cette [chaîne](./schema_bloc.pdf) permet alors — en fixant
l'accéléromètre sur le manche de la guitare — de contrôler la
fréquence du trémolo en fonction de la position de celle-ci.

Le [rapport](./docs/rapport_PAF.pdf) en LaTeX a été réalisé par Geert-Jan Huizing ainsi et
moi-même. Les schémas ont été produits par mes soins avec PGF/TikZ.

## Auteurs

 * Anas Bouzafour
 * Antoine Gallet
 * Antonin Godard
 * Geert-Jan Huizing
