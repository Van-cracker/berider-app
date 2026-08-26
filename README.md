# Be'Rider 🛹

[![License: MIT](https://img.shields.io/badge/License-MIT-8A5CF5.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue.svg)](https://www.typescriptlang.org/)

Bienvenue sur [Be'Rider](https://github.com/ArseneLoukanou/berider-app), l'application communautaire et sociale dédiée aux passionnés de glisse urbaine (Roller, Skate, Trottinette, BMX).

---

## 📋 Présentation

Be'Rider permet aux riders de se connecter localement, de découvrir et référencer les meilleurs spots de ride, d'organiser des sessions en temps réel et d'échanger au sein d'une communauté active. L'application intègre également un système de gamification pour récompenser les membres les plus engagés.

---

## 📸 Aperçu de l'Application

> *Les captures d'écran et démos vidéo seront ajoutées au fur et à mesure de la finalisation des maquettes Figma et de l'intégration.*

| Écran Chat | Carte des Spots | Profil & Badges |
| :---: | :---: | :---: |
| *(Capture à venir)* | *(Capture à venir)* | *(Capture à venir)* |

---

## ✨ Fonctionnalités Clés

* **Authentification & Profils :**
  * Inscription, connexion et profil personnalisable (disciplines, niveau, matériel).
* **Carte Interactive des Spots (Spot Finder) :**
  * Géolocalisation des spots, fiches détaillées (revêtement, éclairage, avis).
  * Signalement de sessions en cours en temps réel.
* **Espace Chat & Communauté :**
  * Salons de discussion thématiques par zone/ville.
  * Messagerie privée et widget interactif "Proposer une Session".
* **Fil d'Actualité (Feed) :**
  * Partage de photos et vidéos de tricks avec système de likes et commentaires.
* **Gamification & Badges :**
  * Gain d'expérience (XP), niveaux de progression et déblocage de badges exclusifs.

---

## 📁 Structure du Projet

```text
src/
├── pages/                # Landing, Login, Register, Feed, Chat, Spots, Profile
├── components/
│   ├── ui/               # Field, Button, Badge, Tag... (composants réutilisables)
│   ├── layout/           # Footer, Navbar, Sidebar...
│   └── [feature]/        # spots/SpotCard, chat/MessageBubble, auth/LoginForm
├── context/              # AuthContext, ChatContext
├── data/                 # Mock-data temporaires (mock-spots.ts, mock-channels.ts)
├── types/                # Définitions TypeScript (spot.ts, user.ts, message.ts)
├── theme/                # Tokens centralisés (colors.ts, typography.ts)
└── hooks/                # Custom hooks (useSpots, useChat, useAuth)
```

---

## 🛠 Tech Stack

* **Frontend :** React, TypeScript, Vite, Tailwind CSS
* **Backend :** Laravel / Nest.js *(à venir)*
* **Base de données :** PostgreSQL / MySQL *(à venir)*
* **Design :** Figma / Lunacy

---

## 🚀 Installation & Lancement

1. **Cloner le projet :**
   ```bash
   git clone https://github.com/ArseneLoukanou/berider-app.git
   cd berider-app
   ```

2. **Installer les dépendances :**
   ```bash
   npm install
   ```

3. **Configurer les variables d'environnement :**

   Créez un fichier `.env.local` à la racine du projet en vous basant sur `.env.example` :
   ```bash
   cp .env.example .env.local
   ```

4. **Lancer le serveur de développement :**
   ```bash
   npm run dev
   ```

---

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. Forkez le projet.
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`).
3. Committez vos modifications (`git commit -m 'Add some AmazingFeature'`).
4. Pushez vers la branche (`git push origin feature/AmazingFeature`).
5. Ouvrez une Pull Request.

---

## 📜 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](./LICENSE) pour plus de détails.
