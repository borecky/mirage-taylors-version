# mirage-taylors-version

A countdown page for the **Mirage (Taylor's Version)** Path of Exile private league.

## Deployment

The page is automatically deployed to **GitHub Pages** on every push to `main`.

### Setup (one-time)

1. Go to the repository **Settings → Pages**.
2. Under **Source**, select **GitHub Actions**.
3. Push to `main` — the workflow in `.github/workflows/deploy.yml` will build and publish the site automatically.

The live URL will be:
```
https://<your-github-username>.github.io/mirage-taylors-version/
```