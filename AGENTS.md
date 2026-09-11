# Repository guidance

This repository contains the Ferensway company website.

## Stack

- Astro
- TypeScript
- Tailwind CSS
- Reduced AstroWind configuration and metadata integration

## Commands

- `npm run dev` starts the local site.
- `npm run check` runs Astro diagnostics and formatting checks.
- `npm run build` produces the static site in `dist/`.

## Working conventions

- Keep `main` deployable and make changes through short-lived branches and pull requests.
- Preserve the single-page information architecture until additional routes have enough real content to justify them.
- Avoid speculative features, client-side JavaScript, tracking and third-party services.
- Never invent customers, case studies, testimonials, partners, certifications or statistics.
- Keep visible copy in clear British English and aimed at established business leaders.
- Use the design tokens in `src/components/CustomStyles.astro` and the restrained Ferensway visual system already established on the homepage.
