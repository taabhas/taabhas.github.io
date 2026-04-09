# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Personal academic website for Aabha Tamhankar (PhD Candidate, Robotics Engineering at WPI). Built on the [academicpages](https://github.com/academicpages/academicpages.github.io) Jekyll theme, deployed via GitHub Pages at https://taabhas.github.io.

## Development Commands

```bash
# Local development with Docker (preferred)
docker-compose up

# Local development with Jekyll directly
bundle install
jekyll serve -l -H localhost

# Build JavaScript assets
npm run build:js
```

The site is served at `http://localhost:4000`. Note: changes to `_config.yml` require restarting the server.

## Architecture

This is a Jekyll site using collections-based content architecture:

- **`_config.yml`** — Central configuration: site metadata, author profile, social links, publication categories, collection definitions, and plugin settings. This is the most important file for site-wide changes.
- **`_data/navigation.yml`** — Controls header navigation links. Currently active: Publications, Teaching, CV (external Google Drive link).
- **`_pages/`** — Top-level site pages (publications.html, teaching.html, cv.md, about.md, etc.)
- **`_layouts/`** — Page templates (single, talk, archive, splash, default)
- **`_includes/`** — Reusable HTML partials (author-profile.html is referenced in config)
- **`_sass/`** — SCSS stylesheets
- **`assets/`** — CSS, JS, fonts, webfonts

### Content Collections

Content is organized as Jekyll collections, each in its own directory with Markdown files using YAML front matter:

- **`_publications/`** — Academic papers. Front matter: `title`, `collection`, `category` (manuscripts/conferences/books), `permalink`, `date`, `venue`, `paperurl`. Categories map to headings defined in `_config.yml` under `publication_category`.
- **`_teaching/`** — Teaching experience entries
- **`_talks/`** — Conference talks (currently disabled in navigation)
- **`_portfolio/`** — Project portfolio (currently disabled in navigation)
- **`_posts/`** — Blog posts (currently disabled in navigation)

### Markdown Generators

`markdown_generator/` contains Python scripts and Jupyter notebooks for bulk-generating collection Markdown files from TSV data or BibTeX files (publications.py, talks.py, pubsFromBib.py).

## Key Conventions

- Publication files are named with the pattern `YYYY-slug.md` (e.g., `2026-ral.md`)
- Static files (PDFs, slides) go in `files/`
- Images go in `images/`
- The `_site/` directory contains the built output (do not edit directly)
