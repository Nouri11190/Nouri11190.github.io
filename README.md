# Mark Allen Group — GitHub Pages starter

A responsive static website for Mark Allen Group, designed to publish first on GitHub Pages and later attach a purchased custom domain.

## What is included

- Responsive home page
- About and focus-area sections
- Project index seeded from historical context
- Working principles
- GitHub profile links
- Accessible mobile navigation
- No build step, npm dependencies, or external JavaScript libraries

## Important content note

Project summaries and statuses are provisional. They are based on conversation history and must be checked against the current repositories before being presented as verified current status. The site intentionally does not expose private infrastructure addresses, credentials, or secrets.

## Publish as `Nouri11190.github.io`

1. Create a repository named exactly `Nouri11190.github.io` under the GitHub account `Nouri11190`.
2. Upload the contents of this folder to the repository root. Do not upload the enclosing folder itself.
3. In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Wait for the Pages deployment to complete and open `https://Nouri11190.github.io`.
5. Test on a phone and desktop. Check every project link and update statuses.

## Later: connect a custom domain

After buying and verifying ownership of `markallengroup.org.ng` or `markallengroup.xyz`:

1. In **Settings → Pages → Custom domain**, enter the exact domain.
2. Configure the DNS records at the registrar using the current GitHub Pages documentation for the chosen domain type.
3. Wait for DNS checks to pass, then enable **Enforce HTTPS** when available.
4. Test both the apex domain and `www` only if you configure it.
5. Keep the GitHub Pages URL as a fallback during setup.

Do not guess DNS values or expose tokens. Follow the current GitHub documentation: https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site

## Editing

This is plain HTML, CSS, and JavaScript. Edit `index.html` for copy and project entries, `assets/styles.css` for design, and `assets/main.js` for small interactions.
