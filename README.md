# Angelwing Culinary Compass

This is a static HTML landing page built with Tailwind CSS via CDN.

## Files
- `index.html` — main page
- `IMG_20280809_103614_397.png` — logo/image used by the site

## Cloudflare Pages Deployment

To deploy this site on Cloudflare Pages:

1. Sign in to Cloudflare and go to **Pages**.
2. Create a new project and connect your Git repository.
3. Set the project root to the repository folder containing `index.html`.
4. Use these settings:
   - Build command: leave blank
   - Output directory: `.`
   - Framework preset: `None`
5. Save and deploy.

## Notes
- This site is fully static and does not need a build step.
- Tailwind CSS and Font Awesome are loaded from CDN, so the page works as long as the browser has internet access.
- If you update the page locally, commit the changes and Cloudflare Pages will redeploy automatically.
