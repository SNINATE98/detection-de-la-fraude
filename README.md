Introduction

Ce projet porte sur la mise en place d’un système de détection de la fraude à partir de données réelles de transactions financières.
L’objectif principal est d’identifier les opérations potentiellement frauduleuses en analysant les motifs et comportements anormaux dans des variables clés telles que le type de transaction, le montant ou les soldes des comptes.

Étant donné le déséquilibre important des classes — les cas de fraude représentant une très faible proportion de l’ensemble des transactions — une attention particulière est portée à la gestion de ce déséquilibre, à l’évaluation des modèles à l’aide de métriques adaptées (précision, rappel, PR AUC) et à l’ajustement du seuil de décision pour optimiser la détection.

En complément des modèles de classification classiques (comme la régression logistique et la forêt aléatoire), une analyse temporelle est également menée afin d’étudier les dynamiques dans le temps des activités frauduleuses.

Le projet se conclut par le développement d’une application interactive Streamlit, permettant à l’utilisateur de saisir les caractéristiques d’une transaction et d’obtenir une prédiction de fraude en temps réel.

Source du jeu de données : Kaggle – Fraud Detection Dataset
[https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset/data](https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset/data)
