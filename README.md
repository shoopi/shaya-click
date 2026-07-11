# shaya.click

Static senior technology profile for Shaya Pourmirza.

## Live Site

- Production domain: <https://shaya.click>

## SEO and Legal Surface

- `index.html` is the canonical, indexable official profile.
- `sitemap.xml` lists the canonical profile URL and key profile images.
- `robots.txt` allows crawling and points crawlers to the sitemap.
- `privacy.html`, `terms.html` and `accessibility.html` are linked from the footer and marked `index,follow`.
- `llms.txt` provides a compact machine-readable profile summary for AI and agent crawlers.
- Cloudflare Web Analytics is included for cookie-free, anonymous aggregate traffic statistics.
- Root favicon assets and `site.webmanifest` provide stable search/browser icon signals.

## Deployment

This repository deploys to GitHub Pages automatically on every push to `main`.

The workflow lives in `.github/workflows/deploy-pages.yml` and publishes the repository root as a static Pages artifact.

## Custom Domain

The `CNAME` file sets the GitHub Pages custom domain to:

```text
shaya.click
```

DNS points `shaya.click` to GitHub Pages. For an apex domain, GitHub expects `A` records for:

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

GitHub Pages serves the site over HTTPS at `https://shaya.click`.
