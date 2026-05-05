# 💘 Speed Dating — Analyse des Facteurs de Séduction

> *Comprendre ce qui influence l'obtention d'un second rendez-vous grâce à l'analyse exploratoire de données de speed dating*

[![Python](https://img.shields.io/badge/Python-3.10-3776AB?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-EDA-150458?logo=pandas)](https://pandas.pydata.org/)
[![SciPy](https://img.shields.io/badge/SciPy-Stats-8CAAE6?logo=scipy)](https://scipy.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Viz-4C72B0)](https://seaborn.pydata.org/)

---

## 🎯 Objectif

**Qu'est-ce qui fait qu'on obtient un second rendez-vous après un speed dating ?**

Ce projet analyse un dataset issu d'une compétition Kaggle sur le speed dating pour identifier les facteurs clés qui influencent la décision de se revoir — attractivité physique, intérêts communs, ambition, sincérité...

---

## 📊 Résultats clés

| Facteur | Corrélation avec match | Remarque |
|---|---|---|
| Attractivité physique | **+0.42** | Facteur le plus discriminant |
| Intérêts communs | **+0.31** | Fort impact sur la décision |
| Ambition perçue | **-0.08** | Légèrement pénalisant |
| Sincérité | **+0.18** | Plus importante chez les femmes |
| Fun | **+0.35** | Deuxième facteur le plus important |

> **43%** des participants obtiennent un match. Les femmes accordent plus d'importance à la sincérité, les hommes à l'attractivité physique.

---

## 🗂️ Structure du projet

```
speed-dating/
├── data/
│   └── speed_dating.csv              # ~8 000 observations — 195 variables
├── notebooks/
│   └── speed_dating_eda.ipynb        # EDA complète + tests statistiques
├── .gitignore
├── README.md
└── requirements.txt
```

---

## 🧠 Analyses réalisées

| Analyse | Technique |
|---|---|
| Distribution des matchs | Histogrammes, pie charts |
| Corrélations | Heatmap, Pearson |
| Différences H/F | Tests t de Student, Mann-Whitney |
| Impact des intérêts | Chi², analyse des hobbies partagés |
| Profil du "perfect match" | Agrégation par décile de score |

---

## 📈 Insights clés

- **43%** de taux de match global
- L'**attractivité physique** est le critère n°1 pour les deux genres
- Les participants **sous-estiment** leur propre attractivité vs la perception des autres
- Les matchs sont **plus fréquents** entre participants du même niveau d'études
- Les **intérêts communs** (sport, lecture, art) augmentent le taux de match de **+12%**
- Les femmes donnent des scores plus **calibrés** — les hommes ont tendance à sur-noter

---

## ⚙️ Installation

```bash
git clone https://github.com/MartialBayom/speed-dating-analysis.git
cd speed-dating-analysis
pip install -r requirements.txt
jupyter notebook notebooks/speed_dating_eda.ipynb
```

---

## 👤 Auteur

| | Nom | Rôle |
|---|---|---|
| 🧑‍💻 | **Martial BAYOM** | Data Science |

Projet réalisé dans le cadre de la **certification Jedha AI School** (RNCP Niveau 6)

---

## 📂 Sources

| Dataset | Lien |
|---|---|
| Speed Dating Experiment | [Kaggle](https://www.kaggle.com/datasets/annavictoria/speed-dating-experiment) |
