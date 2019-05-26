---
title: "Comment mettre à jour WordPress"
date: 201-03-11T14:51:12+06:00
author: Adam
image: images/blog/blog-post-8.jpg
description : "Comment mettre à jour WordPress ?"
---

Comment mettre à jour WordPress ?
Pour mettre à jour WordPress, il existe 2 méthodes différentes :
1. La plus simple et la plus rapide : la mise à jour automatique
2. Quand la mise à jour automatique ne fonctionne pas : la mise à jour manuelle
La mise à jour automatique de WordPress
Une mise à jour automatique de WordPress nécessite :
A minima une version PHP 5.2.4 pour la branche 4 de WordPress.
Les bonnes permissions pour permettre l’écriture des fichiers. (voir le Codex WordPress)
Pour mette à jour WordPress automatiquement, il vous suffit de :
1. Vérifier les pré-requis techniques (version de PHP et droits en écriture).
2. Réaliser une sauvegarde de votre base de données et de vos fichiers (pour pouvoir revenir en arrière).
3. Désactiver toutes les extensions actives.
4. Lancer la mise à jour : Tableau de bord > Mises à jour > Mettre à jour automatiquement.

Mettre à jour WordPress manuellement
Quand le mise à jour automatique ne fonctionne pas ou pour revenir à une version antérieure de WordPress, vous n’aurez pas d’autres choix que la mise à jour manuelle.
La mise à jour manuelle consiste à remplacer par le biais d’un client FTP (FileZilla) ou d’un accès SSH tous les fichiers décompressés de la dernière version de WordPress (à l’exception du dossier WP-content et du fichier WP-config.php qui ne doivent pas être écrasés).


COMME POUR LA MISE À JOUR AUTOMATIQUE, VOUS DEVREZ :
1. Vérifier que votre hébergeur dispose des prérequis et peut accueillir cette mise à jour (principalement les versions PHP & MySQL demandées)
2. Faire une sauvegarde de tous vos fichiers ET ne pas oublier de sauvegarder votre base de données.
3. Désactiver les extensions, c’est recommandé car toutes les extensions ne sont pas forcément à jour et peuvent donc « planter » l’ensemble de la mise à jour. 
