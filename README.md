# MindBrew Light — landing page

Landing page for MindBrew Light, a concept for a light-therapy café in Dublin. It's a single page that introduces the idea, the experience, the menu and the sustainability angle, and ends with contact details and a map link.

**Live:** https://mind-brew-light.vercel.app

## Sections

Hero · About · Experience · Menu · Sustainability · Contact

## Tech stack

React 18 · TypeScript · Vite · Tailwind CSS · shadcn/ui (Radix UI) · Vercel

## Getting started

Requires Node.js 18 or newer.

```bash
npm install
npm run dev       # http://localhost:8080
```

| Script              | What it does                        |
| ------------------- | ----------------------------------- |
| `npm run dev`       | Dev server with hot reload          |
| `npm run build`     | Production build into `dist/`       |
| `npm run preview`   | Serves the production build locally |
| `npm run lint`      | Runs ESLint                         |
| `npm run format`    | Formats the code with Prettier      |
| `npm run typecheck` | Type-checks without emitting        |

## Project structure

```
src/
├── components/   # one component per section, plus ui/ primitives
├── pages/        # Index and NotFound
└── assets/       # images
```

---

Built by [Heleno Matos](https://portfolio.helenomatos.com).
