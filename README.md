# Customer Shopping Behavior Analysis

End-to-end analysis of a retail customer dataset (3,900 transactions, 18 variables): data preparation, exploratory analysis, statistical testing, subscription prediction and a Tableau dashboard, with one combined report.

The project was built in two phases on the same dataset:

| | Phase 1 — Foundation | Phase 2 — Depth |
|---|---|---|
| **Analytics** | Wrangling, feature engineering, descriptive EDA (`notebooks/01`) | Quality evaluation, advanced EDA, statistical tests, classification models (`notebooks/02`) |
| **Visualization** | Exploratory Tableau views (`dashboards/phase1_exploratory_views.twbx`) | 4-page executive dashboard (`dashboards/phase2_executive_dashboard.twbx`) |

## Repository structure

```
data/raw/         shopping_behavior_raw.csv                 original data
data/processed/   shopping_behavior_cleaned.csv             after Phase 1 wrangling
                  shopping_behavior_for_modeling.csv        + Loyalty Level, Customer Segment (Phase 2)
notebooks/        01_phase1_data_preparation_and_eda
                  02_phase2_analysis_and_modeling.ipynb
dashboards/       Tableau workbooks (.twbx, open with Tableau Desktop / Public)
reports/          project_report.md + figures/
```


## Report

The Analytics and Visualization write-ups merged into one lifecycle: context → data understanding → wrangling → EDA (Phase 1) → quality evaluation → advanced analysis → methods & metrics → dashboard design → recommendations (Phase 2). The text is in Bahasa Indonesia with English technical terms.

Published dashboard: Tableau Public — *Customer Shopping Behavior Analysis Dashboard* (link in report)
