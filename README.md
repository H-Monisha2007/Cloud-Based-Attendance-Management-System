# Cloud-Based Attendance Management System

Choose a class/date, mark each learner present or absent, and review attendance percentage. Records persist in localStorage on this browser.

## Requirements
- Node.js (LTS)
- npm

## Run on Windows PowerShell
Open this project folder in VS Code, then run:

```powershell
npm.cmd install
npm.cmd run dev
```

Open the local URL shown by Vite (usually `http://localhost:5173`).

## Build
```powershell
npm.cmd run build
```

## Files
- `index.html` — HTML entry point
- `src/App.jsx` — React application and JavaScript logic
- `src/main.jsx` — React startup
- `src/styles.css` — responsive CSS styling
- `package.json` — dependencies and scripts

## Important
This is a beginner-friendly front-end prototype. Browser `localStorage` is used where applicable, so data stays in that browser and is not automatically shared between users/devices. For actual cloud functionality, add a backend API, authentication, and a cloud database or object-storage provider.
