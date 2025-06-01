# Application de Gestion de Stock - MEAN Stack

Ce projet est une application web développée avec la stack MEAN (MongoDB, Express.js, Angular, Node.js). Elle permet de gérer efficacement un stock de produits, avec des fonctionnalités d’ajout, de suppression, de mise à jour, de consultation, et d’authentification.

## Fonctionnalités principales

- 🔐 Authentification sécurisée via JWT
- 📦 Gestion des produits (CRUD)
- 📊 Suivi des niveaux de stock et mouvements
- 🌐 Application web responsive en Angular
- 🚀 API RESTful avec Express.js et MongoDB

## Structure du projet

```
mean-stock-management/
│
├── backend/                # Serveur Node.js avec Express
│   ├── models/             # Schémas Mongoose (Product, Stock)
│   ├── routes/             # Routes API REST pour les entités
│   ├── middleware/         # Middleware JWT pour la sécurité
│   ├── config/             # Configuration MongoDB
│   └── server.js           # Point d'entrée de l'application backend
│
├── frontend/               # Application Angular (SPA)
│   └── src/app/            # Composants Angular et services API
│
└── README.md               # Ce fichier
```

## Instructions d’installation

1. **Cloner le projet**  
   ```bash
   git clone <lien-du-repo>
   ```

2. **Installation des dépendances backend**  
   ```bash
   cd backend
   npm install
   ```

3. **Lancer le serveur backend**  
   ```bash
   node server.js
   ```

4. **Installation des dépendances frontend**  
   ```bash
   cd ../frontend
   npm install
   ```

5. **Lancer l’application Angular**  
   ```bash
   ng serve
   ```

## Auteurs

Projet réalisé dans le cadre d’un atelier sur le développement MEAN Stack.

