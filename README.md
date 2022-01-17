# GitHub projet OC
 Projet Data Openclassrooms de la formation Data Analyst.

Petit soucis de lecture pour la librairie Plotly avec Github..

Durant ce projet, il faut mettre en évidence les vrais des faux billets avec un jeu de données égal à 1500 billets 1000 vrais pour 500 faux.

Pour ça, j'ai utilisé une imputation sur la regression linéaire des valeurs manquantes et j'ai fait des tests pour vérifier.

Les tests de Shapiro, Godfelt et Quandt ainsi que Breusch Pagan sont des bons moyens de vérifier cette régression linéaire.

Par la suite une ACP, suivi d'un Kmeans mettent en avant les groupes d'individus, même si pour ce projet, les KNN ainsi que la régression logistique sont une bien meilleure option.

Pour créer une fonction de détection de faux billets, j'ai préféré me lancer sur la regression logistique, qui me paraissait plus optimisé dans cette exemple.
