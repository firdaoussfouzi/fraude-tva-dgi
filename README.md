# 🔍 Détection de fraude TVA - DGI (Maroc)

Projet réalisé dans le cadre d’un stage à la **Direction Générale des Impôts** (juillet-août 2024).

🎯 **Objectif** : Identifier des comportements frauduleux dans les déclarations de TVA à l’aide d’algorithmes de Machine Learning.

---

## 📊 Étapes du projet

1. **Exploration des données** : importations, achats, ventes déclarées, etc.
2. **Prétraitement** : nettoyage, gestion des valeurs manquantes, transformations log.
3. **Feature Engineering** :
   - Ratios TVA due / déclarée
   - Comparaison entre filiales
   - Moyennes sectorielles
4. **Modélisation** :
   - Classification (fraude / non-fraude)
   - Algorithmes testés : Random Forest, SVM, XGBoost
5. **Évaluation** :
   - Matrice de confusion
   - Précision, rappel, F1-score
   - Analyse de SHAP values

---

## 🛠️ Technologies utilisées

- Python, pandas, scikit-learn, matplotlib, seaborn
- Machine Learning supervisé
- Visualisation avancée

---

## 📌 Résultats

- Précision du modèle : 70%
- Recall sur les cas de fraude : 87%
- Interprétabilité renforcée par SHAP

---

## 📂 Contenu

- `notebooks/` : Notebook principal d’analyse et de modélisation
- `scripts/` : Script Python exécutable pour la reproduction
- `data/` : Exemple de jeu de données anonymisé
- `images/` : Visualisations (matrice de confusion, courbe ROC…)

---

## 👩‍💼 Réalisé par

**Firdaouss FOUZI**  
Data Scientist diplômée de l'INSEA (2025)  
[fouzifirdaouss2@gmail.com](mailto:fouzifirdaouss2@gmail.com) | [LinkedIn]([https://www.linkedin.com/in/firdaouss-fouzi](https://www.linkedin.com/in/firdaouss-fouzi-6746a7257/))

