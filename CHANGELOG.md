# Changelog

All notable changes to this website are documented in this file.

## [Unreleased]

### To Do
- Add PhD supervisor names to CV page
- Expand teaching page with specific course names and descriptions
- Expand work experience with full history (pending CV from user)
- Clean up `_data/authors.yml` placeholder entries
- Set up Google Analytics tracking ID

## 2026-04-14

### Major Redesign
- Restructured entire site to follow [hasan-rakibul.github.io](https://hasan-rakibul.github.io/) layout
- New navigation: Home, Research, Publications, Teaching, Services, CV, Contact
- Created new **Research** page (interests, awards, conferences, talks)
- Created new **Services** page (peer review, committees, memberships)
- Created new **Teaching** page (replacing empty template)
- Merged Education and Experience into **CV** page
- Added "Find me on" academic profile links footer to every page
- Replaced inline HTML styling with clean Markdown across all pages

### Fixed
- Typo: "school of School of Systems and Computing" → "School of Systems and Computing"
- Typo: "Health Informatcs" → "Health Informatics"
- Typo: "Curriculam Vitae" → "Curriculum Vitae"
- Google Maps embed changed from University of Western Australia to UNSW Canberra
- Contact page `redirect_from: /resume` conflict with CV page removed
- Site description updated from "personal description" to actual description

### Removed
- Old pages: `education.md`, `experience.md`, `speeches-honors-awards.md`, `projects.md`
- Empty template pages: `portfolio.html`, `talks.html`, `teaching.html`, `talkmap.html`
- Unused archive pages: `archive-layout-with-content.md`, `collection-archive.html`, `page-archive.html`, `category-archive.html`, `tag-archive.html`, `year-archive.html`

## 2025-06-12

### Updated
- News page with latest entries

## 2025-06-11

### Added
- Education page with PhD, M.Sc., and B.Sc. details and institution logos
- UNSW Canberra logo (`logounsw.png`)

### Updated
- News page updates

## 2025-06-10

### Updated
- Site configuration (`_config.yml`) with updated author bio and social links
- About page with current PhD student info at UNSW Canberra
- Navigation menu restructured (Home, News, Experience, Education, Publications, Speeches/Honors/Awards, CV, Contact)
- News page with 2025 entries (PhD start, ACS membership, publications)

## 2025-02-24 - 2025-02-25

### Updated
- About page and config updates reflecting PhD program start at UNSW Canberra (February 2025)

## 2024-11-01 - 2024-11-19

### Updated
- Iterative about page refinements

## 2024-10-19 - 2024-10-28

### Updated
- Website content updates (about page, config)
- README and feed.xml updates

## 2024-09-24

### Fixed
- Deployment issues resolved
- Index.html removed from root (Jekyll handles routing)
- Merge and sync with development branch

## 2024-09-22 - 2024-09-23

### Added
- Custom theme: rock-black on golden-reddish color scheme
- Resume/CV section with downloadable PDF
- Sidebar width adjustments and info updates

## 2024-09-21

### Added
- Publications section with conference papers
- Experience section with resume details

## 2024-09-20

### Added
- Initial commit: Jekyll site based on academicpages theme
- Core pages: About, CV, Publications, Contact
- Author profile with academic and social links
