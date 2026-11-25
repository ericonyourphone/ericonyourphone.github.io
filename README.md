# Eric Garcia’s website

Published at https://ericonyourphone.github.io using GitHub Pages and Jekyll. No third-party theme, JavaScript, analytics, external fonts, or runtime dependencies.

## Edit a page

Edit `about.md`, `now.md`, or `projects.md`. The home page is `index.html`. Commit changes to `main`; GitHub Pages builds and publishes automatically.

## Publish a post

Create a file in `_posts` named `YYYY-MM-DD-short-title.md`, with this format:

```markdown
---
title: "Your title"
date: 2026-11-25 12:00:00 -0600
---

Your writing goes here. Use normal Markdown.
```

Only create a post when you want it published. The home page, writing archive, and RSS feed update automatically. You can write these files in Obsidian or any text editor. Future-dated posts are withheld by Jekyll until a build after their date.

## Design

Layouts live in `_layouts`; styling lives in `assets/style.css`. The site uses a dark, terminal-inspired palette and works without JavaScript.

## Publishing

GitHub Pages source: `main`, root directory. The public repository contains only the site’s public content. Update `_config.yml` if adding a custom domain.
