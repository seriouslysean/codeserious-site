# AGENTS.md

Eleventy site for codeserious.com (based on eleventy-base-blog), deployed to GitHub Pages.

- Install: `npm ci` (Node version in `.nvmrc`).
- Gate before a PR: `npm run build`. No lint, format or test scripts exist, and `.github/workflows/deploy.yml` also runs only `npm ci` and `npm run build`.
- Where things live: `content/` pages and posts, `_includes/` layouts and partials, `_data/` site data, `public/` static files, `eleventy.config*.js` Eleventy config.
