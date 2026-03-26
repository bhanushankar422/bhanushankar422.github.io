# Architecture

This site uses **Hugo** as the static site generator and the **Ananke** theme.

## Key components

- Content layer: `content/` (Markdown + front matter)
- Presentation layer: `themes/ananke/` with optional overrides in `layouts/`
- Static assets: `static/`
- Processed assets: `assets/`
- Configuration: `hugo.yaml`

## Render flow

1. Hugo reads `hugo.yaml` and content files.
2. Hugo applies templates from site `layouts/` and then theme templates.
3. Hugo copies static files and processes assets.
4. Generated site is written to `public/`.

## Content model

- Section home pages can use folder bundles (example: `content/about/index.md`).
- Media placed next to `index.md` can be referenced by that page.
- Global static files should go in `static/`.

