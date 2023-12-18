# Fonction recherche de dossier

## Demande :

![image](https://github.com/MathisCastell/Stage-Fonction-recherche-de-dossiers/assets/148212506/268094a1-7735-4390-816e-299c26c2e9b7)

## Modification du fichier menu permettant de lier vers une nouvelle page de recherche 

Code :

![image](https://github.com/MathisCastell/Stage-Fonction-recherche-de-dossiers/assets/148212506/563a087c-9563-480b-a62b-c2284d0798d1)

Résultat :

![image](https://github.com/MathisCastell/Stage-Fonction-recherche-de-dossiers/assets/148212506/85fdbaaa-2bae-4db7-9632-42dca72988cb)

## Modification d'un accueil controller en php :

![image](https://github.com/MathisCastell/Stage-Fonction-recherche-de-dossiers/assets/148212506/55e57890-a4d3-4313-ade5-5956405ec280)

## Création de la page formulaire de recherche

Les pages se divisent en 3 parties distinct, définition des variables, SQL, affichage. J'ai tout d'abord défini les champs du formulaire en leur donnant un type un nom et une valeur.
J'ai ensuite mis les variables de sessions dans des variables.
J'ai créé un appel de PS qui avait pour objectif de faire la recherche dans la PS.
Enfin, j'ai affiché dans la page les champs défini dans la première partie.

Résultat :

![image](https://github.com/MathisCastell/Stage-Fonction-recherche-de-dossiers/assets/148212506/b69c119e-cb88-42ac-a493-cdbad5f018a1)

## Création de la page affichage de la recherche :

J'ai défini les éléments dans la page, donc un tableau car le résultat devait être sous forme de tableau.
J'ai ensuite défini les variables de session ainsi que la requête qui allait chercher dans la base de donnée les données à afficher dans le tableau que j'ai filtré dans le WHERE avec les valeurs rentrées précédement dans la page formulaire (les valeurs sont stockées dans la variable de session définie dans la page php).
J'ai ensuite créé le tri.
J'ai terminé par faire l'affichage dans la page du tableau.

Résultat 

![image](https://github.com/MathisCastell/Stage-Fonction-recherche-de-dossiers/assets/148212506/722efccd-9b12-4fbd-bc2a-b70fba732d94)



