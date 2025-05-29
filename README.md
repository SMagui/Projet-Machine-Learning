# 📊 Projet Machine Learning

Ce projet vise à mettre en œuvre des algorithmes de **Machine Learning supervisé et non supervisé** sur des jeux de données réels. Il permet de traiter l'ensemble du cycle de vie d'un projet ML : de l'importation et la préparation des données, jusqu’à l’évaluation et l’interprétation des modèles.

Nous utilisons des bibliothèques standard de l’écosystème Python : `pandas`, `numpy`, `scikit-learn`, `matplotlib`, et `seaborn`.

---

## 🗂️ Structure du projet

Projet-Machine-Learning/
├── Data/ # Jeux de données (iris.csv, housing.csv, cereals.csv, etc.)
├── Notebooks/ # Jupyter Notebooks d’analyse et d’expérimentation
├── Scripts/ # Scripts Python modulaires (prétraitement, modèles, etc.)
├── requirements.txt # Dépendances du projet
├── README.md # Ce fichier de présentation
└── .gitignore # Fichiers à exclure du contrôle de version

yaml
Copier
Modifier

---

## 🎯 Objectifs pédagogiques

Ce projet a été conçu pour atteindre les objectifs suivants :

- Explorer, nettoyer et transformer des données hétérogènes
- Appliquer des modèles de **classification**, **régression** et **clustering**
- Comparer les performances des modèles avec des **métriques adaptées**
- Visualiser et interpréter les résultats
- Structurer un projet de ML de manière modulaire et reproductible

---

## 📊 Jeux de données utilisés

| Nom du fichier         | Objectif                                 | Type d’apprentissage |
|------------------------|------------------------------------------|-----------------------|
| `iris.csv`             | Classification des espèces de fleurs     | Classification        |
| `housing.csv`          | Prédiction du prix des maisons           | Régression            |
| `cereals.csv`          | Analyse nutritionnelle et clustering     | Clustering            |
| `user+data.csv`        | Classification binaire d’utilisateurs    | Classification        |
| `mallCustomerData.txt` | Segmentation de clients via K-means      | Clustering            |

Chaque fichier est documenté dans les scripts et notebooks pour faciliter la reproductibilité.

---

## 🧠 Modèles implémentés

### 🌼 Classification

- **K-Nearest Neighbors (KNN)** : classification de clients selon leurs caractéristiques.
- **Régression Logistique**, **SVM**, **Arbre de décision** : sur le jeu `iris.csv`.
- **Évaluation** : Matrice de confusion, Précision, Rappel, F1-score.

Chaque modèle est testé avec différents hyperparamètres, et parfois optimisé via `GridSearchCV`.

### 🏠 Régression

- **Régression linéaire simple** : prédiction du prix d'une maison en fonction de sa surface.
- **Modèles avancés** : `RandomForestRegressor`, `GradientBoostingRegressor`.
- **Évaluation** : RMSE, MAE, R² pour comparer la qualité des prédictions.

### 🥣 Clustering (non supervisé)

- **K-Means clustering** : segmentation de clients selon leurs revenus et scores d’achat.
- **Méthode du coude** : choix du nombre optimal de clusters.
- **Visualisation 2D et 3D** pour interpréter la structure des données.

---

## 🔧 Technologies utilisées

| Technologie       | Rôle                             |
|-------------------|----------------------------------|
| Python 3.x        | Langage principal                |
| pandas / numpy    | Traitement et manipulation des données |
| matplotlib / seaborn | Visualisation graphique      |
| scikit-learn      | Modèles de Machine Learning      |
| Jupyter Notebook  | Environnement de test et doc     |
| Git / GitHub      | Versionnage et collaboration     |

---

## ⚙️ Installation et exécution

1. **Cloner le dépôt** :
```bash
git clone https://github.com/SMagui/Projet-Machine-Learning.git
cd Projet-Machine-Learning
Créer un environnement virtuel :

bash
Copier
Modifier
python -m venv .venv
.venv\Scripts\activate     # Sous Windows
# ou
source .venv/bin/activate  # Sous macOS / Linux
Installer les dépendances :

bash
Copier
Modifier
pip install -r requirements.txt
Lancer les notebooks :

bash
Copier
Modifier
jupyter notebook
🧪 Évaluation des modèles
Type de tâche	Métriques d’évaluation
Classification	Accuracy, F1-score, Recall, Matrice de confusion
Régression	RMSE, MAE, R²
Clustering	Inertie (WCSS), silhouette score


Ces métriques permettent de juger les modèles non seulement en termes de performance brute mais aussi d'adéquation à la tâche.

✅ Structure du projet

📁 Dossiers bien séparés entre données, scripts et notebooks

🧼 Données nettoyées et mises à l’échelle si nécessaire

🔁 Pipelines reproductibles via requirements.txt et environnement virtuel .venv

📋 Code commenté et organisé

🔒 .gitignore configuré pour exclure les données sensibles et l’environnement virtuel

👤 Auteur
Projet réalisé par SMagui
🔗 Profil GitHub

📝 Remarques
Tous les jeux de données sont disponibles dans le dossier Data/.

Le projet est évolutif et prêt à intégrer d’autres modèles (ex: PCA, réseaux de neurones).

Pour toute contribution, merci de créer une branche ou une Pull Request.

