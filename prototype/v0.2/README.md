# AdCheck — Google Ads Policy Pre-Flight Checker

**Prototype v0.2**

AdCheck is an independent, browser-based pre-flight checker for Responsive Search Ads. It screens advertiser-supplied assets for potential policy and quality risks using public Google Ads guidance.

## v0.2 changes
- Up to **15 headlines** and **4 descriptions**
- CSV/XLSX upload for Google Sheets exports
- Modern responsive interface
- Dark/light mode with saved preference
- Clear findings **and actionable suggestions**
- Character-limit, duplicate-asset, claim, destination, relevance and category-sensitive screening signals
- Responsive Search Ad readiness checks

## Test locally
Open `index.html` in a modern browser. The spreadsheet parser is loaded from SheetJS CDN, so internet access is needed for XLSX/CSV upload.

## Suggested spreadsheet columns
`Headline 1` through `Headline 15`, `Description 1` through `Description 4`, `Final URL`, `Display Domain`, `Business Name`, `Category`, `Keywords`, `Landing Page Offer`.

If using Google Sheets, download the sheet as `.xlsx` or `.csv` and upload it.

## Important limitation
AdCheck is not Google's review system and cannot guarantee approval. A finding is a review signal, not a confirmed policy violation. Actual Google Ads decisions can depend on context and information unavailable to this prototype.

## Primary public references
- https://support.google.com/google-ads/answer/7684791
- https://support.google.com/adspolicy/answer/6020955
- https://support.google.com/adspolicy/answer/6368661
- https://support.google.com/adspolicy/answer/6021546
