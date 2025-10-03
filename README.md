# utnsl
various html apps for getting things done

This repository contains single-file HTML projects — each project bundles its own CSS and JavaScript so you can drop a single file onto a static host or open it locally.

## Live site

Preview the site at: https://lirohdesign.github.io/utnsl/ (enable GitHub Pages for the `main` branch using the `docs/` folder if it's not already enabled).

## Projects included

- p r o x i m i t y
  - Description: A fuzzy search tool designed to scan large documents and policies for groups of related keywords. It helps surface minor wording variations and related matches so you don't miss relevant entries.
  - Use case: I use this to quickly find policy sections that match several keywords or phrases that might be written differently across documents.
  - How to run: Open `docs/projects/p r o x i m i t y.html` in your browser, paste or load the text corpus, and run queries.

- w r k f l o
  - Description: A visual checklist and workflow builder. Designed for auditing and other repeatable processes where tasks depend on each other. Supports nested branches, progress tracking, and JSON export/import.
  - Use case: Build complex audit checklists once, then reuse them — track progress, branch into subtasks, and save/load project state as JSON.
  - How to run: Open `docs/projects/w r k f l o.html` in your browser, create or load a workflow, then use the UI to manage tasks and export your project.

## Notes & recommendations

- These are single-file apps; if you rely on CDNs (fonts, libraries), expect reduced offline capability.

