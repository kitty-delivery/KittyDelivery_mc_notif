<div align="center">
  <h1>KittyDelivery, module Client</h1>
  <p>Microservice de l'architecture KittyDelivery, plateforme de livraison de repas type Uber Eats</p>
  <p>
    <img src="https://img.shields.io/badge/repo-priv%C3%A9-lightgrey?style=flat-square" alt="repo prive" />
  </p>
</div>

<br />

## Table des matieres

- [A propos](#a-propos)
  - [Stack technique](#stack-technique)
- [Demarrage](#demarrage)
  - [Prerequis](#prerequis)
  - [Installation](#installation)
  - [Lancer le projet](#lancer-le-projet)
- [Depots lies](#depots-lies)
- [Contact](#contact)

## A propos

Ce depot correspond au module interne nomme `Client` dans l'architecture microservices de KittyDelivery, du cote des notifications envoyees aux utilisateurs. Il est genere avec `express-generator` (Express + EJS) et sert de base de service pour cette brique du systeme. A ce stade, le code contient uniquement le squelette par defaut (route d'accueil et route `/users` d'exemple), sans logique metier ajoutee.

### Stack technique

<details>
  <summary>Serveur</summary>
  <ul>
    <li><a href="https://nodejs.org/">Node.js</a></li>
    <li><a href="https://expressjs.com/">Express</a></li>
    <li><a href="https://ejs.co/">EJS</a></li>
    <li><a href="https://www.npmjs.com/package/cookie-parser">cookie-parser</a></li>
    <li><a href="https://www.npmjs.com/package/morgan">morgan</a></li>
  </ul>
</details>

## Demarrage

### Prerequis

Node.js et npm doivent etre installes.

### Installation

```bash
npm install
```

### Lancer le projet

```bash
npm start
```

Le serveur demarre par defaut sur le port configure dans `bin/www` (3000 par defaut).

## Depots lies

Ce module fait partie de l'architecture microservices KittyDelivery, decoupee en plusieurs depots :

- [KittyDelivery](https://github.com/BaditSad/KittyDelivery), depot principal du projet
- [KittyDelivery_API](https://github.com/BaditSad/KittyDelivery_API), passerelle API
- [KittyDelivery_mc_user](https://github.com/BaditSad/KittyDelivery_mc_user), gestion des comptes
- [KittyDelivery_mc_restaurant](https://github.com/BaditSad/KittyDelivery_mc_restaurant), gestion des restaurants
- [KittyDelivery_mc_auth](https://github.com/BaditSad/KittyDelivery_mc_auth), authentification
- [KittyDelivery_mc_component](https://github.com/BaditSad/KittyDelivery_mc_component), composants partages
- [KittyDelivery_mc_article](https://github.com/BaditSad/KittyDelivery_mc_article), produits et plats
- [KittyDelivery_mc_log](https://github.com/BaditSad/KittyDelivery_mc_log), logs
- [KittyDelivery_mc_menu](https://github.com/BaditSad/KittyDelivery_mc_menu), menus
- [KittyDelivery_mc_order](https://github.com/BaditSad/KittyDelivery_mc_order), commandes

## Contact

Brieuc Dumortier

[LinkedIn](https://www.linkedin.com/in/dumortier-brieuc/) . [GitHub](https://github.com/BaditSad) . dumortier.contact@gmail.com
