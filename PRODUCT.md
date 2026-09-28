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

Static Quarto website (`project.type: website`, output to `docs/`) published on GitHub Pages at https://migariane.github.io/biocubo/ from branch `main`, path `/docs`. Content is authored in Spanish in `.qmd` sources (`index.qmd`, `members.qmd`, `seminars.qmd`, `about.qmd`) with a single `styles.css` and `_quarto.yml`. Edits must render with `quarto render`.

## Capabilities and Constraints

- Four static pages: Inicio, Miembros, Seminarios, Sobre el Grupo; navbar search overlay; back-to-top.
- No backend, forms, CMS, or JS build step; only Quarto + Bootstrap + custom CSS.
- Content language: Spanish. Facts (names, roles, departments, seminar details) are fixed and must not be invented.
- Photography exists in `images/` (seminar and group photos, member-less) and must be used as-is; no image generation in this environment.

## Brand Commitments

- Keep the `images/biocubo_logo.svg` cube logo (favicon, navbar, hero) and the UGR crest `images/logo_ugr.png`.
- Keep the Newsreader + Inter typography system (explicitly confirmed).
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
