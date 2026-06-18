# jtecon.github.io

Personal academic website of [Ting Ji (纪珽)](https://jtecon.github.io/), built with [Hugo](https://gohugo.io/) and deployed to GitHub Pages.

## Pages

- **Home** — biography and contact (`content/en/_index.md`)
- **Research** — working papers and publications (`content/en/research/_index.md`)

## Local development

Requires [Hugo Extended](https://gohugo.io/installation/) (v0.135.0 or compatible):

```bash
hugo server -D
```

Open http://localhost:1313/

## Deployment

Pushes to `main` trigger `.github/workflows/deploy.yml`, which builds the site and publishes to GitHub Pages.
