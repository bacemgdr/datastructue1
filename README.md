Objectif du point de contrôle
À ce point de contrôle, il vous est demandé d'écrire un algorithme qui répond à la description suivante :

Description:

            Problème 1
 
Étant donné deux ensembles d’éléments, trouvez la somme de tous les éléments distincts de l’ensemble. En d’autres termes, trouvez la somme de tous les éléments présents dans l’un ou l’autre des ensembles donnés.
Exemple:
Ensemble 1 : [3, 1, 7, 9], Ensemble 2 : [2, 4, 1, 9, 3]
Sortie : 13 (éléments distincts 4, 7, 2)
Donnez une solution à ce problème, en utilisant des tableaux

 
            Problème 2 
Il vous est demandé d'écrire un algorithme qui remplit les conditions suivantes : 

Nom : Produit scalaire
Description:
Ecrire une procédure, appelée dot_product qui calcule dans la variable ps, le produit scalaire de v1 et v2 (v1 et v2 sont des vecteurs de IR)
Écrire un algorithme qui détermine, pour n paires de vecteurs donnés, si deux vecteurs de IR donné sont orthogonaux, en appelant la procédure définie à la question précédente. Le produit scalaire de deux vecteurs orthogonaux est nul.
Modifiez l'algorithme précédent si vous utilisez une fonction dot_product au lieu d'une procédure.
Instructions
Problème 1
Solution avec un tableau.

Initialiser la somme = 0. 
Comparez chaque élément du premier ensemble avec le deuxième ensemble et si l'élément n'est pas présent, ajoutez cet élément à la somme. 
Faites ensuite l’inverse pour ajouter des éléments du deuxième ensemble.
Problème 2

Lors de la création de votre algorithme, vous devez : 

Utilisez un tableau pour présenter le vecteur.
Utilisez une boucle imbriquée (une boucle dans une autre si vous le souhaitez)
Utiliser différents types de paramètres de transmission