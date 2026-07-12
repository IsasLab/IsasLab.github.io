# IsasLab hub (isaslab.github.io)

The landing page for [IsasLab](https://isaslab.github.io/) — the index of all projects
(ISAS Token Reducer, Gatherfire, and more).

Self-contained static site: a single `index.html` with inlined CSS/JS (no build step,
no external stylesheet) plus two images. Served by GitHub Pages at the root domain
because the repo is named `IsasLab.github.io`.

## Structure
- `index.html` — the hub. Each project card links out to that project's own page/repo.
- `logo-mark.png`, `Logo.png` — brand mark + social/OG image.

## Deploy
Push to `main`; GitHub Pages (Settings -> Pages -> Deploy from branch -> `main` / root)
serves it at https://isaslab.github.io/. Because this is a `*.github.io` user/org repo,
Pages publishes at the root automatically.

## Adding a project
Copy an existing `.proj` card in `index.html`, point its `href` at the new project's
URL, and set its status tag (`tag-live` / `tag-building` / `tag-soon`).
