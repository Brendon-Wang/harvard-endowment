# FINM Portfolio & Risk Management — Harvard's Endowment (Group Case)

Case: https://markhendricks.github.io/finm-portfolio/case_studies/Harvard%27s%20Endowment.html

## Structure
```
data/multi_asset_etf_data.xlsx   # course data (monthly ETF returns)
harvard_endowment.ipynb          # single group write-up (submission file)
requirements.txt
```

## Progress
| Section | Status | Owner |
|---|---|---|
| 1. Reading: HMC's Approach | not required | – |
| 2.1 Summary Statistics | ✅ done | |
| 2.2 Descriptive Analysis | ✅ done | |
| 2.3 The MV Frontier | ✅ done | |
| 2.4 TIPS | ✅ done | |
| 3. Allocations (EW / RP / MV) | ✅ done | |
| 4–7. EXTRA | not required | – |

## Conventions (please keep consistent)
- Data is loaded once in the *Setup* cell into `rets` (= excess returns, SHV subtracted, **QAI dropped**, 10 assets).
- `FREQ = 12`; use `performance_summary(df)` to report annualized mean / vol / Sharpe.
- Annualize **statistics only** (mean ×12, vol ×√12), never the raw time series.
- Add your section below the previous one; re-run *Kernel → Restart & Run All* before committing.

## Setup
```bash
pip install -r requirements.txt
jupyter notebook harvard_endowment.ipynb
```
