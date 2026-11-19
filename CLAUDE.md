# Portfolio — project instructions

Personal portfolio of Angelo Torrelli. It leads with **sustainability / ESG** and **data analysis**.
Single static page: `index.html` (no framework, no build step).

## How it is published
- Netlify project `portfolio-angelotorrelli` deploys automatically from the `main` branch.
- Live site: https://portfolio-angelotorrelli.netlify.app
- Merging to `main` publishes the site within seconds. Treat `main` as production.

## Workflow rules
- Never push directly to `main`. Work on a branch and open a pull request; the owner reviews and merges.
- Do not use the GitHub web editor to edit or rename `index.html`: the file is too large and a rename once saved it empty.
- Commit messages: short, in English, describing what changed.

## Working with the owner
- Talk to the owner in neutral Latin American Spanish (tuteo). All website content stays in English.
- The owner is new to Git, GitHub and Claude Code. Before running any command, explain what it does and why, then wait for approval. (Learning-phase rule: remove this line when the owner says so.)
- Make one change at a time and confirm what happened after each step.

## Current state of `index.html`
- About 2.5 MB but only ~15 KB of real code: 16 images (13 JPG, 3 PNG) are embedded as base64 inside the file. Three lines hold most of the weight, so never print the file whole; strip `data:...;base64,...` before reading it.
- Planned fix: move the images out into separate files in the repo.
- Design is flat. Goal of the redesign: it must not look AI-generated or template-like.
- Current look (may change in the redesign): green palette with one wheat accent, Fraunces for headings and Hanken Grotesk for text.

## Must be preserved in any redesign
- The YouTube video in the "Is Decoupling Real?" project: ID `fHRZNEjmNL4`, click-to-load through `youtube-nocookie`.
- Link to the CRM demo: https://crmatorrelli.netlify.app
- Link to LinkedIn: https://www.linkedin.com/in/angelo-torrelli
- The GoatCounter analytics script (`atorrelli.goatcounter.com`).
- The three projects: Is Decoupling Real?, Tree-Monitoring Dashboard, Sales-Analytics CRM, and the in-page document viewer that opens the PDFs.

## Repository contents
- `index.html` — the site
- `Decoupling_Analysis_Angelo_Torrelli.pdf`, `Tree_Dashboard_v1_MVP.pdf` — project documents
- `CO2 Energy V2.xlsx`, `Energy_CO2_Top15.xlsx`, `Desacopleco2.csv` — data files
- `README.md` — public project description and links
- This repo is public: never add private or personal information to any file.
