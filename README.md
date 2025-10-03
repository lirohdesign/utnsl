# utnsl
various html apps for getting things done

This repository hosts single-file HTML projects (each project contains its CSS and JavaScript inline).

GitHub Pages site

I added a simple docs-based site under `docs/` so you can enable GitHub Pages from the `main` branch -> `docs/` folder. The site lists projects from `docs/projects/projects.json` and opens the raw single-file HTML when you click a tile.

How to add a new project

1. Add your single-file HTML into `docs/projects/` (keep filenames simple, e.g. `myapp.html`).
2. Edit `docs/projects/projects.json` and add an entry: `{ "file": "myapp.html", "title": "My App", "description": "Short description" }`.
3. Commit and push. Wait a minute, then visit `https://<your-username>.github.io/<repo>/` (or configure the Pages custom domain in the repo settings).

Notes


If you'd like, I can:

# utnsl
various html apps for getting things done

This repository hosts single-file HTML projects (each project contains its CSS and JavaScript inline).

## GitHub Pages site

I added a simple docs-based site under `docs/` so you can enable GitHub Pages from the `main` branch -> `docs/` folder. The site lists projects from `docs/projects/projects.json` and opens the raw single-file HTML when you click a tile.

## How to add a new project

1. Add your single-file HTML into `docs/projects/` (keep filenames simple, e.g. `myapp.html`).
2. Edit `docs/projects/projects.json` and add an entry: `{ "file": "myapp.html", "title": "My App", "description": "Short description" }`.
3. Commit and push. Wait a minute, then visit `https://<your-username>.github.io/<repo>/` (or configure the Pages custom domain in the repo settings).

## Notes

- A `.nojekyll` file is included so filenames with leading underscores are served correctly.
- Projects are served as raw HTML so keep any external network references within your single-file app intentional.

## Included projects

- w r k f l o — Workflow builder (single-file HTML). Create nested workflows, branches, and export/import project JSON.
- p r o x i m i t y — Interactive proximity demo (single-file HTML).
- example-counter — Simple incrementing counter (single-file HTML).
- example-clock — Live local time display (single-file HTML).

## Next steps (optional)

- I can add a small validator script to ensure `projects.json` entries match files in `docs/projects/`.
- I can add a GitHub Action to auto-sync or validate `projects.json` whenever you push new project files.

---

If you'd like me to import additional single-file HTML projects into `docs/projects/`, drop them here or tell me where they live and I'll add them and update the manifest and README.

