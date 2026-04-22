# Boilerplates y Templates

Repositorio con plantillas y boilerplates para diversos proyectos.

## Plantillas disponibles

### backend MERN
Boilerplate para backend MERN con:
- JWT + bcrypt (autenticación)
- SoftDelete en cascada (genérico)
- Paginación por cursor
- Docker configurado

### frontend Vite React
Boilerplate para frontend con Vite + React:
- React 18 + Vite 6
- Axios con interceptor de JWT
- AuthContext (autenticación)
- useFetch hook (fetching genérico)
- Docker configurado

## Cómo usar

1. Clone el repositorio
2. Copie la carpeta de la plantilla que necesite
3. Renombre y configure según su proyecto

### Backend
```bash
cd backend MERN
npm install
cp .env.example .env
npm run devstart
```

### Frontend
```bash
cd frontend Vite React/frontend
npm install
cp .env.example .env
npm run dev
```