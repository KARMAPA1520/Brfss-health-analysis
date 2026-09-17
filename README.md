# Health, Behavior and Wellbeing — BRFSS Analysis

![Python](https://img.shields.io/badge/Python-3.12-blue)
![pandas](https://img.shields.io/badge/pandas-2.x-150458)
![License](https://img.shields.io/badge/data-ODbL-green)

**How do obesity, physical activity and nutrition vary across U.S. states —
and what explains the differences?**

An end-to-end analysis of CDC BRFSS data, from exploration to a
deployed prediction model.

---

## Key findings
> _Coming in Phase 1._

<!-- Once you have the map, put it here:
![Obesity by state](reports/figures/obesity_map.png)
-->

## Project status
| Phase | Focus | Status |
|-------|-------|--------|
| 1 | Exploration | 🔄 In progress |
| 2 | Inference | ⬜ Not started |
| 3 | Prediction | ⬜ Not started |
| 4 | Causality and profiles | ⬜ Not started |
| 5 | Production | ⬜ Not started |

## Repository structure


## Data
**Source:** CDC — Nutrition, Physical Activity, and Obesity ([BRFSS][src])
**License:** Open Database License (ODbL) · **Accessed:** September 2026

BRFSS is the CDC's national telephone health survey, running since 1984
and covering all 50 states, DC and participating territories. With over
400,000 adult interviews a year, it is the largest ongoing telephone
health survey in the world. This project uses the **aggregated public
release**: prevalence estimates by state, year and demographic group,
rather than individual responses.

[src]: https://data.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7

## Getting started
```bash
git clone https://github.com/<user>/brfss-health-analysis.git
cd brfss-health-analysis
python -m venv .venv
.venv\Scripts\activate      # Windows
pip install -r requirements.txt
```
The data downloads automatically when you run the first notebook.

## Tech stack
`pandas` · `matplotlib` · `seaborn` · `plotly` · `Jupyter`

## Author
**Juan David Castillo** — Data Analyst moving into Data Science
[LinkedIn](your-url) · [GitHub](your-url)