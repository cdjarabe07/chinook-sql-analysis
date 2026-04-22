# Analyse de la base Chinook — SQL & Python

## Objectif du projet

Ce projet a pour objectif d’analyser une base de données musicale (Chinook) afin de :

* Se connecter et exploiter une base SQLite avec Python
* Écrire des requêtes SQL pour extraire des informations business
* Transformer les résultats en DataFrames Pandas
* Créer des indicateurs de performance (KPI)
* Visualiser les données pour en tirer des insights exploitables

## Dataset

* Source : Chinook Database (SQLite)
* Format : .sql (script de création + insertion des données)
* Description : base de données représentant une boutique de musique numérique (artistes, albums, pistes, factures, clients)

## Technologies utilisées

* Python
* SQLite3
* Pandas
* Matplotlib
* Jupyter Notebook

## Instructions pour exécuter le projet

### 1. Cloner le dépôt GitHub
   * git clone `https://github.com/cdjarabe07/Ecommerce_Analysis`
   * cd chinook-sql-analysis
### 2. Installer les dépendances
   `pip install pandas matplotlib`
### 3. Ajouter le dataset
   Placer le fichier : Chinook_Sqlite.sql dans le dossier `data/`
### 4. Lancer Jupyter Notebook
### 5. Exécuter le notebook
  Ouvrir : `notebooks/analysis.ipynb`
  Et exécuter les cellules dans l’ordre.

## Préparation des données

* Création d’une base SQLite à partir du fichier .sql
* Chargement des données dans la base
* Vérification des tables disponibles
* Exploration des relations entre tables
* Extraction des données avec SQL

## Analyses réalisées
### Analyse des ventes de musique

* Identification des 10 titres les plus vendus
* Analyse des pistes les plus populaires

## Analyse géographique

* Identification des pays générant le plus de revenus
* Comparaison des performances par marché

## Analyse des performances commerciales

* Identification du meilleur vendeur (support client)
* Comparaison des performances des employés

## Analyse globale des revenus
* Calcul du chiffre d’affaires total
* Répartition des revenus par pays

## Insights principaux

* Les ventes sont concentrées sur un nombre limité de titres
* Certains pays dominent fortement les revenus générés
* Les performances des vendeurs sont globalement équilibrées
* Le modèle de vente est fortement concentré sur quelques marchés clés

## Recommandations

* Diversifier les marchés pour réduire la dépendance géographique
* Mettre en avant les titres les plus performants
* Analyser les comportements d’achat par région
* Optimiser les stratégies de vente des artistes les plus populaires

## Structure du projet

```
chinook-sql-analysis/
│
├── data/
│   └── Chinook_Sqlite.sql
│
├── db/
│   └── chinook.db (optionnel, généré automatiquement)
│
├── notebooks/
│   └── analysis.ipynb
│
└── README.md
```

### Lien du projet GitHub

`https://roadmap.sh/projects/querying-sql-python`
