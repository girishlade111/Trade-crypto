# Trade Crypto

A modern crypto-trading landing page / dashboard UI built with React, Vite, TypeScript, shadcn-ui, and Tailwind CSS. Client-side only — no backend required.

## Features

- Crypto-trading themed marketing site: hero, features, pricing, testimonials
- Polished component library (shadcn-ui + Radix UI primitives)
- Charts with Recharts, animations with Framer Motion
- Dark-mode support via `next-themes`
- Responsive layout, Tailwind-powered styling

## Tech Stack

- React 18 + TypeScript
- Vite 5 (build tool)
- Tailwind CSS + shadcn-ui / Radix UI
- React Router, TanStack Query, React Hook Form + Zod
- Recharts, Framer Motion, Lucide icons

## Quick Start

Requires Node.js (use [nvm](https://github.com/nvm-sh/nvm#installing-and-updating) to install).

```sh
# 1. Clone the repository
git clone https://github.com/girishlade111/Trade-crypto.git
cd Trade-crypto

# 2. Install dependencies
npm install --legacy-peer-deps

# 3. Start the dev server
npm run dev
```

Open http://localhost:8080 in your browser.

## Project Structure

```
Trade-crypto/
├── index.html            # Entry HTML (base path set for GitHub Pages)
├── vite.config.ts        # Vite config (@ alias, production base path)
├── src/
│   ├── main.tsx          # App entry point
│   ├── App.tsx           # Router + providers
│   ├── pages/            # Route pages (Index)
│   ├── components/       # UI sections + shadcn-ui components
│   ├── hooks/, lib/, config/  # Helpers, utils, config
├── public/               # Static assets
└── dist/                 # Production build output (git-ignored; built output lives at repo root on main for Pages)
```

## Deploy

Static site. The production build is committed at the repo root on `main` and served via GitHub Pages:

https://girishlade111.github.io/Trade-crypto/

To rebuild: `npm run build`, copy `dist/*` to the repo root, commit, and push.

## License

Free to use and modify.

---

Built by [Girish Lade](https://ladestack.in) · More projects at [ladestack.in](https://ladestack.in)
