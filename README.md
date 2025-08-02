# edubank

Sistema de Gestión Educativa

## Características principales

- Roles: Administrador, Docente encargado, Docente estándar, Estudiante
- Los administradores y docentes asignan usuario y contraseña al crear usuarios
- Los usuarios pueden subir foto de perfil
- Interfaz personalizada por institución
- CRUD de instituciones, docentes y estudiantes
- Usuario administrador por defecto: **45102910** / **0502000323Aa**

## Estructura del proyecto

```
edubank/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── uploads/
│   ├── app.js
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
├── schema.sql
└── README.md
```

## Instalación rápida

### Backend

```bash
cd backend
npm install
npm run dev
```

### Frontend

```bash
cd frontend
npm install
npm start
```

## Endpoints principales

- POST `/api/login`
- POST `/api/usuarios` (crear usuarios)
- POST `/api/usuarios/:id/foto` (foto de perfil)
- PUT `/api/instituciones/:id/configuracion-visual` (interfaz visual)

---
