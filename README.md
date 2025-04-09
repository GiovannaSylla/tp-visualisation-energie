# Projet de Visualisation de Données – Profil Énergétique Mondial

## Description du projet

Ce projet a pour objectif de visualiser et comparer la consommation d’énergie dans différents pays à partir d’un jeu de données mondial.  
L’idée est de présenter les données de manière claire, lisible et originale, en utilisant les bons types de graphiques selon ce que l’on veut mettre en valeur.

Le travail suit une logique comparative : on observe l’évolution ou la structure énergétique de plusieurs pays sur une même année, avec des graphiques différents mais complémentaires.

---

## Stack technique

- **Langage** : Python 3
- **Librairies utilisées** :
  - `pandas` pour la manipulation de données
  - `plotly.express` et `plotly.graph_objects` pour les visualisations interactives et claires
  - `matplotlib.pyplot` pour les graphiques circulaires (type radar ou coxcomb)

---

## Source de la donnée

Jeu de données utilisé :  
[World Energy Consumption – Kaggle](https://www.kaggle.com/datasets/ambujtripathi/world-energy-consumption)

Ce jeu de données est pertinent car :
- Il est complet (plusieurs décennies)
- Il couvre de nombreux pays
- Il contient toutes les sources d’énergie analysées : charbon, pétrole, gaz, nucléaire, renouvelables, solaire

---

## Comment exécuter le projet

1. Télécharger le fichier `notebook_visualisation_ready.ipynb` (ou l’ouvrir depuis GitHub)
2. Télécharger les données depuis Kaggle (`world_energy_consumption.csv`)
3. Placer le fichier CSV dans le même dossier que le notebook
4. Ouvrir Jupyter Notebook et exécuter les cellules une à une
5. Les fonctions sont modulaires (une fonction = une action) et documentées avec des docstrings

---

## Visualisations réalisées

### 1. Diagramme de Sankey – Afrique (2010)
Visualisation des flux énergétiques par source. Montre la dépendance au pétrole, charbon et gaz.

### 2. Diagramme Radar – France (2010)
Visualisation du profil global d’un pays. Permet de comparer la part de chaque énergie, avec une domination nette du nucléaire.

### 3. Carte mondiale – Solaire (2010)
Vue d’ensemble sur la répartition géographique de l’énergie solaire. Permet une lecture globale et instantanée.

### 4. Diagramme en coin – Allemagne (2010)
Ce diagramme en coin montre que l’Allemagne utilise principalement du pétrole et du gaz en 2010
On l’utilise ici pour rendre la répartition plus lisible et originale.
---


---
