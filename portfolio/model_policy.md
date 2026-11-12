# Model Portfolio Policy

## Rebalance Directive — November 2026

| Parameter | Value |
| --- | --- |
| Directive ID | RBL-2026-11 |
| Status | Approved by Investment Committee |
| As-of close date | 2026-11-10 |
| Portfolio net asset value (USD) | 9,600,000 |
| Board lot (shares) | 25 |
| Price convention | Unadjusted daily close, rounded to two decimals |
| Register to refresh | portfolio/positions_register.md |

## Target Allocation

| Ticker | Company | Target weight (%) |
| --- | --- | --- |
| MSFT | Microsoft Corporation | 12.0 |
| JNJ | Johnson & Johnson | 10.0 |
| XOM | Exxon Mobil Corporation | 11.0 |
| KO | The Coca-Cola Company | 9.0 |
| PG | The Procter & Gamble Company | 10.5 |
| CAT | Caterpillar Inc. | 8.0 |
| VZ | Verizon Communications Inc. | 9.5 |
| MRK | Merck & Co., Inc. | 11.0 |
| PEP | PepsiCo, Inc. | 9.0 |
| CVX | Chevron Corporation | 10.0 |

## Calculation Convention

1. The target notional for a line is the portfolio net asset value multiplied by
   the target weight, divided by 100.
2. Target shares are the largest whole multiple of the board lot that does not
   exceed target notional divided by the as-of close. Fractional shares are never
   traded.
3. Trade action is BUY when target shares exceed the shares currently on record,
   SELL when they are below, and HOLD when the two are equal.
4. Reference prices are the unadjusted daily closes for the as-of date, quoted to
   two decimals.

## Governance

Weight changes require Investment Committee approval and are recorded in the
positions register. The policy is frozen once a directive is approved; execution
notes belong in the register and the operations log, not in this file.
