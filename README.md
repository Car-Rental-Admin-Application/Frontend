# GestionVoiture - Application Frontend

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.13.

## Description

GestionVoiture est une application frontend développée avec Angular, conçue pour
la gestion de véhicules. Elle offre une interface utilisateur intuitive pour interagir avec un
système de gestion de flotte ou de location de voitures. Ce projet met en œuvre les
meilleures pratiques de développement frontend avec Angular et utilise Angular
Material pour une expérience utilisateur moderne et réactive

## Technologies Utilisées

Ce projet est construit avec les technologies et bibliothèques suivantes :
- Angular (version 19.2.0) : Le framework principal pour la construction de
l'application web.
- Angular Material : Une bibliothèque de composants UI pour Angular qui
implémente Material Design.
- TypeScript : Un sur-ensemble de JavaScript qui ajoute le typage statique.
- RxJS : Une bibliothèque pour la programmation réactive utilisant des Observables,
facilitant la gestion des événements asynchrones.
- Zone.js : Une bibliothèque qui fournit un contexte d'exécution persistant à travers
les tâches asynchrones.

## Fonctionnalités

L'application GestionVoiture est conçue pour fournir les fonctionnalités clés
suivantes (basées sur la structure des modules) :
# Authentification des Utilisateurs : 
Permet aux utilisateurs de se connecter à l'application via une page dédiée.
# Tableau de Bord (Dashboard) : 
Offre une vue d'ensemble des informations importantes et des statistiques relatives à la gestion des véhicules.
# Gestion des Véhicules (Cars) : 
Module complet pour l'ajout, la modification, la suppression et la consultation des détails des véhicules.
# Page d'Accueil (Home) : 
La page d'atterrissage de l'application.
# Journaux d'Activités (Logs) : 
Permet de suivre les différentes opérations et événements au sein de l'application.

## Installation

Pour installer et exécuter ce projet en local, suivez les étapes ci-dessous :

Prérequis
Assurez-vous d'avoir les éléments suivants installés sur votre machine :
- Node.js (version 18.x ou supérieure recommandée)
- npm (généralement inclus avec Node.js)
- Angular CLI : Installez-le globalement en exécutant la commande suivante :

```bash
npm install -g @angular/cli
```
## Utilisation
Pour démarrer l'application en mode développement, exécutez la commande suivante :

```bash
ng serve
```
==> L'application sera accessible à l'adresse http://localhost:4200/ dans votre
navigateur. Les modifications apportées au code seront automatiquement rechargées.

## Structure du Projet
Voici une vue simplifiée de la structure des dossiers clés du projet :

<pre>
GestionVoiture/
├── src/
│   ├── app/
│   │   ├── app.component.ts
│   │   ├── app.component.html
│   │   ├── app.component.css
│   │   ├── app.config.ts
│   │   ├── app.routes.ts
│   │   └── pages/
│   │       ├── cars/
│   │       ├── dashboard/
│   │       ├── home/
│   │       ├── login/
│   │       └── logs/
│   ├── assets/
│   ├── index.html
│   ├── main.ts
│   └── styles.css
├── angular.json
├── package.json
├── package-lock.json
├── README.md
├── tsconfig.app.json
├── tsconfig.json
└── tsconfig.spec.json
</pre>

+ src/ : Contient le code source de l'application.
+ src/app/ : Contient les modules et composants Angular.
+ src/app/pages/ : Organise les différentes vues/pages de l'application.
+ angular.json : Fichier de configuration pour Angular CLI.
+ package.json : Liste les dépendances du projet et les scripts de construction.
## Licence
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.
