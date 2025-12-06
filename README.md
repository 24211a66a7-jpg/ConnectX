# ConnectX Website :-
   https://connectx2025.netlify.app/

## Purpose

This repository contains the source for the ConnectX landing site — a promotional/informational single-page website that showcases the event, speakers, agenda, partners, and ways to join or contact the organizers.

## What This Website Is For

- Presenting event details and agenda
- Highlighting speakers and partners
- Providing registration/join/contact information
- Serving as the canonical public page for ConnectX

## Tech Stack

- Vite (build tooling)
- React (UI)
- TypeScript
- Tailwind CSS (styling)
- PostCSS

Files and tools in this repo that reflect the stack:

- `vite.config.ts`
- `tsconfig.json` / `tsconfig.app.json`
- `tailwind.config.js` / `postcss.config.js`
- `src/` contains React + TypeScript components

## Production Link

https://connectx2025.netlify.app/

## Installation (development)

Requirements: Node.js (16+ recommended) and npm or pnpm.

Using npm (Windows PowerShell):

```powershell
npm install
npm run dev
```

Build for production:

```powershell
npm run build
npm run preview
```

If you use `pnpm` or `yarn`, replace `npm` accordingly.

## Project Structure (high-level)

- `public/` — static assets
- `src/` — React app and components
- `index.html` — app entry
- `package.json` — scripts & dependencies
