# Portfolio Site Plan

**Status: Approved.**

## Site

Create a personal portfolio for Yiying (Hayley) Zhu at `hayleyzhuberkeley.github.io`, published by GitHub Pages from the `main` branch and repository root. The site will use a light theme, a clean system sans-serif stack, generous whitespace, and a responsive single-column layout.

## Pages and shared elements

- **Home:** concise introduction and links to the other pages.
- **About:** supplied education, skills, languages, and interests.
- **Work Experience:** supplied roles and achievement details, in reverse chronological order.
- **Contact:** a public `mailto:hayleyzhu0103@berkeley.edu` link and a link to Hayley's LinkedIn profile; no phone or home address.
- Reusable Jekyll layout and header, navigation, and footer includes.

## Technical approach

- Keep `index.md`, the other Markdown pages, `_config.yml`, `_layouts/`, `_includes/`, `assets/`, and supporting site files directly in the project root. Use YAML front matter and Jekyll URL filters; leave `baseurl` empty.
- Use semantic HTML, plain CSS, minimal JavaScript (prefer none), accessible contrast, SEO metadata, a sitemap, a favicon, and a README with update, local-preview, and Lighthouse instructions.
- Remove unrelated generated application and workspace scaffolding so the final repository is only the static Jekyll site. Do not add a backend, database, form service, blog, CMS, framework, or tracker.

## Content and assumptions

- Use only the résumé text supplied in chat. Correct obvious text-encoding artifacts without changing its meaning; do not add achievements, employers, metrics, projects, a phone number, or a home address.
- Use the LinkedIn profile URL supplied by Hayley.
- Assume the GitHub Pages user-site repository is `hayleyzhuberkeley.github.io` and the site has no custom domain.

## Verification

Check root-level structure, Jekyll/GitHub Pages compatibility, internal navigation and URL-filtered links, responsive appearance at 375px and 1280px, and Lighthouse targets of at least 90 for Performance, Accessibility, Best Practices, and SEO.