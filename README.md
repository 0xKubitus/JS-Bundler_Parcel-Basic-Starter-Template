<div align="center">

[![THP Badge](https://github.com/0xKubitus/Usefull-Stuff-for-README/blob/main/assets/mkdwn-badges/the-hacking-project.svg
)](https://www.thehackingproject.org/)

# my Parcel (very) Basic Starter Template
  
</div>

Simply clone this repo and run the following commands:
```
  npm i
  npm start
```
That's it!
You're good to go with a local server running your `index.html` page.
(which imports `index.js` and `index.scss` files from `src/` and `style/` folders)

# Qu'est ce que Parcel ?

Parcel se veut être le bundler JS le plus simple à utiliser, car il n'a pas besoin d'un fichier de configuration complexe (et même, il fonctionne généralement très bien sans aucune configuration). De plus, il est extrêmement rapide, car il peut utiliser plusieurs "threads" (plusieurs cœurs de votre CPU) à la fois, et a un système de cache très bien géré.

Toujours dans l'esprit de faciliter la vie du développeur, il automatise beaucoup de choses, et notamment l'ajout de dépendances dans le projet : plutôt que d'avoir à arrêter le bundler, installer la dépendance (avec npm ou yarn), puis relancer le bundler avant de pouvoir utiliser cette dépendance, Parcel va automatiquement l'ajouter et l'installer, puis se relancer tout seul, dès le moment où il détecte l'utilisation de cette nouvelle dépendance dans le code.

Parcel est basé sur ce qu'il appelle des "ressources", c'est-à-dire les fichiers JS, HTML, CSS, PNG, etc. Chaque ressource a son "parser" (un script qui décrit comment gérer la ressource). Il existe beaucoup de parsers, pour la plupart des ressources utilisées dans le web, dont la liste de base est visible dans ce fichier. Mais il est bien sûr possible d'utiliser d'autres parsers créés par la communauté.

Sa <a href="https://fr.parceljs.org/getting_started.html">documentation</a> (en Français, si si !) est très bien faite avec plein d'exemples.

Il déclenche un petit serveur à l'adresse http://localhost:1234 qui va nous servir notre fichier HTML ainsi que toutes les ressources associées (JS, CSS) compilées en bundle.
