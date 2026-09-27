# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Primary: scientific peers and potential collaborators (researchers, other groups, funders) evaluating whether BIO³ BIOCUBO is a serious quantitative group to work with. Secondary: prospective students/early-career researchers and the wider UGR public looking for members and the seminar schedule.

## Product Purpose

Public site of BIO³ BIOCUBO, a quantitative research group at the Universidad de Granada (Biomathematics, Biostatistics, Bioinformatics, Epidemiology, Public Health). It presents who the group is, who its members are, what it investigates, and its quarterly seminar cycle. Success: a first-time visitor understands what BIO³ is and reaches members or seminars within seconds.

## Positioning

An interdisciplinary UGR group that applies rigorous mathematical and statistical method to biosciences and public health, standing at the documented intersection of Bioinformatics, Biostatistics and Biomathematics (the "BIO³" name).

## Operating Context

Static Hugo site using the Wowchemy/HugoBlox "academic-cv" theme, published on GitHub Pages at https://migariane.github.io/biocubo/ via GitHub Actions (`.github/workflows/deploy.yml`, Hugo 0.162+ extended). Content is authored in Spanish as Markdown in `content/es/` (home landing sections, `content/es/authors/` for group + members, `content/es/seminars/` for events). Edits build with `hugo --minify`.

## Capabilities and Constraints

- Landing page composed of blocks: hero, biography, members grid, seminars collection, mission; plus a dedicated seminars listing page.
- No backend, forms, or manual copy step; GitHub Actions builds and deploys `public/` automatically on push to `main`.
- Content language: Spanish. Facts (names, roles, departments, seminar details) are fixed and must not be invented.
- Photography exists in `static/media/` (seminar and group photos, member-less) and must be used as-is; no image generation in this environment.

## Brand Commitments

- Humanized navigation: no logos in navbar or page headings; text-only branding.
- Keep the Newsreader + Inter typography intent where the theme allows; cloth quilt color palette (`assets/scss/custom/custom.scss`) applied via CSS custom properties.
- No other visual element is binding: palette, layout, and composition are free to replace.

## Evidence on Hand

Members bios, tags and links (`members.qmd`), seminar entries and gallery (`seminars.qmd`), group description and mission (`about.qmd`, `index.qmd`), institutional partner logos (`images/logos.png`), three seminar/group photos (`images/seminar1.jpg`, `seminar2.jpg`, `ext.jpg`). No testimonials, metrics, publication counts, or funding figures exist on hand — future work must not fabricate them.

## Product Principles

1. Rigor first: the design must read as scientifically serious, not promotional.
2. People and seminars are the product: members and the seminar cycle get the strongest real estate.
3. Facts stay facts: never invent numbers, claims, or affiliations.
4. Institutional credibility: UGR affiliation and partner logos are visible proof.

## Accessibility & Inclusion

Standard web accessibility: keyboard focus visibility, semantic headings, alt text on images, contrast meeting WCAG AA, `prefers-reduced-motion` respected (already a project convention).
