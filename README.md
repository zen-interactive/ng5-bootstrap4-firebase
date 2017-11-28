# Ng5Bootstrap4Firebase

Projet généré avec Angular CLI version 1.5.4.

## Packages supplémentaires

- "@ng-bootstrap/ng-bootstrap": "^1.0.0-beta.5"
- "angularfire2": "^5.0.0-rc.4"
- "bootstrap": "next"
- "firebase": "^4.6.2"

## Informations

Au moment de la création du framework angular ajouter des flags :

> ng new nomdossier --style=scss --routing

Pour que bootstrap fonctionne il faut ajouter la librairie de cette façon :

> npm i -S bootstrap@next

Pour construire le build

> npm run build ou ng build

Ajout du style Bootstrap

> dans le fichier styles.css à la racine du projet

Configurer Firebase

> ajout dans environment et environment.prod la config de connexion

Modification de app.module.ts

> import de Firebase et NgbModule de Bootstrap

