# Projet avec YugaByteDB

Application React/TypeScript complète avec backend Node.js/Express intégré à YugaByteDB.

## 🚀 Démarrage rapide

### 1. Démarrer YugaByteDB

```bash
docker-compose up -d
```

### 2. Configurer le backend

```bash
cd server
cp .env.example .env
npm install
npm run init-db
npm run dev
```

### 3. Configurer le frontend

```bash
# Depuis la racine
npm install
npm run dev
```

## 📚 Documentation complète

Consultez [YUGA_BYTEDB_SETUP.md](./YUGA_BYTEDB_SETUP.md) pour le guide d'installation et de configuration détaillé.

## 🛠️ Technologies utilisées

- **Frontend**: React + TypeScript + Vite + Tailwind CSS
- **Backend**: Node.js + Express + TypeScript
- **Base de données**: YugaByteDB (compatible PostgreSQL)
- **Docker**: Pour l'isolation de YugaByteDB

## 📋 Fonctionnalités

- ✅ Gestion complète de projets (CRUD)
- ✅ Interface utilisateur moderne et responsive
- ✅ Recherche et filtrage
- ✅ Validation des données
- ✅ Gestion d'erreurs robuste

## 🔗 URLs

- Frontend: http://localhost:5173
- Backend API: http://localhost:3000/api
- Health Check: http://localhost:3000/health
- YugaByteDB Master UI: http://localhost:7000
- YugaByteDB TServer UI: http://localhost:9000
