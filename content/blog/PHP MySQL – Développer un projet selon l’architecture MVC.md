+++
title = "PHP MySQL – Développer un projet selon l’architecture MVC"
date = "2019-03-06T21:49:21+02:00"
description = "PHP MySQL – Développer un projet selon l’architecture MVC"
tags = ["golang", "programming", "theme", "hugo"]
categories = ["starting"]
author = "Adam"
image = "images/blog/blog-post-7.jpg"
+++
PHP MySQL – Développer un projet selon l’architecture MVC
Qu’est-ce que MVC et pourquoi l’utiliser ?
MVC est un design pattern (un modèle de conception) qui permet d’organiser son code selon trois parties bien précises : Modèle, Vue et Contrôleur. En suivant les directives du modèle MVC, vous saurez quels fichiers créer et quels rôles leur donner :
Modèle : Cette partie gère les données du site. Elle récupère les données dans la base de données (via des requêtes SQL) et les met en forme pour qu’elles puissent être traitées par la partie Contrôleur.
Vue : Cette partie est dédiée à l’affichage sur l’écran. Elle est généralement composée d’un mélange de code HTML et PHP.
Contrôleur : Cette partie contient la portion “intelligente” du code. Elle reçoit les données du visiteur, demande au Modèle de trouver les données correspondantes dans la base de données, analyse les données fournies par le Modèle et décide ce qui doit être affiché par la partie Vue.
