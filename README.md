# FLUX HOUSE Website

Landing page for FLUX HOUSE — a rental space in Nagareyama / Minami-Nagareyama, Chiba.

Built with [Astro](https://astro.build/).

## Deploy to Cloudflare Pages

1. Push this repository to GitHub.
2. Log in to [Cloudflare Pages](https://pages.cloudflare.com/) and click **Create a project → Connect to Git**.
3. Select this repository.
4. Set the following build settings:
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
5. Under **Environment Variables → Production**, add:
   - `NODE_VERSION` = `18`
6. Click **Save and Deploy**.

Every push to the main branch will trigger an automatic redeploy.

## Local Development

```bash
npm install
npm run dev
```

Then open http://localhost:4321 in your browser.
