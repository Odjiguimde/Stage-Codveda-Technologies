# 🎓 Stage Machine Learning & Data Science — Codveda Technologies

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Pandas](https://img.shields.io/badge/pandas-Data-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Status](https://img.shields.io/badge/Statut-Stage%20terminé-success)]()

Ce dépôt regroupe les **9 notebooks Jupyter** réalisés dans le cadre de mon stage à distance en **Intelligence Artificielle & Machine Learning** chez **[Codveda Technologies](https://www.codveda.com)**, entreprise indienne de services IT et de formation technologique (Chandrapur, Maharashtra).

Le programme s'est déroulé sur **trois niveaux de complexité croissante** — basique, intermédiaire, avancé — couvrant l'ensemble du cycle d'un projet de machine learning : prétraitement de données, apprentissage supervisé (régression et classification), apprentissage non supervisé, et deep learning.

> 📄 Le rapport de stage complet, incluant la présentation de l'entreprise, la méthodologie et le bilan de l'expérience, est disponible dans ce dépôt : [`Rapport_de_stage_Codveda.pdf`](./Rapport_de_stage_Codveda.pdf)

---

## 👤 À propos

- **Stagiaire :** Oumaro Titans DJIGUIMDE
- **Établissement :** École Supérieure Multinationale des Télécommunications (ESMT Dakar) — Filière Ingénierie de Conception des Télécommunications (INGC2)
- **Entreprise d'accueil :** Codveda Technologies (Inde) — pôle Intelligence Artificielle & Machine Learning
- **Format :** Stage 100 % à distance, encadré par un mentor
- **Maître de stage :** M. Kaustubh Duke, Directeur Scientifique

---

## 🗂️ Structure du dépôt

| # | Notebook | Niveau | Dataset | Objectif |
|---|----------|--------|---------|----------|
| 1 | [`1_Data_Preprocessing.ipynb`](./1_Data_Preprocessing.ipynb) | Basique | Telco Churn (BigML) | Pipeline complet de prétraitement : imputation, encodage, standardisation, split stratifié |
| 2 | [`2_Linear_Regression.ipynb`](./2_Linear_Regression.ipynb) | Basique | Boston Housing | Régression linéaire pour la prédiction du prix médian des logements |
| 3 | [`3_KNN_Classifier.ipynb`](./3_KNN_Classifier.ipynb) | Basique | Iris | Classification K-Nearest Neighbors et optimisation de K |
| 4 | [`4_Logistic_Regression.ipynb`](./4_Logistic_Regression.ipynb) | Intermédiaire | Telco Churn | Régression logistique + interprétation des odds ratio pour la prédiction du churn client |
| 5 | [`5_Decision_Tree.ipynb`](./5_Decision_Tree.ipynb) | Intermédiaire | Iris | Arbre de décision, visualisation et élagage (cost-complexity pruning) |
| 6 | [`6_KMeans_Clustering.ipynb`](./6_KMeans_Clustering.ipynb) | Intermédiaire | Stock Prices (2014–2017) | Segmentation d'actions boursières par K-Means + PCA |
| 7 | [`7_Random_Forest.ipynb`](./7_Random_Forest.ipynb) | Avancé | Telco Churn | Random Forest + GridSearchCV, analyse d'importance des variables |
| 8 | [`8_SVM_Classification.ipynb`](./8_SVM_Classification.ipynb) | Avancé | Iris (versicolor vs virginica) | SVM, comparaison des noyaux linéaire vs RBF, courbes ROC |
| 9 | [`9_Neural_Network_Keras.ipynb`](./9_Neural_Network_Keras.ipynb) | Avancé | Sentiment Dataset | Réseau de neurones feed-forward (TensorFlow/Keras) pour la classification de sentiment |

---

## 📊 Résultats clés

| Notebook | Modèle | Métrique principale |
|---|---|---|
| Régression linéaire (Boston) | LinearRegression | R² = 0,669 · RMSE = 4,93 |
| KNN (Iris) | KNeighborsClassifier (K=1) | Accuracy = 0,967 |
| Régression logistique (Churn) | LogisticRegression (balanced) | Accuracy = 0,777 · AUC = 0,818 |
| Arbre de décision (Iris) | DecisionTreeClassifier (élagué) | Accuracy = 0,967 · F1 = 0,967 |
| K-Means (Actions) | KMeans (K=4) | 4 segments distincts identifiés |
| Random Forest (Churn) | RandomForestClassifier + GridSearchCV | Accuracy = 0,951 · F1 = 0,822 |
| SVM (Iris) | SVC (noyau RBF) | Accuracy = 0,88 · AUC = 0,981 |
| Réseau de neurones (Sentiment) | Keras Sequential | Accuracy test = 0,816 |

---

## 🛠️ Technologies utilisées

- **Langage :** Python
- **Manipulation de données :** pandas, NumPy
- **Machine Learning :** scikit-learn (régression, classification, clustering, prétraitement, GridSearchCV, validation croisée)
- **Deep Learning :** TensorFlow / Keras
- **Visualisation :** Matplotlib, Seaborn
- **Environnement :** Jupyter Notebook / Kaggle Notebooks
- **Gestion de version :** Git & GitHub

---

## ▶️ Utilisation

```bash
# Cloner le dépôt
git clone https://github.com/Odjiguimde/Stage-Codveda-Technologies.git
cd codveda-ml-internship

# Installer les dépendances
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow jupyter

# Lancer Jupyter
jupyter notebook
```

Chaque notebook est autonome et documenté (cellules markdown expliquant le contexte, la démarche et l'interprétation des résultats) et peut être exécuté indépendamment.

---

## 🎯 Compétences développées

- Maîtrise du cycle complet d'un projet de machine learning : prétraitement → entraînement → évaluation → interprétation
- Algorithmes supervisés (régression, KNN, arbres de décision, Random Forest, SVM) et non supervisés (K-Means)
- Optimisation d'hyperparamètres (GridSearchCV) et validation croisée
- Choix de métriques adaptées au contexte métier (F1-score, rappel, AUC) plutôt que la seule accuracy sur données déséquilibrées
- Première expérience de conception de réseaux de neurones avec TensorFlow/Keras
- Autonomie et rigueur méthodologique dans un contexte de travail à distance

---

## 📄 Licence

Ce projet est publié à des fins pédagogiques et de démonstration de compétences, dans le cadre de la validation d'un stage académique.

## 📬 Contact

**Oumaro Titans DJIGUIMDE**
📍 Dakar, Sénégal
🔗 [LinkedIn](https://www.linkedin.com) · [GitHub](https://github.com)
