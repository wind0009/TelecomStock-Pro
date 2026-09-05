# TelecomStock Pro

Logiciel de gestion de stock pour télécoms vendant téléphones et accessoires numériques.

## 🚀 Installation

1. Installez Node.js depuis https://nodejs.org
2. Ouvrez un terminal dans le dossier du projet
3. Exécutez : `npm install`
4. Pour lancer en mode développement : `npm start`
5. Pour créer l'exécutable : `npm run build`

## 🔐 Identifiants par défaut

- **Utilisateur** : admin
- **Mot de passe** : admin123

## 📁 Structure du projet

```
TelecomStock-Pro/
├── app/                    # Fichiers de l'application
│   ├── main.js            # Processus principal Electron
│   ├── preload.js         # Bridge Electron
│   ├── server.js          # Serveur Express + API
│   ├── index.html         # Interface utilisateur
│   ├── package.json       # Dépendances
│   └── node_modules/      # Modules Node.js
├── build/                 # Exécutable Windows généré
└── package.json           # Configuration du projet
```

## 📋 Fonctionnalités

- ✅ **Dashboard** : KPIs temps réel, dernières ventes, alertes stock bas
- ✅ **Produits** : CRUD complet, suivi IMEI, catégories, alertes stock
- ✅ **Stock** : Entrées/sorties, historique mouvements, ajustements
- ✅ **Ventes** : Nouvelle vente, historique, impression ticket, envoi WhatsApp
- ✅ **Crédits** : Suivi des dettes clients, paiements partiels
- ✅ **Clients** : Fiche client, historique achats
- ✅ **Fournisseurs** : Liste, produits fournis
- ✅ **Rapports** : Bénéfices par produit
- ✅ **Paramètres** : Configuration du magasin

## 🛠️ Stack technique

- **Backend** : Node.js + Express
- **Frontend** : HTML/CSS/JS vanilla
- **Desktop** : Electron
- **Base de données** : JSON (fichier local)
- **Sécurité** : bcrypt, helmet

## 📝 Licence

© 2026 TelecomStock Pro — Tous droits réservés
