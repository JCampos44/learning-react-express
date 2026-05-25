# learning-react-express

Proyecto fullstack para aprender autenticación y REST con JavaScript puro.

## Stack

- Backend: `Node.js`, `Express`, `SQLite`, `Prisma`
- Frontend: `React`, `Vite`, `Tailwind`
- Package manager: `pnpm`

La documentación detallada del stack vive en [STACK.md](./STACK.md).

## Requisitos

- Node.js instalado
- `pnpm` instalado

## Instalación

Desde la raíz del proyecto:

```bash
pnpm install
```

## Levantar todos los servicios

Desde la raíz:

```bash
pnpm dev
```

Ese comando ejecuta en paralelo:

- `backend/` con `pnpm run dev`
- `frontend/` con `pnpm run dev`

## Levantar cada servicio por separado

Backend:

```bash
cd backend
pnpm dev
```

Frontend:

```bash
cd frontend
pnpm dev
```

## Endpoints actuales

- Backend healthcheck: `GET /health`

## Estructura

- `backend/`: API, base de datos y autenticación
- `frontend/`: interfaz y consumo de la API
- Raíz: configuración compartida y documentación general

