# threadtoself-site

Static website for Thread to Self, intended for GitHub Pages hosting at <https://threadtoself.com>.

## Site structure

- `/` -> `index.html`
- `/privacy/` -> `privacy/index.html`
- `/terms/` -> `terms/index.html`
- `/support/` -> `support/index.html`
- Custom 404 page -> `404.html`
- Shared styles -> `assets/styles.css`
- Custom domain -> `CNAME`

## GitHub Pages publishing

1. Push the repository to the `main` branch.
2. In GitHub, open **Settings > Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Set branch to **main** and folder to **/(root)**.
5. Confirm the custom domain is `threadtoself.com`.

No build step is required. This site is plain HTML and CSS.
