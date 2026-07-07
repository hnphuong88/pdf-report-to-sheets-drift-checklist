# PDF Report To Sheets Drift Checklist

Static validation artifact for recurring PDF reports that feed Google Sheets.

This is intentionally not a parser. It tests whether people care about schema
drift, duplicate periods, missing fields, and suspicious totals after an
automation is already running.

## Files

- `index.html` - publish-ready static page.
- `fixtures/expected-schema.json` - synthetic expected schema.
- `fixtures/sample-output.csv` - synthetic parsed output.
- `fixtures/drift-report.md` - synthetic drift report.

## Paid hypothesis

- $19/month for one recurring report source.
- $29/month for schema drift plus totals sanity checks.
- $99 one-time schema template setup.

## Boundary

No uploads, no customer data, no posting, and no external publishing without
explicit user approval.
