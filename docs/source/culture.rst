Fonctionnalité : Recommandation de Cultures
==========================================

La fonctionnalité de recommandation de cultures d'AgriTech est conçue pour aider les agriculteurs à choisir les cultures les plus adaptées en fonction des caractéristiques spécifiques de leur sol et des conditions climatiques locales. Cette fonctionnalité s'appuie sur des modèles de machine learning robustes et des analyses de données détaillées pour fournir des recommandations précises et pratiques.

Caractéristiques Utilisées
--------------------------

- **Teneur en azote (N)** : Quantité d'azote disponible dans le sol (kg/ha).
- **Teneur en phosphore (P)** : Concentration de phosphore dans le sol (kg/ha).
- **Teneur en potassium (K)** : Niveau de potassium présent dans le sol (kg/ha).
- **Température** : Température ambiante moyenne (°C).
- **Humidité** : Pourcentage d'humidité relative.
- **pH du sol** : Niveau d'acidité ou d'alcalinité du sol.
- **Pluviométrie** : Volume de précipitations reçues (mm).

Modèles Utilisés
----------------

Pour garantir des recommandations optimales, plusieurs modèles de machine learning ont été testés, notamment :

- **Naïve Bayes** : Modèle sélectionné pour sa précision exceptionnelle (99%).
- **Random Forest**
- **LightGBM**
- **Support Vector Machine (SVM)**
- **Réseau de Neurones**

Approche et Résultats
----------------------

1. **Analyse des Données** : Les données relatives au sol et aux conditions climatiques sont collectées et analysées pour identifier les tendances et les corrélations.
2. **Formation des Modèles** : Les modèles sont entraînés sur des ensembles de données riches et diversifiés provenant de sources comme Plant Village.
3. **Recommandations Personnalisées** : Sur la base des données saisies par l'utilisateur, AgriTech fournit une liste hiérarchisée des cultures les plus adaptées, accompagnée de justifications scientifiques.

Cette fonctionnalité est un atout majeur pour les agriculteurs qui souhaitent maximiser leur productivité en prenant des décisions éclairées et basées sur les données.
