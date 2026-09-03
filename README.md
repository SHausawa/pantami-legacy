# Pantami Legacy Digital Archive

A bilingual (English/Hausa), evidence-first React + Vite website designed for GitHub Pages.

## What is included

- 242 project entries transcribed from the **Table of Projects** in the supplied legacy compilation.
- Search and filters by project category and inferred Gombe LGA/location.
- English/Hausa interface and plain-language explanations.
- Evidence modal for every project, showing the corresponding scanned page from the source PDF.
- Interactive Gombe map with approximate LGA-centre pins for browsing.
- Public-service timeline and transparent verification methodology.
- GitHub Actions deployment workflow.
- Responsive mobile/desktop design.

## Important data note

This site presents what the supplied document **records**. `documentedInReport: true` does not mean a claim has been independently verified. The UI deliberately separates report documentation from future government-source, beneficiary, geolocation, and independent verification.

The `lga` field is inferred from place names in project titles where possible; entries without a sufficiently specific place are marked **Statewide / Unspecified**. Map pins represent approximate LGA centres, not project coordinates.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy to GitHub Pages

1. Create a new GitHub repository and upload all files in this folder.
2. Push to the `main` branch.
3. In GitHub: **Settings → Pages → Source → GitHub Actions**.
4. The included `.github/workflows/deploy.yml` workflow will build and publish the site.

Vite uses `base: './'`, so the site works from a GitHub repository sub-path without hard-coding a repository name.

## Data enrichment

Edit `src/projects.json`. Useful next fields are precise coordinates, primary-source URLs, beneficiary confirmations, project status updates, and Hausa project-title review by a native editor.
