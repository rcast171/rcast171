---
name: validate-spreadsheet-product
description: "Validate formula integrity and reusable spreadsheet behavior. Use when a spreadsheet is intended as a reusable template, sellable product or public demonstration, or errors and inconsistent calculated values are observed."
---

# Validate spreadsheet product

1. Identify the canonical workbook, intended user, input cells, outputs and all dependent tabs. Preserve real personal or customer entries privately.
2. Inspect actual formulas and references, not only fetched display text. Record each error with cell, formula, expected behavior and observed behavior.
3. Create a clean synthetic example. Verify calculations independently for normal inputs, blanks, zero denominators, negative values where allowed, goal modes, boundary dates and rolling windows.
4. Repair the authorized formulas and validation rules. Keep legitimate empty states distinct from broken references; never hide an error without fixing its cause.
5. Recheck dependent tabs and protect formula cells where appropriate. Add short input instructions and a clear sample/reset convention.
6. Report exactly which checks passed and which remain blocked. Public or sellable status requires an actual usable export/copy and a reproducible synthetic example.

Output: formula/error ledger, sanitized demo, input instructions, changed-cell summary and validation results.

Scenario checks: seven-day average equals independently calculated values; loss/gain modes behave correctly; a blank week avoids broken-reference errors; original personal entries do not appear in the demo. No tested claim until the workbook has actually been inspected and exercised.
