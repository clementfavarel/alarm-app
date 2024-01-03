Alarm app
Description

Alarm app est une application web permettant de créer et de gérer des alarmes.

L'idée m'est venu après avoir passé presque 3 ans à régler mes réveils au jour le jour.

J'ai donc décidé de créer une application qui me permettrait de créer des alarmes et de les gérer facilement, en un clic.

L'application se présente comme suit :

    Une page de présentation (avec un bouton pour se connecter)
    Une page de connexion (avec possibilité de créer un compte)
    Une page création de compte (avec possibilité de se connecter)
    Une page d'accueil avec la liste des alarmes et un bouton pour en créer une nouvelle
    Une page de création d'alarme
    Une page de modification d'alarme (possibilité de supprimer l'alarme)
    Une page tableau de bord avec une analyse des données de l'application (heure de coucher, heure de lever, temps de sommeil, etc.)

Installation

L'application est contenue dans un container Docker. Cela permet de l'installer facilement et de la faire tourner sur n'importe quel système d'exploitation.

Pour installer l'application, il faut tout d'abord installer Docker sur votre machine. Pour cela, rendez-vous sur le site officiel de Docker : https://docs.docker.com/get-docker/

Une fois Docker installé, il faut cloner le repository Github de l'application. Pour cela, ouvrez un terminal et tapez la commande suivante :

git clone https://github.com/clementfavarel/alarm_app.git

Une fois le repository cloné, rendez-vous dans le dossier de l'application et tapez la commande suivante :

cd alarm_app

docker-compose up -d

L'application est maintenant installée et accessible à l'adresse suivante : http://localhost:8000
Utilisation

L'application est très simple d'utilisation. Il suffit de se rendre sur la page d'accueil et de cliquer sur le bouton "Créer une alarme". Une fois sur la page de création d'alarme, il suffit de renseigner les champs et de cliquer sur le bouton "Créer".

Une fois l'alarme créée, elle apparaît dans la liste des alarmes sur la page d'accueil. Il est possible de la modifier ou de la supprimer en faisant glisser la ligne de l'alarme vers la gauche, puis en cliquant sur le bouton qui contient l'icône de crayon pour "Modifier" ou celui qui contient l'icône poubelle pour "Supprimer".
Technologies utilisées

L'application est développée en JavaScript avec un backend en Node.js lié à une base de données Supabase. Elle est également hébergée sur Vercel à l'adresse suivante : https://alarm-app.vercel.app/
Auteur

Clément Favarel
