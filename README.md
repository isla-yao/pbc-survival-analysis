# pbc-survival-analysis

Survival analysis of the Mayo Clinic Primary Biliary Cholangitis (PBC) trial using Kaplan-Meier curves and Cox proportional hazards models in R.

## Key findings

- D-penicillamine showed **no survival benefit** over placebo
  (log-rank p = 0.7; adjusted HR 1.07, 95% CI 0.77–1.50).
- **Bilirubin** was the strongest prognostic factor: each doubling was
  associated with a near two-fold increase in hazard (HR 1.95).
- Higher **albumin** was protective (HR 0.33 per 1 g/dL).
- The Cox model showed good discrimination (concordance 0.82), with no
  evidence against the proportional hazards assumption.

## Analysis

- [x] Data preparation (composite endpoint: death or transplant)
- [x] Kaplan-Meier survival curves by treatment group, with log-rank test
- [x] Cox proportional hazards model (treatment, age, sex, bilirubin, albumin)
- [x] Proportional hazards assumption checks
- [ ] Extension: longitudinal biomarker modelling with `pbcseq`

## Files

- `analysis.qmd`: full analysis (Quarto source)
- `analysis.html`: rendered report
- `custom.scss`: custom theme (fonts, colours, layout)
- `index.html`: redirects the site homepage to the report

📄 **[View the full report](https://isla-yao.github.io/pbc-survival-analysis/)**