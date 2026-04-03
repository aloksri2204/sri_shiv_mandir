# Shri Shiv Mandir website (GitHub Pages)

This repository contains a static site that can be published on GitHub Pages.

## Deployment (GitHub Pages)

1. Commit and push all files, including `index.html` and `assets/`.
2. Go to repository **Settings** > **Pages**.
3. Under **Build and deployment**, set **Source** to `main` branch and folder `/(root)`.
4. Save.
5. GitHub Pages will publish at `https://<your-user>.github.io/sri_shiv_mandir/`.

## Notes

- `index.html` is the entry point for site serving.
- All asset URLs are relative (e.g. `assets/images/...`) so they work under project page path.
- If you prefer a custom domain, set it in Pages settings and add `CNAME` with your domain name.
