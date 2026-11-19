# Michigan Election Analysis

County-level analysis of Michigan governor 2022 vs 2026 (and president 2020/2024) for all 83 counties.

**Important caveats**
- Michigan has **no party registration**. The "Democratic registration share" is a stand-in: the **August 2024 Democratic primary share** per county.
- **All 2026 numbers are unofficial.** 27 counties (including Wayne, Oakland, Washtenaw) use **NBC News county estimates** scaled to the official statewide total. Ottawa uses its county canvass. Muskegon, Ogemaw and Wexford have data-quality flags.
- Residuals and surplus measure deviation from a model; they are not by themselves evidence of fraud.

See the [wiki](https://github.com/mbenson8989/Michigan-Election-Analysis/wiki) for the full write-up.

- `charts/` — chart PNGs
- `data/` — county tables (CSV) and summaries, including the 83-county data PDF:
  [Michigan_83_County_Democratic_Registration_and_Vote_Change.pdf](data/Michigan_83_County_Democratic_Registration_and_Vote_Change.pdf)
  and the matching [CSV](data/Michigan_83_County_Democratic_Registration_and_Vote_Change.csv)
