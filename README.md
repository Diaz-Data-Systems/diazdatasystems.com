# Diaz Data Systems, LLC — Website

Static marketing site for [diazdatasystems.com](https://www.diazdatasystems.com/),
hosted on **GitHub Pages**. Migrated off Wix.

## Files
| File | Purpose |
|------|---------|
| `index.html` | The entire site (single page: Home / Services / About / Contact) |
| `styles.css` | All styling, no external dependencies |
| `favicon.svg` | Browser tab icon |
| `404.html` | Custom not-found page |
| `CNAME` | Custom domain for GitHub Pages (`www.diazdatasystems.com`) |
| `.nojekyll` | Tells Pages to serve files as-is (no Jekyll build) |

## Editing the site
Everything visitors see is in `index.html`. Edit the text directly, commit, and
push — GitHub Pages redeploys automatically within a minute or two.

### Things to personalize
- **Social links:** in `index.html`, the footer `.social` block has `href="#"`
  placeholders. Replace with your real LinkedIn / Facebook / Instagram / X URLs,
  or delete the ones you don't use.
- **Contact form:** submitting opens the visitor's email app addressed to
  `info@diazdatasystems.com`. To switch to a hosted form later (e.g. Formspree),
  replace the `<form>` action and remove the mailto script.

## Local preview
Open `index.html` in a browser, or run a local server:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```
