
# Inférence causale avec NOTEARS — SDD1004

Notebook Jupyter explorant la découverte de structure causale (DAG) sur des données linéaires et non-linéaires via les algorithmes NOTEARS (linéaire) et NOTEARS-MLP (non-linéaire), avec comparaison des performances.

## Contenu du notebook

- EDA sur deux jeux de données : relations linéaires (Q1) vs non-linéaires trigonométriques (Q2)
- Visualisations : matrice de nuages de points, heatmap de corrélation, clustering K-Means 3D interactif (Plotly)
- Application de NOTEARS linéaire sur les deux jeux de données et visualisation du DAG résultant
- Application de NOTEARS-MLP (réseau de neurones) pour capturer les relations non-linéaires
- Comparaison et analyse critique des deux algorithmes selon la nature des données
- Interprétation des matrices d'adjacence et des graphes causaux (NetworkX)

## Concepts démontrés

- Inférence causale et découverte de structure (structure learning)
- DAG (graphe acyclique dirigé) — contrainte d'acyclicité via puissance matricielle
- NOTEARS linéaire vs NOTEARS-MLP (réseau de neurones multi-couche)
- Régularisation L1 (sparsité) et L2 (stabilité des poids)
- Clustering K-Means 3D interactif

## Technologies

- Python
- gCastle (NOTEARS, NotearsNonlinear)
- NetworkX
- Pandas / NumPy
- Matplotlib / Seaborn / Plotly
- scikit-learn (KMeans, StandardScaler)
- PyTorch (CUDA)
- Google Colab

## Prérequis

```bash
pip install gcastle networkx pandas numpy matplotlib seaborn plotly scikit-learn torch
```

GPU NVIDIA avec CUDA recommandé pour NOTEARS-MLP. Développé sous Google Colab.

## Structure

```
Notears.ipynb  — notebook principal (4 questions)
```

---

Projet universitaire solo — cours SDD1004, UQTR.

