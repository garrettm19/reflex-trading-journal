# Reflex – Developer Setup

## Prerequisites
- Node.js (v18+)
- npm

## Install & Run
1. Clone the repo: `git clone https://github.com/garrettm19/reflex-trading-journal.git`
2. `cd reflex-trading-journal`
3. `npm install`
4. `npm run dev` – Vite dev server for the renderer at http://localhost:5173 (open in a browser)
5. `npm start` – Vite dev server plus the Electron window
6. `npm run build` – build the renderer to `dist/renderer`

## Project Structure
- `src/main/` – Electron main process
- `src/renderer/` – UI (React + Zustand)
- `src/overlay/` – floating mascot overlay (stub, planned)
- `src/db/` – SQLite access (stub, planned)
- `docs/` – SDLC and planning documentation
- `demo/` – screenshots
