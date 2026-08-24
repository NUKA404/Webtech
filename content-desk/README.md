# Content Desk

A lightweight React production task tracker based on the supplied Content Desk code.

## Run locally

```bash
cd content-desk
npm install
npm run dev
```

Then open the local Vite URL shown in the terminal.

## Build

```bash
npm run build
npm run preview
```

## Deployment

GitHub Actions builds `content-desk` and deploys it to GitHub Pages whenever changes are pushed to `main` under this folder.

## Notes

- Tasks and team members are stored in the browser with `localStorage`.
- CSV import/export is supported using Papa Parse.
- The original `window.storage` dependency was replaced with browser storage so the app can run as a normal Vite website.
- The app is kept under `content-desk/` so it does not overwrite the existing Webtech project.
