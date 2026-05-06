# MAGIC Lab Website for GitHub Pages

This folder contains a static website for `MAGIC Lab` that is ready to host on GitHub Pages without a build step.

## Files

- `index.html`: main page content
- `styles.css`: layout, colors, typography, and responsive behavior
- `script.js`: mobile menu toggle and footer year

## Customize

Update the lab content in `index.html`:

- research areas
- publication entries and links
- team members
- news items
- contact email and address

## Publish on GitHub Pages

### Recommended for this site

1. Create or use the repository named `magic-ailab.github.io`.
2. Copy the contents of this folder into the repository root.
3. Push to the `main` branch.
4. In GitHub, open `Settings > Pages`.
5. Under `Build and deployment`, set:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main` and `/ (root)`
6. Visit `https://magic-ailab.github.io/`.

## Local preview

You can open `index.html` directly in a browser for a quick preview. If you want to use a local server instead:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

## Good next upgrades

- add exact Google Scholar, GitHub, and CV links for Jiafei Duan
- add project thumbnails, demo videos, and publication images
- split publications, people, and news into separate pages
- add a `CNAME` file later if you switch to a custom domain
