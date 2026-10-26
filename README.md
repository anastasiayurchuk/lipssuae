# LIPSS UAE

Landing page for LIPSS in the UAE. A static site: `index.html` plus `assets/`, with no build step.

## Publish on GitHub Pages

1. Create a new public repository on GitHub, for example `lipss-uae`.
2. Click **Add file → Upload files** and drag in everything in this folder (`index.html`, `assets`, `.nojekyll`, `README.md`). Commit.
3. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/lipss-uae/`.

## Custom domain (optional)

In **Settings → Pages → Custom domain**, enter your domain (for example `lipss.ae`), then add the DNS records GitHub shows you at your domain provider.

## Enquiry form

GitHub Pages only serves files and cannot receive form submissions. To have B2B enquiries emailed to you:

1. Create a free form at https://formspree.io and copy its endpoint (looks like `https://formspree.io/f/abcdwxyz`).
2. In `index.html`, find `const ENDPOINT = '';` and paste the endpoint between the quotes.

Until then, the form asks visitors to email the address shown in the footer.
