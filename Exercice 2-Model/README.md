# Segmentation d'images

## Architecture UNet : introduction

L'architecture UNet est un réseau de neurone pour la segmentation d'images. Sans aller dans les détails, ce réseau est divisé en deux parties :

- Encoder : Sous-échantillonage de l'image de départ et extraction des motifs de cet image
- Decoder : Sur-échantillonage de la matrice de sortie de l'encoder en combinant les cartes de caractéristiques des couches de l'encoder avec les cartes de caractéristiques du decoder

![u-net-architecture-1024x682](https://github.com/user-attachments/assets/0cb3c28a-ff70-4099-b9ab-8087f95482c3)

## Exercice

1- Télécharger le fichier .iynb sur votre PC.

2- Ouvrer votre Google Drive puis glisser votre fichier dans votre google drive

3- Connecter le GPU puis executer chaque cellule 

4- Sur [Google Doc](https://docs.google.com/document/d/1oOv73m_-I8yRQnuqTiYCmsYdHgRmJoF4hXqMTjh2EyU/edit?usp=sharing), fixer les hyperparamètres puis lancer l'entrainement. Examiner les résultats :

- Comportement de la courbe d'apprentissage

- Evaluation sur les données test
