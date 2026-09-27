# Devora — Custom Software Studio

Marketing site for Devora, built with Next.js (App Router), TypeScript, Tailwind CSS, and Framer Motion.

## Prerequisites

- Node.js 20.9 or later (the minimum version Next.js 16 supports)
- npm, which comes with Node.js

## Getting started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Scripts

| Command | What it does |
| --- | --- |
| `npm run dev` | Starts the development server at http://localhost:3000 |
| `npm run build` | Creates the production build |
| `npm run start` | Serves the production build. Run `npm run build` first. |
| `npm run lint` | Checks the code with ESLint |

## Stack

- Next.js 16 (App Router, static export-friendly)
- TypeScript
- Tailwind CSS v4
- Framer Motion (scroll-triggered and gesture animations)

## Deployment

Deployed on Netlify via `netlify.toml` and `@netlify/plugin-nextjs`. Connect this repository in the Netlify dashboard, or run:

```bash
npx netlify-cli deploy --build --prod
```
