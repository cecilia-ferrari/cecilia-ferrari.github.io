# cecilia-ferrari.github.io

Personal academic website, built with [Hugo Blox](https://hugoblox.com/templates/academic-cv) (Academic CV template) and deployed to GitHub Pages.

## Local development

```bash
npm install
npm run dev     # hugo server at http://localhost:1313
npm run build   # production build to ./public
```

## Structure

- `data/authors/me.yaml` — bio, education, experience, skills, languages, awards
- `content/experience.md` — experience/skills/awards page + extra CV sections (workshops, teaching, organization, outreach)
- `content/publications/` — publication pages
- `content/events/` — talks & seminars
- `config/_default/params.yaml` — theme colors, typography, site identity
- `data/fonts/resume.yaml` — custom font pack (Jost, matching the LaTeX résumé's Avant Garde typeface)

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site and deploys it to GitHub Pages.
