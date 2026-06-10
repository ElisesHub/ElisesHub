 # Hi! 👋

I build **.NET / ASP.NET Core** applications with a focus on clean, layered architecture, REST APIs, authentication, Docker, and SQL / NoSQL databases.

## Featured project — Containerised Multi-Service Account System

An authenticated, containerised account-management application built as a multi-service (three-tier) system, organised with **Clean Architecture** (Domain / Application / Infrastructure / Presentation layers, dependencies pointing inward):

- Razor Pages / MVC frontend
- **Accounts Application API** — application-facing service handling request flow, validation, and coordination
- **Accounts Database API** — dedicated data-access service, separated so it can be reused by other services without duplicating database logic
- MySQL database
- API-key-based service-to-service communication
- Auth0 authentication on the frontend
- Swagger / OpenAPI documentation, health checks, global exception handling, and startup configuration validation
- Full Docker Compose setup, with a separate production repository for **one-command deployment**

See the pinned **Accounts System** repositories below.

## Tech stack

C#, .NET, ASP.NET Core, Razor Pages, MVC, REST APIs, MySQL, Docker, Docker Compose, Auth0, Swagger/OpenAPI. Built with Clean Architecture and DDD tactical patterns (e.g. strongly-typed value objects with validation); actively deepening my Domain-Driven Design.

## Contact

- 📫 LinkedIn: https://www.linkedin.com/in/elise-loi

---

# Bonjour ! 👋

Je développe des applications **.NET / ASP.NET Core**, en mettant l'accent sur une architecture clean et en couches, les API REST, l'authentification, Docker ainsi que les bases de données SQL et NoSQL.

## Projet phare — Système de gestion de comptes multi-services conteneurisé

Une application de gestion de comptes authentifiée et conteneurisée, conçue comme un système multi-services (trois niveaux) et organisée selon les principes de la **Clean Architecture** (couches Domain / Application / Infrastructure / Presentation, dépendances orientées vers l'intérieur) :

- Une interface frontend développée avec Razor Pages / MVC
- **Accounts Application API** — service applicatif gérant le flux des requêtes, la validation et la coordination
- **Accounts Database API** — service d'accès aux données dédié, séparé afin de pouvoir être réutilisé par d'autres services sans dupliquer la logique d'accès à la base de données
- Une base de données MySQL
- Une communication interservices sécurisée par clé API
- Une authentification Auth0 côté frontend
- Documentation Swagger / OpenAPI, health checks, gestion globale des exceptions et validation de la configuration au démarrage
- Un déploiement complet via Docker Compose, avec un dépôt de production distinct permettant un **déploiement en une seule commande**

Consultez ci-dessous les dépôts épinglés du projet **Accounts System**.

## Technologies utilisées

C#, .NET, ASP.NET Core, Razor Pages, MVC, API REST, MySQL, Docker, Docker Compose, Auth0, Swagger/OpenAPI. Conçu selon la Clean Architecture et des patterns tactiques du DDD (par exemple des value objects fortement typés avec validation) ; j'approfondis actuellement le Domain-Driven Design.

## Me contacter

- 📫 LinkedIn : https://www.linkedin.com/in/elise-loi
