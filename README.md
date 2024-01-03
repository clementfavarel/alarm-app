# Alarm app

## Description

Alarm app est une application web permettant de créer et de gérer des alarmes.

L'idée m'est venu après avoir passé presque 3 ans à régler mes réveils au jour le jour.

J'ai donc décidé de créer une application qui me permettrait de créer des alarmes et de les gérer facilement, en un clic.

L'application se présente comme suit :

-   Une page de présentation (avec un bouton pour se connecter)
-   Une page de connexion (avec possibilité de créer un compte)
-   Une page création de compte (avec possibilité de se connecter)
-   Une page d'accueil avec la liste des alarmes et un bouton pour en créer une nouvelle
-   Une page de création d'alarme
-   Une page de modification d'alarme (possibilité de supprimer l'alarme)
-   Une page tableau de bord avec une analyse des données de l'application (heure de coucher, heure de lever, temps de sommeil, etc.)

## Installation

L'application est contenue dans un conteneur Docker.

Assurez-vous donc d'avoir Docker et Docker Compose d'installés sur votre machine, voir [ici](https://docs.docker.com/get-docker/) et [ici](https://docs.docker.com/compose/install/).

Pour l'installer, il suffit de cloner le dépôt, installer les dépendances et de lancer la commande suivante :

```bash
git clone https://github.com/clementfavarel/alarm-app.git
npm install
docker-compose up
```

L'application est ensuite accessible à l'adresse suivante : [http://localhost:3000](http://localhost:3000)

## Utilisation

L'application est très simple d'utilisation. Il suffit de se rendre sur la page d'accueil et de cliquer sur le bouton "Créer une alarme". Une fois sur la page de création d'alarme, il suffit de renseigner les champs et de cliquer sur le bouton "Créer".

Une fois l'alarme créée, elle apparaît dans la liste des alarmes sur la page d'accueil. Il est possible de la modifier ou de la supprimer en faisant glisser la ligne de l'alarme vers la gauche, puis en cliquant sur le bouton qui contient l'icône de crayon pour "Modifier" ou celui qui contient l'icône poubelle pour "Supprimer".
Technologies utilisées

L'application est développée en JavaScript avec un backend en Node.js lié à une base de données MySQL.

## Auteur

Clément Favarel
