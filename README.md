Adult Census Income Classification and Clustering using K-Means
📌 Description
Ce projet explore l'application de techniques de Machine Learning sur le dataset Adult Census Income, en utilisant des méthodes de classification et de clustering pour prédire les revenus des individus (>50K$ ou ≤50K$).

🚀 Objectifs
Développer des modèles de machine learning pour classifier les individus en deux catégories de revenus.
Appliquer des techniques de clustering (K-Means) pour analyser les regroupements des données.
Identifier les facteurs influençant les revenus à l'aide des modèles supervisés et non supervisés.
Améliorer la précision des prédictions en optimisant les modèles et en prétraitant les données.
🛠 Modèles Utilisés
Classification :

Logistic Regression
Support Vector Classifier (SVC)
Decision Tree
Random Forest
K-Nearest Neighbors (KNN)
Naive Bayes
Adaboost
Bagging
Extra Trees
Clustering :

K-Means (dont les résultats ont montré des limites sur ce dataset)
📊 Analyse des Résultats
Les modèles supervisés ont montré de meilleures performances que le clustering.
Logistic Regression et SVC ont obtenu des scores élevés en précision et recall.
K-Means n'est pas bien adapté à ce dataset en raison de la faible séparabilité des données.
Une meilleure préparation des données (traitement des valeurs manquantes, normalisation, sélection de features) a contribué à l'amélioration des performances des modèles supervisés.
📂 Fichiers Importants
Adult_Census_Income_Classification_.ipynb → Implémentation des modèles de classification.
Clustering_with_K_Means.ipynb → Expérimentation avec l'algorithme K-Means.
adult.csv.csv → Dataset utilisé pour l'entraînement et les tests.
Presentation.pdf → Contient des informations détaillées sur le travail réalisé, les méthodes utilisées et les résultats obtenus.
Decision Tree Results.pdf → Résultats spécifiques du modèle Decision Tree.