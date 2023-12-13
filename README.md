# Segmentation des clients pour Olist

## Introduction
Olist est une entreprise brésilienne qui propose une solution de vente sur les marketplaces en ligne. L'entreprise souhaite fournir à ses équipes d'e-commerce une segmentation des clients qu’elles pourront utiliser au quotidien pour leurs campagnes de communication.
Le projet consiste à identifier les différents types d'utilisateurs d'Olist à l'aide de méthodes non supervisées de clustering. Les résultats de l'analyse seront présentés à l'équipe marketing d'Olist pour une utilisation optimale.

## Données utilisées
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Olist fournit une base de données anonymisée comportant des informations sur l'historique de commandes, les produits achetés, les commentaires de satisfaction, et la localisation des clients depuis janvier 2017.
La base de données contient environ 1 million de lignes. Cependant, Olist indique que seuls 3 % des clients ont réalisé plusieurs commandes.

## Méthodes utilisées
Les méthodes non supervisées de clustering seront utilisées pour regrouper les clients en groupes homogènes. Les méthodes suivantes seront évaluées :
* K-means
* Agglomerative clustering
* Density-based clustering
* Segmentation RFM classique
* Analyse de la stabilité temporelle des clusters

## Résultats attendus
Les résultats attendus sont les suivants :
* Une segmentation des clients en groupes homogènes
* Une description actionable de la segmentation et de sa logique sous-jacente
* Une proposition de contrat de maintenance basée sur une analyse de la stabilité des segments au cours du temps

## Plan de travail
Le projet sera réalisé en trois phases :
* Phase 1 : Analyse exploratoire des données
* Phase 2 : Essais des différentes approches de modélisation
* Phase 3 : Simulation pour déterminer la fréquence de mise à jour

## Conclusion
Ce projet est une étape importante dans l'amélioration de la communication marketing d'Olist. Les résultats de l'analyse permettront à l'entreprise de mieux comprendre ses clients et de cibler ses campagnes de communication de manière plus efficace.

## Ressources utilisées 
* Python
* Numpy
* Matplotlib, seaborn
* Plotly
* Scikit-learn, Scipy
* yellowbrick
