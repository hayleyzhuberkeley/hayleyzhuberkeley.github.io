# Change 1: Home Introduction

## Goal

Make the Home page introduction more specific and recruiter-friendly.

## Planned changes

1. Rewrite the Home headline and introduction as a concise value proposition using only résumé facts: Hayley's Head of Growth Marketing & Product Marketing role at Creatify AI while it scaled to $10M ARR, her General Manager role at Done Global, her founding of The Butterfly Effect Media, and her Berkeley MBA expected in 2027.
2. Add a short **Highlights** list with three résumé-based results:
   - Creatify AI scaled to $10M ARR in 18 months; paid CAC fell 34% and blended CAC fell 48%.
   - Done Global's AI therapy product reached 10,000 paid users and more than $1 million in monthly revenue.
   - The Butterfly Effect Media secured $1 million in funding and reached $3 million ARR in its first fiscal year.
3. Keep the existing visual design, accessibility, shared layout, navigation, footer, and page route unchanged. Do not change CSS or add dependencies.
4. Keep `Change1.md` as project planning documentation and exclude it from the generated site.

## Verification

Build the site with `bundle exec jekyll build` and confirm the generated Home page contains the updated introduction and all three highlights. Stay on the `improve-home-intro` branch.