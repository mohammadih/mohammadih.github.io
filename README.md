# Hossein Mohammadi — Academic Research Website

Source repository for [hossein-mohammadi.com](https://hossein-mohammadi.com/), the professional research portfolio of Hossein Mohammadi. The site presents verified research experience, education, technical capabilities, teaching, and professional contact information for work in AI-assisted wireless communication systems.

## Technology Stack

- [Hugo](https://gohugo.io/) Extended 0.136.5
- [Hugo Blox Academic CV](https://hugoblox.com/)
- Hugo Modules managed through `go.mod`
- [Pagefind](https://pagefind.app/) for static search
- GitHub Actions and GitHub Pages for deployment

## Local Preview

Install Hugo Extended 0.136.5 and Go, then run:

```bash
hugo server
```

Hugo serves the development site at `http://localhost:1313/` by default.

## Production Build

Node.js and npm are also required to generate the search index.

```bash
HUGO_ENVIRONMENT=production hugo --minify --baseURL "https://hossein-mohammadi.com/"
npx pagefind --site public
```

The generated website and Pagefind index are written to `public/`.

## Deployment

The workflow in `.github/workflows/publish.yaml` deploys the site to GitHub Pages when changes are pushed to `main` or when the workflow is started manually. It installs the pinned Hugo version, builds the production site, generates the Pagefind index, uploads `public/`, and deploys the Pages artifact. The custom domain is preserved in `CNAME` and in the repository's GitHub Pages settings.

## Content Overview

- `content/_index.md` — homepage composition
- `content/authors/admin/_index.md` — verified biography, education, research experience, capabilities, and distinctions
- `content/experience.md` — research experience and education page
- `content/teaching/_index.md` — teaching page
- `config/_default/menus.yaml` — primary navigation
- `config/_default/params.yaml` — SEO, header, footer, and appearance
- `static/uploads/` — downloadable CV

## Branch and Contribution Workflow

1. Create or use a focused branch such as `website-redesign`.
2. Make source-only changes and keep generated `public/` output out of commits.
3. Run the production build, Pagefind, placeholder scans, and internal-link checks.
4. Review the diff and factual content before merging to `main`.
5. Let the existing GitHub Pages workflow perform deployment after merge.

Do not publish biographical, employment, publication, project, award, or performance claims without verifying them against an authoritative source.
