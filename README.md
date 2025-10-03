# utnsl
various html apps for getting things done

This repository hosts single-file HTML projects (each project contains its CSS and JavaScript inline).

GitHub Pages site
-----------------

I added a simple docs-based site under `docs/` so you can enable GitHub Pages from the `main` branch -> `docs/` folder. The site lists projects from `docs/projects/projects.json` and opens the raw single-file HTML when you click a tile.

How to add a new project
------------------------

1. Add your single-file HTML into `docs/projects/` (keep filenames simple, e.g. `myapp.html`).
2. Edit `docs/projects/projects.json` and add an entry: `{ "file": "myapp.html", "title": "My App", "description": "Short description" }`.
3. Commit and push. Wait a minute, then visit `https://<your-username>.github.io/<repo>/` (or configure the Pages custom domain in the repo settings).

Notes
-----

- A `.nojekyll` file is included so filenames with leading underscores are served correctly.
- Projects are served as raw HTML so keep any external network references within your single-file app intentional.

If you'd like, I can:

- Add a tiny script to validate `projects.json` and scan `docs/projects` for orphans.
- Wire up a GitHub Action that automatically updates `projects.json` from a `projects/` source directory.

