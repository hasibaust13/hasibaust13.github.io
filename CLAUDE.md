# CLAUDE.md

Project guidance for AI assistants working on this repository.

## Project Overview

Personal academic website for **Khan Md Hasib**, PhD student at UNSW Canberra. Built with Jekyll using a customized [academicpages](https://github.com/academicpages/academicpages.github.io) theme (forked from Minimal Mistakes). Hosted on GitHub Pages at [hasibaust13.github.io](https://hasibaust13.github.io).

Redesigned in April 2026 to follow the structure of [hasan-rakibul.github.io](https://hasan-rakibul.github.io/) — clean, content-focused pages with consistent "Find me on" footer links.

## Tech Stack

- **Static site generator**: Jekyll (Ruby)
- **Theme**: Customized academicpages / Minimal Mistakes
- **Hosting**: GitHub Pages
- **Publications**: BibBase (external service, loaded from `references.bib`)
- **Styling**: SCSS (in `_sass/`), compiled by Jekyll

## Repository Structure

```
_config.yml          # Site-wide settings, author info, collections, plugins
_data/               # navigation.yml, authors.yml, UI text
_includes/           # Reusable HTML partials (header, footer, sidebar, SEO)
_layouts/            # Page layout templates
_pages/              # All site pages (about, cv, research, news, etc.)
_sass/               # SCSS stylesheets
_site/               # Generated output (do not edit directly)
assets/              # CSS, JS, fonts
files/               # Downloadable files (CV PDF, BibTeX)
images/              # Profile photo, institution logos, favicons
```

## Key Pages

| Page | File | Status |
|------|------|--------|
| Home / About | `_pages/about.md` | Complete — bio + recent news + find me on |
| Research | `_pages/research.md` | Complete — interests, awards, conferences, talks |
| Publications | `_pages/publications.md` | Complete (via BibBase) |
| Teaching | `_pages/teaching.md` | Minimal — needs course details |
| Services | `_pages/services.md` | Complete — reviewer roles, committees, memberships |
| CV | `_pages/cv.md` | Complete — PDF embed + education + experience summary |
| Contact | `_pages/contact.md` | Complete — email, office, UNSW Canberra map |
| News | `_pages/news.md` | Complete — 2023–2025 entries |

## Navigation

Defined in `_data/navigation.yml`. Current menu: Home, Research, Publications, Teaching, Services, CV, Contact.

## Development

```bash
bundle install          # Install dependencies
bundle exec jekyll serve  # Local development server at localhost:4000
```

## Remaining Items

- PhD supervisor names still TBD (not yet added to CV page)
- Teaching page needs specific course names and descriptions
- Experience section in CV only has one position (BUBT) — pending full CV from user
- `_data/authors.yml` still contains template placeholder entries
- Google Analytics tracking ID is empty (no analytics active)

## Conventions

- Pages use YAML front matter with `layout`, `title`, `permalink`, `author_profile`
- Content is written in clean Markdown (not inline HTML) — consistent with April 2026 redesign
- Every page ends with a "Find me on" section linking to academic profiles
- Institution logos go in `images/` directory
- CV PDF is stored at `files/CV/resume.pdf`
- News entries are added chronologically (newest first) in `_pages/news.md`
