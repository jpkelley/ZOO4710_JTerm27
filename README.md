# Scientific Evidence and Causal Inference — Quarto Book Starter

Starter for **ZOO 4710-80**, University of Wyoming, J-Term II 2027. Uses a Quarto book sidebar model inspired by <https://jpkelley.github.io/ZOO5500/>. The landing page draws from the current course flyer.

## Included files

- `_quarto.yml` — Quarto book navigation and output configuration (site builds to `docs/`)
- `index.qmd` — fully written public landing page, with updated pronghorn header illustration
- `chapters/calendar.qmd` — complete **draft** ten-module calendar
- `chapters/course-information.qmd` — course information and FAQs
- `styles.css` — restrained teal/navy look, matching the flyer
- `assets/course-header.webp` — optimized illustrated course banner with breathing room above horns
- `assets/ZOO4710-80_course_flyer.pdf` — reference flyer, linked from homepage
- `_templates/module-template.qmd` — reusable Quarto lesson/activities template (not yet published)
- `chapters/modules/README.md` — roadmap for the ten future instructional modules

## How to preview

1. Install [Quarto](https://quarto.org/docs/get-started/) if not already installed.
2. Open this folder in RStudio, VS Code, or a terminal.
3. Run `quarto preview` for a live preview, or `quarto render` for a production build.
4. The rendered website is written to `docs/`.

## Publish with GitHub Pages

1. Create a GitHub repository (for example, `ZOO4710`) and commit these source files.
2. Run `quarto render` and commit the generated `docs/` folder.
3. In GitHub repository **Settings > Pages**, select **Deploy from a branch**, branch `main`, folder `/docs`.
4. Add an empty `docs/.nojekyll` file after render if GitHub Pages is processing Quarto assets as Jekyll content.
5. Confirm the actual published URL before generating or placing the QR code on the flyer.

The likely URL for a repository named `ZOO4710` under user `jpkelley` would be `https://jpkelley.github.io/ZOO4710/`, **but it is not established until the repository is published.**

## Add future module chapters

Copy `_templates/module-template.qmd` to `chapters/modules/01_evidence_and_estimands.qmd`, revise its content, then add that file path under a new "Instructional Modules" part in `_quarto.yml`. Repeat as modules are finished. The template is not included in live book navigation, so prospective students only see complete pages.

## Notes

- The draft assumes a suggested progression of 10 instructional modules over Jan 4–15, a suggested Evidence Audit completion period Jan 18–22, and the official UW term extending to Jan 29. **Do not publish a specific final due date until verified.**
- The site is designed for a *public course preview*. Assessment links, grading weights, rules, policies, and any student-specific materials belong in WyoCourses or the finalized syllabus.
- The QR code itself has **not** been created or added.
- This package contains Quarto **source files**, not a pre-rendered website. Rendering requires an installed Quarto CLI.
