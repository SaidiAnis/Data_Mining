# Projet de Data Mining - Extraction de Texte

## Description
Ce projet est une analyse de data mining axée sur le **text mining** appliqué aux articles de Reuters. Le projet inclut des étapes de prétraitement des données textuelles, la transformation TF-IDF, la réduction de dimension, et l’application de techniques de clustering pour identifier des patterns dans les données textuelles.

## Structure du Projet
1. **Chargement et Prétraitement des Données** : Importation des articles Reuters et nettoyage des textes.
2. **Vectorisation** : Transformation des textes en matrice de termes pondérée par **TF-IDF**.
3. **Réduction de Dimension** :
   - **PCA** : Réduction des données à 3 dimensions pour visualiser les clusters.
   - **NMF** : Factorisation en matrice non-négative pour obtenir les vecteurs de caractéristiques et la matrice de clusters.
4. **Clustering et Visualisation** :
   - Visualisation des clusters en 3D, avec un code permettant d’ajuster les angles de vue pour examiner la séparation des clusters.
   - Évaluation des clusters avec des métriques comme **purity score**, **entropie**, **indice de Dunn**, **indice Davies-Bouldin** et **indice Calinski-Harabasz**.

## Installation
Les bibliothèques suivantes sont nécessaires pour exécuter le notebook :
- `numpy`
- `pandas`
- `nltk`
- `scikit-learn`
- `matplotlib`
- `seaborn`
  
Installez-les via `pip install -r requirements.txt` si un fichier `requirements.txt` est fourni.

## Utilisation
1. **Télécharger les données Reuters** : Assurez-vous d'avoir les fichiers de données nécessaires (non inclus dans ce repository) et placez-les dans le répertoire spécifié dans le code.
2. **Exécuter les cellules du notebook** pour reproduire l'analyse et les visualisations des clusters.

## Résultats
Les principales conclusions incluent l'obtention de clusters significatifs dans les données Reuters et l’identification des termes les plus fréquents. La visualisation en 3D permet d’observer la distribution des articles par thèmes principaux.

## Contact
Pour toute question, veuillez contacter [votre email] ou consulter mon profil GitHub pour d'autres projets similaires.

