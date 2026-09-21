# Ferensway website

The public website for Ferensway, a Yorkshire-based delivery partner that designs, builds and ships data, digital and AI products to improve operational efficiency and margins.

## Development

This is a static Astro site built from a deliberately reduced AstroWind scaffold, using TypeScript and Tailwind CSS.

```sh
npm install
npm run dev
```

Run `npm run check` and `npm run build` before opening a pull request.

## Hosting

Merges to `main` deploy the static site to GitHub Pages at
`https://ferensway.github.io/website/`. In the repository's **Settings → Pages**,
set **Build and deployment → Source** to **GitHub Actions**. The deployment
workflow can also be started manually from the **Actions** tab.

The Astro `site` and `base` settings target the GitHub Pages project URL. When
the custom domain is ready, update both `astro.config.ts` and `src/config.yaml`
to use the domain and `/` base path before configuring the domain in GitHub Pages.

## Principles

- Keep the site static and dependency-light.
- Write for senior business decision-makers, not software engineers.
- Start with business problems; treat AI as one possible tool.
- Do not add claims, customers, case studies or credentials that have not been established.
- Prefer clear British English and restrained presentation.
