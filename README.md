# Brynn Interactive Website

Static website prepared for TikTok/Twitch developer registration.

## Files
- `index.html` — public landing page
- `terms.html` — Terms of Service
- `privacy.html` — Privacy Policy
- `styles.css` — visual style

## Recommended public URLs
Once deployed, use:
- `https://YOUR-DOMAIN/terms.html`
- `https://YOUR-DOMAIN/privacy.html`

These are the URLs you can paste into TikTok's:
- Terms of Service URL
- Privacy Policy URL

Do **not** use the OAuth callback URL for those fields.

Your TikTok Desktop Login Kit redirect remains:
`http://127.0.0.1:8765/oauth/tiktok/callback`

## GitHub Pages
1. Create a new public repository, for example `brynn-interactive-site`.
2. Upload all files from this folder to the repository root.
3. Open Settings -> Pages.
4. Under Build and deployment, choose `Deploy from a branch`.
5. Select branch `main` and folder `/ (root)`.
6. Save and wait for GitHub Pages to publish.
7. Your URLs will look like:
   - `https://YOUR-USERNAME.github.io/brynn-interactive-site/terms.html`
   - `https://YOUR-USERNAME.github.io/brynn-interactive-site/privacy.html`

## Cloudflare Pages
1. Create a Pages project.
2. Connect the repository or upload this folder.
3. No build command is required.
4. Use the generated `*.pages.dev` domain.
5. Your URLs will look like:
   - `https://YOUR-PROJECT.pages.dev/terms.html`
   - `https://YOUR-PROJECT.pages.dev/privacy.html`

## Before public release
The legal pages are practical starter templates for an independent beta project, not legal advice.
Before a commercial/public release, replace the generic Contact section with your real support email or contact form and consider legal review.
