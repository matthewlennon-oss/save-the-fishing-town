# Save the Fishing Town

A two-round sustainability decision game for **Year 9 Science**, designed as a companion to **Power the Town**. Students adjust three sliders, run a simplified five-year simulation, reconsider their choices, and compare the outcomes of both strategies.

## Play

Open `index.html` directly in any modern browser. No installation, internet connection, external libraries, student login or data collection is needed.

To print the companion questions, open `student-worksheet.html` or click the worksheet link at the bottom of the game. You can also save it as PDF using the browser's Print option.

## Publish with GitHub Pages

1. Create a **public** GitHub repository, for example `save-the-fishing-town`.
2. Upload **`index.html`, `student-worksheet.html`, `README.md` and `.nojekyll`** to the **root** of your repository.
3. Open **Settings → Pages** on GitHub.
4. Under *Build and deployment*, select **Deploy from a branch** and choose your default branch (usually `main`) and **`/(root)`**.
5. GitHub will show the address after deployment, typically `https://YOUR-USERNAME.github.io/save-the-fishing-town/`.
6. Share that link through Google Classroom.

*Creating a repository does not automatically turn on GitHub Pages. There is no special build step.*

## The three decisions

| Pillar | Lever | Meaning |
|---|---|---|
| Environmental | Marine protection (0–100%) | Percentage of fishing waters closed to commercial fishing |
| Social | Community support (0–100%) | Strength of job retraining, transition aid and economic diversification |
| Economic | Fishing intensity (0–100%) | Fishing effort in waters still open to commercial fishing |

The sliders are **not** shares of one common budget. At 100% marine protection, there is no fishing, regardless of the fishing intensity setting.

## Win conditions

The fictional five-year projection aims to meet all four targets:

| Indicator | Target |
|---|---:|
| Fish population index | 65/100 or greater |
| Local livelihoods index | 72/100 or greater |
| Town economy index | 70/100 or greater |
| Future fishing catch index | 53/100 or greater |

Students play **exactly two rounds** before the comparison report appears. In Round 2 they can change one or several levers. The report includes the four scores, a fish-population line chart for both rounds, differences in scores, a table of settings, feedback on each pillar, reflection questions and a Print / Save as PDF button.

**Important:** Both rounds are *alternative* five-year projections that restart from the exact same starting conditions (fish stock index of 42/100). They do **not** represent ten successive years or an actual marine ecosystem.

## Teacher guidance and discussion

- High permitted fishing can protect some current employment but undermine future fish populations and catches.
- Marine protection can support recovery but reduces access to fishing waters, affecting fishing employment and income.
- Retraining support can help local families and support alternative work, but costs resources in the short term.
- A fully closed fishery may restore the stock but is not automatically a thriving *fishing* town.
- Good sustainability choices can be **unequal** settings across the three pillars, because each lever measures a different thing.

Suggested prompt after Round 1: **“Which result would you improve first, and what might that choice cost the town?”**

Suggested final prompt: **“Which plan would you recommend, based on two pieces of evidence and at least one trade-off?”**

### Example classroom choices (not the only valid solutions)

- **Round 1 starting settings:** 35% marine protection, 40% community support, 65% fishing intensity — fish stock falls short of the target.
- **Possible improved plan:** 60% marine protection, 55% support, 45% fishing intensity — meets the targets under the current teaching model.

Students may find other successful combinations. The final scores are useful for discussion, but do not imply objective real-world policy recommendations.

## Model transparency

The game uses a small, deterministic JavaScript teaching model and entirely invented indices. It simulates a stock trajectory over five fictional years starting at 42/100; fishing effort applied only to open waters reduces recovery, and protected waters help the stock recover. Employment, income and future catch respond to fish stocks, allowed fishing activity and support for workers. The mathematical coefficients and thresholds are illustrative rather than based on field data or validated Australian fisheries models. They should **not** be presented as actual predictions or species-specific fisheries management advice.

The code is contained in `index.html` and can be modified without setting up development tools.
