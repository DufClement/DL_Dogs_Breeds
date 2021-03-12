# DL_Dogs_Breeds
# Sujet 
L'association vous demande de réaliser un algorithme de détection de la race du chien sur une photo, afin d'accélérer leur travail d’indexation.

Vous avez peu d’expérience sur le sujet, vous décidez donc de contacter un ami expert en classification d’images.
Il vous conseille dans un premier temps de pré-processer des images avec des techniques spécifiques (e.g. éventuellement modification de la taille des images, cropping, ) et de réaliser de la data augmentation.

Ensuite, il vous incite à mettre en œuvre deux approches que vous comparerez en termes de temps de traitement et de résultat :

1. Une première en réalisant votre propre réseau CNN, en vous inspirant de réseaux CNN existants. Prenez soin d'optimiser certains hyperparamètres (des layers du modèle, de la compilation du modèle et de l’exécution du modèle)

2. Une deuxième en utilisant le transfer learning, c’est-à-dire en utilisant un réseau déjà entraîné, et en le modifiant pour répondre à votre problème.

Concernant le transfer learning, votre ami vous précise que :
- Une première chose obligatoire est de réentraîner les dernières couches pour prédire les classes qui vous intéressent seulement.
- Il est également possible d’adapter la structure (supprimer certaines couches, par exemple) ou de réentraîner le modèle avec un très faible learning rate pour ajuster les poids à votre problème (plus long) et optimiser les performances.


# Données traitées 
- Telecharger les images de chiens sur : http://vision.stanford.edu/aditya86/ImageNetDogs
- Extraire le dossier images et le déposer dans le dossier du projet 

# Installation 
- pip install pandas
- pip install tensorflow
- pip install matplotlib


- Placer le dossier avec les images déziper dans le dossier Projet
- Éxecuter le premier notebook Dogs_breed.ipynb pour répartir les images en train test valid 
