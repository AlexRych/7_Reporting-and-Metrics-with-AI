**QA Summary — Regression – Sprint 20**

**Overall Results**

| Metric | Value |
|---|---:|
| Suite | Regression – Sprint 20 |
| Total tests | 100 |
| Passed | 92 (92%) |
| Failed | 8 (8%) |
| Flaky | 3 |
| Defects (Critical / Major / Minor) | 2 / 3 / 4 |

**Module Breakdown**

| Module | Passed | Failed | Pass % |
|---|---:|---:|---:|
| Checkout | 20 | 4 | 83.3% |
| Search | 15 | 1 | 93.8% |
| Profile | 25 | 0 | 100.0% |
| Orders | 18 | 3 | 85.7% |
| Login | 14 | 0 | 100.0% |

**ASCII Visualization (overall)**

Passed: 92% |[##############################################----]| 92/100

Legend: `#` = passed portion, `-` = failed portion

**ASCII Visualization (by module)**

Checkout  : [#########################-------] 83% (20/24)
Orders    : [########################--------] 86% (18/21)
Search    : [##############################--] 94% (15/16)
Profile   : [###############################] 100% (25/25)
Login     : [###############################] 100% (14/14)

**Quick Notes & Recommendations**

- Overall pass rate is strong at 92%, but failures are concentrated in Checkout and Orders.
- There are 2 critical defects — these should be triaged immediately.
- Flaky tests (3) need identification and stabilization; add logging and re-run under CI to gather names.
