# Lab 1

## Objectif du TP

Ce TP vise à mettre en place l'environnement de travail nécessaire à la réalisation des TP et à découvrir l'application qui sera utilisée pour les différents TP.

## Pré-requis

Avoir accès au groupe EI8IT213 de l'organisation GitLab Bordeaux INP.
=> Mail envoyé sur adresse Bordeaux INP pour rejoindre ce groupe

Etre répartis en groupe de 2 personnes pour les TP.

## Création du projet sur GitLab

Afin de pouvoir faire les labs, chaque groupe créera son projet sur GitLab à partir d'un projet existant. Le projet à duppliquer/"forker" est disponible sur GitLab: https://gitlab.com/bordeauxinp/ei8it213/vue-2048

1. Créer un fork du projet en cliquant sur le bouton Fork
    1. Le nom du fork doit être préfixé par les initiales des membres du groupe de TP
    2. Le namespace "bordeauxinp/ei8it213" doit être choisi dans l'URL du projet
    3. Les noms des membres du groupe de TP doivent être indiqués dans la description du projet
    4. Valider
2. Ajouter les 2 membres du groupe projet en Owner du projet

## Installation des logiciels nécessaires

1. Installer [git](https://git-scm.com/book/fr/v2/D%C3%A9marrage-rapide-Installation-de-Git)
2. Installer [vscode](https://code.visualstudio.com/)
3. Installer l'extension vscode [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)
4. Installer [pnpm](https://pnpm.io/installation) => la méthode "standalone script" doit être utilisée pour l'installation
5. Installer la dernière version stable de Node.js (LTS)
    - si pas déjà installée sur la machine
    - en utilisant pnpm via la commande `pnpm env use --global lts`

## Récupérer et configurer le projet en local

1. Cloner le projet précédemment créé
2. Ajouter un nouveau dépôt distant en amont pour récupérer les modifications qui seront apportées sur le répertoire d'origine grâce à la commande 
`git remote add upstream https://gitlab.com/bordeauxinp/ei8it213/vue-2048.git`

> Pour récupérer les dernières modifications du répertoire d'origin il suffit de faire un `git pull upstream`

## Lancer l'application en local

Suivre les instructions contenues dans le readme du projet pour lancer le projet