## **README - Scoring du Risque de Crédit**

### 🇫🇷 **Projet : Prédiction du Risque de Crédit**

### 📌 **Contexte**
Dans un environnement bancaire où le risque de crédit est un enjeu clé, l’automatisation du processus d’octroi de crédit permet de :
- Réduire les pertes financières liées aux défauts de paiement.
- Optimiser la prise de décision grâce à des modèles prédictifs performants.
- Améliorer l’expérience client en accélérant le traitement des demandes.

### 🎯 **Objectifs**
Ce projet, dirigé par la **BNP**, vise à concevoir un **modèle de scoring du risque de crédit** en trois étapes :
1. **Analyse des données clients** : Exploration statistique et nettoyage des données.
2. **Construction d’une grille de score** : Utilisation d’un modèle de **régression logistique** pour évaluer la probabilité de défaut.
3. **Amélioration avec le Machine Learning** : Comparaison avec des modèles avancés comme **Random Forest et XGBoost**.

### 🛠 **Technologies utilisées**
- **Python** (Jupyter Notebook)
- **Bibliothèques** : `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost`
- **Modélisation statistique** : `statsmodels`, `scipy`
- **Validation et optimisation** : `GridSearchCV`, `Optuna`

### 🔍 **Méthodologie**
- **Préparation des données** : Gestion des valeurs manquantes, encodage des variables catégorielles (`One-Hot Encoding`), normalisation.
- **Analyse exploratoire** : Étude de la distribution des variables, corrélations (`Pearson, ANOVA`).
- **Modélisation** :
  - **Régression logistique** : Construction d’une grille de score en sélectionnant les variables les plus significatives.
  - **Machine Learning** : Test de plusieurs modèles (`Random Forest`, `Gradient Boosting`, `XGBoost`) pour améliorer la prédiction.
- **Évaluation des performances** : **AUC-ROC, GINI, courbes KS**, analyse de l’impact économique des erreurs.

### 📊 **Résultats attendus**
- Développement d’un modèle performant et explicable pour l’octroi de crédit.
- Comparaison entre la **grille de score traditionnelle** et les **modèles avancés**.
- Optimisation du seuil de décision pour **minimiser les pertes financières**.

---

## **README - Credit Risk Scoring** 🇬🇧

### 📌 **Context**
In the banking industry, credit risk assessment is a major challenge. Automating the credit approval process helps:
- **Reduce financial losses** due to payment defaults.
- **Optimize decision-making** with predictive models.
- **Improve customer experience** by speeding up loan processing.

### 🎯 **Objectives**
This project, led by **BNP**, aims to develop a **credit risk scoring model** through three key steps:
1. **Customer data analysis**: Exploratory data analysis and preprocessing.
2. **Scorecard development**: Using a **logistic regression** model to estimate default probability.
3. **Machine Learning enhancement**: Comparing performance with advanced models like **Random Forest and XGBoost**.

### 🛠 **Technologies Used**
- **Python** (Jupyter Notebook)
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost`
- **Statistical modeling**: `statsmodels`, `scipy`
- **Validation & optimization**: `GridSearchCV`, `Optuna`

### 🔍 **Methodology**
- **Data Preparation**: Handling missing values, encoding categorical variables (`One-Hot Encoding`), normalization.
- **Exploratory Analysis**: Studying variable distributions, correlations (`Pearson, ANOVA`).
- **Modeling**:
  - **Logistic Regression**: Building a scorecard by selecting the most significant variables.
  - **Machine Learning**: Testing multiple models (`Random Forest`, `Gradient Boosting`, `XGBoost`) for performance improvement.
- **Performance Evaluation**: **AUC-ROC, GINI, KS curves**, and assessing the economic impact of classification errors.

### 📊 **Expected Results**
- Development of a **high-performing and interpretable** credit scoring model.
- **Comparison between traditional scorecards and machine learning models**.
- **Optimization of the decision threshold** to minimize financial losses.

---

📂 **Structure du projet / Project Structure**
```
📁 scoring
│── 📄 projet_scoring_BNP.ipynb     # Notebook principal avec l'analyse et la modélisation
│── 📄 Rapport scoring.pdf          # Rapport détaillé du projet
│── 📄 Projet Master IREF.pdf       # Cahier des charges du projet
│── 🧮 client_credit_granting.csv   # Dossier contenant les données
```
---

💡 **Contact**
Pour toute question ou suggestion, n’hésitez pas à me contacter via **GitHub** ou **LinkedIn**.
