# MAZE UI - Architecture Guide

## Stack
| Layer | Technology |
|-------|-----------|
| Frontend | Next.js + TypeScript |
| Backend API | Fastify |
| Styling | Tailwind CSS |

## Architecture
```
Next.js (SSR) --> Fastify API --> Database
     |                |
  React Pages    REST Endpoints
  Components     Middleware
```

## Getting Started
```bash
git clone https://github.com/matigulin/maze-ui.git
cd maze-ui
npm install
npm run dev
```

## Project Structure
- pages/ - Next.js routes
- components/ - Reusable React components
- api/ - Fastify backend endpoints
- lib/ - Shared utilities