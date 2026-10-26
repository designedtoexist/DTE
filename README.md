# Designed to Exist

Scroll-animated website for Designed to Exist. Plain HTML, CSS and JavaScript. No build step.

- Instagram: https://www.instagram.com/designed_toexist
- GitHub: https://github.com/designedtoexist

## Files

- `index.html`: the whole site
- `assets/logo.jpg`: logo (also used as the favicon)
- `vercel.json`: Vercel settings

## Deploy

1. Create a new repository on GitHub and upload these files, keeping the `assets` folder.
2. On vercel.com choose Add New, then Project, and import the repository.
3. Leave Framework Preset as Other, with no build command and no output directory. Click Deploy.

## Notes

- In `index.html`, `window.LIVE_PREVIEW` controls whether the work cards try to load the real sites. Set it to `false` to show the built-in mockups only. A site that refuses to be shown inside another page will appear blank in its card.
- Fonts load from Google Fonts, so the site needs an internet connection to show Cormorant Garamond.
