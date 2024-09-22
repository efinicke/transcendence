# Transcendence

## Skills

- **Full-Stack Development** : Développement d'une application web complète, de l'interface utilisateur au backend, assurant une expérience utilisateur fluide.
- **TypeScript** : Améliorer la sécurité, la maintenabilité et la lisibilité du code.
- **NestJS & Vue.js** : Mise en œuvre de frameworks modernes qui permettent une architecture scalable et réactive.
- **OAuth & Security** : Intégration d'une authentification sécurisée via OAuth et mise en place de mesures de sécurité robustes, incluant la protection contre les injections SQL.
- **Real-Time Communication** : Développement de fonctionnalités en temps réel, comme un chat intégré et des jeux multijoueurs dynamiques.
- **Docker & DevOps** : Utilisation de Docker et Docker Compose pour le déploiement simplifié et la gestion efficace des environnements de développement.
- **Database Management** : Conception et gestion de bases de données relationnelles avec PostgreSQL et Prisma pour assurer la persistance des données.
- **Team Collaboration** : Pratique de la collaboration en équipe avec Git, permettant une gestion efficace du code source et une coordination fluide entre les développeurs.


## Project Overview

**Authors** : Ce projet a été réalisé en collaboration avec Tadeo Amigorena, Augustin Estela et Damien Santerre.

**Transcendence** est une plateforme multijoueur innovante qui permet aux utilisateurs de jouer au jeu classique de Pong en ligne. Grâce à une interface intuitive et à des fonctionnalités avancées, le site offre une expérience de jeu engageante et interactive. Les utilisateurs peuvent créer des profils personnalisés, se connecter via un système d'authentification sécurisé, et participer à des jeux en temps réel avec d'autres joueurs : 
- **Backend** : NestJS (Node.js avec TypeScript)
- **Frontend** : Vue.js avec TypeScript
- **Base de données** : PostgreSQL
- **ORM** : Prisma
- **Infrastructure** : Docker (Docker Compose)
- **Authentification** : OAuth 42
- **Gestion des États** : Vuex


## Features

- **Secure Authentication** : Connexion via OAuth 42, avec des options de vérification en deux étapes (2FA) pour une sécurité accrue.
- **User Profile** : Chaque utilisateur peut créer un profil unique avec un nom d'utilisateur distinct et un avatar personnalisé. Ils peuvent également consulter et partager leur historique de matchs.
- **Integrated Chat** : Système de chat robuste permettant la création de canaux publics et privés, ainsi que l'envoi de messages directs entre utilisateurs.
- **Multiplayer Pong Game** : Matchmaking automatique qui associe les joueurs pour des parties de Pong en temps réel, avec des options de personnalisation du jeu.
- **Account Management** : Fonctionnalités pour ajouter des amis, bloquer des utilisateurs indésirables et visualiser le statut en ligne des amis.

## Usage

Pour lancer le projet, suivez les étapes ci-dessous :

1. Cloner et aller dans le repo : 
```bash
   git clone [URL_DU_DEPOT]
   cd [NOM_DU_DEPOT]/projet
```

2. Installer npm et docker-compose

3. Installer les dépendances avec npm :
```bash
    npm install
```

4. Pour jouer en local avec d'autres joueurs configurer la variable DOMAIN dans le .env avec l'adresse IP de votre PC (du réseau local). Dans le cas contraire l'adresse IP de bouclage est définie (localhost 127.0.0.1).

5. Utiliser l'URL suivant pour accéder au site : `http://<adresse_IP>:<port>`. Par exemple, si votre adresse IP définie dans DOMAIN est `10.24.1.3` sachant que le frontend est sur le port `8080`, entrez `http://10.24.1.3:8080` dans le navigateur pour accéder au site. Tous les joueurs connectés sur le même réseau peuvent accéder à cette adresse.
