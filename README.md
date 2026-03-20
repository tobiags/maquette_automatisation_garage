# AutoPost — Plateforme de publication automatisée

> Maquette interactive d'une solution de gestion et publication de contenu 
> sur les réseaux sociaux pour un réseau de garages automobiles.

**[→ Voir la maquette en live](https://autogarage.tobiasagossou.website)**

---

## Contexte

Projet réalisé pour un réseau de 50 garages automobiles souhaitant automatiser 
la publication de leurs annonces véhicules sur Facebook, Instagram et LinkedIn.

Le client avait besoin de visualiser l'interface avant validation interne du projet.

---

## Ce que montre cette maquette

- **Tableau de bord** — suivi des publications en temps réel (publiées, planifiées, erreurs)
- **Création d'annonce** — texte différencié par plateforme, carrousel 2-5 images, sélection des garages
- **Gestion des garages** — 50 comptes, statut de connexion, plateformes actives
- **Portail client** — interface de connexion OAuth que chaque garage utilise une seule fois

---

## Stack technique (solution finale prévue)

- **Back-end** : Python / Django
- **Tâches asynchrones** : Celery + Redis
- **Base de données** : PostgreSQL
- **APIs** : Facebook Graph API, Instagram Graph API, LinkedIn Partner API
- **Hébergement** : VPS Linux via Coolify

---

## Documents du projet

| Document | Description |
|---|---|
| PRD | Product Requirements Document — objectifs, fonctionnalités, métriques |
| Cahier des charges | Spécifications techniques complètes — architecture, APIs, sécurité, chiffrage |

---

