# shaya.click

Static personal promo page and app catalogue for Shaya Pourmirza.

## Live Site

- Production domain: <https://shaya.click>
- App catalogue first entry: <https://expense.shaya.click/myexpense>

## Deployment

This repository deploys to GitHub Pages automatically on every push to `main`.

The workflow lives in `.github/workflows/deploy-pages.yml` and publishes the repository root as a static Pages artifact.

## Custom Domain

The `CNAME` file sets the GitHub Pages custom domain to:

```text
shaya.click
```

DNS still needs to point `shaya.click` to GitHub Pages. For an apex domain, GitHub expects `A` records for:

```text
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

Recommended `www` record:

```text
www CNAME shoopi.github.io
```

After DNS updates, GitHub Pages can issue the HTTPS certificate and serve `https://shaya.click`.
