# 📊 Projet V – Analyse des performances des employés

## 🧠 Problématique métier  
Une entreprise souhaite analyser la répartition des performances de ses employés afin de comprendre les écarts, détecter les valeurs aberrantes (outliers) et identifier des axes d'amélioration.

## 🎯 Objectif  
Étudier les distributions des **scores de performance** et des **heures travaillées** pour mieux comprendre les profils d’employés et mettre en évidence les anomalies.

## 🛠️ Compétences mobilisées  
- **Statistiques descriptives** : moyenne, médiane, mode, quartiles, variance, écart-type  
- **Visualisation de données** : histogrammes, boxplots, diagrammes en barres et circulaires  
- **Détection des outliers** : méthode des 1.5 * IQR  
- **Manipulation de données** : avec `dplyr` en R

## 🗃️ Données utilisées  
- **HR Analytics Dataset**  
  (Données simulées d’une entreprise incluant les scores de performance et les heures travaillées des employés)

## 🧰 Outils et langage  
- **Langage** : R  
- **Librairies principales** : `dplyr`, `ggplot2`, `tidyverse`

## 📁 Structure du projet  
- Analyse de la répartition des scores de performance pour identifier les écarts significatifs entre employés.
- Visualisations statistiques (boxplots, histogrammes) pour illustrer les différences de performance selon des facteurs clés (département, heures travaillées, etc.).
- Détection précise des employés "outliers" (valeurs extrêmes) à l’aide de la méthode 1.5 * IQR.
- Profilage des employés performants et sous-performants pour aider à la prise de décision.
- Recommandations ciblées pour améliorer les performances globales ou réduire les écarts identifiés (formation, rééquilibrage des charges, etc.).
