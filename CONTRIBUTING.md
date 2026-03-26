# Contributing

Thank you for contributing to this Hugo website.

## Workflow

1. Create a feature branch.
2. Make focused changes.
3. Run local checks.
4. Open a pull request with a clear description.

## Local validation

```powershell
hugo server -D
hugo
```

## Content guidelines

- Keep Markdown simple and readable.
- Use clear headings and short paragraphs.
- Keep front matter consistent with existing pages.
- Place page-specific images near that page bundle (`content/<section>/index.md`).

## Code and template guidelines

- Prefer site overrides in `layouts/` instead of editing theme files directly.
- Keep changes minimal and scoped to the task.
- Do not commit generated output unless your deployment flow explicitly requires it.

## Pull request checklist

- [ ] Content renders correctly locally
- [ ] No broken links/images in changed pages
- [ ] Build passes with `hugo`
- [ ] Documentation updated when behavior changes

