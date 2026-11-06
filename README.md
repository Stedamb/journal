# Journal

A personal journal of short essays and notes, written in Italian.

**Live:** [personal-journal-chi.vercel.app](https://personal-journal-chi.vercel.app)

## Features

- Posts written in Markdown and loaded through Astro content collections with a typed schema
- Fully static output: Astro components only, with a few GSAP animations
- Light and dark themes styled with Tailwind CSS 4

## Tech stack

| Area      | Tooling                              |
| --------- | ------------------------------------ |
| Framework | Astro 7 (static output)              |
| Content   | Markdown and content collections     |
| Styling   | Tailwind CSS 4                       |
| Animation | GSAP                                 |
| Packages  | pnpm                                 |

## Getting started

Requires Node.js 22 or later and [pnpm](https://pnpm.io).

```bash
pnpm install
pnpm dev
```

The dev server runs at <http://localhost:4321>.

## Writing a post

Add a Markdown file to `src/content/posts/`:

```md
---
title: "Titolo del post"
date: "2026-11-06"
description: "Una frase che riassume il post."
---

Il testo del post…
```

It is published at `/posts/<file-name>` on the next build.

## Scripts

| Command        | Description                                          |
| -------------- | ---------------------------------------------------- |
| `pnpm dev`     | Start the dev server                                 |
| `pnpm build`   | Type-check with `astro check`, then build to `dist/` |
| `pnpm preview` | Preview the production build                         |

## License

Code is released under the [MIT License](LICENSE). The posts are © Stefano D'Ambrosio and are not covered by the license.
