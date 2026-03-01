# MERN techNotes Backend

Simple Express backend starter for the techNotes project.

## What this project does

- Serves static assets from `public/`
- Serves home page at `/` and `/index.html`
- Returns a custom 404 page for unknown routes
- Runs on port `3500` by default (or `process.env.PORT`)

## Project structure

- `server.js` - app setup, static middleware, routes, 404 handler, server start
- `routes/root.js` - root route (`/`, `/index.html`)
- `views/index.html` - landing page
- `views/404.html` - not found page
- `public/css/style.css` - styles

## Requirements

- Node.js (recommended LTS)
- npm

## Install

```bash
npm install
```

## Run

### Development (auto-reload)

```bash
npm run dev
```

### Production-like

```bash
npm start
```

Server URL:

- `http://localhost:3500`

## Quick test

- Home page: `http://localhost:3500/`
- 404 page: `http://localhost:3500/anything`

## npm scripts

- `npm start` -> `node server`
- `npm run dev` -> `nodemon server`
