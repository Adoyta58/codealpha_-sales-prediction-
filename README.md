
# 📈 CodeAlpha_Sales_Prediction

Ce projet a été réalisé dans le cadre de mon stage en data science chez **CodeAlpha**.  
Il consiste à prédire les ventes en fonction de facteurs tels que les dépenses publicitaires sur différents canaux (TV, radio, journaux), à l'aide de techniques de régression linéaire.

---

## 🎯 Objectif du projet

L’objectif est de :
- Comprendre l’impact de chaque canal publicitaire sur les ventes.
- Construire un modèle de prédiction à partir des données publicitaires.
- Fournir des insights utiles pour orienter les stratégies marketing.

---

## 🧰 Outils et bibliothèques utilisés

- **Python 3**
- **Pandas** – pour la manipulation de données
- **Matplotlib** & **Seaborn** – pour la visualisation
- **Scikit-learn** – pour la modélisation prédictive (régression linéaire)

---

## 📊 Jeu de données

- **Source** : [Kaggle - Advertising Dataset](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)
- Le dataset contient les dépenses publicitaires sur trois canaux : TV, radio et journaux, ainsi que les ventes correspondantes.

---

## 🧪 Étapes du projet

1. **Chargement et visualisation des données**
   - Inspection des types, valeurs nulles, statistiques descriptives.
   - Visualisations des relations entre variables.
   
2. **Préparation des données**
   - Séparation des variables indépendantes (X) et dépendante (y).
   - Division du jeu de données en ensembles d’entraînement et de test.

3. **Modélisation**
   - Régression linéaire avec `Scikit-learn`.
   - Ajustement du modèle sur les données d’entraînement.

4. **Évaluation**
   - Prédiction sur le jeu de test.
   - Calcul de la performance (RMSE, R²).
   - Interprétation des coefficients pour déterminer les variables les plus influentes.

---
