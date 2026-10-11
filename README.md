# Hi, I'm Toby 👋

Final-year **Economics** student (Computer Science minor) at **UBC**. I build things that
estimate what policies actually did, then simulate what they might do next.

I like questions where the textbook method breaks on real data, and I write down exactly where.

## Featured work

### 📉 [Did BC's short-term rental ban work?](https://github.com/haji5/bc-str-ban-analysis)
End-to-end causal evaluation of Bill 35. 52 Inside Airbnb snapshots (40 recovered from
unlisted archives), a DuckDB/SQL layer, difference-in-differences and event studies with
randomization inference, and an [interactive dashboard](https://haji5.github.io/bc-str-ban-analysis/).
- Listings in covered Victoria-area neighbourhoods fell about 35% versus a 6% rise in never-covered areas
- No detectable rent effect: the plausible size is below the noise in CPI rents
- Includes a corrections log from an independent audit

### 🎮 [Zoned Out: a housing-policy game](https://github.com/haji5/housing-policy-sim) · [play it](https://haji5.github.io/housing-policy-sim/)
An agent-based model calibrated to the estimates above, wrapped in a game where you are
Greater Victoria's housing minister.
- Reproduces the calibration target (-0.399 vs -0.390 log points) and reports where it misses
- Used the simulator to test my own DiD: it overstates the true effect by about 11% when the control group is contaminated
- Deterministic TypeScript core, 300-member parameter ensemble, Playwright and axe accessibility tests

## Toolbox

**Analysis:** Python · pandas · pyfixest · statsmodels · SQL (DuckDB)
**Building:** TypeScript · Preact · D3.js · Canvas · Web Workers · pnpm · GitHub Actions
**Methods:** difference-in-differences · event studies · randomization inference · agent-based modeling · simulated method of moments · ABC calibration
