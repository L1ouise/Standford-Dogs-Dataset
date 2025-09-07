# 🐶 Standford-Dogs-Dataset 

Ce projet est un modèle de deep learning entraîné pour reconnaître les races de chiens à partir d’images, basé sur le dataset Stanford Dogs. Il utilise TensorFlow/Keras et a été entraîné sur Kaggle.

## 📦 Dataset

- **Source** : [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/)
- **Nombre de classes** : 120 races
- **Format** : Images + labels one-hot encodés

## 🧠 Objectif

- Classifier les races de chiens à partir d’images
- Atteindre une bonne **top-5 accuracy** (le bon label dans les 5 premières prédictions)
- Sauvegarder le meilleur modèle avec `ModelCheckpoint`

## 📈 Résultats

- **Accuracy** : ~30%
- **Top-5 Accuracy** : ~66%
- **Val Loss minimale** : 2.84
- **Modèle sauvegardé** : `best_model.h5`

## 📁 Structure du projet

