# Testspeed

## Bean There — Coffee Shop Landing Page

A small landing page for a fictional coffee shop, **Bean There**, built as a **Vite** project.

### Files

- `index.html` — the landing page markup (hero, menu, about, visit, footer).
- `styles.css` — styling and responsive layout (desktop + mobile breakpoint).
- `src/script.js` — toggles the mobile navigation menu (with `aria-expanded` state).
- `package.json` — Vite scripts and dev dependency.

### Menu

The menu section features four items: Espresso, Pour Over, Cold Brew, and Pastries.

### Development

```sh
npm install     # install dependencies
npm run dev     # start the Vite dev server
npm run build   # production build (outputs to dist/)
npm run preview  # preview the production build
```

### Preview

Run `npm run dev` and open the URL printed by Vite, or open `index.html` directly (the page works as a plain static file too, but the Vite scripts are the intended workflow).
