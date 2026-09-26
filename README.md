<div align="center">
  <img src=".github/assets/banner.png" alt="KittyDelivery Notification Service banner" width="100%" />

  <h1>KittyDelivery, Notification Service</h1>

  <p>Microservice of the KittyDelivery architecture, an Uber Eats style food delivery platform.</p>

  <p>
    <img src="https://img.shields.io/github/last-commit/kitty-delivery/KittyDelivery_mc_notif" alt="last update" />
    <img src="https://img.shields.io/badge/status-student%20project-lightgrey" alt="status" />
  </p>
</div>

<br />

## :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Tech Stack](#space_invader-tech-stack)
- [Getting Started](#toolbox-getting-started)
  * [Prerequisites](#bangbang-prerequisites)
  * [Installation](#gear-installation)
  * [Run the project](#running-run-the-project)
- [Related Repositories](#link-related-repositories)
- [Contact](#handshake-contact)

## :star2: About the Project

This repository corresponds to the internal module named `Client` in the KittyDelivery microservices architecture, on the side of notifications sent to users. It is generated with `express-generator` (Express + EJS) and serves as a service base for this part of the system. At this stage, the code only contains the default skeleton (home route and sample `/users` route), without added business logic.

### :space_invader: Tech Stack

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://nodejs.org/">Node.js</a></li>
    <li><a href="https://expressjs.com/">Express</a></li>
    <li><a href="https://ejs.co/">EJS</a></li>
    <li><a href="https://www.npmjs.com/package/cookie-parser">cookie-parser</a></li>
    <li><a href="https://www.npmjs.com/package/morgan">morgan</a></li>
  </ul>
</details>

## :toolbox: Getting Started

### :bangbang: Prerequisites

Node.js and npm must be installed.

### :gear: Installation

```bash
npm install
```

### :running: Run the project

```bash
npm start
```

The server starts by default on the port configured in `bin/www` (3000 by default).

## :link: Related Repositories

This module is part of the KittyDelivery microservices architecture, split across several repositories:

- [KittyDelivery](https://github.com/kitty-delivery/KittyDelivery), main project repository
- [KittyDelivery_core](https://github.com/kitty-delivery/KittyDelivery_core), architecture hub
- [KittyDelivery_API](https://github.com/kitty-delivery/KittyDelivery_API), API gateway
- [KittyDelivery_mc_user](https://github.com/kitty-delivery/KittyDelivery_mc_user), user accounts
- [KittyDelivery_mc_restaurant](https://github.com/kitty-delivery/KittyDelivery_mc_restaurant), restaurant management
- [KittyDelivery_mc_auth](https://github.com/kitty-delivery/KittyDelivery_mc_auth), authentication
- [KittyDelivery_mc_component](https://github.com/kitty-delivery/KittyDelivery_mc_component), shared components
- [KittyDelivery_mc_article](https://github.com/kitty-delivery/KittyDelivery_mc_article), products and dishes
- [KittyDelivery_mc_log](https://github.com/kitty-delivery/KittyDelivery_mc_log), logs
- [KittyDelivery_mc_menu](https://github.com/kitty-delivery/KittyDelivery_mc_menu), menus
- [KittyDelivery_mc_order](https://github.com/kitty-delivery/KittyDelivery_mc_order), orders

## :handshake: Contact

Brieuc Dumortier, [LinkedIn](https://www.linkedin.com/in/dumortier-brieuc/), [GitHub](https://github.com/BaditSad), dumortier.contact@gmail.com
