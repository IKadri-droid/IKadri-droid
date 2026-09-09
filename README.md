<div align="center">

  <h1>IKadri-droid</h1>

  <p><strong>Développement Full-Stack & Cybersécurité — OSINT</strong></p>
  <p>Bachelor Informatique (B1, 2025-2026) · Web · Mobile · Bots · Sécurité applicative</p>

</div>

---

## À propos

En formation Bachelor Informatique, je construis des projets full-stack (web, mobile, bots) tout en approfondissant en parallèle la **cybersécurité et l'OSINT** — veille, écriture de write-ups CTF, et un outil d'auto-audit de vie privée développé de zéro.

Ce qui m'intéresse : comprendre une stack de bout en bout — de l'interface à la base de données — et appliquer une vraie rigueur sécurité (secrets hors du code, requêtes préparées, dépendances auditées) même sur des projets étudiants.

## Compétences

**Langages**

<img src="https://skillicons.dev/icons?i=ts,js,py,go,java,html,css" />

**Frontend & Mobile**

<img src="https://skillicons.dev/icons?i=react,vite,tailwind" />

React Native (Expo) · NativeWind

**Backend & Données**

<img src="https://skillicons.dev/icons?i=nodejs,discordjs,prisma,postgres,sqlite,supabase" />

**Outils & DevOps**

<img src="https://skillicons.dev/icons?i=docker,git,githubactions,maven,figma" />

**Cybersécurité & OSINT**

<img src="https://skillicons.dev/icons?i=linux" />

OSINT (Maigret, WhatsMyName, h8mail) · Tor / dark web · scan de secrets (gitleaks, trufflehog) · cryptographie appliquée · write-ups CTF

## Projets

### 🔎 Where My Informations — outil d'auto-audit OSINT

Outil personnel qui découvre où un email, un pseudo ou un nom apparaissent sur le web (et le dark web), puis aide à faire supprimer ce qui doit l'être.

- **Stack** : Python 3.10+, `http.server` (aucun framework), HTML/CSS/JS vanilla pour l'interface locale
- **OSINT** : scan email (188+ sites, MailAccess, h8mail), scan pseudo (Maigret, WhatsMyName, détection par IA), recherche par nom sur les data brokers
- **Dark web** : recherche via Tor (16+ moteurs .onion), enquête pilotée par IA — verrous de consentement éthique sur les fonctions sensibles
- **Sécurité** : scan de secrets sur ses propres dépôts (gitleaks/trufflehog), chiffrement local des exports, tout reste en local
- Suite de tests (pytest) + CI GitHub Actions · Licence AGPL-3.0

🔒 *Dépôt privé*

### 👑 Kings of Villam — bot Discord RPG

Bot Discord RPG complet avec exploration 2D en temps réel, combats, économie joueur-à-joueur, guildes, PvP classé et assistant IA.

- **Stack** : TypeScript · discord.js v14 · Sapphire · Prisma ORM · PostgreSQL (Supabase/Neon) · IA via Groq (LLaMA)
- 38 commandes slash, 16 modèles de base de données, architecture modulaire par fonctionnalité

[Code source](https://github.com/IKadri-droid/Bot-discord-JS)

### 🥗 Croc ta diète — application mobile de suivi nutritionnel

Application mobile complète de suivi alimentaire, du prototypage à la production.

- **Mobile** : React Native (Expo) · NativeWind (Tailwind) · TypeScript
- **Backend** : Go en architecture propre (`cmd` / `internal` / `pkg`), conteneurisé avec Docker
- Prototype Figma et supports de présentation inclus dans le dépôt

🔒 *Dépôt privé*

### ⚔️ TaskQuest — gestionnaire de tâches gamifié

Application de bureau Java qui transforme une to-do list en quête RPG (XP, niveaux, titres, succès).

- **Stack** : Java 17 · JavaFX · SQLite (JDBC, requêtes préparées) · Maven · JUnit 5
- Architecture MVC + repository, gestion d'exceptions métier dédiées
- Projet universitaire — Bachelor Informatique B1

🔒 *Dépôt privé*

### 🎵 Groupie Tracker — projet école

Application web affichant des données d'artistes/concerts via une API, réalisée en binôme.

- **Backend** : Go · **Frontend** : Vite/TypeScript

🔒 *Dépôts privés*

### 🏰 Royaume Pixel — Puissance 4

Jeu de Puissance 4 en ligne, interface pixel art médiévale, parties en temps réel.

- **Stack** : Go · WebSocket · HTML/CSS
- Système de thèmes persistants (5 décors), détection de victoire/match nul automatique

🔒 *Dépôt privé*

### 🎙️ SpeakWritter — dictée vocale locale

Bloc-notes à dictée vocale qui tourne entièrement en local dans le navigateur (Web Speech API), sans compte ni envoi de données.

- **Stack** : HTML/CSS/JS vanilla · serveur local Python (stdlib uniquement)
- Ponctuation vocale, commandes d'édition à la voix, dictionnaire technique et personnel

[Code source](https://github.com/IKadri-droid/Speakwriter)

### 💼 Portfolio

Site portfolio personnel.

- **Stack** : React 19 · Vite · Tailwind CSS

[Code source](https://github.com/IKadri-droid/Portfolio-ilyace)

## En ce moment

- Formation **Bachelor Informatique** (B1, 2025-2026)
- Approfondissement **OSINT & cybersécurité** (CTF, sécurisation d'outils personnels)
- Projets full-stack persos en parallèle des projets d'école

---

<div align="center">
Ouvert aux échanges sur le développement full-stack et la cybersécurité.
</div>
