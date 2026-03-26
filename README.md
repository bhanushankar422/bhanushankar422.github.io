# bhanushankar422.github.io

This repository contains a Hugo-based static website.

## Run locally

```powershell
hugo server -D
```

## Build

```powershell
hugo
```

## Documentation

- Architecture: `ARCHITECTURE.md`
- Product details: `PRODUCT.md`
- Contributing guide: `CONTRIBUTING.md`

## Project structure (high level)

- `hugo.yaml`: Hugo site configuration
- `content/`: Website pages and markdown content
- `static/`: Static assets copied directly to output
- `assets/`: Source assets processed by Hugo pipeline
- `layouts/`: Site-specific template overrides
- `themes/ananke/`: Theme files
- `public/`: Generated site output

## Common content updates

- Add a new page: create a new markdown file under `content/`.
- Update existing page content: edit corresponding file in `content/`.
- Add images for a section bundle page: place them in the same folder as `index.md`.

