# 🏡 House Price Prediction - ML Model  

## 📌 Description  
Ce projet utilise l'apprentissage automatique pour prédire le prix des maisons en fonction de variables géographiques et structurelles. Nous avons utilisé un modèle **RandomForestClassifier** avec une **discrétisation des prix**, ce qui améliore la fiabilité des prédictions.  

## 📊 Données et Prétraitement  
- 📂 **Données** : Dataset immobilier (surface, proximité aux commerces/transports, âge du bien, latitude, longitude, etc.)  
- 🔄 **Préprocessing** :  
  - Normalisation avec `StandardScaler`  
  - Discrétisation des prix avec `KBinsDiscretizer`  
  - Division du dataset en **train/test** avec `train_test_split`  

## 🚀 Modèle de Machine Learning  
- **Algorithme** : `RandomForestClassifier` avec 40 arbres  
- **Évaluation** :  
  - R² Score : `0.98`  
  - Accuracy Score : `0.96`  

## 🛠️ Installation et Exécution  
### 1️⃣ Cloner le repo  
```bash
git clone https://github.com/votre_nom/House-Price-Prediction.git
cd House-Price-Prediction
