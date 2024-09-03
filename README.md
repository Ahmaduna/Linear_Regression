# Prédiction des Prix des Logements à Boston

## Aperçu
Ce projet met en œuvre un modèle de **régression linéaire** pour prédire la valeur médiane des logements à Boston en fonction de diverses caractéristiques. Grâce aux bibliothèques de science des données de Python, nous explorons, modélisons et évaluons le dataset pour en tirer des insights significatifs.

## Structure du Projet
- **boston.csv** : Le dataset contenant les données sur les logements à Boston.
- **Linear_Regression_Boston_Housing.ipynb** : Jupyter Notebook contenant le code pour l'exploration des données, le prétraitement, l'entraînement du modèle et son évaluation.

## Étapes Clés
1. **Chargement des Données** : Importation du dataset et nettoyage pour l'analyse.
2. **Analyse Exploratoire des Données (EDA)** : Comprendre les corrélations des caractéristiques et visualiser les principaux motifs.
3. **Modélisation** : Entraînement d'un modèle de régression linéaire avec Scikit-Learn et Statsmodels.
4. **Évaluation** : Évaluation des performances du modèle avec des métriques comme RMSE, R², et analyse des résidus.
5. **Visualisation** : Graphiques pour valider les hypothèses du modèle.

## Résultats
- **Coefficients du Modèle** : Aperçu de l'importance des caractéristiques.
- **Métriques de Performance** : MSE, R², et tests statistiques confirment la robustesse du modèle.
- **Analyse des Résidus** : Tests de normalité et vérifications d'autocorrélation garantissent la validité du modèle.

## Prérequis
- `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`
  
Installer les dépendances :
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
