# Development

Markdown-first help center for Kyler Holland products, powered by [Retype](https://retype.com/).

## Local preview

```bash
npm install
npm run dev
```

Opens a live-reloading preview in your browser.

## Deploy

Push to `main` — GitHub Actions builds the site and publishes to the `retype` branch for GitHub Pages.

Live site: https://help.kylerholland.com

## Custom domain (one-time)

Hosting stays on **GitHub Pages**; `help.kylerholland.com` is DNS + GitHub settings.

1. **GitHub** — Repo [Settings → Pages](https://github.com/KYLERHOLLAND/KH-help-center/settings/pages): set **Custom domain** to `help.kylerholland.com`, save, then enable **Enforce HTTPS** when available.
2. **DNS** — Where `kylerholland.com` DNS is managed (Wix Domains or your registrar), add a **CNAME** record:
   - **Host / name:** `help`
   - **Points to:** `kylerholland.github.io`
3. Wait for DNS (often 15–60 minutes; up to 48h). Retype writes `CNAME` on each deploy from `url` in `retype.yml`.
4. **Wix** — Link menus/footer to `https://help.kylerholland.com`.

## Add content

- Edit `.md` files under `products/` (one folder per product)
- Configure the site in `retype.yml`
- Link from your Wix site to https://help.kylerholland.com
