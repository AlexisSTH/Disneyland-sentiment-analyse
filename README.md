# Analyse de Sentiment — Avis Disneyland (NLP)

Analyse de 42 000+ avis clients des parcs Disneyland (Californie, Paris, Hong Kong) avec deux approches : lexicale (VADER) et Machine Learning (Logistic Regression).

## Objectif
Identifier automatiquement le sentiment des avis clients et comparer les performances des deux approches.

## Résultats
| Méthode | Accuracy | F1 Négatif | F1 Neutre | F1 Positif |
|---------|----------|------------|-----------|------------|
| VADER | 80% | 0.42 | 0.05 | 0.90 |
| Logistic Regression | 85% | 0.60 | 0.31 | 0.93 |

## Stack technique
Python, Pandas, NLTK, VADER, Scikit-learn, TF-IDF, Matplotlib, Seaborn

## Dataset
[Disneyland Reviews — Kaggle](https://www.kaggle.com/datasets/arushchillar/disneyland-reviews)

## Auteur
Alexis Sayasith
