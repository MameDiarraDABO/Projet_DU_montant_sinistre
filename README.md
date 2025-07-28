# Prédiction du montant des sinistres automobiles


## 📁 Données utilisées

- Données de sinistres automobiles anonymisées : informations sur les assurés, véhicules, types de sinistres, contextes, montants
- Variables explicatives : âge de l’assuré, type de véhicule, type de garantie, zone géographique, ancienneté du contrat, etc.

---

## 🛠️ Méthodologie

### 1. Préparation des données
- Nettoyage des montants aberrants, encodage des variables catégorielles
- Création de nouvelles variables : ratio sinistres/nombre de contrats, sinistres par région...

### 2. Analyse exploratoire
- Étude de la distribution des montants (fortement asymétrique)
- Visualisation des corrélations et détection des outliers

### 3. Modélisation
- Régression linéaire (base de référence)
- Modèles non linéaires : Random Forest Regressor, XGBoost Regressor
- Comparaison des modèles selon RMSE, MAE, R²

### 4. Interprétation
- Importance des variables (gain, permutation importance)
- Interprétabilité avec SHAP pour comprendre les facteurs influençant les montants élevés

---
