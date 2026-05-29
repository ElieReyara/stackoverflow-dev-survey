# Stack Overflow Developer Survey 2023 — Analyse Python

## Contexte

Analyse exploratoire du Stack Overflow Developer Survey 2023 — **89 184 développeurs**
interrogés dans le monde entier sur leurs outils, salaires, méthodes d'apprentissage
et aspirations technologiques.

L'objectif est de répondre à 5 questions business concrètes à partir des données brutes,
en combinant nettoyage de données, agrégations Pandas et visualisations Matplotlib.

## Stack Technique

- **Python** : Pandas · NumPy · Matplotlib
- **Environnement** : Jupyter Notebook / VS Code
- **Dataset** : [https://www.kaggle.com/datasets/stackoverflow/stack-overflow-2023-developers-survey?resource=download)

---

## 5 Questions Business

| # | Question | Insight clé |
|---|----------|-------------|
| 1 | Quels langages dominent le marché en 2023 ? | JavaScript en tête (55 711 devs), SQL 4ème — universel tous stacks confondus |
| 2 | Quels rôles sont les mieux rémunérés ? | Engineering Manager : 120 000 $ médian — 2x le salaire d'un Data Analyst |
| 3 | Quelles technologies émergent ? | Rust et Go absents du top 10 "used" mais dans le top 10 "want" — adoption en cours |
| 4 | Le diplôme est-il obligatoire ? | Majorité Bachelor/Master — mais proportion non négligeable de devs sans diplôme formel |
| 5 | Les cours en ligne sont-ils suffisants ? | Apprentissage en ligne dominant — mais top 5 mixte : livres, école, formation terrain toujours présents |

---

## Structure du Projet

```
stackoverflow-dev-survey/
│
├── stackoverflow_analysis.ipynb   # Notebook principal — analyses + visualisations
├── README.md                      # Ce fichier
└── survey_results_public.csv  # Dataset source (non versionné — voir lien ci-dessus)
```

---

## Visualisations

1. Top 15 langages les plus utilisés
2. Salaire médian par rôle (top 10, min. 200 répondants)
3. Langages souhaités vs utilisés — tendances émergentes
4. Niveau d'éducation des développeurs
5. Méthodes d'apprentissage les plus utilisées

---

## Lancer le Projet

```bash
git clone https://github.com/votre-github/stackoverflow-dev-survey
cd stackoverflow-dev-survey
jupyter notebook stackoverflow_analysis.ipynb
```

Dataset à télécharger séparément : https://www.kaggle.com/datasets/stackoverflow/stack-overflow-2023-developers-survey?resource=download
→ Placer `survey_results_public.csv` dans le dossier `archive/`
