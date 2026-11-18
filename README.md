# Mehmet Tuzunkan

Industrial engineer and BI engineer who builds tested tools for finance and operations data.

## What I build

- Python tools for finance data: synthetic ledgers with labeled problems, and checks that list entries worth a second look.
- Text extraction for engineering documents, scored against data labeled by hand.
- Browser demos that run the same Python code in the page, so your files are not uploaded.

## Projects

| Project | What it does | Demo | CI | A number you can check |
| --- | --- | --- | --- | --- |
| [ledgercheck](https://github.com/mehmetsean/ledgercheck) | Checks journal entry and AP exports for patterns worth a second look, and measures each rule's precision and recall on labeled synthetic data. | [In the browser](https://mehmetsean.github.io/ledgercheck/) | [![ci](https://github.com/mehmetsean/ledgercheck/actions/workflows/ci.yml/badge.svg)](https://github.com/mehmetsean/ledgercheck/actions/workflows/ci.yml) | Duplicate payment search on 36 months: 526 pair compares instead of 9,850,141, with the same recall ([benchmark](https://github.com/mehmetsean/ledgercheck/blob/main/docs/benchmark.md)) |
| [synthbiz](https://github.com/mehmetsean/synthbiz) | Seeded synthetic finance data for one fictional manufacturer: ten linked tables that reconcile, with planted and labeled anomalies. | [In the browser](https://mehmetsean.github.io/synthbiz/) | [![ci](https://github.com/mehmetsean/synthbiz/actions/workflows/ci.yml/badge.svg)](https://github.com/mehmetsean/synthbiz/actions/workflows/ci.yml) | Ten labeled anomaly types, listed in [anomalies.py](https://github.com/mehmetsean/synthbiz/blob/main/src/synthbiz/anomalies.py) |
| [rfi-analysis-system](https://github.com/mehmetsean/rfi-analysis-system) | Finds standard citations (IEEE, NESC, IEC, ANSI, ASTM, NEMA) in engineering RFIs. Being rebuilt. | Not yet | [![ci](https://github.com/mehmetsean/rfi-analysis-system/actions/workflows/ci.yml/badge.svg)](https://github.com/mehmetsean/rfi-analysis-system/actions/workflows/ci.yml) | Test set of 85 RFIs written by hand, with 185 labeled citations and 51 look-alikes that are not citations ([heldout](https://github.com/mehmetsean/rfi-analysis-system/tree/main/heldout)) |

## How I work

- Every project has tests and CI on Python 3.11 to 3.14, with a coverage floor.
- Numbers in a README come from a script in the repo that you can rerun.
- Accuracy is measured on labeled data, and the false alarms and misses are shown next to the hits.

## Education

- BS Industrial Engineering (ABET-accredited), University at Buffalo (SUNY), 2021
- MBA, University at Buffalo (SUNY), 2021
- MS Computer Science, Human-Computer Interaction specialization, Georgia Tech (OMSCS), in progress, expected December 2027

## Contact

[LinkedIn](https://www.linkedin.com/in/mstuzunkan)

All rights reserved. You may view the code and run it to evaluate it. Commercial use needs a paid license from Mehmet Tuzunkan: https://www.linkedin.com/in/mstuzunkan
