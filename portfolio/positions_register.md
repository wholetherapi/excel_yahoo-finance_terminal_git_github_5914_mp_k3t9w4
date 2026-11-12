# Model Portfolio Positions Register

System of record for the Alder Lane Capital flagship model portfolio. The
register is refreshed after every approved rebalance. Downstream risk and client
reporting jobs read only the "Current Positions" section and expect exactly one
position per line.

## Current Positions

- MSFT: 2150 shares
- JNJ: 3400 shares
- XOM: 6400 shares
- KO: 8900 shares
- PG: 5975 shares
- CAT: 1300 shares
- VZ: 19675 shares
- MRK: 7125 shares
- PEP: 6000 shares
- CVX: 4525 shares

## Rebalance History

| Effective date | Directive | Note |
| --- | --- | --- |
| 2026-10-13 | RBL-2026-10 | October rebalance approved by Investment Committee |
| 2026-09-14 | RBL-2026-09 | September rebalance approved by Investment Committee |
| 2026-08-17 | RBL-2026-08 | August rebalance approved by Investment Committee |
| 2026-07-13 | RBL-2026-07 | July rebalance approved by Investment Committee |
| 2026-06-15 | RBL-2026-06 | June rebalance approved by Investment Committee |
| 2026-05-11 | RBL-2026-05 | May rebalance approved by Investment Committee |
| 2026-04-13 | RBL-2026-04 | April rebalance approved by Investment Committee |
| 2026-03-16 | RBL-2026-03 | March rebalance approved by Investment Committee |
| 2026-02-17 | RBL-2026-02 | February rebalance approved by Investment Committee |
| 2026-01-12 | RBL-2026-01 | January rebalance approved by Investment Committee |
| 2025-12-15 | RBL-2025-12 | December rebalance approved by Investment Committee |
| 2025-11-10 | RBL-2025-11 | November rebalance approved by Investment Committee |

## Distribution Policy

Client distributions are declared on the fifth business day after each quarter
end. Withdrawal requests received before 11:00 Eastern Time are priced at that
day's close; later requests are priced at the next business day's close.
Reinvestment elections must be on file before the declaration date. Distribution
corrections are handled by the Operations desk and reflected in the next cycle.

## Risk Controls

- Single-name concentration above 15 percent of net asset value requires a written
  exception from the Risk Committee before execution.
- Sector exposure above 30 percent requires a documented committee review.
- Names on the restricted list may not be purchased, regardless of target weight.
- Cash buffers below 1 percent of net asset value must be escalated to Treasury.
- Any execution error above 50,000 US dollars is logged as a control incident.
- The register is reconciled to custodian records on the second business day after
  each rebalance.

## Custodian Contacts

| Role | Name | Email |
| --- | --- | --- |
| Primary custodian | Rowan Whitfield | rowan.whitfield@custody.example.com |
| Backup custodian | Priya Raman | priya.raman@custody.example.com |
| Compliance liaison | Martin Osei | martin.osei@compliance.example.com |
| Treasury contact | Helena Brandt | helena.brandt@treasury.example.com |

## Document Control

- Owner: Portfolio Operations
- Review cadence: monthly
- Access: operations, compliance, and risk personnel only
- Retention: seven years
- Backup: nightly snapshot to the operations archive

## Change Log

| Date | Change |
| --- | --- |
| 2026-10-13 | Updated current positions after the October rebalance |
| 2026-08-17 | Added the treasury escalation contact |
| 2026-02-17 | Introduced the quarterly distribution review step |
| 2025-11-10 | Migrated the register to the repository-based workflow |
