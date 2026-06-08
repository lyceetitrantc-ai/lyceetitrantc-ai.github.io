---
title: Stage internationale
subtitle: Projet Console
layout: product
image: https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcROIw36XNBclcO_o2kyhScPkyj4jvuqpNpqKA&s
robots: noindex 
---


Présentation du projet

Dans le cadre d'un projet réalisé lors d'une mobilité internationale à l'Université des Sciences Appliquées de South Westphalia, j'ai participé à la conception et à la fabrication d'une mini-console de jeu capable d'exécuter le célèbre jeu Snake.

Ce projet avait pour objectif de combiner plusieurs domaines techniques : l'électronique, la programmation embarquée, le prototypage et l'impression 3D. Réalisé en binôme, il nous a permis de suivre l'ensemble des étapes de développement d'un système électronique complet, depuis les premiers tests jusqu'à l'assemblage final du produit.

Objectifs

L'objectif principal était de concevoir une console autonome capable d'afficher et de faire fonctionner le jeu Snake sur une matrice LED RGB de 64 × 32 pixels.

Pour cela, nous devions :

Contrôler une matrice LED RGB.
Utiliser une carte Raspberry Pi Pico 2 comme microcontrôleur principal.
Concevoir un système de commandes à l'aide de boutons directionnels.
Programmer le jeu Snake en langage C.
Réaliser les connexions électroniques nécessaires.
Concevoir et imprimer un boîtier en 3D.
Assembler l'ensemble des composants dans un prototype fonctionnel.
Technologies et matériels utilisés
Raspberry Pi Pico 2
Matrice LED RGB 64 × 32 pixels
Arduino IDE
Thonny
Langage C
Bibliothèque Adafruit Protomatter
Plaque de prototypage en cuivre
Fer à souder
Imprimante 3D
Réalisation du projet

La première étape a consisté à prendre en main la carte Raspberry Pi Pico 2 à travers plusieurs programmes de test. Nous avons notamment réalisé des essais de pilotage de LED ainsi que la lecture de l'état de boutons afin de comprendre le fonctionnement des entrées/sorties du microcontrôleur.

Une fois ces bases maîtrisées, nous avons préparé la partie électronique. Les boutons de contrôle ont été soudés sur une plaque de cuivre spécialement modifiée afin d'éviter tout risque de court-circuit. Les connexions entre les boutons, la matrice LED et la carte Raspberry Pi ont ensuite été réalisées manuellement.

Nous avons ensuite travaillé sur la programmation du jeu Snake. Le programme a été compilé et transféré sur la carte à l'aide de l'environnement Arduino IDE. Plusieurs adaptations ont été nécessaires afin de rendre le code compatible avec notre configuration matérielle et notre écran LED.

Durant le développement, nous avons rencontré différents problèmes techniques. Le plus important concernait l'affichage incomplet de la matrice LED. Après plusieurs jours de recherche et de tests, nous avons identifié un court-circuit minuscule sur la plaque électronique. La correction de ce défaut a permis de rétablir le fonctionnement normal de la console.

En parallèle, nous avons conçu un boîtier à l'aide d'un logiciel de modélisation 3D puis imprimé les différentes pièces grâce à une imprimante 3D. Ce boîtier avait pour rôle de protéger les composants électroniques tout en offrant une utilisation confortable.

Enfin, nous avons procédé à l'assemblage final de tous les éléments : écran, boutons, carte Raspberry Pi et câblage. Plusieurs séries de tests ont permis de valider le bon fonctionnement de la console.

Résultat final

Le projet a abouti à la création d'un prototype fonctionnel capable de lancer automatiquement le jeu Snake au démarrage. Les déplacements du serpent sont contrôlés à l'aide des boutons directionnels et l'affichage est réalisé en temps réel sur la matrice LED RGB.

Cette réalisation m'a permis d'acquérir des compétences concrètes en :

Électronique embarquée
Soudure et câblage
Programmation en langage C
Débogage matériel et logiciel
Utilisation d'un microcontrôleur
Conception et impression 3D
Travail en équipe et gestion de projet technique
Conclusion

Ce projet représente une expérience complète de conception d'un système embarqué. Il m'a permis de mettre en pratique des connaissances en électronique, programmation et fabrication numérique tout en développant mes capacités de résolution de problèmes. La réalisation de cette console Snake constitue un excellent exemple de projet mêlant matériel et logiciel dans un environnement proche des conditions réelles de développement industriel.