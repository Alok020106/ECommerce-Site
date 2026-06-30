# E-commerce React Frontend

This is the React + Vite frontend for an e-commerce website.
The working app lives in this folder: `frontend`.

## What this project contains

- React application files in `src/`
- Vite configuration in `vite.config.js`
- `package.json` and `package-lock.json` for dependencies
- `npm run dev` starts the local development server

## Start the app

Open a terminal and run:

```bash
cd "c:\Users\kriss\OneDrive\Documents\Desktop\EcommSite\E-commerce-reactjs\frontend"
npm install
npm run dev
```

Then open this URL in the browser:

```text
http://localhost:5173/
```

## Notes

- The root `E-commerce-reactjs` folder does not contain `package.json`; the app is inside `frontend`.
- `package-lock.json` is created by npm to lock dependency versions.
- If you see a message about vulnerabilities, the app can still run.

## Fixing npm audit warnings

To check dependency security warnings:

```bash
npm audit
```

To try to fix them automatically:

```bash
npm audit fix
```

## Useful commands

- `npm install` — install dependencies
- `npm run dev` — start Vite dev server
- `npm run build` — build production files
- `npm run preview` — preview the built app locally
