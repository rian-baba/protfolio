# Portfolio (Vite + React + TypeScript + TailwindCSS)

Single‑page portfolio with hidden admin mode to add projects locally and copy JSON for later commits. Built for simplicity, performance, and easy customization.

## Quick start

- Install deps: `npm install`
- Dev: `npm run dev`
- Build: `npm run build` then `npm run preview`

## Customize content

- Edit text, links, skills, and default projects in `src/content.ts`.
- Replace `public/vite.svg` or add `public/cv.pdf` and update the hero CV link if needed.
- Projects you add in admin mode are saved in `localStorage`.

## Admin mode (hidden)

- You will see Add Project and Copy Projects JSON. These controls are not visible to regular visitors.

## Tailwind

- Tailwind v3 configured in `tailwind.config.js` and `postcss.config.js`.
- Custom classes live in `src/index.css` (`container-responsive`, `btn-*`, `tag`).

## Deploy

- Vercel, Netlify, GitHub Pages all work. For GitHub Pages, build and push `dist/` or configure actions.



