# Description du dossier sur *Le tour du monde en 80 jours* de Jules Verne

Ce dossier constitue une étude du texte *Le tour du monde en 80 jours* de Jules Verne, notamment avec l'utilisation d'Iramuteq pour créer des visualisations à partir de statistiques issues de cette oeuvre. Il a fallu récupérer le texte intégral pour pouvoir l'encoder afin de l'étudier avec Iramuteq. Grâce aux visualisations, je pourrais mettre en avant les rapports et thèmes de l'oeuvre.

## Récupération du texte et encodage

Pour créer un fichier .txt contenant l'ensemble de l'oeuvre, j'ai récupéré le texte sur [Wiki Source](https://fr.wikisource.org/wiki/Le_Tour_du_monde_en_quatre-vingts_jours/Texte_entier).  

J'ai procédé à un nettoyage très rapide : suppression de l'indicateur dynamique des pages qui s'était mis à la fin de mon document, simplification de l'entête.  
J'ai ensuite encodé mon texte en assignant une variable à chaque chapitre, soit 37 variables différentes.

Lien vers [Le tour du monde en 80 jours.txt](https://github.com/xXADavid999/Antoine_David_Tour_du_monde_en_80_jours/blob/master/Le%20tour%20du%20monde%20en%2080%20jours.txt).

## Version Epub de l'oeuvre

Je suis allé sur le site du Projet Gutenberg pour trouver *Le tour du monde en 80 jours* en [version .epub](http://www.gutenberg.org/ebooks/800), il est intéressant de noter qu'il existe plusieurs versions avec ou sans images, et avec différents formats pour faciliter l'accessibilité.

## Les fichiers en .CSV des occurences

Les visualisations issues d'Iramuteq proviennent d'analyses statistiques que l'on peut retrouver dans les .CSV suivants :

+ [total.csv](https://github.com/xXADavid999/Antoine_David_Tour_du_monde_en_80_jours/blob/master/CSV/total.csv) : sur ce document on retrouve l'ensemble de mots par fréquence décroissante.
+ [formes_actives.csv](https://github.com/xXADavid999/Antoine_David_Tour_du_monde_en_80_jours/blob/master/CSV/formes_actives.csv) : sur ce document, on trouve  la liste   des   formes/mots   actifs (avec   leur   catégorie grammaticale) par fréquences décroissantes. 

Iramuteq résume les statisques générales comme : 
+ Nombre de textes : 37
+ Nombre d'occurrences : 71179
+ Nombre de formes : 5600
+ Nombre d'hapax : 2360 (3,32% des occurrences - 42,14% des formes)
+ Moyenne d'occurrences par texte : 1923,76

Le nombre de texte fait référence à mes variables qui représentent les 37 chapitres du roman.

Comme l'oeuvre étudiée possède 37 chapitres, il m'est également possible d'extraire des CSV pour chaque chapitre ou par regroupement arbitraire de chapitre.

## Visualisation de données 

![représentation statistiques des fréquences sur l'ensemble de l'oeuvre](https://github.com/xXADavid999/Antoine_David_Tour_du_monde_en_80_jours/blob/master/Visualisations/Statistiques%20totales.PNG)

Ce graphique est issu de l'outil stastistique d'Iramuteq. On retrouve sur l'axe des ordonnées la fréquence des mots cités, et sur l'axe des abscisses la quantité d'occurrences. Sans surprise, on retouve une petite quantité de mots cités beaucoup de fois, et une grande quantité de mots peu cités.
