# TelecomStock Pro

Logiciel de gestion de stock pour télécoms - Version desktop (Electron) et Mobile (PWA)

## 🚀 Démarrage rapide

```bash
# Cloner le repo
git clone https://github.com/wind0009/TelecomStock-Pro.git
cd TelecomStock-Pro

# Installer les dépendances
npm install

# Lancer en mode développement
npm run dev

# Construire l'application Windows
npm run build
```

## 📱 Version Mobile

Ouvrez `mobile/index.html` dans un navigateur ou déployez-le sur Netlify.

## 📁 Structure

```
src/
├── main.js          # Processus principal Electron
├── preload.js       # Bridge Electron <-> Renderer
├── server.js        # Serveur Express (API + DB)
├── index.html       # Interface utilisateur
├── db/              # Base de données SQLite
├── routes/          # Routes API
└── styles.css       # Styles

mobile/
└── index.html       # Application mobile PWA
```

## 🔐 Accès

- **Login** : admin / admin123
- **PIN mobile** : 1234

## 🛠️ Technologies

- Electron (app desktop)
- Express.js (serveur local)
- SQLite (base de données)
- HTML/CSS/JS (interface)

## 📄 Licence

Propriété de Windson - Burkina Faso
