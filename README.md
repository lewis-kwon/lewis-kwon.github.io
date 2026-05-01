# lewis-kwon.github.io

Quarto source for the bilingual personal website of Seunghyun Lewis Kwon.

## Structure

- English source pages live at the repository root.
- Korean source pages live under `ko/`.
- The active top-level pages are Home, Publications, Invited Presentations & Lectures, CV, and Contact.
- Shared assets live in `images/` and `files/`.
- Quarto renders the publishable site into `docs/`, as configured in `_quarto.yml`.
- GitHub Pages should be configured to publish from the `docs/` folder on the selected branch.

## Local Preview

```powershell
quarto preview
```

## Render

```powershell
quarto render
```

## Maintenance

1. Update factual content in `WEBSITE_BRIEF.md` first.
2. Copy only confirmed facts into the relevant `.qmd` pages.
3. Keep English pages at the root and Korean translations in `ko/`.
4. Put public PDFs in `files/`.
5. Put profile or talk images in `images/`.
6. Run `quarto render` before publishing.
7. Commit both source files and the rendered `docs/` output.

## Content Rules

- Use `cv_overleaf_source.txt` as the authoritative source for publications, invited presentations and lectures, awards, education, and position.
- Do not add unverified publications, awards, talks, media coverage, affiliations, or job titles.
- Do not add analytics, tracking scripts, external widgets, or heavy animation.
