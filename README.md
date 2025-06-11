# Classification des fleurs d'Iris avec un Perceptron

Ce notebook présente une implémentation d'un modèle de Perceptron pour classer les fleurs d'Iris en utilisant le dataset Iris de scikit-learn.

## Description du projet

L'objectif de ce projet est de construire un modèle de classification capable de distinguer les différentes espèces de fleurs d'Iris (Setosa, Versicolor, Virginica) en se basant sur quatre caract¨¦ristiques morphologiques :
- Longueur des sépales
- Largeur des sépales
- Longueur des pétales
- Largeur des pétales

## Structure du notebook

1. **Chargement des données** : Utilisation de `load_iris()` pour importer le dataset
2. **Préparation des données** :
   - Séparation en ensembles d'entraînement et de test (80%/20%)
   - Normalisation des données avec `StandardScaler`
3. **Modélisation** :
   - Création d'un mod¨¨le Perceptron avec les paramètres :
     - `max_iter=1000` (nombre maximum d'itérations)
     - `eta0=0.1` (taux d'apprentissage)
     - `random_state=42` (pour la reproductibilité)
4. **Evaluation** :
   - Calcul de la précision (accuracy)
   - Rapport de classification détaill¨¦
   - Nombre de prédictions effectuées

## Résultats

Le modèle atteint une précision de **90%** sur l'ensemble de test. Le rapport de classification montre des performances détaillées pour chaque classe :

| Classe  | Précision | Rappel | F1-score | Support |
|---------|-----------|--------|----------|---------|
| 0       | 0.91      | 1.00   | 0.95     | 10      |
| 1       | 0.80      | 0.89   | 0.84     | 9       |
| 2       | 1.00      | 0.82   | 0.90     | 11      |

**Accuracy moyenne** : 0.90  
**Nombre de prédictions** : 30

## Prérequis

Pour exécuter ce notebook, vous aurez besoin des bibliothèques Python suivantes :
- scikit-learn
- numpy
- pandas (pour une éventuelle extension de l'analyse)

## Comment exécuter

1. Clonez le dépôt ou téléchargez le notebook
2. Installez les dépendances nécessaires : `pip install scikit-learn numpy`
3. Exécutez le notebook cellule par cellule ou dans son intégralité

## Améliorations possibles

- Essayer d'autres algorithmes de classification (SVM, Random Forest, etc.)
- Optimiser les hyperparamètres du Perceptron
- Ajouter une visualisation des données et des résultats
- Implémenter une validation croisée pour une évaluation plus robuste


