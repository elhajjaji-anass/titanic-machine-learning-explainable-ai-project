# Titanic ML & Explainable AI (XAI) Project

## 🚢 Projet : Analyse du Dataset Titanic

Ce projet a été réalisé dans le cadre du **Master Machine Learning Avancée et Intelligence Multimedia (MLAIM)** à l'Université Sidi Mohamed Ben Abdellah, Fès, en 2025.

L'objectif principal est de :

- Analyser le dataset **Titanic.csv**.
- Construire des modèles prédictifs pour estimer la probabilité de survie des passagers.
- Interpréter les prédictions à l'aide de **SHAP (Explainable AI)** pour identifier les facteurs influençant la survie.

---

## 🧩 Structure du projet

```
titanic-ml-xai/
│
├── data/
│   └── Titanic.csv                 # Dataset original
│
├── Titanic_ML_XAI_Colab.ipynb      # Notebook complet sur Google Colab
│
├── figures/
│   ├── infos_data.png               # Screenshot dataset
│   ├── shap_summary.png             # SHAP summary plot
│   └── shap_bar.png                 # Importance globale SHAP
│
├── report/
│   └── Titanic_ML_XAI_Report.pdf   # Rapport final LaTeX
├── requirements.txt                # Librairies Python nécessaires
└── README.md                       # Ce fichier
```

---

## 🧪 Exécution du projet

1. Ouvrir le notebook sur **Google Colab** :

[Ouvrir le notebook Colab](https://colab.research.google.com/)

2. Installer les dépendances (si nécessaire) :

```python
!pip install pandas scikit-learn shap matplotlib seaborn
```

3. Exécuter toutes les cellules : le notebook couvre :

- Analyse exploratoire (EDA)
- Prétraitement et nettoyage des données
- Modélisation (Random Forest et Gradient Boosting)
- Interprétation avec **SHAP** (XAI)

---

## 📈 Résultats principaux

- **Random Forest Accuracy :** 79,78 %
- **Gradient Boosting Accuracy :** 80,90 % ✅

### Variables clés identifiées par SHAP

- Sexe (`Sex_female`)
- Classe du billet (`Pclass`)
- Prix du billet (`Fare`)
- Âge (`Age`)
- Taille de la famille (`SibSp + Parch`)

Les visualisations SHAP fournissent une interprétation claire et transparente du modèle.

---

## 📝 Rapport académique

Le rapport complet est disponible dans `report/Titanic_ML_XAI_Report.pdf`.  
Il contient :

- Analyse exploratoire détaillée.
- Prétraitement des données.
- Modélisation prédictive.
- Analyse Explainable AI avec SHAP.
- Interprétation des résultats et conclusions.

---

## 🔮 Prochaines étapes

- Combiner SHAP avec LIME pour des explications plus robustes.
- Ajouter de nouvelles features (emplacement des cabines, regroupements de billets).
- Déployer le modèle et les visualisations dans un tableau de bord interactif.

---

## 🏷 Licence

Ce projet est à usage éducatif et académique.

