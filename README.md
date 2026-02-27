🎬 Netflix Catalogue Analytics Project
📌 Contexte

Dans le cadre de ce projet, nous intervenons en tant que Data Analyst pour une plateforme de streaming souhaitant analyser son catalogue Netflix.

L’objectif est de fournir à la direction une vision claire et stratégique du catalogue afin d’identifier :

Les tendances et performances des contenus

La répartition des films vs séries

Les genres et pays de production dominants

La classification d’âge des contenus

L’évolution du catalogue dans le temps

Ce projet couvre l’ensemble de la chaîne analytique :
Exploration → Nettoyage → Transformation → Visualisation → Insights → Dashboard

🎯 Objectif Final

Produire :

📊 Un rapport analytique complet

📈 Des visualisations claires et pertinentes

📌 Des insights métier actionnables

📉 Un dataset préparé pour un dashboard interactif Power BI

🛠 Technologies utilisées

Python

Pandas

Matplotlib

Seaborn

Power BI

📝 Objectifs du Projet

Explorer et analyser le dataset Netflix avec Python et Pandas

Produire des visualisations pertinentes

Répondre aux questions métier liées au catalogue

Identifier les tendances clés

Préparer les données pour un dashboard interactif

📊 Étapes du Projet
1️⃣ Exploration des Données (EDA)
🎯 Objectif

Comprendre la structure du dataset avant toute transformation.

🔎 Analyses réalisées

Vérification de la structure (info(), describe())

Analyse des types de données

Identification des valeurs manquantes (director, country, rating…)

Détection des doublons

Analyse des distributions :

Films vs séries

Genres

Pays

Classification d’âge

📈 Visualisations exploratoires

Count plots

Histogrammes

Bar charts

Boxplots

⚠️ Durant cette étape, aucun nettoyage définitif n’est appliqué afin de préserver l’intégrité des données brutes.

2️⃣ Préparation et Nettoyage des Données
🎯 Objectif

Préparer un dataset propre et structuré pour l’analyse finale et Power BI.

🔄 Transformations effectuées

Gestion des valeurs manquantes (remplacement ou suppression)

Suppression des doublons

Transformation des colonnes multi-valeurs :

listed_in (genres)

country

Création de colonnes dérivées :

year_added

month_added

day_added

Durée en minutes

Nombre de saisons

Harmonisation des formats (dates, durées, type)

Ces transformations permettent d’améliorer la lisibilité et la performance analytique.

3️⃣ Analyse Métier & Visualisations
🎯 Objectif

Répondre aux questions stratégiques de la direction.

📌 Questions analysées

Quelle est la proportion de films vs séries ?

Quelle est la répartition par classification d’âge ?

Quels sont les genres les plus fréquents ?

Quels pays produisent le plus de contenus ?

Comment le catalogue évolue-t-il dans le temps ?

Combien de séries ont été ajoutées entre 2011 et 2021 ?

Quelle est la relation entre pays et classification d’âge ?

📊 Types de visualisations utilisées

Bar charts

Pie charts

Line charts (évolution temporelle)

Heatmaps (analyse croisée)

Graphiques combinés

Toutes les visualisations sont :

Claires

Annotées

Lisibles

Axées sur la prise de décision

4️⃣ Insights Métier
🎯 Objectif

Interpréter les résultats et fournir des recommandations.

Les analyses ont permis d’identifier :

Les genres dominants du catalogue

Les principaux pays producteurs

Les classifications d’âge majoritaires

Les tendances d’ajout de contenu par année

L’évolution stratégique du catalogue

Ces insights permettent à la direction de :

Mieux comprendre la stratégie de contenu

Identifier les opportunités d’expansion

Ajuster les investissements futurs

5️⃣ Dashboard Power BI
🎯 Objectif

Créer un outil interactif pour la prise de décision.

🔧 Fonctionnalités prévues

Filtres dynamiques :

Type (Movie / TV Show)

Pays

Genre

Année d’ajout

KPIs principaux

Visualisations interactives

Vue synthétique des tendances clés

⚠️ Les transformations appliquées dans Power BI restent cohérentes avec celles réalisées en Python.

🚀 Résultat Attendu

Un pipeline analytique complet permettant :

Une compréhension approfondie du catalogue

Une visualisation stratégique des tendances

Une aide à la décision basée sur les données

Une base solide pour un dashboard interactif
