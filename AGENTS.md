# AGENTS.md

## Scope

Applies to the whole repository unless a more specific `AGENTS.md` exists in a subdirectory.

## Project Context

- Fullstack JavaScript project for learning REST and authentication
- Root source of truth: [STACK.md](./STACK.md)
- Package manager: `pnpm`
- Backend stack: `Node.js`, `Express`, `SQLite`, `Prisma`
- Frontend stack: `React`, `Vite`, `Tailwind`

## Working Rules

- Keep the codebase in JavaScript unless the stack document changes
- Prefer small, understandable changes over premature abstraction
- Keep backend and frontend responsibilities clearly separated
- Use `pnpm` for installs, scripts, and dependency management
- Update `STACK.md` before making important architecture decisions
- Do not remove user changes unless explicitly requested

## File Organization

- `backend/`: API, database access, auth, server logic
- `frontend/`: UI, views, state, and API consumption
- Root: project decisions and shared documentation

## Communication

- Be concise and factual
- Explain assumptions when making them
- Surface risks or missing decisions before implementing them

