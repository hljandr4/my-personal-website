# my-personal-website

This is a static Astro portfolio site configured for GitHub Pages.

## Deployment

- The repo includes a GitHub Actions workflow in `.github/workflows/deploy.yml`.
- On push to `main`, the site builds and deploys to GitHub Pages.
- In GitHub, open Settings > Pages and set the source to `GitHub Actions` to finish enabling the Pages site.
- The expected live URL is `https://hljandr4.github.io/my-personal-website/`.

## Local development

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```
