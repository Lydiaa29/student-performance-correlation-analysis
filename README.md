# Student Performance – Correlation Analysis

Exploration du dataset [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
via différentes méthodes de corrélation (Pearson, Spearman, bisériale, χ²).

## Objectif
Identifier quels facteurs (préparation aux examens, éducation des parents,
genre, type de repas) sont liés aux notes des élèves en maths, lecture et écriture.

## Méthodes utilisées
- Pearson : relations entre les 3 scores
- Spearman : niveau d'éducation des parents (ordinal) vs scores
- Point-bisériale : genre vs score
- χ² / Phi : test de préparation vs type de repas

## Outils
Python, pandas, seaborn, scipy

## Structure
- `notebook.ipynb` — analyse complète
- `data/` — dataset (non versionné, voir lien Kaggle)
- `images/` — heatmaps et graphiques exportés
