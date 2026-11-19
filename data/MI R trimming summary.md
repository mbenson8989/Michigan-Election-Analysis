# Michigan Governor 2022 → 2026: does the "Republican-trimming" hypothesis hold?

**2026 results are UNOFFICIAL / uncertified (as of Nov 17, 2026).** In 27 counties, the 2026 county D/R/other votes are NBC News county counts scaled to the SOS statewide remainder (marked * in the chart and CSV). Ottawa uses the county canvass (‡). Muskegon, Ogemaw and Wexford have known data-quality problems (†). Ballot totals are SOS county turnout for all 83 counties.

## Short answer
**No, the data doesn't support it.** Republican raw votes went **up** in 77 of 83 counties and statewide. Republican share of ballots also rose in most counties. Where it fell, the drops cluster in particular regions and track education levels, not voting-equipment vendor. They aren't uniform cuts across very different counties, which is what a trimming method would produce.

## The race
- **2022:** Whitmer (D) vs Dixon (R), plus minor-party candidates.
- **2026:** Benson (D) vs James (R), plus Hudson (Libertarian), Brandenburg (U.S. Taxpayers) and Campbell (Green). Mike Duggan's independent campaign ended May 21, 2026, and he **was not on the November ballot**. There was no major independent soaking up share. The minor-party vote rose from 1.57% to 1.70% of ballots.

## Statewide (sum of county files)
| | 2022 | 2026 | Change |
|---|---|---|---|
| Republican votes | 1,960,635 | 2,093,435 | **+132,800 (+6.8%)** |
| Democratic votes | 2,430,505 | 2,613,240 | +182,735 (+7.5%) |
| Total ballots | 4,500,400 | 4,843,797 | +343,397 (+7.6%) |
| D share of ballots | 54.01% | 53.95% | −0.06 pts |
| R share of ballots | 43.57% | 43.22% | −0.35 pts |
| Third-party share | 1.57% | 1.70% | +0.13 pts |
| Blank/undervote share (ballots with no governor vote) | 0.85% | 1.13% | +0.28 pts |

The statewide shares barely moved. Of the small drop in R share, the minor-party and blank-ballot increases (+0.41 pts combined) account for more than all of it. D share actually fell slightly.

## Each of the nine questions
1. **Did R raw votes fall while D held or grew?** R raw votes fell in only **6 of 83** counties: Dickinson −227, Gogebic −73, Iron −59, Baraga −26, Ontonagon −22, Keweenaw −5. That's 412 votes in total, all in small Upper Peninsula counties. D raw votes fell in **38** counties.
2. **D raw votes:** the median county changed +0.6%, with a range of −10.9% (Sanilac) to +15.2% (Wayne).
3. **Total ballots:** the median county rose +4.4%, with a range of −4.3% (Ontonagon) to +14.7% (Wayne).
4. **Counties where R fell but ballots were flat (±1%) or rose:** 4 counties.
   - Gogebic: R −73; D +162, undervote +54.
   - Iron: R −59; D +112.
   - Baraga: R −26; D +71, third-party +22.
   - Keweenaw: R −5; D +1, third-party +7, undervote +9.

   These four together involve under 200 Republican votes. In each one, total ballots also grew, so the D gains were mostly new ballots rather than votes moved from R.
5. **Does the D gain mirror the R loss?** The county share changes are strongly negatively correlated (r = −0.73; slope −0.75, R² 0.53). That's expected in any two-party race. In the 23 counties where R share fell, the median D gain was only 0.67 of the R loss. The rest went to minor parties and blank ballots, so it isn't one-for-one.
6. **Floor:** Missaukee (2022: D 26.63%, R 70.82%). Its R share *rose* +1.35 pts in 2026.
   - **Largest D share gain:** Berrien, +2.65 (R −2.81). Even there, R raw votes rose (+490).
   - **Largest R share loss:** Ogemaw on paper, at −3.14. But Ogemaw is a data-quality county: D also fell −5.77 and blank ballots jumped +8.67 pts, which points to an incomplete 2026 count. Leaving out the three data-quality counties, the largest R share losses are Berrien (−2.81), Menominee (−2.57), Kent (−2.46), Gogebic (−2.26) and Ottawa (−2.07).
   - **Largest R share gains:** St. Clair +3.96, Otsego +3.30, Gladwin +3.24, Roscommon +3.16, Clare +3.10.
7. **Correlates of R-share change:**
   - **Size:** bigger counties saw smaller R-share gains (slope −0.80 per 10× population, p = 0.012, R² 0.08). That disappears once demographics are added.
   - **Demographics** (Census ACS 2020–2024 5-year):
     - % with a bachelor's degree or more, Spearman −0.42 (p = 0.0001). In the full model, each extra point of bachelor's lowered R share by 0.056 pts (p = 0.027).
     - % white non-Hispanic, +0.37 (p = 0.0006).
     - Median age, +0.36 (p = 0.0009).
     - Median income, −0.25 (p = 0.02).
   - **Region:** strong. Compared with Metro Detroit, R share fell more in the Upper Peninsula (−4.3 pts, p = 0.0006) and West Michigan (−2.6, p = 0.0002). Mean R-share change by region: Northern Lower Peninsula +1.61, Metro Detroit +1.08, Mid-Michigan +0.90, West Michigan −0.23, Upper Peninsula −0.08.
   - **Vendor (2026):** no effect. With controls, the joint F-test gives p = 0.21 for R share and p = 0.82 for R raw % change. ES&S counties come out +0.98 pts *more* Republican (p = 0.09, only 7 counties). Raw Kruskal-Wallis: p = 0.47. Mean R-share change: Dominion +0.80, ES&S +1.00, Hart +0.34.
   - **NBC-scaled vs SOS counties:** the NBC dummy isn't significant (p = 0.72).
   - The full model explains about half the variation (R² 0.48; adjusted 0.38).
8. **Uniformity:** R-share change has a median of +1.01 pts, SD 1.60 and range −3.14 to +3.96. It fell in 23 of 83 counties and rose in 60. R raw % change has a median of +5.8%, SD 3.4 and range −3.1% to +14.1%. That's the opposite of a uniform cut. The changes are mixed in direction, cluster by region, and follow education levels.
9. **The "pull D back toward Harris 2024" idea:** the 2026 D share of ballots was **higher than Harris's 2024 share in all 83 counties** (median +4.65 pts; statewide 53.95% vs 47.95%). It landed close to Whitmer's 2022 level (54.01%). Nothing suggests a target near Harris's number.

## What these numbers look like instead
- **Normal midterm behavior:** both parties gained raw votes as turnout rose 7.6%. Shares stayed close to 2022.
- **Candidate effects:** this was an open seat, Benson vs James instead of Whitmer vs Dixon. The race shifted toward the Democrats in college-educated and West Michigan areas (Kent, Ottawa, Berrien), likely helped by James's appeal in some areas and not others. It shifted toward the Republicans in older, whiter, less-educated Northern Lower Peninsula counties and in St. Clair.
- **Who turned out:** Wayne's ballots rose +14.7% and its D votes +15.2%, but its R votes also rose (+7.4%). That fits higher Detroit-area turnout, not missing Republican votes.
- **Upper Peninsula population decline:** the six counties where R raw votes fell are all small and shrinking UP counties. In Dickinson and Ontonagon, total ballots fell too.

## Caveats
- All 2026 numbers are unofficial. For the 27 NBC-scaled counties, the county-level D/R/other split is an estimate. Wayne and Oakland are among them.
- In 2026, Muskegon shows more governor votes than ballots, Ogemaw's count looks incomplete, and Wexford's ballots exceed its governor votes in both years. Their changes aren't reliable.
- Like Morissa's equation, this test can't detect fraud. It only shows whether raw vote patterns look like a uniform trim, and they don't.

Files: `MI gov R trimming test.csv` (sorted by population), `MI gov R vs D raw vote change by population.png`, `build_rtrim.py`; statistics in `/workspace/michigan/output/r_trimming_stats.json`; ACS inputs in `/workspace/michigan/raw/acs/`.
