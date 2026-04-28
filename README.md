# Hermès — Public Audit Trail

Small / mid cap USA capitulation reversal · forward paper test from **2026-04-26** · review **2026-07-19** (12 weeks min).

**0 client capital deployed.** All snapshots below are forward paper test on real-time market data with frozen V25 ULTIMATE++++ parameters.

## What you find here

| File | Purpose |
|---|---|
| `<date>_integrity.json` | SHA256 hashes of all frozen strategy files. Proves the engine hasn't been changed. |
| `<date>_drift_report.json` | Aggregate performance (NAV, return, drift vs backtest expected). No tickers. |
| `<date>_paper_state.json` | NAV + closed trade history (ticker / dates / prices / P&L final / exit reason). Open positions: count only. |

## What is NEVER published here

- V25 score values, tier thresholds, star ratings, verdict labels
- Stop %, take profit %, max hold, trailing trigger / giveback %, profit lock %
- Slippage curve parameters, ADV tier mappings
- Open position tickers (Pro+ subscribers only on https://thefrenchinvestor.com)

## Reference claims (source: ~/stoika/shared/claims_sheet.md)

- Backtest 19.4y univers v5 PIT (~1488 tickers) : CAGR +79.78% · Sharpe 2.48 · MaxDD -18.86% · WR 57.4%
- Live expected (DSR + Bonferroni K=25 + régime drift discount) : CAGR **65-67%** · Sharpe **2.05-2.07**
- DSR (Bailey-de Prado 2014) : 1.0000
- OOS 2024-2026 ratio Sharpe / Full = 1.00 (zero overfit signal)
- Probability(CAGR ≥ 65%) = 93.5% via block bootstrap

## Disclaimer

Educational analytics tool. Not investment advice. Past performance does not guarantee future results. Forward paper test means no client capital is deployed; the strategy tracks real market data with frozen parameters for transparency. Forward paper test on small/mid cap stocks is more sensitive to slippage and execution conditions than large-cap strategies — live results may diverge more than usual from backtest.

---

## Snapshots index

| Date | NAV | Days live | Open | Closed | Frozen commit |
|---|---|---|---|---|---|
| 2026-04-26 | 0.9875 | 1 | 2 | 0 | `3d10223f5d4e` |
| 2026-04-28 | 0.1692 | 2 | 5 | 0 | `65a54a22447c` |
