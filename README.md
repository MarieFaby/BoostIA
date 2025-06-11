# 🌸 Analyse du Dataset Iris

Ce projet Jupyter Notebook a pour objectif d'explorer, visualiser et analyser le célèbre dataset **Iris**, utilisé dans l'apprentissage automatique pour la classification. Il inclut un aperçu statistique, des visualisations graphiques et une modélisation avec des algorithmes supervisés.

## 📁 Contenu du projet

- `iris.ipynb` : Notebook principal contenant toutes les étapes du projet :
  - Importation et description du dataset
  - Analyse exploratoire des données (EDA)
  - Visualisations avec Seaborn/Matplotlib
  - Préparation des données pour le Machine Learning
  - Modélisation avec `KNeighborsClassifier` ou d'autres modèles
  - Évaluation des performances

## 📦 Librairies utilisées

- Python 3.x
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/)

## 📊 Dataset

Le dataset Iris contient 150 observations de fleurs, réparties en trois espèces :
- *Setosa*
- *Versicolor*
- *Virginica*

Chaque observation contient 4 caractéristiques :
- Longueur des sépales
- Largeur des sépales
- Longueur des pétales
- Largeur des pétales

Le dataset est accessible via `sklearn.datasets.load_iris()`.

## 🚀 Lancement du projet

### 1. Cloner ce dépôt

```bash
git clone https://github.com/votre-utilisateur/iris-classification.git
cd iris-classification
