# STACK

Proyecto fullstack para aprender autenticación y REST con JavaScript puro.

## Objetivo

Construir una app simple de `todo` con:

- `backend/`: API REST con `Express`
- `frontend/`: interfaz con `React`
- Comunicación entre ambos mediante `fetch` y JSON
- Flujo de autenticación básico para entender sesión, tokens o cookies

## Stack Base

- Lenguaje: JavaScript
- Gestor de paquetes: `pnpm`
- Backend: Node.js + Express + `SQLite` + `Prisma`
- Frontend: React + `Tailwind` via `Vite`
- API: REST
- Transporte: HTTP + JSON
- Autenticación: por definir en etapas, priorizando aprendizaje del flujo completo

## Estructura Esperada

- `backend/`: servidor, rutas, controladores, middleware, lógica de acceso a datos
- `frontend/`: componentes, vistas, cliente HTTP, estado de UI y auth
- Raíz: documentación, decisiones de arquitectura y convenciones del proyecto

## Reglas De Trabajo

- Mantener el proyecto en JavaScript, sin TypeScript por ahora
- Usar `pnpm` en `backend/` y `frontend/` para instalación, scripts y dependencias
- Usar `SQLite` como base de datos en `backend/` y `Prisma` como ORM
- Separar claramente responsabilidades entre frontend y backend
- Diseñar la API pensando en consumo desde React
- Priorizar código simple y entendible sobre abstracción prematura
- Documentar decisiones importantes aquí antes de implementarlas

## Flujo Que Queremos Entender

1. Registro o inicio de sesión de usuario
2. Persistencia de credenciales o sesión
3. Consulta de datos protegidos desde React
4. Creación, edición y eliminación de `todos`
5. Manejo de errores, expiración de sesión y estados de carga

## Próximos Pasos

- Definir dependencias iniciales de `backend/` y `frontend/`
- Elegir estrategia de auth inicial: cookies con sesión o JWT
- Diseñar contratos REST para `auth` y `todos`
- Crear el esqueleto de carpetas y scripts de desarrollo
