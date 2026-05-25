# AGENTS.md

## Scope

Applies to everything inside `backend/`.

## Backend Context

- `Node.js` + `Express`
- Database: `SQLite`
- ORM: `Prisma`
- Package manager: `pnpm`
- Goal: build the API that supports authentication and CRUD for `todos`

## Working Rules

- Keep backend code in JavaScript
- Prefer REST endpoints with clear request and response shapes
- Keep route handlers thin and move logic into dedicated modules when needed
- Treat authentication as part of the API design, not as an afterthought
- Use `pnpm` for scripts, installs, and tooling

## Implementation Expectations

- Separate routes, controllers, services, and data access when the codebase grows
- Keep database schema and migrations aligned with the API contracts
- Validate inputs before touching the database
- Return consistent JSON errors and success payloads

## Important Notes

- If the backend stack changes, update [STACK.md](../STACK.md) first
- If a new pattern is introduced, document it here or in a nearby README

