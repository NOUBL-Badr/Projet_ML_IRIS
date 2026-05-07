# Projet_ML_IRIS

### Auteur
Nom : __Badr Eddine NOUBL__

## Projet de Classification Supervisée : Analyse Comparative

Ce projet implémente un pipeline complet d'apprentissage supervisé en utilisant le dataset __Iris__. L'objectif est de comparer l'efficacité de différents __modèles linéaires__, __non-linéaires__ et d'__ensemble__, tout en analysant le compromis entre __performance prédictive__ et coût __computationnel__.

## Objectifs du Projet
_Implémenter les modèles clés du cursus : __Régression Logistique__, __KNN__, __Arbres de Décision__ et __Ensembles (Random Forest, Boosting)__._

_Évaluer les performances via des métriques robustes (Accuracy, F1-Score)._

_Analyser l'interprétabilité des modèles (règles de décision et importance des variables)._

_Vérifier la capacité de généralisation via la validation croisée et l'analyse biais/variance._

## Structure du Pipeline
### 1. Préparation des Données
Le dataset est divisé en deux ensembles distincts :

* Entraînement (80%) : Utilisé pour l'apprentissage des paramètres.

* Test (20%) : Utilisé exclusivement pour la validation finale.

### 2. Métriques d'Évaluation
* Conformément aux exigences académiques, les modèles sont vérifiés via :

* Accuracy & F1-Score : Pour la performance globale.

* Temps d'exécution : Mesure de l'efficacité du code.

* Matrice de Confusion : Pour la détection précise des types d'erreurs.

* Courbe ROC/AUC : Pour l'analyse de la séparation des classes.

## Visualisations Incluses
1. Le notebook génère automatiquement plusieurs graphiques de diagnostic :

2. Comparaison Performance/Temps : Visualisation double axe des scores vs vitesse.

3. Arbre de Décision : Représentation graphique de la logique "If-Then" pour l'extraction de règles.

4. Importance des Caractéristiques : Classement des variables les plus discriminantes (ex: Petal Width).

5. Learning Curves : Analyse du risque d'overfitting (High Variance).

## Utilisation
1. Ouvrir le fichier dans Google Colab.

2. Exécuter les cellules dans l'ordre chronologique (Imports -> Préparation -> Modélisation -> Évaluation).

3. Consulter le tableau comparison_df pour le classement final des modèles.

