# Content & Verification Guide

This archive is intentionally **evidence-first**. It preserves what the supplied legacy compilation states and visibly separates that from independent verification.

## Verification statuses

1. **Report documented** — the item appears in the supplied compilation.
2. **Government-source confirmation** — add only after locating an official agency/Federal Government source supporting the project.
3. **Beneficiary confirmation** — add only after obtaining a documented confirmation from the institution/community/beneficiary.
4. **Precise geolocation** — add only after confirming the actual project coordinates/location.

Never convert “report documented” into “independently verified” without supporting evidence.

## Hausa editorial review

The interface and plain-language explanations are translated into Hausa. Project titles use partial translation for recurring programme names while preserving institution and place names. Before a major public launch, a native Hausa editor should review all project titles for consistency, especially technical expressions and institutional names.

## Adding richer project records

Each object in `src/projects.json` can be extended with:

- `latitude`, `longitude`
- `primarySourceUrl`
- `primarySourceTitle`
- `beneficiaryQuote`
- `beneficiarySource`
- `photoGallery`
- `verificationDate`
- `verificationNotes`

Keep the scanned legacy-report page as the baseline evidence even after adding independent sources.
