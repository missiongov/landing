# MissionGov — Static GitHub Pages site

This is a small, patriotic government-style static website for **MissionGov**, a disabled veteran owned business.

## Files
- `index.html` — main site
- `styles.css` — styling
- `assets/logo.png` — provided logo (already included)
- `CNAME` — custom domain (missiongov.com)

## How to deploy to GitHub Pages
1. Create a repository named `yourusername.github.io` (or use user/site configuration).
2. Upload these files at the repository root (or build output for a framework).
3. Commit and enable GitHub Pages in repository settings (branch: main, folder: /).
4. Add the `CNAME` file with `missiongov.com` to connect your custom domain and set DNS records.

## Notes
- The contact form is static and uses a JS alert. Replace the `form` action with your preferred form handler (Formspree, Netlify Forms, or a server endpoint) to capture messages.
