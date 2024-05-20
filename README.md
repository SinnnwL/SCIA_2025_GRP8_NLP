# Guide du Projet

Ce guide décrit les notebooks et les modèles inclus dans ce projet de classification et génération de texte. Vous trouverez ci-dessous une brève description de chaque fichier et de son rôle dans le projet.

## Notebooks de Classification

- **bert-classifier.ipynb** : Ce notebook détaille le fine-tuning de BERT pour la classification de spoilers en utilisant les bibliothèques Keras-NLP et transformers.

- **ffn-classifier.ipynb** : Ce notebook présente l'entraînement et l'implémentation de notre modèle feedforward simple avec différents optimizers.

- **logistic_regression.ipynb** : Ce notebook contient les différents modèles de régression logistique (n-gram, tf-idf, word2vec) en utilisant scikit-learn.

- **n_gram_bayesian.ipynb** : Ce notebook décrit l'entraînement de nos modèles 4-gram et d'un modèle bayésien naïf.

## Notebooks de Génération de Texte

- **gpt-2-bad-reviews-generator.ipynb** : Ce notebook décrit le fine-tuning de GPT-2 sur des critiques de films négatives en utilisant la bibliothèque transformers.

- **gpt-2-bad-reviews-generator-inference.ipynb** : Ce notebook présente l'inférence avec notre modèle GPT-2 finetuné sur des critiques négatives.

## Autres Notebooks et Modèles

- **stats-dataset.ipynb** : Ce notebook offre une analyse statistique du jeu de données.

- **word2vec.wordvectors** : Il s'agit de notre modèle Word2Vec entraîné sur l'ensemble des critiques présentes dans le dataset.