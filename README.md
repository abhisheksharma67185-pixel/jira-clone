# Jira Clone

A Next.js clone of a Jira-style app built from the `sites/jira` source in the `theta-enterprise-bench` repo.

## Overview

This repository contains a production-style Jira UI implementation using:

- `next` 16.1.7
- `react` 19.2.4
- `typescript`
- `tailwindcss` v4
- `shadcn/ui`
- `@base-ui/react`

## Getting started

Install dependencies:

```bash
npm install
```

Start the local development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Run the production server locally:

```bash
npm run start
```

Run ESLint:

```bash
npm run lint
```

Run Prettier formatting:

```bash
npm run format
```

Run TypeScript type checking:

```bash
npm run typecheck
```

## Project structure

- `app/` — main Next.js app routes and layouts
- `components/` — reusable UI components
- `lib/` — shared helpers and utilities
- `hooks/` — custom React hooks
- `public/` — static assets
- `components.json` — shadcn UI component metadata

## Vercel deployment

This repository is ready for Vercel deployment. Connect the repo to Vercel and deploy the `main` branch.

## Notes

- This repo is intentionally cleaned to keep only Jira app files and essential configuration.
- Remove or adjust any additional files or settings if you want to customize the deployment further.
