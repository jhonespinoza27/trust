# JHONOTE 📝

App de notas multiusuario con React + Vite (frontend) y Express + MySQL (backend).

## 🚀 Iniciar

### 1. Backend
```bash
cd backend
npm install
npm run dev
```
El servidor corre en http://localhost:5000

### 2. Frontend
```bash
cd frontend
npm install
npm run dev
```
La app corre en http://localhost:5173

## 📁 Estructura

```
notas/
├── backend/          # Express + mysql2
│   ├── src/
│   │   ├── db.ts     # Conexión MySQL
│   │   ├── index.ts  # Servidor
│   │   └── routes/   # API endpoints
│   └── .env          # Configuración
└── frontend/         # React + Vite
    └── src/
        ├── pages/    # Login, Register, Dashboard
        ├── components/
        └── context/  # Auth
```

## ⚙️ Configuración

Backend `.env`:
```
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=admin
DB_NAME=notas_db
JWT_SECRET=tu-secreto-seguro
```

## ✨ Características

- 🔐 Autenticación con JWT + cookies
- 📝 CRUD completo de notas
- 🔍 Búsqueda en tiempo real
- ⌨️ Ctrl+N para nueva nota
- 🎨 Diseño moderno púrpura/rosa
