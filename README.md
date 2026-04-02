# Chicago Workforce Risk & Classification Analysis

A GitHub Pages–ready portfolio project analyzing workforce structure, classification consistency, compensation patterns, compliance context, and 2022 structural change signals using public City of Chicago sources.

## Hosting
This repo is designed for **GitHub Pages** hosting as a static site, not Streamlit.

## Suggested Pages
- Home / Executive Summary
- Workforce Composition
- Classification & Compensation
- Shakman / Hiring Governance
- 2022 Structural Change Signals
- Methods
- Sources

## Repo Structure
- `site/` static website files for GitHub Pages
- `data/` raw, processed, and reference data
- `notebooks/` exploratory and cleaning notebooks
- `src/` reusable data-cleaning and metric code
- `docs/` methods, sources, and data dictionary

## Publish on GitHub Pages
1. Push this repo to GitHub
2. In repo settings, open **Pages**
3. Set source to deploy from your main branch
4. Point Pages to the `/site` folder if using Actions, or move the site files to the repo root if you prefer branch deployment

## Suggested Output Files
Export cleaned CSV or JSON files into:
- `site/assets/data/`
Then reference them from `site/index.html` or separate HTML pages.

## Notes
This project should clearly distinguish:
- hard datasets
- reference documents / memos / PDFs
- inferred or manually coded variables
