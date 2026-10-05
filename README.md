# Projet CampusLink

Un portail digital permettant aux utilisateur(Etudiants, formateurs, equipe technique) de consulter les salles, suivre les équipements et signaler les incidents en ligne via une interface web.


## Fonctionnalités 


-  **Tableau de bord**: permet de voir l'ensemble du campus
- **Salles**: listes des salles disponibles ou indisponibles
- **equipements**: liste de tous les equipements dans les salles fonctionnelles ou pas
- **incident**: liste tous les incidents resolus, encours ou non resolus
- **declarer un incident** : formulaire permettant aux utilisateur de signaler l'equipe technique de l'ensemble des incidents

## Technologies utilisées

- **HTML5**
- **CSS3 (flexbox, grid, mobile first)**

## Structure du projet

```
campusLink/
|____index.html
|____salles.html
|____incident.html
|____equipements.html
|____declarer-incident.html
|____README.md
|____css/
|     |__style.css
|_____images/

```

## Lancer le projet

Le projet demarre avec le fichier **index.html** pour acceder a la page d'accueille


## Choix du conception

- **Organisation du css en 4 section**:(Reglage de base, structure commune, les composants et resposive)
- **les classes de statut réutilisables (vert, orange, rouge)**
- **Flexbox pour le menu**
- **Grid pour les cartes et la galerie**
- **le responsive (media query)**
- *l'accessibilité (aria-current, labels reliés aux champs, couleurs lisibles)**

## Ameliorations

Avec les temps des amelioration seront possible telque:
- **Creation fonction en plus**: connexion utilisateur ou Techniciens
- **Chiffres de l'acceuil**: amelioration pour ne plus ecrire a la mains.
- **Formulaire** redirection vers une base de donnée une fois le formulaire remplie

## Auteurs

Le travaille a été effectuer par 4 personne
- **Jordan NGANONGO**
- **christ TIBE**
- **Alexandre**
- **Jules**
