# Spam/Ham Classifier - Version 2

## Description
Ce projet est un **classificateur de messages SMS** capable de distinguer les messages **spam** (indésirables) des messages **ham** (légitimes).  
Il utilise **Python**, **scikit-learn** et **NLTK** pour le traitement automatique du langage (NLP).

### Version 2
- Dataset réel Kaggle (`spam.csv`) avec 4 000+ SMS.
- Préprocessing avancé : suppression ponctuation, chiffres, URLs, conversion minuscules.
- Vectorisation avec `CountVectorizer`.
- Modèle **Multinomial Naive Bayes**.
- Évaluation : Accuracy, Precision, Recall, F1-Score.
- Test facile sur nouveaux messages.

---

## Dataset
Colonnes :
- `v1` : label (`ham` ou `spam`)
- `v2` : message SMS brut

---

## Installation

1. **Cloner le dépôt**
```bash
git clone https://github.com/jeys47/Basic_Spam_Classifier.git
cd nom_du_repo

## Evaluation
Accuracy
Precision, Recall, F1-score
Macro / weighted averages

  

