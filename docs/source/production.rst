=======================================
Prédiction de Production Agricole
=======================================


La fonctionnalité de prédiction de la production agricole d'AgriTech utilise des techniques d'apprentissage automatique pour estimer les rendements des cultures en fonction de plusieurs variables agricoles. Cette fonctionnalité aide les agriculteurs à planifier la production, à optimiser les rendements et à gérer les ressources de manière plus efficace.

 Fonctionnalité
------------------------------

Cette fonctionnalité repose sur la modélisation des rendements agricoles en fonction de plusieurs facteurs influençant la production. Elle utilise des modèles de régression pour prévoir la production d'une culture en fonction des données disponibles.

 Caractéristiques Utilisées
------------------------------

Les caractéristiques utilisées pour prédire la production agricole incluent :

- **Region** : Région ou pays où se trouve le champ.
- **Produit** : Type de culture.
- **Pluviométrie Moyenne** : Précipitations annuelles moyennes (en mm).
- **Pesticides** : Quantité de pesticides utilisés (en kg).
- **Température Moyenne** : Température moyenne (en °C).

 Modèles de Machine Learning Testés
------------------------------

Plusieurs modèles de régression ont été testés pour prédire la production agricole, parmi lesquels :

- **Régression Linéaire**
- **Lasso**
- **Ridge**
- **K-Nearest Neighbors**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting**
- **XGBoost**

 Meilleur Modèle
------------------------------

Le modèle le plus performant pour la prédiction de la production agricole est **Random Forest Regressor**, avec les performances suivantes :

- **Erreur Quadratique Moyenne (RMSE)** : 9892.72
- **Score R²** : 0.9867

 Objectifs
------------------------------

- **Précision de la Prédiction** : Prédire les rendements agricoles avec une grande précision afin de maximiser la production.
- **Optimisation des Ressources** : Aider les agriculteurs à mieux planifier l'utilisation de l'eau, des engrais et des pesticides.
- **Prise de Décision Éclairée** : Fournir des informations clés pour une prise de décision plus éclairée en matière de gestion des cultures.

 Applications
------------------------------

- Prévision des rendements agricoles pour chaque type de culture.
- Optimisation des pratiques agricoles en fonction des prédictions de production.
- Aide à la planification des ressources et à la gestion des récoltes.

 Technologies Utilisées
------------------------------


- **Scikit-learn** pour l'entraînement et l'évaluation des modèles de machine learning.
- **Random Forest Regressor** comme modèle principal pour la prédiction de la production.
- **Flask** pour la mise en place de l'API permettant l'intégration avec l'application AgriTech.

 Conclusion
------------------------------

La fonctionnalité de prédiction de production agricole permet aux agriculteurs de mieux prévoir les rendements et d'optimiser leur gestion des ressources, contribuant ainsi à une agriculture plus durable et plus efficace.

