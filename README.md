
# Dashboard Plotly Interactif

Projet réalisé avec Python et Plotly dans le cadre du challenge **30 Days of Python**.

## Objectif

Créer un dashboard interactif permettant d'analyser des données de ventes :

- Chiffre d'affaires par produit
- Répartition des ventes par région
- Évolution mensuelle du CA
- Analyse Quantité vs Montant

---

## Technologies utilisées

- Python
- Pandas
- NumPy
- Plotly

---

## Structure du projet

```bash
.
├── Dashboard_Plotly.ipynb
├── graphique_bar.png
├── graphique_pie.png
├── graphique_line.png
├── graphique_scatter.png
├── dashboard_final.png
├── dashboard_final.html
└── README.md
```

---

## Aperçu des graphiques

### 1. CA par Produit
Visualisation du chiffre d'affaires généré par chaque produit.

### 2. Répartition du CA par Région
Graphique circulaire interactif permettant d'identifier les régions les plus performantes.

### 3. Évolution Mensuelle du CA
Courbe temporelle pour suivre la progression des ventes.

### 4. Quantité vs Montant
Scatter plot pour analyser la relation entre quantité vendue et montant des ventes.

---

## Dashboard Final

Le dashboard final combine tous les graphiques dans une seule interface interactive réalisée avec `make_subplots`.

---

## Lancer le projet

Installer les dépendances :

```bash
pip install pandas numpy plotly kaleido
```

Exécuter le notebook :

```bash
jupyter notebook
```

---

## Résultat

- Dashboard interactif exporté en HTML
- Dashboard exporté en PNG
- Visualisations individuelles exportées en PNG

---

## Auteur

Projet réalisé pour enrichir un portfolio Data Analytics / Data Visualization avec Plotly.
