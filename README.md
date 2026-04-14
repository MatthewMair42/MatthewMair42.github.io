# Matthew Mair — Personal Academic Website

Personal academic website for Matthew Mair, PhD student in Agricultural and Applied Economics at Virginia Tech.

## Stack

- **Framework:** [Quarto](https://quarto.org/) website
- **Theme:** Cosmo (Bootstrap) + custom SCSS (`theme.scss`)
- **Fonts:** Fraunces (headings) + Commissioner (body) via Google Fonts
- **Deployment:** GitHub Pages (served from `docs/`)

## Source Files

| File | Purpose |
|------|---------|
| `index.qmd` | Homepage — bio, photo, links |
| `research.qmd` | Working papers and publications |
| `cv.qmd` | CV page with embedded PDF viewer |
| `_quarto.yml` | Site config, navbar, output settings |
| `theme.scss` | VT color palette + font overrides |
| `styles.css` | Additional layout rules |
| `cv.pdf` | CV document (update manually) |
| `pics/` | Profile photos and image assets |

## Render & Preview

**Render** (rebuilds `docs/`):
```
quarto render
```

**Preview** (live reload in browser):
```
quarto preview
```

Or open `docs/index.html` directly in a browser for a static preview.

Quarto is bundled with RStudio at:
`C:\Users\mcmma\OneDrive\Documents\RStudio\resources\app\bin\quarto\bin\quarto.exe`

## Archive

`archive/` contains two previous Hugo Apero attempts (`personalsite/`, `mm_site/`) kept for reference. Not part of the active build.
