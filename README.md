# Analyse des discours de la FED – Prédiction du Federal Funds Rate

Ce projet vise à prédire l’évolution du taux des fonds fédéraux (Federal Funds Rate) à partir des discours publics de la FED, en combinant des techniques de traitement automatique du langage (NLP) et des modèles de classification supervisée.

## 📁 Structure du projet

- `projet.ipynb` : Notebook principal du projet. Il contient l’ensemble des étapes de traitement :
  - Nettoyage et prétraitement des textes
  - Vectorisation (CountVectorizer, TF-IDF, GloVe)
  - Modélisation (Naive Bayes, SVM, Régression Logistique, XGBoost, FinBERT)
  - Évaluation des performances

- `scrapper.ipynb` : Script utilisé pour automatiser le **webscraping des discours** publiés sur le site de la Federal Reserve. Ce notebook télécharge et organise les discours en format texte dans le dossier `DATA/`.

- `DATA/` : Répertoire contenant les discours scrappés depuis le site de la FED, utilisés comme jeu de données principal pour l’analyse.

## Prérequis

- Python 3.11.8


