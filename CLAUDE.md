# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

End-user documentation site for Aureus ERP (Laravel/Filament open-source ERP), built with VitePress 1.x. Content is Markdown; there is no application code and no test suite. Pushes to `main` build and deploy to GitHub Pages (`docs.aureuserp.com`) via `.github/workflows/deploy.yml` (Node 18, `npm ci`, `npm run docs:build`).

## Commands

- `npm run docs:dev` — dev server on port 5173 (host exposed, all hosts allowed)
- `npm run docs:build` — production build to `.vitepress/dist`; use it to catch broken links/Vue template errors
- `npm run docs:preview` — build, then preview
- `npm run docs:format` — `prettier --write .` (no semicolons, single quotes, no trailing commas, printWidth 75)

## Architecture

- `.vitepress/config.ts` — `srcDir: 'src'`, site meta, nav, local search, edit link, `VersionSwitcher` nav component.
- `.vitepress/routes/index.ts` — maps URL prefix to sidebar. Only `/master/` exists today.
- `.vitepress/routes/master.ts` — **hand-written sidebar**. Not generated from the file tree. Every new page must be added here or it will not appear in navigation.
- `.vitepress/theme/` — extends default theme; registers global components `VersionSwitcher` and `ImagePopup`; custom CSS in `styles/`.
- `src/master/<module>/...` — pages, one folder per ERP module (invoice, sales, purchase, inventories, manufacturing, maintenance, project, employees, recruitment, timeOff, website, contact, advanced/chatter). The `master` segment is the doc version; `VersionSwitcher` swaps `/<version>/` in the URL, so a new version means a new `src/<version>/` tree, a new routes file, and an entry in the `versions` array in `VersionSwitcher.vue`.
- `src/public/` — static assets served from `/`.

## Page conventions

- Sidebar `link` values are absolute and extension-less (`/master/maintenance/configurations/teams`); in-page cross-references use relative `.md` links (`../equipments/equipments.md`).
- Screenshots use the global component, not Markdown image syntax: `<ImagePopup src="/images1/<module>/<name>.png" alt="..." />`.
- Images live in `src/public/images1/<module>/`. New pages use `images1`. The older flat `src/public/images/` directory is legacy; do not add to it.
- Pages follow a pattern: intro and bold term definition, **Use Case**, a `> **In simple words:**` blockquote, then numbered steps with navigation paths written as `` `Module → Section → Page` `` and field lists as `**_Field:_** description`. Match an existing sibling page (e.g. `src/master/maintenance/configurations/teams.md`) when writing new ones.
- Note spelling differences already in the tree: `timeOff` (camelCase folder), `sales/toInvoice`. Check the real filename before linking.
