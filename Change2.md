# Change 2: Work Experience Layout

## Goal

Make the Work Experience page easier to scan without changing its single-column layout.

## Planned changes

1. Add an **At a glance** list at the top with every company, role, and date range. Link each role to its company's section; Done Global's two roles will link to the same section.
2. Place each company and its existing résumé details in a separate card-like section, using a subtle border and spacing while preserving the site's accessible text and link contrast.
3. Add **Education** and **Skills & Languages** sections at the bottom, using the résumé details already shown on the About page:
   - UC Berkeley MBA, expected June 2027; University of Washington BA in International Studies, French minor, 2015–2018.
   - Data analytics: SQL, Excel; design: Figma, Adobe, Framer, Webflow; project management: Feishu, Linear, Asana.
   - Mandarin and English (native), French (intermediate), Italian (conversational), and Cantonese (no proficiency level listed).
4. Exclude `Change2.md` from the generated site, as with `Change1.md`.

## Verification

Run `bundle exec jekyll build`, confirm summary links target the company sections and the new education/skills content is present, and inspect the Work Experience page at 375px and 1280px. Stay on `improve-experience-layout`.