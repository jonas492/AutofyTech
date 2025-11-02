# AutofyTech – Netlify + GitHub (Vite + Tailwind)

## Quick start
```bash
npm i
npm run dev
```

## Deploy to Netlify
1. Push this folder to a new GitHub repo.
2. In Netlify → **New site from Git**, pick the repo.
3. Build command: `npm run build`
4. Publish directory: `dist`
5. Add environment variable (optional): `VITE_CALENDLY_LINK` if you wire a link.
6. Forms are handled via **Netlify Forms** (modal form named `demo`).

### Replace logo
Put your logo file at `public/AutofyTech_Logo_HQ.jpg`. The app references `/AutofyTech_Logo_HQ.jpg` at runtime.
