# cummins.dev

Personal site for Ryan Cummins. Built with [Astro](https://astro.build) and deployed on [Cloudflare Pages](https://pages.cloudflare.com).

## Development

```sh
npm install
npm run dev       # localhost:4321
npm run build     # production build to ./dist/
npm run preview   # preview production build locally
```

## Adding an Essay

Create a Markdown file in `src/content/writing/`:

```
src/content/writing/your-essay-slug.md
```

With this frontmatter:

```yaml
---
title: "Your Essay Title"
description: "One-sentence description shown on the index page."
date: 2026-04-06
---
```

The essay will automatically appear at `/writing/your-essay-slug`.

## Deployment

Cloudflare Pages is connected to this repo. Pushing to `main` deploys to production. Any other branch gets a preview deployment with a unique URL posted to the PR.
