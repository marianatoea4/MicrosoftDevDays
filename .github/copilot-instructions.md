# Project Guidelines

## Project Overview
- This repository is an Astro v5 starter for Mona Mayhem, a retro-themed site.
- Runtime is server-side (SSR) using `@astrojs/node` in standalone mode.
- TypeScript uses Astro strict configuration.

## Build And Dev Commands
- Install dependencies: `npm install`
- Start development server: `npm run dev`
- Build production output: `npm run build`
- Preview production build: `npm run preview`
- Run Astro CLI directly: `npm run astro -- <args>`

## Architecture
- File-based routes live under `src/pages`.
- The home page is `src/pages/index.astro`.
- API endpoints are implemented as route files under `src/pages/api`.
- Dynamic API route example: `src/pages/api/contributions/[username].ts`.

## Astro Best Practices
- Prefer `.astro` pages and components for markup-first UI.
- Keep server-only logic in API routes and server contexts, not browser scripts.
- For dynamic SSR endpoints, set `export const prerender = false`.
- Preserve TypeScript strictness; add explicit types for route handlers and response shapes.
- Keep page routes and API routes small and composable; extract reusable logic into modules when needed.
- Validate user input in API routes and return JSON with clear status codes.

## Conventions
- Use ESM syntax consistently (`import`/`export`).
- Keep changes focused; avoid broad refactors unless requested.
- Do not edit generated build outputs (for example `dist`).

## References
- Project overview and setup: `README.md`
- Astro docs: https://docs.astro.build
- Astro API routes: https://docs.astro.build/en/guides/endpoints/
