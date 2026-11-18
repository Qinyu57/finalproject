# BST260 Final Project

**Author:** Qinyu Xu (GitHub: [Qinyu57](https://github.com/Qinyu57))
**Course:** BST260, Fall 2026
**Site:** https://Qinyu57.github.io/finalproject

This repository contains my final project for BST260. It has two vignettes, each built around a public CDC dataset.

## Vignette 1: CDC waterborne disease outbreaks (`waterborne`)

- **Data:** 66,713 CDC enteric disease outbreak records from 1971 onward, restricted to drinking-water outbreaks (N = 1,175 in the main analysis).
- **Methods:** Data cleaning, descriptive statistics, plots, and a regression of illnesses on water type, adjusted for year, season and US Census region (log scale or negative binomial).

## Vignette 2: CDC firearm mortality (`cdcfiremort`)

- **Data:** State-level death rates for the 50 states and DC in 2005 and 2014–2024 (612 state-year rows).
- **Methods:** Descriptive statistics, a regression of log death rate on region and year with state-clustered standard errors. Sensitivity analyses use population weighting and drop 2005.

