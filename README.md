# Meani

Le project a été généré avec [Angular CLI](https://github.com/angular/angular-cli) version 13.3.6.

## Pré-installation

>1. Télécharger et installer [Nodejs](https://nodejs.org/fr/) version 16.15.0 . (Inclus NPM - node package manager)

*Node.js® est un environnement d’exécution JavaScript construit sur le moteur JavaScript V8 de Chrome.*

>2. Télécharger et installer [git](https://git-scm.com/)

*Git est un système de contrôle de version distribué gratuit et open source conçu pour tout gérer, des petits aux très grands projets, avec rapidité et efficacité.*

>3. Installer `Angular CLI`.

<code>$ npm install -g @angular/cli</code>

***

## Initialisation du projet ##

>1. Initialisation de l'application.

<code>$ ng new *\<nom du projet\>* --routing </code>

>2. Installer Ng-Bootstrap

<code>$ ng add @ng-bootstrap/ng-bootstrap</code>

***

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

*Utiliser [Jest](https://jestjs.io/) à la place de Karma*
1. Suppression de Karma et de sa configuration.
   
>><code>$ ng add @briebug/jest-schematic</code>

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
