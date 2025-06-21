# Prédiction des impayés locatifs avec des modèles de deep learning pour données tabulaires

Ce dépôt contient les notebooks utilisés dans le cadre de mon mémoire de fin d’études de Master, consacré à l’évaluation de modèles récents de deep learning pour la prédiction des impayés locatifs.

## 📄 Objectif du projet

L’objectif de ce travail est d’explorer le potentiel des architectures modernes de deep learning, spécialement conçues pour les données tabulaires, dans un contexte réel de gestion locative. Nous comparons leurs performances à celles de méthodes plus classiques, tout en accordant une attention particulière à l’explicabilité des modèles.

## 🧠 Modèles étudiés

### 🔬 Modèles de deep learning pour données tabulaires

- **FT-Transformer** (modèle principal)
- TabNet
- TabTransformer

### 🧪 Méthodes classiques utilisées en comparaison

- Arbres de décision
- Random Forest
- XGBoost
- CatBoost

## 🧪 Démarche expérimentale

- **Extraction et prétraitement des données** de facturation locative
- **Application des modèles** à notre problème de classification binaire visant à prédire la présence ou non d’un impayé locatif
- **Évaluation** des performances à l’aide de plusieurs métriques : Accuracy, F1-score, AUC
- **Explicabilité** à l’aide de SHAP et de l’analyse du mécanisme d’attention des Transformers
- Les notebooks utilisent un jeu de données fourni dans le cadre du stage (non inclus dans le dépôt pour des raisons de confidentialité)

## 📊 Principaux résultats

- Le **FT-Transformer** obtient les meilleures performances sur l’ensemble des métriques testées.
- Certains modèles classiques restent néanmoins compétitifs selon les cas.
- L’**explicabilité** s’avère essentielle pour une adoption en contexte métier.

