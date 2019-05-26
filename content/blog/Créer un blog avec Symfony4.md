---
title: "Créer un blog avec Symfony4"
date: 2019-04-12T14:51:14+06:00
author: Mamadou
image: images/blog/blog-post-2.jpg
description : "Créer un blog avec Symfony4 "
---

Créer un blog avec Symfony4 
Symfony 4 est la version du framework Symfony qui a apporté de changements majeures.
Dans ce tutoriel nous allons apprendre à faire un blog avec un système de commentaire pour les articles et un espace d’administration.
Si c’est votre première fois de faire du Symfony, je vous suggère de lire l'article sur l'Introduction de Symfony 4 avant de commencer.
Sinon, nous allons commencer tout de suite.

Installation
Avant de commencer, il nous faut d’abord créer et configurer notre projet Symfony.
Symfony utilise Composer pour la gestion des dépendances, assurez vous donc d’avoir Composer installer sur votre machine, il faut aussi vous assurez que la commande composer est disponible en l’ajoutant au PATH (vous pouvez suivre le tutoriel d'introduction sur Composer).
Maintenant installons symfony, placez vous dans le répertoire dans le quel vous voulez créer votre projet et entrez cette ligne de commande:

Configuration de l’environnement
L’une des grandes nouveautés de la version 4 de Symfony est le fichier .env qui se trouve à la racine, ce fichier contient les configurations de notre application comme les informations sur la base de données, l'environnement dans le quel on travail (dev ou prod). Ouvrons le donc:

Les routes de notre application
Nous allons maintenant définir les routes de notre application. Nous allons pour cela utiliser le fichier config/routes.yaml. Je préfère utiliser ce fichier pour définir les routes de mon application, mais il faut savoir qu’il y a d’autres méthodes qui existent comme les annotationsou encore dans un fichier xml.
Avant de définir les routes dans le ficher routes.yaml, énumérons d’abord les routes dont on pense notre application a besoin.

L’accueil: c’est la rentrée de notre application et nous allons en profiter pour afficher la liste de nos articles
L’ajout d’un article
La lecture d’un article: cette page va nous permettre d’afficher un article quand on clique dessus
La modification d’un article
La suppression d’un article
Les contrôleurs
Pour la petite définition, le contrôleur est juste une méthode qui va nous permettre de retourner une réponse. En gros le contrôleur reçois une requête Request et renvoie une réponse Response.
Pour créer le contrôleur, nous allons utiliser la ligne de commande, la fameuse ligne de commande de Symfony....Suite:prochain tuto

