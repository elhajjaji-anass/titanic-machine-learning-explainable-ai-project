# Titanic ML & Explainable AI (XAI) Project

Projet académique réalisé dans le cadre du Master MLAIM à l'Université Sidi Mohamed Ben Abdellah, Fès (2025).  
Analyse du dataset Titanic avec modélisation ML (Random Forest, Gradient Boosting) et interprétation avec **SHAP (Explainable AI)**.

---

## 🧪 Exécution du projet

1. Télécharger le dataset depuis Kaggle :

[Titanic Dataset](https://www.kaggle.com/datasets/shubhamgupta012/titanic-dataset)

2. Placer le fichier `Titanic.csv` dans le dossier `data/`.

3. Ouvrir le notebook sur **Google Colab** :

[Ouvrir le notebook Colab](https://colab.research.google.com/)

4. Installer les dépendances si nécessaire :

```python
!pip install pandas scikit-learn shap matplotlib seaborn
```

5. Exécuter toutes les cellules pour reproduire l'analyse.

Résultats principaux

Random Forest Accuracy : 79,78 %

Gradient Boosting Accuracy : 80,90 %

Variables clés selon SHAP

```
Sex_female, Pclass, Fare, Age, SibSp + Parch
```

6. structure de projet
```
   titanic-ml-xai/
│
├── data/                  # Dataset Titanic.csv
├── notebooks/XAI_ML.ipynb # Notebook complet
├── imgs/               # Visualisations SHAP et screenshots              
└── README.md
```


