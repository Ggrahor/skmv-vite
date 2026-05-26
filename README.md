# ŠKMV — Vite Static Site

Simple Vite-powered static website. No framework, just HTML + CSS bundled by Vite.

## Local development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

Output is written to `dist/`.

## Deploy

### Vercel
1. Import the repo into Vercel.
2. Framework Preset: **Vite**
3. Build Command: `npm run build`
4. Output Directory: `dist`

### Netlify
1. Drag-and-drop `dist/` to Netlify, **or** connect repo with:
   - Build command: `npm run build`
   - Publish directory: `dist`

## Structure

```
index.html        ← entry HTML (root)
styles.css        ← all styles
public/assets/    ← images served at /assets/*
vite.config.js
```
