# PhotyAi

PhotyAi - Your personal AI outfit styling assistant.

## GitHub Pages

This repository hosts the following pages via GitHub Pages:

- **Home**: https://tugberktabak.github.io/photyai/
- **Privacy Policy**: https://tugberktabak.github.io/photyai/privacy
- **Terms of Use**: https://tugberktabak.github.io/photyai/terms
- **Support**: https://tugberktabak.github.io/photyai/support

### Setup

GitHub Pages is configured to deploy automatically from the `main` branch using GitHub Actions. The workflow is defined in `.github/workflows/pages.yml`.

To enable GitHub Pages for this repository:

1. Go to repository Settings → Pages
2. Under "Build and deployment", select "GitHub Actions" as the source
3. The pages will be automatically deployed when changes are pushed to the `main` branch

### Structure

- `index.html` - Main landing page
- `privacy/index.html` - Privacy policy page (accessible at `/privacy`)
- `terms/index.html` - Terms of use page (accessible at `/terms`)
- `support/index.html` - Support page (accessible at `/support`)
- `.nojekyll` - Disables Jekyll processing for faster deployment

The original HTML files (`privacy.html`, `terms.html`, `support.html`) are kept for backward compatibility.
