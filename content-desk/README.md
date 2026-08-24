# Content Desk

A lightweight React production tracker based on the supplied Content Desk code.

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

## Notes

- Tasks and team members are stored in the browser with `localStorage`.
- CSV import is supported using the supplied tracker column order.
- The original `window.storage` dependency was replaced with browser storage so the app can run as a normal Vite website.
- The app is kept under `content-desk/` so it does not overwrite the existing Webtech project.
