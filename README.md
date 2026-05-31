# LabTrack — Sistema de Gestión de Laboratorios

Proyecto integrador desarrollado con **Node.js + Express** en el backend y **HTML/CSS/JS** en el frontend.

## Tecnologías
- Backend: Node.js, Express, MySQL2, JWT, bcryptjs
- Frontend: HTML5, CSS3 (Vanilla), JavaScript (Fetch API)
- Base de datos: MySQL (XAMPP)

## Estructura
```
LabTrack_Proyecto/
├── backend/
│   ├── config/        # Conexión a BD y SQL schema
│   ├── controllers/   # Lógica de negocio
│   ├── middlewares/   # Verificación de token JWT
│   ├── models/        # Consultas SQL
│   ├── routes/        # Rutas de la API
│   └── server.js
└── frontend/
    ├── css/           # Estilos
    ├── js/            # Lógica del cliente
    └── *.html         # Vistas
```

## Instalación
```bash
cd backend
npm install
# Configurar .env con credenciales de MySQL
node server.js
```

## Módulos
- **Autenticación**: Login / Registro con JWT
- **Inventario**: CRUD de equipos del laboratorio
- **Préstamos**: Control de préstamos y devoluciones
