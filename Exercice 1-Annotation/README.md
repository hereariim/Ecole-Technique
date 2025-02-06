# Annotation des images

Annotation des images est une activité où un expert annote à sa main les étiquettes associés à une image. Les images annotées sont appelées vérité terrain.

**Exemples :**

- Classification d'images : une image d'animaux est associée à l'espèce animal figurant sur l'images

- Segmentation d'images : une image d'un objet est associée à un masque où la couleur couvre l'objet figurant sur l'image

- Détection d'objet : une image d'un objet est associée à un tableau de coordonnées d'une boîte englobante encadrant l'objet figurant sur l'image

![Ecole technique](https://github.com/user-attachments/assets/3e0729ad-a032-4b3b-bf44-0dc333fd61a5)

## Intérêt

A partir d'une image couleur et de sa vérité terrain, le modèle va tenter de retrouver les vérités terrains réalisée par l'expert. La qualité de cette quête repose fondamentalement sur la qualité des annotations. Une image parfaitement annoté conduit à une bonne performance du modèle. Une image très mal annoté rends cette tache difficilement perfectible.

## Exercice

Très souvent, bien que l'annotation semble être, de loin, une tache pas très fatiguante, atteindre une excellente annotation est dans les faits difficiles. Cette activité nécessite en réalité un expert dans le domaine, de l'attention sur l'image et de la rigueur dans l'annotation sous la contrainte du temps.

Dans cette exercice, on va étudier le biais du jugement de l'annotateur. 

### Consignes

Sur label me, annoter les feuilles sur l'image **label_me_TP.tif**.

a) Ouvrir label me à partir de votre console (ou le logiciel)

b) Glisser votre image dans la fenêtre labelme

c) **Annoter individuellement chaque feuille que vous voyez**

d) Sur [google sheet](https://docs.google.com/spreadsheets/d/15odfotj9SrouKqpQQ2fR2GaOFjlhJsiLpN09QjCSjnw/edit?usp=sharing), noter le nombre de feuille annoté
