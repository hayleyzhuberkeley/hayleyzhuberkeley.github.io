# Hayley Zhu's portfolio

This is a static Jekyll site for `https://hayleyzhuberkeley.github.io`. GitHub Pages builds it directly from the `main` branch and the repository root; no separate build workflow is needed.

## Update the site

- Edit `index.md`, `about.md`, `work-experience.md`, or `contact.md` to update page content. Keep the YAML front matter at the top of each page.
- Update shared navigation, page structure, and footer in `_includes/` and `_layouts/default.html`.
- Change colors, typography, spacing, and responsive rules in `assets/css/portfolio.css`.
- The Contact page links to Hayley's LinkedIn profile.
- Your email address is public on the Contact page. Visitors need an email app configured to use the `mailto:` link.

## Preview locally

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve --livereload
```

Open `http://127.0.0.1:4000/`. Jekyll serves the site locally and rebuilds pages as you edit them.

## Check responsive layouts and Lighthouse

In Chrome, open the local preview and use DevTools' device toolbar to inspect widths of **375px** and **1280px**. Click each navigation link at both sizes.

To run Lighthouse, open Chrome DevTools, choose **Lighthouse**, select Performance, Accessibility, Best Practices, and SEO, then generate reports for both mobile and desktop. The target for each category is **90 or higher**.

## Publish with GitHub Pages

1. Use a GitHub user-site repository named `hayleyzhuberkeley.github.io`.
2. Push the site files to its `main` branch with `_config.yml` and `index.md` at the repository root.
3. In the repository's **Settings → Pages**, select **Deploy from a branch**, then choose `main` and `/(root)`.

GitHub Pages will run its supported Jekyll build automatically. Do not select a nested folder or add a custom Actions build for this site.