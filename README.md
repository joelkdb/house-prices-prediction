# 🏡 House Prices Prediction

## 📌 Description
Ce projet vise à prédire le prix des maisons en fonction de différentes caractéristiques (surface, nombre de pièces, localisation, etc.).  
Il est basé sur le dataset Kaggle ["House Prices - Advanced Regression Techniques"](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

## 📊 Dataset
- **Source** : Kaggle  
- **Nombre d’échantillons** : 1460 maisons  
- **Features** : 80 caractéristiques (surface, année de construction, type de toiture, etc.)  
- **Variable cible** : `SalePrice` (le prix de vente en $)  

## ⚙️ Approche
- Analyse exploratoire des données (EDA)
- Traitement des données manquantes et outliers
- Feature engineering
- Entraînement de plusieurs modèles de Machine Learning (Linear Regression, Random Forest, XGBoost)
- Évaluation des performances avec RMSE

## 🚀 Résultats
- Meilleur modèle : **XGBoost avec RMSE = 25000**  
- Insight : Les caractéristiques les plus importantes sont `GrLivArea`, `TotalBsmtSF`, et `OverallQual`.  

## 🛠️ Installation & Exécution
```bash
# Cloner le repo
git clone https://github.com/joelkdb/house-prices-prediction.git
cd house-prices-prediction

# Installer les dépendances
pip install -r requirements.txt

# Lancer le Notebook
jupyter notebook
