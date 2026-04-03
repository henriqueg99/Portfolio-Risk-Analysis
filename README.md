# Portfolio Risk Analysis Tool (V1)

## Overview

Ce projet est un outil d’analyse du risque de portefeuille développé en Python sous forme de notebook.

L’objectif est d’analyser le profil de risque d’un portefeuille multi-actifs (actions et indices) à l’aide de méthodes classiques de gestion des risques en finance quantitative.

Cette première version se concentre sur la construction d’un **moteur d’analyse du risque** et la visualisation des résultats.


## Fonctionnalités principales

Le projet permet de :

* récupérer des données de marché historiques (yfinance)
* calculer les rendements logarithmiques
* analyser la volatilité des actifs
* étudier les corrélations entre actifs
* estimer la volatilité du portefeuille
* simuler les rendements via Monte Carlo
* calculer la Value at Risk (VaR)
* calculer l’Expected Shortfall (ES)
* effectuer un backtesting de la VaR
* analyser des scénarios de stress
* décomposer la contribution au risque par actif


## Actifs étudiés

Le portefeuille étudié comprend plusieurs actifs :

* LVMH (MC.PA)
* Dassault Systèmes (DSY.PA)
* Sanofi (SAN.PA)
* BYD (BY6.F)
* ETF Asie (PAASI.PA)
* S&P 500 (^GSPC)
* Euro Stoxx 50 (^STOXX50E)


## Visualisations

Le notebook inclut plusieurs visualisations permettant d’interpréter le risque :

* évolution des rendements
* distribution des rendements
* volatilité des actifs
* matrice de corrélation (heatmap)
* distribution des pertes
* VaR et Expected Shortfall
* contribution au risque


## Technologies utilisées

* Python
* pandas
* numpy
* matplotlib
* seaborn
* yfinance
* Jupyter Notebook


## Évolution du projet

Une seconde version (V2) est en cours de développement avec pour objectif de transformer ce notebook en un **outil interactif d’analyse de portefeuille**.

Les évolutions prévues incluent :

* saisie d’un portefeuille via nombre d’actions
* calcul automatique des poids
* diagnostic de risque automatisé
* optimisation du portefeuille
* interface utilisateur (Streamlit)


## Objectif

Ce projet s’inscrit dans une démarche personnelle d’apprentissage en **finance quantitative et gestion des risques**, avec une application aux problématiques de gestion de portefeuille.


## Auteur

Henrique Guedes

Étudiant en mathématiques appliquées et modélisation

GitHub : https://github.com/henriqueg99
LinkedIn : [www.linkedin.com/in/henrique-guedes-347259390](http://www.linkedin.com/in/henrique-guedes-347259390)
