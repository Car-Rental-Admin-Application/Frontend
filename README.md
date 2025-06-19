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

## Interfaces de l'Application
Cette section décrit les différentes interfaces utilisateur de l'application GestionVoiture, en mettant en évidence leurs fonctionnalités et leur rôle.
<br>
  1. Interface d'Authentification 
      
L'interface d'authentification est la première page que les utilisateurs rencontrent. Elle est conçue pour permettre aux utilisateurs de se connecter au système en toute sécurité. Elle présente un design épuré et moderne, intégrant des éléments visuels attrayants.
![image](https://github.com/user-attachments/assets/3190c5e1-e04e-4136-abb9-fea090071046)
Fonctionnalités : <br>
• Champs de saisie sécurisés : L'utilisateur doit entrer son nom d'utilisateur et son mot de passe dans les champs dédiés.<br>
• Option "Mot de passe oublié ?" : Un lien est disponible pour les utilisateurs ayant oublié leur mot de passe, les redirigeant vers un processus de récupération (fonctionnalité à implémenter ou à détailler si existante).<br>
• Bouton de soumission : Un bouton "SUBMIT" permet de valider les informations d'identification et de tenter la connexion.

<b>Design</b> :
L'interface est divisée en deux sections principales : une section visuelle sur la gauche présentant une image pertinente (ici, une voiture de sport), et une section de formulaire sur la droite. Cette disposition améliore l'esthétique et l'expérience utilisateur.

<br> 
       2.Interface du Tableau de Bord (Dashboard). 
<br>
Le tableau de bord est le centre de commande de l'application, offrant une vue d'ensemble rapide et des statistiques clés sur la gestion des véhicules. Il est conçu pour fournir des informations essentielles en un coup d'œil, permettant aux utilisateurs de surveiller l'état général de leur flotte.

![image](https://github.com/user-attachments/assets/e0061275-b0e0-4a38-9e3e-125ead6a74b7)
Fonctionnalités : <br>
Navigation principale : En haut de la page, des liens de navigation permettent d'accéder facilement aux sections "Dashboard", "Cars" (Véhicules) et "Logs" (Journaux).<br>
• Statistiques clés : Des cartes d'information affichent des métriques importantes :<br>
• Total Cars : Le nombre total de véhicules gérés dans le système (ici, 127).<br>
• Total Sold Last Month : Le nombre total de véhicules vendus ou loués le mois précédent (ici, 74).<br>
• Visualisation des données : Un graphique en anneau (donut chart) présente la répartition des véhicules par marque, par exemple, 60% de Toyota et 40% de Chevrolet, offrant une compréhension visuelle rapide de la composition de la flotte.<br>
• Aperçu visuel : Une section dédiée affiche une image représentative d'un véhicule, ajoutant un élément visuel agréable au tableau de bord.<br>
<br>
<b>Design</b> : <br>
L'interface du tableau de bord est organisée en une grille de cartes, chacune dédiée à une information ou une statistique spécifique. Cette disposition modulaire rend l'information facile à digérer et l'interface utilisateur claire et fonctionnelle.

<br> 
       3. Interface de Gestion des Véhicules (Cars)
<br>
L'interface "Cars" est dédiée à la gestion détaillée du parc automobile. Elle permet aux utilisateurs de visualiser, rechercher, filtrer et gérer les informations relatives à chaque véhicule.

![image](https://github.com/user-attachments/assets/e4f4c599-b63b-4566-9ecb-7c7208d93683)

Fonctionnalités :<br>

•Recherche de Véhicules : Un champ de recherche permet de trouver rapidement des véhicules spécifiques en fonction de critères (par exemple, marque, modèle, année).<br>
•Filtrage : Un bouton "Filtrer" suggère la présence d'options de filtrage avancées pour affiner la liste des véhicules affichés.<br>
•Suppression Multiple : Un bouton "Supprimer multiple" indique la possibilité de sélectionner plusieurs véhicules pour une suppression groupée, améliorant l'efficacité de la gestion.<br>
•Ajout de Nouveau Véhicule : Le bouton "Ajouter voiture +" permet d'initier le processus d'ajout d'un nouveau véhicule à la base de données.<br>
•Affichage des Véhicules : Les véhicules sont présentés sous forme de cartes individuelles, chacune affichant des informations clés :<br>
•Image du Véhicule : Une photo représentative du modèle.<br>
•Nom/Modèle : Le nom et l'année du modèle (ex: Toyota Corolla 2023, Mercedes Classe A, BMW Série 3).<br>
•Prix : Le prix du véhicule (ex: 236.000 DH).<br>
•Type de Transmission : Indique si le véhicule est automatique ou manuel.<br>
•Kilométrage : Le kilométrage actuel du véhicule.<br>
<br>
Design :
<br>
L'interface est conçue pour être visuellement attrayante et facile à naviguer. La présentation en grille des cartes de véhicules offre une vue claire et organisée, facilitant la consultation et la gestion des informations.

<br> 
      4. Interface des Journaux (Logs).<br>
<br>
L'interface "Logs" est essentielle pour le suivi et l'audit des activités au sein de l'application. Elle permet de consulter un historique des événements, des actions des utilisateurs ou des modifications apportées aux données.

![image](https://github.com/user-attachments/assets/b6a66dd4-eeb7-409a-84a1-3ea2f51b688b)

Fonctionnalités :<br>

•Affichage des Journaux : Présente une liste chronologique des événements enregistrés par l'application.<br>
•Détails des Événements : Chaque entrée de journal devrait idéalement inclure des informations telles que la date et l'heure de l'événement, l'utilisateur concerné, le type d'action effectuée et les détails pertinents de cette action.<br>
•Recherche et Filtrage : Bien que non visible sur l'image, il est probable que cette interface inclue des fonctionnalités de recherche et de filtrage pour permettre aux utilisateurs de trouver des événements spécifiques (par date, type d'action, utilisateur, etc.).<br>

<br>
<b> Design : </b>
<br>
L'interface des journaux est généralement conçue pour être claire et fonctionnelle, avec une présentation tabulaire ou listée des données pour faciliter la lecture et l'analyse des informations. L'accent est mis sur la lisibilité et l'organisation des données pour un suivi efficace.

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
