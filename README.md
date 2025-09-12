# ExitDeck mini-site

Static site for Privacy Policy and Support (GitHub Pages ready).

## Publish on GitHub Pages
1. Create a repo (e.g. `exitdeck-site`).
2. Commit all files to the repo root.
3. In GitHub: Settings → Pages → Source: `Deploy from a branch`, Branch: `main` (`/root`).
4. Use the generated URL for App Store Connect metadata:
   - Privacy: `https://<username>.github.io/exitdeck-site/privacy.html`
   - Support: `https://<username>.github.io/exitdeck-site/support.html`

## Custom domain (optional)
- Add a `CNAME` file with your domain (e.g. `yourdomain.com`).
- Point DNS:
  - For `www`: CNAME → `<username>.github.io`
  - For apex/root: A records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- In GitHub Pages, set the custom domain and enable HTTPS.
