Projet d'année 2 - Battleship
=============================

📝 Description
===============

Ce projet propose une version jouable en terminal ou en interface graphique (GUI), selon l’option de compilation choisie.

Le jeu inclut un système de gestion de comptes utilisateurs, permettant à chaque joueur de :

- se connecter avec un profil ;
- gérer une liste d'amis ;
- envoyer et recevoir des messages privés ;
- créer ou rejoindre des parties multijoueurs ;
- paramétrer une partie hébergée ;
- consulter le replay de la dernière partie jouée.

Cette application met en œuvre plusieurs aspects : gestion d’interfaces (CLI/GUI), persistance des données, communication entre utilisateurs et logique de jeu multijoueur.

📘 Consignes du projet : 📎 Voir le [PDF](./Consignes.pdf).

Team
====

- Coia Pascal - 000540745
- Lo Cascio Rosario - RosarioLC - 000546687
- Malouch Nikita - Aerynnisss - 000545795
- Mekhiouba Islam - 000538266
- Mertens Bryan - Ayat0ooo - 000522960
- Sanchez Espinosa Carlos - carsanche - 000514371
- Speilers Capucine - Spl4sh9 - 000540555
- Truong Nha - Minti - 000576343
- Veyret Danae - Phantom - 000570552

Requir*e*ments
==============

- C++ : version 12
- SFML : ``sudo apt-get install libsfml-dev`` (pour le programme GUI)

Compilation
===========

- ``make terminal`` : crée le ``server`` ainsi que le ``client_terminal`` ;
- ``make gui`` : crée le ``server`` ainsi que le ``client_gui`` ;
- ``make mrclean`` : à utiliser avant de changer de client (supprime les exécutables, les ``.o`` et les ``.d``).

⚠️ Attention : il n'est pas possible de compiler les deux clients en même temps.

💡 Remarque : ``make clean`` supprime uniquement les fichiers ``.o`` et ``.d``.
