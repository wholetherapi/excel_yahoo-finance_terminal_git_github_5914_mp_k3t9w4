# Alder Lane Capital — Model Portfolio Operations

This repository is the system of record for the Alder Lane flagship model
portfolio.

## Layout

- `portfolio/model_policy.md` — the approved rebalance directive and target allocation
- `portfolio/positions_register.md` — the positions register consumed by the risk
  and client-reporting systems

## Conventions

- All portfolio arithmetic is performed on unadjusted, two-decimal US-dollar prices.
- The positions register is refreshed in place after each approved rebalance.
- Directive changes and register refreshes are committed to the repository's
  default branch (`master`).
