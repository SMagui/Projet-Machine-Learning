# 🤖 Projet Machine Learning — Classification & Régression

Ce projet a pour objectif de développer et d’évaluer des modèles de Machine Learning pour résoudre des problèmes concrets à partir de données réelles. Il couvre l'ensemble du pipeline : de la préparation des données à la prédiction, en passant par la modélisation et l'évaluation.

---

## 📁 Structure du projet

```
Projet-Machine-Learning/
├── Data/                         # Jeux de données (iris.csv, housing.csv, cereals.csv)
├── Notebooks/                   # Jupyter notebooks de chaque analyse
├── Scripts/                     # Scripts Python (prétraitement, modèles, évaluation)
├── requirements.txt             # Bibliothèques nécessaires
├── README.md                    # Présentation du projet
└── .gitignore                   # Fichiers à ne pas pousser
```

---

## 🎯 Objectifs

- Explorer, nettoyer et transformer différents jeux de données
- Appliquer des modèles de classification et de régression
- Comparer les performances (accuracy, RMSE, etc.)
- Automatiser des pipelines de Machine Learning
- Visualiser les résultats et interpréter les modèles

---

## 📊 Jeux de données utilisés

- `iris.csv` : classification d'espèces de fleurs
- `housing.csv` : régression des prix de logements
- `cereals.csv` : analyse nutritionnelle de céréales

---

## 🔧 Technologies et outils

- **Python** 3.x
- **Pandas**, **NumPy** — Manipulation des données
- **Scikit-learn** — Modélisation Machine Learning
- **Matplotlib**, **Seaborn** — Visualisation
- **Jupyter Notebook** — Exploration et documentation
- **.venv** (non versionné) — Environnement virtuel

---

## ⚙️ Installation & exécution

1. Cloner le dépôt :
```bash
git clone https://github.com/SMagui/Projet-Machine-Learning.git
cd Projet-Machine-Learning
```

2. Créer et activer un environnement virtuel :
```bash
python -m venv .venv
.venv\Scripts\activate         # Windows
# OU
source .venv/bin/activate      # Mac/Linux
```

3. Installer les dépendances :
```bash
pip install -r requirements.txt
```

4. Lancer les notebooks :
```bash
jupyter notebook
```

---

## 📈 Modèles implémentés

### 🌼 Classification — *Iris Dataset*

- K-Nearest Neighbors (KNN)
- Régression Logistique
- Arbre de Décision
- SVM

### 🏠 Régression — *Housing Dataset*

- Régression Linéaire
- Random Forest Regressor
- Gradient Boosting
- Evaluation : RMSE, R²

### 🥣 Analyse — *Cereals Dataset*

- Nettoyage et visualisation
- Clustering (KMeans)
- PCA pour réduction de dimension

---

## 🧪 Évaluation des modèles

- **Classification** : accuracy, confusion matrix, precision, recall, F1
- **Régression** : RMSE, MAE, R²
- **Clustering** : silhouette score, méthode du coude

---

## 🧠 Compétences démontrées

- Préparation et traitement de données
- Choix de modèles adaptés
- Evaluation comparative de modèles
- Visualisation et storytelling avec Python
- Utilisation propre de Git et structuration de projet

---

## 👤 Auteur

Projet réalisé par **SMagui**  
🔗 [Mon profil GitHub](https://github.com/SMagui)

---

## 📌 Remarques

- Le dossier `.venv` est volontairement ignoré via `.gitignore`
- Le fichier `requirements.txt` permet de reproduire l’environnement

