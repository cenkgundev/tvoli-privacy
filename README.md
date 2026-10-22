# Tvoli Privacy and Support

The public privacy policy, terms of use and support page for **Tvoli**, a TV remote app for iPhone and iPad. The site is plain HTML with inline CSS. It has no build step, no scripts and no tracking.

**Live site:** https://cenkgundev.github.io/tvoli-privacy/

## Pages

| File | URL | Content |
| --- | --- | --- |
| `index.html` | [/](https://cenkgundev.github.io/tvoli-privacy/) | Privacy policy (English) |
| `privacy-tr.html` | [/privacy-tr.html](https://cenkgundev.github.io/tvoli-privacy/privacy-tr.html) | Privacy policy (Turkish) |
| `terms.html` | [/terms.html](https://cenkgundev.github.io/tvoli-privacy/terms.html) | Terms of use (English) |
| `terms-tr.html` | [/terms-tr.html](https://cenkgundev.github.io/tvoli-privacy/terms-tr.html) | Terms of use (Turkish) |
| `support.html` | [/support.html](https://cenkgundev.github.io/tvoli-privacy/support.html) | Finding a TV, pairing per brand, contact |

The app's paywall opens the privacy policy at the root URL. Keep that file name and path stable.

Contact on every page: support@melyro.app.

## Update and deploy

GitHub Pages serves the `main` branch from the repository root, with HTTPS enforced and no custom domain.

1. Edit the HTML files. Each page carries its own `<style>` block, footer navigation and light and dark colours.
2. When you change the privacy policy or terms, update the effective date and make the same change in the English and Turkish files.
3. Preview locally with `python3 -m http.server` and open http://localhost:8000.
4. Commit and push to `main`. Pages publishes the change within a minute or two.

## Licence

Proprietary. All rights reserved.
