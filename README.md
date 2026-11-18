# pbc-survival-analysis
Kaplan-Meier and Cox regression analysis of primary biliary cholangitis (PBC) survival data in R, with a reproducible Quarto report.
Survival analysis of the Mayo Clinic Primary Biliary Cholangitis (PBC) trial using Kaplan-Meier curves and Cox proportional hazards models in R.

## Status

🚧 Work in progress

## Planned analysis

- [ ] Data preparation (composite endpoint: death or transplant)
- [ ] Kaplan-Meier survival curves by treatment group, with log-rank test
- [ ] Cox proportional hazards model (treatment, age, sex, bilirubin, albumin)
- [ ] Proportional hazards assumption checks
- [ ] Extension: longitudinal biomarker modelling with `pbcseq`

## Data

The `pbc` and `pbcseq` datasets are publicly available in the R
[`survival`](https://cran.r-project.org/package=survival) package.