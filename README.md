# English

Bilingual (English / French) software engineer with 13+ years building production systems in C# and .NET — REST APIs, relational & document databases, and cloud services on Azure.

---

## Featured projects

### 🔷 Containerised Multi-Service Account System *(C# / .NET)*

An authenticated, containerised account-management application built as a multi-service system, organised with **Clean Architecture** (Domain / Application / Infrastructure / Presentation layers, dependencies pointing inward):

- Razor Pages / MVC frontend, an **Accounts Application API**, and a dedicated **Accounts Database API** — the data-access service is separated so it can be reused by other APIs without duplicating database logic
- API-key-based service-to-service communication; Auth0 authentication; Swagger / OpenAPI documentation
- Full Docker Compose setup, with a separate production repository for **one-command deployment**

**Stack:** C#, ASP.NET Core, Razor Pages, MVC, MySQL, Docker, Auth0. Built with Clean Architecture and DDD tactical patterns (typed value objects with validation).

See the pinned **Accounts System** repositories.

### 🐍 Energy Readings API *(Python / FastAPI)*

A FastAPI service for ingesting and querying hourly energy meter readings, built while broadening my stack into Python and data engineering:

- Organised by feature (**vertical slice**) with **CQS** — command/query separation — at the folder level
- REST endpoints for ingesting (single + bulk), querying, and daily aggregations
- PostgreSQL with **SQLModel**, validated inputs via Pydantic, full **Docker Compose** setup

**Stack:** Python, FastAPI, SQLModel, PostgreSQL, Docker.

See the **energy-readings-api** repository.

---

## Contact

📫 [LinkedIn](https://www.linkedin.com/in/elise-loi)

---

# Français 

Développeuse logicielle bilingue (français / anglais) avec plus de 13 ans d'expérience à concevoir des systèmes en production en C# et .NET — API REST, bases de données relationnelles, services cloud sur Azure.

---

## Projets phares

### 🔷 Système de gestion de comptes multi-services conteneurisé *(C# / .NET)*

Une application de gestion de comptes authentifiée et conteneurisée, conçue comme un système multi-services et organisée selon les principes de la **Clean Architecture** (couches Domain / Application / Infrastructure / Presentation, dépendances orientées vers l'intérieur) :

- Un frontend Razor Pages / MVC, une **Accounts Application API**, et une **Accounts Database API** dédiée — le service d'accès aux données est isolé afin de pouvoir être réutilisé par d'autres API sans dupliquer la logique d'accès à la base
- Communication interservices sécurisée par clé API ; authentification Auth0 ; documentation Swagger / OpenAPI
- Déploiement complet via Docker Compose, avec un dépôt de production distinct permettant un **déploiement en une seule commande**

**Stack :** C#, ASP.NET Core, Razor Pages, MVC, MySQL, Docker, Auth0. Conçu selon la Clean Architecture et avec des patterns tactiques du DDD (value objects fortement typés avec validation).

Voir les dépôts épinglés **Accounts System**.

### 🐍 Energy Readings API *(Python / FastAPI)*

Un service FastAPI pour l'ingestion et l'interrogation de relevés énergétiques horaires, construit en parallèle de l'élargissement de ma stack vers Python et la data engineering :

- Organisé par feature (**vertical slice**), avec une séparation **CQS** — command/query separation — au niveau des dossiers
- Endpoints REST pour l'ingestion (unitaire et en masse), l'interrogation, et les agrégations journalières
- PostgreSQL avec **SQLModel**, validation des entrées via Pydantic, déploiement complet via **Docker Compose**

**Stack :** Python, FastAPI, SQLModel, PostgreSQL, Docker.

Voir le dépôt **energy-readings-api**.

---

## Me contacter

📫 [LinkedIn](https://www.linkedin.com/in/elise-loi)


---

> *"Every system we create today will one day become a legacy system if it is valuable enough to survive"*
>
> — **Martin Kleppmann**, *Designing Data-Intensive Applications*

---

