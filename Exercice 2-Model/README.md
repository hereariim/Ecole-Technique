# Segmentation d'images

## Architecture UNet : introduction

L'architecture UNet est un réseau de neurone pour la segmentation d'images. Sans aller dans les détails, ce réseau est divisé en deux parties :

- Encoder : Extraction des motifs importants de l'image en utilisant des filtres. Cette extraction utilise un calcul de convolution qui réduit sa dimension. A la fin de cette 
partie, on obtient une image de taille plus petite que l'image de départ.
- Decoder : Reconstruction de la petite image au dimension de l'image de départ. A chaque étape, les cartes de caractéristiques de chaque bloc de l'encoder et les caractéristique  
de decoder sont concaténer pour récupérer les détails fins dans l'image pendant l'augmentation de la dimension.

![u-net-architecture-1024x682](https://github.com/user-attachments/assets/0cb3c28a-ff70-4099-b9ab-8087f95482c3)

## Exercice

Dans cet exercice, on va prendre en main un code écrit en Python. Ce code illustré est écrit dans un notebook.

1- Télécharger le fichier .iynb sur votre PC.

2- Ouvrer votre Google Drive puis glisser votre fichier dans votre google drive

3- Connecter le GPU puis executer chaque cellule 

4- Sur [Google Doc](https://docs.google.com/document/d/1oOv73m_-I8yRQnuqTiYCmsYdHgRmJoF4hXqMTjh2EyU/edit?usp=sharing), fixer les hyperparamètres puis lancer l'entrainement. Examiner les résultats :

- Comportement de la courbe d'apprentissage

- Evaluation sur les données test
