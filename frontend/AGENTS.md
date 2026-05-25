# AGENTS.md

## Scope

Applies to everything inside `frontend/`.

## Frontend Context

- `React` application built with `Vite`
- Styling with `Tailwind`
- Package manager: `pnpm`
- Goal: consume the backend API and support auth plus todo workflows

## Working Rules

- Keep frontend code in JavaScript
- Prefer simple, reusable UI components
- Build around the API contracts defined by the backend
- Keep state handling predictable and localized
- Use `pnpm` for scripts, installs, and tooling

## Implementation Expectations

- Keep the app empty until features are intentionally added
- Use Tailwind for styling instead of adding another UI framework
- Separate presentation, data fetching, and state logic when useful
- Handle loading, error, and empty states explicitly

## Important Notes

- If the frontend stack changes, update [STACK.md](../STACK.md) first
- Keep `frontend/` clean of leftover template assets or demo code

