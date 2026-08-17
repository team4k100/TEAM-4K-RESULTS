# TEAM 4K Results Checker — COMPLETE

This version fixes the previous issue where the screen stayed at "—" because the
browser could not load `data/results.json`.

## What is fixed
- Result data is embedded directly in `app.js`.
- No fetch/API is required.
- The button visibly changes to "Checking…" and then shows the result.
- Percentage is calculated from marks / 1100 × 100.
- Grade is calculated using the BIEK grading thresholds in the supplied gazette.
- Normal result rows indexed: 9853
- Private/component records indexed: 60
- Withheld/UFM records indexed: 550
- Official gazette statistics shown on the page: 18,014 appeared, 9,922 passed, 55.08%.

## Test
Enter: 804713

Expected calculation:
1006 / 1100 × 100 = 91.45% → A-1

## Run
You can simply extract the ZIP and double-click `index.html`.

For hosting, a normal static web server also works.

## Important
The supplied BIEK gazette states that it is provisional and may contain errors/omissions.
This is a TEAM 4K informational checker, not the official BIEK website.
