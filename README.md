# test-manager-library-3239137-app

Frontend de **Manager Library** en **React + Vite**.

Consume el contrato de api-contract.md del repositorio docs a través del backend Laravel.

## Stack

| Capa | Tecnología |
|------|------------|
| UI | React 18 |
| Build | Vite 5 |
| Rutas | React Router 6 |
| Idioma UI | Español |

## Requisitos

- Node.js 18+
- npm
- Backend (api) corriendo en http://localhost:8000

## Arranque rápido

1. Instalar dependencias: npm install
2. Copiar entorno: cp .env.example .env
3. Levantar en desarrollo: npm run dev

La app queda en: http://localhost:5173

## Variables de entorno

| Variable | Uso |
|----------|-----|
| VITE_API_BASE_URL | URL base de la API (ej. http://localhost:8000/api/v1) |

## Pantallas previstas (según HUs)

- Login (HU-01)
- Catálogo de libros (HU-03, HU-04)
- Socios (HU-05)
- Registrar préstamo (HU-06)
- Devolver (HU-07)
- Vencidos (HU-09)
- Reporte más prestados (HU-10, solo admin)

## Relación con el spec

| Documento | Cómo se aplica aquí |
|-----------|---------------------|
| api-contract.md | Todas las llamadas HTTP respetan rutas, códigos y cuerpo de error |
| spec.md | Las pantallas cubren las historias de usuario del MVP |
| constitution.md | Mensajes al usuario en español; sin secretos en el frontend |
