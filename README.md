# organ-donation-policy
Causal inference analysis of U.S. living organ donor compensation policies on organ donation rates

## Overview

This repository contains code for my master's research examining the effects of U.S. legislation compensating living organ donors, including paid leave and tax credits, on organ donation outcomes.

## Research Question

How do state policies that compensate living organ donors affect living organ donation rates?

## Methods

- Fixed Effects/Panel Data
- Difference-in-Differences
- LASSO and Ridge
- Trees and Random Forests
- Propensity Score Matching (PSM)
- Inverse Probability Weighting (IPW)
- Doubly Robust Estimation
- Double Machine Learning (Linear and Causal Forest)
- Meta Learners (S-, T-, X- Learners)
- Callaway & Sant'Anna Event Study

## Data

This project uses publicly available data from

- OPTN/UNOS
- FRED
- U.S. Census Bureau

The state-level dates for living donor compensation legislation were compiled using:

> Lacetera, N., Macis, M., Stith, S. S., & Tonin, M. (2014). *Removing financial barriers to organ and bone marrow donation: The effect of leave and tax legislation in the U.S.*

Restricted datasets used in later extensions are **not included** in this repository.

## Repository Structure

```
notebooks/      Analysis notebooks
src/            Python source code
figures/        Figures and plots
```

## Author

Christine Reeve  
M.A. Economics, University of Toronto
